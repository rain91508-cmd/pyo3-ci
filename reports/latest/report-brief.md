# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 8 of 2664 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#33953486091](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/33953486091) |
| Commit | `3fa0dc1001` (main) |
| Triggered by | rain91508-cmd |
| Base seed | 1788594528, 1788594529, 1788594530, 1788594531, 1788594532, 1788594533, 1788594535 |
| Generated | 2026-09-05 08:11 UTC |

## Suites

| Suite | Shard | PASS | FAIL | TIMEOUT | ERROR | MISSING | Total | Status |
|---|---|---|---|---|---|---|---|---|
| block-BAC | none | 96 | 0 | 0+0 | 0 | 0 | 96 | PASS |
| block-BPredUnit | none | 96 | 0 | 0+0 | 0 | 0 | 96 | PASS |
| block-CSRFile | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Commit | none | 65 | 0 | 0+0 | 0 | 0 | 65 | PASS |
| block-DTLBProbe | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Decode | none | 105 | 0 | 0+0 | 0 | 0 | 105 | PASS |
| block-Dispatch | none | 47 | 0 | 0+0 | 0 | 0 | 47 | PASS |
| block-FTQ | none | 130 | 0 | 0+0 | 0 | 0 | 130 | PASS |
| block-FUPool | none | 51 | 0 | 0+0 | 0 | 0 | 51 | PASS |
| block-Fetch | none | 186 | 0 | 0+0 | 0 | 0 | 186 | PASS |
| block-FrontEnd | none | 72 | 0 | 0+0 | 0 | 0 | 72 | PASS |
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
| block-Testbench | none | 100 | 0 | 0+0 | 0 | 0 | 100 | PASS |
| block-TlbiController | none | 11 | 0 | 0+0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | 89 | 0 | 0+0 | 0 | 0 | 89 | PASS |
| p- | none | 204 | 0 | 0+0 | 0 | 0 | 204 | PASS |
| v- | 1/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 10/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 11/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 12/18 | 8 | 0 | 1+0 | 0 | 0 | 9 | FAIL |
| v- | 13/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 14/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 15/18 | 8 | 0 | 1+0 | 0 | 0 | 9 | FAIL |
| v- | 16/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 17/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 18/18 | 8 | 0 | 1+0 | 0 | 0 | 9 | FAIL |
| v- | 2/18 | 9 | 0 | 1+0 | 0 | 0 | 10 | FAIL |
| v- | 3/18 | 8 | 0 | 2+0 | 0 | 0 | 10 | FAIL |
| v- | 4/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 5/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 6/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | 9 | 0 | 1+0 | 0 | 0 | 10 | FAIL |
| v- | 8/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | 9 | 0 | 1+0 | 0 | 0 | 10 | FAIL |
| **all** |  | 2656 | 0 | 8+0 | 0 | 0 | 2664 | FAIL |

## Failures

| Test | Suite | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|
| `rv64ua-v-lrsc` | v- | TIMEOUT | - | - | 868s | 15641384 | - |
| `rv64ud-v-move` | v- | TIMEOUT | - | - | 1078s | 164361643 | - |
| `rv64ui-v-ld` | v- | TIMEOUT | - | - | 1143s | 787313928 | - |
| `rv64ui-v-lw` | v- | TIMEOUT | - | - | 1002s | 210202173 | - |
| `rv64ui-v-sllw` | v- | TIMEOUT | - | - | 1094s | 52466197 | - |
| `rv64ui-v-srl` | v- | TIMEOUT | - | - | 1106s | 98616063 | - |
| `rv64uzbkb-v-pack` | v- | TIMEOUT | - | - | 926s | 805714513 | - |
| `rv64uzbs-v-binv` | v- | TIMEOUT | - | - | 841s | 502858163 | - |

_Full 2664-test table: see the `pyo3-ci-report.md` asset._
