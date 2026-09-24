# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 12 of 2813 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#35948494932](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/35948494932) |
| Commit | `7313e2b56c` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1790217944, 1790217945, 1790217946, 1790217947, 1790217948, 1790217949, 1790217950, 1790217951, 1790217952, 1790217953, 1790217954, 1790217956, 1790217978 |
| Generated | 2026-09-24 02:59 UTC |

## Suites

| Suite | Shard | PASS | FAIL | TIMEOUT | ERROR | MISSING | Total | Status |
|---|---|---|---|---|---|---|---|---|
| block-BACV2 | none | 84 | 0 | 0+0 | 0 | 0 | 84 | PASS |
| block-BPredUnitV2 | none | 227 | 0 | 0+0 | 0 | 0 | 227 | PASS |
| block-CSRFile | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Commit | none | 65 | 0 | 0+0 | 0 | 0 | 65 | PASS |
| block-DTLBProbe | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Decode | none | 115 | 0 | 0+0 | 0 | 0 | 115 | PASS |
| block-Dispatch | none | 47 | 0 | 0+0 | 0 | 0 | 47 | PASS |
| block-FTQ | none | 168 | 0 | 0+0 | 0 | 0 | 168 | PASS |
| block-FUPool | none | 51 | 0 | 0+0 | 0 | 0 | 51 | PASS |
| block-Fetch | none | 208 | 0 | 0+0 | 0 | 0 | 208 | PASS |
| block-FrontEnd | none | 16 | 0 | 0+0 | 0 | 0 | 16 | PASS |
| block-ICache | none | 53 | 0 | 0+0 | 0 | 0 | 53 | PASS |
| block-IEW | none | 112 | 0 | 0+0 | 0 | 0 | 112 | PASS |
| block-IQ | none | 132 | 0 | 0+0 | 0 | 0 | 132 | PASS |
| block-LQCore | none | 118 | 0 | 0+0 | 0 | 0 | 118 | PASS |
| block-LSQParent | none | 265 | 0 | 0+0 | 0 | 0 | 265 | PASS |
| block-O3Control | none | 45 | 0 | 0+0 | 0 | 0 | 45 | PASS |
| block-PhysRegFile | none | 27 | 0 | 0+0 | 0 | 0 | 27 | PASS |
| block-ROB | none | 59 | 0 | 0+0 | 0 | 0 | 59 | PASS |
| block-ReadOperand | none | 48 | 0 | 0+0 | 0 | 0 | 48 | PASS |
| block-ReadOperandInt | none | 14 | 0 | 0+0 | 0 | 0 | 14 | PASS |
| block-ReadOperandMem | none | 6 | 0 | 0+0 | 0 | 0 | 6 | PASS |
| block-Rename | none | 84 | 0 | 0+0 | 0 | 0 | 84 | PASS |
| block-SQStore | none | 117 | 0 | 0+0 | 0 | 0 | 117 | PASS |
| block-Scoreboard | none | 54 | 0 | 0+0 | 0 | 0 | 54 | PASS |
| block-StorageManager | none | 28 | 0 | 0+0 | 0 | 0 | 28 | PASS |
| block-StoreSet | none | 19 | 0 | 0+0 | 0 | 0 | 19 | PASS |
| block-Testbench | none | 111 | 5 | 0+0 | 0 | 0 | 116 | FAIL |
| block-TlbiController | none | 11 | 0 | 0+0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | 89 | 0 | 0+0 | 0 | 0 | 89 | PASS |
| p- | none | 202 | 0 | 1+0 | 1 | 0 | 204 | FAIL |
| v- | 1/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 10/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 11/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 12/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 13/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 14/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 15/18 | 8 | 0 | 1+0 | 0 | 0 | 9 | FAIL |
| v- | 16/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 17/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 18/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 2/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 3/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 4/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 5/18 | 9 | 1 | 0+0 | 0 | 0 | 10 | FAIL |
| v- | 6/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | 8 | 2 | 0+0 | 0 | 0 | 10 | FAIL |
| v- | 8/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | 9 | 1 | 0+0 | 0 | 0 | 10 | FAIL |
| **all** |  | 2801 | 9 | 2+0 | 1 | 0 | 2813 | FAIL |

## Failures

| Test | Suite | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|
| `test_o3_core_v2.TestElfOnV2Core::test_rv64ui_p_add_passes_on_v2` | block-Testbench | FAIL | - | - | 8s | - | [XPASS(strict)] L9b ACCEPTANCE SCAFFOLD — the v2 core schedules now (F-41 fixed: `FrontendV2` no longer carries the `M(d... |
| `test_o3_core_v2.TestElfOnV2Core::test_v2_core_commits_instructions_and_retires_stores` | block-Testbench | FAIL | - | - | 8s | - | [XPASS(strict)] L9b ACCEPTANCE SCAFFOLD — the v2 core schedules now (F-41 fixed: `FrontendV2` no longer carries the `M(d... |
| `test_o3_core_v2.TestNackChainOrdering::test_elf_reaches_exit_on_every_schedule_seed` | block-Testbench | FAIL | - | - | 48s | - | [XPASS(strict)] L9b ACCEPTANCE SCAFFOLD — the v2 core schedules now (F-41 fixed: `FrontendV2` no longer carries the `M(d... |
| `test_o3_core_v2.TestNackChainOrdering::test_no_seed_stalls_the_frontend` | block-Testbench | FAIL | - | - | 47s | - | [XPASS(strict)] L9b ACCEPTANCE SCAFFOLD — the v2 core schedules now (F-41 fixed: `FrontendV2` no longer carries the `M(d... |
| `test_o3_core_v2.TestNackChainOrdering::test_the_sweep_actually_executed_the_frontend` | block-Testbench | FAIL | - | - | 9s | - | [XPASS(strict)] L9b ACCEPTANCE SCAFFOLD — the v2 core schedules now (F-41 fixed: `FrontendV2` no longer carries the `M(d... |
| `rv64ua-p-lrsc` | p- | TIMEOUT | - | - | 304s | 936692101 | - |
| `rv64uziccid-p-ziccid` | p- | ERROR | - | - | 19s | 493934621 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-lrsc` | v- | TIMEOUT | - | - | 724s | 434500265 | - |
| `rv64ui-v-and` | v- | FAIL | 45 | 15586 | 101s | 959251535 | exit=45 cycles=15586 status=FAIL |
| `rv64uzba-v-sh1add_uw` | v- | FAIL | 69 | 15521 | 75s | 945168883 | exit=69 cycles=15521 status=FAIL |
| `rv64uzba-v-sh2add_uw` | v- | FAIL | 69 | 15521 | 96s | 683713704 | exit=69 cycles=15521 status=FAIL |
| `rv64uzba-v-sh3add_uw` | v- | FAIL | 69 | 15521 | 50s | 901077912 | exit=69 cycles=15521 status=FAIL |

_Full 2813-test table: see the `pyo3-ci-report.md` asset._
