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

## All 2813 results

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
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_does_not_carry_a_bb_idx | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_is_buffered_unconditionally | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_is_consumed_after_the_auto_transition_and_overrides_it | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_is_running_two_cycles_later | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_resteer_redirects_bacpc_and_flushes_the_ftq | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_the_ack_survives_a_higher_priority_squash | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2ResteerProtocol::test_the_first_post_resteer_ft_forms_at_the_redirected_pc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2RetryNeverDrop::test_a_resteer_under_backpressure_is_not_discarded | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2RetryNeverDrop::test_a_squash_under_backpressure_is_not_discarded | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2RetryNeverDrop::test_drain_squash_under_backpressure_is_retried | block-BACV2 | PASS | - | 0 |
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
| test_bac_v2_cl.TestBACV2StatusFSM::test_drain_stall_squashes_and_goes_idle | block-BACV2 | PASS | - | 0 |
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
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_commit_mispredict_anchors_at_the_mispredicting_insts_row | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_commit_type0_squash_anchors_at_the_latched_head_row | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_constructed_squash_freed_younger_equals_flushed_minus_anchor | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_decode_mispredict_anchors_at_the_dec_bb_idx | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_resteer_anchors_at_the_oldest_ftq_row | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_type0_falls_back_to_the_ftq_oldest_when_the_latch_is_absent | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_a_younger_squash_is_dropped_while_the_slot_is_occupied | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_outstanding_squash_survives_many_ticks_of_backpressure | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_redirect_is_applied_immediately_not_on_landing | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_status_holds_squashing_until_the_squash_lands | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_a_fresh_thread_with_no_live_row_sends_the_invalid_anchor | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_absent_latch_falls_to_the_ft_covering_the_pc | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_anchor_is_the_ft_stamped_row | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_unreachable_latch_and_no_covering_entry_falls_to | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_drain_type0_anchor_is_the_ftq_oldest_row | block-BACV2 | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_the_anchor_is_re_read_every_squash_not_latched | block-BACV2 | PASS | - | 0 |
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
| test_bimodal_v2_cl.TestTrainModeRouting::test_an_unknown_train_mode_is_a_loud_construct_failure | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestTrainModeRouting::test_commit_mode_trains_only_the_commit_arm | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestTrainModeRouting::test_default_mode_is_squash | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestTrainModeRouting::test_one_counter_update_per_occurrence_in_both_modes | block-BPredUnitV2 | PASS | - | 0 |
| test_bimodal_v2_cl.TestTrainModeRouting::test_squash_mode_trains_only_the_squashed_arm | block-BPredUnitV2 | PASS | - | 0 |
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
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_no_taken_record_yields_terminal_minus_one_and_zero_target | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_only_records_up_to_the_terminal_push_history | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_terminal_is_the_lowest_taken_record | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_terminal_target_comes_from_the_btb_record | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3WriteEntryOrdering::test_same_cycle_alloc_and_write_entry_leaves_the_written_row | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3WriteEntryOrdering::test_the_rows_checkpoint_is_the_one_the_entry_allocated | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Accounting::test_allocation_accounting_balances_over_a_long_sequence | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Accounting::test_the_accounting_counter_notices_a_missing_release | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4BitmapResidency::test_a_pre_terminal_member_reads_bb_n_image_after_bb_n1_predicts | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4ModeRouting::test_commit_mode_raises_at_construct | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4ModeRouting::test_squash_mode_does_not_train_at_commit | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_a_commit_matching_the_head_does_not_release | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_a_commit_naming_a_newer_row_releases_the_head_row_and_its_ckpt | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_releasing_a_row_whose_ckpt_was_never_allocated_is_safe | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_two_releases_on_one_head_do_not_double_free | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4ReleaseNonDegeneracy::test_a_commit_naming_a_gap_row_releases_the_row_at_the_head_only | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4ReleaseNonDegeneracy::test_the_head_naming_commit_is_inert_while_rows_are_live | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Backpressure::test_a_second_squash_does_not_displace_the_first | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Backpressure::test_rdy_is_false_while_a_squash_is_outstanding | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5BulkSquash::test_a_type_zero_squash_never_trains_even_when_taken | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5BulkSquash::test_a_type_zero_squash_truncates_without_training_or_writing_ghr | block-BPredUnitV2 | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5CorrectiveTrain::test_the_corrective_trains_at_the_rows_ckpt_image_not_the_live_ghr | block-BPredUnitV2 | PASS | - | 0 |
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
| test_bpu_v2_btb_install.TestInstallPathGating::test_a_bulk_squash_does_not_install | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallPathGating::test_the_commit_path_does_not_install | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallPortDiscipline::test_the_install_is_issued_through_the_update_port | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestL5BtbInstall::test_a_taken_corrective_installs_a_btb_record | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestL5BtbInstall::test_the_installed_inst_size_uses_the_one_bit_convention | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_btb_install.TestL5BtbInstall::test_the_installed_record_lands_in_the_branchs_own_window | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_construct_rejects_an_unknown_cpred_type | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_drain_complete_reports_drained_on_a_fresh_bpu | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_elaborates_with_bimodal | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_exposes_exactly_the_stub_bpu_port_surface | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_exposes_the_cur_bb_idx_squash_anchor | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_port_request_types_match_the_stub | block-BPredUnitV2 | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_squash_req_carries_rdy_and_returns_a_resp | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_full_set_evicts_the_least_recently_used_way | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_later_install_leaves_the_windows_sibling_records_untouched | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_a_later_install_overwrites_the_pool_slot_it_reuses | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_aliasing_windows_are_distinguished_by_tag | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_all_sixteen_slots_of_a_window_may_hold_members | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_direct_call_records_consume_a_slot_and_return_call_records_do_not | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_evict_to_admit_never_hard_fails_a_whole_window_replacement | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_evicting_a_slot_consumer_frees_its_slot | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_flush_clears_every_way_of_every_set | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_install_is_visible_exactly_one_cycle_after_acceptance | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_invalid_ways_are_filled_before_a_valid_way_is_evicted | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_pool_covers_a_real_dense_window_resident_plus_one | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_pool_depth_is_the_documented_null_plus_slots | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_pool_exhaustion_across_ways_is_reached_only_past_the_measured_max | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_record_fields_round_trip_through_an_install | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_record_pc_is_the_window_base_plus_twice_the_offset | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_records_of_one_set_read_their_targets_from_the_shared_pool | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_return_and_indirect_records_consume_no_target_slot | block-BPredUnitV2 | PASS | - | 0 |
| test_btb_v2_cl::test_same_window_trainings_in_one_pass_coalesce_into_one_write | block-BPredUnitV2 | PASS | - | 0 |
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
| test_gshare_v2_cl.TestTrainReq::test_commit_mode_does_not_train_on_a_squashed_event | block-BPredUnitV2 | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_squash_mode_does_not_train_on_a_non_squashed_event | block-BPredUnitV2 | PASS | - | 0 |
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
| test_v1_v2_parity::test_v1_v2_commit_value_stream_parity | block-BPredUnitV2 | PASS | - | 10 |
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
| test_fetch_cl.TestAssertionANoBBLeftUnmarked::test_rv64ui_p_add_leaves_no_bb_unmarked | block-Fetch | PASS | - | 7 |
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
| test_frontend_v2_compose.TestScheduleSeedSweep::test_identical_outcomes_across_schedule_seeds | block-FrontEnd | PASS | - | 2 |
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
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_core_frontend_carries_the_v2_blocks | block-Testbench | PASS | - | 0 |
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_core_frontend_is_frontend_v2 | block-Testbench | PASS | - | 0 |
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_v2_core_exposes_the_testbench_surface | block-Testbench | PASS | - | 0 |
| test_o3_core_v2.TestElfOnV2Core::test_rv64ui_p_add_passes_on_v2 | block-Testbench | FAIL | - | 8 |
| test_o3_core_v2.TestElfOnV2Core::test_v2_core_commits_instructions_and_retires_stores | block-Testbench | FAIL | - | 8 |
| test_o3_core_v2.TestNackChainOrdering::test_elf_reaches_exit_on_every_schedule_seed | block-Testbench | FAIL | - | 48 |
| test_o3_core_v2.TestNackChainOrdering::test_no_seed_stalls_the_frontend | block-Testbench | FAIL | - | 47 |
| test_o3_core_v2.TestNackChainOrdering::test_the_sweep_actually_executed_the_frontend | block-Testbench | FAIL | - | 9 |
| test_riscv_tests_isa::test_riscv_tests_smoke_add | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-add:R-type addition] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addi:I-type add immediate] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addiw:IW-type add immediate] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addw:R-type add word] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-and:R-type AND] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-andi:I-type AND immediate] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-auipc:add upper immediate to PC] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-beq:branch equal] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bge:branch greater equal] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bgeu:branch greater equal unsigned] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-blt:branch less than] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bltu:branch less than unsigned] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bne:branch not equal] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-fence_i:instruction fence] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-jal:jump and link] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-jalr:jump and link register] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lb:load byte] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lbu:load byte unsigned] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-ld:load double] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lh:load half] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lhu:load half unsigned] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lui:load upper immediate] | block-Testbench | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lw:load word] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lwu:load word unsigned] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-or:R-type OR] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-ori:I-type OR immediate] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sb:store byte] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sd:store double] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sh:store half] | block-Testbench | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sll:shift left logical] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slli:shift left logical immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sllw:shift left logical word] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slt:set less than] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slti:set less than immediate] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sltiu:set less than immediate unsigned] | block-Testbench | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sltu:set less than unsigned] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sra:shift right arithmetic] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srai:shift right arithmetic immediate] | block-Testbench | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sraw:shift right arithmetic word] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srl:shift right logical] | block-Testbench | PASS | - | 9 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srli:shift right logical immediate] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srlw:shift right logical word] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sub:R-type subtraction] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-subw:R-type sub word] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sw:store word] | block-Testbench | PASS | - | 8 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-xor:R-type XOR] | block-Testbench | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-xori:I-type XOR immediate] | block-Testbench | PASS | - | 5 |
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
| hypervisor-p-2-stage_translation_implicit_load_error | p- | PASS | 1656 | 15 |
| hypervisor-p-2-stage_translation_implicit_load_error_hs | p- | PASS | 1831 | 15 |
| hypervisor-svadu-p-2-stage_translation_implicit_store_error | p- | PASS | 1777 | 15 |
| hypervisor-svadu-p-2-stage_translation_implicit_store_error_hs | p- | PASS | 1944 | 14 |
| rv64mi-p-breakpoint | p- | PASS | 3480 | 23 |
| rv64mi-p-csr | p- | PASS | 3535 | 24 |
| rv64mi-p-illegal | p- | PASS | 4575 | 29 |
| rv64mi-p-instret_overflow | p- | PASS | 1258 | 10 |
| rv64mi-p-ld-misaligned | p- | PASS | 1386 | 10 |
| rv64mi-p-lh-misaligned | p- | PASS | 1102 | 9 |
| rv64mi-p-lw-misaligned | p- | PASS | 1171 | 10 |
| rv64mi-p-ma_addr | p- | PASS | 1540 | 12 |
| rv64mi-p-ma_fetch | p- | PASS | 1939 | 14 |
| rv64mi-p-mcsr | p- | PASS | 1342 | 10 |
| rv64mi-p-pmpaddr | p- | PASS | 1185 | 9 |
| rv64mi-p-sbreak | p- | PASS | 1312 | 10 |
| rv64mi-p-scall | p- | PASS | 1259 | 10 |
| rv64mi-p-sd-misaligned | p- | PASS | 1436 | 11 |
| rv64mi-p-sh-misaligned | p- | PASS | 1109 | 9 |
| rv64mi-p-sw-misaligned | p- | PASS | 1150 | 9 |
| rv64mi-p-zicntr | p- | PASS | 1439 | 12 |
| rv64mzicbo-p-zero | p- | PASS | 1160 | 10 |
| rv64si-p-csr | p- | PASS | 2277 | 17 |
| rv64si-p-dirty | p- | PASS | 2337 | 17 |
| rv64si-p-icache-alias | p- | PASS | 2385 | 16 |
| rv64si-p-ma_fetch | p- | PASS | 1374 | 10 |
| rv64si-p-sbreak | p- | PASS | 1325 | 10 |
| rv64si-p-scall | p- | PASS | 1443 | 11 |
| rv64si-p-wfi | p- | PASS | 1173 | 9 |
| rv64ssvnapot-p-napot | p- | PASS | 1658 | 13 |
| rv64ua-p-amoadd_d | p- | PASS | 1081 | 9 |
| rv64ua-p-amoadd_w | p- | PASS | 1120 | 9 |
| rv64ua-p-amoand_d | p- | PASS | 1121 | 9 |
| rv64ua-p-amoand_w | p- | PASS | 1117 | 8 |
| rv64ua-p-amomax_d | p- | PASS | 1077 | 9 |
| rv64ua-p-amomax_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amomaxu_d | p- | PASS | 1077 | 8 |
| rv64ua-p-amomaxu_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amomin_d | p- | PASS | 1077 | 9 |
| rv64ua-p-amomin_w | p- | PASS | 1100 | 8 |
| rv64ua-p-amominu_d | p- | PASS | 1077 | 9 |
| rv64ua-p-amominu_w | p- | PASS | 1100 | 9 |
| rv64ua-p-amoor_d | p- | PASS | 1117 | 9 |
| rv64ua-p-amoor_w | p- | PASS | 1117 | 10 |
| rv64ua-p-amoswap_d | p- | PASS | 1121 | 9 |
| rv64ua-p-amoswap_w | p- | PASS | 1117 | 9 |
| rv64ua-p-amoxor_d | p- | PASS | 1125 | 9 |
| rv64ua-p-amoxor_w | p- | PASS | 1129 | 9 |
| rv64ua-p-lrsc | p- | TIMEOUT | - | 304 |
| rv64uc-p-rvc | p- | PASS | 1586 | 11 |
| rv64ud-p-fadd | p- | PASS | 1913 | 14 |
| rv64ud-p-fclass | p- | PASS | 1233 | 10 |
| rv64ud-p-fcmp | p- | PASS | 2231 | 16 |
| rv64ud-p-fcvt | p- | PASS | 1841 | 13 |
| rv64ud-p-fcvt_w | p- | PASS | 3801 | 26 |
| rv64ud-p-fdiv | p- | PASS | 1739 | 13 |
| rv64ud-p-fmadd | p- | PASS | 2070 | 15 |
| rv64ud-p-fmin | p- | PASS | 2541 | 19 |
| rv64ud-p-ldst | p- | PASS | 1172 | 10 |
| rv64ud-p-move | p- | PASS | 2696 | 20 |
| rv64ud-p-recoding | p- | PASS | 1245 | 10 |
| rv64ud-p-structural | p- | PASS | 2030 | 14 |
| rv64uf-p-fadd | p- | PASS | 1913 | 14 |
| rv64uf-p-fclass | p- | PASS | 1217 | 9 |
| rv64uf-p-fcmp | p- | PASS | 2231 | 17 |
| rv64uf-p-fcvt | p- | PASS | 1630 | 13 |
| rv64uf-p-fcvt_w | p- | PASS | 3428 | 25 |
| rv64uf-p-fdiv | p- | PASS | 1663 | 13 |
| rv64uf-p-fmadd | p- | PASS | 2070 | 16 |
| rv64uf-p-fmin | p- | PASS | 2541 | 19 |
| rv64uf-p-ldst | p- | PASS | 1183 | 10 |
| rv64uf-p-move | p- | PASS | 1817 | 14 |
| rv64uf-p-recoding | p- | PASS | 1198 | 9 |
| rv64ui-p-add | p- | PASS | 2453 | 18 |
| rv64ui-p-addi | p- | PASS | 1630 | 13 |
| rv64ui-p-addiw | p- | PASS | 1621 | 13 |
| rv64ui-p-addw | p- | PASS | 2443 | 17 |
| rv64ui-p-and | p- | PASS | 2613 | 19 |
| rv64ui-p-andi | p- | PASS | 1609 | 12 |
| rv64ui-p-auipc | p- | PASS | 1053 | 9 |
| rv64ui-p-beq | p- | PASS | 2427 | 18 |
| rv64ui-p-bge | p- | PASS | 2726 | 19 |
| rv64ui-p-bgeu | p- | PASS | 2956 | 21 |
| rv64ui-p-blt | p- | PASS | 2429 | 18 |
| rv64ui-p-bltu | p- | PASS | 2643 | 19 |
| rv64ui-p-bne | p- | PASS | 2482 | 18 |
| rv64ui-p-fence_i | p- | PASS | 2097 | 15 |
| rv64ui-p-jal | p- | PASS | 1049 | 8 |
| rv64ui-p-jalr | p- | PASS | 1550 | 12 |
| rv64ui-p-lb | p- | PASS | 1671 | 13 |
| rv64ui-p-lbu | p- | PASS | 1671 | 12 |
| rv64ui-p-ld | p- | PASS | 2066 | 15 |
| rv64ui-p-ld_st | p- | PASS | 4467 | 31 |
| rv64ui-p-lh | p- | PASS | 1711 | 14 |
| rv64ui-p-lhu | p- | PASS | 1717 | 12 |
| rv64ui-p-lui | p- | PASS | 1065 | 8 |
| rv64ui-p-lw | p- | PASS | 1731 | 14 |
| rv64ui-p-lwu | p- | PASS | 1797 | 14 |
| rv64ui-p-ma_data | p- | PASS | 7718 | 48 |
| rv64ui-p-or | p- | PASS | 2670 | 19 |
| rv64ui-p-ori | p- | PASS | 1591 | 12 |
| rv64ui-p-sb | p- | PASS | 2292 | 16 |
| rv64ui-p-sd | p- | PASS | 2616 | 19 |
| rv64ui-p-sh | p- | PASS | 2362 | 17 |
| rv64ui-p-simple | p- | PASS | 1003 | 8 |
| rv64ui-p-sll | p- | PASS | 2573 | 18 |
| rv64ui-p-slli | p- | PASS | 1691 | 12 |
| rv64ui-p-slliw | p- | PASS | 1685 | 12 |
| rv64ui-p-sllw | p- | PASS | 2577 | 19 |
| rv64ui-p-slt | p- | PASS | 2431 | 18 |
| rv64ui-p-slti | p- | PASS | 1617 | 13 |
| rv64ui-p-sltiu | p- | PASS | 1617 | 12 |
| rv64ui-p-sltu | p- | PASS | 2469 | 17 |
| rv64ui-p-sra | p- | PASS | 2523 | 18 |
| rv64ui-p-srai | p- | PASS | 1654 | 13 |
| rv64ui-p-sraiw | p- | PASS | 1755 | 12 |
| rv64ui-p-sraw | p- | PASS | 2595 | 19 |
| rv64ui-p-srl | p- | PASS | 2619 | 18 |
| rv64ui-p-srli | p- | PASS | 1715 | 13 |
| rv64ui-p-srliw | p- | PASS | 1703 | 13 |
| rv64ui-p-srlw | p- | PASS | 2583 | 18 |
| rv64ui-p-st_ld | p- | PASS | 1993 | 15 |
| rv64ui-p-sub | p- | PASS | 2437 | 17 |
| rv64ui-p-subw | p- | PASS | 2429 | 17 |
| rv64ui-p-sw | p- | PASS | 2382 | 16 |
| rv64ui-p-xor | p- | PASS | 2664 | 19 |
| rv64ui-p-xori | p- | PASS | 1595 | 13 |
| rv64um-p-div | p- | PASS | 1157 | 10 |
| rv64um-p-divu | p- | PASS | 1167 | 9 |
| rv64um-p-divuw | p- | PASS | 1147 | 10 |
| rv64um-p-divw | p- | PASS | 1139 | 9 |
| rv64um-p-mul | p- | PASS | 2461 | 18 |
| rv64um-p-mulh | p- | PASS | 2471 | 17 |
| rv64um-p-mulhsu | p- | PASS | 2471 | 17 |
| rv64um-p-mulhu | p- | PASS | 2531 | 18 |
| rv64um-p-mulw | p- | PASS | 2329 | 16 |
| rv64um-p-rem | p- | PASS | 1131 | 9 |
| rv64um-p-remu | p- | PASS | 1133 | 9 |
| rv64um-p-remuw | p- | PASS | 1129 | 9 |
| rv64um-p-remw | p- | PASS | 1139 | 9 |
| rv64uzba-p-add_uw | p- | PASS | 2455 | 17 |
| rv64uzba-p-sh1add | p- | PASS | 2461 | 17 |
| rv64uzba-p-sh1add_uw | p- | PASS | 2469 | 17 |
| rv64uzba-p-sh2add | p- | PASS | 2461 | 17 |
| rv64uzba-p-sh2add_uw | p- | PASS | 2469 | 17 |
| rv64uzba-p-sh3add | p- | PASS | 2461 | 17 |
| rv64uzba-p-sh3add_uw | p- | PASS | 2469 | 17 |
| rv64uzba-p-slli_uw | p- | PASS | 1719 | 13 |
| rv64uzbb-p-andn | p- | PASS | 2655 | 18 |
| rv64uzbb-p-clz | p- | PASS | 1497 | 11 |
| rv64uzbb-p-clzw | p- | PASS | 1465 | 11 |
| rv64uzbb-p-cpop | p- | PASS | 1497 | 11 |
| rv64uzbb-p-cpopw | p- | PASS | 1465 | 11 |
| rv64uzbb-p-ctz | p- | PASS | 1497 | 11 |
| rv64uzbb-p-ctzw | p- | PASS | 1467 | 11 |
| rv64uzbb-p-max | p- | PASS | 2441 | 18 |
| rv64uzbb-p-maxu | p- | PASS | 2503 | 18 |
| rv64uzbb-p-min | p- | PASS | 2433 | 17 |
| rv64uzbb-p-minu | p- | PASS | 2481 | 18 |
| rv64uzbb-p-orc_b | p- | PASS | 1539 | 12 |
| rv64uzbb-p-orn | p- | PASS | 2673 | 18 |
| rv64uzbb-p-rev8 | p- | PASS | 1572 | 12 |
| rv64uzbb-p-rol | p- | PASS | 2583 | 18 |
| rv64uzbb-p-rolw | p- | PASS | 2585 | 18 |
| rv64uzbb-p-ror | p- | PASS | 2645 | 18 |
| rv64uzbb-p-rori | p- | PASS | 1712 | 13 |
| rv64uzbb-p-roriw | p- | PASS | 1625 | 12 |
| rv64uzbb-p-rorw | p- | PASS | 2513 | 18 |
| rv64uzbb-p-sext_b | p- | PASS | 1497 | 11 |
| rv64uzbb-p-sext_h | p- | PASS | 1503 | 11 |
| rv64uzbb-p-xnor | p- | PASS | 2671 | 19 |
| rv64uzbb-p-zext_h | p- | PASS | 1509 | 12 |
| rv64uzbc-p-clmul | p- | PASS | 2463 | 17 |
| rv64uzbc-p-clmulh | p- | PASS | 2473 | 18 |
| rv64uzbc-p-clmulr | p- | PASS | 2469 | 17 |
| rv64uzbkb-p-brev8 | p- | PASS | 1537 | 11 |
| rv64uzbkb-p-pack | p- | PASS | 2913 | 21 |
| rv64uzbkb-p-packh | p- | PASS | 2583 | 18 |
| rv64uzbkb-p-packw | p- | PASS | 2443 | 18 |
| rv64uzbkx-p-xperm4 | p- | PASS | 2767 | 20 |
| rv64uzbkx-p-xperm8 | p- | PASS | 3598 | 24 |
| rv64uzbs-p-bclr | p- | PASS | 2796 | 19 |
| rv64uzbs-p-bclri | p- | PASS | 1779 | 13 |
| rv64uzbs-p-bext | p- | PASS | 2661 | 18 |
| rv64uzbs-p-bexti | p- | PASS | 1711 | 12 |
| rv64uzbs-p-binv | p- | PASS | 2631 | 19 |
| rv64uzbs-p-binvi | p- | PASS | 1715 | 13 |
| rv64uzbs-p-bset | p- | PASS | 2800 | 20 |
| rv64uzbs-p-bseti | p- | PASS | 1793 | 14 |
| rv64uzfh-p-fadd | p- | PASS | 1913 | 14 |
| rv64uzfh-p-fclass | p- | PASS | 1218 | 9 |
| rv64uzfh-p-fcmp | p- | PASS | 1565 | 11 |
| rv64uzfh-p-fcvt | p- | PASS | 1803 | 13 |
| rv64uzfh-p-fcvt_w | p- | PASS | 3428 | 24 |
| rv64uzfh-p-fdiv | p- | PASS | 1663 | 12 |
| rv64uzfh-p-fmadd | p- | PASS | 2070 | 15 |
| rv64uzfh-p-fmin | p- | PASS | 2541 | 18 |
| rv64uzfh-p-ldst | p- | PASS | 1194 | 9 |
| rv64uzfh-p-move | p- | PASS | 1812 | 14 |
| rv64uzfh-p-recoding | p- | PASS | 1198 | 10 |
| rv64uziccid-p-ziccid | p- | ERROR | - | 19 |
| rv64uzicond-p-czero_eqz | p- | PASS | 2389 | 12 |
| rv64uzicond-p-czero_nez | p- | PASS | 2377 | 13 |
| rv64ua-v-amoadd_d | v- | PASS | 23918 | 149 |
| rv64ua-v-amoadd_w | v- | PASS | 23957 | 120 |
| rv64ua-v-amoand_d | v- | PASS | 24016 | 153 |
| rv64ua-v-amoand_w | v- | PASS | 24016 | 117 |
| rv64ua-v-amomax_d | v- | PASS | 23870 | 143 |
| rv64ua-v-amomax_w | v- | PASS | 23898 | 143 |
| rv64ua-v-amomaxu_d | v- | PASS | 23870 | 85 |
| rv64ua-v-amomaxu_w | v- | PASS | 23898 | 144 |
| rv64ua-v-amomin_d | v- | PASS | 23870 | 112 |
| rv64ua-v-amomin_w | v- | PASS | 24042 | 148 |
| rv64ua-v-amominu_d | v- | PASS | 23919 | 159 |
| rv64ua-v-amominu_w | v- | PASS | 23947 | 146 |
| rv64ua-v-amoor_d | v- | PASS | 23897 | 75 |
| rv64ua-v-amoor_w | v- | PASS | 23897 | 144 |
| rv64ua-v-amoswap_d | v- | PASS | 24046 | 129 |
| rv64ua-v-amoswap_w | v- | PASS | 24046 | 150 |
| rv64ua-v-amoxor_d | v- | PASS | 23914 | 148 |
| rv64ua-v-amoxor_w | v- | PASS | 23923 | 78 |
| rv64ua-v-lrsc | v- | TIMEOUT | - | 724 |
| rv64uc-v-rvc | v- | PASS | 32877 | 110 |
| rv64ud-v-fadd | v- | PASS | 23593 | 81 |
| rv64ud-v-fclass | v- | PASS | 14320 | 90 |
| rv64ud-v-fcmp | v- | PASS | 23905 | 133 |
| rv64ud-v-fcvt | v- | PASS | 23543 | 152 |
| rv64ud-v-fcvt_w | v- | PASS | 34038 | 187 |
| rv64ud-v-fdiv | v- | PASS | 23419 | 78 |
| rv64ud-v-fmadd | v- | PASS | 23753 | 146 |
| rv64ud-v-fmin | v- | PASS | 24224 | 118 |
| rv64ud-v-ldst | v- | PASS | 23668 | 125 |
| rv64ud-v-move | v- | PASS | 24405 | 116 |
| rv64ud-v-recoding | v- | PASS | 23956 | 145 |
| rv64ud-v-structural | v- | PASS | 14941 | 56 |
| rv64uf-v-fadd | v- | PASS | 23593 | 115 |
| rv64uf-v-fclass | v- | PASS | 14304 | 90 |
| rv64uf-v-fcmp | v- | PASS | 23905 | 114 |
| rv64uf-v-fcvt | v- | PASS | 23326 | 143 |
| rv64uf-v-fcvt_w | v- | PASS | 33684 | 118 |
| rv64uf-v-fdiv | v- | PASS | 23345 | 144 |
| rv64uf-v-fmadd | v- | PASS | 23753 | 145 |
| rv64uf-v-fmin | v- | PASS | 24224 | 115 |
| rv64uf-v-ldst | v- | PASS | 23904 | 157 |
| rv64uf-v-move | v- | PASS | 14997 | 94 |
| rv64uf-v-recoding | v- | PASS | 22884 | 143 |
| rv64ui-v-add | v- | PASS | 15553 | 102 |
| rv64ui-v-addi | v- | PASS | 14854 | 65 |
| rv64ui-v-addiw | v- | PASS | 14847 | 97 |
| rv64ui-v-addw | v- | PASS | 15690 | 101 |
| rv64ui-v-and | v- | FAIL | 15586 | 101 |
| rv64ui-v-andi | v- | PASS | 14820 | 102 |
| rv64ui-v-auipc | v- | PASS | 14097 | 93 |
| rv64ui-v-beq | v- | PASS | 15508 | 103 |
| rv64ui-v-bge | v- | PASS | 15911 | 54 |
| rv64ui-v-bgeu | v- | PASS | 16134 | 102 |
| rv64ui-v-blt | v- | PASS | 15506 | 79 |
| rv64ui-v-bltu | v- | PASS | 15738 | 103 |
| rv64ui-v-bne | v- | PASS | 15680 | 80 |
| rv64ui-v-fence_i | v- | PASS | 24871 | 157 |
| rv64ui-v-jal | v- | PASS | 14091 | 92 |
| rv64ui-v-jalr | v- | PASS | 14588 | 61 |
| rv64ui-v-lb | v- | PASS | 23422 | 148 |
| rv64ui-v-lbu | v- | PASS | 23399 | 147 |
| rv64ui-v-ld | v- | PASS | 24023 | 85 |
| rv64ui-v-ld_st | v- | PASS | 44364 | 149 |
| rv64ui-v-lh | v- | PASS | 23446 | 115 |
| rv64ui-v-lhu | v- | PASS | 23472 | 171 |
| rv64ui-v-lui | v- | PASS | 14177 | 85 |
| rv64ui-v-lw | v- | PASS | 23465 | 150 |
| rv64ui-v-lwu | v- | PASS | 23616 | 153 |
| rv64ui-v-ma_data | v- | PASS | 49924 | 223 |
| rv64ui-v-or | v- | PASS | 15900 | 58 |
| rv64ui-v-ori | v- | PASS | 14785 | 97 |
| rv64ui-v-sb | v- | PASS | 24528 | 154 |
| rv64ui-v-sd | v- | PASS | 33555 | 215 |
| rv64ui-v-sh | v- | PASS | 24679 | 142 |
| rv64ui-v-simple | v- | PASS | 14104 | 71 |
| rv64ui-v-sll | v- | PASS | 24424 | 155 |
| rv64ui-v-slli | v- | PASS | 14899 | 76 |
| rv64ui-v-slliw | v- | PASS | 15004 | 98 |
| rv64ui-v-sllw | v- | PASS | 24300 | 98 |
| rv64ui-v-slt | v- | PASS | 15530 | 102 |
| rv64ui-v-slti | v- | PASS | 14839 | 50 |
| rv64ui-v-sltiu | v- | PASS | 14839 | 75 |
| rv64ui-v-sltu | v- | PASS | 15583 | 99 |
| rv64ui-v-sra | v- | PASS | 15647 | 100 |
| rv64ui-v-srai | v- | PASS | 14761 | 101 |
| rv64ui-v-sraiw | v- | PASS | 15084 | 57 |
| rv64ui-v-sraw | v- | PASS | 24357 | 154 |
| rv64ui-v-srl | v- | PASS | 24439 | 153 |
| rv64ui-v-srli | v- | PASS | 14797 | 94 |
| rv64ui-v-srliw | v- | PASS | 15024 | 76 |
| rv64ui-v-srlw | v- | PASS | 24464 | 174 |
| rv64ui-v-st_ld | v- | PASS | 32952 | 204 |
| rv64ui-v-sub | v- | PASS | 15654 | 78 |
| rv64ui-v-subw | v- | PASS | 15643 | 113 |
| rv64ui-v-sw | v- | PASS | 24831 | 159 |
| rv64ui-v-xor | v- | PASS | 15901 | 94 |
| rv64ui-v-xori | v- | PASS | 14775 | 97 |
| rv64um-v-div | v- | PASS | 14287 | 73 |
| rv64um-v-divu | v- | PASS | 14278 | 106 |
| rv64um-v-divuw | v- | PASS | 14260 | 85 |
| rv64um-v-divw | v- | PASS | 14266 | 94 |
| rv64um-v-mul | v- | PASS | 15677 | 102 |
| rv64um-v-mulh | v- | PASS | 15591 | 68 |
| rv64um-v-mulhsu | v- | PASS | 15577 | 101 |
| rv64um-v-mulhu | v- | PASS | 15744 | 100 |
| rv64um-v-mulw | v- | PASS | 15538 | 57 |
| rv64um-v-rem | v- | PASS | 14268 | 92 |
| rv64um-v-remu | v- | PASS | 14268 | 96 |
| rv64um-v-remuw | v- | PASS | 14256 | 94 |
| rv64um-v-remw | v- | PASS | 14266 | 94 |
| rv64uzba-v-add_uw | v- | PASS | 15565 | 97 |
| rv64uzba-v-sh1add | v- | PASS | 15567 | 97 |
| rv64uzba-v-sh1add_uw | v- | FAIL | 15521 | 75 |
| rv64uzba-v-sh2add | v- | PASS | 15567 | 103 |
| rv64uzba-v-sh2add_uw | v- | FAIL | 15521 | 96 |
| rv64uzba-v-sh3add | v- | PASS | 15567 | 102 |
| rv64uzba-v-sh3add_uw | v- | FAIL | 15521 | 50 |
| rv64uzba-v-slli_uw | v- | PASS | 14909 | 93 |
| rv64uzbb-v-andn | v- | PASS | 15759 | 87 |
| rv64uzbb-v-clz | v- | PASS | 14757 | 95 |
| rv64uzbb-v-clzw | v- | PASS | 14691 | 95 |
| rv64uzbb-v-cpop | v- | PASS | 14757 | 50 |
| rv64uzbb-v-cpopw | v- | PASS | 14691 | 90 |
| rv64uzbb-v-ctz | v- | PASS | 14757 | 73 |
| rv64uzbb-v-ctzw | v- | PASS | 14806 | 93 |
| rv64uzbb-v-max | v- | PASS | 15397 | 74 |
| rv64uzbb-v-maxu | v- | PASS | 15670 | 97 |
| rv64uzbb-v-min | v- | PASS | 15388 | 56 |
| rv64uzbb-v-minu | v- | PASS | 15430 | 95 |
| rv64uzbb-v-orc_b | v- | PASS | 14799 | 91 |
| rv64uzbb-v-orn | v- | PASS | 24467 | 101 |
| rv64uzbb-v-rev8 | v- | PASS | 14729 | 98 |
| rv64uzbb-v-rol | v- | PASS | 24290 | 123 |
| rv64uzbb-v-rolw | v- | PASS | 24241 | 134 |
| rv64uzbb-v-ror | v- | PASS | 24423 | 81 |
| rv64uzbb-v-rori | v- | PASS | 14849 | 93 |
| rv64uzbb-v-roriw | v- | PASS | 14906 | 79 |
| rv64uzbb-v-rorw | v- | PASS | 15695 | 95 |
| rv64uzbb-v-sext_b | v- | PASS | 14757 | 93 |
| rv64uzbb-v-sext_h | v- | PASS | 14767 | 43 |
| rv64uzbb-v-xnor | v- | PASS | 24412 | 128 |
| rv64uzbb-v-zext_h | v- | PASS | 14772 | 74 |
| rv64uzbc-v-clmul | v- | PASS | 15686 | 97 |
| rv64uzbc-v-clmulh | v- | PASS | 15691 | 57 |
| rv64uzbc-v-clmulr | v- | PASS | 15686 | 74 |
| rv64uzbkb-v-brev8 | v- | PASS | 14647 | 54 |
| rv64uzbkb-v-pack | v- | PASS | 24681 | 90 |
| rv64uzbkb-v-packh | v- | PASS | 15730 | 73 |
| rv64uzbkb-v-packw | v- | PASS | 15579 | 70 |
| rv64uzbkx-v-xperm4 | v- | PASS | 24520 | 94 |
| rv64uzbkx-v-xperm8 | v- | PASS | 25393 | 123 |
| rv64uzbs-v-bclr | v- | PASS | 24546 | 121 |
| rv64uzbs-v-bclri | v- | PASS | 14886 | 52 |
| rv64uzbs-v-bext | v- | PASS | 24430 | 112 |
| rv64uzbs-v-bexti | v- | PASS | 14823 | 64 |
| rv64uzbs-v-binv | v- | PASS | 24427 | 110 |
| rv64uzbs-v-binvi | v- | PASS | 14936 | 85 |
| rv64uzbs-v-bset | v- | PASS | 24598 | 56 |
| rv64uzbs-v-bseti | v- | PASS | 14726 | 90 |
| rv64uzfh-v-fadd | v- | PASS | 23593 | 83 |
| rv64uzfh-v-fclass | v- | PASS | 14304 | 78 |
| rv64uzfh-v-fcmp | v- | PASS | 23240 | 79 |
| rv64uzfh-v-fcvt | v- | PASS | 23479 | 88 |
| rv64uzfh-v-fcvt_w | v- | PASS | 33684 | 73 |
| rv64uzfh-v-fdiv | v- | PASS | 23345 | 85 |
| rv64uzfh-v-fmadd | v- | PASS | 23753 | 87 |
| rv64uzfh-v-fmin | v- | PASS | 24224 | 81 |
| rv64uzfh-v-ldst | v- | PASS | 23839 | 88 |
| rv64uzfh-v-move | v- | PASS | 14897 | 86 |
| rv64uzfh-v-recoding | v- | PASS | 22884 | 98 |
| rv64uziccid-v-ziccid | v- | PASS | 163785 | 498 |
| rv64uzicond-v-czero_eqz | v- | PASS | 15317 | 34 |
| rv64uzicond-v-czero_nez | v- | PASS | 15330 | 59 |

