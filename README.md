# pyo3-ci

Runs the [pyo3 CL-model](https://github.com/rain91508-cmd/gem5) CI suites
against a chosen ref of the (private) source repo `rain91508-cmd/gem5`, and
publishes the aggregated report to **this repo's** rolling `pyo3-ci-report`
pre-release.

Because this repo is **public**, the report is readable by anyone, without a
GitHub account or token:

- **Stable release link:** https://github.com/rain91508-cmd/pyo3-ci/releases/tag/pyo3-ci-report

## Triggering a run

This is a `workflow_dispatch` workflow — run it from the **Actions** tab
("CI Tests" → "Run workflow"), or:

```bash
gh workflow run ci-tests.yaml --repo rain91508-cmd/pyo3-ci \
    -f gem5_ref=pycpu
```

`gem5_ref` selects the branch / tag / commit SHA in `rain91508-cmd/gem5` to
test (default: `pycpu`, gem5's default branch). Each run:

1. Shallow-clones the private `rain91508-cmd/gem5` at `gem5_ref` over https
   using the repo secret `KEY_PULL_REPO` (a PAT with read access to that repo),
   and fetches the `riscv-tests` + `pymtl3_submodule` submodules.
2. Builds the riscv-tests ELFs (downloads a prebuilt riscv-gnu-toolchain).
3. Runs the `-p-` (machine mode), `-v-` (Sv39, 4 shards), and block-test
   suites — the same suites the gem5 repo's own CI runs.
4. Aggregates every result and publishes `pyo3-ci-report.md`,
   `pyo3-ci-results.tsv`, and `pyo3-perf-counters.tsv` (one counter per column)
   to the `pyo3-ci-report` pre-release here.

## Report

The report header names the **gem5 commit** that was tested; the release tag
and run link live on this repo. The four release assets are:

- `report-brief.md` — summary + failures table (the release body)
- `pyo3-ci-report.md` — full report incl. the complete per-test table
- `pyo3-ci-results.tsv` — every test result (8 fixed columns)
- `pyo3-perf-counters.tsv` — the O3 core perf counters, one counter per column

## Setup notes

- The shared checkout+setup logic is the composite action
  `.github/actions/setup-pyo3` in this repo, referenced from the workflow as
  `rain91508-cmd/pyo3-ci/.github/actions/setup-pyo3@main` (a local `./...`
  reference would be looked up in the gem5 clone that occupies the workspace
  root, not this repo).
- Secret: `KEY_PULL_REPO` (repo-level) — a PAT with read access to
  `rain91508-cmd/gem5` (and its private `pymtl3_submodule` if it ever becomes
  private again). Configure it in **Settings → Secrets and variables →
  Actions**.
