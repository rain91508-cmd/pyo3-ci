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

## All 2672 results

<details>
<summary>Full per-test table</summary>

| Test | Suite | Status | cycles | wall |
|---|---|---|---|---|
| test_bac_cl.TestBACConstruction::test_bac_construct | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACConstruction::test_bac_initial_state | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACConstruction::test_bac_reset_state | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACSpecGapsRound2::test_case3_squash_before_predict | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACSpecGapsRound2::test_case5_is_uncond_from_branch_type | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACSpecGapsRound2::test_pred_target_carries_next_pc_when_not_taken | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACSpecGapsRound2::test_resteer_ack_cleared_on_squashing_to_running | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACSpecGapsRound2::test_resteer_ack_not_cleared_if_squash_extends | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACThreadStatusFSM::test_drain_to_idle | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACThreadStatusFSM::test_ftqfull_to_running | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACThreadStatusFSM::test_idle_to_running | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACThreadStatusFSM::test_running_to_ftqfull | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACThreadStatusFSM::test_running_to_squashing_commit | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBACThreadStatusFSM::test_squashing_to_running | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSMTAndValidation::test_bpu_hist_buf_global_allocation | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSMTAndValidation::test_bpu_squash_checks_valid | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSMTAndValidation::test_bpu_update_checks_valid | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSMTAndValidation::test_ftq_entry_has_bpu_history_valid | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSMTAndValidation::test_squash_to_uses_bpu_history_valid | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSquashTo::test_squash_to_calls_bpu_squash_to | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSquashTo::test_squash_to_clears_bpred_hist | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSquashTo::test_squash_to_empty_ftq | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBPUSquashTo::test_squash_to_skips_zero_hist | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteer::test_resteer_basic | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteer::test_resteer_clear_states | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteer::test_resteer_invalidate_ftq | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteer::test_resteer_protocol_timing | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteerAck::test_resteer_ack_cleared_after_tick | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteerAck::test_resteer_ack_cleared_by_clear_states | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteerAck::test_resteer_ack_cleared_by_deactivate_thread | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteerAck::test_resteer_ack_deferred_one_cycle | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteerAck::test_resteer_ack_no_resteer_is_false | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteerAck::test_resteer_guard_while_squashing | block-BAC | PASS | - | 0 |
| test_bac_cl.TestBacResteerAck::test_resteer_invalid_request_no_ack | block-BAC | PASS | - | 0 |
| test_bac_cl.TestCheckSignalsAndUpdate::test_commit_done_seqnum_update | block-BAC | PASS | - | 0 |
| test_bac_cl.TestCheckSignalsAndUpdate::test_commit_over_decode_squash | block-BAC | PASS | - | 0 |
| test_bac_cl.TestCheckSignalsAndUpdate::test_commit_squash_corrective | block-BAC | PASS | - | 0 |
| test_bac_cl.TestCheckSignalsAndUpdate::test_commit_squash_simple | block-BAC | PASS | - | 0 |
| test_bac_cl.TestCheckSignalsAndUpdate::test_decode_squash_corrective | block-BAC | PASS | - | 0 |
| test_bac_cl.TestCheckSignalsAndUpdate::test_decode_squash_simple | block-BAC | PASS | - | 0 |
| test_bac_cl.TestCheckSignalsAndUpdate::test_non_control_mispredict | block-BAC | PASS | - | 0 |
| test_bac_cl.TestClearStates::test_clear_states | block-BAC | PASS | - | 0 |
| test_bac_cl.TestClearStates::test_deactivate_thread | block-BAC | PASS | - | 0 |
| test_bac_cl.TestClearStates::test_drain_complete | block-BAC | PASS | - | 0 |
| test_bac_cl.TestDoPredictForPredecode::test_do_predict_for_predecode_not_taken | block-BAC | PASS | - | 0 |
| test_bac_cl.TestDoPredictForPredecode::test_do_predict_for_predecode_taken | block-BAC | PASS | - | 0 |
| test_bac_cl.TestDoPredictForPredecode::test_update_pre_decode_calls_predict_for_no_entry | block-BAC | PASS | - | 0 |
| test_bac_cl.TestDoPredictForPredecode::test_update_pre_decode_calls_predict_for_non_exit | block-BAC | PASS | - | 0 |
| test_bac_cl.TestGenerateFetchTargets::test_btb_hit_with_not_taken_prediction | block-BAC | FAIL | - | 0 |
| test_bac_cl.TestGenerateFetchTargets::test_btb_hit_with_taken_prediction | block-BAC | FAIL | - | 0 |
| test_bac_cl.TestGenerateFetchTargets::test_ftq_full_stops_generation | block-BAC | PASS | - | 0 |
| test_bac_cl.TestGenerateFetchTargets::test_max_ft_per_cycle_limit | block-BAC | PASS | - | 0 |
| test_bac_cl.TestGenerateFetchTargets::test_max_taken_pred_per_cycle_limit | block-BAC | PASS | - | 0 |
| test_bac_cl.TestGenerateFetchTargets::test_no_btb_hit_creates_fallthrough_ft | block-BAC | PASS | - | 0 |
| test_bac_cl.TestGlobalStageStatus::test_active_when_running | block-BAC | PASS | - | 0 |
| test_bac_cl.TestGlobalStageStatus::test_active_when_squashing | block-BAC | PASS | - | 0 |
| test_bac_cl.TestGlobalStageStatus::test_inactive_when_ftqfull | block-BAC | PASS | - | 0 |
| test_bac_cl.TestGlobalStageStatus::test_inactive_when_idle | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3Gaps::test_case2_type_mismatch_calls_predict_with_tid | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3Gaps::test_commit_done_seqnum_no_update_when_zero | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3Gaps::test_commit_done_seqnum_triggers_bpu_update | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3Gaps::test_update_pre_decode_uses_bb_idx_lookup | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3MediumGaps::test_resteer_ack_cleared_second_tick | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3MediumGaps::test_resteer_ack_not_visible_immediately | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3MediumGaps::test_resteer_ack_visible_after_tick | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3MediumGaps::test_update_pc_flags_default_false_for_conditional | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3MediumGaps::test_update_pc_forwards_is_call | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3MediumGaps::test_update_pc_forwards_is_return | block-BAC | PASS | - | 0 |
| test_bac_cl.TestRound3MediumGaps::test_update_pc_forwards_is_uncond | block-BAC | FAIL | - | 0 |
| test_bac_cl.TestSpecCrossCheckGaps::test_squash_to_passes_tid | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSpecCrossCheckGaps::test_squash_to_passes_tid_nonzero | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSpecCrossCheckGaps::test_status_change_on_ftq_full_in_generation | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSpecCrossCheckGaps::test_update_bac_status_called_from_tick | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSpecCrossCheckGaps::test_update_bac_status_not_called_when_no_change | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSpecCrossCheckMisc::test_clear_states_requires_committed_pc | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSpecCrossCheckMisc::test_deactivate_thread_ifc_exists | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSpecCrossCheckMisc::test_deactivate_thread_uses_reset_state | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSpecCrossCheckMisc::test_param_validation_fetch_target_width | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSquashHandling::test_squash_bpu_histories | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSquashHandling::test_squash_flushes_ftq | block-BAC | PASS | - | 0 |
| test_bac_cl.TestSquashHandling::test_squashing_one_cycle_transient | block-BAC | PASS | - | 0 |
| test_bac_cl.TestTickBehavior::test_status_change_flag | block-BAC | PASS | - | 0 |
| test_bac_cl.TestTickBehavior::test_tick_no_signals_running | block-BAC | PASS | - | 0 |
| test_bac_cl.TestTickBehavior::test_tick_not_running_no_generation | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePC::test_ft_consumed_exit_inst | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePC::test_non_branch_advance | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePC::test_pred_taken_return | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecode::test_exit_branch_no_history_creates_placeholder | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecode::test_invalid_request_returns_default | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecode::test_multi_branch_microop_locks_ftq | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecode::test_no_ftq_entry_creates_placeholder | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecode::test_non_exit_branch_creates_placeholder | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecode::test_normal_match_exit_branch | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecode::test_type_mismatch_squashes_and_locks | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecodeTypeMismatch::test_type_match_normal_path | block-BAC | PASS | - | 0 |
| test_bac_cl.TestUpdatePreDecodeTypeMismatch::test_type_mismatch_squashes_and_locks_ftq | block-BAC | PASS | - | 0 |
| test_bimodal_cl.TestBimodalLookup::test_initial_prediction_is_not_taken | block-BPredUnit | PASS | - | 0 |
| test_bimodal_cl.TestBimodalLookup::test_lookup_returns_prediction | block-BPredUnit | PASS | - | 0 |
| test_bimodal_cl.TestBimodalSquash::test_squash_releases_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_bimodal_cl.TestBimodalTrain::test_train_decrements_counter_on_not_taken | block-BPredUnit | PASS | - | 0 |
| test_bimodal_cl.TestBimodalTrain::test_train_increments_counter_on_taken | block-BPredUnit | PASS | - | 0 |
| test_bimodal_cl.TestBimodalTrainSquashed::test_train_squashed_does_not_update_counter | block-BPredUnit | PASS | - | 0 |
| test_bimodal_cl.TestBimodalTrainSquashed::test_train_squashed_releases_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_bimodal_cl.TestBimodalUpdateHist::test_update_hist_is_noop | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBPU2CyclePipeline::test_1cycle_response_is_immediate | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBPU2CyclePipeline::test_2cycle_req_ready_deasserted_during_processing | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBPU2CyclePipeline::test_2cycle_req_ready_reasserted_after_tick | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBPU2CyclePipeline::test_2cycle_response_not_immediate | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBPU2CyclePipeline::test_2cycle_response_valid_after_tick | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBPUPerfCounters::test_perf_branches_increments_on_predict | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBPUPerfCounters::test_perf_mispredicts_increments_on_mispredict_commit | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBPUSquashTo::test_squash_to_removes_entries_from_anchor | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestBTBUpdateAtSquash::test_corrective_squash_no_btb_update_when_flag_false | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBTBUpdateAtSquash::test_corrective_squash_no_btb_update_when_not_taken | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBTBUpdateAtSquash::test_corrective_squash_updates_btb_when_updateBTBAtSquash | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBasicPrediction::test_predict_btb_hit_returns_taken | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestBasicPrediction::test_predict_btb_miss_returns_not_taken | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestDrainComplete::test_drain_complete_false_when_cpred_ckpt_not_empty | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestDrainComplete::test_drain_complete_false_when_history_not_empty | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestDrainComplete::test_drain_complete_true_after_commit | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestDrainComplete::test_drain_complete_true_when_empty | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestDrainComplete::test_drain_complete_with_ipred_checks_ipred_ckpt | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestHistFullBackPressure::test_predict_does_not_modify_cpred_when_full | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestHistFullBackPressure::test_predict_does_not_modify_ras_when_full | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestHistFullBackPressure::test_predict_returns_hist_full_when_buffer_full | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestPlaceholderAllocation::test_placeholder_allocates_entry_after_anchor | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestPlaceholderAllocation::test_placeholder_clones_cpred_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestPlaceholderAllocation::test_placeholder_commit_time_corrective_squash | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestPlaceholderAllocation::test_placeholder_no_squash_to | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestPlaceholderAllocation::test_placeholder_updates_btb | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestRAS::test_predict_call_pushes_ras | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestRAS::test_predict_return_pops_ras | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestSkipBTBUpdateNoRequiresBTBHit::test_btb_update_skip_logic | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestSquash::test_corrective_squash_corrects_mispredict | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestSquash::test_simple_squash_removes_younger_entries | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestTargetPriority::test_no_target_forces_not_taken | block-BPredUnit | PASS | - | 0 |
| test_bpred_unit_cl.TestTargetPriority::test_ras_overrides_btb_target | block-BPredUnit | FAIL | - | 0 |
| test_bpred_unit_cl.TestUpdate::test_update_commits_oldest_entries | block-BPredUnit | FAIL | - | 0 |
| test_bpu_update_train_cl.TestBPUTrainPipeline::test_combined_training_pipeline | block-BPredUnit | FAIL | - | 0 |
| test_bpu_update_train_cl.TestBPUTrainPipeline::test_combined_training_pipeline_commit_mode | block-BPredUnit | FAIL | - | 0 |
| test_btb_cl.TestBTBAccess::test_access_different_pc_misses | block-BPredUnit | PASS | - | 0 |
| test_btb_cl.TestBTBAccess::test_access_hit_after_install | block-BPredUnit | PASS | - | 0 |
| test_btb_cl.TestBTBAccess::test_access_miss_returns_no_hit | block-BPredUnit | PASS | - | 0 |
| test_btb_cl.TestBTBAccess::test_access_returns_branch_metadata | block-BPredUnit | PASS | - | 0 |
| test_btb_cl.TestBTBFlush::test_flush_invalidates_all_entries | block-BPredUnit | PASS | - | 0 |
| test_btb_cl.TestBTBUpdate::test_update_req_buffers_update | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareLookup::test_initial_prediction_is_not_taken | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareLookup::test_lookup_allocates_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareLookup::test_lookup_invalid_returns_default | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareLookup::test_lookup_returns_taken_or_not_taken | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareSquash::test_squash_releases_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareSquash::test_squash_restores_ghr | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrain::test_train_commit_does_not_update_counter_in_squash_mode | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrain::test_train_consumes_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrain::test_train_decrements_counter_on_not_taken | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrain::test_train_increments_counter_on_taken | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrainSquashed::test_train_squashed_does_not_update_counter_in_commit_mode | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrainSquashed::test_train_squashed_not_taken_replays_direction | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrainSquashed::test_train_squashed_releases_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrainSquashed::test_train_squashed_restores_ghr_and_updates_counter | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareTrainSquashed::test_train_squashed_updates_counter_in_squash_mode | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareUpdateHist::test_update_hist_masks_ghr_width | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareUpdateHist::test_update_hist_shifts_ghr_not_taken | block-BPredUnit | PASS | - | 0 |
| test_gshare_cl.TestGshareUpdateHist::test_update_hist_shifts_ghr_taken | block-BPredUnit | PASS | - | 0 |
| test_indirect_pred_cl.TestIPredCommit::test_commit_does_not_crash | block-BPredUnit | PASS | - | 0 |
| test_indirect_pred_cl.TestIPredCorrect::test_correct_installs_target_in_cache | block-BPredUnit | PASS | - | 0 |
| test_indirect_pred_cl.TestIPredLookup::test_lookup_miss_returns_no_hit | block-BPredUnit | PASS | - | 0 |
| test_indirect_pred_cl.TestIPredLookup::test_lookup_returns_bb_idx | block-BPredUnit | PASS | - | 0 |
| test_indirect_pred_cl.TestIPredSquash::test_squash_restores_ghr | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASCommit::test_commit_preserves_ras_state | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASCommit::test_commit_releases_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASPop::test_pop_empty_returns_empty | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASPop::test_pop_lifo_ordering | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASPop::test_pop_returns_hist_idx | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASPop::test_pop_returns_last_pushed | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASPush::test_push_allocates_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASPush::test_push_increments_tos | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASPush::test_push_returns_hist_idx | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASPush::test_push_stores_return_address | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASSquash::test_squash_undoes_push | block-BPredUnit | PASS | - | 0 |
| test_ras_cl.TestRASSquash::test_squash_undoes_younger_push_keeps_older | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGELookup::test_lookup_allocates_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGELookup::test_lookup_returns_prediction | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGELookup::test_lookup_uses_base_table_on_no_tagged_hit | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGESquash::test_squash_releases_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGESquash::test_squash_restores_ghr_and_path_hist | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGETrainSquashed::test_train_squashed_does_not_update_base_table | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGETrainSquashed::test_train_squashed_not_taken_replays_direction | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGETrainSquashed::test_train_squashed_releases_checkpoint | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGETrainSquashed::test_train_squashed_restores_ghr_and_path_hist | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGEUpdateHist::test_update_hist_shifts_ghr | block-BPredUnit | PASS | - | 0 |
| test_tage_cl.TestTAGEUpdateHist::test_update_hist_updates_path_history | block-BPredUnit | PASS | - | 0 |
| test_csr_file_cl.TestConstruction::test_constructs_with_default_params | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestConstruction::test_exposes_read_callee_ifc | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestConstruction::test_exposes_write_callee_ifc | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestConstruction::test_read_rdy_is_true_after_reset | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestMultiThread::test_write_tid0_does_not_affect_tid1 | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestOverwriteAndReset::test_overwrite_csr_returns_latest_value | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestOverwriteAndReset::test_reset_restores_misa_default | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestRead::test_read_misa_returns_default_after_reset | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestRead::test_read_uninitialized_csr_returns_zero | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestSStatusAlias::test_read_sstatus_returns_mstatus_view_after_reset | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestSStatusAlias::test_write_sstatus_sie_folds_into_mstatus | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestSStatusAlias::test_write_sstatus_zero_preserves_uxl_sxl | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_read_triggers_snapshot | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_reset_disables_all_triggers | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata1_load_and_store_triggers_round_trip | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata1_type2_round_trip | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata1_unsupported_type_disabled | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata2_write_and_read | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata3_write_and_read | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata_indirection_across_slots | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tinfo_readonly_value | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tselect_defaults_to_zero | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tselect_out_of_range_ignored | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tselect_write_and_read | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTwoWriterSlots::test_cmt_write_field_merge_preserves_frm | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTwoWriterSlots::test_wb_and_cmt_write_same_cycle_both_land | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestTwoWriterSlots::test_wb_and_cmt_write_same_cycle_rdy_restore | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestWrite::test_write_rdy_false_when_pending | block-CSRFile | PASS | - | 0 |
| test_csr_file_cl.TestWrite::test_write_then_read_returns_value_after_tick | block-CSRFile | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_no_capable_fu_mce_follows_fault_path | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_rob_retire_ack_semantics | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_trap_count_init_trapLatency_not_minus_1 | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_trap_state_cleanup_after_trapSquash | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADR0005M6OptionB::test_commit_derives_prev_phys_reg_via_m6_option_b | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADR0005M6OptionB::test_commit_skips_free_when_allocated_new_false | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADR0005M6OptionB::test_fip_drain_during_rob_squashing_full_bandwidth | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADR0005M6OptionB::test_fip_drain_during_running_strict_priority | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_cmt_fip_full_false_when_empty | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_cmt_fip_full_when_fifo_full | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_fip_clear_on_superseding_squash | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_fip_fifo_depth_matches_spec | block-Commit | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_has_stores_to_wb_prev_falling_edge | block-Commit | PASS | - | 0 |
| test_commit_cl.TestBackwardBus::test_bc_done_seqnum | block-Commit | PASS | - | 0 |
| test_commit_cl.TestBackwardBus::test_bc_free_rob_entries | block-Commit | PASS | - | 0 |
| test_commit_cl.TestBackwardBus::test_bc_squash_broadcast | block-Commit | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_can_handle_interrupts | block-Commit | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_commit_status_running | block-Commit | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_drain_flags | block-Commit | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_fip_fifo_empty | block-Commit | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_pc | block-Commit | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_seqnums_zero | block-Commit | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_trap_flags | block-Commit | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_is_store_alone_does_not_trigger_serialize_after | block-Commit | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_is_store_alone_does_not_trigger_strictly_ordered | block-Commit | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_robhi_serialize_after_field_exists | block-Commit | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_robhi_strictly_ordered_field_exists | block-Commit | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_serialize_after_sets_pending_without_is_store | block-Commit | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_strictly_ordered_sets_bc_without_is_store | block-Commit | PASS | - | 0 |
| test_commit_cl.TestEmptyROB::test_empty_rob_four_way_conjunction | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFIPDrain::test_fip_commit_frees_have_priority | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFIPDrain::test_fip_drains_to_freelist | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFIPDrain::test_fip_writes_from_rename | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_fault_guard_met_triggers_trap | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_fault_guard_not_met_stalls | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_trap_countdown_multi_cycle | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_trap_fsm_to_rob_squashing | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_trap_sets_no_squash_from_tc | block-Commit | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_trap_sets_trap_pending | block-Commit | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_mispredict_sets_bc_mispredict_inst | block-Commit | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_squash_drives_rob_squash_req | block-Commit | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_squash_sets_bc_squash_inst | block-Commit | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_squash_too_young_ignored | block-Commit | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_squash_validates_age | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNonSpeculative::test_non_spec_broadcasts_seqnum | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNonSpeculative::test_non_spec_clears_can_commit | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNonSpeculative::test_non_spec_stalls_when_stores_pending | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNonSpeculative::test_strictly_ordered_load_sets_bc_flag | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_advances_pc | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_broadcasts_done_seqnum | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_frees_prev_phys_reg_to_freelist | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_multiple_up_to_width | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_no_dest_no_freelist_update | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_retires_rob_head | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_single_instruction | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_store_sets_committed_stores | block-Commit | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_updates_renamemap | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_oldest_ready_selection | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_round_robin_selection | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_phase1_commits | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_phase1_sets_pending | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_phase2_initiates_squash | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_phase2_squashes | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSquashedHeadRetirement::test_squashed_head_no_arch_effect | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSquashedHeadRetirement::test_squashed_head_silently_retired | block-Commit | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_dcache_va_probe_pa_caller_ifc_exists | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_dcache_va_probe_req_caller_ifc_exists | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_dcache_va_probe_resp_callee_ifc_exists | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_dtlb_ports_param_exists | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_no_pa_req_ports_on_dtlb_probe | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestDTLBResp::test_dtlb_fault_sends_result | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestDTLBResp::test_dtlb_hit_sets_paddr | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestDTLBResp::test_dtlb_miss_keeps_waiting | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestInterfaces::test_callee_ports_exist | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestInterfaces::test_caller_ports_exist | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestL1Probe::test_l1_hit_sends_result | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestL1Probe::test_l1_miss_sends_result_no_data | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_both_threads_independent | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_construct_accepts_max_threads_param | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_default_max_threads_is_one_backward_compat | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_tag_space_accommodates_total_entries | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_tag_space_asymmetric_sizes_uses_max | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_translate_req_tid0_uses_tag_in_lq_partition | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_translate_req_tid1_uses_tag_in_lq_partition | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestReset::test_after_reset_all_inactive | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestReset::test_after_reset_no_pending | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestTranslateReq::test_translate_req_processed_after_tick | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestTranslateReq::test_translate_req_sets_pending | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_dtlb_miss_recovery_does_not_send_va_probe_pa | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_dtlb_miss_recovery_sends_translate_result_l1_hit_false | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_l1_cancelled_on_dtlb_fault | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_l1_cancelled_on_dtlb_miss | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_l1_response_ignored_after_cancellation | block-DTLBProbe | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_translate_req_resets_l1_cancelled | block-DTLBProbe | PASS | - | 0 |
| test_decode_cl.TestBPUCorrectionSignals::test_bpu_correction_includes_tid_and_bb_idx | block-Decode | PASS | - | 0 |
| test_decode_cl.TestBPUCorrectionSignals::test_branch_mispredict_sets_both_squash_and_mispredict | block-Decode | PASS | - | 0 |
| test_decode_cl.TestBPUCorrectionSignals::test_commit_squash_suppresses_bpu_correction | block-Decode | PASS | - | 0 |
| test_decode_cl.TestBPUCorrectionSignals::test_control_miss_sets_bpu_squash_not_mispredict | block-Decode | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_backpressure_resume_flow | block-Decode | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_preload_buffer_absorbs_when_thread_not_selected | block-Decode | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_preload_buffer_full_fetch_sees_not_full_false | block-Decode | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_rename_stall_prevents_thread_selection | block-Decode | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_rename_unblock_allows_thread_selection | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_custom_params_construction | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_default_construction | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_dr_buffer_empty | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_fsm_state_all_idle | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_fsm_state_multi_thread | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_no_rename_stall | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_preload_buffer_empty | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_rr_ptr_zero | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_reset_clears_all_state | block-Decode | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_wrote_to_time_buffer_initially_false | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_dr_pop_interface | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_dr_tid_count_exposed | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_dr_tid_not_empty_exposed | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_dr_tid_not_full_exposed | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_rename_width_limits_pop | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeErrorHandling::test_decode1_typeerror_from_regid_construction_propagates | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeErrorHandling::test_decode2_keyerror_from_decode_inst_does_not_propagate | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeErrorHandling::test_decode2_typeerror_from_decode_inst_propagates | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_count_increments | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_flush_on_squash | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_multi_thread_isolation | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_not_empty | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_not_full | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_shared_pool_capacity | block-Decode | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_push_instruction_to_dr_buffer | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_conditional_branch_correct_prediction | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_conditional_branch_mispredict | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_control_miss_corrected_pc_is_fallthrough | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_control_miss_predicted_taken_not_control | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_correct_prediction_no_squash | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_direct_branch_mispredict_jal_target_mismatch | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_drives_decode_bpu_correction | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_drives_decode_squash_to_fetch | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_flushes_dr_buffer | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_flushes_preload_buffer | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_sets_squashing_state | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_squashing_to_running_next_cycle | block-Decode | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_single_mispredict_per_cycle_per_thread | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_activity_flag_not_set_when_idle | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_activity_flag_set_on_decode | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_backpressure_resume_flow | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_branch_not_taken_correctly_predicted | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_early_mispredict_recovery_timeline | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_fetch_decode_rename_flow | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_full_flow_with_mispredict_and_recovery | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_is_active_when_running | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_is_active_when_squashing | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_jal_always_taken_mispredict | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_multi_cycle_decode_flow | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_multiple_instructions_decode_in_one_cycle | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_preload_buffer_bypass_same_cycle | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_smt_2_threads_interleaving | block-Decode | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_squash_resume_flow | block-Decode | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_can_issue_set_when_num_src_regs_zero | block-Decode | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_addi_instruction | block-Decode | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_branch_instruction | block-Decode | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_dest_reg_idx_populated | block-Decode | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_jal_instruction | block-Decode | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_nop | block-Decode | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_width_limit_respected | block-Decode | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_forward_f_fields_unchanged | block-Decode | PASS | - | 0 |
| test_decode_cl.TestNewFields::test_can_issue_false_for_nonzero_src_regs | block-Decode | PASS | - | 0 |
| test_decode_cl.TestNewFields::test_can_issue_true_for_zero_src_regs | block-Decode | PASS | - | 0 |
| test_decode_cl.TestNewFields::test_op_class_populated | block-Decode | PASS | - | 0 |
| test_decode_cl.TestNewFields::test_static_opcode_carries_machinst | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_accumulates_when_not_selected | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_count | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_flush_on_squash | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_multi_thread_isolation | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_not_empty | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_not_full | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_pop | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_shared_pool_capacity | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_push_instruction_to_preload_buffer | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBufferExposed::test_preload_count_exposed | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBufferExposed::test_preload_not_empty_exposed | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPreloadBufferExposed::test_preload_not_full_exposed | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPullModel::test_fd_has_data_used_for_eligibility | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPullModel::test_tid_sel_set_on_thread_selection | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPullModel::test_tid_sel_valid_false_when_no_data | block-Decode | PASS | - | 0 |
| test_decode_cl.TestPullModel::test_tid_sel_with_multi_thread | block-Decode | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_commit_squash_flushes_buffers | block-Decode | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_commit_squash_multi_thread | block-Decode | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_commit_squash_priority_over_decode_mispredict | block-Decode | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_commit_squash_sets_squashing_state | block-Decode | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_squash_while_processing_instructions | block-Decode | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_squashing_to_running_next_cycle | block-Decode | PASS | - | 0 |
| test_decode_cl.TestSquashedInstruction::test_all_squashed_no_output | block-Decode | PASS | - | 0 |
| test_decode_cl.TestSquashedInstruction::test_squashed_instruction_skipped | block-Decode | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_no_eligible_thread_no_selection | block-Decode | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_round_robin_across_2_threads | block-Decode | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_rr_pointer_advances_correctly | block-Decode | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_single_thread_always_selected | block-Decode | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_skip_thread_in_squashing_state | block-Decode | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_skip_thread_with_dr_buffer_full | block-Decode | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_skip_thread_with_rename_stall | block-Decode | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_backpressure_then_ready_dispatches | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_iq_not_ready_skips_dispatch | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_iq_ready_dispatches_normally | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_lsq_load_not_ready_skips_dispatch | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_lsq_load_uses_caller_ifc_port | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_lsq_store_not_ready_skips_dispatch | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_lsq_store_uses_caller_ifc_port | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_has_op_class | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_has_phys_src_reg | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_has_seqnum | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_has_tid | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_is_not_none | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToIQ::test_dispatch_round_robin_across_threads | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToIQ::test_dispatch_sends_iq_dispatch_req | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToLSQ::test_load_dispatched_to_lsq | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToLSQ::test_lsq_indices_passed_to_iq_req | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToLSQ::test_store_dispatched_to_lsq | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_fsm_running_after_squash_allows_dispatch | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_non_squashed_thread_dispatches_normally | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_squash_keeps_fsm_running | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_squash_prevents_dispatch_in_same_cycle | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestRenameReceive::test_rename_buffers_into_fifo | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestRenameReceive::test_rename_rdy_when_fifo_not_full | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestReset::test_after_reset_fifos_empty | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestReset::test_after_reset_fsm_running | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestSquash::test_squash_discards_younger_entries | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestBatchedIQDispatch::test_iq_dispatch_returns_local_indices | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestBatchedIQDispatch::test_multiple_instructions_single_batched_call | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestBatchedIQDispatch::test_single_instruction_batched_call | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIQSetDependency::test_no_set_dependency_for_ready_source | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIQSetDependency::test_set_dependency_for_multiple_distinct_producers | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIQSetDependency::test_set_dependency_for_single_not_ready_source | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInstCarriesIQMetadata::test_inst_cluster_id_set | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInstCarriesIQMetadata::test_inst_iq_local_id_set | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInterfaceExistence::test_iq_set_dependency_port_exists | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInterfaceExistence::test_sb_get_producer_port_exists | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInterfaceExistence::test_sb_set_producer_port_exists | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIntraBatchShadow::test_same_cycle_producer_resolved_via_shadow | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIntraBatchShadow::test_shadow_populated_by_each_dest_reg | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestPendingSrcCount::test_pending_src_count_deduped | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestPendingSrcCount::test_pending_src_count_multiple_distinct_producers | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestPendingSrcCount::test_pending_src_count_one_for_single_producer | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestPendingSrcCount::test_pending_src_count_zero_for_ready_sources | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestProducerDedup::test_dedup_same_producer_two_slots | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestSetProducerOnDestRegs::test_set_producer_called_for_multiple_dests | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestSetProducerOnDestRegs::test_set_producer_called_for_single_dest | block-Dispatch | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestSetProducerOnDestRegs::test_set_producer_uses_cluster_base_for_global_id | block-Dispatch | PASS | - | 0 |
| test_ftq_cl.TestConcurrentOperations::test_concurrent_insert_pop | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestConcurrentOperations::test_concurrent_insert_squash | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_construct_custom | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_construct_default | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_initial_state | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_reset_clears_all | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_reset_initial_signals | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_status_enum_values | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestControlSignalArbitration::test_squash_from_any_state | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_bb_idx_stored_in_sram | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_bpu_history_valid_lifecycle | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_insert_after_squash | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_multiple_squashes | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_single_entry_queue | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_wrap_around | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_end_address | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_has_exceeded | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_in_range | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_is_exit_branch | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_is_exit_inst | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_size | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_start_address | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestHeadRegisterAndBubble::test_head_reg_bb_idx_forwarded | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestHeadRegisterAndBubble::test_head_reg_bubble_after_pop | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestHeadRegisterAndBubble::test_head_reg_deasserted_on_squash | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestHeadRegisterAndBubble::test_head_reg_forward_on_insert_empty | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestHeadRegisterAndBubble::test_head_reg_initially_invalid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestHeadRegisterAndBubble::test_head_reg_set_on_insert | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestHeadRegisterAndBubble::test_head_reg_valid_next_cycle | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_bb_idx_forwarding | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_bpu_history_valid_default | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_empty_makes_head_valid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_fields | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_full_fails | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_full_status | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_invalid_fails | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_multiple | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_single | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_advances_head | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_bubble | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_case1_clears_sram_read_pending | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_case1_deasserts_head_valid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_empties_queue | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_empty_queue | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_failure_case1 | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_fifo_order | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_success | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestReadHeadOperations::test_head_ready_signal | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestReadHeadOperations::test_read_head_correct_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestReadHeadOperations::test_read_head_empty | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestReadHeadOperations::test_read_head_invalid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestReadHeadOperations::test_read_head_not_valid_after_pop | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestReadHeadOperations::test_read_head_returns_entry | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestRecoveryTiming::test_bac_initiated_squash_recovery | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestRecoveryTiming::test_fetch_initiated_recovery | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestRecoveryTiming::test_pop_head_failure_triggers_invalidate | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestResetStateOperations::test_reset_state_clears_entries | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestResetStateOperations::test_reset_state_preserves_other_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestResetStateOperations::test_reset_state_sets_valid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_dequeue_correct_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_insert_rejected_when_invalid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_is_empty_per_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_is_full_per_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_per_thread_head_reg | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_per_thread_status | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_reset_state_preserves_other_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_squash_preserves_other_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_clears_entries | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_deasserts_head_valid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_from_invalid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_preserves_other_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_preserves_other_thread_head_reg | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_resets_pointers | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_sets_valid | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_single_cycle | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_empty | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_empty_per_thread | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_full | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_head_ready | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_ready | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_num_free_entries | block-FTQ | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_size | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_ftq_entry_has_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_ftq_entry_no_bpred_hist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_ftq_insert_req_has_ftq_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_ftq_insert_req_no_ftq_bpred_hist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_insert_bb_idx_forwarded_to_head | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_iter_entry_resp_has_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_iter_entry_resp_no_bpred_hist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestClearHeadHistory::test_clear_head_history_clears_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestClearHeadHistory::test_clear_head_history_clears_bpu_history_valid | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestClearHeadHistory::test_clear_head_history_is_callable | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestControlSignalPriority::test_squash_overrides_insert | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestForAllBackwardRemoved::test_for_all_backward_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestGetOldestBpuAnchor::test_get_oldest_bpu_anchor_is_callable | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestGetOldestBpuAnchor::test_get_oldest_bpu_anchor_returns_head_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestGetOldestBpuAnchor::test_get_oldest_bpu_anchor_returns_invalid_when_none | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestIsFullPerThread::test_is_full_accepts_tid | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestIsFullPerThread::test_is_full_based_on_per_thread_count | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_attribute_exists | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_count_after_one_insert | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_has_per_thread_count | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_has_per_thread_head | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_has_per_thread_tail | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_head_initially_invalid | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_head_valid_after_insert | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestRemovedMethods::test_get_count_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestRemovedMethods::test_get_status_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestRemovedMethods::test_unlock_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestResetStateNoReReadHead::test_reset_state_head_valid_unconditionally_false | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestResetStateNoReReadHead::test_reset_state_no_head_reg_after_reset | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestClearHeadHistoryTriggerChange::test_clear_head_history_mentions_fetch | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestControlSignalPriorityChange::test_priority_is_reset_state_squash_pop_insert | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFSMEncodingChange::test_invalid_is_0 | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFSMEncodingChange::test_locked_attribute_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFSMEncodingChange::test_valid_is_1 | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFtSeqnumWidthRemoved::test_construct_does_not_accept_ft_seqnum_width | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFtSeqnumWidthRemoved::test_ft_seqnum_width_attribute_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFtSeqnumWidthRemoved::test_head_seqnum_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFtqLockedSignalRemoved::test_is_locked_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestIsLockedMethodRemoved::test_is_locked_method_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockMethodRemoved::test_lock_method_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockMethodRemoved::test_pending_lock_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockedStateRemoved::test_ftq_status_never_value_2 | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockedStateRemoved::test_initial_status_is_valid | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockedStateRemoved::test_locked_attribute_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestMaxThreadsDefaultChange::test_default_max_threads_is_1 | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestPopHeadCase2Removed::test_pop_head_never_returns_fail_reason_1 | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestPopHeadCase2Removed::test_pop_head_only_one_failure_case | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestPopHeadCase2Removed::test_pop_head_valid_and_bpu_history_valid_returns_fail_reason_0 | block-FTQ | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_5_clusters_present | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_float_cluster_has_fpadd_fpmult_fpdiv | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_int_cluster_has_intalu_intmult_intdiv | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_max_op_latency_is_20 | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_mem_cluster_has_address_calc_fu | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestCompletionTiming::test_1_cycle_op_completes_next_cycle | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestCompletionTiming::test_fu_drained_false_when_pipeline_occupied | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestFreeFU::test_freefu_is_noop_in_pipelined_model | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestFuCompleteBundle::test_fu_complete_bundle_default_fields | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestFuCompleteBundle::test_fu_complete_bundle_has_branch_mispredict | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestFuCompleteBundle::test_fu_complete_bundle_no_trap_fields | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestFuOperand::test_fu_operand_squashed_bypass_skips_compute | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestFuOperand::test_fu_operand_stores_result_in_pending_compute | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_float_cluster | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_mem_cluster | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_returns_fu_idx_for_supported_opclass | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_returns_no_capable_for_unsupported_opclass | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_returns_op_latency | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestPerClusterState::test_per_cluster_in_flight_arrays_exist | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestPerClusterState::test_per_cluster_pipeline_arrays_exist | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestPerClusterState::test_pipeline_stages_sized_to_max_op_latency | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_end_to_end_add_compute_and_extract | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_end_to_end_add_through_fupool | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_end_to_end_fadds_through_fupool | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_real_add_instruction_category | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_real_add_instruction_compute | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestReset::test_after_reset_all_pipelines_empty | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestReset::test_after_reset_fu_drained_true | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl.TestReset::test_after_reset_rr_ptrs_zero | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestFuRealCompletePort::test_fu_real_complete_is_callable | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestFuRealCompletePort::test_fu_real_complete_port_exists | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestLDACompletionNoFuRealComplete::test_lda_does_not_fire_fu_real_complete_from_fupool | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestNormalCompletionFiresFuRealComplete::test_float_completion_fires_fu_real_complete | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestNormalCompletionFiresFuRealComplete::test_int_completion_fires_fu_real_complete | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestSTA_STDDecallocAtIssue::test_sta_does_not_fire_fu_real_complete_at_issue | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestSTA_STDDecallocAtIssue::test_std_does_not_fire_fu_real_complete_at_issue | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestSquashedFastPathQ12::test_squashed_does_not_wait_for_op_latency | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestSquashedFastPathQ12::test_squashed_int_fires_fu_real_complete_same_cycle | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestNormalCompletionFiresSbSetReg::test_int_completion_fires_sb_setReg_for_single_dest | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestNormalCompletionFiresSbSetReg::test_multi_dest_completion_fires_sb_setReg_per_dest | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestSbSetRegInterface::test_sb_setReg_is_callable | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestSbSetRegInterface::test_sb_setReg_port_exists | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestSquashedCompletionSuppressesSbSetReg::test_squashed_non_lda_completion_skips_sb_setReg | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteInterface::test_fu_early_complete_is_callable | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteInterface::test_fu_early_complete_port_exists | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteMemUopRouting::test_no_early_complete_for_lda | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteTiming::test_early_complete_fires_before_real_complete | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteTiming::test_early_complete_not_fired_for_squashed | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_squash_force_ack.TestSquashForceEarlyCompleteADR0033::test_fu_pool_exposes_ic_squash_port | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_squash_force_ack.TestSquashForceEarlyCompleteADR0033::test_ic_squash_is_callable | block-FUPool | PASS | - | 0 |
| test_fu_pool_cl_adr0033_squash_force_ack.TestSquashForceEarlyCompleteADR0033::test_squash_mid_flight_fires_force_early_complete | block-FUPool | PASS | - | 0 |
| test_fetch_cl.TestBACResteer::test_f120_bac_resteer_req_dispatched | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBACResteer::test_f121_bac_resteer_req_fields | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f320_bc_has_commit_info | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f321_bc_no_dec_to_fetch | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f322_bc_has_stalls_drain | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f323_bc_no_old_flat_arrays | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f324_bc_commit_info_per_thread | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f325_bc_no_dec_to_fetch_per_thread | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f326_bc_stalls_drain_defaults | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f327_bc_commit_info_squash_triggers_squash | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f328_decode_squash_to_fetch_triggers_squash | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f329_bc_stalls_drain_blocks_drain | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f330_bc_commit_info_interrupt | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f331_bc_commit_info_clear_interrupt | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f332_bc_to_dict_roundtrip | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBuildPerThreadTickReq::test_f90_builds_request | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBuildPerThreadTickReq::test_f91_includes_stall_flags | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestBuildPerThreadTickReq::test_f92_includes_interrupt_from_bc | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f300_commit_info_defaults | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f301_commit_info_squash_and_pc | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f302_commit_info_interrupt_flags | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f303_commit_info_to_dict | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f304_commit_info_from_dict | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestConstants::test_f70_invalid_thread_id | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestCountFetchingThreads::test_f80_zero_when_all_waiting | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestCountFetchingThreads::test_f81_one_when_running | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestCountFetchingThreads::test_f82_counts_eligible_states | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDesignParameters::test_f340_max_ft_per_cycle_exists | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDesignParameters::test_f341_max_ft_per_cycle_default | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDesignParameters::test_f342_max_taken_pred_per_cycle_exists | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDesignParameters::test_f343_max_taken_pred_per_cycle_default | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueues::test_f140_drain_assigns_seqnum | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueues::test_f141_drain_respects_decode_width | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueues::test_f142_drain_respects_decode_stall | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueues::test_f143_drain_respects_drain_stall | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f160_no_drain_without_tid_sel_valid | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f161_drain_when_tid_sel_valid | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f162_all_insts_same_thread | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f163_drain_only_selected_thread | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f164_drain_respects_decode_width | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f165_drain_empty_selected_thread | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f166_per_thread_status_always_provided | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f167_drain_assigns_seqnum | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f168_no_drain_priority_counter | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f169_drain_respects_decode_stall_pull | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f170_drain_respects_drain_stall_pull | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f10_custom_decode_width | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f1_default_construction | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f2_initial_seq_num_counter | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f3_initial_global_status_inactive | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f4_initial_per_thread_components | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f5_initial_priority_list | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f6_initial_stalls_clear | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f7_initial_num_inst_zero | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f8_custom_max_threads | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f9_custom_fetch_width | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f30_single_thread_running | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f31_single_thread_idle | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f32_no_eligible_thread | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f33_round_robin_rotation | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f34_eligible_states | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f35_ineligible_states | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestResetClear::test_f50_reset_stage | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestResetClear::test_f51_reset_stage_per_thread | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestResetClear::test_f52_clear_states | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestResetClear::test_f53_clear_states_preserves_other_threads | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSequenceNumber::test_f11_first_seq_is_one | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSequenceNumber::test_f12_seq_monotonically_increasing | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSequenceNumber::test_f13_seq_counter_increments | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSequenceNumber::test_f14_seq_shared_across_threads | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSignalRenames::test_f200_fetch_to_decode_has_fd_tid_count | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSignalRenames::test_f201_fetch_to_decode_no_fq_count | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSignalRenames::test_f202_fetch_to_decode_no_fq_not_empty | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSignalRenames::test_f203_fetch_to_decode_no_fq_not_full | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f100_commit_squash_calls_do_squash | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f101_decode_squash_calls_do_squash | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f102_trap_pending_sets_flag | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f103_decode_block_removed | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f104_decode_unblock_removed | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f105_commit_squash_priority_over_decode | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f106_squash_redirects_pc | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f107_squash_clears_fetch_queue | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f108_squash_sets_delayed_commit | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestStallFlags::test_f20_stall_flags_initial | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestStallFlags::test_f21_stall_flags_set_decode | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestStallFlags::test_f22_stall_flags_set_drain | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestStallsDrain::test_f25_stalls_drain_from_bc | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestStallsDrain::test_f26_stalls_drain_cleared_when_deasserted | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestStallsDrain::test_f27_is_drained_initially | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestStallsDrain::test_f28_drain_stall_method_removed | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestUpdateFetchStatus::test_f40_active_when_running | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestUpdateFetchStatus::test_f41_active_when_icache_access_complete | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestUpdateFetchStatus::test_f42_inactive_when_all_idle | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestUpdateFetchStatus::test_f43_inactive_when_all_ftq_wait | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestWakeFromQuiesce::test_f60_wake_sets_running | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestWakeFromQuiesce::test_f61_wake_adds_to_priority_list | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestWakeFromQuiesce::test_f62_wake_no_duplicate_in_priority | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt60_build_inst_creates_dyninst | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt61_build_inst_sets_pc | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt62_build_inst_sets_pred_pc | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt63_build_inst_sets_tid | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt64_build_inst_pushes_to_queue | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt65_build_inst_with_fault | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt66_drain_fetch_queue_empty | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt67_drain_fetch_queue_partial | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt68_drain_fetch_queue_full | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt69_drain_preserves_order | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestCheckSignalsPriority::test_pt110_trap_pending_overrides_running | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestCheckSignalsPriority::test_pt112_squashing_to_running | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestClearHeadHistory::test_pt310_resp_has_clear_head_history | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestClearHeadHistory::test_pt311_clear_head_history_default_false | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestClearHeadHistory::test_pt312_clear_head_history_on_ftq_pop | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt10_initial_not_resteering | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt11_initial_no_cache_line | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt12_initial_empty_fetch_queue | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt13_initial_not_predicted_branch | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt14_custom_tid | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt15_custom_fetch_width | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt16_custom_fetch_queue_size | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt1_default_construction | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt2_initial_status_idle | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt3_initial_pc_zero | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt4_initial_fetch_offset_zero | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt5_initial_buffer_invalid | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt8_initial_no_delayed_commit | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt9_initial_no_fault_pending | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDecodeErrorHandling::test_keyerror_from_decoder_does_not_propagate | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDecodeErrorHandling::test_typeerror_from_decoder_propagates | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt50_squash_sets_pc | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt51_squash_resets_fetch_offset | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt54_squash_sets_squashing_status | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt55_squash_clears_fetch_queue | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt56_squash_sets_delayed_commit | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt57_squash_clears_resteering | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt58_squash_invalidates_buffer | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFailReason1Bit::test_pt300_pop_head_fail_reason_1bit | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFailReason1Bit::test_pt301_pop_head_no_locked_reason | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt30_running_value | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt31_idle_value | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt32_squashing_value | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt34_trap_pending_value | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt35_quiesce_pending_value | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt39_icache_access_complete_value | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt40_ftq_wait_value | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt41_no_good_addr_value | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt42_no_fetching_state | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt140_align_to_buffer | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt141_buffer_hit_valid | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt142_buffer_hit_invalid | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt143_buffer_hit_miss | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt144_num_insts_derived | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsBranchFromFetch::test_pt320_is_branch_set_from_ftq_head | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsBranchFromFetch::test_pt321_is_branch_default_false_without_ftq | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsDrained::test_pt70_drained_initially | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsDrained::test_pt71_not_drained_with_queue | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsDrained::test_pt72_not_drained_with_fault_pending | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestLatchState::test_pt120_latch_status | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestLatchState::test_pt121_latch_pc | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestLatchState::test_pt122_latch_fetch_offset | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestLatchState::test_pt123_latch_buffer_valid | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestNoGoodAddrAndQuiesce::test_pt280_no_good_addr_no_fetch | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestNoGoodAddrAndQuiesce::test_pt281_quiesce_pending_no_fetch | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestNoGoodAddrAndQuiesce::test_pt282_no_good_addr_exits_on_squash | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestPredictedBranch::test_pt290_predicted_branch_stops_fetch | block-Fetch | FAIL | - | 0 |
| test_per_thread_fetch_cl.TestPredictedBranch::test_pt291_predicted_branch_cleared_after | block-Fetch | FAIL | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt20_reset_stage | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt21_clear_states | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt22_clear_states_preserves_status | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt23_clear_states_preserves_pc | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt24_clear_states_preserves_fetch_queue | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSetters::test_pt90_set_interrupt_pending | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSetters::test_pt91_set_trap_pending | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt201_squash_clears_fault_pending | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt204_trap_pending_in_tick | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt205_trap_pending_cleared_after_tick | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt206_interrupt_pending_blocks_fetch | block-Fetch | FAIL | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt207_interrupt_with_delayed_commit | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt210_squashing_to_ftq_wait | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt212_squashing_delayed_commit_cleared | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt100_tick_idle_no_op | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt102_tick_running_with_valid_buffer | block-Fetch | FAIL | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt103_tick_icache_access_complete | block-Fetch | FAIL | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt104_tick_squashing_no_fetch | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt106_tick_drain_stall_blocks | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestWakeFromQuiesce::test_pt80_wake_sets_running | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestWakeFromQuiesce::test_pt81_wake_updates_pending_status | block-Fetch | PASS | - | 0 |
| test_frontend_cl.TestBACPredictionFlow::test_bac_commit_done_seqnum_triggers_bpu_update | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACPredictionFlow::test_bac_drain_stall_transitions_to_idle | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACPredictionFlow::test_bac_generates_ftq_entry | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACPredictionFlow::test_bac_idle_to_running_on_tick | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACPredictionFlow::test_bac_pc_advances_after_generation | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACPredictionFlow::test_ftq_entry_has_valid_start_pc | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACResteerFlow::test_fetch_bac_resteer_wired | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACResteerFlow::test_fetch_resteer_to_bac_end_to_end | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACResteerFlow::test_resteer_ack_cleared_after_tick | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACResteerFlow::test_resteer_ack_deferred_one_cycle | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACResteerFlow::test_resteer_basic | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACResteerFlow::test_resteer_ignored_while_squashing | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBACResteerFlow::test_resteer_protocol_timing | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestBPUSquashInPlaceholder::test_bpu_placeholder_squash_issued | block-FrontEnd | FAIL | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_bac_initial_pc_zero | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_bac_initial_state_idle | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_decode_initial_preload_count_zero | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_decode_initial_status | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_fetch_initial_status_inactive | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_fetch_per_thread_initial_idle | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_frontend_constructs | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_frontend_sub_components_wired | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_ftq_initially_empty | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_line_trace_format | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_set_trace_enabled | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestConstructionAndReset::test_sim_reset_clears_pending_buffers | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestDecodeFlow::test_backward_ctrl_consumed_after_tick | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestDecodeFlow::test_backward_ctrl_forwarded_to_decode | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestDecodeFlow::test_decode_drain_sel_wired | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestDecodeFlow::test_decode_initial_preload_empty | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestDecodeFlow::test_decode_to_rename_interface_exists | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestEndToEndBTBMissAndTraining::test_btb_miss_placeholder_detection | block-FrontEnd | FAIL | - | 0 |
| test_frontend_cl.TestEndToEndBTBMissAndTraining::test_btb_miss_then_training_flow | block-FrontEnd | FAIL | - | 0 |
| test_frontend_cl.TestEndToEndBTBMissAndTraining::test_prediction_switch_not_taken_to_taken | block-FrontEnd | FAIL | - | 0 |
| test_frontend_cl.TestFTQToFetchDataPath::test_ftq_head_cleared_after_squash | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFTQToFetchDataPath::test_ftq_head_committed_to_fetch_after_tick | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFTQToFetchDataPath::test_ftq_is_full_back_pressure | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFTQToFetchDataPath::test_ftq_read_head_after_bac_generation | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFTQToFetchDataPath::test_ftq_read_head_after_pop | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFTQToFetchDataPath::test_ftq_read_head_after_squash | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFTQToFetchDataPath::test_ftq_read_head_multiple_entries | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFetchToDecodeDrain::test_decode_drain_sel_triggers_fetch_drain | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFetchToDecodeDrain::test_decode_drain_with_dr_pop_and_field_check | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFetchToDecodeDrain::test_fetch_drain_end_to_end_with_icache | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFetchToDecodeDrain::test_fetch_drain_multiple_instructions | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFetchToDecodeDrain::test_fetch_drain_stalled_by_drain_stall | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFetchToDecodeDrain::test_fetch_drain_without_decode_selection | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFrontendIntegration::test_bac_backward_ctrl_dispatched | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFrontendIntegration::test_clear_interrupt_via_backward_bus | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFrontendIntegration::test_drain_stall_via_backward_bus | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFrontendIntegration::test_ftq_full_stops_bac_generation | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFrontendIntegration::test_interrupt_pending_via_backward_bus | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFrontendIntegration::test_multiple_ticks_advance_pipeline | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestFrontendIntegration::test_trap_pending_via_backward_bus | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestICacheAccessFlow::test_icache_resp_consumed_after_tick | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestICacheAccessFlow::test_icache_resp_forwarded_to_fetch | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestICacheAccessFlow::test_icache_resp_with_synthetic_instructions | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestICacheAccessFlow::test_itlb_resp_consumed_after_tick | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestICacheAccessFlow::test_itlb_resp_forwarded_to_fetch | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestInternalInterfaces::test_ftq_empty_after_squash_then_refill | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestInternalInterfaces::test_ftq_push_head_fields_match_ftq | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestInternalInterfaces::test_ftq_push_to_fetch | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestInternalInterfaces::test_per_thread_round_trip_inst_count | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestInternalInterfaces::test_per_thread_round_trip_tick_req | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestInternalInterfaces::test_pop_head_clear_history_buffered_before_dispatch | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestInternalInterfaces::test_pop_head_clear_history_dispatched | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestSquashFlow::test_commit_squash_forwarded_to_fetch | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestSquashFlow::test_commit_squash_priority_over_decode | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestSquashFlow::test_commit_squash_redirects_bac | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestSquashFlow::test_commit_squash_with_mispredict | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestSquashFlow::test_decode_squash_via_backward_ctrl | block-FrontEnd | PASS | - | 0 |
| test_frontend_cl.TestSquashFlow::test_squashing_is_one_cycle_transient | block-FrontEnd | PASS | - | 0 |
| test_icache_cl.TestBackpressure::test_i51_ready_after_reset | block-ICache | PASS | - | 0 |
| test_icache_cl.TestBackpressure::test_i52_not_ready_when_mshr_full | block-ICache | PASS | - | 0 |
| test_icache_cl.TestBackpressure::test_i53_ready_after_mshr_freed | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i11_single_hit | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i12_multiple_hits_same_cycle | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i13_hit_updates_plru | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i14_hit_does_not_allocate_mshr | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i15_miss_after_hit_line_invalidated | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i16_miss_allocates_mshr | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i17_miss_issues_memory_request | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i18_fill_completes_miss | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i19_fill_writes_cache | block-ICache | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i20_miss_frees_mshr_after_fill | block-ICache | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i36_itlb_miss_allocates_ptw_mshr | block-ICache | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i37_itlb_late_response_retrys_miss | block-ICache | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i38_itlb_late_fault_responds | block-ICache | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i39_itlb_late_perm_denied | block-ICache | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i40_ptw_then_fill | block-ICache | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i41_flush_all_invalidates_everything | block-ICache | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i42_flush_all_ack | block-ICache | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i43_flush_by_va_invalidates_match | block-ICache | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i44_flush_by_va_preserves_unrelated | block-ICache | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i45_flush_by_range | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i0_default_construction | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i10_custom_mshr_config | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i2_derived_parameters | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i3_initial_tag_array_invalid | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i4_initial_plru_zero | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i5_initial_mshr_free | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i6_initial_response_queue_empty | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i7_initial_asid_zero | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i8_initial_flush_inactive | block-ICache | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i9_custom_cache_size | block-ICache | PASS | - | 0 |
| test_icache_cl.TestITLBFault::test_i31_translation_fault_response | block-ICache | PASS | - | 0 |
| test_icache_cl.TestITLBFault::test_i32_permission_denied_no_execute | block-ICache | PASS | - | 0 |
| test_icache_cl.TestITLBFault::test_i33_fault_does_not_allocate_mshr | block-ICache | PASS | - | 0 |
| test_icache_cl.TestITLBFault::test_i34_hit_permission_denied | block-ICache | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i61_fetch_request_port | block-ICache | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i62_fetch_response_port | block-ICache | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i63_itlb_ports | block-ICache | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i64_memory_ports | block-ICache | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i65_flush_ports | block-ICache | PASS | - | 0 |
| test_icache_cl.TestMSHRCoalescing::test_i26_two_requests_same_line_coalesce | block-ICache | PASS | - | 0 |
| test_icache_cl.TestMSHRCoalescing::test_i27_coalesced_waiters_both_respond | block-ICache | PASS | - | 0 |
| test_icache_cl.TestMSHRCoalescing::test_i28_different_lines_allocate_separate_mshrs | block-ICache | PASS | - | 0 |
| test_icache_cl.TestMSHRCoalescing::test_i29_coalesce_only_same_line | block-ICache | PASS | - | 0 |
| test_icache_cl.TestMemoryError::test_i56_memory_error_fault | block-ICache | PASS | - | 0 |
| test_icache_cl.TestMemoryError::test_i57_memory_error_frees_mshr | block-ICache | PASS | - | 0 |
| test_icache_cl.TestMemoryError::test_i58_memory_error_does_not_fill_cache | block-ICache | PASS | - | 0 |
| test_icache_cl.TestPLRU::test_i46_plru_replace_initial | block-ICache | PASS | - | 0 |
| test_icache_cl.TestPLRU::test_i47_plru_replace_after_access | block-ICache | PASS | - | 0 |
| test_icache_cl.TestPLRU::test_i48_fill_uses_plru_victim | block-ICache | PASS | - | 0 |
| test_icache_cl.TestPLRU::test_i49_plru_updates_on_fill | block-ICache | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestBranchClusterWiring::test_branch_cluster_has_dedicated_fus | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestBranchClusterWiring::test_branch_cluster_wires_are_connected | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRFileIntegration::test_csr_file_is_csr_file_cl_instance | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRFileIntegration::test_csr_file_uses_iew_max_threads | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRFileIntegration::test_iew_exposes_csr_file_sub_component | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringReadOperand::test_all_five_read_operand_clusters_have_csr_read_wired | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringReadOperand::test_csr_read_returns_misa_default | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringReadOperand::test_csr_read_returns_zero_for_uninitialized_csr | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringWriteBack::test_wb_csr_write_committed_to_csr_file_after_tick | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringWriteBack::test_wb_csr_write_rdy_follows_csr_file_write_rdy | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EFloatCluster::test_fadd_s_completes_through_float_cluster | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIcSquashFunctional::test_ic_squash_clears_iq_entries | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIcSquashFunctional::test_ic_squash_clears_lsq_load_entry | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIntCluster::test_add_completes_through_int_cluster | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIntCluster::test_addi_imm_completes_through_int_cluster | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2ELoadMemoryPath::test_load_completes_through_memory_path | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMemClusterFUExecution::test_mem_cluster_wires_fire_on_load | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMemLoadPath::test_load_inserts_into_lsq_and_mem_iq | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMemLoadPath::test_load_routes_to_mem_iq_not_int_iq | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMispredictToCommit::test_beq_mispredict_fires_iew_to_commit | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMispredictToCommit::test_mispredict_per_thread_isolation | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureAmoAddWord::test_amo_add_creates_sq_but_not_lq | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureBackToBackIntMultSingleFU::test_two_intmult_ops_both_complete | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureBackwardBusFreeEntries::test_free_iq_entries_decrease_after_dispatch | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureBackwardBusIewBlock::test_iew_block_and_unblock | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureBranchClusterFUExecution::test_beq_through_branch_cluster_wires_fire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureCSRWrite::test_csrrw_fires_wb_csr_write | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureCommitLoadsPath::test_commit_loads_frees_lq_entry | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureCsrWriteFullSignals::test_csrrw_wb_csr_write_all_signals | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureDependentInstructions::test_dependent_adds_raw_bypass | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureDirectCompletePath::test_faulted_lw_fires_direct_complete | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureDrainComplete::test_drain_complete_after_instructions | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureDrainHoldsAfterStallsDrainDeasserts::test_drain_holds_after_deassert | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFaultPreExecPath::test_pre_exec_fault_fires_wb_fault | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFaultTranslationPath::test_load_translation_fault_fires_wb_fault | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFenceExecution::test_fence_complete_clears_lq_sq_fence_entries | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFencePassThrough::test_fence_complete_alias_and_forwarding | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFuAllocNoContentionModel::test_two_mul_ops_both_complete_no_contention | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureIcSquashFunctional::test_squashed_add_issues_with_squashed_flag | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureIqFullBackpressure::test_iq_full_rdy_returns_false | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureLSQLoadPath::test_lw_load_path_fires_dtlb_req | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureLSQStorePath::test_sw_store_path_fires_dtlb_req | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureLoadDataReturnPath::test_load_data_flows_through_lsq_execute_resp | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureLsqInsertRdyGap::test_insert_load_rdy_always_true | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMemClusterWiresFunctional::test_lw_through_mem_cluster_wires_fire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMemViolationToCommit::test_mem_violation_fires_iew_to_commit | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMispredictToCommit::test_beq_taken_pred_not_taken_fires_iew_to_commit | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMispredictToCommit::test_bne_not_taken_pred_taken_fires_iew_to_commit | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMispredictToCommit::test_jal_unconditional_pred_not_taken_fires_iew_to_commit | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureNonSpecInstReady::test_non_spec_inst_ready_clears_sq_entry | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSCFailurePath::test_sc_fails_when_reservation_not_set | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSCPath::test_lr_then_sc_succeeds_with_reservation | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSRETFault::test_sret_u_mode_fires_wb_fault | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSnoopInv::test_snoop_inv_reissues_inflight_load | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSplitLoadPath::test_split_load_issues_two_dcache_reqs | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashDuringFuCompute::test_fadd_squash_mid_compute_suppresses_rf_write | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashDuringLsqExecute::test_load_squash_in_lsq_suppresses_rf_write | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashEffect::test_add_squash_before_issue_suppresses_rf_write | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashEffect::test_intmult_squash_mid_flight_suppresses_rf_write | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashThreadIsolation::test_squash_tid0_isolates_tid1 | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureStoreDTLBFullSignals::test_store_dtlb_req_all_signals | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureStrictlyOrderedLoadReplay::test_strictly_ordered_load_polls_then_issues_after_commit | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureTLBIInv::test_tlbi_inv_marks_lq_entries_stale | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureTLBMissDefer::test_dtlb_miss_defers_load_then_reissue | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureTwoIndependentInstructions::test_two_independent_adds_both_complete | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureTwoThreadConcurrentDispatch::test_two_thread_adds_both_complete | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureViolationAck::test_violation_ack_clears_sticky_flag | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureViolationBeatsMispredict::test_violation_beats_mispredict_same_cycle | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureWawOrdering::test_waw_both_writeback_in_order | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureWbFaultFullSignals::test_sret_wb_fault_all_signals | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EStoreMemoryPath::test_store_pa_req_fires_with_correct_signals | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EStorePath::test_store_inserts_into_lsq_and_mem_iq | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVAProbePath::test_dcache_va_probe_resp_accepted | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVAProbePath::test_va_probe_pa_fires_on_dtlb_hit | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVAProbePath::test_va_probe_req_fires_with_load | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVectorCluster::test_vector_op_routes_to_vector_iq | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVectorClusterFUExecution::test_vector_fu_executes_and_writes_vec_reg | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EWbCsrWritePath::test_csrrw_fires_through_pipeline | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EWbFaultPath::test_ecall_faults_through_pipeline | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EWbRobUpdateFullSignals::test_rob_update_carries_all_9_signals | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EWbRobUpdateFullSignals::test_sb_setreg_fires_with_correct_phys_reg | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_bc_iew_squash_clears_pending_in_parent | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_bc_iew_squash_per_thread_isolation | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_bc_iew_squash_propagates_to_writeback_pending | block-IEW | PASS | - | 1 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_writeback_ic_squash_signature_is_tid_seqnum | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_dispatch_to_iq_iq_dispatch_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_dispatch_to_lsq_insert_load_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_dispatch_to_lsq_insert_store_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_fupool_to_writeback_fu_complete_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_ic_squash_fanout_to_all_sub_blocks | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_iq_to_readoperand_int_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_lsq_to_writeback_execute_resp_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_float_to_fupool_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_float_to_physregfile_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_float_to_writeback_issued_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_mem_to_writeback_direct_complete_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_to_fupool_int_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_to_physregfile_int_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_to_writeback_issued_wire | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestStructuralBackwardBusWiring::test_bc_ports_exist_and_wired | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestStructuralDrainWiring::test_drain_ports_exist_and_wired | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl::test_violation_push_sink_to_mempending | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestBypassQueryWiringADR0033Primary::test_all_five_ro_bypass_query_wired_to_write_back | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestBypassQueryWiringADR0033Primary::test_bypass_query_returns_hit_when_completion_pending | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestSbSetRegWiringADR0033Primary::test_fu_pool_sb_setReg_propagates_to_scoreboard | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestSbSetRegWiringADR0033Primary::test_lsq_sb_setReg_propagates_to_scoreboard | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestSbSetRegWiringADR0033Primary::test_scoreboard_has_wb_set_req_from_lsq_port | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestSbSetRegWiringADR0033Primary::test_write_back_has_no_sb_setReg_caller | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_speculation.TestSpeculationWiringADR0033::test_fu_pool_fu_early_complete_wired_to_iq | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_speculation.TestSpeculationWiringADR0033::test_iq_has_fu_early_complete_from_lsq_port | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_speculation.TestSpeculationWiringADR0033::test_lsq_fu_early_complete_wired_to_iq_from_lsq | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_speculation.TestSpeculationWiringADR0033::test_lsq_fu_nack_wired_to_iq | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl.TestReset::test_after_reset_no_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestAddConsumer::test_add_consumer_accumulates_bits | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestAddConsumer::test_add_consumer_idempotent_same_bit | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestAddConsumer::test_add_consumer_rdy_when_producer_valid | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestAddConsumer::test_add_consumer_sets_bit_in_consumer_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_empty_list | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_entries_committed_after_tick | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_rdy_checks_capacity | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_rdy_true_when_enough_space | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_returns_local_indices | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestEntryFields::test_entry_fields_initialized_to_zero | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestEntryFields::test_entry_has_adr0033_fields_after_dispatch | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_broadcasts_consumer_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_sets_acked_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_snapshots_last_ack_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuEarlyComplete::test_fu_real_complete_after_early_complete_only_broadcasts_unacked | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuNack::test_fu_nack_broadcasts_last_ack_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuNack::test_fu_nack_clears_acked_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuNack::test_fu_nack_uses_last_ack_mask_not_current | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_broadcasts_wakeup_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_deallocates_entry | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_excludes_acked_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestIssuedField::test_fu_real_complete_clears_issued_field | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestIssuedField::test_issued_entry_does_not_block_younger_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestIssuedField::test_ready_entry_marked_issued_not_deallocated | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestIssuedField::test_select_skips_issued_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLazySquash::test_squashed_unready_entry_stays_in_iq | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLazySquash::test_sre_shadow_dispatching_state_not_squashed | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLazySquash::test_sre_shadow_squashing_state_detected | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLegacyRemoved::test_pending_wakeup_dests_attribute_removed | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLegacyRemoved::test_state_depend_graph_attribute_removed | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLegacyRemoved::test_wb_wake_destreg_attribute_removed | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbNack::test_wb_nack_increments_pending_src_count | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbNack::test_wb_nack_only_affects_matching_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_decrements_pending_src_count | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_no_match_leaves_unchanged | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_only_affects_matching_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_sets_all_srcs_ready_when_count_reaches_zero | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_empty_list_returns_empty | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_mixed_ops_returns_indices_per_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_multiple_int_reqs_one_cluster_call | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_branch_op_to_branch_iq | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_float_op_to_float_iq | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_int_op_to_int_iq | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_mem_load_to_mem_iq | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_vector_op_to_vector_iq | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBroadcastNackFanout::test_broadcast_nack_fanout_calls_all_5_clusters | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBroadcastWakeupFanout::test_broadcast_wakeup_fanout_calls_all_5_clusters | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBroadcastWakeupFanout::test_int_iq_fu_real_complete_broadcasts_to_all_clusters | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_branch_iq_cluster_base_is_36 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_float_iq_cluster_base_is_44 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_int_iq_cluster_base_is_0 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_mem_iq_cluster_base_is_24 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_vector_iq_cluster_base_is_56 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuEarlyCompleteNackRouting::test_fu_early_complete_routes_to_int_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuEarlyCompleteNackRouting::test_fu_early_complete_routes_to_mem_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuEarlyCompleteNackRouting::test_fu_nack_routes_to_int_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_branch_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_float_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_int_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_mem_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_vector_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIcSquashBroadcast::test_ic_squash_broadcasts_to_all_clusters | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_branch_port_exists | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_float_port_exists | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_int_port_exists | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_mem_port_exists | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_vector_port_exists | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqSetDependency::test_iq_set_dependency_routes_to_float_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqSetDependency::test_iq_set_dependency_routes_to_int_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqSetDependency::test_iq_set_dependency_routes_to_mem_cluster | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestLegacyRemoved::test_no_iq_dispatch_default_attribute | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestLegacyRemoved::test_no_pending_overflow_attribute | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestLegacyRemoved::test_no_up_drain_overflow_attribute | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestLegacyRemoved::test_no_wb_wake_destreg_attribute | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestAddConsumer::test_add_consumer_accumulates_bits | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestAddConsumer::test_add_consumer_idempotent_same_bit | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestAddConsumer::test_add_consumer_rdy_when_producer_valid | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestAddConsumer::test_add_consumer_sets_bit_in_lda_consumer_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_empty_list | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_entries_committed_after_tick | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_load_creates_lda_entry | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_load_returns_one_index | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_rdy_true_when_two_slots_free | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_store_creates_sta_and_std_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_store_needs_two_free_slots | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_store_returns_one_index | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_two_loads_returns_two_indices | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestEntryFields::test_lda_entry_fields_initialized_to_zero | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestEntryFields::test_lda_entry_has_adr0033_fields_after_dispatch | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestEntryFields::test_sta_entry_has_adr0033_fields_after_dispatch | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_broadcasts_consumer_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_sets_acked_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_snapshots_last_ack_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuEarlyComplete::test_fu_real_complete_after_early_complete_only_broadcasts_unacked | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuNack::test_fu_nack_broadcasts_last_ack_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuNack::test_fu_nack_clears_acked_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuNack::test_fu_nack_uses_last_ack_mask_not_current | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_broadcasts_wakeup_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_deallocates_lda_entry | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_excludes_acked_mask | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_fu_real_complete_clears_issued_field_lda | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_fu_real_complete_on_sta_std_is_noop | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_lda_marked_issued_not_deallocated_at_issue | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_select_skips_issued_lda_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_sta_deallocated_at_issue | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_std_deallocated_at_issue | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLazySquash::test_squashed_unready_lda_entry_stays_in_iq | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLazySquash::test_sre_shadow_dispatching_state_not_squashed | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLazySquash::test_sre_shadow_squashing_state_detected | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLegacyRemoved::test_pending_wakeup_dests_attribute_removed | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLegacyRemoved::test_state_depend_graph_attribute_removed | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLegacyRemoved::test_wb_wake_destreg_attribute_removed | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbNack::test_wb_nack_increments_pending_src_count | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbNack::test_wb_nack_only_affects_matching_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_decrements_pending_src_count | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_no_match_leaves_unchanged | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_only_affects_matching_entries | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_sets_all_srcs_ready_when_count_reaches_zero | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_branch_is_36 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_float_is_44 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_branch | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_float | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_int | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_mem | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_vector | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_int_is_0 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_mem_is_24 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_unknown_raises | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_vector_is_56 | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_dispatch_cl_has_no_local_cluster_base_dict | block-IQ | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_iq_cl_has_no_local_cluster_base_constants | block-IQ | PASS | - | 0 |
| test_lq_core_cl.TestADR0019Ports::test_dcache_load_pa_req_caller_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestADR0019Ports::test_dcache_load_pa_req_fires_on_translated | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestADR0019Ports::test_dcache_req_removed | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_advances_head | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_all_entries | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_callee_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_no_entries_above_threshold | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_per_thread | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_pops_head_entries_with_seqnum_le_threshold | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDCacheResp::test_dcache_resp_completes_load | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_callee_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_decrements_pending_producers | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_does_not_decrement_below_zero | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_passes_sq_idx_and_bitvector | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_skips_non_matching_lq_idx | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_unstalls_when_counter_reaches_zero | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_insert_clears_pending_producers | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_load_gated_when_pending_producers_positive | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_load_not_gated_when_pending_producers_zero | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_lq_entry_has_pending_producers_field | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_multiple_producers_require_multiple_broadcasts | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestFSMTranslated::test_dcache_req_caller_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestFSMTranslated::test_translated_to_waiting_resp | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestFSMTranslated::test_waiting_resp_to_complete_on_dcache_resp | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestInsert::test_insert_adds_entry | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestInterfaces::test_callee_ports_exist | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestInterfaces::test_caller_ports_exist | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_completion_no_violation_without_flag | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_completion_no_violation_without_overlap | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_completion_scans_older_entries | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_on_load_violation_dropped_if_already_valid | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_on_load_violation_sticky_until_ack | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_possible_load_violation_flag_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_cache_block_aligned_overlap | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_callee_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_no_match_no_flag | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_sets_possible_load_violation | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_skips_completed_loads | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_skips_untranslated_loads | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_construct_accepts_max_threads_param | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_default_max_threads_is_one_backward_compat | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_insert_tid0_uses_partition0 | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_insert_tid1_uses_partition1 | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_violation_state_per_thread | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_full_forward_does_not_stall | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_no_forward_does_not_stall | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_partial_forward_sets_stalled_flag | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_store_complete_notify_callee_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_store_complete_notify_does_not_unstall_non_matching | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_store_complete_notify_unstalls_matching_load | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_unstalled_load_reruns_stage_b_forward | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestReset::test_after_reset_all_empty | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestReset::test_after_reset_fsm_idle | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSetPhysAddr::test_set_phys_addr_sets_eff_addr_valid | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_clears_ll_sc_reservation_on_is_lr | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_no_dtlb_retrigger | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_reissues_dcache_load_pa_req | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_skips_completed_loads | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_skips_non_overlapping | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_tso_force_squash_younger_loads | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitSnoopScan::test_snoop_hit_frag0_only_triggers_reexec | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitSnoopScan::test_snoop_hit_frag1_only_triggers_reexec | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitSnoopScan::test_snoop_no_hit_no_reexec | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitSnoopScan::test_split_snoop_reexec_reissues_both_fragments | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_both_responses_merge_and_complete | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_frag0_response_stored_separately | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_frag1_response_stored_separately | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_fragment_flags_reset_after_merge | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_lq_entry_has_frag0_fields | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_lq_entry_has_frag1_fields | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_merge_order_independent | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_non_split_load_issues_single_dcache_request | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_partial_fault_frag0_priority | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_partial_fault_frag1_when_frag0_ok | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_split_load_issues_two_dcache_requests | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_split_load_sets_waiting_split_resp_fsm | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrdered::test_strictly_ordered_flag_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrdered::test_strictly_ordered_insert | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_normal_load_not_at_head_proceeds | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_at_head_proceeds | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_not_at_head_polls_internally | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_not_at_head_visible_to_snoop | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_not_at_head_visible_to_violation | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_polls_internally | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_has_stale_method_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_has_stale_per_thread | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_has_stale_returns_false_when_no_stale_entries | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_has_stale_returns_true_when_stale_entries_exist | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_lq_entry_has_stale_translation_field | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_lq_entry_has_vaddr_field | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_non_stale_entry_does_not_trigger_translate_req | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_stale_entry_triggers_translate_req | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_stale_flag_cleared_on_dcache_resp | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_callee_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_is_per_thread | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_marks_inflight_entry_stale | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_skips_completed_loads | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_skips_untranslated_loads | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_translate_req_caller_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestViolationCheck::test_no_violation_on_different_addr | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestViolationCheck::test_violation_detected_on_overlap | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestViolationPayload::test_violation_ack_callee_ifc_exists | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestViolationPayload::test_violation_dropped_if_already_valid | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestViolationPayload::test_violation_sticky_until_ack | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_execute_load_pushes_to_l1_shift_register | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_l1_shift_register_default_depth_matches_params | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_l1_shift_register_depth_is_l1_lat_minus_iss_lat | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_l1_shift_register_pop_fires_fu_early_complete | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_l1_shift_register_release_after_pop | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_lq_core_exposes_l1_shift_register_state | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_default_depth_matches_params | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_depth_is_l2_lat_minus_iss_lat | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_pop_fires_fu_early_complete | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_push_persists_payload | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_release_after_pop | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_lq_core_exposes_l2_shift_register_state | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_f33_shift_cancel_ordering.TestF33ShiftCancelOrdering::test_l1_shift_pop_silent_on_completion_cancel | block-LQCore | PASS | - | 0 |
| test_lq_core_cl_f33_shift_cancel_ordering.TestF33ShiftCancelOrdering::test_l2_shift_pop_silent_on_completion_cancel | block-LQCore | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0017::test_store_set_violation_fires_on_violation_detection | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0017::test_violation_signal_still_fires | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_fence_complete_marks_lq_fence_entry_completed | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_fence_complete_marks_sq_fence_entry_completed | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_fence_complete_unblocks_barred_load | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_full_fence_allocates_both_lq_and_sq_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_insert_load_accepts_is_fence_load_kwarg | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_insert_store_accepts_is_fence_store_kwarg | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_is_load_barred_false_when_no_fence_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_is_load_barred_scans_lq_fence_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_is_store_barred_false_when_no_fence_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_is_store_barred_scans_sq_fence_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_lq_entry_has_is_fence_load_field | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_no_separate_barrier_sets_or_insert_fence | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0029FenceViaLsqEntries::test_sq_entry_has_is_fence_store_field | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_amo_lq_forwards_from_different_seqnum_store | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_amo_lq_skips_own_sq_goes_to_dcache | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_is_atomic_defaults_false_on_lq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_is_atomic_field_set_on_lq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_normal_load_stalls_on_amo_sq | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestCommitLoads::test_commit_loads_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestCommitLoads::test_commit_loads_pops_lq_head_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_dependents_broadcast_wired_to_dependents_update | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_end_to_end_load_stalls_until_producer_executes | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_insert_load_no_producer_leaves_pending_producers_zero | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_insert_load_sets_dependents_bit_on_producer_sq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_insert_load_sets_pending_producers_when_producer_predicted | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_squash_clears_dependents_on_sq_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_squash_clears_pending_producers_on_lq_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_drain_done_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_drain_done_when_empty | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_free_lq_entries_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_free_lq_entries_when_empty | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_free_sq_entries_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_has_stores_to_wb_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_ic_drain_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_execute_store_unified_removed | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_forward_query_waiting_data_registers_dependency | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_no_data_zero_forwarding_in_waiting_data | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_sq_entry_has_data_valid_field | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_sta_sets_fsm_to_waiting_data | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_std_arrival_unstalls_dependent_load | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_std_before_sta | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_std_transitions_waiting_data_to_executed | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_atomic_amo_lq_sq_pair | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_cbo_as_store_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_commit_loads_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_data_prefetch_skip_cam | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_dcache_resp_fifo | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_dtlb_port_arbitration | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_fence_barrier_gating | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_fence_full_barrier_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_ic_drain_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_ignored_responses_counter | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_ll_sc_reservation_set_path | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_ll_sc_success | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_load_on_load_violation_tso_force_squash_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_lsq_dep_check_shift | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_multi_thread_independent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_multi_thread_smoke | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_non_spec_gating | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_predicated_false_fast_path | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_sc_failure_fast_complete | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_simple_load_completion | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_simple_store_completion | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_snoop_lr_clears_reservation_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_snoop_reexec_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_split_load_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_split_store_non_forwardable_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_split_store_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_squash_and_replay | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_squashed_bypass | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_store_backpressure_retry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_store_forwarding_to_load | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_storeset_prediction_full_cycle | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_strictly_ordered_internal_poll | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_tlbi_empty_immediate_sync | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_tlbi_full_flow | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_violation_ack_handshake_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_violation_flow | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_vipt_speculative_l1_load_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_zero_size_store_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoad::test_exec_load_processed_after_tick | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoad::test_exec_load_sets_pending | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_combined_insert_then_execute_load_preserves_size_vaddr | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_combined_insert_then_execute_store_preserves_size_vaddr_data | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_load_does_not_allocate | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_load_preserves_dispatch_fields | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_load_writes_vaddr_size_to_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_store_does_not_allocate | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_store_writes_vaddr_size_data_to_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteStore::test_exec_store_sets_pending | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_load_populates_dispatch_fields | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_load_returns_one_second | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_load_returns_zero_first | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_load_tid_partition | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_store_populates_dispatch_fields | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_store_returns_zero_first | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInterfaces::test_external_callee_ports_exist | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInterfaces::test_external_caller_ports_exist | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestInterfaces::test_stale_interfaces_removed | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestLLSCWiring::test_clear_reservation_callee_ifc_exists_on_sq_store | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestLLSCWiring::test_ll_sc_clear_reservation_wired_in_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_construct_accepts_max_threads_param | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_default_max_threads_is_one_backward_compat | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_exec_load_tid0_allocates_in_partition0 | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_exec_load_tid1_allocates_in_partition1 | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_free_lq_entries_per_thread | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_free_sq_entries_per_thread | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_squash_tid0_does_not_invalidate_tid1 | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_state_lq_alloc_is_per_thread_array | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_state_sq_alloc_is_per_thread_array | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_subblocks_get_max_threads | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_check_inst_returns_3_tuple | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_check_inst_returns_ssid_after_violation_only | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_check_inst_returns_valid_after_store_dispatch | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_end_to_end_dependent_loads_setup_via_n1 | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_insert_store_stores_ssid_on_sq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_populate_lfst_fires_at_dispatch | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_populate_lfst_fires_for_non_spec_then_clear_lfst_at_translation | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_populate_lfst_fires_once_at_dispatch | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_sq_entry_has_ssid_field | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_execute_load_no_longer_takes_size_or_is_lr | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_execute_store_no_longer_takes_size | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_insert_load_mem_size_defaults_to_zero | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_insert_load_takes_mem_size_and_is_lr | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_insert_store_is_sc_defaults_to_false | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_insert_store_takes_mem_size_and_is_sc | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_sc_fast_complete_path_via_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_fence_complete_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_insert_store_non_atomic_has_non_spec_false | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_is_load_barred_blocks_younger_loads | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_is_load_barred_false_when_no_barriers | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_is_store_barred_blocks_younger_stores | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_is_store_barred_false_when_no_barriers | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_load_execute_stalled_by_barrier | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_load_execute_unblocks_after_fence_complete | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_nonSpecInstReady_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_nonSpecInstReady_clears_sq_non_spec | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_store_execute_stalled_by_barrier | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_store_execute_unblocks_after_fence_complete | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_lq_tag_forwards_to_lq_core | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_frag0_tag_calls_store_complete | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_frag1_tag_calls_store_complete_is_frag1 | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_tag_reads_tid_from_sq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_parent_dcache_resp_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_execute_load_rdy_false_when_all_slots_full | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_execute_load_rdy_when_all_slots_free | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_existing_single_load_still_works | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_fence_barred_load_retries_next_cycle | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_first_free_slot_reused_after_tick | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_ports_capacity | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_slot_dict_fields | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_multiple_loads_accepted_per_cycle | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_multiple_stores_accepted_per_cycle | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_squashed_bypass_multiple_ports | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestReset::test_after_reset_alloc_zero | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestReset::test_after_reset_no_pending | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitAccess::test_split_field_exists_on_lq | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitAccess::test_split_field_exists_on_sq | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitFragmentCompletion::test_both_frags_complete_marks_eff_addr_valid | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitFragmentCompletion::test_frag0_translate_sets_frag0_valid_only | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitFragmentCompletion::test_frag1_then_frag0_also_completes | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitFragmentCompletion::test_frag1_translate_sets_frag1_valid_only | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitStore::test_non_split_store_has_none_split | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitStore::test_split_store_both_frags_complete | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitStore::test_split_store_crossing_page_boundary | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitStore::test_split_store_issues_two_dtlb_requests | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_non_split_load_has_none_split | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_non_split_load_issues_single_dtlb_request | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_split_field_exists_on_lq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_split_load_crossing_page_boundary | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_split_load_issues_two_dtlb_requests | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashHandling::test_ic_squash_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashHandling::test_squash_complete_caller_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashHandling::test_squash_complete_pulses | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashHandling::test_squash_invalidates_lq_entries | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_load_bypass | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_load_does_not_set_eff_addr_valid | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_load_entry_freed_by_squash_walk | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_store_bypass | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_store_does_not_set_canWB | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_ldstq_count_after_insert_load | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_ldstq_count_after_insert_store | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_ldstq_count_combined | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_ldstq_count_decreases_on_commit | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_ldstq_count_zero_after_reset | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_update_next_cycle_false_after_reset | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_update_next_cycle_false_when_no_store_popped | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_update_next_cycle_true_when_store_popped | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStoreCommit::test_commit_stores_forwards_to_sq_store | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStoreSetIntegration::test_insert_load_calls_check_inst | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStoreSetIntegration::test_store_set_subblock_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestStoreSetIntegration::test_violation_trains_store_set | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSubBlocks::test_dtlb_probe_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSubBlocks::test_lq_core_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestSubBlocks::test_sq_store_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTLBI::test_tlbi_inv_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTLBI::test_tlbi_sync_comp_caller_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTLBISyncComp::test_tlbi_sync_comp_fires_after_tlbi_inv_resolves | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTranslationFault::test_no_fault_load_proceeds_normally | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTranslationFault::test_translation_fault_load_completes_with_fault | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTranslationFault::test_translation_fault_load_no_dcache_req | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTranslationFault::test_translation_fault_store_completes_with_fault | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_commit_stores_sets_canwb | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_parent_sq_commit_wired_to_commit_stores | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_store_writeback_not_directly_called | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_two_stage_pipeline_commit_then_writeback | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestVaddrPropagation::test_execute_load_passes_vaddr_to_lq_insert | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestVaddrPropagation::test_execute_store_passes_vaddr_to_sq_insert | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestViolationAckParent::test_violation_ack_exists_on_parent | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestViolationAckParent::test_violation_ack_forwards_to_lq_core | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_execute_load_activates_dtlb_probe_in_flight | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_execute_load_inserts_into_lq_via_wiring | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_execute_store_activates_dtlb_probe_in_flight | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_execute_store_inserts_into_sq_via_wiring | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_lsq_execute_resp_delivered_with_separate_args | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_store_set_violation_delivered_with_separate_args | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_violation_signal_aliased_to_lq_core | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_violation_signal_delivered_with_separate_args | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestExecuteLoadAcceptsClusterArgs::test_execute_load_accepts_cluster_id_kwarg | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestExecuteLoadAcceptsClusterArgs::test_execute_load_defaults_cluster_args_to_zero | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestExecuteLoadAcceptsClusterArgs::test_execute_load_writes_cluster_id_to_lq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestFuRealCompletePort::test_fu_real_complete_caller_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestFuRealCompletePort::test_fu_real_complete_is_callable | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestNormalLDACompletionFiresFuRealComplete::test_normal_lda_fires_fu_real_complete_on_dcache_resp | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestNormalLDACompletionFiresFuRealComplete::test_normal_lda_no_fu_real_complete_before_dcache_resp | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestSquashedLDAFastPathQ13::test_squashed_lda_does_not_wait_for_dcache | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestSquashedLDAFastPathQ13::test_squashed_lda_fires_fu_real_complete_immediately | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestSquashedLDAFastPathQ13::test_squashed_lda_no_duplicate_fu_real_complete_at_completion | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestTranslationFaultLDAFiresFuRealComplete::test_translation_fault_lda_fires_fu_real_complete | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_hit_cancel_l2.TestLSQParentL1HitCancelsL2::test_l1_hit_does_not_push_to_l2_shift_register | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_hit_cancel_l2.TestLSQParentL1HitCancelsL2::test_l1_miss_pushes_to_l2_shift_register | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_miss_nack.TestLSQParentL1MissFiresNack::test_l1_hit_does_not_fire_fu_nack | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_miss_nack.TestLSQParentL1MissFiresNack::test_l1_miss_fires_fu_nack | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_miss_nack.TestLSQParentL1MissFiresNack::test_translation_fault_does_not_fire_fu_nack | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentExecuteLoadPushesToL1ShiftRegister::test_execute_load_pushes_cluster_id_and_iq_local_id | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentExecuteLoadPushesToL1ShiftRegister::test_predicated_execute_load_does_not_push | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentExecuteLoadPushesToL1ShiftRegister::test_squashed_execute_load_does_not_push | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentL1ShiftRegisterParamForwarding::test_lsq_parent_accepts_l1_hit_lat_kwarg | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentL1ShiftRegisterParamForwarding::test_lsq_parent_accepts_l2_hit_lat_kwarg | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentL1ShiftRegisterParamForwarding::test_lsq_parent_default_l1_hit_lat_matches_params | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentL1ShiftRegisterPopFires::test_pop_fires_fu_early_complete_with_pushed_payload | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l2_push.TestLSQParentL2ShiftRegisterPopFires::test_pop_fires_fu_early_complete_with_pushed_payload | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l2_push.TestLSQParentTranslateResultPushesL2::test_translate_result_pushes_to_l2_shift_register | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l2_push.TestLSQParentTranslateResultPushesL2::test_translation_fault_does_not_push_to_l2 | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestNormalLDACompletionFiresSbSetReg::test_normal_lda_fires_sb_setreg_on_dcache_resp | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestNormalLDACompletionFiresSbSetReg::test_normal_lda_no_sb_setreg_before_dcache_resp | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestSbSetRegInterface::test_sb_setreg_caller_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestSbSetRegInterface::test_sb_setreg_is_callable | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestSquashedLDAFastPathSuppressesSbSetReg::test_squashed_lda_does_not_fire_sb_setreg | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestSquashedLDAFastPathSuppressesSbSetReg::test_squashed_lda_still_fires_fu_real_complete | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestTranslationFaultLDAFiresSbSetReg::test_translation_fault_lda_fires_sb_setreg | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_early_complete_alias_shares_lq_core_object | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_early_complete_is_callable | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_early_complete_port_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_nack_alias_shares_lq_core_object | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_nack_is_callable | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_nack_port_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL1::test_squash_clears_l1_shift_reg_slot_silent_pop | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL1::test_squash_does_not_fire_and_clears_l1_slot | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL2::test_squash_clears_l2_shift_reg_slot_silent_pop | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL2::test_squash_does_not_fire_and_clears_l2_slot | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckNegativeCases::test_squash_walks_only_matching_seqnum | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckNegativeCases::test_squash_with_empty_shift_regs_does_not_fire | block-LSQParent | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_backward_ctrl_in_forwards_to_commit | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_rename_to_iew_accessible | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_rob_empty_reaches_rename | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_squash_reaches_rename | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_squash_seqnum_reaches_rename | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_commit_reset_running | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_exported_interfaces_exist | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_nested_sub_blocks_exist | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_rename_reset_idle | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_rob_reset_empty | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_sub_blocks_exist | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestEndToEndRenameCommit::test_decode_from_forwards_to_rename | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestEndToEndRenameCommit::test_rob_commit_connection_exists | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestEndToEndRenameCommit::test_rob_insert_via_rename | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestSquashRecovery::test_fip_write_connection | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestSquashRecovery::test_iew_squash_sets_commit_rob_squashing | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestSquashRecovery::test_iew_squash_sets_commit_squash | block-O3Control | PASS | - | 0 |
| test_o3_control_cl.TestSquashRecovery::test_squash_walk_bridge_initiated | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestBackwardBus::test_backward_ctrl_in_merges_to_output | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestBackwardBus::test_free_rob_entries_on_backward_bus | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestBackwardBus::test_rob_empty_on_backward_bus | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestCommitFlow::test_commit_frees_phys_reg | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestCommitFlow::test_commit_retires_instruction | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestCommitFlow::test_done_seqnum_on_backward_bus | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestFIPWrite::test_fip_write_connection_active | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestFIPWrite::test_fip_write_reaches_commit | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestFaultTrap::test_fault_sets_trap_pending | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestFaultTrap::test_trap_triggers_cpu_trap_call | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestNonSpeculative::test_non_spec_broadcasts_seqnum | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestNonSpeculative::test_non_spec_clears_can_commit | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestROBInsert::test_multi_inst_insert | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestROBInsert::test_rename_inserts_into_rob | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestRenamePipeline::test_multi_inst_rename_bundle | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestRenamePipeline::test_nop_renamed_to_iew_output | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestRenamePipeline::test_rename_advances_running_state | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestRenamePipeline::test_rename_to_iew_receives_output | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestSMT::test_two_thread_rename | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestSerializeBlock::test_block_signal_affects_rename | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestSerializeBlock::test_serialize_before_stall | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_iew_squash_reaches_commit | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_iew_squash_sets_bc_rename_squash | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_squash_reaches_rename_via_backward_bus | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_squash_walk_bridge_activated | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_squash_with_instructions_in_flight | block-O3Control | PASS | - | 0 |
| test_o3_control_e2e.TestWBUpdate::test_wb_sets_completed | block-O3Control | PASS | - | 0 |
| test_phys_reg_file_cl.TestCCClassOmission::test_cc_class_omitted_when_zero | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestCCClassOmission::test_cc_class_present_when_nonzero | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestCCClassOmission::test_cc_read_returns_zero_when_omitted | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestDuplicateIndexAssertion::test_duplicate_index_different_classes_ok | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestDuplicateIndexAssertion::test_duplicate_index_same_class_raises | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPerClassWritePortsParams::test_params_per_class_writeports | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPerClassWritePortsParams::test_write_ports_match_constructed_methods | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_read_req_dataclass | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_read_resp_dataclass | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_read_resp_default_ready_asserted | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_write_port_dataclass_default | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_write_port_dataclass_set_fields | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegIdAndClassEnum::test_physreg_id_class_index_roundtrip | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegIdAndClassEnum::test_reg_class_enum_encoding | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestReadRegCombinational::test_read_each_class_returns_zero_after_reset | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestReadRegCombinational::test_read_reg_rdy_permanently_asserted | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestReadRegCombinational::test_read_returns_zero_after_reset | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestResetClearsPending::test_reset_clears_pending | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestResetClearsPending::test_reset_clears_pending_each_class | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestTiming::test_chained_writes_each_cycle | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestTiming::test_read_latency_zero_cycles | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestTiming::test_write_latency_one_cycle | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_multi_port_write_same_cycle | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_overwrite_via_two_writes | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_per_class_isolation | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_write_to_each_class | block-PhysRegFile | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_write_visible_next_cycle_not_same_cycle | block-PhysRegFile | PASS | - | 0 |
| test_rob_cl.TestClearCanCommit::test_clear_can_commit | block-ROB | PASS | - | 0 |
| test_rob_cl.TestClearCanCommit::test_clear_then_wb_reasserts | block-ROB | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_max_entries_dynamic | block-ROB | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_max_entries_partitioned | block-ROB | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_reset_done_squashing_true | block-ROB | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_reset_head_tail_count_zero | block-ROB | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_reset_rob_status_idle | block-ROB | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_reset_youngest_seqnum_zero | block-ROB | PASS | - | 0 |
| test_rob_cl.TestFSM::test_idle_to_running | block-ROB | PASS | - | 0 |
| test_rob_cl.TestFSM::test_running_to_squashing | block-ROB | PASS | - | 0 |
| test_rob_cl.TestFSM::test_squashing_to_running | block-ROB | PASS | - | 0 |
| test_rob_cl.TestFindBySeqNum::test_find_existing | block-ROB | PASS | - | 0 |
| test_rob_cl.TestFindBySeqNum::test_find_not_found | block-ROB | PASS | - | 0 |
| test_rob_cl.TestFreeEntryQuery::test_free_entries | block-ROB | PASS | - | 0 |
| test_rob_cl.TestFreeEntryQuery::test_is_empty | block-ROB | PASS | - | 0 |
| test_rob_cl.TestFreeEntryQuery::test_is_full | block-ROB | PASS | - | 0 |
| test_rob_cl.TestHeadRead::test_head_read_empty | block-ROB | PASS | - | 0 |
| test_rob_cl.TestHeadRead::test_head_read_returns_oldest | block-ROB | PASS | - | 0 |
| test_rob_cl.TestHeadRead::test_head_ready_reflects_can_commit | block-ROB | PASS | - | 0 |
| test_rob_cl.TestInsert::test_insert_ack_combinational | block-ROB | PASS | - | 0 |
| test_rob_cl.TestInsert::test_insert_updates_youngest_seqnum | block-ROB | PASS | - | 0 |
| test_rob_cl.TestInsert::test_insert_when_full | block-ROB | PASS | - | 0 |
| test_rob_cl.TestInsert::test_multi_slot_insert | block-ROB | PASS | - | 0 |
| test_rob_cl.TestInsert::test_single_insert | block-ROB | PASS | - | 0 |
| test_rob_cl.TestLayerSeparation::test_next_rob_entries_not_aliased_to_state_after_tick | block-ROB | PASS | - | 0 |
| test_rob_cl.TestLayerSeparation::test_next_rob_entries_outer_list_independent | block-ROB | PASS | - | 0 |
| test_rob_cl.TestRetire::test_retire_count_actual | block-ROB | PASS | - | 0 |
| test_rob_cl.TestRetire::test_retire_multiple | block-ROB | PASS | - | 0 |
| test_rob_cl.TestRetire::test_retire_single | block-ROB | PASS | - | 0 |
| test_rob_cl.TestRetire::test_retire_squashed_drains | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSMTArbitration::test_dynamic_multi_thread | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSMTArbitration::test_partitioned_capacity | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_done_signal | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_empty_fast_path | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_marks_entries | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_new_request_restarts | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_no_head_tail_count_change | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_updates_youngest_seqnum | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquash::test_thread_exiting_override | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquash::test_youngest_seqnum_squash_overrides_insert | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_cmt_fip_full_stall | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_walk_abort | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_walk_done_with_last_beat | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_walk_fields | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_walk_youngest_to_oldest | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_ckpt_metadata_save_restore | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_ckpt_restore_falls_back_to_head_ptr | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_ckpt_save_reset_to_zero | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_insert_stores_allocated_new | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_abort_superseding | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_cmt_fip_full_stalls_phase3_only | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_empty_rob_fast_path | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_phase2_replay | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_phase3_free | block-ROB | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_simultaneous | block-ROB | PASS | - | 0 |
| test_rob_cl.TestWBUpdate::test_wb_discarded_if_squashed | block-ROB | PASS | - | 0 |
| test_rob_cl.TestWBUpdate::test_wb_fault_stored | block-ROB | PASS | - | 0 |
| test_rob_cl.TestWBUpdate::test_wb_set_can_commit | block-ROB | PASS | - | 0 |
| test_rob_cl.TestWBUpdate::test_wb_set_completed | block-ROB | PASS | - | 0 |
| test_read_operand_cl.TestFromIQ::test_fromiq_rdy_false_when_pending | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestFromIQ::test_fromiq_rdy_when_empty | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestFromIQ::test_fromiq_stores_request | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestIcDrainHandling::test_ic_drain_port_exists | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestIcDrainHandling::test_ic_drain_reset_clears_state | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestIcDrainHandling::test_ic_drain_skips_slot_for_drained_thread | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_csr_read_port_exists | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_direct_complete_port_exists | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_fromiq_port_exists | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_fu_operand_port_exists | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_ic_drain_port_exists | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_rf_read_port_exists | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_ro_inst_issued_port_exists | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_create_load_factory_accepts_cluster_id_iq_local_id | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_lsq_execute_resp_has_cluster_id_field | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_lsq_execute_resp_has_iq_local_id_field | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_lsq_execute_resp_to_fu_complete_bundle_forwards_cluster_id | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_lsq_execute_resp_to_fu_complete_bundle_forwards_iq_local_id | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_calls_direct_complete | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_calls_ro_inst_issued | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_check_before_fault | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_check_before_predicate_false | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_skips_fupool | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestPreExecFaultShortCircuit::test_no_fault_proceeds_to_fupool | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestPreExecFaultShortCircuit::test_nonmem_fault_calls_direct_complete | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestPreExecFaultShortCircuit::test_nonmem_fault_calls_ro_inst_issued | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestPreExecFaultShortCircuit::test_nonmem_fault_skips_fupool | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestPredicateFalseShortCircuit::test_predicate_false_calls_direct_complete | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestPredicateFalseShortCircuit::test_predicate_false_calls_ro_inst_issued | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestPredicateFalseShortCircuit::test_predicate_false_skips_fupool | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestPredicateFalseShortCircuit::test_predicate_true_proceeds_to_fupool | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestProcessing::test_no_handoff_without_fromiq | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestProcessing::test_process_clears_state_after_tick | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestROInstIssuedProducer::test_ro_inst_issued_called_for_squashed | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestROInstIssuedProducer::test_ro_inst_issued_called_with_tid | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestReset::test_after_reset_drain_state_cleared | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestReset::test_after_resetpending_fromiq_is_none | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestReset::test_after_resetstate_fromiq_is_none | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestRfReadWiring::test_rfread_called_for_each_source_operand | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestSquashedBypass::test_squashed_still_handed_off | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_direct_complete_bundle_carries_cluster_id_iq_local_id | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_read_operand_populates_cluster_id_default_when_absent | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_read_operand_populates_cluster_id_from_inst | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_read_operand_populates_iq_local_id_from_inst | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_wbinfo_has_cluster_id_field | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_wbinfo_has_iq_local_id_field | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoExtraction::test_fu_operand_req_carries_wbinfo | block-ReadOperand | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoExtraction::test_wbinfo_dest_phys_reg_defaults_to_zero | block-ReadOperand | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestDirectComplete::test_direct_complete_called_for_fault | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestHandoff::test_fu_operand_called_after_read | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestHandoff::test_squashed_still_handed_off | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestOperandRead::test_rf_read_called_for_sources | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestReceiveIssue::test_fromiq_rdy_when_not_full | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestReceiveIssue::test_fromiq_stores_request | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestWBInfoConstruction::test_wbinfo_has_dest_phys_reg | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryCalledPerSourceReg::test_bypass_query_called_for_each_source | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryHitUsesBypassValue::test_bypass_query_hit_uses_bypass_value | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryHitUsesBypassValue::test_bypass_query_miss_uses_rf_read_value | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_caller_ifc_exists | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_is_callable | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryPrecedence::test_bypass_query_hit_suppresses_rf_read | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryPrecedence::test_bypass_query_partial_hit_suppresses_only_hit_sources | block-ReadOperandInt | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_lda_calls_fu_operand | block-ReadOperandMem | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_none_uop_calls_fu_operand | block-ReadOperandMem | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_sta_calls_fu_operand | block-ReadOperandMem | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_calls_lsq_execute_store_data | block-ReadOperandMem | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_does_not_call_fu_operand | block-ReadOperandMem | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_passes_inst_list_idx_zero | block-ReadOperandMem | PASS | - | 0 |
| test_free_list_cl.TestAllocFreeSameCycle::test_alloc_does_not_see_same_cycle_free | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_alloc_advances_head | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_alloc_from_empty_class | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_multi_slot_alloc_same_class | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_per_class_isolation | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_single_alloc | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestBugFixes::test_alloc_empty_class_returns_invalid | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestBugFixes::test_count_single_write_alloc_and_free_same_cycle | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestBugFixes::test_free_pushes_to_correct_class | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestCapacitySignals::test_empty_flag_after_draining_class | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestCapacitySignals::test_empty_flag_false_when_class_has_regs | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestCapacitySignals::test_empty_flag_when_class_empty | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestConstructionAndReset::test_reset_count_matches_phys_regs | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestConstructionAndReset::test_reset_head_tail | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestConstructionAndReset::test_reset_loads_all_phys_regs | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestReclamation::test_free_cc_class_is_noop | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestReclamation::test_free_then_alloc_fifo_order | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestReclamation::test_single_free | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_alloc_more_than_available | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_circular_buffer_wraparound | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_circular_buffer_wrapping | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_mixed_class_multi_alloc | block-Rename | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_multiple_allocs_in_order | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointSaveTrigger::test_cond_branch_high_confidence_skips_save | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointSaveTrigger::test_cond_branch_triggers_checkpoint_save | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointSaveTrigger::test_indirect_branch_triggers_checkpoint_save | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointSaveTrigger::test_interval_counter_increments_on_rename | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointState::test_branch_confidence_high_default_false | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointState::test_ckpt_state_reset | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005ForwardReplay::test_allocated_new_false_skips_fip_write | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005ForwardReplay::test_phase3_walk_triggers_fip_write | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005SquashRecovery::test_squash_exits_on_both_walks_done | block-Rename | PASS | - | 0 |
| test_rename_cl.TestADR0005SquashRecovery::test_walk_done_flags_reset_on_squash | block-Rename | PASS | - | 0 |
| test_rename_cl.TestBlockUnblock::test_block_on_iq_full | block-Rename | PASS | - | 0 |
| test_rename_cl.TestBlockUnblock::test_block_on_rob_full | block-Rename | PASS | - | 0 |
| test_rename_cl.TestBlockUnblock::test_unblock_when_resources_available | block-Rename | PASS | - | 0 |
| test_rename_cl.TestCombinationalOccupancyReadback::test_comb_occupancy_readback_default_true | block-Rename | PASS | - | 0 |
| test_rename_cl.TestCombinationalOccupancyReadback::test_comb_occupancy_readback_false | block-Rename | PASS | - | 0 |
| test_rename_cl.TestConstructionAndReset::test_rename_map_initialized | block-Rename | PASS | - | 0 |
| test_rename_cl.TestConstructionAndReset::test_reset_empty_queues | block-Rename | PASS | - | 0 |
| test_rename_cl.TestConstructionAndReset::test_reset_no_block_signals | block-Rename | PASS | - | 0 |
| test_rename_cl.TestConstructionAndReset::test_reset_status_idle | block-Rename | PASS | - | 0 |
| test_rename_cl.TestFIPBackPressure::test_fip_back_pressure_stalls_walk | block-Rename | PASS | - | 0 |
| test_rename_cl.TestFIPBackPressure::test_fip_clear_on_new_squash | block-Rename | PASS | - | 0 |
| test_rename_cl.TestFIPBackPressure::test_fip_full_reset_false | block-Rename | PASS | - | 0 |
| test_rename_cl.TestFIPBackPressure::test_fip_full_set_on_walk | block-Rename | PASS | - | 0 |
| test_rename_cl.TestMultiInstructionRename::test_intra_bundle_dependency | block-Rename | PASS | - | 0 |
| test_rename_cl.TestMultiInstructionRename::test_two_instructions_same_cycle | block-Rename | PASS | - | 0 |
| test_rename_cl.TestNormalRename::test_instruction_with_source_reg | block-Rename | PASS | - | 0 |
| test_rename_cl.TestNormalRename::test_nop_instruction | block-Rename | PASS | - | 0 |
| test_rename_cl.TestNormalRename::test_single_instruction_rename | block-Rename | PASS | - | 0 |
| test_rename_cl.TestShadowCounters::test_cached_state_reset | block-Rename | PASS | - | 0 |
| test_rename_cl.TestShadowCounters::test_shadow_counters_reset_zero | block-Rename | PASS | - | 0 |
| test_rename_cl.TestSkidBuffer::test_blocked_instruction_goes_to_skid | block-Rename | PASS | - | 0 |
| test_rename_cl.TestSquashRecovery::test_squash_clears_queues | block-Rename | PASS | - | 0 |
| test_rename_cl.TestSquashRecovery::test_squash_seqnum_captured | block-Rename | PASS | - | 0 |
| test_rename_cl.TestSquashRecovery::test_squash_sets_squashing_state | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCanRename::test_can_rename_fails_when_empty | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCanRename::test_can_rename_when_free_regs_available | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestore::test_restore_done_pulse | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestore::test_restore_returns_to_saved_state | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestoreCAMLookup::test_checkpoint_restore_cam_lookup | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestoreCAMLookup::test_checkpoint_restore_invalidates_younger | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestoreCAMLookup::test_checkpoint_restore_no_match | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointSave::test_save_captures_spec_map | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointSaveMetadata::test_checkpoint_save_done_pulse | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointSaveMetadata::test_checkpoint_save_stores_metadata | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCircularNextFreeAllocation::test_circular_next_free_slot_allocation | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCommitSetEntry::test_commit_updates_arch_map_only | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCommitSetEntry::test_non_commit_updates_spec_only | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestCommitSetReqOldPhysReg::test_commit_set_req_returns_old_phys_reg | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestConstructionAndReset::test_arch_map_initialized | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestConstructionAndReset::test_spec_arch_map_match_after_reset | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestConstructionAndReset::test_spec_map_initialized | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestForwardReplayPhase2::test_forward_replay_phase2_set_entry | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestIntraBundleBypass::test_inst1_source_sees_inst0_dest_rename | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestMiscReg::test_misc_reg_identity_mapping | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestMiscReg::test_misc_reg_rename_returns_identity | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestPinnedWrites::test_pin_count_zero_allocates_normally | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestPinnedWrites::test_pin_counter_not_decremented_in_cl | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestPinnedWrites::test_pinned_register_reuses_mapping | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestRenameBundle::test_basic_lookup | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestRenameBundle::test_basic_rename | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestSetEntry::test_set_entry_updates_spec_map_only | block-Rename | PASS | - | 0 |
| test_sq_store_cl.TestADR0019Ports::test_dcache_store_pa_req_caller_ifc_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestADR0019Ports::test_dcache_store_pa_req_fires_on_writeback | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestADR0019Ports::test_dcache_store_write_removed | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestBarrierFence::test_is_release_flag_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestBitFieldTagScheme::test_cfg_tag_n_field_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_includes_tag | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_tag_value_idx0 | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_tag_value_idx1 | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_clean_writeback | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_excluded_from_forwarding | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_flush_writeback | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_no_violation_scan_on_translated | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_participates_in_tso | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_two_stage_writeback_path | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_type_field_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_zero_writeback | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_dcache_store_write_carries_cbo_type | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_insert_accepts_cbo_type | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_normal_store_cbo_type_zero | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestCacheMaintenance::test_cache_maintenance_flag_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_broadcast_fires_even_without_dependents_bits | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_broadcast_fires_on_executed_fsm_with_dependents | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_broadcast_one_shot_does_not_refire | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_broadcast_passes_sq_idx_and_bitvector | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_cfg_lq_size_param_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_default_cfg_lq_size_is_32 | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_dependents_broadcast_caller_ifc_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_insert_clears_dependents_and_broadcast_flag | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_sq_entry_has_dependents_broadcast_flag | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_sq_entry_has_dependents_field | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_has_stores_to_wb_false_after_drain | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_has_stores_to_wb_false_when_empty | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_has_stores_to_wb_true_when_stores_pending | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_normal_store_not_blocked_by_sq_head | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_release_store_blocked_while_a_in_flight | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_release_store_fires_after_batch_pop | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_sc_store_fires_after_batch_pop | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_state_stores_to_wb_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestForwardQuery::test_forward_full_coverage_hit | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestForwardQuery::test_forward_no_match | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestForwardQuery::test_forward_partial_coverage | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestForwardingCAMMatrix::test_atomic_store_no_forward | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestForwardingCAMMatrix::test_zero_fill_forward | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestInsert::test_insert_adds_entry | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestInsert::test_insert_advances_tail | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestInterfaces::test_callee_ports_exist | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestInterfaces::test_caller_ports_exist | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_is_data_prefetch_field_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_normal_store_still_sends_to_dcache | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_prefetch_does_not_set_storeInFlight | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_prefetch_store_skips_dcache | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_zero_size_store_skips_dcache | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM5StoreBackpressure::test_blocked_store_retries_same_packet | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM5StoreBackpressure::test_isStoreBlocked_resets | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM5StoreBackpressure::test_store_blocked_when_dcache_not_ready | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestM5StoreBackpressure::test_store_unblocks_when_dcache_ready | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_construct_accepts_max_threads_param | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_default_max_threads_is_one_backward_compat | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_insert_both_threads_independent | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_insert_tid0_uses_partition0 | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_insert_tid1_uses_partition1 | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_insert_defaults_non_spec_false | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_insert_sets_non_spec_true | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_sq_entry_has_non_spec_field | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_up_once_store_translated_proceeds_when_non_spec_cleared | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_up_once_store_translated_proceeds_when_non_spec_false | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_up_once_store_translated_skipped_when_non_spec | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestPartialForwardStallSeqnum::test_forward_query_returns_6_tuple_on_partial | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestPartialForwardStallSeqnum::test_forward_query_returns_zero_seqnum_on_full_hit | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestPartialForwardStallSeqnum::test_forward_query_returns_zero_seqnum_on_no_match | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestPerFragmentViolationCheck::test_split_store_triggers_violation_check_twice | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestReset::test_after_reset_all_empty | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestReset::test_after_reset_fsm_idle | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestReset::test_after_reset_head_tail_zero | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSCLR::test_reservation_registers_exist | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSCLR::test_sc_failure_completes_without_write | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSCLR::test_set_reservation_method_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_has_stale_method_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_sq_entry_has_stale_translation_field | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_sq_entry_has_vaddr_field | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_stale_store_triggers_translate_req | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_tlbi_inv_callee_ifc_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_tlbi_inv_marks_inflight_store_stale | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_translate_req_caller_ifc_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreClearReservation::test_clear_reservation_callee_ifc_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreClearReservation::test_clear_reservation_clears_state | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreClearReservation::test_clear_reservation_mismatched_addr_no_clear | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSetPhysAddr::test_set_phys_addr_sets_eff_addr_valid | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreNonForwardable::test_split_store_skipped_by_forward_query | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreWriteback::test_split_store_completion_requires_both_acks | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreWriteback::test_split_store_issues_two_dcache_reqs | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreWriteback::test_split_store_marks_committed_on_writeback | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreWriteback::test_split_store_sets_storeInFlight_on_writeback | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_batch_pop_multiple_consecutive_completed | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_batch_pop_respects_writeback_width | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_batch_pop_single_completed_entry | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_batch_pop_stops_at_non_completed | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_retire_store_removed | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_store_complete_batch_pop_in_up_clear_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteNotify::test_store_complete_fires_notify_with_head_seqnum | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteNotify::test_store_complete_notify_caller_ifc_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_completed_not_set_at_send_time | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_split_store_complete_requires_both_acks | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_split_store_pending_flags_only_after_both_acks | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_accepts_sq_idx_and_is_frag1 | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_sets_completed | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_sets_pending_flags_only_on_completion | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestStoreTranslatedContinuation::test_translated_to_executed | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestTwoStageWriteback::test_canwb_set_by_commit_stores | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestTwoStageWriteback::test_storeInFlight_register_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestTwoStageWriteback::test_storeWBIt_iterator_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestTwoStageWriteback::test_storesToWB_counter_exists | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_canWB_store_sent_to_dcache_autonomously | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_non_canWB_store_not_sent | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_storeInFlight_blocks_second_store | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_store_complete_allows_next_store | block-SQStore | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_store_complete_clears_storeInFlight | block-SQStore | PASS | - | 0 |
| test_scoreboard_cl.TestDesignParams::test_misc_base_after_renameable | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestDesignParams::test_num_phys_regs_total | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestIntraGroupRAW::test_earlier_unset_makes_getReg_return_0_same_cycle | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestIsAlwaysReady::test_misc_reg_always_ready_after_unset | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestIsAlwaysReady::test_misc_reg_getReg_returns_1 | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestIsAlwaysReady::test_misc_reg_setReg_no_op | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestLifecycle::test_squash_recovery_reverses_busy_to_ready | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestLifecycle::test_unset_then_set_lifecycle | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestMethodExistence::test_getReg_methods_exist_for_all_slots | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestMethodExistence::test_setRegSquash_methods_exist_for_all_slots | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestMethodExistence::test_setReg_methods_exist_for_all_slots | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestMethodExistence::test_unsetReg_methods_exist_for_all_slots | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestMultiSlotPositional::test_each_squash_slot_writes_unique_pending_entry | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestMultiSlotPositional::test_each_unset_slot_writes_unique_pending_entry | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestMultiSlotPositional::test_each_wb_slot_writes_unique_pending_entry | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestMultipleReads::test_multiple_getReg_calls_same_cycle | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestNoWBBypass::test_getReg_does_not_see_wb_set_same_cycle | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestPendingSizing::test_pending_sq_set_sized_to_squash_width_x_max_dest_regs | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestPendingSizing::test_pending_unset_sized_to_max_rename_width_x_max_dest_regs | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestPendingSizing::test_pending_wb_set_sized_to_wb_width_x_max_dest_regs | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestReset::test_after_reset_all_bits_ready | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestReset::test_reset_clears_all_pending | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_clears_all_pending_buffers | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_clears_pending_after_commit | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_is_callee_ifc_cl | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_rdy_always_true | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_sets_pending_flag | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_valid_sets_all_bits_to_1 | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestSetReg::test_set_visible_next_cycle | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestSetRegSquashBypass::test_squash_set_same_cycle_getReg_bypass | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestUnsetReg::test_unset_visible_next_cycle_not_same_cycle | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestWritePortPriority::test_squash_overrides_unset | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl.TestWritePortPriority::test_unset_overrides_wb | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_bypass_overrides_stale_state | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_global_id_zero_is_valid_when_not_ready | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_returns_committed_value_when_not_ready | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_returns_ready_after_reset | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_same_cycle_bypass | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestInterfaceExistence::test_get_producer_port_exists | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestInterfaceExistence::test_set_producer_port_exists | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestPendingSetProducerBuffer::test_pending_cleared_after_tick | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestPendingSetProducerBuffer::test_pending_set_producer_exists | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestPendingSetProducerBuffer::test_set_producer_buffers_to_pending | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestProducerIdInit::test_state_producer_id_all_zero_after_reset | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestProducerIdInit::test_state_producer_id_exists | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestResetClearsProducerId::test_sb_reset_clears_producer_id | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestResetClearsProducerId::test_sim_reset_clears_producer_id | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetProducer::test_set_producer_not_visible_same_cycle | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetProducer::test_set_producer_overwrites_previous | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetProducer::test_set_producer_visible_next_cycle | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetRegClearsProducerId::test_set_reg_clears_producer_id | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetRegClearsProducerId::test_wb_set_req_clears_producer_id | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetRegSquashClearsProducerId::test_set_reg_squash_clears_producer_id | block-Scoreboard | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestUnsetRegPreservesProducerId::test_unset_reg_preserves_producer_id | block-Scoreboard | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_alloc_returns_index | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_alloc_until_full | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_get_by_index | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_get_oldest_returns_head | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_is_full_and_empty | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_release_head_fifo | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_combined_with_alloc | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_empty_list | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_head_as_new_head | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_mid_list | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_no_capacity | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_preserves_other_thread | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_reserves_but_does_not_write | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_tail | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerMultiThread::test_multi_thread_isolation | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerMultiThread::test_thread_independent_heads | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerMultiThread::test_thread_reset_isolated | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPendingAllocs::test_alloc_prevents_double_reservation | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPendingAllocs::test_alloc_reserves_but_does_not_write | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPendingAllocs::test_is_full_accounts_for_reserved | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPendingAllocs::test_reset_clears_pending | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPowerOfTwoConstraint::test_non_power_of_two_raises | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPowerOfTwoConstraint::test_power_of_two_ok | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerReset::test_reset_clears_all | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerReset::test_reset_tid_none | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerSquash::test_squash_to_bulk | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerSquash::test_squash_to_head_keeps_all | block-StorageManager | PASS | - | 0 |
| test_storage_manager.TestStorageManagerSquash::test_squash_to_invalid_anchor_asserts | block-StorageManager | PASS | - | 0 |
| test_store_set_cl.TestCheckInst::test_check_inst_no_prediction_after_reset | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestCheckInst::test_check_inst_no_prediction_after_training_only | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestCheckInst::test_check_inst_returns_producer_after_training | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestClearCounter::test_ssit_cleared_at_threshold | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestPopulateLfst::test_populate_lfst_accumulates_multiple | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestPopulateLfst::test_populate_lfst_callee_ifc_exists | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestPopulateLfst::test_populate_lfst_updates_lfst | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestReset::test_clearcounter_zero_after_reset | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestReset::test_lfst_all_invalid_after_reset | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestReset::test_ssit_all_invalid_after_reset | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestReset::test_storelist_empty_after_reset | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_callee_ifc_exists | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_invalidates_lfst_when_no_survivors | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_invalidates_younger_stores | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_noop_when_no_younger_stores | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestViolation::test_violation_callee_ifc_exists | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestViolation::test_violation_increments_clear_counter | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestViolation::test_violation_sets_ssit_entries | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestViolation::test_violation_two_distinct_storesets | block-StoreSet | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_cbo_inval_clean_flush_write_nothing | block-Testbench | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_cbo_zero_covers_block_lanes | block-Testbench | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_empty_pending_returns_none | block-Testbench | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_exit_store_suppressed_from_overlay | block-Testbench | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_lane_merge_partial_stores_youngest_wins_with_memory_fallback | block-Testbench | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_no_intersection_returns_none | block-Testbench | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_store_crossing_word_boundary_splits_across_words | block-Testbench | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_younger_full_store_supersedes_older_partial | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_bne_not_taken_no_squash | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_double_beq_lifo_invalidation | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_jal_then_beq_uses_correct_checkpoint | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_jal_triggers_checkpoint_save | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_taken_beq_mispredict_restores_checkpoint | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationDebug::test_debug_bare_minimum_exit | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationDebug::test_debug_single_nop_then_exit | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationRunElf::test_run_elf_exit_nonzero | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationRunElf::test_run_elf_exit_zero | block-Testbench | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationRunElf::test_run_elf_nops_then_exit | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConfigurableLatency::test_mem_latency_2_delays_dcache_load_by_2_cycles | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConfigurableLatency::test_tlb_latency_1_default_delays_response_by_1_cycle | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConfigurableLatency::test_tlb_latency_2_delays_response_by_2_cycles | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_constructs_with_exit_addr | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_core_sub_component | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_elf_entry | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_exit_code | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_halted_flag | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_pages_memory_dict | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheLoadResponder::test_load_req_4byte_size | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheLoadResponder::test_load_req_returns_data_after_tick | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_req_writes_to_memory_after_tick | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_to_exit_addr_captures_exit_code | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_to_exit_addr_does_not_write_memory | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_to_exit_addr_halts_testbench | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_to_exit_addr_still_acks_store | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestELFLoading::test_load_elf_multiple_segments | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestELFLoading::test_load_elf_populates_memory_from_pt_load_segment | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestELFLoading::test_load_elf_sets_elf_entry | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestICacheFetchResponder::test_icache_req_fault_for_address_outside_loaded_range | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestICacheFetchResponder::test_icache_req_fault_on_unloaded_address | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestICacheFetchResponder::test_icache_req_no_fault_for_loaded_range | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestICacheFetchResponder::test_icache_req_returns_instruction_data_after_tick | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestIdentityTLB::test_dtlb_req_returns_identity_paddr_after_one_tick | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestIdentityTLB::test_dtlb_resp_uses_identity_translation | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestInitialPC::test_cfg_initial_pc_sets_bac_pc | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestInitialPC::test_cfg_initial_pc_sets_commit_state_pc | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestInitialPC::test_get_pc_returns_cfg_initial_pc | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_load_elf_segment_populates_memory | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_load_elf_segment_zero_fills_bss | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_load_segment_spans_multiple_pages | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_read_uninitialized_page_allocates_page | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_read_uninitialized_page_returns_zero | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_write_byte_boundary | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_write_does_not_corrupt_adjacent_bytes | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_write_then_read_returns_value | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_write_to_uninitialized_page_allocates_page | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestRunElfFactory::test_run_elf_raises_timeout_when_no_exit_store | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestRunElfFactory::test_run_elf_returns_exit_code_on_halt | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestVAProbeCoordinator::test_va_probe_miss_when_no_pa_arrives | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestVAProbeCoordinator::test_va_probe_odd_cacheline_misses | block-Testbench | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestVAProbeCoordinator::test_va_probe_resp_fires_2_cycles_after_req | block-Testbench | PASS | - | 0 |
| test_riscv_tests_isa::test_riscv_tests_smoke_add | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-add:R-type addition] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addi:I-type add immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addiw:IW-type add immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addw:R-type add word] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-and:R-type AND] | block-Testbench | PASS | - | 10 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-andi:I-type AND immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-auipc:add upper immediate to PC] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-beq:branch equal] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bge:branch greater equal] | block-Testbench | PASS | - | 10 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bgeu:branch greater equal unsigned] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-blt:branch less than] | block-Testbench | PASS | - | 10 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bltu:branch less than unsigned] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bne:branch not equal] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-fence_i:instruction fence] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-jal:jump and link] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-jalr:jump and link register] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lb:load byte] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lbu:load byte unsigned] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-ld:load double] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lh:load half] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lhu:load half unsigned] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lui:load upper immediate] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lw:load word] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lwu:load word unsigned] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-or:R-type OR] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-ori:I-type OR immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sb:store byte] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sd:store double] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sh:store half] | block-Testbench | FAIL | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sll:shift left logical] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slli:shift left logical immediate] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sllw:shift left logical word] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slt:set less than] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slti:set less than immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sltiu:set less than immediate unsigned] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sltu:set less than unsigned] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sra:shift right arithmetic] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srai:shift right arithmetic immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sraw:shift right arithmetic word] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srl:shift right logical] | block-Testbench | PASS | - | 10 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srli:shift right logical immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srlw:shift right logical word] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sub:R-type subtraction] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-subw:R-type sub word] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sw:store word] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-xor:R-type XOR] | block-Testbench | PASS | - | 10 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-xori:I-type XOR immediate] | block-Testbench | PASS | - | 6 |
| test_tlbi_controller_cl.TestEdgeCases::test_second_tlbi_req_after_first_completes | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestEdgeCases::test_sync_comp_before_inv_sent_ignored_or_buffered | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestIntegrationWithLSQ::test_integration_controller_with_lsq | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestInvSent::test_inv_sent_after_in_flight | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestMultipleTids::test_multiple_tids_independent | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiComplete::test_no_spurious_complete_without_sync_comp | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiComplete::test_state_cleared_after_complete | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiComplete::test_tlbi_complete_after_sync_comp | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiReq::test_tlbi_req_committed_in_update_ff | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiReq::test_tlbi_req_does_not_fire_immediately | block-TlbiController | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiReq::test_tlbi_req_sets_pending | block-TlbiController | PASS | - | 0 |
| test_write_back_cl.TestBranchForwarding::test_mispredict_calls_wb_mispredict | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestBranchForwarding::test_no_mispredict_no_call | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestBranchForwarding::test_squashed_mispredict_not_forwarded | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestCSRWrite::test_csr_write_called_when_csr_write_valid_true | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestCSRWrite::test_csr_write_skipped_when_csr_write_valid_false | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestCSRWrite::test_squashed_csr_write_skipped | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestCSRWrite::test_wb_csr_write_port_exists | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestDecrWbOutstanding::test_normal_completion_ignores_decr_wb_outstanding | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_buffers_completion | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_calls_rf_write | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_decrements_counter | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_marks_slot_processed | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_port_exists | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_squashed_skips_rf_write | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFaultForwarding::test_fault_calls_wb_fault | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFaultForwarding::test_no_fault_no_call | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuComplete::test_fu_complete_buffers_into_pending | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuComplete::test_multiple_completions_buffered | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_construct_with_wbinfo | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_has_branch_fields | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_has_fault_fields | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_has_squashed_field | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_has_wbinfo_field | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_no_trap_fields | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_wbinfo_defaults_to_empty | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_after_reset_counter_is_zero | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_after_reset_squash_boundary_is_zero | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_fu_complete_decrements_counter | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_ic_squash_updates_boundary | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_ro_inst_issued_increments_counter | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_rf_write_called_with_two_individual_args | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_wb_csr_write_called_with_three_individual_args | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_wb_fault_called_with_three_individual_args | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_wb_mispredict_called_with_four_individual_args | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_wb_rob_update_called_with_single_wbtorobupdate_object | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestInterfaces::test_caller_ports_exist | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestInterfaces::test_fu_complete_callee_exists | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_lsq_rdy_false_when_buffer_full | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_lsq_rdy_recovers_after_process | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_lsq_rdy_true_when_buffer_has_space | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_lsq_rejected_when_rdy_false | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_squashed_completion_skips_rf_write | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestLSQExecuteResp::test_lsq_execute_resp_callee_exists | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestLSQExecuteResp::test_lsq_load_completion_calls_rf_write | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestLSQExecuteResp::test_lsq_store_completion_no_rf_write | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPendingWBQueue::test_fifo_order_preserved | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPendingWBQueue::test_pop_time_squash_with_writeback_width | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPendingWBQueue::test_writeback_width_does_not_drop_completions | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPendingWBQueue::test_writeback_width_limits_processing_per_cycle | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_class_of_phys_reg_helper | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_float_class_dest_routes_to_float_port | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_int_class_dest_routes_to_int_port | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_int_dest_does_not_route_to_float_port | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_multi_dest_different_classes_route_to_different_ports | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_two_int_dests_use_two_int_ports | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestProcessing::test_invalid_slot_skipped | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestProcessing::test_process_clears_after_next_tick | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestProcessing::test_process_marks_processed | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestROBUpdate::test_fault_forwarded_in_rob_update | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestROBUpdate::test_normal_completion_calls_wb_rob_update | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestROBUpdate::test_squashed_completion_skips_rob_update | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestReset::test_after_reset_all_slots_empty | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestReset::test_after_reset_next_slot_zero | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestRfWriteSetReg::test_multi_dest_completion_calls_rf_write_per_dest | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestRfWriteSetReg::test_normal_completion_calls_rf_write_with_dest_phys_reg | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestRfWriteSetReg::test_normal_completion_does_not_fire_sb_setreg | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestRfWriteSetReg::test_squashed_completion_skips_rf_write | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestSquashAtCompletion::test_seqnum_above_boundary_skips_rf_write | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_cleared_after_all_inflight_drained | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_not_cleared_while_completion_in_buffer | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_not_cleared_while_inflight_remaining | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestSquashedBypass::test_squashed_marks_slot_processed | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_construct_with_values | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_dest_phys_reg_defaults_to_zero | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_has_csr_num_field | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_has_csr_write_valid_field | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_has_dest_phys_reg_field | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_has_flags_field | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWritePortOverflowProtection::test_overflow_bypass_query_returns_hit_for_overflow_completion | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWritePortOverflowProtection::test_overflow_does_not_crash | block-WriteBack | PASS | - | 0 |
| test_write_back_cl.TestWritePortOverflowProtection::test_overflow_drops_excess_rf_write | block-WriteBack | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_misses_for_squashed_completion | block-WriteBack | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_port_exists | block-WriteBack | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_returns_hit_for_matching_phys_reg | block-WriteBack | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_returns_hit_for_second_dest | block-WriteBack | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_returns_miss_for_unknown_phys_reg | block-WriteBack | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_returns_miss_when_buf_empty | block-WriteBack | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestSbSetRegRemovedFromWriteBack::test_normal_completion_does_not_fire_sb_setReg | block-WriteBack | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestSbSetRegRemovedFromWriteBack::test_sb_setReg_caller_ifc_removed | block-WriteBack | PASS | - | 0 |
| hypervisor-p-2-stage_translation | p- | PASS | 1374 | 13 |
| hypervisor-p-2-stage_translation_implicit_load_error | p- | PASS | 1652 | 14 |
| hypervisor-p-2-stage_translation_implicit_load_error_hs | p- | PASS | 1827 | 16 |
| hypervisor-svadu-p-2-stage_translation_implicit_store_error | p- | PASS | 1768 | 15 |
| hypervisor-svadu-p-2-stage_translation_implicit_store_error_hs | p- | PASS | 1945 | 14 |
| rv64mi-p-breakpoint | p- | PASS | 3343 | 23 |
| rv64mi-p-csr | p- | PASS | 3467 | 24 |
| rv64mi-p-illegal | p- | TIMEOUT | - | 108 |
| rv64mi-p-instret_overflow | p- | PASS | 1252 | 10 |
| rv64mi-p-ld-misaligned | p- | PASS | 1386 | 11 |
| rv64mi-p-lh-misaligned | p- | PASS | 1102 | 9 |
| rv64mi-p-lw-misaligned | p- | PASS | 1171 | 9 |
| rv64mi-p-ma_addr | p- | PASS | 1538 | 12 |
| rv64mi-p-ma_fetch | p- | PASS | 1950 | 14 |
| rv64mi-p-mcsr | p- | PASS | 1342 | 11 |
| rv64mi-p-pmpaddr | p- | PASS | 1185 | 9 |
| rv64mi-p-sbreak | p- | PASS | 1315 | 10 |
| rv64mi-p-scall | p- | PASS | 1261 | 10 |
| rv64mi-p-sd-misaligned | p- | PASS | 1436 | 11 |
| rv64mi-p-sh-misaligned | p- | PASS | 1109 | 9 |
| rv64mi-p-sw-misaligned | p- | PASS | 1150 | 9 |
| rv64mi-p-zicntr | p- | PASS | 1439 | 11 |
| rv64mzicbo-p-zero | p- | PASS | 1160 | 10 |
| rv64si-p-csr | p- | PASS | 2277 | 16 |
| rv64si-p-dirty | p- | PASS | 2274 | 16 |
| rv64si-p-icache-alias | p- | PASS | 2372 | 17 |
| rv64si-p-ma_fetch | p- | PASS | 1382 | 11 |
| rv64si-p-sbreak | p- | PASS | 1325 | 10 |
| rv64si-p-scall | p- | PASS | 1443 | 11 |
| rv64si-p-wfi | p- | PASS | 1173 | 9 |
| rv64ssvnapot-p-napot | p- | PASS | 1658 | 13 |
| rv64ua-p-amoadd_d | p- | PASS | 1081 | 8 |
| rv64ua-p-amoadd_w | p- | PASS | 1120 | 9 |
| rv64ua-p-amoand_d | p- | PASS | 1121 | 9 |
| rv64ua-p-amoand_w | p- | PASS | 1117 | 9 |
| rv64ua-p-amomax_d | p- | PASS | 1077 | 9 |
| rv64ua-p-amomax_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amomaxu_d | p- | PASS | 1077 | 8 |
| rv64ua-p-amomaxu_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amomin_d | p- | PASS | 1077 | 8 |
| rv64ua-p-amomin_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amominu_d | p- | PASS | 1077 | 9 |
| rv64ua-p-amominu_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amoor_d | p- | PASS | 1117 | 10 |
| rv64ua-p-amoor_w | p- | PASS | 1117 | 9 |
| rv64ua-p-amoswap_d | p- | PASS | 1121 | 9 |
| rv64ua-p-amoswap_w | p- | PASS | 1117 | 9 |
| rv64ua-p-amoxor_d | p- | PASS | 1125 | 9 |
| rv64ua-p-amoxor_w | p- | PASS | 1129 | 9 |
| rv64ua-p-lrsc | p- | PASS | 19229 | 120 |
| rv64uc-p-rvc | p- | PASS | 1589 | 12 |
| rv64ud-p-fadd | p- | PASS | 1912 | 14 |
| rv64ud-p-fclass | p- | PASS | 1233 | 10 |
| rv64ud-p-fcmp | p- | PASS | 2232 | 16 |
| rv64ud-p-fcvt | p- | PASS | 1840 | 14 |
| rv64ud-p-fcvt_w | p- | PASS | 3802 | 27 |
| rv64ud-p-fdiv | p- | PASS | 1740 | 14 |
| rv64ud-p-fmadd | p- | PASS | 2072 | 16 |
| rv64ud-p-fmin | p- | PASS | 2544 | 18 |
| rv64ud-p-ldst | p- | PASS | 1172 | 10 |
| rv64ud-p-move | p- | PASS | 2696 | 19 |
| rv64ud-p-recoding | p- | PASS | 1245 | 10 |
| rv64ud-p-structural | p- | PASS | 2027 | 15 |
| rv64uf-p-fadd | p- | PASS | 1912 | 15 |
| rv64uf-p-fclass | p- | PASS | 1217 | 10 |
| rv64uf-p-fcmp | p- | PASS | 2232 | 16 |
| rv64uf-p-fcvt | p- | PASS | 1629 | 13 |
| rv64uf-p-fcvt_w | p- | PASS | 3430 | 24 |
| rv64uf-p-fdiv | p- | PASS | 1664 | 13 |
| rv64uf-p-fmadd | p- | PASS | 2035 | 16 |
| rv64uf-p-fmin | p- | PASS | 2544 | 18 |
| rv64uf-p-ldst | p- | PASS | 1184 | 10 |
| rv64uf-p-move | p- | PASS | 1817 | 13 |
| rv64uf-p-recoding | p- | PASS | 1198 | 9 |
| rv64ui-p-add | p- | PASS | 2453 | 18 |
| rv64ui-p-addi | p- | PASS | 1630 | 12 |
| rv64ui-p-addiw | p- | PASS | 1621 | 13 |
| rv64ui-p-addw | p- | PASS | 2443 | 18 |
| rv64ui-p-and | p- | PASS | 2613 | 19 |
| rv64ui-p-andi | p- | PASS | 1609 | 12 |
| rv64ui-p-auipc | p- | PASS | 1053 | 9 |
| rv64ui-p-beq | p- | PASS | 2427 | 17 |
| rv64ui-p-bge | p- | PASS | 2726 | 19 |
| rv64ui-p-bgeu | p- | PASS | 2956 | 20 |
| rv64ui-p-blt | p- | PASS | 2429 | 17 |
| rv64ui-p-bltu | p- | PASS | 2643 | 19 |
| rv64ui-p-bne | p- | PASS | 2482 | 18 |
| rv64ui-p-fence_i | p- | PASS | 2030 | 15 |
| rv64ui-p-jal | p- | PASS | 1049 | 9 |
| rv64ui-p-jalr | p- | PASS | 1557 | 12 |
| rv64ui-p-lb | p- | PASS | 1671 | 13 |
| rv64ui-p-lbu | p- | PASS | 1671 | 12 |
| rv64ui-p-ld | p- | PASS | 2066 | 16 |
| rv64ui-p-ld_st | p- | PASS | 4478 | 29 |
| rv64ui-p-lh | p- | PASS | 1711 | 12 |
| rv64ui-p-lhu | p- | PASS | 1717 | 13 |
| rv64ui-p-lui | p- | PASS | 1065 | 8 |
| rv64ui-p-lw | p- | PASS | 1731 | 13 |
| rv64ui-p-lwu | p- | PASS | 1797 | 14 |
| rv64ui-p-ma_data | p- | PASS | 7851 | 51 |
| rv64ui-p-or | p- | PASS | 2670 | 19 |
| rv64ui-p-ori | p- | PASS | 1591 | 12 |
| rv64ui-p-sb | p- | PASS | 2292 | 16 |
| rv64ui-p-sd | p- | PASS | 2616 | 19 |
| rv64ui-p-sh | p- | PASS | 2362 | 17 |
| rv64ui-p-simple | p- | PASS | 1003 | 8 |
| rv64ui-p-sll | p- | PASS | 2573 | 19 |
| rv64ui-p-slli | p- | PASS | 1691 | 13 |
| rv64ui-p-slliw | p- | PASS | 1685 | 12 |
| rv64ui-p-sllw | p- | PASS | 2577 | 18 |
| rv64ui-p-slt | p- | PASS | 2431 | 17 |
| rv64ui-p-slti | p- | PASS | 1617 | 12 |
| rv64ui-p-sltiu | p- | PASS | 1617 | 12 |
| rv64ui-p-sltu | p- | PASS | 2469 | 17 |
| rv64ui-p-sra | p- | PASS | 2524 | 18 |
| rv64ui-p-srai | p- | PASS | 1654 | 12 |
| rv64ui-p-sraiw | p- | PASS | 1755 | 13 |
| rv64ui-p-sraw | p- | PASS | 2595 | 18 |
| rv64ui-p-srl | p- | PASS | 2619 | 18 |
| rv64ui-p-srli | p- | PASS | 1715 | 12 |
| rv64ui-p-srliw | p- | PASS | 1703 | 13 |
| rv64ui-p-srlw | p- | PASS | 2583 | 18 |
| rv64ui-p-st_ld | p- | PASS | 1993 | 15 |
| rv64ui-p-sub | p- | PASS | 2437 | 17 |
| rv64ui-p-subw | p- | PASS | 2429 | 18 |
| rv64ui-p-sw | p- | PASS | 2382 | 16 |
| rv64ui-p-xor | p- | PASS | 2664 | 19 |
| rv64ui-p-xori | p- | PASS | 1595 | 12 |
| rv64um-p-div | p- | PASS | 1157 | 9 |
| rv64um-p-divu | p- | PASS | 1167 | 10 |
| rv64um-p-divuw | p- | PASS | 1147 | 9 |
| rv64um-p-divw | p- | PASS | 1139 | 10 |
| rv64um-p-mul | p- | PASS | 2465 | 18 |
| rv64um-p-mulh | p- | PASS | 2471 | 18 |
| rv64um-p-mulhsu | p- | PASS | 2471 | 18 |
| rv64um-p-mulhu | p- | PASS | 2531 | 18 |
| rv64um-p-mulw | p- | PASS | 2330 | 16 |
| rv64um-p-rem | p- | PASS | 1131 | 9 |
| rv64um-p-remu | p- | PASS | 1133 | 9 |
| rv64um-p-remuw | p- | PASS | 1129 | 9 |
| rv64um-p-remw | p- | PASS | 1139 | 9 |
| rv64uzba-p-add_uw | p- | PASS | 2455 | 17 |
| rv64uzba-p-sh1add | p- | PASS | 2461 | 18 |
| rv64uzba-p-sh1add_uw | p- | PASS | 2469 | 18 |
| rv64uzba-p-sh2add | p- | PASS | 2461 | 18 |
| rv64uzba-p-sh2add_uw | p- | PASS | 2469 | 19 |
| rv64uzba-p-sh3add | p- | PASS | 2461 | 19 |
| rv64uzba-p-sh3add_uw | p- | PASS | 2469 | 19 |
| rv64uzba-p-slli_uw | p- | PASS | 1719 | 13 |
| rv64uzbb-p-andn | p- | PASS | 2655 | 20 |
| rv64uzbb-p-clz | p- | PASS | 1497 | 12 |
| rv64uzbb-p-clzw | p- | PASS | 1465 | 13 |
| rv64uzbb-p-cpop | p- | PASS | 1497 | 12 |
| rv64uzbb-p-cpopw | p- | PASS | 1465 | 12 |
| rv64uzbb-p-ctz | p- | PASS | 1497 | 12 |
| rv64uzbb-p-ctzw | p- | PASS | 1467 | 12 |
| rv64uzbb-p-max | p- | PASS | 2441 | 18 |
| rv64uzbb-p-maxu | p- | PASS | 2503 | 18 |
| rv64uzbb-p-min | p- | PASS | 2433 | 18 |
| rv64uzbb-p-minu | p- | PASS | 2482 | 19 |
| rv64uzbb-p-orc_b | p- | PASS | 1539 | 12 |
| rv64uzbb-p-orn | p- | PASS | 2673 | 20 |
| rv64uzbb-p-rev8 | p- | PASS | 1572 | 13 |
| rv64uzbb-p-rol | p- | PASS | 2584 | 19 |
| rv64uzbb-p-rolw | p- | PASS | 2586 | 19 |
| rv64uzbb-p-ror | p- | PASS | 2645 | 20 |
| rv64uzbb-p-rori | p- | PASS | 1712 | 13 |
| rv64uzbb-p-roriw | p- | PASS | 1625 | 13 |
| rv64uzbb-p-rorw | p- | PASS | 2513 | 19 |
| rv64uzbb-p-sext_b | p- | PASS | 1497 | 12 |
| rv64uzbb-p-sext_h | p- | PASS | 1503 | 12 |
| rv64uzbb-p-xnor | p- | PASS | 2671 | 20 |
| rv64uzbb-p-zext_h | p- | PASS | 1509 | 12 |
| rv64uzbc-p-clmul | p- | PASS | 2467 | 18 |
| rv64uzbc-p-clmulh | p- | PASS | 2478 | 18 |
| rv64uzbc-p-clmulr | p- | PASS | 2473 | 18 |
| rv64uzbkb-p-brev8 | p- | PASS | 1537 | 12 |
| rv64uzbkb-p-pack | p- | PASS | 2913 | 22 |
| rv64uzbkb-p-packh | p- | PASS | 2583 | 19 |
| rv64uzbkb-p-packw | p- | PASS | 2443 | 19 |
| rv64uzbkx-p-xperm4 | p- | PASS | 2769 | 21 |
| rv64uzbkx-p-xperm8 | p- | PASS | 3598 | 26 |
| rv64uzbs-p-bclr | p- | PASS | 2796 | 20 |
| rv64uzbs-p-bclri | p- | PASS | 1779 | 14 |
| rv64uzbs-p-bext | p- | PASS | 2661 | 20 |
| rv64uzbs-p-bexti | p- | PASS | 1711 | 13 |
| rv64uzbs-p-binv | p- | PASS | 2631 | 20 |
| rv64uzbs-p-binvi | p- | PASS | 1715 | 14 |
| rv64uzbs-p-bset | p- | PASS | 2800 | 20 |
| rv64uzbs-p-bseti | p- | PASS | 1793 | 14 |
| rv64uzfh-p-fadd | p- | PASS | 1912 | 14 |
| rv64uzfh-p-fclass | p- | PASS | 1218 | 9 |
| rv64uzfh-p-fcmp | p- | PASS | 1566 | 12 |
| rv64uzfh-p-fcvt | p- | PASS | 1802 | 14 |
| rv64uzfh-p-fcvt_w | p- | PASS | 3430 | 25 |
| rv64uzfh-p-fdiv | p- | PASS | 1664 | 13 |
| rv64uzfh-p-fmadd | p- | PASS | 2072 | 16 |
| rv64uzfh-p-fmin | p- | PASS | 2544 | 19 |
| rv64uzfh-p-ldst | p- | PASS | 1196 | 10 |
| rv64uzfh-p-move | p- | PASS | 1812 | 14 |
| rv64uzfh-p-recoding | p- | PASS | 1198 | 10 |
| rv64uziccid-p-ziccid | p- | PASS | 8240 | 37 |
| rv64uzicond-p-czero_eqz | p- | PASS | 2389 | 11 |
| rv64uzicond-p-czero_nez | p- | PASS | 2377 | 14 |
| rv64ua-v-amoadd_d | v- | PASS | 28360 | 215 |
| rv64ua-v-amoadd_w | v- | PASS | 28349 | 186 |
| rv64ua-v-amoand_d | v- | PASS | 27836 | 184 |
| rv64ua-v-amoand_w | v- | PASS | 27836 | 196 |
| rv64ua-v-amomax_d | v- | PASS | 28223 | 187 |
| rv64ua-v-amomax_w | v- | PASS | 28360 | 137 |
| rv64ua-v-amomaxu_d | v- | PASS | 28223 | 187 |
| rv64ua-v-amomaxu_w | v- | PASS | 28360 | 137 |
| rv64ua-v-amomin_d | v- | PASS | 28223 | 197 |
| rv64ua-v-amomin_w | v- | PASS | 28487 | 188 |
| rv64ua-v-amominu_d | v- | PASS | 28380 | 191 |
| rv64ua-v-amominu_w | v- | PASS | 28369 | 187 |
| rv64ua-v-amoor_d | v- | PASS | 28276 | 183 |
| rv64ua-v-amoor_w | v- | PASS | 28276 | 182 |
| rv64ua-v-amoswap_d | v- | PASS | 28539 | 117 |
| rv64ua-v-amoswap_w | v- | PASS | 28385 | 163 |
| rv64ua-v-amoxor_d | v- | PASS | 28333 | 94 |
| rv64ua-v-amoxor_w | v- | PASS | 28365 | 164 |
| rv64ua-v-lrsc | v- | PASS | 46275 | 266 |
| rv64uc-v-rvc | v- | PASS | 37465 | 219 |
| rv64ud-v-fadd | v- | PASS | 27787 | 185 |
| rv64ud-v-fclass | v- | PASS | 17769 | 118 |
| rv64ud-v-fcmp | v- | PASS | 28100 | 119 |
| rv64ud-v-fcvt | v- | PASS | 27434 | 173 |
| rv64ud-v-fcvt_w | v- | PASS | 38653 | 107 |
| rv64ud-v-fdiv | v- | PASS | 27615 | 163 |
| rv64ud-v-fmadd | v- | PASS | 27949 | 204 |
| rv64ud-v-fmin | v- | PASS | 28419 | 135 |
| rv64ud-v-ldst | v- | PASS | 28263 | 138 |
| rv64ud-v-move | v- | PASS | 28511 | 198 |
| rv64ud-v-recoding | v- | PASS | 27790 | 187 |
| rv64ud-v-structural | v- | PASS | 18543 | 131 |
| rv64uf-v-fadd | v- | PASS | 27787 | 164 |
| rv64uf-v-fclass | v- | PASS | 17753 | 118 |
| rv64uf-v-fcmp | v- | PASS | 28100 | 192 |
| rv64uf-v-fcvt | v- | PASS | 27216 | 184 |
| rv64uf-v-fcvt_w | v- | PASS | 38304 | 256 |
| rv64uf-v-fdiv | v- | PASS | 27536 | 136 |
| rv64uf-v-fmadd | v- | PASS | 27949 | 138 |
| rv64uf-v-fmin | v- | PASS | 28419 | 201 |
| rv64uf-v-ldst | v- | PASS | 28407 | 191 |
| rv64uf-v-move | v- | PASS | 18400 | 125 |
| rv64uf-v-recoding | v- | PASS | 26855 | 181 |
| rv64ui-v-add | v- | PASS | 19222 | 133 |
| rv64ui-v-addi | v- | PASS | 18412 | 126 |
| rv64ui-v-addiw | v- | PASS | 18339 | 92 |
| rv64ui-v-addw | v- | PASS | 19183 | 97 |
| rv64ui-v-and | v- | PASS | 19255 | 133 |
| rv64ui-v-andi | v- | PASS | 18277 | 123 |
| rv64ui-v-auipc | v- | PASS | 17683 | 120 |
| rv64ui-v-beq | v- | PASS | 18929 | 67 |
| rv64ui-v-bge | v- | PASS | 19133 | 115 |
| rv64ui-v-bgeu | v- | PASS | 19385 | 148 |
| rv64ui-v-blt | v- | PASS | 18932 | 124 |
| rv64ui-v-bltu | v- | PASS | 19125 | 129 |
| rv64ui-v-bne | v- | PASS | 18861 | 136 |
| rv64ui-v-fence_i | v- | PASS | 29504 | 196 |
| rv64ui-v-jal | v- | PASS | 17683 | 123 |
| rv64ui-v-jalr | v- | PASS | 18225 | 126 |
| rv64ui-v-lb | v- | PASS | 27482 | 136 |
| rv64ui-v-lbu | v- | PASS | 27482 | 138 |
| rv64ui-v-ld | v- | PASS | 27847 | 188 |
| rv64ui-v-ld_st | v- | PASS | 49420 | 283 |
| rv64ui-v-lh | v- | PASS | 27506 | 198 |
| rv64ui-v-lhu | v- | PASS | 27586 | 187 |
| rv64ui-v-lui | v- | PASS | 17713 | 76 |
| rv64ui-v-lw | v- | PASS | 27414 | 186 |
| rv64ui-v-lwu | v- | PASS | 27423 | 183 |
| rv64ui-v-ma_data | v- | PASS | 51138 | 348 |
| rv64ui-v-or | v- | PASS | 19480 | 132 |
| rv64ui-v-ori | v- | PASS | 18316 | 124 |
| rv64ui-v-sb | v- | PASS | 28733 | 188 |
| rv64ui-v-sd | v- | PASS | 38675 | 132 |
| rv64ui-v-sh | v- | PASS | 28439 | 119 |
| rv64ui-v-simple | v- | PASS | 17598 | 116 |
| rv64ui-v-sll | v- | PASS | 28441 | 193 |
| rv64ui-v-slli | v- | PASS | 18421 | 134 |
| rv64ui-v-slliw | v- | PASS | 18468 | 128 |
| rv64ui-v-sllw | v- | PASS | 28692 | 192 |
| rv64ui-v-slt | v- | ERROR | - | 50 |
| rv64ui-v-slti | v- | PASS | 18358 | 111 |
| rv64ui-v-sltiu | v- | PASS | 18358 | 123 |
| rv64ui-v-sltu | v- | PASS | 19206 | 147 |
| rv64ui-v-sra | v- | PASS | 19173 | 133 |
| rv64ui-v-srai | v- | PASS | 18234 | 122 |
| rv64ui-v-sraiw | v- | PASS | 18547 | 127 |
| rv64ui-v-sraw | v- | PASS | 28610 | 192 |
| rv64ui-v-srl | v- | PASS | 28647 | 141 |
| rv64ui-v-srli | v- | PASS | 18283 | 92 |
| rv64ui-v-srliw | v- | PASS | 18485 | 138 |
| rv64ui-v-srlw | v- | PASS | 28690 | 191 |
| rv64ui-v-st_ld | v- | PASS | 38139 | 282 |
| rv64ui-v-sub | v- | PASS | 19132 | 142 |
| rv64ui-v-subw | v- | PASS | 19169 | 129 |
| rv64ui-v-sw | v- | PASS | 29100 | 190 |
| rv64ui-v-xor | v- | PASS | 19425 | 81 |
| rv64ui-v-xori | v- | PASS | 18149 | 122 |
| rv64um-v-div | v- | PASS | 17908 | 133 |
| rv64um-v-divu | v- | PASS | 17866 | 123 |
| rv64um-v-divuw | v- | PASS | 17850 | 76 |
| rv64um-v-divw | v- | PASS | 17892 | 120 |
| rv64um-v-mul | v- | PASS | 19155 | 133 |
| rv64um-v-mulh | v- | PASS | 19246 | 135 |
| rv64um-v-mulhsu | v- | PASS | 19246 | 96 |
| rv64um-v-mulhu | v- | PASS | 19306 | 98 |
| rv64um-v-mulw | v- | PASS | 19119 | 130 |
| rv64um-v-rem | v- | PASS | 17889 | 126 |
| rv64um-v-remu | v- | PASS | 17893 | 121 |
| rv64um-v-remuw | v- | PASS | 17784 | 62 |
| rv64um-v-remw | v- | PASS | 17794 | 120 |
| rv64uzba-v-add_uw | v- | PASS | 18997 | 94 |
| rv64uzba-v-sh1add | v- | PASS | 19005 | 94 |
| rv64uzba-v-sh1add_uw | v- | PASS | 19012 | 137 |
| rv64uzba-v-sh2add | v- | PASS | 19005 | 132 |
| rv64uzba-v-sh2add_uw | v- | PASS | 19012 | 129 |
| rv64uzba-v-sh3add | v- | PASS | 19005 | 126 |
| rv64uzba-v-sh3add_uw | v- | PASS | 19012 | 130 |
| rv64uzba-v-slli_uw | v- | PASS | 18371 | 121 |
| rv64uzbb-v-andn | v- | PASS | 19068 | 81 |
| rv64uzbb-v-clz | v- | ERROR | - | 9 |
| rv64uzbb-v-clzw | v- | ERROR | - | 5 |
| rv64uzbb-v-cpop | v- | ERROR | - | 8 |
| rv64uzbb-v-cpopw | v- | ERROR | - | 10 |
| rv64uzbb-v-ctz | v- | ERROR | - | 9 |
| rv64uzbb-v-ctzw | v- | ERROR | - | 9 |
| rv64uzbb-v-max | v- | PASS | 19030 | 131 |
| rv64uzbb-v-maxu | v- | PASS | 19087 | 133 |
| rv64uzbb-v-min | v- | PASS | 19023 | 130 |
| rv64uzbb-v-minu | v- | PASS | 19066 | 94 |
| rv64uzbb-v-orc_b | v- | ERROR | - | 7 |
| rv64uzbb-v-orn | v- | PASS | 28248 | 199 |
| rv64uzbb-v-rev8 | v- | PASS | 18256 | 128 |
| rv64uzbb-v-rol | v- | PASS | 28314 | 187 |
| rv64uzbb-v-rolw | v- | PASS | 28454 | 179 |
| rv64uzbb-v-ror | v- | PASS | 28217 | 178 |
| rv64uzbb-v-rori | v- | PASS | 18372 | 119 |
| rv64uzbb-v-roriw | v- | ERROR | - | 5 |
| rv64uzbb-v-rorw | v- | PASS | 19102 | 126 |
| rv64uzbb-v-sext_b | v- | ERROR | - | 5 |
| rv64uzbb-v-sext_h | v- | ERROR | - | 8 |
| rv64uzbb-v-xnor | v- | PASS | 28183 | 194 |
| rv64uzbb-v-zext_h | v- | ERROR | - | 9 |
| rv64uzbc-v-clmul | v- | PASS | 19208 | 128 |
| rv64uzbc-v-clmulh | v- | PASS | 19167 | 80 |
| rv64uzbc-v-clmulr | v- | PASS | 19164 | 97 |
| rv64uzbkb-v-brev8 | v- | PASS | 18249 | 120 |
| rv64uzbkb-v-pack | v- | PASS | 28656 | 82 |
| rv64uzbkb-v-packh | v- | PASS | 19281 | 90 |
| rv64uzbkb-v-packw | v- | PASS | 19087 | 128 |
| rv64uzbkx-v-xperm4 | v- | PASS | 28703 | 110 |
| rv64uzbkx-v-xperm8 | v- | PASS | 29557 | 136 |
| rv64uzbs-v-bclr | v- | PASS | 28336 | 159 |
| rv64uzbs-v-bclri | v- | PASS | 18522 | 114 |
| rv64uzbs-v-bext | v- | PASS | 28531 | 136 |
| rv64uzbs-v-bexti | v- | PASS | 18363 | 75 |
| rv64uzbs-v-binv | v- | PASS | 28132 | 145 |
| rv64uzbs-v-binvi | v- | PASS | 18348 | 63 |
| rv64uzbs-v-bset | v- | PASS | 28653 | 113 |
| rv64uzbs-v-bseti | v- | PASS | 18586 | 133 |
| rv64uzfh-v-fadd | v- | PASS | 27787 | 153 |
| rv64uzfh-v-fclass | v- | PASS | 17753 | 121 |
| rv64uzfh-v-fcmp | v- | PASS | 27435 | 122 |
| rv64uzfh-v-fcvt | v- | PASS | 27377 | 108 |
| rv64uzfh-v-fcvt_w | v- | PASS | 38304 | 148 |
| rv64uzfh-v-fdiv | v- | PASS | 27536 | 80 |
| rv64uzfh-v-fmadd | v- | PASS | 27949 | 97 |
| rv64uzfh-v-fmin | v- | PASS | 28419 | 119 |
| rv64uzfh-v-ldst | v- | PASS | 28545 | 107 |
| rv64uzfh-v-move | v- | PASS | 18395 | 119 |
| rv64uzfh-v-recoding | v- | PASS | 26853 | 120 |
| rv64uziccid-v-ziccid | v- | TIMEOUT | - | 584 |
| rv64uzicond-v-czero_eqz | v- | PASS | 19129 | 78 |
| rv64uzicond-v-czero_nez | v- | PASS | 19004 | 76 |

