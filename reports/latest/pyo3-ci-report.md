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

## All 2898 results

<details>
<summary>Full per-test table</summary>

| Test | Suite | Status | cycles | wall |
|---|---|---|---|---|
| test_bac_v2_cl.TestBACV2CommitEventSurvivesCommitSquash::test_a_commit_on_a_squash_cycle_still_reaches_the_bpu | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2CommitEventSurvivesCommitSquash::test_an_unknown_bb_idx_on_a_squash_cycle_dispatches_nothing | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2CommitEventSurvivesCommitSquash::test_the_squash_itself_still_issues_on_that_cycle | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_clear_states_flushes_the_ftq_and_clears_the_ack_slot | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_clear_states_sets_running_at_committed_pc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_default_parameters_match_spec_9 | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_dut_constructs_its_own_bpu_and_ftq_children | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_initial_status_is_idle | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_reset_signal_returns_the_thread_to_idle_at_the_initial_pc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_a_rejected_predict_emits_no_ft_and_holds_bacpc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_a_retry_after_a_reject_succeeds_when_a_pool_frees | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_branch_less_ft_ends_at_the_window_edge_and_is_not_a_bb_end | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_ft_is_exactly_one_per_cycle | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_ft_never_crosses_a_window | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_terminal_ft_end_uses_the_compressed_size | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_terminal_ft_ends_exclusive_at_the_terminal | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_the_retry_re_reads_the_window | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_window_edge_ft_for_an_all_not_taken_member_set | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2GenerationEntryTest::test_ftq_full_at_entry_emits_no_ft_and_holds_bacpc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2GenerationEntryTest::test_ftqfull_at_entry_is_latched_even_without_a_tick_req | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_bacpc_is_advanced_only_after_the_insert | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_insert_precedes_the_ftqfull_latch | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_post_insert_fullness_does_not_lose_the_ft | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_predict_is_called_even_for_a_branch_less_ft | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_prediction_accepted_is_always_inserted | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_window_read_precedes_the_predict_call | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_an_invalid_resteer_request_is_a_no_op | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_ack_is_a_registered_single_cycle_pulse | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_ack_is_per_thread | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_carries_a_bb_idx_and_bac_requires_it | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_is_buffered_unconditionally | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_is_consumed_after_the_auto_transition_and_overrides_it | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_is_running_two_cycles_later | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_redirects_bacpc_and_flushes_the_ftq | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_the_ack_survives_a_higher_priority_squash | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_the_first_post_resteer_ft_forms_at_the_redirected_pc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2RetryNeverDrop::test_a_resteer_under_backpressure_is_not_discarded | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2RetryNeverDrop::test_a_squash_under_backpressure_is_not_discarded | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2RetryNeverDrop::test_the_resteer_buffer_is_the_retry_mechanism | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_members_below_start_pc_are_pre_filtered_out | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_records_outside_the_window_base_are_ignored | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_slot_bits_use_the_absolute_window_offset | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_slot_size_fields_are_indexed_absolutely_too | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_the_prediction_records_keep_absolute_offsets | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_commit_squash_cancels_this_cycle_prediction | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_decode_squash_cancels_this_cycle_prediction | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_decode_squash_is_one_cycle_latency | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_first_post_redirect_ft_forms_next_cycle_at_the_corrected_pc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_squash_flushes_the_ftq_in_the_same_cycle | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusEnum::test_no_deleted_ports_exist | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusEnum::test_no_v1_deleted_state_exists | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusEnum::test_status_enum_is_exactly_four_states | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_commit_trap_squash_enters_squashing | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_ftq_not_ready_leaves_idle | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_ftqfull_to_running_when_the_ftq_frees | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_idle_to_running_when_ftq_ready | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_only_the_documented_transitions_exist | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_reject_stall_is_not_a_state | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_running_to_ftqfull_when_the_ftq_is_full | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_squashing_auto_transitions_to_running | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_squashing_lasts_exactly_one_cycle | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestInstSizeConventionBoundary::test_a_commit_origin_corrective_converts_bytes_to_the_enum | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestInstSizeConventionBoundary::test_a_two_byte_branch_converts_to_zero | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestL2ConfigPassThrough::test_enabling_at_bac_reaches_the_bpu | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestL2ConfigPassThrough::test_the_default_leaves_the_bpu_one_cycle | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_commit_mispredict_anchors_at_the_mispredicting_insts_row | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_commit_type0_squash_anchors_at_the_latched_head_row | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_commit_type0_unreachable_latch_raises | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_constructed_squash_freed_younger_equals_flushed_minus_anchor | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_decode_mispredict_anchors_at_the_dec_bb_idx | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_resteer_anchors_at_the_row_it_carries | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_a_younger_squash_is_dropped_while_the_slot_is_occupied | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_outstanding_squash_survives_many_ticks_of_backpressure | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_redirect_is_applied_immediately_not_on_landing | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_status_holds_squashing_until_the_squash_lands | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_bc_drain_stall_has_no_effect_on_bac | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_commit_type0_no_anchor_sentinel_raises | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_absent_latch_falls_to_the_ft_covering_the_pc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_anchor_is_the_ft_stamped_row | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_unreachable_latch_with_no_covering_entry_raises | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_the_anchor_is_read_from_each_request_not_latched | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_type0_commit_anchor_ignores_cur_bb_idx | block-BACV2 | PASS | - | 0 |
| test_harness_bacv2::test_conftest_import_strategy_resolves_real_pymtl3 | block-BACV2 | PASS | - | 0 |
| test_harness_bacv2::test_conftest_import_strategy_uses_the_o3_shim | block-BACV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBatchLookupIsPureRead::test_allocates_no_checkpoint_and_leaves_sm_untouched | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBatchLookupIsPureRead::test_count_selects_the_members_and_zero_count_reads_nothing | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBatchLookupIsPureRead::test_returns_the_counter_values_as_a_taken_mask | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_counters_are_per_branch_not_global | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_saturates_at_strong_not_taken_0 | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_saturates_at_strong_taken_3 | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_weak_and_strong_taken_boundary_flips_the_prediction | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_weak_not_taken_is_0_and_predicts_not_taken | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBpuConfigSurface::test_the_bpu_config_gate_accepts_bimodal | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBpuConfigSurface::test_the_bpu_with_bimodal_composes_a_cpred_child | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestBpuConfigSurface::test_the_class_the_bpu_names_for_bimodal_is_real_and_on_contract | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestCpredV2PortSurface::test_exposes_every_frozen_cpred_v2_port | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestCpredV2PortSurface::test_request_ports_carry_the_frozen_request_types | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestCpredV2PortSurface::test_surface_is_identical_to_gshare_v2 | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_a_request_buffered_in_the_reset_cycle_does_not_survive_it | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_reset_clears_every_counter | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_reset_clears_the_checkpoint_list | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_reset_clears_the_next_counter_shadow | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_reset_zeroes_both_ghr_images | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_the_dut_still_predicts_after_a_reset | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_chkpt_alloc_returns_a_live_index_and_grows_occupancy | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_chkpt_alloc_stores_the_passed_ghr_even_when_it_differs_from_live | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_chkpt_alloc_stores_the_passed_ghr_snapshot | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_chkpt_ghr_at_is_none_for_a_never_allocated_or_out_of_range_index | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_set_ghr_is_visible_on_the_next_cycle_not_the_current_one | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_at_the_tail_is_a_no_op_on_the_list | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_does_not_release_the_anchor | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_does_not_write_the_ghr_register | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_truncates_strictly_younger_checkpoints | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestAssertionA::test_assertion_a_fires_when_a_commit_names_an_older_row | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestAssertionA::test_assertion_a_is_not_an_index_comparison | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestAssertionA::test_assertion_a_never_fires_over_a_commit_stream | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestBulkSquashTruncatesCpredChain::test_a_bulk_squash_truncates_the_cpred_checkpoint_chain | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestBulkSquashTruncatesCpredChain::test_a_corrective_still_truncates_via_its_train_not_a_second_port | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI1PerPredictCheck::test_a_predict_on_an_allocation_free_path_stays_silent | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI1PerPredictCheck::test_a_stale_ckpt_image_at_a_predict_fires_the_counter | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_a_squash_truncation_is_counted_as_a_release | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_k_cnt_nonzero_is_a_pulse_not_an_invariant | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_A_and_I1_counters_are_enforced_not_merely_exported | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_assertion_fails_the_run_on_a_genuine_leak | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_exported_counter_is_the_asserted_expression | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_i1_conjunct_of_the_gate_is_reachable | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_live_term_balances_at_every_settled_pass | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_live_term_is_load_bearing | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3AnbPolicy::test_an_all_not_taken_member_set_arms_anb | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3AnbPolicy::test_only_count_zero_leaves_anb_clear | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3Bitmap::test_a_second_ending_ft_in_the_same_window_overwrites_not_merges | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3Bitmap::test_bb_n_plus_1_allocation_does_not_disturb_bb_n_row | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3Bitmap::test_bitmap_is_not_the_ft_relative_index | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3Bitmap::test_bitmap_sets_exactly_the_member_offsets | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3BranchlessFT::test_count_zero_leaves_the_previous_bitmap_untouched | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3BranchlessFT::test_count_zero_returns_cur_bb_idx_and_arms_no_anb | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3EntryAllocation::test_anb_set_allocates_a_row_and_a_checkpoint_with_the_live_ghr | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3EntryAllocation::test_no_anb_means_no_allocation | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3IBFormationAssert::test_a_non_pushing_class_below_the_terminal_is_a_formation_error | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3IBFormationAssert::test_a_one_below_the_terminal_is_a_formation_error | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3IBFormationAssert::test_a_well_formed_member_set_passes_the_formation_check | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3PoolsShortReject::test_pools_short_rejects_without_any_side_effect | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_always_taken_classes_are_forced_taken | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_conditional_members_take_their_counter_opinion | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_empty_ras_return_terminal_is_demoted_too | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_no_taken_record_yields_terminal_minus_one_and_zero_target | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_only_records_up_to_the_terminal_push_history | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_targetless_taken_terminal_is_demoted_at_the_producer | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_terminal_is_the_lowest_taken_record | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_terminal_target_comes_from_the_btb_record | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3WriteEntryOrdering::test_same_cycle_alloc_and_write_entry_leaves_the_written_row | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3WriteEntryOrdering::test_the_rows_checkpoint_is_the_one_the_entry_allocated | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Accounting::test_allocation_accounting_balances_over_a_long_sequence | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Accounting::test_the_accounting_counter_notices_a_missing_release | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4BitmapResidency::test_a_pre_terminal_member_reads_bb_n_image_after_bb_n1_predicts | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_a_commit_frees_every_strictly_older_row_and_spares_its_own | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_a_squash_never_reads_or_writes_the_latch | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_an_unreachable_latch_asserts_instead_of_draining_the_list | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_detector_is_inert_without_attached_views | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_release_path_is_inert_until_the_first_commit | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_stall_detector_fires_after_a_bounded_number_of_cycles | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_stall_detector_stays_quiet_while_any_conjunct_is_false | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_walk_is_bounded_per_cycle_and_resumes_from_the_retained_latch | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_a_commit_matching_the_head_does_not_release | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_a_commit_naming_a_newer_row_releases_the_head_row_and_its_ckpt | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_releasing_a_row_whose_ckpt_was_never_allocated_is_safe | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_two_releases_on_one_head_do_not_double_free | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4ReleaseNonDegeneracy::test_a_commit_naming_a_gap_row_walks_the_head_up_to_it | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4ReleaseNonDegeneracy::test_the_head_naming_commit_is_inert_while_rows_are_live | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Backpressure::test_a_second_squash_does_not_displace_the_first | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Backpressure::test_rdy_is_false_while_a_squash_is_outstanding | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5BulkSquash::test_a_type_zero_squash_never_trains_even_when_taken | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5BulkSquash::test_a_type_zero_squash_truncates_without_training_or_writing_ghr | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5CorrectiveTrain::test_the_resolve_trains_at_the_rows_ckpt_image_not_the_live_ghr | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Kcnt::test_a_corrective_uses_the_derived_k_cnt_for_g_prime | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Kcnt::test_g_prime_is_h0_shifted_by_k_plus_one_or_the_taken_bit | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Kcnt::test_k_cnt_is_the_prefix_popcount_of_the_row_bitmap | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Kcnt::test_the_window_guard_forces_k_cnt_to_zero | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Promotion::test_zs_own_marked_commit_releases_the_row_it_inherited | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5ReachabilityAssert::test_an_unreachable_in_range_anchor_asserts | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5TruncationAndAnb::test_g_prime_survives_the_same_pass_squash_to | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5TruncationAndAnb::test_the_corrective_re_arms_anb | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5TruncationAndAnb::test_the_retained_row_is_the_anchor_and_its_image_is_intact | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5TruncationAndAnb::test_younger_rows_and_checkpoints_are_truncated | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestOneOwnerBothPoolsSameAnchor::test_a_mispredict_squash_truncates_both_pools_at_the_same_anchor | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestOneOwnerBothPoolsSameAnchor::test_a_tail_anchor_frees_zero_rows | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestOneOwnerBothPoolsSameAnchor::test_a_type0_resteer_squash_truncates_both_pools_at_the_same_anchor | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestOneOwnerBothPoolsSameAnchor::test_the_corrective_truncates_the_ckpt_chain_to_the_anchor | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSec15MispredSquashPulse::test_one_accepted_corrective_is_exactly_one_pulse_even_if_reissued | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_a_flushed_row_released_before_the_gate_is_not_an_orphan | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_a_strand_with_room_in_the_arena_is_not_yet_fatal | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_the_anchor_and_strictly_younger_rows_are_excluded | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_the_ftq_records_the_distinct_bb_idx_it_discards_on_a_flush | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_the_gate_fires_when_a_strand_saturates_the_arena | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_direct_call_consumes_a_target_slot | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_direct_uncond_consumes_a_target_slot_and_stores_its_target | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[1-False-False-False-Return] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[2-True-False-False-CallDirect] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[3-True-True-False-CallIndirect] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[5-False-False-True-DirectUncond] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[6-False-True-False-IndirectCond] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[7-False-True-True-IndirectUncond] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_return_consumes_no_target_slot | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_an_indirect_consumes_no_target_slot | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallGateObservedTaken::test_a_not_taken_corrective_does_not_install | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallGateObservedTaken::test_an_uncond_corrective_installs_with_a_not_taken_payload | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallIssuance::test_a_non_directcond_class_ignores_the_filter | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallIssuance::test_a_nonresident_directcond_installs | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallIssuance::test_a_resident_directcond_still_emits_an_install | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallIssuance::test_the_window_test_precedes_the_bitmap_test | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallPathGating::test_a_bulk_squash_does_not_install | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallPathGating::test_the_commit_path_does_not_install | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallPortDiscipline::test_the_install_is_issued_through_the_update_port | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestL5BtbInstall::test_a_taken_corrective_installs_a_btb_record | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestL5BtbInstall::test_the_installed_inst_size_uses_the_one_bit_convention | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestL5BtbInstall::test_the_installed_record_lands_in_the_branchs_own_window | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_a_zero_latency_with_l2_enabled_is_rejected | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_enabling_builds_the_l2_geometry | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_latency_below_one_without_l2_is_not_rejected | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_predict_latency_is_stored_and_defaults_to_two | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_the_default_configuration_builds_no_l2_array | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2IsInertUntilLatencyOpens::test_nothing_ever_reaches_the_l2_array | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2IsInertUntilLatencyOpens::test_the_l2_ports_are_never_called_by_the_one_cycle_path | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2IsInertUntilLatencyOpens::test_the_same_predict_gives_the_same_response_either_way | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_a_none_anchor_raises_rather_than_naming_row_zero[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_a_none_anchor_raises_rather_than_naming_row_zero[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_a_resolve_for_a_dead_row_raises[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_a_resolve_for_a_dead_row_raises[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_severing_the_arm_by_class_drives_the_census_to_zero[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_severing_the_arm_by_class_drives_the_census_to_zero[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_the_census_counts_every_counter_write_the_arm_performs[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_the_census_counts_every_counter_write_the_arm_performs[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCounterStrengthensOnCorrectResolutions::test_a_stably_not_taken_member_pulls_its_counter_down[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCounterStrengthensOnCorrectResolutions::test_a_stably_not_taken_member_pulls_its_counter_down[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCounterStrengthensOnCorrectResolutions::test_a_stably_taken_conditional_saturates_its_counter[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCounterStrengthensOnCorrectResolutions::test_a_stably_taken_conditional_saturates_its_counter[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestOneWriterPerOccurrence::test_a_mispredict_produces_exactly_one_counter_write[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestOneWriterPerOccurrence::test_a_mispredict_produces_exactly_one_counter_write[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestOneWriterPerOccurrence::test_the_corrective_alone_writes_no_counter[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestOneWriterPerOccurrence::test_the_corrective_alone_writes_no_counter[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainHasNoCheckpointSideEffect::test_repeated_resolves_leave_the_anchor_checkpoint_intact[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainHasNoCheckpointSideEffect::test_repeated_resolves_leave_the_anchor_checkpoint_intact[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainingPredicate::test_a_btb_miss_resolving_not_taken_trains_and_installs_nothing[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainingPredicate::test_a_btb_miss_resolving_not_taken_trains_and_installs_nothing[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainingPredicate::test_a_btb_miss_resolving_taken_installs_and_seeds_the_counter[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainingPredicate::test_a_btb_miss_resolving_taken_installs_and_seeds_the_counter[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_construct_rejects_an_unknown_cpred_type | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_drain_complete_reports_drained_on_a_fresh_bpu | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_elaborates_with_bimodal | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_exposes_exactly_the_stub_bpu_port_surface | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_exposes_the_cur_bb_idx_squash_anchor | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_port_request_types_match_the_stub | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_squash_req_carries_rdy_and_returns_a_resp | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[br_type] | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[inst_size] | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[is_call] | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[is_indirect] | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[is_return] | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[is_uncond] | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[target] | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_disagreeing_reinstall_still_promotes_its_way | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_full_set_evicts_the_least_recently_used_way | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_later_install_leaves_the_windows_sibling_records_untouched | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_later_install_overwrites_the_pool_slot_it_reuses | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_target_repair_keeps_the_slot_it_already_held | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_aliasing_windows_are_distinguished_by_tag | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_all_sixteen_slots_of_a_window_may_hold_members | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_an_agreeing_reinstall_leaves_replacement_state_untouched | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_an_identical_reinstall_leaves_the_record_undisturbed | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_direct_call_records_consume_a_slot_and_return_call_records_do_not | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_evict_to_admit_never_hard_fails_a_whole_window_replacement | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_evicting_a_slot_consumer_frees_its_slot | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_flush_clears_every_way_of_every_set | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_install_is_visible_exactly_one_cycle_after_acceptance | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_invalid_ways_are_filled_before_a_valid_way_is_evicted | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_metadata_only_records_do_not_trip_the_slot_claim_assertion | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_pool_covers_a_real_dense_window_resident_plus_one | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_pool_depth_is_the_documented_null_plus_slots | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_pool_exhaustion_across_ways_is_reached_only_past_the_measured_max | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_record_fields_round_trip_through_an_install | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_record_pc_is_the_window_base_plus_twice_the_offset | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_records_of_one_set_read_their_targets_from_the_shared_pool | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_retag_without_pressure_releases_the_destroyed_tenants_slots | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_retagging_a_way_without_slot_pressure_hides_the_previous_tenant | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_return_and_indirect_records_consume_no_target_slot | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_same_address_slot_consuming_reinstall_reuses_its_slot | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_same_window_trainings_in_one_pass_coalesce_into_one_write | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_slot_consuming_record_without_a_slot_claim_fails_the_run | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_tag_is_masked_to_cfg_tag_bits | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_window_index_is_the_window_number_modulo_num_sets | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_window_read_miss_does_not_disturb_the_lru_order | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_window_read_of_an_empty_window_reports_the_base_and_no_records | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_window_read_promotes_the_hit_way_to_mru | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_window_read_returns_records_of_the_aligned_window | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_window_req_rdy_is_false_until_the_cycle_consumes_the_read | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_config_surface::test_supported_cpred_types_elaborate[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_config_surface::test_supported_cpred_types_elaborate[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_config_surface::test_unsupported_cpred_type_raises_at_construct | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_co_located_2b_slots_never_share_an_index[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_co_located_2b_slots_never_share_an_index[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_every_index_is_reachable_by_4b_branches[bimodal] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_every_index_is_reachable_by_4b_branches[gshare] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[10] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[11] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[12] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[1] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[2] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[3] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[4] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[5] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[6] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[7] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[8] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[9] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface::test_cpred_v2_implementation_exposes_the_frozen_port_surface[o3.bimodal_v2_cl] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface::test_cpred_v2_implementation_exposes_the_frozen_port_surface[o3.gshare_v2_cl] | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface::test_cpred_v2_implementations_have_identical_surfaces | block-BPredUnitV2 | PASS | - | 0 |
| test_cpred_v2_port_surface::test_cpred_v2_request_ports_carry_the_frozen_request_types | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupIsPureRead::test_batch_lookup_leaves_occupancy_next_and_alloc_counts_unchanged | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupIsPureRead::test_batch_lookup_reports_reading_beyond_count_as_zero | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupIsPureRead::test_batch_lookup_returns_counter_values | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupUsesASingleGhr::test_a_nonzero_ghr_moves_every_member_together | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupUsesASingleGhr::test_all_members_are_read_at_the_live_ghr | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestChkptAlloc::test_alloc_does_not_advance_the_register | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestChkptAlloc::test_alloc_reports_rdy_only_when_a_slot_is_free | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestChkptAlloc::test_stored_ghr_equals_the_value_passed | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestIntraUpProcessOrder::test_same_pass_set_ghr_and_squash_to_keeps_the_set_ghr_value | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestIntraUpProcessOrder::test_update_hist_applies_before_set_ghr_in_the_same_pass | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestReset::test_reset_clears_counters_and_checkpoints | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestReset::test_reset_seeds_both_ghr_images | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestSetGhrReq::test_set_ghr_is_masked_to_the_register_width | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestSetGhrReq::test_set_ghr_last_one_wins | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestSetGhrReq::test_set_ghr_overwrites_and_is_visible_next_cycle | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_does_not_write_the_register | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_truncates_strictly_younger_checkpoints | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_train_does_not_write_the_register | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_train_is_a_single_step_per_occurrence | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_train_saturates_at_both_ends | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_train_updates_the_counter_at_the_ckpt_image_index | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestUpdateHistAppliesInIssueOrder::test_issue_order_not_sorted_order | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestUpdateHistAppliesInIssueOrder::test_k_pushes_apply_in_issue_order | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestUpdateHistAppliesInIssueOrder::test_k_pushes_are_visible_at_the_next_ff | block-BPredUnitV2 | PASS | - | 0 |
| test_harness_dir_conftest::test_conftest_import_strategy_resolves_real_pymtl3 | block-BPredUnitV2 | PASS | - | 0 |
| test_harness_dir_conftest::test_conftest_import_strategy_uses_the_o3_shim | block-BPredUnitV2 | PASS | - | 0 |
| test_harness_v2::test_install_window_makes_the_window_readable_from_the_dut | block-BPredUnitV2 | PASS | - | 0 |
| test_harness_v2::test_make_btb_v2_elaborates | block-BPredUnitV2 | PASS | - | 0 |
| test_harness_v2::test_mk_records_places_records_at_the_given_offsets | block-BPredUnitV2 | PASS | - | 0 |
| test_harness_v2::test_tick_advances_the_dut | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_btb_flush_req_exists | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_btb_update_v2_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_btb_update_v2_round_trips | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_inst_size_encoding_boundary | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_window_record_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_window_record_round_trips_through_to_from_dict | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_window_req_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_window_req_round_trips | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_window_resp_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_btb_v2::test_window_resp_round_trips_records | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_batch_lookup_req_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_batch_lookup_req_round_trips_keys_and_count | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_batch_lookup_resp_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_batch_lookup_resp_round_trips_taken_mask | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_chkpt_alloc_req_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_chkpt_alloc_req_round_trips | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_set_ghr_req_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_set_ghr_req_round_trips | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_squash_to_req_has_no_ghr_field | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_squash_to_req_round_trips | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_train_req_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_train_req_round_trips_all_four_fields | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_update_hist_req_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_cpred_v2::test_update_hist_req_round_trips | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_req_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_req_round_trips | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_resp_carries_a_16_bit_taken_mask | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_resp_field_set_matches_spec | block-BPredUnitV2 | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_resp_round_trips_with_defaults | block-BPredUnitV2 | PASS | - | 0 |
| test_v1_v2_parity::test_v1_v2_commit_value_stream_parity | block-BPredUnitV2 | PASS | - | 7 |
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
| test_commit_cl.TestCommitRequiresBBIdx::test_a_head_without_a_bb_idx_fails_the_run | block-Commit | PASS | - | 0 |
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
| test_commit_cl.TestSMTArbitration::test_backfill_skips_empty_rob_thread | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_backfill_skips_stalled_head | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_no_backfill_past_squashed_head | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_no_backfill_past_trap_head | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_round_robin_selection | block-Commit | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_rr_pointer_rotates_across_cycles | block-Commit | PASS | - | 0 |
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
| test_decode_v2_members.TestCorrectionPayloadHasNoKcnt::test_case1_correction_payload_has_no_k_cnt | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestCorrectionPayloadHasNoKcnt::test_decode_bpu_correction_req_has_no_k_cnt_field | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestLeadingMemberTakenDetectedByCase2::test_case2_fires_for_an_interior_member | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestLeadingMemberTakenDetectedByCase2::test_leading_member_with_matching_fallthrough_is_not_case_2 | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestLeadingMemberTakenDetectedByCase2::test_nt_predicted_conditional_member_is_not_a_case2_candidate | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestMemberBtbMissStaysDead::test_btb_missed_conditional_member_produces_no_btb_miss_correction | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestMemberBtbMissStaysDead::test_member_carries_its_slot_and_bitmap_identity_to_decode | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestPredictedNotTakenLeadingMember::test_predicted_nt_leading_member_is_not_a_control_miss | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestPredictedNotTakenLeadingMember::test_predicted_nt_leading_member_with_live_bb_idx_is_not_a_control_miss | block-Decode | PASS | - | 0 |
| test_decode_v2_members.TestPredictedNotTakenLeadingMember::test_predicted_nt_member_still_reaches_rename | block-Decode | PASS | - | 0 |
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
| test_bb_idx_none_roundtrip::test_bac_backward_ctrl_bus_round_trips_none_commit_bb_idx | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_bpu_update_req_round_trips_none_bb_idx | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_bpu_update_req_still_round_trips_a_real_index | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_decode_rename_inst_round_trips_none_bb_idx | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_fetch_decode_inst_round_trips_none_bb_idx | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_ftq_ctrl_insert_req_round_trips_none_bb_idx | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_per_thread_fetch_tick_req_round_trips_none_bb_idx | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_rename_inst_round_trips_none_bb_idx | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_rob_head_inst_round_trips_none_bb_idx | block-FTQ | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_u8_raises_on_none | block-FTQ | PASS | - | 0 |
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
| test_ftq_cl_spec_alignment.TestClearHeadHistory::test_clear_head_history_clears_bpu_history_valid | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestClearHeadHistory::test_clear_head_history_is_callable | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestClearHeadHistory::test_clear_head_history_preserves_bb_idx | block-FTQ | PASS | - | 0 |
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
| test_ftq_cl_spec_v3_window.TestAllNotTakenEdgeFt::test_fetchs_stop_and_jump_predicate_is_false_for_the_all_nt_ft | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestAllNotTakenEdgeFt::test_is_branch_with_a_zero_pred_target_is_storable_and_readable | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_end_pc_is_exclusive | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_returns_none_when_empty | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_returns_none_when_no_entry_covers_the_pc | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_returns_none_when_the_covering_entry_has_no_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_returns_the_covering_entrys_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBrTypeEncodingIsTheLandedBranchType::test_a_return_record_consumes_no_target_slot_but_a_direct_cond_does | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBrTypeEncodingIsTheLandedBranchType::test_btb_v2_type_constants_equal_the_landed_enum | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestClearHeadHistoryPopPairing::test_a_clear_without_a_same_cycle_pop_is_a_protocol_violation | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestClearHeadHistoryPopPairing::test_a_cleared_and_popped_ft_is_not_readable | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestClearHeadHistoryPopPairing::test_clear_and_pop_may_pair_with_an_insert_in_the_same_cycle | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestDuplicateBbIdxIsLegal::test_no_bb_idx_keyed_lookup_dict_exists | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestDuplicateBbIdxIsLegal::test_two_fts_sharing_a_bb_idx_both_queue_and_read_back | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestDuplicateBbIdxIsLegal::test_window_fields_survive_the_sram_read_bubble_after_a_pop | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestGetOldestBpuAnchorMechanism::test_returns_invalid_when_empty | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestGetOldestBpuAnchorMechanism::test_returns_the_head_entrys_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestGetOldestBpuAnchorMechanism::test_two_fts_of_one_bb_yield_the_same_anchor | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestMaxDensityWindow::test_all_sixteen_slots_valid_round_trips | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestMaxDensityWindow::test_all_sixteen_slots_valid_with_all_two_byte_members | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestNoBbIdxInheritance::test_a_bac_to_ftq_insert_also_does_not_inherit | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestNoBbIdxInheritance::test_a_branchless_ft_keeps_its_own_bb_idx | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestNoBbIdxInheritance::test_a_branchless_ft_that_omits_bb_idx_reads_back_zero | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestNoBbIdxInheritance::test_the_propagation_state_does_not_exist | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestSlotsValidIsAbsolutelyIndexed::test_an_ft_starting_mid_window_keeps_its_members_at_window_offsets | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestSlotsValidIsAbsolutelyIndexed::test_slot_size_is_indexed_by_the_same_absolute_slot | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestWindowFieldsRoundTrip::test_window_base_slots_valid_and_slot_size_round_trip | block-FTQ | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestWindowFieldsRoundTrip::test_window_fields_default_to_zero_when_a_stale_caller_omits_them | block-FTQ | PASS | - | 0 |
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
| test_fetch_cl.TestAssertionANoBBLeftUnmarked::test_rv64ui_p_add_leaves_no_bb_unmarked | block-Fetch | PASS | - | 5 |
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
| test_fetch_cl.TestFTExitPreDecodeFacts::test_a_non_resident_control_transfer_at_the_ft_exit_is_a_branch | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFTExitPreDecodeFacts::test_a_plain_instruction_at_the_ft_exit_is_not_a_branch | block-Fetch | PASS | - | 0 |
| test_fetch_cl.TestFTExitPreDecodeFacts::test_the_ft_prediction_is_exit_scoped | block-Fetch | PASS | - | 0 |
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
| test_fetch_v2_window.TestAbsoluteSlotIndex::test_member_absent_from_slots_valid_is_not_a_member | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestAbsoluteSlotIndex::test_member_at_absolute_slot_4_of_the_window | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestAttachedFactsAndKcntAbsence::test_bb_idx_is_attached_to_every_instruction_including_members | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestAttachedFactsAndKcntAbsence::test_no_k_cnt_field_exists_anywhere | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestAttachedFactsAndKcntAbsence::test_no_k_cnt_on_the_fetch_tick_request_or_response | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestControlMissReExpression::test_predicted_taken_ft_with_a_control_exit_is_not_a_control_miss | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestControlMissReExpression::test_predicted_taken_ft_with_non_control_exit_is_a_control_miss | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestControlMissReExpression::test_trigger_fires_without_the_ft_level_mark_one | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestDownstreamTerminalInference::test_a_non_branch_instruction_carries_its_bb_idx_to_the_rob | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestDownstreamTerminalInference::test_an_interior_member_carries_its_bb_idx_to_the_rob | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestDownstreamTerminalInference::test_the_rob_carries_no_terminal_bit_at_all | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestFTExitFactsForBranchlessAndMemberFTs::test_all_nt_member_ft_edge_is_fetched_and_not_taken | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestFTExitFactsForBranchlessAndMemberFTs::test_branchless_ft_exit_is_not_a_branch | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestIsExitGeTest::test_no_instruction_after_the_crossing_exit_is_fetched | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestIsExitGeTest::test_rvc_instruction_crossing_the_window_edge_is_the_exit | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestPredictionStaysExitScoped::test_interior_member_does_not_inherit_the_ft_prediction | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestStopAndJumpV2::test_all_nt_edge_ft_does_not_jump_and_pops | block-Fetch | PASS | - | 0 |
| test_fetch_v2_window.TestStopAndJumpV2::test_taken_terminal_still_jumps_to_the_predicted_target | block-Fetch | PASS | - | 0 |
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
| test_per_thread_fetch_cl.TestPredictedBranch::test_pt290_predicted_branch_stops_fetch | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestPredictedBranch::test_pt291_predicted_branch_cleared_after | block-Fetch | PASS | - | 0 |
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
| test_per_thread_fetch_cl.TestSquashHandling::test_pt206_interrupt_pending_blocks_fetch | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt207_interrupt_with_delayed_commit | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt210_squashing_to_ftq_wait | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt212_squashing_delayed_commit_cleared | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt100_tick_idle_no_op | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt102_tick_running_with_valid_buffer | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt103_tick_icache_access_complete | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt104_tick_squashing_no_fetch | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt106_tick_drain_stall_blocks | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestWakeFromQuiesce::test_pt80_wake_sets_running | block-Fetch | PASS | - | 0 |
| test_per_thread_fetch_cl.TestWakeFromQuiesce::test_pt81_wake_updates_pending_status | block-Fetch | PASS | - | 0 |
| test_frontend_v2_compose.TestComposedPathStall::test_case2_fires_and_leaves_fetch_on_a_stale_head | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposedPathStall::test_frontend_recovers_from_a_dropped_head | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposedPathStall::test_mismatched_target_is_a_real_mispredict | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposedPathStall::test_the_frontend_keeps_making_progress_after_the_redirect | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_bb_idx_reaches_decode_to_rename | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_fetch_advances_past_the_first_ft | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_fetch_stamps_the_bpu_row_index | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_frontend_v2_children_are_wired | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_frontend_v2_constructs_and_resets | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_ft_flows_bac_ftq_fetch_decode | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_ftq_head_bb_idx_comes_from_the_bpu_row_allocator | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_the_path_does_not_park_before_the_end_of_the_run | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestScheduleSeedSweep::test_identical_outcomes_across_schedule_seeds | block-FrontEnd | PASS | - | 1 |
| test_frontend_v2_compose.TestScheduleSeedSweep::test_sweep_reaches_a_formed_ft | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestWindowAttach::test_member_bitmap_is_absolute_not_ft_relative | block-FrontEnd | PASS | - | 0 |
| test_frontend_v2_compose.TestWindowAttach::test_member_instruction_gets_absolute_slot | block-FrontEnd | PASS | - | 0 |
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
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFenceExecution::test_nonSpecInstReady_clears_sq_placeholder_non_spec | block-IEW | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFencePassThrough::test_fence_complete_alias_removed | block-IEW | PASS | - | 0 |
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
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_bc_iew_squash_propagates_to_writeback_pending | block-IEW | PASS | - | 0 |
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
| test_lq_core_cl.TestDesignBComputeAgeKey::test_all_loads_older_than_store_no_violation | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDesignBComputeAgeKey::test_committed_store_rescan_distance_beyond_sqsize | block-LQCore | PASS | - | 0 |
| test_lq_core_cl.TestDesignBComputeAgeKey::test_oldest_younger_wins_and_older_load_excluded | block-LQCore | PASS | - | 0 |
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
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_active_placeholder_holds_younger_load_positionally | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_aq_disable_barrier_releases_held_load | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_disabled_placeholder_not_counted_by_dispatch_walk | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_fence_placeholder_is_commit_gated_and_stores_nothing | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_insert_load_no_longer_accepts_is_fence_load_kwarg | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_insert_store_accepts_is_fence_store_and_barrier_kwargs | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_lq_entry_has_no_is_fence_load_field | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_no_barrier_entries_no_hold | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_no_fence_complete_chain_anywhere | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_no_separate_barrier_sets_or_insert_fence | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_placeholder_commit_marks_completed_and_clears_barrier | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_sq_entry_has_is_fence_store_and_barrier_fields | block-LSQParent | PASS | - | 0 |
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
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_active_placeholder_holds_younger_load | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_aq_load_execute_disables_placeholder | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_disable_barrier_ifc_exists_fence_complete_removed | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_disabled_placeholder_transparent_to_new_loads | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_insert_store_non_atomic_has_non_spec_false | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_no_placeholder_no_hold | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_nonSpecInstReady_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_nonSpecInstReady_clears_sq_non_spec | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_commit_drains_storesToWB_accounting | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_commit_releases_held_load | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_squash_invalidates_like_any_sq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_younger_load_proceeds_at_execute_while_held | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_younger_store_not_execute_gated_commit_order_release | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_lq_tag_forwards_to_lq_core | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_frag0_tag_calls_store_complete | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_frag1_tag_calls_store_complete_is_frag1 | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_tag_reads_tid_from_sq_entry | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_parent_dcache_resp_callee_ifc_exists | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_execute_load_rdy_false_when_all_slots_full | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_execute_load_rdy_when_all_slots_free | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_existing_single_load_still_works | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_first_free_slot_reused_after_tick | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_ports_capacity | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_slot_dict_fields | block-LSQParent | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_under_active_barrier_executes_first_cycle | block-LSQParent | PASS | - | 0 |
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
| test_rename_map_cl.TestP8RobIdxTagCAM::test_d7_out_of_window_tag_never_outranks_in_window | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_distance_ordering_selects_youngest_qualifying | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_duplicate_tag_assert_still_fires | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_restore_no_valid_slots_cam_miss | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_slot0_duplicate_save_exempt | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_trap_reseed_resets_next_free_first_save_overwrites | block-Rename | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_younger_invalidation_by_extended_distance | block-Rename | PASS | - | 0 |
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
| test_store_set_cl.TestSquash::test_squash_recompute_multi_ssid | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_recompute_positional_youngest_survivor | block-StoreSet | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_recompute_wraparound | block-StoreSet | PASS | - | 0 |
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
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_core_frontend_carries_the_v2_blocks | block-Testbench | PASS | - | 0 |
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_core_frontend_is_frontend_v2 | block-Testbench | PASS | - | 0 |
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_v2_core_exposes_the_testbench_surface | block-Testbench | PASS | - | 0 |
| test_o3_core_v2.TestElfOnV2Core::test_rv64ui_p_add_passes_on_v2 | block-Testbench | PASS | - | 6 |
| test_o3_core_v2.TestElfOnV2Core::test_v2_core_commits_instructions_and_retires_stores | block-Testbench | PASS | - | 5 |
| test_o3_core_v2.TestNackChainOrdering::test_elf_reaches_exit_on_every_schedule_seed | block-Testbench | PASS | - | 34 |
| test_o3_core_v2.TestNackChainOrdering::test_no_seed_stalls_the_frontend | block-Testbench | PASS | - | 34 |
| test_o3_core_v2.TestNackChainOrdering::test_the_sweep_actually_executed_the_frontend | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_riscv_tests_smoke_add | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-add:R-type addition] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addi:I-type add immediate] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addiw:IW-type add immediate] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addw:R-type add word] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-and:R-type AND] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-andi:I-type AND immediate] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-auipc:add upper immediate to PC] | block-Testbench | PASS | - | 2 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-beq:branch equal] | block-Testbench | FAIL | - | 2 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bge:branch greater equal] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bgeu:branch greater equal unsigned] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-blt:branch less than] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bltu:branch less than unsigned] | block-Testbench | FAIL | - | 2 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bne:branch not equal] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-fence_i:instruction fence] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-jal:jump and link] | block-Testbench | PASS | - | 2 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-jalr:jump and link register] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lb:load byte] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lbu:load byte unsigned] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-ld:load double] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lh:load half] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lhu:load half unsigned] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lui:load upper immediate] | block-Testbench | PASS | - | 2 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lw:load word] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lwu:load word unsigned] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-or:R-type OR] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-ori:I-type OR immediate] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sb:store byte] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sd:store double] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sh:store half] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sll:shift left logical] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slli:shift left logical immediate] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sllw:shift left logical word] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slt:set less than] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slti:set less than immediate] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sltiu:set less than immediate unsigned] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sltu:set less than unsigned] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sra:shift right arithmetic] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srai:shift right arithmetic immediate] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sraw:shift right arithmetic word] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srl:shift right logical] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srli:shift right logical immediate] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srlw:shift right logical word] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sub:R-type subtraction] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-subw:R-type sub word] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sw:store word] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-xor:R-type XOR] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-xori:I-type XOR immediate] | block-Testbench | PASS | - | 4 |
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
| hypervisor-p-2-stage_translation | p- | PASS | 1380 | 12 |
| hypervisor-p-2-stage_translation_implicit_load_error | p- | PASS | 1641 | 14 |
| hypervisor-p-2-stage_translation_implicit_load_error_hs | p- | PASS | 1816 | 15 |
| hypervisor-svadu-p-2-stage_translation_implicit_store_error | p- | PASS | 1722 | 14 |
| hypervisor-svadu-p-2-stage_translation_implicit_store_error_hs | p- | PASS | 1929 | 14 |
| rv64mi-p-breakpoint | p- | PASS | 3480 | 23 |
| rv64mi-p-csr | p- | PASS | 3552 | 24 |
| rv64mi-p-illegal | p- | PASS | 4578 | 30 |
| rv64mi-p-instret_overflow | p- | ERROR | - | 10 |
| rv64mi-p-ld-misaligned | p- | PASS | 1386 | 10 |
| rv64mi-p-lh-misaligned | p- | PASS | 1102 | 9 |
| rv64mi-p-lw-misaligned | p- | PASS | 1171 | 9 |
| rv64mi-p-ma_addr | p- | PASS | 1540 | 12 |
| rv64mi-p-ma_fetch | p- | ERROR | - | 13 |
| rv64mi-p-mcsr | p- | PASS | 1342 | 10 |
| rv64mi-p-pmpaddr | p- | ERROR | - | 10 |
| rv64mi-p-sbreak | p- | PASS | 1341 | 10 |
| rv64mi-p-scall | p- | PASS | 1259 | 10 |
| rv64mi-p-sd-misaligned | p- | PASS | 1482 | 11 |
| rv64mi-p-sh-misaligned | p- | PASS | 1123 | 9 |
| rv64mi-p-sw-misaligned | p- | PASS | 1164 | 9 |
| rv64mi-p-zicntr | p- | ERROR | - | 11 |
| rv64mzicbo-p-zero | p- | PASS | 1162 | 9 |
| rv64si-p-csr | p- | PASS | 2277 | 17 |
| rv64si-p-dirty | p- | PASS | 2339 | 16 |
| rv64si-p-icache-alias | p- | PASS | 2463 | 17 |
| rv64si-p-ma_fetch | p- | PASS | 1415 | 10 |
| rv64si-p-sbreak | p- | PASS | 1354 | 10 |
| rv64si-p-scall | p- | PASS | 1472 | 11 |
| rv64si-p-wfi | p- | PASS | 1173 | 9 |
| rv64ssvnapot-p-napot | p- | PASS | 1658 | 13 |
| rv64ua-p-amoadd_d | p- | PASS | 1081 | 9 |
| rv64ua-p-amoadd_w | p- | PASS | 1120 | 9 |
| rv64ua-p-amoand_d | p- | PASS | 1121 | 9 |
| rv64ua-p-amoand_w | p- | PASS | 1117 | 9 |
| rv64ua-p-amomax_d | p- | PASS | 1077 | 8 |
| rv64ua-p-amomax_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amomaxu_d | p- | PASS | 1077 | 9 |
| rv64ua-p-amomaxu_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amomin_d | p- | PASS | 1077 | 9 |
| rv64ua-p-amomin_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amominu_d | p- | PASS | 1077 | 9 |
| rv64ua-p-amominu_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amoor_d | p- | PASS | 1117 | 9 |
| rv64ua-p-amoor_w | p- | PASS | 1117 | 9 |
| rv64ua-p-amoswap_d | p- | PASS | 1121 | 9 |
| rv64ua-p-amoswap_w | p- | PASS | 1117 | 8 |
| rv64ua-p-amoxor_d | p- | PASS | 1125 | 9 |
| rv64ua-p-amoxor_w | p- | PASS | 1129 | 9 |
| rv64ua-p-lrsc | p- | PASS | 19290 | 119 |
| rv64uc-p-rvc | p- | PASS | 1666 | 12 |
| rv64ud-p-fadd | p- | PASS | 1913 | 14 |
| rv64ud-p-fclass | p- | PASS | 1233 | 10 |
| rv64ud-p-fcmp | p- | PASS | 2231 | 16 |
| rv64ud-p-fcvt | p- | PASS | 1841 | 14 |
| rv64ud-p-fcvt_w | p- | PASS | 3801 | 26 |
| rv64ud-p-fdiv | p- | PASS | 1739 | 13 |
| rv64ud-p-fmadd | p- | PASS | 2070 | 15 |
| rv64ud-p-fmin | p- | PASS | 2541 | 18 |
| rv64ud-p-ldst | p- | PASS | 1172 | 9 |
| rv64ud-p-move | p- | PASS | 2696 | 19 |
| rv64ud-p-recoding | p- | PASS | 1245 | 10 |
| rv64ud-p-structural | p- | PASS | 2023 | 14 |
| rv64uf-p-fadd | p- | PASS | 1913 | 14 |
| rv64uf-p-fclass | p- | PASS | 1217 | 10 |
| rv64uf-p-fcmp | p- | PASS | 2231 | 16 |
| rv64uf-p-fcvt | p- | PASS | 1630 | 13 |
| rv64uf-p-fcvt_w | p- | PASS | 3428 | 24 |
| rv64uf-p-fdiv | p- | PASS | 1663 | 12 |
| rv64uf-p-fmadd | p- | PASS | 2070 | 15 |
| rv64uf-p-fmin | p- | PASS | 2541 | 18 |
| rv64uf-p-ldst | p- | PASS | 1183 | 9 |
| rv64uf-p-move | p- | PASS | 1817 | 14 |
| rv64uf-p-recoding | p- | PASS | 1198 | 9 |
| rv64ui-p-add | p- | PASS | 2453 | 17 |
| rv64ui-p-addi | p- | PASS | 1630 | 12 |
| rv64ui-p-addiw | p- | PASS | 1621 | 12 |
| rv64ui-p-addw | p- | PASS | 2443 | 17 |
| rv64ui-p-and | p- | PASS | 2613 | 19 |
| rv64ui-p-andi | p- | PASS | 1609 | 12 |
| rv64ui-p-auipc | p- | PASS | 1053 | 9 |
| rv64ui-p-beq | p- | PASS | 2427 | 17 |
| rv64ui-p-bge | p- | PASS | 2726 | 19 |
| rv64ui-p-bgeu | p- | PASS | 2956 | 20 |
| rv64ui-p-blt | p- | PASS | 2429 | 17 |
| rv64ui-p-bltu | p- | PASS | 2643 | 19 |
| rv64ui-p-bne | p- | PASS | 2482 | 18 |
| rv64ui-p-fence_i | p- | PASS | 2097 | 15 |
| rv64ui-p-jal | p- | PASS | 1103 | 9 |
| rv64ui-p-jalr | p- | PASS | 1511 | 11 |
| rv64ui-p-lb | p- | PASS | 1671 | 12 |
| rv64ui-p-lbu | p- | PASS | 1671 | 13 |
| rv64ui-p-ld | p- | PASS | 2066 | 14 |
| rv64ui-p-ld_st | p- | PASS | 4452 | 29 |
| rv64ui-p-lh | p- | PASS | 1711 | 13 |
| rv64ui-p-lhu | p- | PASS | 1717 | 12 |
| rv64ui-p-lui | p- | PASS | 1065 | 8 |
| rv64ui-p-lw | p- | PASS | 1731 | 13 |
| rv64ui-p-lwu | p- | PASS | 1797 | 13 |
| rv64ui-p-ma_data | p- | PASS | 7654 | 49 |
| rv64ui-p-or | p- | PASS | 2670 | 18 |
| rv64ui-p-ori | p- | PASS | 1591 | 12 |
| rv64ui-p-sb | p- | PASS | 2308 | 17 |
| rv64ui-p-sd | p- | PASS | 2656 | 19 |
| rv64ui-p-sh | p- | PASS | 2374 | 17 |
| rv64ui-p-simple | p- | PASS | 1003 | 8 |
| rv64ui-p-sll | p- | PASS | 2573 | 18 |
| rv64ui-p-slli | p- | PASS | 1691 | 13 |
| rv64ui-p-slliw | p- | PASS | 1685 | 13 |
| rv64ui-p-sllw | p- | PASS | 2577 | 18 |
| rv64ui-p-slt | p- | PASS | 2431 | 17 |
| rv64ui-p-slti | p- | PASS | 1617 | 12 |
| rv64ui-p-sltiu | p- | PASS | 1617 | 12 |
| rv64ui-p-sltu | p- | PASS | 2469 | 18 |
| rv64ui-p-sra | p- | PASS | 2523 | 18 |
| rv64ui-p-srai | p- | PASS | 1654 | 12 |
| rv64ui-p-sraiw | p- | PASS | 1755 | 13 |
| rv64ui-p-sraw | p- | PASS | 2595 | 18 |
| rv64ui-p-srl | p- | PASS | 2619 | 18 |
| rv64ui-p-srli | p- | PASS | 1715 | 12 |
| rv64ui-p-srliw | p- | PASS | 1703 | 13 |
| rv64ui-p-srlw | p- | PASS | 2583 | 18 |
| rv64ui-p-st_ld | p- | PASS | 1993 | 14 |
| rv64ui-p-sub | p- | PASS | 2437 | 18 |
| rv64ui-p-subw | p- | PASS | 2429 | 17 |
| rv64ui-p-sw | p- | PASS | 2392 | 17 |
| rv64ui-p-xor | p- | PASS | 2664 | 19 |
| rv64ui-p-xori | p- | PASS | 1595 | 12 |
| rv64um-p-div | p- | PASS | 1157 | 10 |
| rv64um-p-divu | p- | PASS | 1167 | 9 |
| rv64um-p-divuw | p- | PASS | 1147 | 9 |
| rv64um-p-divw | p- | PASS | 1139 | 9 |
| rv64um-p-mul | p- | PASS | 2461 | 17 |
| rv64um-p-mulh | p- | PASS | 2471 | 18 |
| rv64um-p-mulhsu | p- | PASS | 2471 | 18 |
| rv64um-p-mulhu | p- | PASS | 2531 | 18 |
| rv64um-p-mulw | p- | PASS | 2329 | 16 |
| rv64um-p-rem | p- | PASS | 1131 | 9 |
| rv64um-p-remu | p- | PASS | 1133 | 9 |
| rv64um-p-remuw | p- | PASS | 1129 | 9 |
| rv64um-p-remw | p- | PASS | 1139 | 9 |
| rv64uzba-p-add_uw | p- | PASS | 2455 | 17 |
| rv64uzba-p-sh1add | p- | PASS | 2461 | 18 |
| rv64uzba-p-sh1add_uw | p- | PASS | 2469 | 17 |
| rv64uzba-p-sh2add | p- | PASS | 2461 | 17 |
| rv64uzba-p-sh2add_uw | p- | PASS | 2469 | 18 |
| rv64uzba-p-sh3add | p- | PASS | 2461 | 17 |
| rv64uzba-p-sh3add_uw | p- | PASS | 2469 | 18 |
| rv64uzba-p-slli_uw | p- | PASS | 1719 | 13 |
| rv64uzbb-p-andn | p- | PASS | 2655 | 18 |
| rv64uzbb-p-clz | p- | PASS | 1497 | 12 |
| rv64uzbb-p-clzw | p- | PASS | 1465 | 11 |
| rv64uzbb-p-cpop | p- | PASS | 1497 | 11 |
| rv64uzbb-p-cpopw | p- | PASS | 1465 | 11 |
| rv64uzbb-p-ctz | p- | PASS | 1497 | 11 |
| rv64uzbb-p-ctzw | p- | PASS | 1467 | 11 |
| rv64uzbb-p-max | p- | PASS | 2441 | 18 |
| rv64uzbb-p-maxu | p- | PASS | 2503 | 17 |
| rv64uzbb-p-min | p- | PASS | 2433 | 18 |
| rv64uzbb-p-minu | p- | PASS | 2481 | 18 |
| rv64uzbb-p-orc_b | p- | PASS | 1539 | 11 |
| rv64uzbb-p-orn | p- | PASS | 2673 | 19 |
| rv64uzbb-p-rev8 | p- | PASS | 1572 | 12 |
| rv64uzbb-p-rol | p- | PASS | 2583 | 18 |
| rv64uzbb-p-rolw | p- | PASS | 2585 | 18 |
| rv64uzbb-p-ror | p- | PASS | 2645 | 18 |
| rv64uzbb-p-rori | p- | PASS | 1712 | 13 |
| rv64uzbb-p-roriw | p- | PASS | 1625 | 12 |
| rv64uzbb-p-rorw | p- | PASS | 2513 | 18 |
| rv64uzbb-p-sext_b | p- | PASS | 1497 | 11 |
| rv64uzbb-p-sext_h | p- | PASS | 1503 | 12 |
| rv64uzbb-p-xnor | p- | PASS | 2671 | 19 |
| rv64uzbb-p-zext_h | p- | PASS | 1509 | 12 |
| rv64uzbc-p-clmul | p- | PASS | 2463 | 17 |
| rv64uzbc-p-clmulh | p- | PASS | 2473 | 17 |
| rv64uzbc-p-clmulr | p- | PASS | 2469 | 18 |
| rv64uzbkb-p-brev8 | p- | PASS | 1537 | 11 |
| rv64uzbkb-p-pack | p- | PASS | 2913 | 21 |
| rv64uzbkb-p-packh | p- | PASS | 2583 | 18 |
| rv64uzbkb-p-packw | p- | PASS | 2443 | 18 |
| rv64uzbkx-p-xperm4 | p- | PASS | 2767 | 19 |
| rv64uzbkx-p-xperm8 | p- | PASS | 3598 | 25 |
| rv64uzbs-p-bclr | p- | PASS | 2796 | 19 |
| rv64uzbs-p-bclri | p- | PASS | 1779 | 13 |
| rv64uzbs-p-bext | p- | PASS | 2661 | 19 |
| rv64uzbs-p-bexti | p- | PASS | 1711 | 13 |
| rv64uzbs-p-binv | p- | PASS | 2631 | 19 |
| rv64uzbs-p-binvi | p- | PASS | 1715 | 12 |
| rv64uzbs-p-bset | p- | PASS | 2800 | 19 |
| rv64uzbs-p-bseti | p- | PASS | 1793 | 13 |
| rv64uzfh-p-fadd | p- | PASS | 1913 | 14 |
| rv64uzfh-p-fclass | p- | PASS | 1218 | 9 |
| rv64uzfh-p-fcmp | p- | PASS | 1565 | 12 |
| rv64uzfh-p-fcvt | p- | PASS | 1803 | 14 |
| rv64uzfh-p-fcvt_w | p- | PASS | 3428 | 24 |
| rv64uzfh-p-fdiv | p- | PASS | 1663 | 13 |
| rv64uzfh-p-fmadd | p- | PASS | 2070 | 15 |
| rv64uzfh-p-fmin | p- | PASS | 2541 | 18 |
| rv64uzfh-p-ldst | p- | PASS | 1194 | 9 |
| rv64uzfh-p-move | p- | PASS | 1812 | 13 |
| rv64uzfh-p-recoding | p- | PASS | 1198 | 10 |
| rv64uziccid-p-ziccid | p- | PASS | 7364 | 31 |
| rv64uzicond-p-czero_eqz | p- | PASS | 2389 | 17 |
| rv64uzicond-p-czero_nez | p- | PASS | 2377 | 16 |
| rv64ua-v-amoadd_d | v- | PASS | 23926 | 99 |
| rv64ua-v-amoadd_w | v- | PASS | 23960 | 162 |
| rv64ua-v-amoand_d | v- | PASS | 24068 | 160 |
| rv64ua-v-amoand_w | v- | PASS | 24071 | 167 |
| rv64ua-v-amomax_d | v- | PASS | 23861 | 154 |
| rv64ua-v-amomax_w | v- | PASS | 23909 | 94 |
| rv64ua-v-amomaxu_d | v- | PASS | 23861 | 168 |
| rv64ua-v-amomaxu_w | v- | PASS | 23909 | 156 |
| rv64ua-v-amomin_d | v- | PASS | 23861 | 93 |
| rv64ua-v-amomin_w | v- | PASS | 24058 | 86 |
| rv64ua-v-amominu_d | v- | PASS | 23910 | 149 |
| rv64ua-v-amominu_w | v- | PASS | 23958 | 171 |
| rv64ua-v-amoor_d | v- | PASS | 23914 | 157 |
| rv64ua-v-amoor_w | v- | PASS | 23914 | 118 |
| rv64ua-v-amoswap_d | v- | PASS | 24068 | 155 |
| rv64ua-v-amoswap_w | v- | PASS | 24071 | 155 |
| rv64ua-v-amoxor_d | v- | PASS | 23916 | 161 |
| rv64ua-v-amoxor_w | v- | PASS | 23923 | 157 |
| rv64ua-v-lrsc | v- | PASS | 41845 | 154 |
| rv64uc-v-rvc | v- | PASS | 33050 | 221 |
| rv64ud-v-fadd | v- | PASS | 23566 | 157 |
| rv64ud-v-fclass | v- | PASS | 14141 | 72 |
| rv64ud-v-fcmp | v- | PASS | 23874 | 156 |
| rv64ud-v-fcvt | v- | PASS | 23488 | 155 |
| rv64ud-v-fcvt_w | v- | PASS | 34125 | 217 |
| rv64ud-v-fdiv | v- | PASS | 23394 | 157 |
| rv64ud-v-fmadd | v- | PASS | 23715 | 97 |
| rv64ud-v-fmin | v- | PASS | 24197 | 165 |
| rv64ud-v-ldst | v- | PASS | 23572 | 130 |
| rv64ud-v-move | v- | PASS | 24427 | 171 |
| rv64ud-v-recoding | v- | PASS | 23884 | 159 |
| rv64ud-v-structural | v- | PASS | 14883 | 111 |
| rv64uf-v-fadd | v- | PASS | 23566 | 158 |
| rv64uf-v-fclass | v- | PASS | 14125 | 92 |
| rv64uf-v-fcmp | v- | PASS | 23874 | 163 |
| rv64uf-v-fcvt | v- | PASS | 23269 | 159 |
| rv64uf-v-fcvt_w | v- | PASS | 33789 | 219 |
| rv64uf-v-fdiv | v- | PASS | 23316 | 156 |
| rv64uf-v-fmadd | v- | PASS | 23715 | 96 |
| rv64uf-v-fmin | v- | PASS | 24197 | 101 |
| rv64uf-v-ldst | v- | PASS | 23775 | 150 |
| rv64uf-v-move | v- | PASS | 14695 | 109 |
| rv64uf-v-recoding | v- | PASS | 22830 | 83 |
| rv64ui-v-add | v- | PASS | 15388 | 104 |
| rv64ui-v-addi | v- | PASS | 14562 | 110 |
| rv64ui-v-addiw | v- | PASS | 14556 | 101 |
| rv64ui-v-addw | v- | PASS | 15377 | 67 |
| rv64ui-v-and | v- | PASS | 15565 | 118 |
| rv64ui-v-andi | v- | PASS | 14538 | 53 |
| rv64ui-v-auipc | v- | PASS | 13979 | 96 |
| rv64ui-v-beq | v- | PASS | 15302 | 107 |
| rv64ui-v-bge | v- | PASS | 15596 | 107 |
| rv64ui-v-bgeu | v- | PASS | 15836 | 66 |
| rv64ui-v-blt | v- | PASS | 15303 | 106 |
| rv64ui-v-bltu | v- | PASS | 15523 | 104 |
| rv64ui-v-bne | v- | PASS | 15354 | 111 |
| rv64ui-v-fence_i | v- | PASS | 24755 | 162 |
| rv64ui-v-jal | v- | PASS | 13988 | 95 |
| rv64ui-v-jalr | v- | PASS | 14334 | 106 |
| rv64ui-v-lb | v- | PASS | 23398 | 163 |
| rv64ui-v-lbu | v- | PASS | 23398 | 100 |
| rv64ui-v-ld | v- | PASS | 23922 | 166 |
| rv64ui-v-ld_st | v- | PASS | 44110 | 293 |
| rv64ui-v-lh | v- | PASS | 23425 | 98 |
| rv64ui-v-lhu | v- | PASS | 23449 | 155 |
| rv64ui-v-lui | v- | PASS | 13996 | 94 |
| rv64ui-v-lw | v- | PASS | 23451 | 179 |
| rv64ui-v-lwu | v- | PASS | 23518 | 87 |
| rv64ui-v-ma_data | v- | PASS | 46560 | 315 |
| rv64ui-v-or | v- | PASS | 15636 | 107 |
| rv64ui-v-ori | v- | PASS | 14518 | 77 |
| rv64ui-v-sb | v- | PASS | 24714 | 128 |
| rv64ui-v-sd | v- | PASS | 33723 | 229 |
| rv64ui-v-sh | v- | PASS | 24801 | 164 |
| rv64ui-v-simple | v- | PASS | 13932 | 98 |
| rv64ui-v-sll | v- | PASS | 24297 | 163 |
| rv64ui-v-slli | v- | PASS | 14612 | 105 |
| rv64ui-v-slliw | v- | PASS | 14625 | 99 |
| rv64ui-v-sllw | v- | PASS | 24295 | 179 |
| rv64ui-v-slt | v- | PASS | 15365 | 105 |
| rv64ui-v-slti | v- | PASS | 14553 | 99 |
| rv64ui-v-sltiu | v- | PASS | 14553 | 99 |
| rv64ui-v-sltu | v- | PASS | 15371 | 66 |
| rv64ui-v-sra | v- | PASS | 15462 | 119 |
| rv64ui-v-srai | v- | PASS | 14589 | 53 |
| rv64ui-v-sraiw | v- | PASS | 14671 | 101 |
| rv64ui-v-sraw | v- | PASS | 24311 | 126 |
| rv64ui-v-srl | v- | PASS | 24347 | 172 |
| rv64ui-v-srli | v- | PASS | 14641 | 64 |
| rv64ui-v-srliw | v- | PASS | 14638 | 60 |
| rv64ui-v-srlw | v- | PASS | 24306 | 160 |
| rv64ui-v-st_ld | v- | PASS | 33135 | 135 |
| rv64ui-v-sub | v- | PASS | 15371 | 64 |
| rv64ui-v-subw | v- | PASS | 15333 | 102 |
| rv64ui-v-sw | v- | PASS | 24819 | 167 |
| rv64ui-v-xor | v- | PASS | 15633 | 107 |
| rv64ui-v-xori | v- | PASS | 14520 | 102 |
| rv64um-v-div | v- | PASS | 14102 | 58 |
| rv64um-v-divu | v- | PASS | 14112 | 95 |
| rv64um-v-divuw | v- | PASS | 14100 | 96 |
| rv64um-v-divw | v- | PASS | 14055 | 85 |
| rv64um-v-mul | v- | PASS | 15413 | 104 |
| rv64um-v-mulh | v- | PASS | 15410 | 114 |
| rv64um-v-mulhsu | v- | PASS | 15411 | 106 |
| rv64um-v-mulhu | v- | PASS | 15470 | 67 |
| rv64um-v-mulw | v- | PASS | 15263 | 106 |
| rv64um-v-rem | v- | PASS | 14083 | 110 |
| rv64um-v-remu | v- | PASS | 14087 | 52 |
| rv64um-v-remuw | v- | PASS | 14075 | 96 |
| rv64um-v-remw | v- | PASS | 14055 | 97 |
| rv64uzba-v-add_uw | v- | PASS | 15350 | 104 |
| rv64uzba-v-sh1add | v- | PASS | 15361 | 62 |
| rv64uzba-v-sh1add_uw | v- | PASS | 15363 | 63 |
| rv64uzba-v-sh2add | v- | PASS | 15361 | 102 |
| rv64uzba-v-sh2add_uw | v- | PASS | 15363 | 115 |
| rv64uzba-v-sh3add | v- | PASS | 15361 | 56 |
| rv64uzba-v-sh3add_uw | v- | PASS | 15363 | 104 |
| rv64uzba-v-slli_uw | v- | PASS | 14589 | 73 |
| rv64uzbb-v-andn | v- | PASS | 15622 | 103 |
| rv64uzbb-v-clz | v- | PASS | 14458 | 95 |
| rv64uzbb-v-clzw | v- | PASS | 14436 | 100 |
| rv64uzbb-v-cpop | v- | PASS | 14458 | 98 |
| rv64uzbb-v-cpopw | v- | PASS | 14436 | 59 |
| rv64uzbb-v-ctz | v- | PASS | 14458 | 98 |
| rv64uzbb-v-ctzw | v- | PASS | 14436 | 94 |
| rv64uzbb-v-max | v- | PASS | 15353 | 107 |
| rv64uzbb-v-maxu | v- | PASS | 15446 | 103 |
| rv64uzbb-v-min | v- | PASS | 15380 | 109 |
| rv64uzbb-v-minu | v- | PASS | 15423 | 101 |
| rv64uzbb-v-orc_b | v- | PASS | 14503 | 58 |
| rv64uzbb-v-orn | v- | PASS | 24458 | 89 |
| rv64uzbb-v-rev8 | v- | PASS | 14548 | 93 |
| rv64uzbb-v-rol | v- | PASS | 24397 | 150 |
| rv64uzbb-v-rolw | v- | PASS | 24390 | 72 |
| rv64uzbb-v-ror | v- | PASS | 24433 | 140 |
| rv64uzbb-v-rori | v- | PASS | 14663 | 77 |
| rv64uzbb-v-roriw | v- | PASS | 14571 | 96 |
| rv64uzbb-v-rorw | v- | PASS | 15458 | 95 |
| rv64uzbb-v-sext_b | v- | PASS | 14458 | 95 |
| rv64uzbb-v-sext_h | v- | PASS | 14467 | 81 |
| rv64uzbb-v-xnor | v- | PASS | 24488 | 81 |
| rv64uzbb-v-zext_h | v- | PASS | 14473 | 97 |
| rv64uzbc-v-clmul | v- | PASS | 15414 | 98 |
| rv64uzbc-v-clmulh | v- | PASS | 15424 | 82 |
| rv64uzbc-v-clmulr | v- | PASS | 15422 | 83 |
| rv64uzbkb-v-brev8 | v- | PASS | 14524 | 91 |
| rv64uzbkb-v-pack | v- | PASS | 24805 | 104 |
| rv64uzbkb-v-packh | v- | PASS | 15604 | 52 |
| rv64uzbkb-v-packw | v- | PASS | 15453 | 49 |
| rv64uzbkx-v-xperm4 | v- | PASS | 24529 | 97 |
| rv64uzbkx-v-xperm8 | v- | PASS | 25372 | 145 |
| rv64uzbs-v-bclr | v- | PASS | 24528 | 72 |
| rv64uzbs-v-bclri | v- | PASS | 14686 | 97 |
| rv64uzbs-v-bext | v- | PASS | 24386 | 91 |
| rv64uzbs-v-bexti | v- | PASS | 14617 | 76 |
| rv64uzbs-v-binv | v- | PASS | 24349 | 115 |
| rv64uzbs-v-binvi | v- | PASS | 14601 | 79 |
| rv64uzbs-v-bset | v- | PASS | 24532 | 108 |
| rv64uzbs-v-bseti | v- | PASS | 14700 | 47 |
| rv64uzfh-v-fadd | v- | PASS | 23566 | 116 |
| rv64uzfh-v-fclass | v- | PASS | 14116 | 81 |
| rv64uzfh-v-fcmp | v- | PASS | 23208 | 94 |
| rv64uzfh-v-fcvt | v- | PASS | 23431 | 95 |
| rv64uzfh-v-fcvt_w | v- | PASS | 33789 | 147 |
| rv64uzfh-v-fdiv | v- | PASS | 23316 | 98 |
| rv64uzfh-v-fmadd | v- | PASS | 23715 | 58 |
| rv64uzfh-v-fmin | v- | PASS | 24197 | 65 |
| rv64uzfh-v-ldst | v- | PASS | 23820 | 88 |
| rv64uzfh-v-move | v- | PASS | 14690 | 105 |
| rv64uzfh-v-recoding | v- | PASS | 22830 | 57 |
| rv64uziccid-v-ziccid | v- | PASS | 164934 | 604 |
| rv64uzicond-v-czero_eqz | v- | PASS | 15378 | 80 |
| rv64uzicond-v-czero_nez | v- | PASS | 15379 | 48 |

