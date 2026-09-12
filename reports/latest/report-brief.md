# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 41 of 2672 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#34720346903](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/34720346903) |
| Commit | `5b1a6c9882` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1789248997, 1789248998, 1789248999, 1789249000, 1789249001, 1789249003, 1789249004, 1789249005 |
| Generated | 2026-09-12 21:50 UTC |

## Suites

| Suite | Shard | PASS | FAIL | TIMEOUT | ERROR | MISSING | Total | Status |
|---|---|---|---|---|---|---|---|---|
| block-BAC | none | 93 | 3 | 0+0 | 0 | 0 | 96 | FAIL |
| block-BPredUnit | none | 82 | 14 | 0+0 | 0 | 0 | 96 | FAIL |
| block-CSRFile | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Commit | none | 65 | 0 | 0+0 | 0 | 0 | 65 | PASS |
| block-DTLBProbe | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Decode | none | 105 | 0 | 0+0 | 0 | 0 | 105 | PASS |
| block-Dispatch | none | 47 | 0 | 0+0 | 0 | 0 | 47 | PASS |
| block-FTQ | none | 130 | 0 | 0+0 | 0 | 0 | 130 | PASS |
| block-FUPool | none | 51 | 0 | 0+0 | 0 | 0 | 51 | PASS |
| block-Fetch | none | 181 | 5 | 0+0 | 0 | 0 | 186 | FAIL |
| block-FrontEnd | none | 68 | 4 | 0+0 | 0 | 0 | 72 | FAIL |
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
| block-Testbench | none | 107 | 1 | 0+0 | 0 | 0 | 108 | FAIL |
| block-TlbiController | none | 11 | 0 | 0+0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | 89 | 0 | 0+0 | 0 | 0 | 89 | PASS |
| p- | none | 203 | 0 | 1+0 | 0 | 0 | 204 | FAIL |
| v- | 1/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 10/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 11/18 | 8 | 0 | 1+0 | 1 | 0 | 10 | FAIL |
| v- | 12/18 | 8 | 0 | 0+0 | 1 | 0 | 9 | FAIL |
| v- | 13/18 | 6 | 0 | 0+0 | 3 | 0 | 9 | FAIL |
| v- | 14/18 | 7 | 0 | 0+0 | 2 | 0 | 9 | FAIL |
| v- | 15/18 | 8 | 0 | 0+0 | 1 | 0 | 9 | FAIL |
| v- | 16/18 | 7 | 0 | 0+0 | 2 | 0 | 9 | FAIL |
| v- | 17/18 | 8 | 0 | 0+0 | 1 | 0 | 9 | FAIL |
| v- | 18/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 2/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 3/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 4/18 | 9 | 0 | 0+0 | 1 | 0 | 10 | FAIL |
| v- | 5/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 6/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 8/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| **all** |  | 2631 | 27 | 2+0 | 12 | 0 | 2672 | FAIL |

## Failures