</details>

## Performance counters

| Test | Suite | Shard | cycles | cpred_predicted | cpred_mispred_squash | cpred_btb_miss_redirect | ras_predicted | ras_mispred | indirect_predicted | indirect_mispred | fetch_resteer_to_bac | load_committed | lr_committed | store_committed | sc_committed | store_violation_squash | all_squashes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| `hypervisor-p-2-stage_translation` | p- | none | 1374 | 0 | 2 | 6 | 0 | 0 | 0 | 0 | 1 | 1 | 0 | 13 | 0 | 0 | 27 |
| `hypervisor-p-2-stage_translation_implicit_load_error` | p- | none | 1652 | 0 | 2 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 3 | 0 | 0 | 34 |
| `hypervisor-p-2-stage_translation_implicit_load_error_hs` | p- | none | 1827 | 0 | 2 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 3 | 0 | 0 | 38 |
| `hypervisor-svadu-p-2-stage_translation_implicit_store_error` | p- | none | 1768 | 0 | 2 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 3 | 0 | 0 | 36 |
| `hypervisor-svadu-p-2-stage_translation_implicit_store_error_hs` | p- | none | 1945 | 0 | 2 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 3 | 0 | 0 | 40 |
| `rv64mi-p-breakpoint` | p- | none | 3343 | 0 | 2 | 8 | 0 | 0 | 10 | 1 | 1 | 3 | 0 | 2 | 0 | 0 | 74 |
| `rv64mi-p-csr` | p- | none | 3467 | 16 | 1 | 9 | 0 | 0 | 6 | 1 | 1 | 1 | 0 | 1 | 0 | 0 | 77 |
| `rv64mi-p-instret_overflow` | p- | none | 1252 | 0 | 0 | 8 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64mi-p-ld-misaligned` | p- | none | 1386 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 8 | 0 | 1 | 0 | 0 | 25 |
| `rv64mi-p-lh-misaligned` | p- | none | 1102 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 1 | 0 | 0 | 25 |
| `rv64mi-p-lw-misaligned` | p- | none | 1171 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 4 | 0 | 1 | 0 | 0 | 25 |
| `rv64mi-p-ma_addr` | p- | none | 1538 | 0 | 2 | 8 | 0 | 0 | 0 | 0 | 1 | 59 | 0 | 12 | 0 | 0 | 25 |
| `rv64mi-p-ma_fetch` | p- | none | 1950 | 0 | 1 | 26 | 0 | 0 | 0 | 0 | 9 | 0 | 0 | 1 | 0 | 0 | 48 |
| `rv64mi-p-mcsr` | p- | none | 1342 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 32 |
| `rv64mi-p-pmpaddr` | p- | none | 1185 | 0 | 0 | 9 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64mi-p-sbreak` | p- | none | 1315 | 27 | 0 | 10 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64mi-p-scall` | p- | none | 1261 | 0 | 0 | 9 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64mi-p-sd-misaligned` | p- | none | 1436 | 0 | 3 | 16 | 0 | 0 | 0 | 0 | 1 | 8 | 0 | 9 | 0 | 0 | 26 |
| `rv64mi-p-sh-misaligned` | p- | none | 1109 | 0 | 2 | 9 | 0 | 0 | 0 | 0 | 2 | 2 | 0 | 3 | 0 | 0 | 25 |
| `rv64mi-p-sw-misaligned` | p- | none | 1150 | 0 | 2 | 11 | 0 | 0 | 0 | 0 | 3 | 4 | 0 | 5 | 0 | 0 | 25 |
| `rv64mi-p-zicntr` | p- | none | 1439 | 0 | 0 | 8 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 33 |
| `rv64mzicbo-p-zero` | p- | none | 1160 | 0 | 2 | 7 | 0 | 0 | 0 | 0 | 1 | 8 | 0 | 2 | 0 | 0 | 24 |
| `rv64si-p-csr` | p- | none | 2277 | 0 | 2 | 6 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 51 |
| `rv64si-p-dirty` | p- | none | 2274 | 46 | 1 | 11 | 0 | 0 | 6 | 1 | 1 | 6 | 0 | 5 | 0 | 0 | 49 |
| `rv64si-p-icache-alias` | p- | none | 2372 | 0 | 3 | 8 | 0 | 0 | 82 | 4 | 1 | 0 | 0 | 7 | 0 | 0 | 53 |
| `rv64si-p-ma_fetch` | p- | none | 1382 | 0 | 1 | 23 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 1 | 0 | 0 | 33 |
| `rv64si-p-sbreak` | p- | none | 1325 | 15 | 0 | 8 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64si-p-scall` | p- | none | 1443 | 13 | 0 | 8 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 34 |
| `rv64si-p-wfi` | p- | none | 1173 | 0 | 2 | 6 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64ssvnapot-p-napot` | p- | none | 1658 | 3 | 2 | 8 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 7 | 0 | 0 | 34 |
| `rv64ua-p-amoadd_d` | p- | none | 1081 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 0 | 24 |
| `rv64ua-p-amoadd_w` | p- | none | 1120 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoand_d` | p- | none | 1121 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoand_w` | p- | none | 1117 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amomax_d` | p- | none | 1077 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 3 | 0 | 0 | 24 |
| `rv64ua-p-amomax_w` | p- | none | 1100 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 3 | 0 | 4 | 0 | 0 | 24 |
| `rv64ua-p-amomaxu_d` | p- | none | 1077 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 3 | 0 | 0 | 24 |
| `rv64ua-p-amomaxu_w` | p- | none | 1100 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 3 | 0 | 4 | 0 | 0 | 24 |
| `rv64ua-p-amomin_d` | p- | none | 1077 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 3 | 0 | 0 | 24 |
| `rv64ua-p-amomin_w` | p- | none | 1100 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 3 | 0 | 4 | 0 | 0 | 24 |
| `rv64ua-p-amominu_d` | p- | none | 1077 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 3 | 0 | 0 | 24 |
| `rv64ua-p-amominu_w` | p- | none | 1100 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 3 | 0 | 4 | 0 | 0 | 24 |
| `rv64ua-p-amoor_d` | p- | none | 1117 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoor_w` | p- | none | 1117 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoswap_d` | p- | none | 1121 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoswap_w` | p- | none | 1117 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoxor_d` | p- | none | 1125 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoxor_w` | p- | none | 1129 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-lrsc` | p- | none | 19229 | 2203 | 12 | 9 | 0 | 0 | 0 | 0 | 1 | 4 | 1025 | 1 | 1028 | 74 | 108 |
| `rv64uc-p-rvc` | p- | none | 1589 | 1 | 4 | 28 | 0 | 0 | 0 | 1 | 7 | 9 | 0 | 5 | 0 | 0 | 34 |
| `rv64ud-p-fadd` | p- | none | 1912 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 40 | 0 | 1 | 0 | 0 | 36 |
| `rv64ud-p-fclass` | p- | none | 1233 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 26 |
| `rv64ud-p-fcmp` | p- | none | 2232 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 60 | 0 | 1 | 0 | 0 | 41 |
| `rv64ud-p-fcvt` | p- | none | 1840 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 17 | 0 | 1 | 0 | 0 | 36 |
| `rv64ud-p-fcvt_w` | p- | none | 3802 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 152 | 0 | 1 | 0 | 0 | 60 |
| `rv64ud-p-fdiv` | p- | none | 1740 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 32 | 0 | 1 | 0 | 0 | 34 |
| `rv64ud-p-fmadd` | p- | none | 2072 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 48 | 0 | 1 | 0 | 0 | 38 |
| `rv64ud-p-fmin` | p- | none | 2544 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 72 | 0 | 1 | 0 | 0 | 44 |
| `rv64ud-p-ldst` | p- | none | 1172 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 10 | 0 | 6 | 0 | 0 | 26 |
| `rv64ud-p-move` | p- | none | 2696 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 26 |
| `rv64ud-p-recoding` | p- | none | 1245 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 7 | 0 | 2 | 0 | 0 | 26 |
| `rv64ud-p-structural` | p- | none | 2027 | 0 | 17 | 48 | 0 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 46 |
| `rv64uf-p-fadd` | p- | none | 1912 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 40 | 0 | 1 | 0 | 0 | 36 |
| `rv64uf-p-fclass` | p- | none | 1217 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 26 |
| `rv64uf-p-fcmp` | p- | none | 2232 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 60 | 0 | 1 | 0 | 0 | 41 |
| `rv64uf-p-fcvt` | p- | none | 1629 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 8 | 0 | 1 | 0 | 0 | 34 |
| `rv64uf-p-fcvt_w` | p- | none | 3430 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 132 | 0 | 1 | 0 | 0 | 55 |
| `rv64uf-p-fdiv` | p- | none | 1664 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 28 | 0 | 1 | 0 | 0 | 33 |
| `rv64uf-p-fmadd` | p- | none | 2035 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 48 | 0 | 1 | 0 | 0 | 38 |
| `rv64uf-p-fmin` | p- | none | 2544 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 72 | 0 | 1 | 0 | 0 | 44 |
| `rv64uf-p-ldst` | p- | none | 1184 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 4 | 0 | 3 | 0 | 0 | 26 |
| `rv64uf-p-move` | p- | none | 1817 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 34 |
| `rv64uf-p-recoding` | p- | none | 1198 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 1 | 0 | 0 | 26 |
| `rv64ui-p-add` | p- | none | 2453 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-addi` | p- | none | 1630 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-addiw` | p- | none | 1621 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-addw` | p- | none | 2443 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-and` | p- | none | 2613 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-andi` | p- | none | 1609 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-auipc` | p- | none | 1053 | 0 | 2 | 9 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64ui-p-beq` | p- | none | 2427 | 15 | 28 | 33 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 50 |
| `rv64ui-p-bge` | p- | none | 2726 | 18 | 37 | 42 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 59 |
| `rv64ui-p-bgeu` | p- | none | 2956 | 18 | 37 | 42 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 59 |
| `rv64ui-p-blt` | p- | none | 2429 | 15 | 28 | 33 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 50 |
| `rv64ui-p-bltu` | p- | none | 2643 | 15 | 28 | 33 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 50 |
| `rv64ui-p-bne` | p- | none | 2482 | 16 | 30 | 35 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 52 |
| `rv64ui-p-fence_i` | p- | none | 2030 | 161 | 10 | 12 | 0 | 0 | 0 | 1 | 1 | 2 | 0 | 5 | 0 | 0 | 38 |
| `rv64ui-p-jal` | p- | none | 1049 | 0 | 1 | 9 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64ui-p-jalr` | p- | none | 1557 | 3 | 5 | 21 | 0 | 0 | 3 | 3 | 1 | 0 | 0 | 1 | 0 | 0 | 37 |
| `rv64ui-p-lb` | p- | none | 1671 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-lbu` | p- | none | 1671 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-ld` | p- | none | 2066 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-ld_st` | p- | none | 4478 | 0 | 22 | 157 | 0 | 0 | 0 | 0 | 1 | 277 | 0 | 278 | 0 | 0 | 137 |
| `rv64ui-p-lh` | p- | none | 1711 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-lhu` | p- | none | 1717 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-lui` | p- | none | 1065 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64ui-p-lw` | p- | none | 1731 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-lwu` | p- | none | 1797 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-ma_data` | p- | none | 7851 | 0 | 3 | 211 | 0 | 0 | 0 | 0 | 1 | 180 | 0 | 136 | 0 | 0 | 197 |
| `rv64ui-p-or` | p- | none | 2670 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-ori` | p- | none | 1591 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sb` | p- | none | 2292 | 12 | 14 | 27 | 0 | 0 | 0 | 0 | 1 | 34 | 0 | 36 | 0 | 1 | 38 |
| `rv64ui-p-sd` | p- | none | 2616 | 12 | 14 | 27 | 0 | 0 | 0 | 0 | 1 | 34 | 0 | 35 | 0 | 1 | 38 |
| `rv64ui-p-sh` | p- | none | 2362 | 12 | 14 | 27 | 0 | 0 | 0 | 0 | 1 | 34 | 0 | 36 | 0 | 1 | 38 |
| `rv64ui-p-simple` | p- | none | 1003 | 0 | 2 | 6 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 23 |
| `rv64ui-p-sll` | p- | none | 2573 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-slli` | p- | none | 1691 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-slliw` | p- | none | 1685 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sllw` | p- | none | 2577 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-slt` | p- | none | 2431 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-slti` | p- | none | 1617 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sltiu` | p- | none | 1617 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sltu` | p- | none | 2469 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-sra` | p- | none | 2524 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-srai` | p- | none | 1654 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sraiw` | p- | none | 1755 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sraw` | p- | none | 2595 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-srl` | p- | none | 2619 | 15 | 18 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-srli` | p- | none | 1715 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-srliw` | p- | none | 1703 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-srlw` | p- | none | 2583 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-st_ld` | p- | none | 1993 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 70 | 0 | 71 | 0 | 0 | 24 |
| `rv64ui-p-sub` | p- | none | 2437 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-subw` | p- | none | 2429 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-sw` | p- | none | 2382 | 12 | 15 | 27 | 0 | 0 | 0 | 0 | 2 | 34 | 0 | 35 | 0 | 1 | 38 |
| `rv64ui-p-xor` | p- | none | 2664 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-xori` | p- | none | 1595 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64um-p-div` | p- | none | 1157 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-divu` | p- | none | 1167 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-divuw` | p- | none | 1147 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-divw` | p- | none | 1139 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-mul` | p- | none | 2465 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-mulh` | p- | none | 2471 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-mulhsu` | p- | none | 2471 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-mulhu` | p- | none | 2531 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-mulw` | p- | none | 2330 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-rem` | p- | none | 1131 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-remu` | p- | none | 1133 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-remuw` | p- | none | 1129 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-remw` | p- | none | 1139 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64uzba-p-add_uw` | p- | none | 2455 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh1add` | p- | none | 2461 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh1add_uw` | p- | none | 2469 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh2add` | p- | none | 2461 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh2add_uw` | p- | none | 2469 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh3add` | p- | none | 2461 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh3add_uw` | p- | none | 2469 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-slli_uw` | p- | none | 1719 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbb-p-andn` | p- | none | 2655 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-clz` | p- | none | 1497 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-clzw` | p- | none | 1465 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-cpop` | p- | none | 1497 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-cpopw` | p- | none | 1465 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-ctz` | p- | none | 1497 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-ctzw` | p- | none | 1467 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-max` | p- | none | 2441 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-maxu` | p- | none | 2503 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-min` | p- | none | 2433 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-minu` | p- | none | 2482 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-orc_b` | p- | none | 1539 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-orn` | p- | none | 2673 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-rev8` | p- | none | 1572 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-rol` | p- | none | 2584 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-rolw` | p- | none | 2586 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-ror` | p- | none | 2645 | 15 | 18 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-rori` | p- | none | 1712 | 6 | 8 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbb-p-roriw` | p- | none | 1625 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbb-p-rorw` | p- | none | 2513 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-sext_b` | p- | none | 1497 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-sext_h` | p- | none | 1503 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-xnor` | p- | none | 2671 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-zext_h` | p- | none | 1509 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbc-p-clmul` | p- | none | 2467 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbc-p-clmulh` | p- | none | 2478 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbc-p-clmulr` | p- | none | 2473 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkb-p-brev8` | p- | none | 1537 | 3 | 7 | 10 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbkb-p-pack` | p- | none | 2913 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkb-p-packh` | p- | none | 2583 | 15 | 18 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkb-p-packw` | p- | none | 2443 | 15 | 18 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkx-p-xperm4` | p- | none | 2769 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkx-p-xperm8` | p- | none | 3598 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-bclr` | p- | none | 2796 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-bclri` | p- | none | 1779 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbs-p-bext` | p- | none | 2661 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-bexti` | p- | none | 1711 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbs-p-binv` | p- | none | 2631 | 15 | 18 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-binvi` | p- | none | 1715 | 6 | 8 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbs-p-bset` | p- | none | 2800 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-bseti` | p- | none | 1793 | 6 | 9 | 13 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzfh-p-fadd` | p- | none | 1912 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 40 | 0 | 1 | 0 | 0 | 36 |
| `rv64uzfh-p-fclass` | p- | none | 1218 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 26 |
| `rv64uzfh-p-fcmp` | p- | none | 1566 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 24 | 0 | 1 | 0 | 0 | 32 |
| `rv64uzfh-p-fcvt` | p- | none | 1802 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 16 | 0 | 1 | 0 | 0 | 36 |
| `rv64uzfh-p-fcvt_w` | p- | none | 3430 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 132 | 0 | 1 | 0 | 0 | 55 |
| `rv64uzfh-p-fdiv` | p- | none | 1664 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 28 | 0 | 1 | 0 | 0 | 33 |
| `rv64uzfh-p-fmadd` | p- | none | 2072 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 48 | 0 | 1 | 0 | 0 | 38 |
| `rv64uzfh-p-fmin` | p- | none | 2544 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 72 | 0 | 1 | 0 | 0 | 44 |
| `rv64uzfh-p-ldst` | p- | none | 1196 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 4 | 0 | 3 | 0 | 0 | 26 |
| `rv64uzfh-p-move` | p- | none | 1812 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 34 |
| `rv64uzfh-p-recoding` | p- | none | 1198 | 0 | 3 | 7 | 0 | 0 | 0 | 0 | 1 | 2 | 0 | 1 | 0 | 0 | 26 |
| `rv64uziccid-p-ziccid` | p- | none | 8240 | 678 | 68 | 398 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 105 | 0 | 0 | 470 |
| `rv64uzicond-p-czero_eqz` | p- | none | 2389 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzicond-p-czero_nez` | p- | none | 2377 | 15 | 19 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ua-v-amoadd_d` | v- | 15/18 | 28360 | 1578 | 377 | 308 | 0 | 0 | 219 | 7 | 1 | 2891 | 0 | 1987 | 0 | 0 | 493 |
| `rv64ua-v-amoadd_w` | v- | 16/18 | 28349 | 1570 | 369 | 299 | 0 | 0 | 217 | 7 | 1 | 2891 | 0 | 1987 | 0 | 1 | 484 |
| `rv64ua-v-amoand_d` | v- | 17/18 | 27836 | 1675 | 292 | 277 | 0 | 0 | 217 | 7 | 1 | 2895 | 0 | 1987 | 0 | 1 | 410 |
| `rv64ua-v-amoand_w` | v- | 18/18 | 27836 | 1675 | 292 | 277 | 0 | 0 | 217 | 7 | 1 | 2895 | 0 | 1987 | 0 | 1 | 410 |
| `rv64ua-v-amomax_d` | v- | 1/18 | 28223 | 1574 | 353 | 293 | 0 | 0 | 220 | 6 | 1 | 2889 | 0 | 1988 | 0 | 0 | 469 |
| `rv64ua-v-amomax_w` | v- | 4/18 | 28360 | 1589 | 370 | 300 | 0 | 0 | 220 | 5 | 1 | 2890 | 0 | 1989 | 0 | 0 | 486 |
| `rv64ua-v-amomaxu_d` | v- | 2/18 | 28223 | 1574 | 353 | 293 | 0 | 0 | 220 | 6 | 1 | 2889 | 0 | 1988 | 0 | 0 | 469 |
| `rv64ua-v-amomaxu_w` | v- | 3/18 | 28360 | 1589 | 370 | 300 | 0 | 0 | 220 | 5 | 1 | 2890 | 0 | 1989 | 0 | 0 | 486 |
| `rv64ua-v-amomin_d` | v- | 5/18 | 28223 | 1574 | 353 | 293 | 0 | 0 | 220 | 6 | 1 | 2889 | 0 | 1988 | 0 | 0 | 469 |
| `rv64ua-v-amomin_w` | v- | 8/18 | 28487 | 1589 | 369 | 301 | 0 | 0 | 223 | 4 | 1 | 2896 | 0 | 1989 | 0 | 0 | 485 |
| `rv64ua-v-amominu_d` | v- | 6/18 | 28380 | 1592 | 365 | 299 | 0 | 0 | 222 | 5 | 1 | 2891 | 0 | 1988 | 0 | 0 | 481 |
| `rv64ua-v-amominu_w` | v- | 7/18 | 28369 | 1585 | 366 | 300 | 0 | 0 | 221 | 4 | 1 | 2892 | 0 | 1989 | 0 | 0 | 482 |
| `rv64ua-v-amoor_d` | v- | 9/18 | 28276 | 1581 | 359 | 295 | 0 | 0 | 221 | 6 | 1 | 2889 | 0 | 1987 | 0 | 1 | 476 |
| `rv64ua-v-amoor_w` | v- | 10/18 | 28276 | 1581 | 359 | 295 | 0 | 0 | 221 | 6 | 1 | 2889 | 0 | 1987 | 0 | 1 | 476 |
| `rv64ua-v-amoswap_d` | v- | 11/18 | 28539 | 1593 | 372 | 300 | 0 | 0 | 223 | 5 | 1 | 2895 | 0 | 1987 | 0 | 1 | 489 |
| `rv64ua-v-amoswap_w` | v- | 12/18 | 28385 | 1581 | 357 | 294 | 0 | 0 | 223 | 5 | 1 | 2895 | 0 | 1987 | 0 | 1 | 474 |
| `rv64ua-v-amoxor_d` | v- | 13/18 | 28333 | 1576 | 365 | 298 | 0 | 0 | 220 | 7 | 1 | 2889 | 0 | 1987 | 0 | 1 | 482 |
| `rv64ua-v-amoxor_w` | v- | 14/18 | 28365 | 1582 | 366 | 300 | 0 | 0 | 220 | 5 | 1 | 2889 | 0 | 1987 | 0 | 1 | 483 |
| `rv64ua-v-lrsc` | v- | 15/18 | 46275 | 3711 | 367 | 300 | 0 | 0 | 211 | 5 | 1 | 2891 | 1025 | 1986 | 1028 | 75 | 559 |
| `rv64uc-v-rvc` | v- | 14/18 | 37465 | 2869 | 411 | 335 | 0 | 0 | 428 | 11 | 10 | 4535 | 0 | 2601 | 0 | 0 | 561 |
| `rv64ud-v-fadd` | v- | 9/18 | 27787 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3395 | 0 | 1433 | 0 | 0 | 410 |
| `rv64ud-v-fclass` | v- | 10/18 | 17769 | 1095 | 197 | 188 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 271 |
| `rv64ud-v-fcmp` | v- | 11/18 | 28100 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3415 | 0 | 1433 | 0 | 0 | 415 |
| `rv64ud-v-fcvt` | v- | 12/18 | 27434 | 2412 | 277 | 257 | 0 | 0 | 207 | 5 | 1 | 3372 | 0 | 1433 | 0 | 0 | 391 |
| `rv64ud-v-fcvt_w` | v- | 13/18 | 38653 | 3749 | 367 | 339 | 0 | 0 | 323 | 8 | 1 | 5136 | 0 | 2044 | 0 | 0 | 543 |
| `rv64ud-v-fdiv` | v- | 14/18 | 27615 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3387 | 0 | 1433 | 0 | 0 | 408 |
| `rv64ud-v-fmadd` | v- | 15/18 | 27949 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3403 | 0 | 1433 | 0 | 0 | 412 |
| `rv64ud-v-fmin` | v- | 16/18 | 28419 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3427 | 0 | 1433 | 0 | 0 | 418 |
| `rv64ud-v-ldst` | v- | 17/18 | 28263 | 1580 | 369 | 309 | 0 | 0 | 217 | 4 | 1 | 2901 | 0 | 1991 | 0 | 0 | 488 |
| `rv64ud-v-move` | v- | 18/18 | 28511 | 2411 | 279 | 260 | 0 | 0 | 207 | 6 | 1 | 3355 | 0 | 1433 | 0 | 0 | 386 |
| `rv64ud-v-recoding` | v- | 1/18 | 27790 | 1659 | 281 | 267 | 0 | 0 | 221 | 6 | 1 | 2908 | 0 | 1987 | 0 | 0 | 399 |
| `rv64ud-v-structural` | v- | 2/18 | 18543 | 1094 | 215 | 251 | 0 | 0 | 89 | 6 | 2 | 1726 | 0 | 822 | 0 | 0 | 294 |
| `rv64uf-v-fadd` | v- | 16/18 | 27787 | 2433 | 293 | 268 | 0 | 0 | 211 | 5 | 1 | 3395 | 0 | 1433 | 0 | 0 | 410 |
| `rv64uf-v-fclass` | v- | 17/18 | 17753 | 1095 | 198 | 188 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 271 |
| `rv64uf-v-fcmp` | v- | 18/18 | 28100 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3415 | 0 | 1433 | 0 | 0 | 415 |
| `rv64uf-v-fcvt` | v- | 1/18 | 27216 | 2412 | 277 | 256 | 0 | 0 | 207 | 5 | 1 | 3363 | 0 | 1433 | 0 | 0 | 389 |
| `rv64uf-v-fcvt_w` | v- | 2/18 | 38304 | 3749 | 366 | 339 | 0 | 0 | 323 | 8 | 1 | 5116 | 0 | 2044 | 0 | 0 | 538 |
| `rv64uf-v-fdiv` | v- | 3/18 | 27536 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3383 | 0 | 1433 | 0 | 0 | 407 |
| `rv64uf-v-fmadd` | v- | 4/18 | 27949 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3403 | 0 | 1433 | 0 | 0 | 412 |
| `rv64uf-v-fmin` | v- | 5/18 | 28419 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3427 | 0 | 1433 | 0 | 0 | 418 |
| `rv64uf-v-ldst` | v- | 6/18 | 28407 | 1600 | 367 | 307 | 0 | 0 | 222 | 5 | 1 | 2903 | 0 | 1988 | 0 | 0 | 487 |
| `rv64uf-v-move` | v- | 7/18 | 18400 | 1063 | 195 | 187 | 0 | 0 | 93 | 5 | 1 | 1726 | 0 | 822 | 0 | 0 | 276 |
| `rv64uf-v-recoding` | v- | 8/18 | 26855 | 2415 | 278 | 260 | 0 | 0 | 208 | 6 | 1 | 3357 | 0 | 1433 | 0 | 0 | 384 |
| `rv64ui-v-add` | v- | 1/18 | 19222 | 1125 | 219 | 213 | 0 | 0 | 87 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 294 |
| `rv64ui-v-addi` | v- | 2/18 | 18412 | 1084 | 214 | 205 | 0 | 0 | 94 | 6 | 1 | 1726 | 0 | 822 | 0 | 0 | 284 |
| `rv64ui-v-addiw` | v- | 3/18 | 18339 | 1113 | 212 | 203 | 0 | 0 | 92 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 285 |
| `rv64ui-v-addw` | v- | 4/18 | 19183 | 1116 | 220 | 212 | 0 | 0 | 93 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 293 |
| `rv64ui-v-and` | v- | 7/18 | 19255 | 1113 | 209 | 204 | 0 | 0 | 93 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 281 |
| `rv64ui-v-andi` | v- | 8/18 | 18277 | 1108 | 201 | 192 | 0 | 0 | 94 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 273 |
| `rv64ui-v-auipc` | v- | 12/18 | 17683 | 1097 | 198 | 196 | 0 | 0 | 105 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 270 |
| `rv64ui-v-beq` | v- | 13/18 | 18929 | 1108 | 199 | 209 | 0 | 0 | 92 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 291 |
| `rv64ui-v-bge` | v- | 14/18 | 19133 | 1110 | 206 | 222 | 0 | 0 | 107 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 299 |
| `rv64ui-v-bgeu` | v- | 15/18 | 19385 | 1115 | 202 | 222 | 0 | 0 | 85 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 300 |
| `rv64ui-v-blt` | v- | 16/18 | 18932 | 1108 | 199 | 209 | 0 | 0 | 92 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 291 |
| `rv64ui-v-bltu` | v- | 17/18 | 19125 | 1121 | 212 | 222 | 0 | 0 | 85 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 301 |
| `rv64ui-v-bne` | v- | 18/18 | 18861 | 1117 | 202 | 213 | 0 | 0 | 85 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 292 |
| `rv64ui-v-fence_i` | v- | 17/18 | 29504 | 1645 | 398 | 311 | 0 | 0 | 295 | 8 | 1 | 2901 | 0 | 1990 | 0 | 0 | 517 |
| `rv64ui-v-jal` | v- | 1/18 | 17683 | 1098 | 194 | 195 | 0 | 0 | 93 | 5 | 1 | 1726 | 0 | 822 | 0 | 0 | 268 |
| `rv64ui-v-jalr` | v- | 2/18 | 18225 | 1112 | 207 | 217 | 0 | 0 | 89 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 295 |
| `rv64ui-v-lb` | v- | 3/18 | 27482 | 2426 | 282 | 262 | 0 | 0 | 212 | 5 | 1 | 3379 | 0 | 1433 | 0 | 0 | 390 |
| `rv64ui-v-lbu` | v- | 4/18 | 27482 | 2426 | 282 | 262 | 0 | 0 | 212 | 5 | 1 | 3379 | 0 | 1433 | 0 | 0 | 390 |
| `rv64ui-v-ld` | v- | 9/18 | 27847 | 2410 | 282 | 260 | 0 | 0 | 207 | 5 | 1 | 3379 | 0 | 1433 | 0 | 0 | 384 |
| `rv64ui-v-ld_st` | v- | 14/18 | 49420 | 4410 | 496 | 545 | 0 | 0 | 301 | 10 | 1 | 6422 | 0 | 3485 | 0 | 0 | 773 |
| `rv64ui-v-lh` | v- | 5/18 | 27506 | 2417 | 285 | 263 | 0 | 0 | 212 | 5 | 1 | 3379 | 0 | 1433 | 0 | 0 | 390 |
| `rv64ui-v-lhu` | v- | 6/18 | 27586 | 2435 | 292 | 273 | 0 | 0 | 212 | 5 | 1 | 3379 | 0 | 1433 | 0 | 0 | 400 |
| `rv64ui-v-lui` | v- | 11/18 | 17713 | 1098 | 194 | 187 | 0 | 0 | 93 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 267 |
| `rv64ui-v-lw` | v- | 7/18 | 27414 | 2427 | 291 | 272 | 0 | 0 | 208 | 5 | 1 | 3379 | 0 | 1433 | 0 | 0 | 394 |
| `rv64ui-v-lwu` | v- | 8/18 | 27423 | 2418 | 281 | 261 | 0 | 0 | 208 | 5 | 1 | 3379 | 0 | 1433 | 0 | 0 | 384 |
| `rv64ui-v-ma_data` | v- | 18/18 | 51138 | 4316 | 441 | 595 | 0 | 0 | 295 | 12 | 1 | 6327 | 0 | 3343 | 0 | 0 | 750 |
| `rv64ui-v-or` | v- | 9/18 | 19480 | 1128 | 219 | 210 | 0 | 0 | 94 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 293 |
| `rv64ui-v-ori` | v- | 10/18 | 18316 | 1117 | 210 | 203 | 0 | 0 | 94 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 284 |
| `rv64ui-v-sb` | v- | 10/18 | 28733 | 1658 | 320 | 285 | 0 | 0 | 230 | 7 | 3 | 2921 | 0 | 2021 | 0 | 1 | 438 |
| `rv64ui-v-sd` | v- | 13/18 | 38675 | 3101 | 416 | 399 | 0 | 0 | 146 | 17 | 5 | 4550 | 0 | 2631 | 0 | 1 | 581 |
| `rv64ui-v-sh` | v- | 11/18 | 28439 | 1897 | 244 | 263 | 0 | 0 | 125 | 6 | 2 | 2921 | 0 | 2021 | 0 | 1 | 369 |
| `rv64ui-v-simple` | v- | 16/18 | 17598 | 1061 | 194 | 186 | 0 | 0 | 93 | 6 | 1 | 1726 | 0 | 822 | 0 | 0 | 266 |
| `rv64ui-v-sll` | v- | 17/18 | 28441 | 2415 | 291 | 271 | 0 | 0 | 141 | 5 | 1 | 3355 | 0 | 1433 | 0 | 0 | 394 |
| `rv64ui-v-slli` | v- | 18/18 | 18421 | 1085 | 213 | 205 | 0 | 0 | 94 | 6 | 1 | 1726 | 0 | 822 | 0 | 0 | 283 |
| `rv64ui-v-slliw` | v- | 1/18 | 18468 | 1084 | 214 | 205 | 0 | 0 | 94 | 6 | 1 | 1726 | 0 | 822 | 0 | 0 | 284 |
| `rv64ui-v-sllw` | v- | 2/18 | 28692 | 2582 | 325 | 286 | 0 | 0 | 140 | 5 | 1 | 3355 | 0 | 1433 | 0 | 0 | 428 |
| `rv64ui-v-slti` | v- | 14/18 | 18358 | 1085 | 213 | 205 | 0 | 0 | 94 | 6 | 1 | 1726 | 0 | 822 | 0 | 0 | 283 |
| `rv64ui-v-sltiu` | v- | 16/18 | 18358 | 1085 | 213 | 205 | 0 | 0 | 94 | 6 | 1 | 1726 | 0 | 822 | 0 | 0 | 283 |
| `rv64ui-v-sltu` | v- | 15/18 | 19206 | 1122 | 219 | 214 | 0 | 0 | 93 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 293 |
| `rv64ui-v-sra` | v- | 7/18 | 19173 | 1084 | 217 | 211 | 0 | 0 | 93 | 5 | 1 | 1726 | 0 | 822 | 0 | 0 | 289 |
| `rv64ui-v-srai` | v- | 8/18 | 18234 | 1104 | 200 | 193 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 273 |
| `rv64ui-v-sraiw` | v- | 9/18 | 18547 | 1084 | 214 | 205 | 0 | 0 | 94 | 6 | 1 | 1726 | 0 | 822 | 0 | 0 | 284 |
| `rv64ui-v-sraw` | v- | 10/18 | 28610 | 2584 | 318 | 283 | 0 | 0 | 140 | 8 | 1 | 3355 | 0 | 1433 | 0 | 0 | 423 |
| `rv64ui-v-srl` | v- | 3/18 | 28647 | 2573 | 309 | 276 | 0 | 0 | 141 | 5 | 1 | 3355 | 0 | 1433 | 0 | 0 | 414 |
| `rv64ui-v-srli` | v- | 4/18 | 18283 | 1115 | 210 | 202 | 0 | 0 | 92 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 282 |
| `rv64ui-v-srliw` | v- | 5/18 | 18485 | 1078 | 214 | 205 | 0 | 0 | 94 | 6 | 1 | 1726 | 0 | 822 | 0 | 0 | 284 |
| `rv64ui-v-srlw` | v- | 6/18 | 28690 | 2582 | 319 | 285 | 0 | 0 | 141 | 5 | 1 | 3355 | 0 | 1433 | 0 | 0 | 423 |
| `rv64ui-v-st_ld` | v- | 15/18 | 38139 | 3035 | 467 | 381 | 0 | 0 | 248 | 8 | 1 | 4586 | 0 | 2667 | 0 | 0 | 619 |
| `rv64ui-v-sub` | v- | 5/18 | 19132 | 1085 | 217 | 211 | 0 | 0 | 93 | 5 | 1 | 1726 | 0 | 822 | 0 | 0 | 290 |
| `rv64ui-v-subw` | v- | 6/18 | 19169 | 1116 | 220 | 212 | 0 | 0 | 93 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 293 |
| `rv64ui-v-sw` | v- | 12/18 | 29100 | 1615 | 315 | 327 | 0 | 0 | 122 | 6 | 6 | 2921 | 0 | 2020 | 0 | 1 | 444 |
| `rv64ui-v-xor` | v- | 11/18 | 19425 | 1130 | 218 | 210 | 0 | 0 | 95 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 292 |
| `rv64ui-v-xori` | v- | 12/18 | 18149 | 1107 | 199 | 189 | 0 | 0 | 94 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 272 |
| `rv64um-v-div` | v- | 5/18 | 17908 | 1107 | 203 | 198 | 0 | 0 | 93 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 278 |
| `rv64um-v-divu` | v- | 6/18 | 17866 | 1099 | 195 | 187 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 269 |
| `rv64um-v-divuw` | v- | 11/18 | 17850 | 1102 | 195 | 188 | 0 | 0 | 94 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 269 |
| `rv64um-v-divw` | v- | 10/18 | 17892 | 1107 | 203 | 198 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 278 |
| `rv64um-v-mul` | v- | 1/18 | 19155 | 1120 | 206 | 201 | 0 | 0 | 94 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 279 |
| `rv64um-v-mulh` | v- | 2/18 | 19246 | 1122 | 220 | 213 | 0 | 0 | 86 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 294 |
| `rv64um-v-mulhsu` | v- | 3/18 | 19246 | 1122 | 220 | 213 | 0 | 0 | 86 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 294 |
| `rv64um-v-mulhu` | v- | 4/18 | 19306 | 1126 | 219 | 213 | 0 | 0 | 87 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 294 |
| `rv64um-v-mulw` | v- | 9/18 | 19119 | 1124 | 220 | 212 | 0 | 0 | 94 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 294 |
| `rv64um-v-rem` | v- | 7/18 | 17889 | 1107 | 203 | 199 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 278 |
| `rv64um-v-remu` | v- | 8/18 | 17893 | 1107 | 203 | 198 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 278 |
| `rv64um-v-remuw` | v- | 13/18 | 17784 | 1096 | 201 | 197 | 0 | 0 | 93 | 5 | 1 | 1726 | 0 | 822 | 0 | 0 | 274 |
| `rv64um-v-remw` | v- | 12/18 | 17794 | 1095 | 201 | 197 | 0 | 0 | 93 | 5 | 1 | 1726 | 0 | 822 | 0 | 0 | 274 |
| `rv64uzba-v-add_uw` | v- | 3/18 | 18997 | 1134 | 206 | 198 | 0 | 0 | 106 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 280 |
| `rv64uzba-v-sh1add` | v- | 4/18 | 19005 | 1131 | 206 | 198 | 0 | 0 | 106 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 280 |
| `rv64uzba-v-sh1add_uw` | v- | 5/18 | 19012 | 1130 | 206 | 199 | 0 | 0 | 105 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 280 |
| `rv64uzba-v-sh2add` | v- | 6/18 | 19005 | 1131 | 206 | 198 | 0 | 0 | 106 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 280 |
| `rv64uzba-v-sh2add_uw` | v- | 7/18 | 19012 | 1130 | 206 | 199 | 0 | 0 | 105 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 280 |
| `rv64uzba-v-sh3add` | v- | 8/18 | 19005 | 1131 | 206 | 198 | 0 | 0 | 106 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 280 |
| `rv64uzba-v-sh3add_uw` | v- | 9/18 | 19012 | 1130 | 206 | 199 | 0 | 0 | 105 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 280 |
| `rv64uzba-v-slli_uw` | v- | 10/18 | 18371 | 1114 | 199 | 191 | 0 | 0 | 106 | 5 | 1 | 1726 | 0 | 822 | 0 | 0 | 272 |
| `rv64uzbb-v-andn` | v- | 11/18 | 19068 | 1109 | 207 | 198 | 0 | 0 | 97 | 4 | 1 | 1726 | 0 | 822 | 0 | 0 | 279 |
| `rv64uzbb-v-max` | v- | 18/18 | 19030 | 1123 | 211 | 201 | 0 | 0 | 97 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 285 |
| `rv64uzbb-v-maxu` | v- | 1/18 | 19087 | 1124 | 211 | 200 | 0 | 0 | 105 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 285 |
| `rv64uzbb-v-min` | v- | 2/18 | 19023 | 1122 | 211 | 200 | 0 | 0 | 97 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 285 |
| `rv64uzbb-v-minu` | v- | 3/18 | 19066 | 1122 | 211 | 200 | 0 | 0 | 106 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 285 |
| `rv64uzbb-v-orn` | v- | 5/18 | 28248 | 2363 | 300 | 269 | 0 | 0 | 246 | 4 | 1 | 3355 | 0 | 1433 | 0 | 0 | 400 |
| `rv64uzbb-v-rev8` | v- | 6/18 | 18256 | 1111 | 198 | 189 | 0 | 0 | 106 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 276 |
| `rv64uzbb-v-rol` | v- | 7/18 | 28314 | 2394 | 311 | 277 | 0 | 0 | 261 | 3 | 1 | 3355 | 0 | 1433 | 0 | 0 | 414 |
| `rv64uzbb-v-rolw` | v- | 8/18 | 28454 | 2599 | 313 | 273 | 0 | 0 | 154 | 5 | 1 | 3355 | 0 | 1433 | 0 | 0 | 419 |
| `rv64uzbb-v-ror` | v- | 9/18 | 28217 | 2450 | 289 | 266 | 0 | 0 | 234 | 5 | 1 | 3355 | 0 | 1433 | 0 | 0 | 393 |
| `rv64uzbb-v-rori` | v- | 10/18 | 18372 | 1114 | 201 | 192 | 0 | 0 | 106 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 279 |
| `rv64uzbb-v-rorw` | v- | 12/18 | 19102 | 1122 | 211 | 201 | 0 | 0 | 97 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 285 |
| `rv64uzbb-v-xnor` | v- | 15/18 | 28183 | 2367 | 279 | 253 | 0 | 0 | 234 | 3 | 1 | 3355 | 0 | 1433 | 0 | 0 | 380 |
| `rv64uzbc-v-clmul` | v- | 17/18 | 19208 | 1116 | 208 | 199 | 0 | 0 | 94 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 280 |
| `rv64uzbc-v-clmulh` | v- | 18/18 | 19167 | 1116 | 207 | 200 | 0 | 0 | 94 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 279 |
| `rv64uzbc-v-clmulr` | v- | 1/18 | 19164 | 1120 | 206 | 201 | 0 | 0 | 94 | 3 | 1 | 1726 | 0 | 822 | 0 | 0 | 279 |
| `rv64uzbkb-v-brev8` | v- | 2/18 | 18249 | 1137 | 209 | 201 | 0 | 0 | 112 | 3 | 0 | 1726 | 0 | 822 | 0 | 0 | 287 |
| `rv64uzbkb-v-pack` | v- | 3/18 | 28656 | 2383 | 312 | 279 | 0 | 0 | 260 | 4 | 0 | 3355 | 0 | 1433 | 0 | 0 | 411 |
| `rv64uzbkb-v-packh` | v- | 4/18 | 19281 | 1123 | 212 | 202 | 0 | 0 | 101 | 3 | 0 | 1726 | 0 | 822 | 0 | 0 | 285 |
| `rv64uzbkb-v-packw` | v- | 5/18 | 19087 | 1141 | 215 | 212 | 0 | 0 | 109 | 3 | 0 | 1726 | 0 | 822 | 0 | 0 | 293 |
| `rv64uzbkx-v-xperm4` | v- | 6/18 | 28703 | 2574 | 314 | 276 | 0 | 0 | 140 | 8 | 1 | 3355 | 0 | 1433 | 0 | 0 | 419 |
| `rv64uzbkx-v-xperm8` | v- | 7/18 | 29557 | 2582 | 317 | 274 | 0 | 0 | 140 | 5 | 1 | 3355 | 0 | 1433 | 0 | 0 | 419 |
| `rv64uzbs-v-bclr` | v- | 8/18 | 28336 | 2397 | 294 | 265 | 0 | 0 | 248 | 6 | 0 | 3355 | 0 | 1433 | 0 | 0 | 393 |
| `rv64uzbs-v-bclri` | v- | 9/18 | 18522 | 1131 | 214 | 204 | 0 | 0 | 113 | 5 | 0 | 1726 | 0 | 822 | 0 | 0 | 286 |
| `rv64uzbs-v-bext` | v- | 10/18 | 28531 | 2631 | 317 | 278 | 0 | 0 | 165 | 4 | 0 | 3355 | 0 | 1433 | 0 | 0 | 417 |
| `rv64uzbs-v-bexti` | v- | 11/18 | 18363 | 1115 | 202 | 192 | 0 | 0 | 110 | 3 | 0 | 1726 | 0 | 822 | 0 | 0 | 272 |
| `rv64uzbs-v-binv` | v- | 12/18 | 28132 | 2380 | 316 | 284 | 0 | 0 | 283 | 4 | 0 | 3355 | 0 | 1433 | 0 | 0 | 416 |
| `rv64uzbs-v-binvi` | v- | 13/18 | 18348 | 1097 | 205 | 193 | 0 | 0 | 113 | 4 | 0 | 1726 | 0 | 822 | 0 | 0 | 275 |
| `rv64uzbs-v-bset` | v- | 14/18 | 28653 | 2641 | 311 | 279 | 0 | 0 | 167 | 6 | 0 | 3355 | 0 | 1433 | 0 | 0 | 410 |
| `rv64uzbs-v-bseti` | v- | 15/18 | 18586 | 1132 | 215 | 204 | 0 | 0 | 113 | 5 | 0 | 1726 | 0 | 822 | 0 | 0 | 287 |
| `rv64uzfh-v-fadd` | v- | 16/18 | 27787 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3395 | 0 | 1433 | 0 | 0 | 410 |
| `rv64uzfh-v-fclass` | v- | 17/18 | 17753 | 1095 | 198 | 188 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 271 |
| `rv64uzfh-v-fcmp` | v- | 18/18 | 27435 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3379 | 0 | 1433 | 0 | 0 | 406 |
| `rv64uzfh-v-fcvt` | v- | 1/18 | 27377 | 2412 | 277 | 257 | 0 | 0 | 207 | 5 | 1 | 3371 | 0 | 1433 | 0 | 0 | 391 |
| `rv64uzfh-v-fcvt_w` | v- | 2/18 | 38304 | 3749 | 366 | 339 | 0 | 0 | 323 | 8 | 1 | 5116 | 0 | 2044 | 0 | 0 | 538 |
| `rv64uzfh-v-fdiv` | v- | 3/18 | 27536 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3383 | 0 | 1433 | 0 | 0 | 407 |
| `rv64uzfh-v-fmadd` | v- | 4/18 | 27949 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3403 | 0 | 1433 | 0 | 0 | 412 |
| `rv64uzfh-v-fmin` | v- | 5/18 | 28419 | 2429 | 291 | 268 | 0 | 0 | 210 | 5 | 1 | 3427 | 0 | 1433 | 0 | 0 | 418 |
| `rv64uzfh-v-ldst` | v- | 6/18 | 28545 | 1598 | 377 | 313 | 0 | 0 | 225 | 6 | 1 | 2903 | 0 | 1988 | 0 | 0 | 499 |
| `rv64uzfh-v-move` | v- | 7/18 | 18395 | 1063 | 195 | 187 | 0 | 0 | 93 | 5 | 1 | 1726 | 0 | 822 | 0 | 0 | 276 |
| `rv64uzfh-v-recoding` | v- | 8/18 | 26853 | 2413 | 277 | 260 | 0 | 0 | 207 | 6 | 1 | 3357 | 0 | 1433 | 0 | 0 | 383 |
| `rv64uzicond-v-czero_eqz` | v- | 9/18 | 19129 | 1122 | 223 | 214 | 0 | 0 | 93 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 296 |
| `rv64uzicond-v-czero_nez` | v- | 10/18 | 19004 | 1112 | 213 | 203 | 0 | 0 | 95 | 2 | 1 | 1726 | 0 | 822 | 0 | 0 | 285 |