</details>

## Performance counters

| Test | Suite | Shard | cycles | predicted_ft | multimember_ft | k_cnt_nonzero | mispred_squash | btb_window_hit | alloc_total | rel_commit | rel_squash | i1_violation | release_accounting_mismatch | assertion_a_violation | fetch_resteer_to_bac | load_committed | lr_committed | store_committed | sc_committed | store_violation_squash | all_squashes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| `hypervisor-p-2-stage_translation` | p- | none | 1380 | 643 | 0 | 0 | 15 | 14 | 42 | 27 | 10 | 0 | 1 | 0 | 0 | 1 | 0 | 13 | 0 | 0 | 28 |
| `hypervisor-p-2-stage_translation_implicit_load_error` | p- | none | 1641 | 839 | 0 | 0 | 31 | 17 | 66 | 34 | 27 | 0 | 1 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 36 |
| `hypervisor-p-2-stage_translation_implicit_load_error_hs` | p- | none | 1816 | 948 | 0 | 0 | 35 | 15 | 74 | 38 | 31 | 0 | 1 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 40 |
| `hypervisor-svadu-p-2-stage_translation_implicit_store_error` | p- | none | 1722 | 904 | 0 | 0 | 33 | 18 | 69 | 36 | 28 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 38 |
| `hypervisor-svadu-p-2-stage_translation_implicit_store_error_hs` | p- | none | 1929 | 980 | 0 | 0 | 32 | 18 | 74 | 40 | 29 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 42 |
| `rv64mi-p-breakpoint` | p- | none | 3480 | 1751 | 0 | 10 | 64 | 44 | 143 | 78 | 63 | 0 | 0 | 0 | 0 | 3 | 0 | 2 | 0 | 0 | 79 |
| `rv64mi-p-csr` | p- | none | 3552 | 1895 | 0 | 6 | 72 | 40 | 160 | 80 | 78 | 0 | 0 | 0 | 0 | 1 | 0 | 1 | 0 | 0 | 81 |
| `rv64mi-p-illegal` | p- | none | 4578 | 3175 | 89 | 15 | 211 | 715 | 913 | 130 | 781 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 122 |
| `rv64mi-p-ld-misaligned` | p- | none | 1386 | 629 | 0 | 0 | 18 | 4 | 39 | 25 | 12 | 0 | 0 | 0 | 0 | 8 | 0 | 1 | 0 | 0 | 26 |
| `rv64mi-p-lh-misaligned` | p- | none | 1102 | 542 | 0 | 0 | 18 | 4 | 39 | 25 | 12 | 0 | 0 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 26 |
| `rv64mi-p-lw-misaligned` | p- | none | 1171 | 570 | 0 | 0 | 18 | 4 | 39 | 25 | 12 | 0 | 0 | 0 | 0 | 4 | 0 | 1 | 0 | 0 | 26 |
| `rv64mi-p-ma_addr` | p- | none | 1540 | 898 | 0 | 0 | 46 | 7 | 67 | 25 | 40 | 0 | 0 | 0 | 0 | 59 | 0 | 12 | 0 | 0 | 26 |
| `rv64mi-p-mcsr` | p- | none | 1342 | 650 | 0 | 0 | 15 | 13 | 46 | 32 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 33 |
| `rv64mi-p-sbreak` | p- | none | 1341 | 995 | 0 | 2 | 79 | 32 | 125 | 32 | 91 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 33 |
| `rv64mi-p-scall` | p- | none | 1259 | 872 | 0 | 0 | 63 | 4 | 86 | 30 | 54 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64mi-p-sd-misaligned` | p- | none | 1482 | 1002 | 0 | 0 | 74 | 4 | 94 | 33 | 59 | 0 | 0 | 0 | 0 | 8 | 0 | 9 | 0 | 0 | 34 |
| `rv64mi-p-sh-misaligned` | p- | none | 1123 | 775 | 0 | 0 | 61 | 4 | 80 | 27 | 51 | 0 | 0 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 28 |
| `rv64mi-p-sw-misaligned` | p- | none | 1164 | 827 | 0 | 0 | 77 | 4 | 94 | 29 | 63 | 0 | 0 | 0 | 0 | 4 | 0 | 5 | 0 | 0 | 30 |
| `rv64mzicbo-p-zero` | p- | none | 1162 | 613 | 0 | 0 | 23 | 13 | 47 | 25 | 17 | 0 | 1 | 0 | 0 | 8 | 0 | 2 | 0 | 0 | 26 |
| `rv64si-p-csr` | p- | none | 2277 | 1081 | 0 | 0 | 14 | 13 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 52 |
| `rv64si-p-dirty` | p- | none | 2339 | 1456 | 0 | 6 | 96 | 66 | 181 | 52 | 120 | 0 | 1 | 0 | 0 | 6 | 0 | 5 | 0 | 0 | 54 |
| `rv64si-p-icache-alias` | p- | none | 2463 | 1301 | 0 | 8 | 62 | 72 | 148 | 59 | 84 | 0 | 1 | 0 | 3 | 0 | 0 | 7 | 0 | 0 | 57 |
| `rv64si-p-ma_fetch` | p- | none | 1415 | 1132 | 0 | 0 | 114 | 28 | 143 | 37 | 101 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 42 |
| `rv64si-p-sbreak` | p- | none | 1354 | 997 | 0 | 0 | 73 | 31 | 121 | 32 | 84 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 33 |
| `rv64si-p-scall` | p- | none | 1472 | 1099 | 0 | 0 | 80 | 30 | 130 | 35 | 90 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 36 |
| `rv64si-p-wfi` | p- | none | 1173 | 582 | 0 | 0 | 14 | 13 | 42 | 28 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 29 |
| `rv64ssvnapot-p-napot` | p- | none | 1658 | 807 | 0 | 2 | 29 | 19 | 66 | 34 | 24 | 0 | 1 | 0 | 0 | 0 | 0 | 6 | 0 | 0 | 35 |
| `rv64ua-p-amoadd_d` | p- | none | 1081 | 520 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 0 | 25 |
| `rv64ua-p-amoadd_w` | p- | none | 1120 | 538 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-amoand_d` | p- | none | 1121 | 537 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-amoand_w` | p- | none | 1117 | 535 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-amomax_d` | p- | none | 1077 | 519 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 25 |
| `rv64ua-p-amomax_w` | p- | none | 1100 | 532 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 3 | 0 | 4 | 0 | 0 | 25 |
| `rv64ua-p-amomaxu_d` | p- | none | 1077 | 519 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 25 |
| `rv64ua-p-amomaxu_w` | p- | none | 1100 | 532 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 3 | 0 | 4 | 0 | 0 | 25 |
| `rv64ua-p-amomin_d` | p- | none | 1077 | 519 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 25 |
| `rv64ua-p-amomin_w` | p- | none | 1100 | 532 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 3 | 0 | 4 | 0 | 0 | 25 |
| `rv64ua-p-amominu_d` | p- | none | 1077 | 519 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 25 |
| `rv64ua-p-amominu_w` | p- | none | 1100 | 532 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 3 | 0 | 4 | 0 | 0 | 25 |
| `rv64ua-p-amoor_d` | p- | none | 1117 | 536 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-amoor_w` | p- | none | 1117 | 536 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-amoswap_d` | p- | none | 1121 | 537 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-amoswap_w` | p- | none | 1117 | 535 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-amoxor_d` | p- | none | 1125 | 538 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-amoxor_w` | p- | none | 1129 | 539 | 0 | 0 | 15 | 12 | 39 | 25 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 26 |
| `rv64ua-p-lrsc` | p- | none | 19290 | 5605 | 0 | 0 | 28 | 2403 | 2478 | 1124 | 1349 | 0 | 1 | 0 | 0 | 4 | 1025 | 1 | 1028 | 75 | 113 |
| `rv64uc-p-rvc` | p- | none | 1666 | 1003 | 0 | 0 | 78 | 10 | 101 | 37 | 59 | 0 | 1 | 0 | 0 | 9 | 0 | 5 | 0 | 0 | 42 |
| `rv64ud-p-fadd` | p- | none | 1913 | 852 | 0 | 0 | 15 | 12 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 40 | 0 | 1 | 0 | 0 | 37 |
| `rv64ud-p-fclass` | p- | none | 1233 | 597 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64ud-p-fcmp` | p- | none | 2231 | 987 | 0 | 0 | 15 | 12 | 55 | 41 | 9 | 0 | 1 | 0 | 0 | 60 | 0 | 1 | 0 | 0 | 42 |
| `rv64ud-p-fcvt` | p- | none | 1841 | 836 | 0 | 0 | 15 | 12 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 17 | 0 | 1 | 0 | 0 | 37 |
| `rv64ud-p-fcvt_w` | p- | none | 3801 | 1630 | 0 | 0 | 15 | 12 | 74 | 60 | 9 | 0 | 1 | 0 | 0 | 152 | 0 | 1 | 0 | 0 | 61 |
| `rv64ud-p-fdiv` | p- | none | 1739 | 788 | 0 | 0 | 15 | 12 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 32 | 0 | 1 | 0 | 0 | 35 |
| `rv64ud-p-fmadd` | p- | none | 2070 | 917 | 0 | 0 | 15 | 12 | 52 | 38 | 9 | 0 | 1 | 0 | 0 | 48 | 0 | 1 | 0 | 0 | 39 |
| `rv64ud-p-fmin` | p- | none | 2541 | 1095 | 0 | 0 | 15 | 12 | 58 | 44 | 9 | 0 | 1 | 0 | 0 | 72 | 0 | 1 | 0 | 0 | 45 |
| `rv64ud-p-ldst` | p- | none | 1172 | 576 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 10 | 0 | 6 | 0 | 0 | 27 |
| `rv64ud-p-move` | p- | none | 2696 | 937 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64ud-p-recoding` | p- | none | 1245 | 592 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 7 | 0 | 2 | 0 | 0 | 27 |
| `rv64ud-p-structural` | p- | none | 2023 | 1272 | 0 | 0 | 109 | 22 | 134 | 47 | 82 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 54 |
| `rv64uf-p-fadd` | p- | none | 1913 | 852 | 0 | 0 | 15 | 12 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 40 | 0 | 1 | 0 | 0 | 37 |
| `rv64uf-p-fclass` | p- | none | 1217 | 594 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uf-p-fcmp` | p- | none | 2231 | 987 | 0 | 0 | 15 | 12 | 55 | 41 | 9 | 0 | 1 | 0 | 0 | 60 | 0 | 1 | 0 | 0 | 42 |
| `rv64uf-p-fcvt` | p- | none | 1630 | 756 | 0 | 0 | 15 | 12 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 8 | 0 | 1 | 0 | 0 | 35 |
| `rv64uf-p-fcvt_w` | p- | none | 3428 | 1480 | 0 | 0 | 15 | 12 | 69 | 55 | 9 | 0 | 1 | 0 | 0 | 132 | 0 | 1 | 0 | 0 | 56 |
| `rv64uf-p-fdiv` | p- | none | 1663 | 763 | 0 | 0 | 15 | 12 | 47 | 33 | 9 | 0 | 1 | 0 | 0 | 28 | 0 | 1 | 0 | 0 | 34 |
| `rv64uf-p-fmadd` | p- | none | 2070 | 917 | 0 | 0 | 15 | 12 | 52 | 38 | 9 | 0 | 1 | 0 | 0 | 48 | 0 | 1 | 0 | 0 | 39 |
| `rv64uf-p-fmin` | p- | none | 2541 | 1095 | 0 | 0 | 15 | 12 | 58 | 44 | 9 | 0 | 1 | 0 | 0 | 72 | 0 | 1 | 0 | 0 | 45 |
| `rv64uf-p-ldst` | p- | none | 1183 | 561 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 4 | 0 | 3 | 0 | 0 | 27 |
| `rv64uf-p-move` | p- | none | 1817 | 819 | 0 | 0 | 15 | 12 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 35 |
| `rv64uf-p-recoding` | p- | none | 1198 | 575 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 27 |
| `rv64ui-p-add` | p- | none | 2453 | 1028 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-addi` | p- | none | 1630 | 726 | 0 | 0 | 21 | 18 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-addiw` | p- | none | 1621 | 723 | 0 | 0 | 21 | 15 | 47 | 33 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-addw` | p- | none | 2443 | 1026 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-and` | p- | none | 2613 | 1103 | 0 | 0 | 30 | 27 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-andi` | p- | none | 1609 | 717 | 0 | 0 | 21 | 16 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-auipc` | p- | none | 1053 | 762 | 0 | 0 | 53 | 13 | 76 | 26 | 45 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64ui-p-beq` | p- | none | 2427 | 1106 | 0 | 0 | 41 | 29 | 72 | 58 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 51 |
| `rv64ui-p-bge` | p- | none | 2726 | 1256 | 0 | 0 | 50 | 32 | 81 | 67 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 60 |
| `rv64ui-p-bgeu` | p- | none | 2956 | 1322 | 0 | 0 | 50 | 38 | 85 | 71 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 60 |
| `rv64ui-p-blt` | p- | none | 2429 | 1106 | 0 | 0 | 41 | 29 | 72 | 58 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 51 |
| `rv64ui-p-bltu` | p- | none | 2643 | 1166 | 0 | 1 | 41 | 36 | 77 | 61 | 11 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 51 |
| `rv64ui-p-bne` | p- | none | 2482 | 1133 | 0 | 1 | 43 | 37 | 78 | 63 | 10 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 53 |
| `rv64ui-p-fence_i` | p- | none | 2097 | 926 | 0 | 0 | 29 | 389 | 182 | 130 | 47 | 0 | 1 | 0 | 0 | 2 | 0 | 5 | 0 | 0 | 41 |
| `rv64ui-p-jal` | p- | none | 1103 | 750 | 0 | 0 | 58 | 12 | 81 | 26 | 50 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64ui-p-jalr` | p- | none | 1511 | 894 | 3 | 4 | 56 | 24 | 86 | 38 | 43 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 45 |
| `rv64ui-p-lb` | p- | none | 1671 | 736 | 0 | 0 | 21 | 20 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-lbu` | p- | none | 1671 | 736 | 0 | 0 | 21 | 20 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-ld` | p- | none | 2066 | 834 | 0 | 0 | 21 | 21 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-ld_st` | p- | none | 4452 | 2368 | 0 | 0 | 205 | 63 | 228 | 81 | 142 | 0 | 1 | 0 | 0 | 277 | 0 | 278 | 0 | 0 | 139 |
| `rv64ui-p-lh` | p- | none | 1711 | 748 | 0 | 0 | 21 | 20 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-lhu` | p- | none | 1717 | 744 | 0 | 0 | 21 | 21 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-lui` | p- | none | 1065 | 518 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64ui-p-lw` | p- | none | 1731 | 753 | 0 | 0 | 21 | 21 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-lwu` | p- | none | 1797 | 767 | 0 | 0 | 21 | 23 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-ma_data` | p- | none | 7654 | 3834 | 0 | 0 | 296 | 79 | 319 | 111 | 203 | 0 | 1 | 0 | 0 | 180 | 0 | 136 | 0 | 0 | 199 |
| `rv64ui-p-or` | p- | none | 2670 | 1106 | 0 | 0 | 30 | 27 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-ori` | p- | none | 1591 | 714 | 0 | 0 | 21 | 18 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-sb` | p- | none | 2308 | 1268 | 0 | 0 | 89 | 29 | 124 | 57 | 62 | 0 | 1 | 0 | 0 | 34 | 0 | 36 | 0 | 1 | 46 |
| `rv64ui-p-sd` | p- | none | 2656 | 1369 | 0 | 1 | 80 | 31 | 115 | 56 | 54 | 0 | 1 | 0 | 0 | 34 | 0 | 35 | 0 | 1 | 46 |
| `rv64ui-p-sh` | p- | none | 2374 | 1287 | 0 | 0 | 89 | 33 | 124 | 57 | 62 | 0 | 1 | 0 | 0 | 34 | 0 | 36 | 0 | 1 | 46 |
| `rv64ui-p-simple` | p- | none | 1003 | 480 | 0 | 0 | 14 | 12 | 37 | 23 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64ui-p-sll` | p- | none | 2573 | 1064 | 0 | 0 | 30 | 29 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-slli` | p- | none | 1691 | 736 | 0 | 0 | 21 | 18 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-slliw` | p- | none | 1685 | 740 | 0 | 0 | 21 | 18 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-sllw` | p- | none | 2577 | 1067 | 0 | 0 | 30 | 29 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-slt` | p- | none | 2431 | 1030 | 0 | 0 | 30 | 29 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-slti` | p- | none | 1617 | 719 | 0 | 0 | 21 | 18 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-sltiu` | p- | none | 1617 | 719 | 0 | 0 | 21 | 18 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-sltu` | p- | none | 2469 | 1036 | 0 | 0 | 30 | 26 | 63 | 49 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-sra` | p- | none | 2523 | 1050 | 0 | 0 | 30 | 29 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-srai` | p- | none | 1654 | 734 | 0 | 0 | 21 | 20 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-sraiw` | p- | none | 1755 | 757 | 0 | 0 | 21 | 19 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-sraw` | p- | none | 2595 | 1070 | 0 | 0 | 30 | 29 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-srl` | p- | none | 2619 | 1081 | 0 | 0 | 30 | 31 | 67 | 53 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-srli` | p- | none | 1715 | 746 | 0 | 0 | 21 | 19 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-srliw` | p- | none | 1703 | 741 | 0 | 0 | 21 | 15 | 47 | 33 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64ui-p-srlw` | p- | none | 2583 | 1061 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-st_ld` | p- | none | 1993 | 745 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 70 | 0 | 71 | 0 | 0 | 25 |
| `rv64ui-p-sub` | p- | none | 2437 | 1030 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-subw` | p- | none | 2429 | 1029 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-sw` | p- | none | 2392 | 1286 | 0 | 1 | 86 | 31 | 119 | 56 | 58 | 0 | 1 | 0 | 0 | 34 | 0 | 35 | 0 | 1 | 46 |
| `rv64ui-p-xor` | p- | none | 2664 | 1104 | 0 | 0 | 30 | 28 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-xori` | p- | none | 1595 | 717 | 0 | 0 | 21 | 17 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64um-p-div` | p- | none | 1157 | 558 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64um-p-divu` | p- | none | 1167 | 561 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64um-p-divuw` | p- | none | 1147 | 551 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64um-p-divw` | p- | none | 1139 | 549 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64um-p-mul` | p- | none | 2461 | 1035 | 0 | 0 | 30 | 26 | 63 | 49 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64um-p-mulh` | p- | none | 2471 | 1038 | 0 | 0 | 30 | 32 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64um-p-mulhsu` | p- | none | 2471 | 1038 | 0 | 0 | 30 | 32 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64um-p-mulhu` | p- | none | 2531 | 1053 | 0 | 0 | 30 | 32 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64um-p-mulw` | p- | none | 2329 | 1002 | 0 | 0 | 30 | 29 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64um-p-rem` | p- | none | 1131 | 549 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64um-p-remu` | p- | none | 1133 | 549 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64um-p-remuw` | p- | none | 1129 | 548 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64um-p-remw` | p- | none | 1139 | 549 | 0 | 0 | 15 | 12 | 38 | 24 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 25 |
| `rv64uzba-p-add_uw` | p- | none | 2455 | 1033 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzba-p-sh1add` | p- | none | 2461 | 1036 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzba-p-sh1add_uw` | p- | none | 2469 | 1031 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzba-p-sh2add` | p- | none | 2461 | 1036 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzba-p-sh2add_uw` | p- | none | 2469 | 1031 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzba-p-sh3add` | p- | none | 2461 | 1036 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzba-p-sh3add_uw` | p- | none | 2469 | 1031 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzba-p-slli_uw` | p- | none | 1719 | 747 | 0 | 0 | 21 | 19 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64uzbb-p-andn` | p- | none | 2655 | 1095 | 0 | 0 | 30 | 31 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-clz` | p- | none | 1497 | 670 | 0 | 0 | 18 | 14 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-clzw` | p- | none | 1465 | 660 | 0 | 0 | 18 | 14 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-cpop` | p- | none | 1497 | 670 | 0 | 0 | 18 | 14 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-cpopw` | p- | none | 1465 | 660 | 0 | 0 | 18 | 14 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-ctz` | p- | none | 1497 | 670 | 0 | 0 | 18 | 14 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-ctzw` | p- | none | 1467 | 660 | 0 | 0 | 18 | 15 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-max` | p- | none | 2441 | 1029 | 0 | 0 | 30 | 27 | 64 | 50 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-maxu` | p- | none | 2503 | 1046 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-min` | p- | none | 2433 | 1028 | 0 | 0 | 30 | 26 | 63 | 49 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-minu` | p- | none | 2481 | 1035 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-orc_b` | p- | none | 1539 | 680 | 0 | 0 | 18 | 15 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-orn` | p- | none | 2673 | 1088 | 0 | 0 | 30 | 30 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-rev8` | p- | none | 1572 | 689 | 0 | 0 | 18 | 14 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-rol` | p- | none | 2583 | 1068 | 0 | 0 | 30 | 32 | 67 | 53 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-rolw` | p- | none | 2585 | 1066 | 0 | 0 | 30 | 29 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-ror` | p- | none | 2645 | 1085 | 0 | 0 | 30 | 28 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-rori` | p- | none | 1712 | 743 | 0 | 0 | 21 | 17 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64uzbb-p-roriw` | p- | none | 1625 | 725 | 0 | 0 | 21 | 16 | 47 | 33 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64uzbb-p-rorw` | p- | none | 2513 | 1050 | 0 | 0 | 30 | 29 | 65 | 51 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-sext_b` | p- | none | 1497 | 670 | 0 | 0 | 18 | 14 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-sext_h` | p- | none | 1503 | 669 | 0 | 0 | 18 | 15 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbb-p-xnor` | p- | none | 2671 | 1091 | 0 | 0 | 30 | 28 | 67 | 53 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbb-p-zext_h` | p- | none | 1509 | 674 | 0 | 0 | 18 | 15 | 43 | 29 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbc-p-clmul` | p- | none | 2463 | 1038 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbc-p-clmulh` | p- | none | 2473 | 1035 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbc-p-clmulr` | p- | none | 2469 | 1036 | 0 | 0 | 30 | 27 | 64 | 50 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbkb-p-brev8` | p- | none | 1537 | 675 | 0 | 0 | 18 | 16 | 44 | 30 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64uzbkb-p-pack` | p- | none | 2913 | 1175 | 0 | 0 | 30 | 29 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbkb-p-packh` | p- | none | 2583 | 1085 | 0 | 0 | 30 | 31 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbkb-p-packw` | p- | none | 2443 | 1034 | 0 | 0 | 30 | 30 | 67 | 53 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbkx-p-xperm4` | p- | none | 2767 | 1134 | 0 | 0 | 30 | 31 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbkx-p-xperm8` | p- | none | 3598 | 1363 | 0 | 0 | 30 | 27 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbs-p-bclr` | p- | none | 2796 | 1143 | 0 | 0 | 30 | 29 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbs-p-bclri` | p- | none | 1779 | 764 | 0 | 0 | 21 | 18 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64uzbs-p-bext` | p- | none | 2661 | 1082 | 0 | 0 | 30 | 31 | 67 | 53 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbs-p-bexti` | p- | none | 1711 | 747 | 0 | 0 | 21 | 18 | 49 | 35 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64uzbs-p-binv` | p- | none | 2631 | 1083 | 0 | 0 | 30 | 26 | 64 | 50 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbs-p-binvi` | p- | none | 1715 | 745 | 0 | 0 | 21 | 17 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64uzbs-p-bset` | p- | none | 2800 | 1144 | 0 | 0 | 30 | 27 | 68 | 54 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzbs-p-bseti` | p- | none | 1793 | 763 | 0 | 0 | 21 | 19 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64uzfh-p-fadd` | p- | none | 1913 | 852 | 0 | 0 | 15 | 12 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 40 | 0 | 1 | 0 | 0 | 37 |
| `rv64uzfh-p-fclass` | p- | none | 1218 | 594 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzfh-p-fcmp` | p- | none | 1565 | 724 | 0 | 0 | 15 | 12 | 46 | 32 | 9 | 0 | 1 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 33 |
| `rv64uzfh-p-fcvt` | p- | none | 1803 | 825 | 0 | 0 | 15 | 12 | 50 | 36 | 9 | 0 | 1 | 0 | 0 | 16 | 0 | 1 | 0 | 0 | 37 |
| `rv64uzfh-p-fcvt_w` | p- | none | 3428 | 1480 | 0 | 0 | 15 | 12 | 69 | 55 | 9 | 0 | 1 | 0 | 0 | 132 | 0 | 1 | 0 | 0 | 56 |
| `rv64uzfh-p-fdiv` | p- | none | 1663 | 763 | 0 | 0 | 15 | 12 | 47 | 33 | 9 | 0 | 1 | 0 | 0 | 28 | 0 | 1 | 0 | 0 | 34 |
| `rv64uzfh-p-fmadd` | p- | none | 2070 | 917 | 0 | 0 | 15 | 12 | 52 | 38 | 9 | 0 | 1 | 0 | 0 | 48 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzfh-p-fmin` | p- | none | 2541 | 1095 | 0 | 0 | 15 | 12 | 58 | 44 | 9 | 0 | 1 | 0 | 0 | 72 | 0 | 1 | 0 | 0 | 45 |
| `rv64uzfh-p-ldst` | p- | none | 1194 | 573 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 4 | 0 | 3 | 0 | 0 | 27 |
| `rv64uzfh-p-move` | p- | none | 1812 | 817 | 0 | 0 | 15 | 12 | 48 | 34 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 35 |
| `rv64uzfh-p-recoding` | p- | none | 1198 | 575 | 0 | 0 | 15 | 12 | 40 | 26 | 9 | 0 | 1 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 27 |
| `rv64uziccid-p-ziccid` | p- | none | 7364 | 4864 | 435 | 0 | 700 | 1340 | 1531 | 591 | 935 | 0 | 1 | 0 | 0 | 0 | 0 | 105 | 0 | 0 | 446 |
| `rv64uzicond-p-czero_eqz` | p- | none | 2389 | 1012 | 0 | 0 | 30 | 31 | 66 | 52 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64uzicond-p-czero_nez` | p- | none | 2377 | 1013 | 0 | 0 | 30 | 27 | 64 | 50 | 9 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ua-v-amoadd_d` | v- | 15/18 | 23926 | 7017 | 274 | 6 | 359 | 4733 | 2354 | 1280 | 1050 | 0 | 0 | 0 | 0 | 2891 | 0 | 1987 | 0 | 0 | 245 |
| `rv64ua-v-amoadd_w` | v- | 16/18 | 23960 | 7067 | 274 | 6 | 359 | 4734 | 2359 | 1281 | 1054 | 0 | 0 | 0 | 0 | 2891 | 0 | 1987 | 0 | 1 | 246 |
| `rv64ua-v-amoand_d` | v- | 17/18 | 24068 | 7139 | 276 | 6 | 367 | 4739 | 2370 | 1283 | 1063 | 0 | 0 | 0 | 0 | 2895 | 0 | 1987 | 0 | 1 | 248 |
| `rv64ua-v-amoand_w` | v- | 18/18 | 24071 | 7126 | 276 | 6 | 367 | 4739 | 2370 | 1283 | 1063 | 0 | 0 | 0 | 0 | 2895 | 0 | 1987 | 0 | 1 | 248 |
| `rv64ua-v-amomax_d` | v- | 1/18 | 23861 | 6975 | 273 | 6 | 352 | 4742 | 2352 | 1279 | 1049 | 0 | 0 | 0 | 0 | 2889 | 0 | 1988 | 0 | 0 | 243 |
| `rv64ua-v-amomax_w` | v- | 4/18 | 23909 | 7011 | 273 | 6 | 354 | 4730 | 2351 | 1279 | 1048 | 0 | 0 | 0 | 0 | 2890 | 0 | 1989 | 0 | 0 | 244 |
| `rv64ua-v-amomaxu_d` | v- | 2/18 | 23861 | 6975 | 273 | 6 | 352 | 4742 | 2352 | 1279 | 1049 | 0 | 0 | 0 | 0 | 2889 | 0 | 1988 | 0 | 0 | 243 |
| `rv64ua-v-amomaxu_w` | v- | 3/18 | 23909 | 7011 | 273 | 6 | 354 | 4730 | 2351 | 1279 | 1048 | 0 | 0 | 0 | 0 | 2890 | 0 | 1989 | 0 | 0 | 244 |
| `rv64ua-v-amomin_d` | v- | 5/18 | 23861 | 6975 | 273 | 6 | 352 | 4742 | 2352 | 1279 | 1049 | 0 | 0 | 0 | 0 | 2889 | 0 | 1988 | 0 | 0 | 243 |
| `rv64ua-v-amomin_w` | v- | 8/18 | 24058 | 7121 | 276 | 6 | 366 | 4738 | 2366 | 1282 | 1060 | 0 | 0 | 0 | 0 | 2896 | 0 | 1989 | 0 | 0 | 247 |
| `rv64ua-v-amominu_d` | v- | 6/18 | 23910 | 7007 | 276 | 7 | 356 | 4753 | 2363 | 1280 | 1059 | 0 | 0 | 0 | 0 | 2891 | 0 | 1988 | 0 | 0 | 246 |
| `rv64ua-v-amominu_w` | v- | 7/18 | 23958 | 7043 | 276 | 7 | 358 | 4741 | 2362 | 1280 | 1058 | 0 | 0 | 0 | 0 | 2892 | 0 | 1989 | 0 | 0 | 247 |
| `rv64ua-v-amoor_d` | v- | 9/18 | 23914 | 7005 | 274 | 7 | 356 | 4733 | 2357 | 1280 | 1053 | 0 | 0 | 0 | 0 | 2889 | 0 | 1987 | 0 | 1 | 246 |
| `rv64ua-v-amoor_w` | v- | 10/18 | 23914 | 7005 | 274 | 7 | 356 | 4733 | 2357 | 1280 | 1053 | 0 | 0 | 0 | 0 | 2889 | 0 | 1987 | 0 | 1 | 246 |
| `rv64ua-v-amoswap_d` | v- | 11/18 | 24068 | 7139 | 276 | 6 | 367 | 4739 | 2370 | 1283 | 1063 | 0 | 0 | 0 | 0 | 2895 | 0 | 1987 | 0 | 1 | 248 |
| `rv64ua-v-amoswap_w` | v- | 12/18 | 24071 | 7126 | 276 | 6 | 367 | 4739 | 2370 | 1283 | 1063 | 0 | 0 | 0 | 0 | 2895 | 0 | 1987 | 0 | 1 | 248 |
| `rv64ua-v-amoxor_d` | v- | 13/18 | 23916 | 7033 | 274 | 7 | 356 | 4733 | 2357 | 1280 | 1053 | 0 | 0 | 0 | 0 | 2889 | 0 | 1987 | 0 | 1 | 246 |
| `rv64ua-v-amoxor_w` | v- | 14/18 | 23923 | 7004 | 273 | 6 | 355 | 4731 | 2355 | 1280 | 1051 | 0 | 0 | 0 | 0 | 2889 | 0 | 1987 | 0 | 1 | 245 |
| `rv64ua-v-lrsc` | v- | 15/18 | 41845 | 11839 | 269 | 7 | 335 | 7124 | 4734 | 2379 | 2331 | 0 | 0 | 0 | 0 | 2891 | 1025 | 1986 | 1028 | 75 | 325 |
| `rv64uc-v-rvc` | v- | 14/18 | 33050 | 9504 | 925 | 37 | 487 | 8355 | 3553 | 1985 | 1544 | 0 | 0 | 0 | 0 | 4535 | 0 | 2601 | 0 | 0 | 330 |
| `rv64ud-v-fadd` | v- | 9/18 | 23566 | 6986 | 775 | 14 | 312 | 7582 | 2626 | 1654 | 948 | 0 | 0 | 0 | 0 | 3395 | 0 | 1433 | 0 | 0 | 232 |
| `rv64ud-v-fclass` | v- | 10/18 | 14141 | 4637 | 168 | 6 | 256 | 4059 | 1561 | 955 | 582 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 155 |
| `rv64ud-v-fcmp` | v- | 11/18 | 23874 | 7124 | 775 | 14 | 312 | 7583 | 2632 | 1659 | 949 | 0 | 0 | 0 | 0 | 3415 | 0 | 1433 | 0 | 0 | 237 |
| `rv64ud-v-fcvt` | v- | 12/18 | 23488 | 6971 | 774 | 14 | 314 | 7582 | 2627 | 1654 | 949 | 0 | 0 | 0 | 0 | 3372 | 0 | 1433 | 0 | 0 | 232 |
| `rv64ud-v-fcvt_w` | v- | 13/18 | 34125 | 9645 | 1376 | 20 | 367 | 11096 | 3696 | 2367 | 1305 | 0 | 0 | 0 | 0 | 5136 | 0 | 2044 | 0 | 0 | 319 |
| `rv64ud-v-fdiv` | v- | 14/18 | 23394 | 6923 | 775 | 14 | 312 | 7582 | 2624 | 1652 | 948 | 0 | 0 | 0 | 0 | 3387 | 0 | 1433 | 0 | 0 | 230 |
| `rv64ud-v-fmadd` | v- | 15/18 | 23715 | 7049 | 774 | 14 | 312 | 7579 | 2625 | 1656 | 945 | 0 | 0 | 0 | 0 | 3403 | 0 | 1433 | 0 | 0 | 234 |
| `rv64ud-v-fmin` | v- | 16/18 | 24197 | 7251 | 775 | 14 | 312 | 7582 | 2634 | 1662 | 948 | 0 | 0 | 0 | 0 | 3427 | 0 | 1433 | 0 | 0 | 240 |
| `rv64ud-v-ldst` | v- | 17/18 | 23572 | 6779 | 272 | 8 | 326 | 4742 | 2307 | 1282 | 1001 | 0 | 0 | 0 | 0 | 2901 | 0 | 1991 | 0 | 0 | 240 |
| `rv64ud-v-move` | v- | 18/18 | 24427 | 6863 | 776 | 14 | 314 | 7588 | 2623 | 1644 | 955 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 222 |
| `rv64ud-v-recoding` | v- | 1/18 | 23884 | 6986 | 282 | 13 | 345 | 4767 | 2338 | 1287 | 1027 | 0 | 0 | 0 | 0 | 2908 | 0 | 1987 | 0 | 0 | 250 |
| `rv64ud-v-structural` | v- | 2/18 | 14883 | 5404 | 166 | 6 | 368 | 4078 | 1668 | 976 | 668 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 180 |
| `rv64uf-v-fadd` | v- | 16/18 | 23566 | 6986 | 775 | 14 | 312 | 7582 | 2626 | 1654 | 948 | 0 | 0 | 0 | 0 | 3395 | 0 | 1433 | 0 | 0 | 232 |
| `rv64uf-v-fclass` | v- | 17/18 | 14125 | 4631 | 168 | 6 | 256 | 4059 | 1561 | 955 | 582 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 155 |
| `rv64uf-v-fcmp` | v- | 18/18 | 23874 | 7124 | 775 | 14 | 312 | 7583 | 2632 | 1659 | 949 | 0 | 0 | 0 | 0 | 3415 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uf-v-fcvt` | v- | 1/18 | 23269 | 6868 | 774 | 14 | 313 | 7582 | 2624 | 1652 | 948 | 0 | 0 | 0 | 0 | 3363 | 0 | 1433 | 0 | 0 | 230 |
| `rv64uf-v-fcvt_w` | v- | 2/18 | 33789 | 9556 | 1377 | 20 | 367 | 11099 | 3694 | 2362 | 1308 | 0 | 0 | 0 | 0 | 5116 | 0 | 2044 | 0 | 0 | 314 |
| `rv64uf-v-fdiv` | v- | 3/18 | 23316 | 6883 | 775 | 14 | 312 | 7582 | 2623 | 1651 | 948 | 0 | 0 | 0 | 0 | 3383 | 0 | 1433 | 0 | 0 | 229 |
| `rv64uf-v-fmadd` | v- | 4/18 | 23715 | 7049 | 774 | 14 | 312 | 7579 | 2625 | 1656 | 945 | 0 | 0 | 0 | 0 | 3403 | 0 | 1433 | 0 | 0 | 234 |
| `rv64uf-v-fmin` | v- | 5/18 | 24197 | 7251 | 775 | 14 | 312 | 7582 | 2634 | 1662 | 948 | 0 | 0 | 0 | 0 | 3427 | 0 | 1433 | 0 | 0 | 240 |
| `rv64uf-v-ldst` | v- | 6/18 | 23775 | 6911 | 280 | 12 | 347 | 4762 | 2335 | 1286 | 1025 | 0 | 0 | 0 | 0 | 2903 | 0 | 1988 | 0 | 0 | 248 |
| `rv64uf-v-move` | v- | 7/18 | 14695 | 4819 | 167 | 6 | 255 | 4054 | 1564 | 963 | 577 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 163 |
| `rv64uf-v-recoding` | v- | 8/18 | 22830 | 6666 | 774 | 14 | 317 | 7579 | 2617 | 1644 | 949 | 0 | 0 | 0 | 0 | 3357 | 0 | 1433 | 0 | 0 | 222 |
| `rv64ui-v-add` | v- | 1/18 | 15388 | 5066 | 168 | 6 | 270 | 4077 | 1586 | 982 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-addi` | v- | 2/18 | 14562 | 4785 | 168 | 6 | 262 | 4063 | 1569 | 964 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-addiw` | v- | 3/18 | 14556 | 4793 | 168 | 6 | 262 | 4066 | 1570 | 965 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-addw` | v- | 4/18 | 15377 | 5079 | 168 | 6 | 271 | 4080 | 1589 | 982 | 583 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-and` | v- | 7/18 | 15565 | 5119 | 168 | 6 | 271 | 4083 | 1591 | 984 | 583 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-andi` | v- | 8/18 | 14538 | 4785 | 168 | 6 | 262 | 4064 | 1568 | 964 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-auipc` | v- | 12/18 | 13979 | 4900 | 147 | 23 | 314 | 4108 | 1646 | 956 | 666 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 154 |
| `rv64ui-v-beq` | v- | 13/18 | 15302 | 5152 | 167 | 7 | 280 | 4075 | 1589 | 989 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 180 |
| `rv64ui-v-bge` | v- | 14/18 | 15596 | 5390 | 167 | 7 | 291 | 4090 | 1599 | 998 | 577 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 189 |
| `rv64ui-v-bgeu` | v- | 15/18 | 15836 | 5378 | 167 | 7 | 289 | 4081 | 1601 | 1000 | 577 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 189 |
| `rv64ui-v-blt` | v- | 16/18 | 15303 | 5152 | 167 | 7 | 280 | 4075 | 1589 | 989 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 180 |
| `rv64ui-v-bltu` | v- | 17/18 | 15523 | 5223 | 167 | 6 | 280 | 4077 | 1592 | 992 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 180 |
| `rv64ui-v-bne` | v- | 18/18 | 15354 | 5184 | 167 | 7 | 282 | 4076 | 1591 | 991 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 182 |
| `rv64ui-v-fence_i` | v- | 17/18 | 24755 | 7379 | 281 | 13 | 362 | 5140 | 2475 | 1391 | 1060 | 0 | 0 | 0 | 0 | 2901 | 0 | 1990 | 0 | 0 | 264 |
| `rv64ui-v-jal` | v- | 1/18 | 13988 | 4858 | 166 | 6 | 306 | 4091 | 1615 | 956 | 635 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 156 |
| `rv64ui-v-jalr` | v- | 2/18 | 14334 | 4909 | 169 | 9 | 302 | 4081 | 1622 | 968 | 630 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 175 |
| `rv64ui-v-lb` | v- | 3/18 | 23398 | 6913 | 777 | 14 | 321 | 7602 | 2636 | 1655 | 957 | 0 | 0 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ui-v-lbu` | v- | 4/18 | 23398 | 6913 | 777 | 14 | 321 | 7602 | 2636 | 1655 | 957 | 0 | 0 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ui-v-ld` | v- | 9/18 | 23922 | 7019 | 778 | 14 | 327 | 7603 | 2648 | 1655 | 969 | 0 | 0 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 229 |
| `rv64ui-v-ld_st` | v- | 14/18 | 44110 | 12597 | 1460 | 20 | 692 | 11740 | 4584 | 2713 | 1847 | 0 | 0 | 0 | 0 | 6422 | 0 | 3485 | 0 | 0 | 465 |
| `rv64ui-v-lh` | v- | 5/18 | 23425 | 6933 | 776 | 14 | 321 | 7599 | 2636 | 1655 | 957 | 0 | 0 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ui-v-lhu` | v- | 6/18 | 23449 | 6930 | 776 | 14 | 320 | 7600 | 2636 | 1655 | 957 | 0 | 0 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ui-v-lui` | v- | 11/18 | 13996 | 4568 | 167 | 6 | 258 | 4056 | 1558 | 954 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 154 |
| `rv64ui-v-lw` | v- | 7/18 | 23451 | 6935 | 776 | 14 | 320 | 7598 | 2635 | 1655 | 956 | 0 | 0 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ui-v-lwu` | v- | 8/18 | 23518 | 6946 | 776 | 14 | 321 | 7597 | 2635 | 1655 | 956 | 0 | 0 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ui-v-ma_data` | v- | 18/18 | 46560 | 13025 | 1460 | 22 | 744 | 11852 | 4718 | 2744 | 1950 | 0 | 0 | 0 | 0 | 6327 | 0 | 3343 | 0 | 0 | 533 |
| `rv64ui-v-or` | v- | 9/18 | 15636 | 5078 | 168 | 6 | 270 | 4076 | 1589 | 984 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-ori` | v- | 10/18 | 14518 | 4790 | 168 | 6 | 261 | 4066 | 1571 | 965 | 582 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-sb` | v- | 10/18 | 24714 | 8364 | 268 | 7 | 529 | 4785 | 2521 | 1312 | 1185 | 0 | 0 | 0 | 0 | 2921 | 0 | 2021 | 0 | 1 | 258 |
| `rv64ui-v-sd` | v- | 13/18 | 33723 | 10345 | 867 | 15 | 557 | 8296 | 3548 | 2001 | 1523 | 0 | 0 | 0 | 0 | 4550 | 0 | 2631 | 0 | 1 | 322 |
| `rv64ui-v-sh` | v- | 11/18 | 24801 | 8329 | 268 | 7 | 522 | 4782 | 2517 | 1312 | 1181 | 0 | 0 | 0 | 0 | 2921 | 0 | 2021 | 0 | 1 | 258 |
| `rv64ui-v-simple` | v- | 16/18 | 13932 | 4493 | 167 | 6 | 256 | 4054 | 1555 | 953 | 578 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 153 |
| `rv64ui-v-sll` | v- | 17/18 | 24297 | 7078 | 776 | 14 | 329 | 7604 | 2649 | 1670 | 955 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 236 |
| `rv64ui-v-slli` | v- | 18/18 | 14612 | 4796 | 168 | 6 | 262 | 4066 | 1571 | 965 | 582 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-slliw` | v- | 1/18 | 14625 | 4791 | 168 | 6 | 262 | 4063 | 1569 | 964 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-sllw` | v- | 2/18 | 24295 | 7080 | 776 | 14 | 328 | 7606 | 2649 | 1670 | 955 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 236 |
| `rv64ui-v-slt` | v- | 13/18 | 15365 | 5078 | 168 | 6 | 270 | 4075 | 1585 | 981 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-slti` | v- | 14/18 | 14553 | 4785 | 168 | 6 | 262 | 4066 | 1570 | 965 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-sltiu` | v- | 16/18 | 14553 | 4785 | 168 | 6 | 262 | 4066 | 1570 | 965 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-sltu` | v- | 15/18 | 15371 | 5029 | 168 | 6 | 268 | 4084 | 1580 | 980 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 168 |
| `rv64ui-v-sra` | v- | 7/18 | 15462 | 5023 | 168 | 6 | 270 | 4075 | 1585 | 981 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-srai` | v- | 8/18 | 14589 | 4802 | 168 | 6 | 263 | 4062 | 1569 | 963 | 582 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-sraiw` | v- | 9/18 | 14671 | 4789 | 168 | 6 | 259 | 4076 | 1567 | 964 | 579 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64ui-v-sraw` | v- | 10/18 | 24311 | 7060 | 776 | 14 | 328 | 7606 | 2649 | 1670 | 955 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 236 |
| `rv64ui-v-srl` | v- | 3/18 | 24347 | 7110 | 776 | 14 | 329 | 7609 | 2652 | 1672 | 956 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 236 |
| `rv64ui-v-srli` | v- | 4/18 | 14641 | 4809 | 168 | 6 | 262 | 4067 | 1572 | 965 | 583 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-srliw` | v- | 5/18 | 14638 | 4799 | 168 | 6 | 262 | 4067 | 1571 | 965 | 582 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ui-v-srlw` | v- | 6/18 | 24306 | 7070 | 776 | 14 | 328 | 7608 | 2650 | 1671 | 955 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 236 |
| `rv64ui-v-st_ld` | v- | 15/18 | 33135 | 8981 | 872 | 15 | 380 | 8260 | 3349 | 1968 | 1357 | 0 | 0 | 0 | 0 | 4586 | 0 | 2667 | 0 | 0 | 302 |
| `rv64ui-v-sub` | v- | 5/18 | 15371 | 5081 | 168 | 6 | 271 | 4080 | 1589 | 982 | 583 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-subw` | v- | 6/18 | 15333 | 5040 | 168 | 6 | 267 | 4088 | 1582 | 982 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 168 |
| `rv64ui-v-sw` | v- | 12/18 | 24819 | 8313 | 268 | 7 | 530 | 4784 | 2521 | 1312 | 1185 | 0 | 0 | 0 | 0 | 2921 | 0 | 2020 | 0 | 1 | 258 |
| `rv64ui-v-xor` | v- | 11/18 | 15633 | 5094 | 168 | 6 | 270 | 4075 | 1589 | 984 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-xori` | v- | 12/18 | 14520 | 4788 | 168 | 6 | 262 | 4067 | 1571 | 966 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64um-v-div` | v- | 5/18 | 14102 | 4616 | 168 | 6 | 256 | 4058 | 1559 | 954 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 154 |
| `rv64um-v-divu` | v- | 6/18 | 14112 | 4624 | 168 | 6 | 257 | 4059 | 1560 | 954 | 582 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 154 |
| `rv64um-v-divuw` | v- | 11/18 | 14100 | 4623 | 168 | 6 | 256 | 4059 | 1560 | 954 | 582 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 154 |
| `rv64um-v-divw` | v- | 10/18 | 14055 | 4578 | 168 | 6 | 253 | 4069 | 1556 | 954 | 578 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 153 |
| `rv64um-v-mul` | v- | 1/18 | 15413 | 5095 | 168 | 6 | 271 | 4073 | 1583 | 980 | 579 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64um-v-mulh` | v- | 2/18 | 15410 | 5109 | 168 | 6 | 270 | 4080 | 1588 | 984 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64um-v-mulhsu` | v- | 3/18 | 15411 | 5102 | 168 | 6 | 270 | 4080 | 1587 | 984 | 579 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64um-v-mulhu` | v- | 4/18 | 15470 | 5095 | 168 | 6 | 270 | 4080 | 1588 | 984 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64um-v-mulw` | v- | 9/18 | 15263 | 5079 | 168 | 6 | 270 | 4075 | 1585 | 981 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64um-v-rem` | v- | 7/18 | 14083 | 4614 | 168 | 6 | 256 | 4058 | 1559 | 954 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 154 |
| `rv64um-v-remu` | v- | 8/18 | 14087 | 4607 | 168 | 6 | 256 | 4058 | 1559 | 954 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 154 |
| `rv64um-v-remuw` | v- | 13/18 | 14075 | 4606 | 168 | 6 | 256 | 4058 | 1559 | 954 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 154 |
| `rv64um-v-remw` | v- | 12/18 | 14055 | 4578 | 168 | 6 | 253 | 4069 | 1556 | 954 | 578 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 153 |
| `rv64uzba-v-add_uw` | v- | 3/18 | 15350 | 5256 | 56 | 6 | 276 | 4122 | 1636 | 982 | 632 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64uzba-v-sh1add` | v- | 4/18 | 15361 | 5251 | 56 | 6 | 276 | 4124 | 1637 | 983 | 632 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64uzba-v-sh1add_uw` | v- | 5/18 | 15363 | 5250 | 56 | 6 | 276 | 4124 | 1637 | 983 | 632 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64uzba-v-sh2add` | v- | 6/18 | 15361 | 5251 | 56 | 6 | 276 | 4124 | 1637 | 983 | 632 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64uzba-v-sh2add_uw` | v- | 7/18 | 15363 | 5250 | 56 | 6 | 276 | 4124 | 1637 | 983 | 632 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64uzba-v-sh3add` | v- | 8/18 | 15361 | 5251 | 56 | 6 | 276 | 4124 | 1637 | 983 | 632 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64uzba-v-sh3add_uw` | v- | 9/18 | 15363 | 5250 | 56 | 6 | 276 | 4124 | 1637 | 983 | 632 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64uzba-v-slli_uw` | v- | 10/18 | 14589 | 4984 | 56 | 6 | 268 | 4113 | 1621 | 966 | 633 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 162 |
| `rv64uzbb-v-andn` | v- | 11/18 | 15622 | 5104 | 163 | 6 | 270 | 3828 | 1583 | 985 | 574 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 170 |
| `rv64uzbb-v-clz` | v- | 12/18 | 14458 | 4785 | 163 | 6 | 260 | 3812 | 1559 | 960 | 575 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-clzw` | v- | 13/18 | 14436 | 4784 | 163 | 6 | 261 | 3813 | 1561 | 960 | 577 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-cpop` | v- | 14/18 | 14458 | 4785 | 163 | 6 | 260 | 3812 | 1559 | 960 | 575 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-cpopw` | v- | 15/18 | 14436 | 4784 | 163 | 6 | 261 | 3813 | 1561 | 960 | 577 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-ctz` | v- | 16/18 | 14458 | 4785 | 163 | 6 | 260 | 3812 | 1559 | 960 | 575 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-ctzw` | v- | 17/18 | 14436 | 4783 | 163 | 6 | 261 | 3814 | 1562 | 961 | 577 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-max` | v- | 18/18 | 15353 | 5096 | 163 | 6 | 266 | 3825 | 1575 | 980 | 571 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64uzbb-v-maxu` | v- | 1/18 | 15446 | 5094 | 163 | 6 | 271 | 3828 | 1580 | 983 | 573 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 170 |
| `rv64uzbb-v-min` | v- | 2/18 | 15380 | 5131 | 163 | 6 | 271 | 3827 | 1581 | 981 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 170 |
| `rv64uzbb-v-minu` | v- | 3/18 | 15423 | 5105 | 163 | 6 | 271 | 3828 | 1580 | 983 | 573 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 170 |
| `rv64uzbb-v-orc_b` | v- | 4/18 | 14503 | 4793 | 163 | 6 | 261 | 3811 | 1559 | 960 | 575 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-orn` | v- | 5/18 | 24458 | 7228 | 773 | 14 | 335 | 7374 | 2670 | 1674 | 972 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 241 |
| `rv64uzbb-v-rev8` | v- | 6/18 | 14548 | 4804 | 163 | 6 | 261 | 3813 | 1561 | 960 | 577 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-rol` | v- | 7/18 | 24397 | 7184 | 773 | 14 | 336 | 7370 | 2665 | 1672 | 969 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 241 |
| `rv64uzbb-v-rolw` | v- | 8/18 | 24390 | 7181 | 773 | 14 | 336 | 7369 | 2664 | 1672 | 968 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 241 |
| `rv64uzbb-v-ror` | v- | 9/18 | 24433 | 7171 | 773 | 14 | 336 | 7366 | 2665 | 1671 | 970 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 241 |
| `rv64uzbb-v-rori` | v- | 10/18 | 14663 | 4856 | 163 | 6 | 262 | 3817 | 1565 | 965 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 161 |
| `rv64uzbb-v-roriw` | v- | 11/18 | 14571 | 4840 | 163 | 6 | 262 | 3817 | 1564 | 966 | 574 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 161 |
| `rv64uzbb-v-rorw` | v- | 12/18 | 15458 | 5077 | 163 | 6 | 270 | 3826 | 1579 | 982 | 573 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 170 |
| `rv64uzbb-v-sext_b` | v- | 13/18 | 14458 | 4785 | 163 | 6 | 260 | 3812 | 1559 | 960 | 575 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-sext_h` | v- | 14/18 | 14467 | 4786 | 163 | 6 | 260 | 3813 | 1560 | 961 | 575 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbb-v-xnor` | v- | 15/18 | 24488 | 7244 | 773 | 14 | 336 | 7373 | 2668 | 1675 | 969 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 241 |
| `rv64uzbb-v-zext_h` | v- | 16/18 | 14473 | 4789 | 163 | 6 | 260 | 3811 | 1559 | 960 | 575 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64uzbc-v-clmul` | v- | 17/18 | 15414 | 5092 | 168 | 6 | 271 | 4077 | 1585 | 982 | 579 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64uzbc-v-clmulh` | v- | 18/18 | 15424 | 5091 | 168 | 6 | 271 | 4077 | 1586 | 982 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64uzbc-v-clmulr` | v- | 1/18 | 15422 | 5089 | 168 | 6 | 271 | 4072 | 1582 | 979 | 579 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64uzbkb-v-brev8` | v- | 2/18 | 14524 | 4926 | 247 | 7 | 267 | 3833 | 1563 | 960 | 579 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 161 |
| `rv64uzbkb-v-pack` | v- | 3/18 | 24805 | 7464 | 856 | 14 | 351 | 7403 | 2676 | 1675 | 977 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 245 |
| `rv64uzbkb-v-packh` | v- | 4/18 | 15604 | 5310 | 247 | 6 | 277 | 3851 | 1583 | 983 | 576 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 173 |
| `rv64uzbkb-v-packw` | v- | 5/18 | 15453 | 5310 | 247 | 6 | 278 | 3849 | 1587 | 983 | 580 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 173 |
| `rv64uzbkx-v-xperm4` | v- | 6/18 | 24529 | 7150 | 776 | 14 | 332 | 7610 | 2657 | 1673 | 960 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uzbkx-v-xperm8` | v- | 7/18 | 25372 | 7349 | 776 | 14 | 332 | 7606 | 2658 | 1673 | 961 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uzbs-v-bclr` | v- | 8/18 | 24528 | 7204 | 816 | 14 | 340 | 7294 | 2606 | 1673 | 909 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uzbs-v-bclri` | v- | 9/18 | 14686 | 4875 | 166 | 6 | 266 | 3799 | 1552 | 966 | 562 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64uzbs-v-bext` | v- | 10/18 | 24386 | 7185 | 817 | 14 | 339 | 7299 | 2606 | 1673 | 909 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uzbs-v-bexti` | v- | 11/18 | 14617 | 4861 | 166 | 6 | 266 | 3800 | 1552 | 966 | 562 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64uzbs-v-binv` | v- | 12/18 | 24349 | 7170 | 817 | 14 | 339 | 7297 | 2602 | 1671 | 907 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uzbs-v-binvi` | v- | 13/18 | 14601 | 4850 | 165 | 6 | 266 | 3795 | 1549 | 964 | 561 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64uzbs-v-bset` | v- | 14/18 | 24532 | 7204 | 816 | 14 | 340 | 7294 | 2606 | 1673 | 909 | 0 | 0 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uzbs-v-bseti` | v- | 15/18 | 14700 | 4883 | 166 | 6 | 266 | 3796 | 1551 | 965 | 562 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64uzfh-v-fadd` | v- | 16/18 | 23566 | 6986 | 775 | 14 | 312 | 7582 | 2626 | 1654 | 948 | 0 | 0 | 0 | 0 | 3395 | 0 | 1433 | 0 | 0 | 232 |
| `rv64uzfh-v-fclass` | v- | 17/18 | 14116 | 4629 | 168 | 6 | 256 | 4059 | 1560 | 955 | 581 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 155 |
| `rv64uzfh-v-fcmp` | v- | 18/18 | 23208 | 6836 | 775 | 14 | 313 | 7583 | 2624 | 1650 | 950 | 0 | 0 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 228 |
| `rv64uzfh-v-fcvt` | v- | 1/18 | 23431 | 6933 | 774 | 14 | 313 | 7582 | 2626 | 1654 | 948 | 0 | 0 | 0 | 0 | 3371 | 0 | 1433 | 0 | 0 | 232 |
| `rv64uzfh-v-fcvt_w` | v- | 2/18 | 33789 | 9556 | 1377 | 20 | 367 | 11099 | 3694 | 2362 | 1308 | 0 | 0 | 0 | 0 | 5116 | 0 | 2044 | 0 | 0 | 314 |
| `rv64uzfh-v-fdiv` | v- | 3/18 | 23316 | 6883 | 775 | 14 | 312 | 7582 | 2623 | 1651 | 948 | 0 | 0 | 0 | 0 | 3383 | 0 | 1433 | 0 | 0 | 229 |
| `rv64uzfh-v-fmadd` | v- | 4/18 | 23715 | 7049 | 774 | 14 | 312 | 7579 | 2625 | 1656 | 945 | 0 | 0 | 0 | 0 | 3403 | 0 | 1433 | 0 | 0 | 234 |
| `rv64uzfh-v-fmin` | v- | 5/18 | 24197 | 7251 | 775 | 14 | 312 | 7582 | 2634 | 1662 | 948 | 0 | 0 | 0 | 0 | 3427 | 0 | 1433 | 0 | 0 | 240 |
| `rv64uzfh-v-ldst` | v- | 6/18 | 23820 | 6941 | 281 | 12 | 346 | 4764 | 2337 | 1286 | 1027 | 0 | 0 | 0 | 0 | 2903 | 0 | 1988 | 0 | 0 | 248 |
| `rv64uzfh-v-move` | v- | 7/18 | 14690 | 4815 | 167 | 6 | 255 | 4054 | 1564 | 963 | 577 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 163 |
| `rv64uzfh-v-recoding` | v- | 8/18 | 22830 | 6666 | 774 | 14 | 317 | 7579 | 2617 | 1644 | 949 | 0 | 0 | 0 | 0 | 3357 | 0 | 1433 | 0 | 0 | 222 |
| `rv64uziccid-v-ziccid` | v- | 11/18 | 164934 | 41280 | 10130 | 103 | 1714 | 61005 | 18976 | 12898 | 6054 | 0 | 0 | 0 | 0 | 29013 | 0 | 11907 | 0 | 0 | 1287 |
| `rv64uzicond-v-czero_eqz` | v- | 9/18 | 15378 | 5278 | 155 | 6 | 272 | 3837 | 1575 | 979 | 572 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64uzicond-v-czero_nez` | v- | 10/18 | 15379 | 5287 | 155 | 6 | 272 | 3840 | 1577 | 981 | 572 | 0 | 0 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 171 |
