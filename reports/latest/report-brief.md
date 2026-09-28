# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 6 of 2898 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#36381828457](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/36381828457) |
| Commit | `1504d6ebbd` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1790573219, 1790573220, 1790573221, 1790573222, 1790573223, 1790573224, 1790573226, 1790573227, 1790573228, 1790573231, 1790573232, 1790573240 |
| Generated | 2026-09-28 05:41 UTC |

## Suites

| Suite | Shard | PASS | FAIL | TIMEOUT | ERROR | MISSING | Total | Status |
|---|---|---|---|---|---|---|---|---|
| block-BACV2 | none | 84 | 0 | 0+0 | 0 | 0 | 84 | PASS |
| block-BPredUnitV2 | none | 294 | 0 | 0+0 | 0 | 0 | 294 | PASS |
| block-CSRFile | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Commit | none | 70 | 0 | 0+0 | 0 | 0 | 70 | PASS |
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
| block-LQCore | none | 121 | 0 | 0+0 | 0 | 0 | 121 | PASS |
| block-LSQParent | none | 265 | 0 | 0+0 | 0 | 0 | 265 | PASS |
| block-O3Control | none | 45 | 0 | 0+0 | 0 | 0 | 45 | PASS |
| block-PhysRegFile | none | 27 | 0 | 0+0 | 0 | 0 | 27 | PASS |
| block-ROB | none | 59 | 0 | 0+0 | 0 | 0 | 59 | PASS |
| block-ReadOperand | none | 48 | 0 | 0+0 | 0 | 0 | 48 | PASS |
| block-ReadOperandInt | none | 14 | 0 | 0+0 | 0 | 0 | 14 | PASS |
| block-ReadOperandMem | none | 6 | 0 | 0+0 | 0 | 0 | 6 | PASS |
| block-Rename | none | 91 | 0 | 0+0 | 0 | 0 | 91 | PASS |
| block-SQStore | none | 117 | 0 | 0+0 | 0 | 0 | 117 | PASS |
| block-Scoreboard | none | 54 | 0 | 0+0 | 0 | 0 | 54 | PASS |
| block-StorageManager | none | 28 | 0 | 0+0 | 0 | 0 | 28 | PASS |
| block-StoreSet | none | 22 | 0 | 0+0 | 0 | 0 | 22 | PASS |
| block-Testbench | none | 114 | 2 | 0+0 | 0 | 0 | 116 | FAIL |
| block-TlbiController | none | 11 | 0 | 0+0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | 89 | 0 | 0+0 | 0 | 0 | 89 | PASS |
| p- | none | 200 | 0 | 0+0 | 4 | 0 | 204 | FAIL |
| v- | 1/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 10/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 11/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 12/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 13/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 14/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 15/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 16/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 17/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 18/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 2/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 3/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 4/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 5/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 6/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 8/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| **all** |  | 2892 | 2 | 0+0 | 4 | 0 | 2898 | FAIL |

## Failures

| Test | Suite | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|
| `test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-beq:branch equal]` | block-Testbench | FAIL | - | - | 2s | - | AssertionError: CommitCL ADR-0048 §5: a resolve named a ROB slot that is not live (tid=0 rob_idx=122). WriteBack filters... |
| `test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bltu:branch less than unsigned]` | block-Testbench | FAIL | - | - | 2s | - | AssertionError: CommitCL ADR-0048 §5: a resolve named a ROB slot that is not live (tid=0 rob_idx=126). WriteBack filters... |
| `rv64mi-p-instret_overflow` | p- | ERROR | - | - | 10s | 619244385 | exit=None cycles=-1 status=ERROR |
| `rv64mi-p-ma_fetch` | p- | ERROR | - | - | 13s | 828114212 | exit=None cycles=-1 status=ERROR |
| `rv64mi-p-pmpaddr` | p- | ERROR | - | - | 10s | 86969664 | exit=None cycles=-1 status=ERROR |
| `rv64mi-p-zicntr` | p- | ERROR | - | - | 11s | 800943242 | exit=None cycles=-1 status=ERROR |

_Full 2898-test table: see the `pyo3-ci-report.md` asset._
