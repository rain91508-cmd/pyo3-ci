# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 3 of 2672 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#34919755955](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/34919755955) |
| Commit | `6d98dbae71` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1789437976, 1789437977, 1789437978, 1789437979, 1789437980, 1789437981, 1789437985 |
| Generated | 2026-09-15 02:22 UTC |

## Suites

| Suite | Shard | PASS | FAIL | TIMEOUT | ERROR | MISSING | Total | Status |
|---|---|---|---|---|---|---|---|---|
| block-BAC | none | 96 | 0 | 0+0 | 0 | 0 | 96 | PASS |
| block-BPredUnit | none | 94 | 2 | 0+0 | 0 | 0 | 96 | FAIL |
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
| block-Testbench | none | 108 | 0 | 0+0 | 0 | 0 | 108 | PASS |
| block-TlbiController | none | 11 | 0 | 0+0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | 89 | 0 | 0+0 | 0 | 0 | 89 | PASS |
| p- | none | 204 | 0 | 0+0 | 0 | 0 | 204 | PASS |
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
| v- | 3/18 | 9 | 0 | 1+0 | 0 | 0 | 10 | FAIL |
| v- | 4/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 5/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 6/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 8/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| **all** |  | 2669 | 2 | 1+0 | 0 | 0 | 2672 | FAIL |

## Failures

| Test | Suite | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|
| `test_bpu_update_train_cl.TestBPUTrainPipeline::test_combined_training_pipeline` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: cycle 12: should be not-taken assert True is False  +  where True = BPUPredictResp(bpu_predict_resp_vali... |
| `test_bpu_update_train_cl.TestBPUTrainPipeline::test_combined_training_pipeline_commit_mode` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: cycle 2: should be not-taken assert True is False  +  where True = BPUPredictResp(bpu_predict_resp_valid... |
| `rv64ui-v-lb` | v- | TIMEOUT | - | - | 633s | 832989866 | - |

_Full 2672-test table: see the `pyo3-ci-report.md` asset._