| Test | Suite | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|
| `test_bac_cl.TestGenerateFetchTargets::test_btb_hit_with_not_taken_prediction` | block-BAC | FAIL | - | - | 0s | - | assert 4104 == 4100  +  where 4104 = FTQHeadEntry(ft_bb_idx=3, start_pc=4096, end_pc=4104, pred_target=4104, is_branch=T... |
| `test_bac_cl.TestGenerateFetchTargets::test_btb_hit_with_taken_prediction` | block-BAC | FAIL | - | - | 0s | - | assert 4100 == 4096  +  where 4100 = FTQHeadEntry(ft_bb_idx=5, start_pc=4096, end_pc=4100, pred_target=8192, is_branch=T... |
| `test_bac_cl.TestRound3MediumGaps::test_update_pc_forwards_is_uncond` | block-BAC | FAIL | - | - | 0s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) self = <BAC.test_bac_cl.TestRound3MediumG... |
| `test_bpred_unit_cl.TestBPUSquashTo::test_squash_to_removes_entries_from_anchor` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) self = <BPredUnit.test_bpred_unit_cl.Test... |
| `test_bpred_unit_cl.TestDrainComplete::test_drain_complete_true_after_commit` | block-BPredUnit | FAIL | - | - | 0s | - | assert False is True  +  where False = <o3.bpred_unit_cl._DrainCompleteResp object at 0x7f887480a2f0>.complete  +    whe... |
| `test_bpred_unit_cl.TestHistFullBackPressure::test_predict_does_not_modify_cpred_when_full` | block-BPredUnit | FAIL | - | - | 0s | - | UnboundLocalError: cannot access local variable '_own_ck' where it is not associated with a value self = <BPredUnit.test... |
| `test_bpred_unit_cl.TestHistFullBackPressure::test_predict_does_not_modify_ras_when_full` | block-BPredUnit | FAIL | - | - | 0s | - | UnboundLocalError: cannot access local variable '_own_ck' where it is not associated with a value self = <BPredUnit.test... |
| `test_bpred_unit_cl.TestPlaceholderAllocation::test_placeholder_allocates_entry_after_anchor` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) self = <BPredUnit.test_bpred_unit_cl.Test... |
| `test_bpred_unit_cl.TestPlaceholderAllocation::test_placeholder_commit_time_corrective_squash` | block-BPredUnit | FAIL | - | - | 0s | - | assert 3 == 2  +  where 3 = _count_entries(s.hist_buf)  +    where s.hist_buf = s.hist_buf self = <BPredUnit.test_bpred_... |
| `test_bpred_unit_cl.TestPlaceholderAllocation::test_placeholder_no_squash_to` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) self = <BPredUnit.test_bpred_unit_cl.Test... |
| `test_bpred_unit_cl.TestRAS::test_predict_return_pops_ras` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) self = <BPredUnit.test_bpred_unit_cl.Test... |
| `test_bpred_unit_cl.TestSkipBTBUpdateNoRequiresBTBHit::test_btb_update_skip_logic` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: call should add BTB entry assert 2 == (0 + 1)  +  where 2 = <function TestSkipBTBUpdateNoRequiresBTBHit.... |
| `test_bpred_unit_cl.TestSquash::test_simple_squash_removes_younger_entries` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) self = <BPredUnit.test_bpred_unit_cl.Test... |
| `test_bpred_unit_cl.TestTargetPriority::test_ras_overrides_btb_target` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) self = <BPredUnit.test_bpred_unit_cl.Test... |
| `test_bpred_unit_cl.TestUpdate::test_update_commits_oldest_entries` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) self = <BPredUnit.test_bpred_unit_cl.Test... |
| `test_bpu_update_train_cl.TestBPUTrainPipeline::test_combined_training_pipeline` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: cycle 13: should be not-taken assert True is False  +  where True = BPUPredictResp(bpu_predict_resp_vali... |
| `test_bpu_update_train_cl.TestBPUTrainPipeline::test_combined_training_pipeline_commit_mode` | block-BPredUnit | FAIL | - | - | 0s | - | AssertionError: cycle 2: should be not-taken assert True is False  +  where True = BPUPredictResp(bpu_predict_resp_valid... |
| `test_per_thread_fetch_cl.TestPredictedBranch::test_pt290_predicted_branch_stops_fetch` | block-Fetch | FAIL | - | - | 0s | - | assert 0 == 1  +  where 0 = PerThreadFetchTickResp(pt_new_fetch_status=11, pt_new_pc=4096, pt_new_fetch_offset=0, pt_new... |
| `test_per_thread_fetch_cl.TestPredictedBranch::test_pt291_predicted_branch_cleared_after` | block-Fetch | FAIL | - | - | 0s | - | assert True is False  +  where True = s._pending_predicted_branch self = <Fetch.test_per_thread_fetch_cl.TestPredictedBr... |
| `test_per_thread_fetch_cl.TestSquashHandling::test_pt206_interrupt_pending_blocks_fetch` | block-Fetch | FAIL | - | - | 0s | - | assert 11 == <FetchStatus.TrapPending: 5>  +  where 11 = PerThreadFetchTickResp(pt_new_fetch_status=11, pt_new_pc=4096, ... |
| `test_per_thread_fetch_cl.TestTickBasic::test_pt102_tick_running_with_valid_buffer` | block-Fetch | FAIL | - | - | 0s | - | assert 0 > 0  +  where 0 = PerThreadFetchTickResp(pt_new_fetch_status=11, pt_new_pc=4096, pt_new_fetch_offset=0, pt_new_... |
| `test_per_thread_fetch_cl.TestTickBasic::test_pt103_tick_icache_access_complete` | block-Fetch | FAIL | - | - | 0s | - | assert 11 == <FetchStatus.Running: 0>  +  where 11 = PerThreadFetchTickResp(pt_new_fetch_status=11, pt_new_pc=4096, pt_n... |
| `test_frontend_cl.TestBPUSquashInPlaceholder::test_bpu_placeholder_squash_issued` | block-FrontEnd | FAIL | - | - | 0s | - | AssertionError: PlaceholderOnly squash should have occurred assert 0 > 0  +  where 0 = len([]) self = <FrontEnd.test_fro... |
| `test_frontend_cl.TestEndToEndBTBMissAndTraining::test_btb_miss_placeholder_detection` | block-FrontEnd | FAIL | - | - | 0s | - | AssertionError: Expected PlaceholderOnly squash call, got 0 calls: types=[] assert 0 > 0  +  where 0 = len([]) self = <F... |
| `test_frontend_cl.TestEndToEndBTBMissAndTraining::test_btb_miss_then_training_flow` | block-FrontEnd | FAIL | - | - | 0s | - | AssertionError: PlaceholderOnly squash should have occurred assert 0 > 0  +  where 0 = len([]) self = <FrontEnd.test_fro... |
| `test_frontend_cl.TestEndToEndBTBMissAndTraining::test_prediction_switch_not_taken_to_taken` | block-FrontEnd | FAIL | - | - | 0s | - | AssertionError: PlaceholderOnly squash required for training test assert 0 > 0  +  where 0 = len([]) self = <FrontEnd.te... |
| `test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sh:store half]` | block-Testbench | FAIL | - | - | 8s | - | AssertionError: StorageManager: alloc buffer full (cfg_max_allocs_per_cycle=2) riscv_tests_elf_dir = '/home/runner/work/... |
| `rv64mi-p-illegal` | p- | TIMEOUT | - | - | 108s | 599820860 | - |
| `rv64ui-v-slt` | v- | ERROR | - | - | 50s | 520768026 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-clz` | v- | ERROR | - | - | 9s | 611267770 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-clzw` | v- | ERROR | - | - | 5s | 833410950 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-cpop` | v- | ERROR | - | - | 8s | 467549282 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-cpopw` | v- | ERROR | - | - | 10s | 702051997 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-ctz` | v- | ERROR | - | - | 9s | 888588262 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-ctzw` | v- | ERROR | - | - | 9s | 664613286 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-orc_b` | v- | ERROR | - | - | 7s | 513164782 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-roriw` | v- | ERROR | - | - | 5s | 373980776 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-sext_b` | v- | ERROR | - | - | 5s | 623354292 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-sext_h` | v- | ERROR | - | - | 8s | 336999000 | exit=None cycles=-1 status=ERROR |
| `rv64uzbb-v-zext_h` | v- | ERROR | - | - | 9s | 468332173 | exit=None cycles=-1 status=ERROR |
| `rv64uziccid-v-ziccid` | v- | TIMEOUT | - | - | 584s | 173096690 | - |

_Full 2672-test table: see the `pyo3-ci-report.md` asset._