</details>

## Performance counters

| Test | Suite | Shard | cycles | predicted_ft | multimember_ft | k_cnt_nonzero | mispred_squash | btb_window_hit | alloc_total | rel_commit | rel_squash | i1_violation | release_accounting_mismatch | assertion_a_violation | fetch_resteer_to_bac | load_committed | lr_committed | store_committed | sc_committed | store_violation_squash | all_squashes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| `hypervisor-p-2-stage_translation` | p- | none | 1374 | 600 | 0 | 0 | 7 | 57 | 56 | 27 | 19 | 0 | 0 | 0 | 2 | 1 | 0 | 13 | 0 | 0 | 27 |
| `hypervisor-p-2-stage_translation_implicit_load_error` | p- | none | 1656 | 714 | 0 | 0 | 8 | 82 | 88 | 34 | 44 | 0 | 0 | 0 | 2 | 0 | 0 | 3 | 0 | 0 | 34 |
| `hypervisor-p-2-stage_translation_implicit_load_error_hs` | p- | none | 1831 | 802 | 0 | 0 | 8 | 85 | 96 | 38 | 48 | 0 | 0 | 0 | 2 | 0 | 0 | 3 | 0 | 0 | 38 |
| `hypervisor-svadu-p-2-stage_translation_implicit_store_error` | p- | none | 1777 | 777 | 0 | 0 | 8 | 86 | 92 | 36 | 46 | 0 | 0 | 0 | 2 | 0 | 0 | 3 | 0 | 0 | 36 |
| `hypervisor-svadu-p-2-stage_translation_implicit_store_error_hs` | p- | none | 1944 | 839 | 0 | 0 | 8 | 89 | 100 | 40 | 50 | 0 | 0 | 0 | 2 | 0 | 0 | 3 | 0 | 0 | 40 |
| `rv64mi-p-breakpoint` | p- | none | 3480 | 1668 | 10 | 0 | 13 | 324 | 368 | 78 | 266 | 0 | 0 | 0 | 12 | 3 | 0 | 2 | 0 | 0 | 78 |
| `rv64mi-p-csr` | p- | none | 3535 | 1674 | 6 | 0 | 14 | 253 | 311 | 80 | 207 | 0 | 0 | 0 | 8 | 1 | 0 | 1 | 0 | 0 | 79 |
| `rv64mi-p-illegal` | p- | none | 4575 | 2556 | 102 | 3 | 44 | 1301 | 1322 | 130 | 1168 | 0 | 0 | 0 | 20 | 0 | 0 | 1 | 0 | 0 | 117 |
| `rv64mi-p-instret_overflow` | p- | none | 1258 | 747 | 0 | 0 | 9 | 342 | 341 | 30 | 287 | 0 | 0 | 0 | 3 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64mi-p-ld-misaligned` | p- | none | 1386 | 603 | 0 | 0 | 8 | 66 | 87 | 25 | 38 | 0 | 0 | 0 | 2 | 8 | 0 | 1 | 0 | 0 | 25 |
| `rv64mi-p-lh-misaligned` | p- | none | 1102 | 516 | 0 | 0 | 8 | 66 | 87 | 25 | 38 | 0 | 0 | 0 | 2 | 2 | 0 | 1 | 0 | 0 | 25 |
| `rv64mi-p-lw-misaligned` | p- | none | 1171 | 544 | 0 | 0 | 8 | 66 | 87 | 25 | 38 | 0 | 0 | 0 | 2 | 4 | 0 | 1 | 0 | 0 | 25 |
| `rv64mi-p-ma_addr` | p- | none | 1540 | 663 | 0 | 0 | 9 | 111 | 124 | 25 | 75 | 0 | 0 | 0 | 3 | 59 | 0 | 12 | 0 | 0 | 25 |
| `rv64mi-p-ma_fetch` | p- | none | 1939 | 1079 | 27 | 0 | 31 | 358 | 341 | 52 | 265 | 0 | 0 | 0 | 17 | 0 | 0 | 1 | 0 | 0 | 48 |
| `rv64mi-p-mcsr` | p- | none | 1342 | 610 | 0 | 0 | 8 | 56 | 60 | 32 | 18 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 32 |
| `rv64mi-p-pmpaddr` | p- | none | 1185 | 626 | 0 | 0 | 10 | 224 | 246 | 28 | 194 | 0 | 0 | 0 | 3 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64mi-p-sbreak` | p- | none | 1312 | 716 | 2 | 0 | 11 | 302 | 301 | 32 | 245 | 0 | 0 | 0 | 6 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64mi-p-scall` | p- | none | 1259 | 658 | 0 | 0 | 10 | 223 | 223 | 30 | 169 | 0 | 0 | 0 | 4 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64mi-p-sd-misaligned` | p- | none | 1436 | 690 | 0 | 0 | 17 | 168 | 146 | 33 | 89 | 0 | 0 | 0 | 8 | 8 | 0 | 9 | 0 | 0 | 26 |
| `rv64mi-p-sh-misaligned` | p- | none | 1109 | 550 | 0 | 0 | 10 | 128 | 130 | 27 | 79 | 0 | 0 | 0 | 3 | 2 | 0 | 3 | 0 | 0 | 25 |
| `rv64mi-p-sw-misaligned` | p- | none | 1150 | 587 | 0 | 0 | 12 | 209 | 171 | 29 | 118 | 0 | 0 | 0 | 4 | 4 | 0 | 5 | 0 | 0 | 25 |
| `rv64mi-p-zicntr` | p- | none | 1439 | 715 | 0 | 0 | 9 | 281 | 288 | 33 | 231 | 0 | 0 | 0 | 3 | 0 | 0 | 1 | 0 | 0 | 33 |
| `rv64mzicbo-p-zero` | p- | none | 1160 | 534 | 0 | 0 | 8 | 76 | 73 | 25 | 38 | 0 | 0 | 0 | 2 | 8 | 0 | 2 | 0 | 0 | 24 |
| `rv64si-p-csr` | p- | none | 2277 | 1042 | 0 | 0 | 7 | 56 | 79 | 51 | 18 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 51 |
| `rv64si-p-dirty` | p- | none | 2337 | 1139 | 6 | 0 | 15 | 335 | 358 | 53 | 281 | 0 | 1 | 0 | 9 | 6 | 0 | 7 | 0 | 0 | 51 |
| `rv64si-p-icache-alias` | p- | none | 2385 | 1303 | 12 | 0 | 15 | 391 | 397 | 60 | 314 | 0 | -1 | 0 | 25 | 0 | 0 | 7 | 0 | 0 | 56 |
| `rv64si-p-ma_fetch` | p- | none | 1374 | 752 | 1 | 0 | 29 | 278 | 261 | 37 | 214 | 0 | 0 | 0 | 10 | 0 | 0 | 1 | 0 | 0 | 34 |
| `rv64si-p-sbreak` | p- | none | 1325 | 690 | 0 | 0 | 9 | 258 | 236 | 32 | 194 | 0 | 0 | 0 | 4 | 0 | 0 | 1 | 0 | 0 | 31 |
| `rv64si-p-scall` | p- | none | 1443 | 760 | 0 | 0 | 9 | 281 | 245 | 35 | 200 | 0 | 0 | 0 | 4 | 0 | 0 | 1 | 0 | 0 | 34 |
| `rv64si-p-wfi` | p- | none | 1173 | 543 | 0 | 0 | 7 | 56 | 56 | 28 | 18 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 28 |
| `rv64ssvnapot-p-napot` | p- | none | 1658 | 763 | 2 | 0 | 9 | 120 | 144 | 35 | 86 | 0 | 0 | 0 | 4 | 0 | 0 | 7 | 0 | 0 | 34 |
| `rv64ua-p-amoadd_d` | p- | none | 1081 | 484 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 0 | 24 |
| `rv64ua-p-amoadd_w` | p- | none | 1120 | 502 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoand_d` | p- | none | 1121 | 501 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoand_w` | p- | none | 1117 | 499 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amomax_d` | p- | none | 1077 | 483 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 3 | 0 | 0 | 24 |
| `rv64ua-p-amomax_w` | p- | none | 1100 | 496 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 3 | 0 | 4 | 0 | 0 | 24 |
| `rv64ua-p-amomaxu_d` | p- | none | 1077 | 483 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 3 | 0 | 0 | 24 |
| `rv64ua-p-amomaxu_w` | p- | none | 1100 | 496 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 3 | 0 | 4 | 0 | 0 | 24 |
| `rv64ua-p-amomin_d` | p- | none | 1077 | 483 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 3 | 0 | 0 | 24 |
| `rv64ua-p-amomin_w` | p- | none | 1100 | 496 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 3 | 0 | 4 | 0 | 0 | 24 |
| `rv64ua-p-amominu_d` | p- | none | 1077 | 483 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 3 | 0 | 0 | 24 |
| `rv64ua-p-amominu_w` | p- | none | 1100 | 496 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 3 | 0 | 4 | 0 | 0 | 24 |
| `rv64ua-p-amoor_d` | p- | none | 1117 | 500 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoor_w` | p- | none | 1117 | 500 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoswap_d` | p- | none | 1121 | 501 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoswap_w` | p- | none | 1117 | 499 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoxor_d` | p- | none | 1125 | 502 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64ua-p-amoxor_w` | p- | none | 1129 | 503 | 0 | 0 | 8 | 54 | 52 | 25 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 2 | 0 | 1 | 25 |
| `rv64uc-p-rvc` | p- | none | 1586 | 719 | 2 | 0 | 35 | 89 | 101 | 37 | 54 | 0 | 0 | 0 | 14 | 9 | 0 | 5 | 0 | 0 | 34 |
| `rv64ud-p-fadd` | p- | none | 1913 | 816 | 0 | 0 | 8 | 54 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 40 | 0 | 1 | 0 | 0 | 36 |
| `rv64ud-p-fclass` | p- | none | 1233 | 561 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 26 |
| `rv64ud-p-fcmp` | p- | none | 2231 | 951 | 0 | 0 | 8 | 54 | 68 | 41 | 17 | 0 | 0 | 0 | 2 | 60 | 0 | 1 | 0 | 0 | 41 |
| `rv64ud-p-fcvt` | p- | none | 1841 | 800 | 0 | 0 | 8 | 54 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 17 | 0 | 1 | 0 | 0 | 36 |
| `rv64ud-p-fcvt_w` | p- | none | 3801 | 1594 | 0 | 0 | 8 | 54 | 87 | 60 | 17 | 0 | 0 | 0 | 2 | 152 | 0 | 1 | 0 | 0 | 60 |
| `rv64ud-p-fdiv` | p- | none | 1739 | 752 | 0 | 0 | 8 | 54 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 32 | 0 | 1 | 0 | 0 | 34 |
| `rv64ud-p-fmadd` | p- | none | 2070 | 881 | 0 | 0 | 8 | 54 | 65 | 38 | 17 | 0 | 0 | 0 | 2 | 48 | 0 | 1 | 0 | 0 | 38 |
| `rv64ud-p-fmin` | p- | none | 2541 | 1059 | 0 | 0 | 8 | 54 | 71 | 44 | 17 | 0 | 0 | 0 | 2 | 72 | 0 | 1 | 0 | 0 | 44 |
| `rv64ud-p-ldst` | p- | none | 1172 | 540 | 0 | 0 | 8 | 55 | 54 | 26 | 18 | 0 | 0 | 0 | 2 | 10 | 0 | 6 | 0 | 0 | 26 |
| `rv64ud-p-move` | p- | none | 2696 | 901 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 26 |
| `rv64ud-p-recoding` | p- | none | 1245 | 556 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 7 | 0 | 2 | 0 | 0 | 26 |
| `rv64ud-p-structural` | p- | none | 2030 | 988 | 0 | 0 | 49 | 113 | 141 | 47 | 84 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 46 |
| `rv64uf-p-fadd` | p- | none | 1913 | 816 | 0 | 0 | 8 | 54 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 40 | 0 | 1 | 0 | 0 | 36 |
| `rv64uf-p-fclass` | p- | none | 1217 | 558 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 26 |
| `rv64uf-p-fcmp` | p- | none | 2231 | 951 | 0 | 0 | 8 | 54 | 68 | 41 | 17 | 0 | 0 | 0 | 2 | 60 | 0 | 1 | 0 | 0 | 41 |
| `rv64uf-p-fcvt` | p- | none | 1630 | 720 | 0 | 0 | 8 | 54 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 8 | 0 | 1 | 0 | 0 | 34 |
| `rv64uf-p-fcvt_w` | p- | none | 3428 | 1444 | 0 | 0 | 8 | 54 | 82 | 55 | 17 | 0 | 0 | 0 | 2 | 132 | 0 | 1 | 0 | 0 | 55 |
| `rv64uf-p-fdiv` | p- | none | 1663 | 727 | 0 | 0 | 8 | 54 | 60 | 33 | 17 | 0 | 0 | 0 | 2 | 28 | 0 | 1 | 0 | 0 | 33 |
| `rv64uf-p-fmadd` | p- | none | 2070 | 881 | 0 | 0 | 8 | 54 | 65 | 38 | 17 | 0 | 0 | 0 | 2 | 48 | 0 | 1 | 0 | 0 | 38 |
| `rv64uf-p-fmin` | p- | none | 2541 | 1059 | 0 | 0 | 8 | 54 | 71 | 44 | 17 | 0 | 0 | 0 | 2 | 72 | 0 | 1 | 0 | 0 | 44 |
| `rv64uf-p-ldst` | p- | none | 1183 | 525 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 4 | 0 | 3 | 0 | 0 | 26 |
| `rv64uf-p-move` | p- | none | 1817 | 783 | 0 | 0 | 8 | 54 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 34 |
| `rv64uf-p-recoding` | p- | none | 1198 | 539 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 1 | 0 | 0 | 26 |
| `rv64ui-p-add` | p- | none | 2453 | 992 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-addi` | p- | none | 1630 | 690 | 0 | 0 | 14 | 60 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-addiw` | p- | none | 1621 | 687 | 0 | 0 | 14 | 57 | 60 | 33 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-addw` | p- | none | 2443 | 990 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-and` | p- | none | 2613 | 1067 | 0 | 0 | 23 | 69 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-andi` | p- | none | 1609 | 681 | 0 | 0 | 14 | 58 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-auipc` | p- | none | 1053 | 515 | 0 | 0 | 10 | 132 | 91 | 26 | 55 | 0 | 0 | 0 | 4 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64ui-p-beq` | p- | none | 2427 | 1070 | 0 | 0 | 34 | 71 | 85 | 58 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 50 |
| `rv64ui-p-bge` | p- | none | 2726 | 1220 | 0 | 0 | 43 | 74 | 94 | 67 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 59 |
| `rv64ui-p-bgeu` | p- | none | 2956 | 1286 | 0 | 0 | 43 | 80 | 98 | 71 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 59 |
| `rv64ui-p-blt` | p- | none | 2429 | 1070 | 0 | 0 | 34 | 71 | 85 | 58 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 50 |
| `rv64ui-p-bltu` | p- | none | 2643 | 1130 | 0 | 1 | 34 | 78 | 90 | 61 | 19 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 50 |
| `rv64ui-p-bne` | p- | none | 2482 | 1097 | 0 | 1 | 36 | 79 | 91 | 63 | 18 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 52 |
| `rv64ui-p-fence_i` | p- | none | 2097 | 890 | 0 | 0 | 22 | 431 | 195 | 130 | 55 | 0 | 0 | 0 | 2 | 2 | 0 | 5 | 0 | 0 | 40 |
| `rv64ui-p-jal` | p- | none | 1049 | 490 | 0 | 0 | 10 | 92 | 91 | 26 | 55 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64ui-p-jalr` | p- | none | 1550 | 746 | 9 | 1 | 26 | 109 | 117 | 38 | 69 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 40 |
| `rv64ui-p-lb` | p- | none | 1671 | 700 | 0 | 0 | 14 | 62 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-lbu` | p- | none | 1671 | 700 | 0 | 0 | 14 | 62 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-ld` | p- | none | 2066 | 798 | 0 | 0 | 14 | 63 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-ld_st` | p- | none | 4467 | 2195 | 0 | 0 | 178 | 124 | 240 | 81 | 149 | 0 | 0 | 0 | 2 | 277 | 0 | 278 | 0 | 0 | 137 |
| `rv64ui-p-lh` | p- | none | 1711 | 712 | 0 | 0 | 14 | 62 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-lhu` | p- | none | 1717 | 708 | 0 | 0 | 14 | 63 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-lui` | p- | none | 1065 | 482 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64ui-p-lw` | p- | none | 1731 | 717 | 0 | 0 | 14 | 63 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-lwu` | p- | none | 1797 | 731 | 0 | 0 | 14 | 65 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 24 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-ma_data` | p- | none | 7718 | 3720 | 16 | 2 | 268 | 146 | 369 | 120 | 242 | 0 | 0 | 0 | 16 | 180 | 0 | 136 | 0 | 0 | 196 |
| `rv64ui-p-or` | p- | none | 2670 | 1070 | 0 | 0 | 23 | 69 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-ori` | p- | none | 1591 | 678 | 0 | 0 | 14 | 60 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sb` | p- | none | 2292 | 981 | 0 | 0 | 29 | 226 | 161 | 57 | 94 | 0 | 0 | 0 | 7 | 34 | 0 | 36 | 0 | 1 | 38 |
| `rv64ui-p-sd` | p- | none | 2616 | 1082 | 0 | 1 | 29 | 170 | 130 | 56 | 64 | 0 | 0 | 0 | 9 | 34 | 0 | 35 | 0 | 1 | 38 |
| `rv64ui-p-sh` | p- | none | 2362 | 1009 | 0 | 0 | 29 | 224 | 166 | 57 | 99 | 0 | 0 | 0 | 8 | 34 | 0 | 36 | 0 | 1 | 38 |
| `rv64ui-p-simple` | p- | none | 1003 | 444 | 0 | 0 | 7 | 54 | 50 | 23 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 23 |
| `rv64ui-p-sll` | p- | none | 2573 | 1028 | 0 | 0 | 23 | 71 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-slli` | p- | none | 1691 | 700 | 0 | 0 | 14 | 60 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-slliw` | p- | none | 1685 | 704 | 0 | 0 | 14 | 60 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sllw` | p- | none | 2577 | 1031 | 0 | 0 | 23 | 71 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-slt` | p- | none | 2431 | 994 | 0 | 0 | 23 | 71 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-slti` | p- | none | 1617 | 683 | 0 | 0 | 14 | 60 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sltiu` | p- | none | 1617 | 683 | 0 | 0 | 14 | 60 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sltu` | p- | none | 2469 | 1000 | 0 | 0 | 23 | 68 | 76 | 49 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-sra` | p- | none | 2523 | 1014 | 0 | 0 | 23 | 71 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-srai` | p- | none | 1654 | 698 | 0 | 0 | 14 | 62 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sraiw` | p- | none | 1755 | 721 | 0 | 0 | 14 | 61 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-sraw` | p- | none | 2595 | 1034 | 0 | 0 | 23 | 71 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-srl` | p- | none | 2619 | 1045 | 0 | 0 | 23 | 73 | 80 | 53 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-srli` | p- | none | 1715 | 710 | 0 | 0 | 14 | 61 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-srliw` | p- | none | 1703 | 705 | 0 | 0 | 14 | 57 | 60 | 33 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64ui-p-srlw` | p- | none | 2583 | 1025 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-st_ld` | p- | none | 1993 | 709 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 70 | 0 | 71 | 0 | 0 | 24 |
| `rv64ui-p-sub` | p- | none | 2437 | 994 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-subw` | p- | none | 2429 | 993 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-sw` | p- | none | 2382 | 1006 | 0 | 1 | 29 | 215 | 158 | 56 | 92 | 0 | 0 | 0 | 7 | 34 | 0 | 35 | 0 | 1 | 38 |
| `rv64ui-p-xor` | p- | none | 2664 | 1068 | 0 | 0 | 23 | 70 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ui-p-xori` | p- | none | 1595 | 681 | 0 | 0 | 14 | 59 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64um-p-div` | p- | none | 1157 | 522 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-divu` | p- | none | 1167 | 525 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-divuw` | p- | none | 1147 | 515 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-divw` | p- | none | 1139 | 513 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-mul` | p- | none | 2461 | 999 | 0 | 0 | 23 | 68 | 76 | 49 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-mulh` | p- | none | 2471 | 1002 | 0 | 0 | 23 | 74 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-mulhsu` | p- | none | 2471 | 1002 | 0 | 0 | 23 | 74 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-mulhu` | p- | none | 2531 | 1017 | 0 | 0 | 23 | 74 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-mulw` | p- | none | 2329 | 966 | 0 | 0 | 23 | 71 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64um-p-rem` | p- | none | 1131 | 513 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-remu` | p- | none | 1133 | 513 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-remuw` | p- | none | 1129 | 512 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64um-p-remw` | p- | none | 1139 | 513 | 0 | 0 | 8 | 54 | 51 | 24 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 24 |
| `rv64uzba-p-add_uw` | p- | none | 2455 | 997 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh1add` | p- | none | 2461 | 1000 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh1add_uw` | p- | none | 2469 | 995 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh2add` | p- | none | 2461 | 1000 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh2add_uw` | p- | none | 2469 | 995 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh3add` | p- | none | 2461 | 1000 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-sh3add_uw` | p- | none | 2469 | 995 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzba-p-slli_uw` | p- | none | 1719 | 711 | 0 | 0 | 14 | 61 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbb-p-andn` | p- | none | 2655 | 1059 | 0 | 0 | 23 | 73 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-clz` | p- | none | 1497 | 634 | 0 | 0 | 11 | 56 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-clzw` | p- | none | 1465 | 624 | 0 | 0 | 11 | 56 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-cpop` | p- | none | 1497 | 634 | 0 | 0 | 11 | 56 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-cpopw` | p- | none | 1465 | 624 | 0 | 0 | 11 | 56 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-ctz` | p- | none | 1497 | 634 | 0 | 0 | 11 | 56 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-ctzw` | p- | none | 1467 | 624 | 0 | 0 | 11 | 57 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-max` | p- | none | 2441 | 993 | 0 | 0 | 23 | 69 | 77 | 50 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-maxu` | p- | none | 2503 | 1010 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-min` | p- | none | 2433 | 992 | 0 | 0 | 23 | 68 | 76 | 49 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-minu` | p- | none | 2481 | 999 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-orc_b` | p- | none | 1539 | 644 | 0 | 0 | 11 | 57 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-orn` | p- | none | 2673 | 1052 | 0 | 0 | 23 | 72 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-rev8` | p- | none | 1572 | 653 | 0 | 0 | 11 | 56 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-rol` | p- | none | 2583 | 1032 | 0 | 0 | 23 | 74 | 80 | 53 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-rolw` | p- | none | 2585 | 1030 | 0 | 0 | 23 | 71 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-ror` | p- | none | 2645 | 1049 | 0 | 0 | 23 | 70 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-rori` | p- | none | 1712 | 707 | 0 | 0 | 14 | 59 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbb-p-roriw` | p- | none | 1625 | 689 | 0 | 0 | 14 | 58 | 60 | 33 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbb-p-rorw` | p- | none | 2513 | 1014 | 0 | 0 | 23 | 71 | 78 | 51 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-sext_b` | p- | none | 1497 | 634 | 0 | 0 | 11 | 56 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-sext_h` | p- | none | 1503 | 633 | 0 | 0 | 11 | 57 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbb-p-xnor` | p- | none | 2671 | 1055 | 0 | 0 | 23 | 70 | 80 | 53 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbb-p-zext_h` | p- | none | 1509 | 638 | 0 | 0 | 11 | 57 | 56 | 29 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbc-p-clmul` | p- | none | 2463 | 1002 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbc-p-clmulh` | p- | none | 2473 | 999 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbc-p-clmulr` | p- | none | 2469 | 1000 | 0 | 0 | 23 | 69 | 77 | 50 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkb-p-brev8` | p- | none | 1537 | 639 | 0 | 0 | 11 | 58 | 57 | 30 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 27 |
| `rv64uzbkb-p-pack` | p- | none | 2913 | 1139 | 0 | 0 | 23 | 71 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkb-p-packh` | p- | none | 2583 | 1049 | 0 | 0 | 23 | 73 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkb-p-packw` | p- | none | 2443 | 998 | 0 | 0 | 23 | 72 | 80 | 53 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkx-p-xperm4` | p- | none | 2767 | 1098 | 0 | 0 | 23 | 73 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbkx-p-xperm8` | p- | none | 3598 | 1327 | 0 | 0 | 23 | 69 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-bclr` | p- | none | 2796 | 1107 | 0 | 0 | 23 | 71 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-bclri` | p- | none | 1779 | 728 | 0 | 0 | 14 | 60 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbs-p-bext` | p- | none | 2661 | 1046 | 0 | 0 | 23 | 73 | 80 | 53 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-bexti` | p- | none | 1711 | 711 | 0 | 0 | 14 | 60 | 62 | 35 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbs-p-binv` | p- | none | 2631 | 1047 | 0 | 0 | 23 | 68 | 77 | 50 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-binvi` | p- | none | 1715 | 709 | 0 | 0 | 14 | 59 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzbs-p-bset` | p- | none | 2800 | 1108 | 0 | 0 | 23 | 69 | 81 | 54 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzbs-p-bseti` | p- | none | 1793 | 727 | 0 | 0 | 14 | 61 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 30 |
| `rv64uzfh-p-fadd` | p- | none | 1913 | 816 | 0 | 0 | 8 | 54 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 40 | 0 | 1 | 0 | 0 | 36 |
| `rv64uzfh-p-fclass` | p- | none | 1218 | 558 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 26 |
| `rv64uzfh-p-fcmp` | p- | none | 1565 | 688 | 0 | 0 | 8 | 54 | 59 | 32 | 17 | 0 | 0 | 0 | 2 | 24 | 0 | 1 | 0 | 0 | 32 |
| `rv64uzfh-p-fcvt` | p- | none | 1803 | 789 | 0 | 0 | 8 | 54 | 63 | 36 | 17 | 0 | 0 | 0 | 2 | 16 | 0 | 1 | 0 | 0 | 36 |
| `rv64uzfh-p-fcvt_w` | p- | none | 3428 | 1444 | 0 | 0 | 8 | 54 | 82 | 55 | 17 | 0 | 0 | 0 | 2 | 132 | 0 | 1 | 0 | 0 | 55 |
| `rv64uzfh-p-fdiv` | p- | none | 1663 | 727 | 0 | 0 | 8 | 54 | 60 | 33 | 17 | 0 | 0 | 0 | 2 | 28 | 0 | 1 | 0 | 0 | 33 |
| `rv64uzfh-p-fmadd` | p- | none | 2070 | 881 | 0 | 0 | 8 | 54 | 65 | 38 | 17 | 0 | 0 | 0 | 2 | 48 | 0 | 1 | 0 | 0 | 38 |
| `rv64uzfh-p-fmin` | p- | none | 2541 | 1059 | 0 | 0 | 8 | 54 | 71 | 44 | 17 | 0 | 0 | 0 | 2 | 72 | 0 | 1 | 0 | 0 | 44 |
| `rv64uzfh-p-ldst` | p- | none | 1194 | 537 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 4 | 0 | 3 | 0 | 0 | 26 |
| `rv64uzfh-p-move` | p- | none | 1812 | 781 | 0 | 0 | 8 | 54 | 61 | 34 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 34 |
| `rv64uzfh-p-recoding` | p- | none | 1198 | 539 | 0 | 0 | 8 | 54 | 53 | 26 | 17 | 0 | 0 | 0 | 2 | 2 | 0 | 1 | 0 | 0 | 26 |
| `rv64uzicond-p-czero_eqz` | p- | none | 2389 | 976 | 0 | 0 | 23 | 73 | 79 | 52 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64uzicond-p-czero_nez` | p- | none | 2377 | 977 | 0 | 0 | 23 | 69 | 77 | 50 | 17 | 0 | 0 | 0 | 2 | 0 | 0 | 1 | 0 | 0 | 39 |
| `rv64ua-v-amoadd_d` | v- | 15/18 | 23918 | 7378 | 240 | 8 | 184 | 6596 | 3654 | 1283 | 2347 | 0 | 0 | 0 | 23 | 2891 | 0 | 1987 | 0 | 0 | 251 |
| `rv64ua-v-amoadd_w` | v- | 16/18 | 23957 | 7398 | 240 | 8 | 184 | 6595 | 3656 | 1284 | 2348 | 0 | 0 | 0 | 23 | 2891 | 0 | 1987 | 0 | 1 | 252 |
| `rv64ua-v-amoand_d` | v- | 17/18 | 24016 | 7451 | 244 | 10 | 188 | 6627 | 3676 | 1286 | 2366 | 0 | 0 | 0 | 23 | 2895 | 0 | 1987 | 0 | 1 | 256 |
| `rv64ua-v-amoand_w` | v- | 18/18 | 24016 | 7448 | 244 | 10 | 188 | 6627 | 3676 | 1286 | 2366 | 0 | 0 | 0 | 23 | 2895 | 0 | 1987 | 0 | 1 | 256 |
| `rv64ua-v-amomax_d` | v- | 1/18 | 23870 | 7343 | 238 | 7 | 182 | 6578 | 3642 | 1282 | 2336 | 0 | 0 | 0 | 23 | 2889 | 0 | 1988 | 0 | 0 | 249 |
| `rv64ua-v-amomax_w` | v- | 4/18 | 23898 | 7362 | 238 | 7 | 182 | 6577 | 3640 | 1282 | 2334 | 0 | 0 | 0 | 23 | 2890 | 0 | 1989 | 0 | 0 | 250 |
| `rv64ua-v-amomaxu_d` | v- | 2/18 | 23870 | 7343 | 238 | 7 | 182 | 6578 | 3642 | 1282 | 2336 | 0 | 0 | 0 | 23 | 2889 | 0 | 1988 | 0 | 0 | 249 |
| `rv64ua-v-amomaxu_w` | v- | 3/18 | 23898 | 7362 | 238 | 7 | 182 | 6577 | 3640 | 1282 | 2334 | 0 | 0 | 0 | 23 | 2890 | 0 | 1989 | 0 | 0 | 250 |
| `rv64ua-v-amomin_d` | v- | 5/18 | 23870 | 7343 | 238 | 7 | 182 | 6578 | 3642 | 1282 | 2336 | 0 | 0 | 0 | 23 | 2889 | 0 | 1988 | 0 | 0 | 249 |
| `rv64ua-v-amomin_w` | v- | 8/18 | 24042 | 7463 | 244 | 10 | 188 | 6631 | 3681 | 1285 | 2372 | 0 | 0 | 0 | 23 | 2896 | 0 | 1989 | 0 | 0 | 256 |
| `rv64ua-v-amominu_d` | v- | 6/18 | 23919 | 7375 | 240 | 7 | 184 | 6594 | 3656 | 1283 | 2349 | 0 | 0 | 0 | 23 | 2891 | 0 | 1988 | 0 | 0 | 251 |
| `rv64ua-v-amominu_w` | v- | 7/18 | 23947 | 7394 | 240 | 7 | 184 | 6593 | 3654 | 1283 | 2347 | 0 | 0 | 0 | 23 | 2892 | 0 | 1989 | 0 | 0 | 252 |
| `rv64ua-v-amoor_d` | v- | 9/18 | 23897 | 7355 | 238 | 7 | 182 | 6579 | 3643 | 1283 | 2336 | 0 | 0 | 0 | 23 | 2889 | 0 | 1987 | 0 | 1 | 250 |
| `rv64ua-v-amoor_w` | v- | 10/18 | 23897 | 7355 | 238 | 7 | 182 | 6579 | 3643 | 1283 | 2336 | 0 | 0 | 0 | 23 | 2889 | 0 | 1987 | 0 | 1 | 250 |
| `rv64ua-v-amoswap_d` | v- | 11/18 | 24046 | 7464 | 244 | 10 | 188 | 6634 | 3686 | 1286 | 2376 | 0 | 0 | 0 | 23 | 2895 | 0 | 1987 | 0 | 1 | 256 |
| `rv64ua-v-amoswap_w` | v- | 12/18 | 24046 | 7461 | 244 | 10 | 188 | 6634 | 3686 | 1286 | 2376 | 0 | 0 | 0 | 23 | 2895 | 0 | 1987 | 0 | 1 | 256 |
| `rv64ua-v-amoxor_d` | v- | 13/18 | 23914 | 7366 | 238 | 7 | 182 | 6578 | 3640 | 1283 | 2333 | 0 | 0 | 0 | 23 | 2889 | 0 | 1987 | 0 | 1 | 250 |
| `rv64ua-v-amoxor_w` | v- | 14/18 | 23923 | 7361 | 238 | 7 | 182 | 6579 | 3641 | 1283 | 2334 | 0 | 0 | 0 | 23 | 2889 | 0 | 1987 | 0 | 1 | 250 |
| `rv64uc-v-rvc` | v- | 14/18 | 32877 | 9839 | 867 | 38 | 255 | 10509 | 4906 | 1987 | 2895 | 0 | 0 | 0 | 39 | 4535 | 0 | 2601 | 0 | 0 | 329 |
| `rv64ud-v-fadd` | v- | 9/18 | 23593 | 7247 | 740 | 13 | 168 | 9041 | 3608 | 1657 | 1927 | 0 | 0 | 0 | 23 | 3395 | 0 | 1433 | 0 | 0 | 237 |
| `rv64ud-v-fclass` | v- | 10/18 | 14320 | 4642 | 165 | 6 | 128 | 5093 | 2280 | 956 | 1300 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64ud-v-fcmp` | v- | 11/18 | 23905 | 7373 | 740 | 13 | 168 | 9040 | 3612 | 1662 | 1926 | 0 | 0 | 0 | 23 | 3415 | 0 | 1433 | 0 | 0 | 242 |
| `rv64ud-v-fcvt` | v- | 12/18 | 23543 | 7242 | 740 | 13 | 169 | 9041 | 3609 | 1657 | 1928 | 0 | 0 | 0 | 23 | 3372 | 0 | 1433 | 0 | 0 | 237 |
| `rv64ud-v-fcvt_w` | v- | 13/18 | 34038 | 10152 | 1312 | 18 | 205 | 12986 | 4941 | 2372 | 2545 | 0 | 0 | 0 | 25 | 5136 | 0 | 2044 | 0 | 0 | 323 |
| `rv64ud-v-fdiv` | v- | 14/18 | 23419 | 7186 | 740 | 13 | 168 | 9041 | 3606 | 1655 | 1927 | 0 | 0 | 0 | 23 | 3387 | 0 | 1433 | 0 | 0 | 235 |
| `rv64ud-v-fmadd` | v- | 15/18 | 23753 | 7305 | 740 | 13 | 168 | 9042 | 3611 | 1659 | 1928 | 0 | 0 | 0 | 23 | 3403 | 0 | 1433 | 0 | 0 | 239 |
| `rv64ud-v-fmin` | v- | 16/18 | 24224 | 7493 | 740 | 13 | 168 | 9041 | 3616 | 1665 | 1927 | 0 | 0 | 0 | 23 | 3427 | 0 | 1433 | 0 | 0 | 245 |
| `rv64ud-v-ldst` | v- | 17/18 | 23668 | 7592 | 274 | 8 | 170 | 6377 | 3673 | 1346 | 2303 | 0 | 0 | 0 | 86 | 2901 | 0 | 1991 | 0 | 0 | 239 |
| `rv64ud-v-move` | v- | 18/18 | 24405 | 7086 | 740 | 13 | 169 | 9042 | 3600 | 1647 | 1929 | 0 | 0 | 0 | 23 | 3355 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ud-v-recoding` | v- | 1/18 | 23956 | 7409 | 248 | 13 | 189 | 6567 | 3588 | 1290 | 2274 | 0 | 0 | 0 | 24 | 2908 | 0 | 1987 | 0 | 0 | 257 |
| `rv64ud-v-structural` | v- | 2/18 | 14941 | 4983 | 465 | 7 | 168 | 5112 | 2303 | 976 | 1303 | 0 | 0 | 0 | 30 | 1726 | 0 | 822 | 0 | 0 | 173 |
| `rv64uf-v-fadd` | v- | 16/18 | 23593 | 7247 | 740 | 13 | 168 | 9041 | 3608 | 1657 | 1927 | 0 | 0 | 0 | 23 | 3395 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uf-v-fclass` | v- | 17/18 | 14304 | 4638 | 165 | 6 | 128 | 5093 | 2280 | 956 | 1300 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64uf-v-fcmp` | v- | 18/18 | 23905 | 7373 | 740 | 13 | 168 | 9040 | 3612 | 1662 | 1926 | 0 | 0 | 0 | 23 | 3415 | 0 | 1433 | 0 | 0 | 242 |
| `rv64uf-v-fcvt` | v- | 1/18 | 23326 | 7153 | 740 | 13 | 168 | 9042 | 3607 | 1655 | 1928 | 0 | 0 | 0 | 23 | 3363 | 0 | 1433 | 0 | 0 | 235 |
| `rv64uf-v-fcvt_w` | v- | 2/18 | 33684 | 10059 | 1312 | 18 | 205 | 12987 | 4938 | 2367 | 2547 | 0 | 0 | 0 | 25 | 5116 | 0 | 2044 | 0 | 0 | 318 |
| `rv64uf-v-fdiv` | v- | 3/18 | 23345 | 7152 | 740 | 13 | 168 | 9043 | 3607 | 1654 | 1929 | 0 | 0 | 0 | 23 | 3383 | 0 | 1433 | 0 | 0 | 234 |
| `rv64uf-v-fmadd` | v- | 4/18 | 23753 | 7305 | 740 | 13 | 168 | 9042 | 3611 | 1659 | 1928 | 0 | 0 | 0 | 23 | 3403 | 0 | 1433 | 0 | 0 | 239 |
| `rv64uf-v-fmin` | v- | 5/18 | 24224 | 7493 | 740 | 13 | 168 | 9041 | 3616 | 1665 | 1927 | 0 | 0 | 0 | 23 | 3427 | 0 | 1433 | 0 | 0 | 245 |
| `rv64uf-v-ldst` | v- | 6/18 | 23904 | 7367 | 245 | 12 | 184 | 6551 | 3572 | 1289 | 2259 | 0 | 0 | 0 | 23 | 2903 | 0 | 1988 | 0 | 0 | 252 |
| `rv64uf-v-move` | v- | 7/18 | 14997 | 5240 | 211 | 6 | 122 | 5015 | 2469 | 1025 | 1420 | 0 | 0 | 0 | 84 | 1726 | 0 | 822 | 0 | 0 | 162 |
| `rv64uf-v-recoding` | v- | 8/18 | 22884 | 6965 | 740 | 13 | 169 | 9041 | 3599 | 1647 | 1928 | 0 | 0 | 0 | 23 | 3357 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ui-v-add` | v- | 1/18 | 15553 | 5055 | 166 | 7 | 144 | 5107 | 2289 | 983 | 1282 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 174 |
| `rv64ui-v-addi` | v- | 2/18 | 14854 | 4842 | 165 | 7 | 134 | 5116 | 2308 | 966 | 1318 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64ui-v-addiw` | v- | 3/18 | 14847 | 4850 | 166 | 7 | 136 | 5119 | 2297 | 966 | 1307 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64ui-v-addw` | v- | 4/18 | 15690 | 5522 | 220 | 9 | 141 | 4852 | 2371 | 1045 | 1302 | 0 | 0 | 0 | 91 | 1726 | 0 | 822 | 0 | 0 | 169 |
| `rv64ui-v-and` | v- | 7/18 | 15586 | 5133 | 260 | 7 | 141 | 5161 | 2363 | 984 | 1355 | 0 | 0 | 0 | 38 | 1726 | 0 | 822 | 0 | 0 | 171 |
| `rv64ui-v-andi` | v- | 8/18 | 14820 | 5207 | 211 | 7 | 128 | 5022 | 2458 | 1026 | 1408 | 0 | 0 | 0 | 85 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64ui-v-auipc` | v- | 12/18 | 14097 | 4558 | 146 | 6 | 130 | 5124 | 2275 | 957 | 1294 | 0 | 0 | 0 | 27 | 1726 | 0 | 822 | 0 | 0 | 155 |
| `rv64ui-v-beq` | v- | 13/18 | 15508 | 5197 | 243 | 8 | 153 | 5141 | 2347 | 992 | 1331 | 0 | 0 | 0 | 33 | 1726 | 0 | 822 | 0 | 0 | 185 |
| `rv64ui-v-bge` | v- | 14/18 | 15911 | 5818 | 213 | 7 | 158 | 5049 | 2501 | 1062 | 1415 | 0 | 0 | 0 | 86 | 1726 | 0 | 822 | 0 | 0 | 189 |
| `rv64ui-v-bgeu` | v- | 15/18 | 16134 | 5802 | 223 | 8 | 158 | 5049 | 2501 | 1062 | 1415 | 0 | 0 | 0 | 85 | 1726 | 0 | 822 | 0 | 0 | 188 |
| `rv64ui-v-blt` | v- | 16/18 | 15506 | 5192 | 243 | 8 | 153 | 5140 | 2344 | 992 | 1328 | 0 | 0 | 0 | 33 | 1726 | 0 | 822 | 0 | 0 | 185 |
| `rv64ui-v-bltu` | v- | 17/18 | 15738 | 5264 | 244 | 6 | 153 | 5144 | 2350 | 995 | 1331 | 0 | 0 | 0 | 33 | 1726 | 0 | 822 | 0 | 0 | 185 |
| `rv64ui-v-bne` | v- | 18/18 | 15680 | 5631 | 212 | 8 | 151 | 5037 | 2500 | 1054 | 1422 | 0 | 0 | 0 | 86 | 1726 | 0 | 822 | 0 | 0 | 182 |
| `rv64ui-v-fence_i` | v- | 17/18 | 24871 | 7770 | 244 | 13 | 201 | 6918 | 3694 | 1392 | 2278 | 0 | 0 | 0 | 19 | 2901 | 0 | 1990 | 0 | 0 | 270 |
| `rv64ui-v-jal` | v- | 1/18 | 14091 | 4548 | 165 | 6 | 130 | 5104 | 2274 | 957 | 1293 | 0 | 0 | 0 | 25 | 1726 | 0 | 822 | 0 | 0 | 155 |
| `rv64ui-v-jalr` | v- | 2/18 | 14588 | 5200 | 216 | 7 | 143 | 5044 | 2501 | 1030 | 1447 | 0 | 0 | 0 | 89 | 1726 | 0 | 822 | 0 | 0 | 170 |
| `rv64ui-v-lb` | v- | 3/18 | 23422 | 7186 | 742 | 13 | 176 | 9079 | 3640 | 1659 | 1957 | 0 | 0 | 0 | 25 | 3379 | 0 | 1433 | 0 | 0 | 233 |
| `rv64ui-v-lbu` | v- | 4/18 | 23399 | 7175 | 742 | 13 | 176 | 9073 | 3631 | 1659 | 1948 | 0 | 0 | 0 | 25 | 3379 | 0 | 1433 | 0 | 0 | 233 |
| `rv64ui-v-ld` | v- | 9/18 | 24023 | 7669 | 788 | 15 | 172 | 9032 | 3833 | 1719 | 2090 | 0 | 0 | 0 | 87 | 3379 | 0 | 1433 | 0 | 0 | 228 |
| `rv64ui-v-ld_st` | v- | 14/18 | 44364 | 14156 | 2242 | 51 | 421 | 13682 | 6264 | 2876 | 3364 | 0 | 0 | 0 | 283 | 6422 | 0 | 3485 | 0 | 0 | 476 |
| `rv64ui-v-lh` | v- | 5/18 | 23446 | 7186 | 743 | 13 | 176 | 9079 | 3643 | 1659 | 1960 | 0 | 0 | 0 | 25 | 3379 | 0 | 1433 | 0 | 0 | 233 |
| `rv64ui-v-lhu` | v- | 6/18 | 23472 | 7225 | 817 | 13 | 176 | 9111 | 3673 | 1660 | 1989 | 0 | 0 | 0 | 36 | 3379 | 0 | 1433 | 0 | 0 | 233 |
| `rv64ui-v-lui` | v- | 11/18 | 14177 | 4578 | 165 | 6 | 127 | 5091 | 2275 | 955 | 1296 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 158 |
| `rv64ui-v-lw` | v- | 7/18 | 23465 | 7195 | 742 | 15 | 176 | 9079 | 3643 | 1659 | 1960 | 0 | 0 | 0 | 25 | 3379 | 0 | 1433 | 0 | 0 | 233 |
| `rv64ui-v-lwu` | v- | 8/18 | 23616 | 7599 | 786 | 13 | 170 | 8998 | 3815 | 1719 | 2072 | 0 | 0 | 0 | 86 | 3379 | 0 | 1433 | 0 | 0 | 227 |
| `rv64ui-v-ma_data` | v- | 18/18 | 49924 | 25271 | 4563 | 20 | 472 | 13432 | 12918 | 4590 | 8304 | 0 | 0 | 0 | 1987 | 6327 | 0 | 3343 | 0 | 0 | 499 |
| `rv64ui-v-or` | v- | 9/18 | 15900 | 5477 | 213 | 7 | 135 | 5034 | 2492 | 1047 | 1421 | 0 | 0 | 0 | 86 | 1726 | 0 | 822 | 0 | 0 | 167 |
| `rv64ui-v-ori` | v- | 10/18 | 14785 | 5199 | 211 | 7 | 129 | 5017 | 2456 | 1027 | 1405 | 0 | 0 | 0 | 85 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64ui-v-sb` | v- | 10/18 | 24528 | 7684 | 610 | 9 | 206 | 6162 | 3379 | 1319 | 2036 | 0 | 0 | 0 | 65 | 2921 | 0 | 2021 | 0 | 1 | 253 |
| `rv64ui-v-sd` | v- | 13/18 | 33555 | 11668 | 2030 | 17 | 250 | 11793 | 5976 | 2197 | 3755 | 0 | 0 | 0 | 289 | 4550 | 0 | 2631 | 0 | 1 | 327 |
| `rv64ui-v-sh` | v- | 11/18 | 24679 | 9012 | 1481 | 7 | 219 | 7952 | 4547 | 1447 | 3076 | 0 | 0 | 0 | 221 | 2921 | 0 | 2021 | 0 | 1 | 266 |
| `rv64ui-v-simple` | v- | 16/18 | 14104 | 4536 | 165 | 6 | 126 | 4748 | 2037 | 954 | 1059 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 157 |
| `rv64ui-v-sll` | v- | 17/18 | 24424 | 7738 | 785 | 13 | 180 | 9000 | 3823 | 1734 | 2065 | 0 | 0 | 0 | 84 | 3355 | 0 | 1433 | 0 | 0 | 237 |
| `rv64ui-v-slli` | v- | 18/18 | 14899 | 4854 | 165 | 6 | 134 | 5121 | 2311 | 967 | 1320 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64ui-v-slliw` | v- | 1/18 | 15004 | 5249 | 211 | 6 | 128 | 5037 | 2484 | 1026 | 1434 | 0 | 0 | 0 | 84 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64ui-v-sllw` | v- | 2/18 | 24300 | 7306 | 740 | 15 | 183 | 9057 | 3624 | 1673 | 1927 | 0 | 0 | 0 | 23 | 3355 | 0 | 1433 | 0 | 0 | 241 |
| `rv64ui-v-slt` | v- | 13/18 | 15530 | 5077 | 166 | 7 | 144 | 5111 | 2298 | 984 | 1290 | 0 | 0 | 0 | 25 | 1726 | 0 | 822 | 0 | 0 | 174 |
| `rv64ui-v-slti` | v- | 14/18 | 14839 | 4848 | 165 | 6 | 134 | 5122 | 2312 | 967 | 1321 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64ui-v-sltiu` | v- | 16/18 | 14839 | 4848 | 165 | 6 | 134 | 5122 | 2312 | 967 | 1321 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64ui-v-sltu` | v- | 15/18 | 15583 | 5086 | 244 | 6 | 142 | 5133 | 2334 | 982 | 1328 | 0 | 0 | 0 | 32 | 1726 | 0 | 822 | 0 | 0 | 174 |
| `rv64ui-v-sra` | v- | 7/18 | 15647 | 5045 | 244 | 6 | 142 | 5133 | 2334 | 983 | 1327 | 0 | 0 | 0 | 32 | 1726 | 0 | 822 | 0 | 0 | 174 |
| `rv64ui-v-srai` | v- | 8/18 | 14761 | 4810 | 241 | 6 | 134 | 5126 | 2320 | 964 | 1332 | 0 | 0 | 0 | 30 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64ui-v-sraiw` | v- | 9/18 | 15084 | 5272 | 211 | 6 | 128 | 5040 | 2485 | 1026 | 1435 | 0 | 0 | 0 | 84 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64ui-v-sraw` | v- | 10/18 | 24357 | 7317 | 740 | 17 | 187 | 9069 | 3641 | 1675 | 1942 | 0 | 0 | 0 | 26 | 3355 | 0 | 1433 | 0 | 0 | 243 |
| `rv64ui-v-srl` | v- | 3/18 | 24439 | 7771 | 786 | 15 | 180 | 9014 | 3841 | 1738 | 2079 | 0 | 0 | 0 | 89 | 3355 | 0 | 1433 | 0 | 0 | 237 |
| `rv64ui-v-srli` | v- | 4/18 | 14797 | 4792 | 165 | 6 | 134 | 5105 | 2292 | 966 | 1302 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64ui-v-srliw` | v- | 5/18 | 15024 | 5257 | 211 | 6 | 128 | 5042 | 2490 | 1027 | 1439 | 0 | 0 | 0 | 84 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64ui-v-srlw` | v- | 6/18 | 24464 | 7748 | 791 | 17 | 184 | 9006 | 3818 | 1736 | 2058 | 0 | 0 | 0 | 87 | 3355 | 0 | 1433 | 0 | 0 | 238 |
| `rv64ui-v-st_ld` | v- | 15/18 | 32952 | 9577 | 885 | 14 | 212 | 10397 | 4811 | 1973 | 2814 | 0 | 0 | 0 | 36 | 4586 | 0 | 2667 | 0 | 0 | 305 |
| `rv64ui-v-sub` | v- | 5/18 | 15654 | 5522 | 224 | 7 | 139 | 4863 | 2386 | 1047 | 1315 | 0 | 0 | 0 | 94 | 1726 | 0 | 822 | 0 | 0 | 168 |
| `rv64ui-v-subw` | v- | 6/18 | 15643 | 5480 | 211 | 6 | 136 | 5034 | 2489 | 1044 | 1421 | 0 | 0 | 0 | 84 | 1726 | 0 | 822 | 0 | 0 | 168 |
| `rv64ui-v-sw` | v- | 12/18 | 24831 | 8068 | 660 | 9 | 202 | 6576 | 3777 | 1377 | 2376 | 0 | 0 | 0 | 107 | 2921 | 0 | 2020 | 0 | 1 | 247 |
| `rv64ui-v-xor` | v- | 11/18 | 15901 | 5498 | 211 | 6 | 135 | 5036 | 2495 | 1047 | 1424 | 0 | 0 | 0 | 86 | 1726 | 0 | 822 | 0 | 0 | 167 |
| `rv64ui-v-xori` | v- | 12/18 | 14775 | 5191 | 210 | 6 | 127 | 5017 | 2467 | 1028 | 1415 | 0 | 0 | 0 | 84 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64um-v-div` | v- | 5/18 | 14287 | 4628 | 165 | 6 | 128 | 5095 | 2283 | 955 | 1304 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64um-v-divu` | v- | 6/18 | 14278 | 4624 | 165 | 6 | 128 | 5092 | 2279 | 955 | 1300 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64um-v-divuw` | v- | 11/18 | 14260 | 4621 | 165 | 6 | 128 | 5092 | 2278 | 955 | 1299 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64um-v-divw` | v- | 10/18 | 14266 | 4617 | 165 | 6 | 128 | 5093 | 2281 | 955 | 1302 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64um-v-mul` | v- | 1/18 | 15677 | 5516 | 218 | 7 | 138 | 5032 | 2481 | 1044 | 1413 | 0 | 0 | 0 | 89 | 1726 | 0 | 822 | 0 | 0 | 167 |
| `rv64um-v-mulh` | v- | 2/18 | 15591 | 5108 | 166 | 7 | 142 | 5113 | 2312 | 986 | 1302 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 174 |
| `rv64um-v-mulhsu` | v- | 3/18 | 15577 | 5100 | 166 | 7 | 142 | 5111 | 2306 | 986 | 1296 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 174 |
| `rv64um-v-mulhu` | v- | 4/18 | 15744 | 5502 | 210 | 14 | 137 | 5027 | 2486 | 1048 | 1414 | 0 | 0 | 0 | 87 | 1726 | 0 | 822 | 0 | 0 | 168 |
| `rv64um-v-mulw` | v- | 9/18 | 15538 | 5487 | 212 | 7 | 138 | 5029 | 2474 | 1043 | 1407 | 0 | 0 | 0 | 85 | 1726 | 0 | 822 | 0 | 0 | 168 |
| `rv64um-v-rem` | v- | 7/18 | 14268 | 4624 | 165 | 6 | 128 | 5095 | 2282 | 955 | 1303 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64um-v-remu` | v- | 8/18 | 14268 | 4618 | 165 | 6 | 128 | 5093 | 2281 | 955 | 1302 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64um-v-remuw` | v- | 13/18 | 14256 | 4616 | 165 | 6 | 128 | 5093 | 2281 | 955 | 1302 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64um-v-remw` | v- | 12/18 | 14266 | 4617 | 165 | 6 | 128 | 5093 | 2281 | 955 | 1302 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 159 |
| `rv64uzba-v-add_uw` | v- | 3/18 | 15565 | 5249 | 280 | 6 | 143 | 5115 | 2294 | 982 | 1290 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 176 |
| `rv64uzba-v-sh1add` | v- | 4/18 | 15567 | 5239 | 278 | 6 | 143 | 5115 | 2293 | 983 | 1288 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 176 |
| `rv64uzba-v-sh1add_uw` | v- | 5/18 | 15521 | 5236 | 55 | 7 | 143 | 5120 | 2296 | 982 | 1292 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 175 |
| `rv64uzba-v-sh2add` | v- | 6/18 | 15567 | 5239 | 278 | 6 | 143 | 5115 | 2293 | 983 | 1288 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 176 |
| `rv64uzba-v-sh2add_uw` | v- | 7/18 | 15521 | 5236 | 55 | 7 | 143 | 5120 | 2296 | 982 | 1292 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 175 |
| `rv64uzba-v-sh3add` | v- | 8/18 | 15567 | 5239 | 278 | 6 | 143 | 5115 | 2293 | 983 | 1288 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 176 |
| `rv64uzba-v-sh3add_uw` | v- | 9/18 | 15521 | 5236 | 55 | 7 | 143 | 5120 | 2296 | 982 | 1292 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 175 |
| `rv64uzba-v-slli_uw` | v- | 10/18 | 14909 | 5036 | 54 | 6 | 135 | 5124 | 2299 | 966 | 1311 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 167 |
| `rv64uzbb-v-andn` | v- | 11/18 | 15759 | 5119 | 227 | 7 | 144 | 4866 | 2302 | 986 | 1292 | 0 | 0 | 0 | 31 | 1726 | 0 | 822 | 0 | 0 | 175 |
| `rv64uzbb-v-clz` | v- | 12/18 | 14757 | 4835 | 225 | 13 | 132 | 4851 | 2289 | 962 | 1303 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbb-v-clzw` | v- | 13/18 | 14691 | 4813 | 157 | 7 | 133 | 4840 | 2267 | 961 | 1282 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 163 |
| `rv64uzbb-v-cpop` | v- | 14/18 | 14757 | 4835 | 225 | 13 | 132 | 4851 | 2289 | 962 | 1303 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbb-v-cpopw` | v- | 15/18 | 14691 | 4813 | 157 | 7 | 133 | 4840 | 2267 | 961 | 1282 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 163 |
| `rv64uzbb-v-ctz` | v- | 16/18 | 14757 | 4835 | 225 | 13 | 132 | 4851 | 2289 | 962 | 1303 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbb-v-ctzw` | v- | 17/18 | 14806 | 4875 | 157 | 9 | 136 | 4857 | 2294 | 963 | 1307 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 166 |
| `rv64uzbb-v-max` | v- | 18/18 | 15397 | 5042 | 234 | 13 | 142 | 4584 | 2099 | 982 | 1093 | 0 | 0 | 0 | 28 | 1726 | 0 | 822 | 0 | 0 | 172 |
| `rv64uzbb-v-maxu` | v- | 1/18 | 15670 | 5112 | 157 | 9 | 145 | 4857 | 2304 | 986 | 1294 | 0 | 0 | 0 | 24 | 1726 | 0 | 822 | 0 | 0 | 177 |
| `rv64uzbb-v-min` | v- | 2/18 | 15388 | 5043 | 232 | 13 | 142 | 4776 | 2222 | 984 | 1214 | 0 | 0 | 0 | 26 | 1726 | 0 | 822 | 0 | 0 | 172 |
| `rv64uzbb-v-minu` | v- | 3/18 | 15430 | 5001 | 225 | 13 | 141 | 4775 | 2212 | 984 | 1204 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 172 |
| `rv64uzbb-v-orc_b` | v- | 4/18 | 14799 | 4834 | 156 | 6 | 132 | 4848 | 2284 | 961 | 1299 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbb-v-orn` | v- | 5/18 | 24467 | 7475 | 751 | 13 | 188 | 8350 | 3360 | 1681 | 1655 | 0 | 0 | 0 | 48 | 3355 | 0 | 1433 | 0 | 0 | 245 |
| `rv64uzbb-v-rev8` | v- | 6/18 | 14729 | 4782 | 157 | 6 | 132 | 4835 | 2272 | 961 | 1287 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbb-v-rol` | v- | 7/18 | 24290 | 7328 | 804 | 23 | 186 | 8763 | 3580 | 1676 | 1880 | 0 | 0 | 0 | 26 | 3355 | 0 | 1433 | 0 | 0 | 243 |
| `rv64uzbb-v-rolw` | v- | 8/18 | 24241 | 7313 | 808 | 21 | 184 | 8759 | 3574 | 1675 | 1875 | 0 | 0 | 0 | 25 | 3355 | 0 | 1433 | 0 | 0 | 242 |
| `rv64uzbb-v-ror` | v- | 9/18 | 24423 | 7386 | 738 | 15 | 189 | 8826 | 3639 | 1675 | 1940 | 0 | 0 | 0 | 24 | 3355 | 0 | 1433 | 0 | 0 | 246 |
| `rv64uzbb-v-rori` | v- | 10/18 | 14849 | 4850 | 226 | 13 | 135 | 4847 | 2286 | 967 | 1295 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 167 |
| `rv64uzbb-v-roriw` | v- | 11/18 | 14906 | 4923 | 157 | 9 | 137 | 4866 | 2306 | 969 | 1313 | 0 | 0 | 0 | 24 | 1726 | 0 | 822 | 0 | 0 | 168 |
| `rv64uzbb-v-rorw` | v- | 12/18 | 15695 | 5094 | 226 | 13 | 144 | 4854 | 2299 | 984 | 1291 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 177 |
| `rv64uzbb-v-sext_b` | v- | 13/18 | 14757 | 4835 | 225 | 13 | 132 | 4851 | 2289 | 962 | 1303 | 0 | 0 | 0 | 22 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbb-v-sext_h` | v- | 14/18 | 14767 | 4873 | 226 | 6 | 132 | 4880 | 2315 | 962 | 1329 | 0 | 0 | 0 | 30 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbb-v-xnor` | v- | 15/18 | 24412 | 7418 | 730 | 13 | 186 | 8820 | 3629 | 1677 | 1928 | 0 | 0 | 0 | 23 | 3355 | 0 | 1433 | 0 | 0 | 244 |
| `rv64uzbb-v-zext_h` | v- | 16/18 | 14772 | 4874 | 226 | 6 | 132 | 4877 | 2314 | 961 | 1329 | 0 | 0 | 0 | 30 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbc-v-clmul` | v- | 17/18 | 15686 | 5531 | 223 | 7 | 138 | 4863 | 2382 | 1047 | 1311 | 0 | 0 | 0 | 94 | 1726 | 0 | 822 | 0 | 0 | 167 |
| `rv64uzbc-v-clmulh` | v- | 18/18 | 15691 | 5494 | 212 | 6 | 135 | 5035 | 2488 | 1045 | 1419 | 0 | 0 | 0 | 86 | 1726 | 0 | 822 | 0 | 0 | 167 |
| `rv64uzbc-v-clmulr` | v- | 1/18 | 15686 | 5515 | 219 | 7 | 138 | 4846 | 2364 | 1042 | 1298 | 0 | 0 | 0 | 91 | 1726 | 0 | 822 | 0 | 0 | 167 |
| `rv64uzbkb-v-brev8` | v- | 2/18 | 14647 | 4879 | 239 | 7 | 132 | 4871 | 2289 | 961 | 1304 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbkb-v-pack` | v- | 3/18 | 24681 | 7661 | 862 | 12 | 185 | 8957 | 3745 | 1681 | 2040 | 0 | 0 | 0 | 42 | 3355 | 0 | 1433 | 0 | 0 | 241 |
| `rv64uzbkb-v-packh` | v- | 4/18 | 15730 | 5291 | 266 | 19 | 143 | 4909 | 2327 | 987 | 1316 | 0 | 0 | 0 | 25 | 1726 | 0 | 822 | 0 | 0 | 175 |
| `rv64uzbkb-v-packw` | v- | 5/18 | 15579 | 5270 | 331 | 13 | 143 | 4887 | 2317 | 986 | 1307 | 0 | 0 | 0 | 24 | 1726 | 0 | 822 | 0 | 0 | 176 |
| `rv64uzbkx-v-xperm4` | v- | 6/18 | 24520 | 7440 | 844 | 15 | 189 | 9117 | 3678 | 1677 | 1977 | 0 | 0 | 0 | 38 | 3355 | 0 | 1433 | 0 | 0 | 242 |
| `rv64uzbkx-v-xperm8` | v- | 7/18 | 25393 | 7714 | 846 | 13 | 188 | 8600 | 3364 | 1680 | 1660 | 0 | 0 | 0 | 55 | 3355 | 0 | 1433 | 0 | 0 | 243 |
| `rv64uzbs-v-bclr` | v- | 8/18 | 24546 | 7483 | 854 | 13 | 184 | 8865 | 3662 | 1674 | 1964 | 0 | 0 | 0 | 29 | 3355 | 0 | 1433 | 0 | 0 | 241 |
| `rv64uzbs-v-bclri` | v- | 9/18 | 14886 | 4892 | 178 | 6 | 133 | 4854 | 2291 | 966 | 1301 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 164 |
| `rv64uzbs-v-bext` | v- | 10/18 | 24430 | 7662 | 860 | 15 | 185 | 8949 | 3753 | 1676 | 2053 | 0 | 0 | 0 | 61 | 3355 | 0 | 1433 | 0 | 0 | 242 |
| `rv64uzbs-v-bexti` | v- | 11/18 | 14823 | 4886 | 157 | 6 | 134 | 4854 | 2290 | 966 | 1300 | 0 | 0 | 0 | 19 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64uzbs-v-binv` | v- | 12/18 | 24427 | 7694 | 853 | 13 | 185 | 8961 | 3769 | 1676 | 2069 | 0 | 0 | 0 | 63 | 3355 | 0 | 1433 | 0 | 0 | 243 |
| `rv64uzbs-v-binvi` | v- | 13/18 | 14936 | 4987 | 227 | 6 | 134 | 4895 | 2327 | 964 | 1339 | 0 | 0 | 0 | 29 | 1726 | 0 | 822 | 0 | 0 | 165 |
| `rv64uzbs-v-bset` | v- | 14/18 | 24598 | 7653 | 781 | 13 | 185 | 8941 | 3752 | 1676 | 2052 | 0 | 0 | 0 | 50 | 3355 | 0 | 1433 | 0 | 0 | 242 |
| `rv64uzbs-v-bseti` | v- | 15/18 | 14726 | 4832 | 224 | 13 | 129 | 4802 | 2237 | 965 | 1248 | 0 | 0 | 0 | 26 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64uzfh-v-fadd` | v- | 16/18 | 23593 | 7247 | 740 | 13 | 168 | 9041 | 3608 | 1657 | 1927 | 0 | 0 | 0 | 23 | 3395 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uzfh-v-fclass` | v- | 17/18 | 14304 | 4638 | 165 | 6 | 128 | 5093 | 2280 | 956 | 1300 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 160 |
| `rv64uzfh-v-fcmp` | v- | 18/18 | 23240 | 7115 | 740 | 13 | 168 | 9040 | 3603 | 1653 | 1926 | 0 | 0 | 0 | 23 | 3379 | 0 | 1433 | 0 | 0 | 233 |
| `rv64uzfh-v-fcvt` | v- | 1/18 | 23479 | 7213 | 741 | 15 | 170 | 9036 | 3593 | 1657 | 1912 | 0 | 0 | 0 | 24 | 3371 | 0 | 1433 | 0 | 0 | 237 |
| `rv64uzfh-v-fcvt_w` | v- | 2/18 | 33684 | 10059 | 1312 | 18 | 205 | 12987 | 4938 | 2367 | 2547 | 0 | 0 | 0 | 25 | 5116 | 0 | 2044 | 0 | 0 | 318 |
| `rv64uzfh-v-fdiv` | v- | 3/18 | 23345 | 7152 | 740 | 13 | 168 | 9043 | 3607 | 1654 | 1929 | 0 | 0 | 0 | 23 | 3383 | 0 | 1433 | 0 | 0 | 234 |
| `rv64uzfh-v-fmadd` | v- | 4/18 | 23753 | 7305 | 740 | 13 | 168 | 9042 | 3611 | 1659 | 1928 | 0 | 0 | 0 | 23 | 3403 | 0 | 1433 | 0 | 0 | 239 |
| `rv64uzfh-v-fmin` | v- | 5/18 | 24224 | 7493 | 740 | 13 | 168 | 9041 | 3616 | 1665 | 1927 | 0 | 0 | 0 | 23 | 3427 | 0 | 1433 | 0 | 0 | 245 |
| `rv64uzfh-v-ldst` | v- | 6/18 | 23839 | 7347 | 245 | 12 | 184 | 6537 | 3560 | 1289 | 2247 | 0 | 0 | 0 | 23 | 2903 | 0 | 1988 | 0 | 0 | 253 |
| `rv64uzfh-v-move` | v- | 7/18 | 14897 | 4827 | 165 | 6 | 128 | 5094 | 2289 | 964 | 1301 | 0 | 0 | 0 | 21 | 1726 | 0 | 822 | 0 | 0 | 168 |
| `rv64uzfh-v-recoding` | v- | 8/18 | 22884 | 6965 | 740 | 13 | 169 | 9041 | 3599 | 1647 | 1928 | 0 | 0 | 0 | 23 | 3357 | 0 | 1433 | 0 | 0 | 227 |
| `rv64uziccid-v-ziccid` | v- | 11/18 | 163785 | 44475 | 10619 | 79 | 1085 | 69035 | 23807 | 12960 | 10823 | 0 | 0 | 0 | 272 | 29013 | 0 | 11907 | 0 | 0 | 1339 |
| `rv64uzicond-v-czero_eqz` | v- | 9/18 | 15317 | 5109 | 222 | 12 | 138 | 4792 | 2214 | 981 | 1209 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 170 |
| `rv64uzicond-v-czero_nez` | v- | 10/18 | 15330 | 5120 | 221 | 12 | 138 | 4796 | 2217 | 983 | 1210 | 0 | 0 | 0 | 23 | 1726 | 0 | 822 | 0 | 0 | 170 |
