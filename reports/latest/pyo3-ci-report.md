# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 13 of 4184 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#45311573966](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/45311573966) |
| Commit | `8d9e547b31` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1795487179, 1795487205, 1795487234, 1795487239, 1795487248, 1795487250, 1795487252, 1795487259, 1795487260, 1795487335, 1795487338, 1795487362, 1795487368, 1795487377, 1795487379, 1795487399, 1795487404, 1795487405, 1795487415, 1795487474, 1795487476, 1795487483, 1795487500, 1795487517, 1795487526, 1795487552, 1795487558, 1795487566, 1795487569, 1795487579, 1795487588, 1795487601, 1795487644, 1795487666, 1795487762, 1795487886, 1795487905 |
| Testbench | default |
| Generated | 2026-11-24 02:46 UTC |

## Suites

| Suite | Shard | TB | PASS | FAIL | TIMEOUT | ERROR | MISSING | XFAIL-NOTRUN | Total | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| block-BACV2 | none | default | 110 | 0 | 0+0 | 0 | 0 | 0 | 110 | PASS |
| block-BPredUnitV2 | none | default | 695 | 0 | 0+0 | 0 | 0 | 0 | 695 | PASS |
| block-CSRFile | none | default | 35 | 0 | 0+0 | 0 | 0 | 0 | 35 | PASS |
| block-CacheCtrl | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-Commit | none | default | 87 | 0 | 0+0 | 0 | 0 | 0 | 87 | PASS |
| block-DTLBProbe | none | default | 32 | 0 | 0+0 | 0 | 0 | 0 | 32 | PASS |
| block-Decode | none | default | 126 | 0 | 0+0 | 0 | 0 | 0 | 126 | PASS |
| block-Dispatch | none | default | 50 | 0 | 0+0 | 0 | 0 | 0 | 50 | PASS |
| block-FTQ | none | default | 159 | 0 | 0+0 | 0 | 0 | 0 | 159 | PASS |
| block-FUPool | none | default | 63 | 0 | 0+0 | 0 | 0 | 0 | 63 | PASS |
| block-Fetch | none | default | 272 | 0 | 0+0 | 0 | 0 | 0 | 272 | PASS |
| block-FrontEnd | none | default | 21 | 0 | 0+0 | 0 | 0 | 0 | 21 | PASS |
| block-ICache | none | default | 63 | 0 | 0+0 | 0 | 0 | 0 | 63 | PASS |
| block-ICacheV2 | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-IEW | none | default | 110 | 0 | 0+0 | 0 | 0 | 0 | 110 | PASS |
| block-IQ | none | default | 132 | 0 | 0+0 | 0 | 0 | 0 | 132 | PASS |
| block-ITLB | none | default | 19 | 0 | 0+0 | 0 | 0 | 0 | 19 | PASS |
| block-L1DCache | none | default | 73 | 0 | 0+0 | 0 | 0 | 0 | 73 | PASS |
| block-LQCore | none | default | 131 | 0 | 0+0 | 0 | 0 | 0 | 131 | PASS |
| block-LSQParent | none | default | 272 | 0 | 0+0 | 0 | 0 | 0 | 272 | PASS |
| block-LSQv2 | none | default | 6 | 0 | 0+0 | 0 | 0 | 0 | 6 | PASS |
| block-MMU | none | default | 105 | 0 | 0+0 | 0 | 0 | 0 | 105 | PASS |
| block-O3Control | none | default | 45 | 0 | 0+0 | 0 | 0 | 0 | 45 | PASS |
| block-PL2 | none | default | 60 | 0 | 0+0 | 0 | 0 | 0 | 60 | PASS |
| block-PhysRegFile | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-ROB | none | default | 59 | 0 | 0+0 | 0 | 0 | 0 | 59 | PASS |
| block-ReadOperand | none | default | 43 | 0 | 0+0 | 0 | 0 | 0 | 43 | PASS |
| block-ReadOperandInt | none | default | 14 | 0 | 0+0 | 0 | 0 | 0 | 14 | PASS |
| block-ReadOperandMem | none | default | 6 | 0 | 0+0 | 0 | 0 | 0 | 6 | PASS |
| block-Rename | none | default | 96 | 0 | 0+0 | 0 | 0 | 0 | 96 | PASS |
| block-SQStore | none | default | 119 | 0 | 0+0 | 0 | 0 | 0 | 119 | PASS |
| block-Scoreboard | none | default | 54 | 0 | 0+0 | 0 | 0 | 0 | 54 | PASS |
| block-StorageManager | none | default | 33 | 0 | 0+0 | 0 | 0 | 0 | 33 | PASS |
| block-StoreSet | none | default | 22 | 0 | 0+0 | 0 | 0 | 0 | 22 | PASS |
| block-Testbench | none | default | 137 | 0 | 0+0 | 0 | 0 | 0 | 137 | PASS |
| block-TlbiController | none | default | 11 | 0 | 0+0 | 0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | default | 96 | 0 | 0+0 | 0 | 0 | 0 | 96 | PASS |
| cosim-p | none | default | 185 | 13 | 0+0 | 0 | 0 | 0 | 198 | FAIL |
| cosim-v | 1/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 10/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 11/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| cosim-v | 12/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| cosim-v | 13/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| cosim-v | 14/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| cosim-v | 15/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| cosim-v | 16/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| cosim-v | 17/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| cosim-v | 18/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| cosim-v | 2/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 3/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 4/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 5/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 6/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 7/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 8/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| cosim-v | 9/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| p- | none | default | 204 | 0 | 0+0 | 0 | 0 | 0 | 204 | PASS |
| v- | 1/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 10/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 11/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 12/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| v- | 13/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| v- | 14/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| v- | 15/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| v- | 16/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| v- | 17/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| v- | 18/18 | default | 9 | 0 | 0+0 | 0 | 0 | 0 | 9 | PASS |
| v- | 2/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 3/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 4/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 5/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 6/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 8/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| **all** |  |  | 4171 | 13 | 0+0 | 0 | 0 | 0 | 4184 | FAIL |

## Failures

| Test | Suite | TB | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|---|
| `rv64mi-p-breakpoint` | cosim-p | default | FAIL | - | - | 6s | 810639445 | (6s): rv64mi-p-breakpoint: MISMATCH at commit 95 pc=0x800001f0 field=absorbed-record-not-NOP | [1] absorbed-record-not-N... |
| `rv64mi-p-csr` | cosim-p | default | FAIL | - | - | 8s | 489043872 | (8s): rv64mi-p-csr: MISMATCH at commit 167 pc=0x80000328 field=x10 | [1] x10: CL 0x800000000014112d | Spike 0x8000000000... |
| `rv64mi-p-illegal` | cosim-p | default | FAIL | - | - | 6s | 507493854 | (6s): rv64mi-p-illegal: MISMATCH at commit 111 pc=0x800001d0 field=csr344 | [1] csr344: CL 0x2 | Spike 0x82   (CL source... |
| `rv64mi-p-ma_fetch` | cosim-p | default | FAIL | - | - | 5s | 497823772 | (5s): rv64mi-p-ma_fetch: MISMATCH at commit 108 pc=0x8000023c field=csr301 | [1] csr301: CL 0x800000000014112d | Spike 0... |
| `rv64mi-p-mcsr` | cosim-p | default | FAIL | - | - | 4s | 728930165 | (4s): rv64mi-p-mcsr: MISMATCH at commit 77 pc=0x800001a0 field=x10 | [1] x10: CL 0x800000000014112d | Spike 0x8000000000... |
| `rv64mi-p-pmpaddr` | cosim-p | default | FAIL | - | - | 5s | 756679231 | (5s): rv64mi-p-pmpaddr: MISMATCH at commit 79 pc=0x800001ac field=csr3b0 | [1] csr3b0: CL 0xffffffffffffffff | Spike 0x3... |
| `rv64mi-p-scall` | cosim-p | default | FAIL | - | - | 5s | 347724092 | (5s): rv64mi-p-scall: MISMATCH at commit 100 pc=0x0 field=store-stream: unmatched tail | [1] store-stream: unmatched tai... |
| `rv64si-p-csr` | cosim-p | default | FAIL | - | - | 4s | 467146429 | (4s): rv64si-p-csr: MISMATCH at commit 71 pc=0x80000178 field=csr302 | [1] csr302: CL 0xb109 | Spike 0xb108   (CL source... |
| `rv64si-p-icache-alias` | cosim-p | default | FAIL | - | - | 10s | 671894537 | (10s): rv64si-p-icache-alias: MISMATCH at commit 232 pc=0x0 field=store-stream: unmatched tail | [1] store-stream: unmat... |
| `rv64si-p-ma_fetch` | cosim-p | default | FAIL | - | - | 4s | 499737242 | (4s): rv64si-p-ma_fetch: MISMATCH at commit 71 pc=0x80000178 field=csr302 | [1] csr302: CL 0xb109 | Spike 0xb108   (CL s... |
| `rv64si-p-sbreak` | cosim-p | default | FAIL | - | - | 4s | 907244591 | (4s): rv64si-p-sbreak: MISMATCH at commit 71 pc=0x80000178 field=csr302 | [1] csr302: CL 0xb109 | Spike 0xb108   (CL sou... |
| `rv64si-p-scall` | cosim-p | default | FAIL | - | - | 4s | 917697064 | (4s): rv64si-p-scall: MISMATCH at commit 71 pc=0x80000178 field=csr302 | [1] csr302: CL 0xb109 | Spike 0xb108   (CL sour... |
| `rv64si-p-wfi` | cosim-p | default | FAIL | - | - | 5s | 456055710 | (5s): rv64si-p-wfi: MISMATCH at commit 79 pc=0x800001a8 field=csr104 | [1] csr104: CL no write, committed=0x0 | Spike wr... |

## All 4184 results

<details>
<summary>Full per-test table</summary>

| Test | Suite | TB | Status | cycles | wall |
|---|---|---|---|---|---|
| test_bac_v2_btb_flush::test_a_non_serialize_squash_does_not_flush | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_btb_flush::test_one_flush_pulse_across_a_multi_cycle_level | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2CommitEventSurvivesCommitSquash::test_a_commit_on_a_squash_cycle_still_reaches_the_bpu | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2CommitEventSurvivesCommitSquash::test_an_unknown_bb_idx_on_a_squash_cycle_dispatches_nothing | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2CommitEventSurvivesCommitSquash::test_the_squash_itself_still_issues_on_that_cycle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_clear_states_flushes_the_ftq | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_clear_states_sets_running_at_committed_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_default_parameters_match_spec_9 | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_dut_constructs_its_own_bpu_and_ftq_children | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_initial_status_is_idle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2Construction::test_reset_signal_returns_the_thread_to_idle_at_the_initial_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_a_rejected_predict_emits_no_ft_and_holds_bacpc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_a_retry_after_a_reject_succeeds_when_a_pool_frees | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_branch_less_ft_ends_at_the_window_edge_and_is_not_a_bb_end | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_ft_is_exactly_one_per_cycle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_ft_never_crosses_a_window | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_terminal_ft_ends_exclusive_at_the_terminal | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_the_last_slot_of_a_window_and_the_first_of_the_next | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_the_retry_re_reads_the_window | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_the_terminal_slot_alone_fixes_the_ft_end | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2FTFormation::test_window_edge_ft_for_an_all_not_taken_member_set | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2GenerationEntryTest::test_ftq_full_at_entry_emits_no_ft_and_holds_bacpc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2GenerationEntryTest::test_ftqfull_at_entry_is_latched_even_without_a_tick_req | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_bacpc_is_advanced_only_after_the_insert | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_insert_precedes_the_ftqfull_latch | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_post_insert_fullness_does_not_lose_the_ft | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_predict_is_called_even_for_a_branch_less_ft | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_prediction_accepted_is_always_inserted | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2InsertOrder::test_window_read_precedes_the_predict_call | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2LookaheadPC::test_a_rejected_predict_advances_neither_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2LookaheadPC::test_a_squash_restores_the_lookahead_to_the_committed_front | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2LookaheadPC::test_an_accepted_predict_advances_both_pcs_to_the_same_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2LookaheadPC::test_clear_states_restores_the_lookahead_to_the_committed_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2LookaheadPC::test_generation_reads_the_lookahead_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2LookaheadPC::test_the_one_cycle_parity_check_raises_when_only_bacpc_moves | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2LookaheadPC::test_the_reset_mirror_includes_the_lookahead_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2RetryNeverDrop::test_a_squash_under_backpressure_is_not_discarded | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_members_below_start_pc_are_pre_filtered_out | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_records_outside_the_window_base_are_ignored | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_slot_bits_use_the_absolute_window_offset | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SlotsAbsoluteIndexing::test_the_prediction_records_keep_absolute_offsets | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_commit_squash_cancels_this_cycle_prediction | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_decode_squash_cancels_this_cycle_prediction | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_decode_squash_is_one_cycle_latency | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_first_post_redirect_ft_forms_next_cycle_at_the_corrected_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2SquashCancelsPrediction::test_squash_flushes_the_ftq_in_the_same_cycle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusEnum::test_no_deleted_ports_exist | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusEnum::test_no_v1_deleted_state_exists | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusEnum::test_status_enum_is_exactly_four_states | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_commit_trap_squash_enters_squashing | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_ftq_not_ready_leaves_idle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_ftqfull_to_running_when_the_ftq_frees | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_idle_to_running_when_ftq_ready | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_only_the_documented_transitions_exist | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_reject_stall_is_not_a_state | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_running_to_ftqfull_when_the_ftq_is_full | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_squashing_auto_transitions_to_running | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestBACV2StatusFSM::test_squashing_lasts_exactly_one_cycle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestInstSizeConventionBoundary::test_a_commit_origin_corrective_converts_bytes_to_the_enum | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestInstSizeConventionBoundary::test_a_two_byte_branch_converts_to_zero | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestL2ConfigPassThrough::test_enabling_at_bac_reaches_the_bpu | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestL2ConfigPassThrough::test_the_default_leaves_the_bpu_one_cycle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestResolveLeg::test_a_resolve_is_delivered_while_squashing | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestResolveLeg::test_a_resolve_slot_refusal_raises_instead_of_dropping | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_commit_mispredict_anchors_at_the_mispredicting_insts_row | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_commit_type0_squash_anchors_at_the_latched_head_row | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_commit_type0_unreachable_latch_raises | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_constructed_squash_freed_younger_equals_flushed_minus_anchor | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashAnchorFreesTheFlushedRows::test_decode_mispredict_anchors_at_the_dec_bb_idx | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_a_younger_squash_is_dropped_while_the_slot_is_occupied | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_outstanding_squash_survives_many_ticks_of_backpressure | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_redirect_is_applied_immediately_not_on_landing | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestSquashMergeOldestWins::test_the_status_holds_squashing_until_the_squash_lands | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_commit_type0_no_anchor_sentinel_raises | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_absent_latch_falls_to_the_ft_covering_the_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_anchor_is_the_ft_stamped_row | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_decode_type0_unreachable_latch_with_no_covering_entry_raises | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_the_anchor_is_read_from_each_request_not_latched | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_cl.TestType0AnchorSourcing::test_type0_commit_anchor_ignores_cur_bb_idx | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2FinalizeConsume::test_a_branch_less_window_still_finalizes_and_inserts | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2FinalizeConsume::test_a_consumed_record_is_never_inserted_twice | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2FinalizeConsume::test_a_not_taken_record_advances_bacpc_to_end_pc | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2FinalizeConsume::test_a_window_accepted_at_n_is_inserted_at_n_plus_one | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2FinalizeConsume::test_bacpc_advances_by_the_record_s_own_terminal_rule | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2FinalizeConsume::test_the_insert_precedes_the_ftqfull_latch | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2L2OffControlUnchanged::test_a_squash_with_l2_off_touches_no_transport_state | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2L2OffControlUnchanged::test_the_one_cycle_insert_still_lands_in_the_accepting_cycle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2L2OffControlUnchanged::test_the_strong_parity_assert_stays_armed_when_l2_is_off | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2ProvisionalGeneration::test_a_refused_accept_holds_the_lookahead | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2ProvisionalGeneration::test_the_accept_leg_moves_lookaheadpc_and_nothing_else | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2ProvisionalGeneration::test_the_strong_parity_assert_is_disarmed_under_l2 | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2ProvisionalGeneration::test_the_two_pcs_diverge_in_flight_and_converge_on_finalize | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2ProvisionalGeneration::test_the_weak_check_has_teeth_on_a_divergence_with_nothing_in_flight | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2ProvisionalGeneration::test_the_weak_check_has_teeth_on_an_over_bound_window_count | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2SquashDiscardsTransport::test_a_squash_discards_the_record_that_was_about_to_be_consumed | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2SquashDiscardsTransport::test_clear_states_voids_the_transport_too | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_finalize_consume.TestBACV2SquashDiscardsTransport::test_the_bpu_s_in_flight_window_and_latched_record_are_both_voided | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_ftq_contract.TestCheckedInsert::test_a_backpressured_finalize_insert_raises_not_drops | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_ftq_contract.TestCheckedInsert::test_a_backpressured_generation_insert_raises_not_drops | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_ftq_contract.TestRealFTQFullness::test_a_pop_reopens_the_queue_after_its_shadow_commits | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_ftq_contract.TestRealFTQFullness::test_the_insert_that_fills_the_ftq_latches_full_in_the_same_cycle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_squash_merge.TestCommitPrecedence::test_a_commit_is_held_after_the_decode_issued_this_cycle | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_squash_merge.TestCommitPrecedence::test_a_commit_squash_replaces_a_pending_decode_squash | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_squash_merge.TestCommitPrecedence::test_same_origin_oldest_wins | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_squash_merge.TestResetClearsPending::test_clear_states_drops_a_pending_squash | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_squash_merge.TestResetClearsPending::test_deactivate_drops_a_pending_squash | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_squash_merge.TestResetClearsPending::test_set_pc_drops_a_pending_squash | block-BACV2 | default | PASS | - | 0 |
| test_bac_v2_update_port::test_a_backpressured_commit_update_raises | block-BACV2 | default | PASS | - | 0 |
| test_harness_bacv2::test_conftest_import_strategy_resolves_real_pymtl3 | block-BACV2 | default | PASS | - | 0 |
| test_harness_bacv2::test_conftest_import_strategy_uses_the_o3_shim | block-BACV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBatchLookupIsPureRead::test_allocates_no_checkpoint_and_leaves_sm_untouched | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBatchLookupIsPureRead::test_count_selects_the_members_and_zero_count_reads_nothing | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBatchLookupIsPureRead::test_returns_the_counter_values_as_a_taken_mask | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_counters_are_per_branch_not_global | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_saturates_at_strong_not_taken_0 | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_saturates_at_strong_taken_3 | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_weak_and_strong_taken_boundary_flips_the_prediction | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBimodalCounterSaturation::test_weak_not_taken_is_0_and_predicts_not_taken | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBpuConfigSurface::test_the_bpu_config_gate_accepts_bimodal | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBpuConfigSurface::test_the_bpu_with_bimodal_composes_a_cpred_child | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestBpuConfigSurface::test_the_class_the_bpu_names_for_bimodal_is_real_and_on_contract | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestCpredV2PortSurface::test_exposes_every_frozen_cpred_v2_port | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestCpredV2PortSurface::test_request_ports_carry_the_frozen_request_types | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestCpredV2PortSurface::test_surface_is_identical_to_gshare_v2 | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_a_request_buffered_in_the_reset_cycle_does_not_survive_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_reset_clears_every_counter | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_reset_clears_the_checkpoint_list | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_reset_clears_the_next_counter_shadow | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_reset_zeroes_both_ghr_images | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestReset::test_the_dut_still_predicts_after_a_reset | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_chkpt_alloc_returns_a_live_index_and_grows_occupancy | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_chkpt_alloc_stores_the_passed_ghr_even_when_it_differs_from_live | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_chkpt_alloc_stores_the_passed_ghr_snapshot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_chkpt_ghr_at_is_none_for_a_never_allocated_or_out_of_range_index | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSetGhrAndChkptAlloc::test_set_ghr_is_visible_on_the_next_cycle_not_the_current_one | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_at_the_tail_is_a_no_op_on_the_list | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_does_not_release_the_anchor | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_does_not_write_the_ghr_register | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bimodal_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_truncates_strictly_younger_checkpoints | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestAssertionA::test_assertion_a_fires_when_a_commit_names_an_older_row | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestAssertionA::test_assertion_a_is_not_an_index_comparison | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestAssertionA::test_assertion_a_never_fires_over_a_commit_stream | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestBulkSquashTruncatesCpredChain::test_a_bulk_squash_truncates_the_cpred_checkpoint_chain | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestBulkSquashTruncatesCpredChain::test_a_corrective_still_truncates_via_its_train_not_a_second_port | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI1PerPredictCheck::test_a_predict_on_an_allocation_free_path_stays_silent | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI1PerPredictCheck::test_a_stale_ckpt_image_at_a_predict_fires_the_counter | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_a_squash_truncation_is_counted_as_a_release | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_k_cnt_nonzero_is_a_pulse_not_an_invariant | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_A_and_I1_counters_are_enforced_not_merely_exported | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_assertion_fails_the_run_on_a_genuine_leak | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_exported_counter_is_the_asserted_expression | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_i1_conjunct_of_the_gate_is_reachable | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_live_term_balances_at_every_settled_pass | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestI4ReleaseAccountingAssert::test_the_live_term_is_load_bearing | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3AnbPolicy::test_an_all_not_taken_member_set_arms_anb | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3AnbPolicy::test_only_count_zero_leaves_anb_clear | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3Bitmap::test_a_second_ending_ft_in_the_same_window_overwrites_not_merges | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3Bitmap::test_bb_n_plus_1_allocation_does_not_disturb_bb_n_row | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3Bitmap::test_bitmap_is_not_the_ft_relative_index | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3Bitmap::test_bitmap_sets_exactly_the_member_offsets | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3BranchlessFT::test_count_zero_leaves_the_previous_bitmap_untouched | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3BranchlessFT::test_count_zero_returns_cur_bb_idx_and_arms_no_anb | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3EntryAllocation::test_anb_set_allocates_a_row_and_a_checkpoint_with_the_live_ghr | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3EntryAllocation::test_no_anb_means_no_allocation | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3IBFormationAssert::test_a_non_pushing_class_below_the_terminal_is_a_formation_error | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3IBFormationAssert::test_a_one_below_the_terminal_is_a_formation_error | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3IBFormationAssert::test_a_well_formed_member_set_passes_the_formation_check | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3PoolsShortReject::test_pools_short_rejects_without_any_side_effect | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_always_taken_classes_are_forced_taken | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_conditional_members_take_their_counter_opinion | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_empty_ras_return_terminal_is_demoted_too | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_no_taken_record_yields_terminal_minus_one_and_zero_target | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_only_records_up_to_the_terminal_push_history | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_targetless_taken_terminal_is_demoted_at_the_producer | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_terminal_is_the_lowest_taken_record | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3TakenMaskAndTerminal::test_terminal_target_comes_from_the_btb_record | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3WriteEntryOrdering::test_same_cycle_alloc_and_write_entry_leaves_the_written_row | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL3WriteEntryOrdering::test_the_rows_checkpoint_is_the_one_the_entry_allocated | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Accounting::test_allocation_accounting_balances_over_a_long_sequence | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Accounting::test_the_accounting_counter_notices_a_missing_release | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4BitmapResidency::test_a_pre_terminal_member_reads_bb_n_image_after_bb_n1_predicts | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_a_commit_frees_every_strictly_older_row_and_spares_its_own | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_a_squash_never_reads_or_writes_the_latch | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_an_unreachable_latch_asserts_instead_of_draining_the_list | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_detector_is_inert_without_attached_views | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_release_path_is_inert_until_the_first_commit | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_stall_detector_fires_after_a_bounded_number_of_cycles | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_stall_detector_stays_quiet_while_any_conjunct_is_false | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4CatchupRelease::test_the_walk_is_bounded_per_cycle_and_resumes_from_the_retained_latch | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_a_commit_matching_the_head_does_not_release | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_a_commit_naming_a_newer_row_releases_the_head_row_and_its_ckpt | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_releasing_a_row_whose_ckpt_was_never_allocated_is_safe | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_the_catchup_walk_drains_every_older_row_over_successive_cycles | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4Release::test_two_releases_on_one_head_do_not_double_free | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4ReleaseNonDegeneracy::test_a_commit_naming_a_gap_row_walks_the_head_up_to_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL4ReleaseNonDegeneracy::test_the_head_naming_commit_is_inert_while_rows_are_live | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Backpressure::test_a_second_squash_does_not_displace_the_first | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Backpressure::test_rdy_is_false_while_a_squash_is_outstanding | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5BulkSquash::test_a_type_zero_squash_never_trains_even_when_taken | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5BulkSquash::test_a_type_zero_squash_truncates_without_training_or_writing_ghr | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5CorrectiveTrain::test_the_resolve_trains_at_the_rows_ckpt_image_not_the_live_ghr | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Kcnt::test_a_corrective_uses_the_derived_k_cnt_for_g_prime | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Kcnt::test_g_prime_is_h0_shifted_by_k_plus_one_or_the_taken_bit | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Kcnt::test_k_cnt_is_the_prefix_popcount_of_the_row_bitmap | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Kcnt::test_the_window_guard_forces_k_cnt_to_zero | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5Promotion::test_zs_own_marked_commit_releases_the_row_it_inherited | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5ReachabilityAssert::test_an_unreachable_in_range_anchor_asserts | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5TruncationAndAnb::test_g_prime_survives_the_same_pass_squash_to | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5TruncationAndAnb::test_the_corrective_re_arms_anb | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5TruncationAndAnb::test_the_retained_row_is_the_anchor_and_its_image_is_intact | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestL5TruncationAndAnb::test_younger_rows_and_checkpoints_are_truncated | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestOneOwnerBothPoolsSameAnchor::test_a_mispredict_squash_truncates_both_pools_at_the_same_anchor | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestOneOwnerBothPoolsSameAnchor::test_a_tail_anchor_frees_zero_rows | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestOneOwnerBothPoolsSameAnchor::test_a_type0_resteer_squash_truncates_both_pools_at_the_same_anchor | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestOneOwnerBothPoolsSameAnchor::test_the_corrective_truncates_the_ckpt_chain_to_the_anchor | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSec15MispredSquashPulse::test_one_accepted_corrective_is_exactly_one_pulse_even_if_reissued | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_a_flushed_row_released_before_the_gate_is_not_an_orphan | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_a_strand_with_room_in_the_arena_is_not_yet_fatal | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_the_anchor_and_strictly_younger_rows_are_excluded | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_the_ftq_records_the_distinct_bb_idx_it_discards_on_a_flush | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpred_unit_v2_cl.TestSquashOrphanGate::test_the_gate_fires_when_a_strand_saturates_the_arena | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_update_scope::test_the_commit_update_port_refuses_multiple_threads | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_flush_driver::test_a_same_cycle_read_is_not_protected_but_the_next_cycle_is | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_flush_driver::test_flush_pulse_clears_the_installed_record | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_flush_driver::test_flush_rdy_is_false_only_while_a_pulse_is_buffered | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_flush_driver::test_no_flush_control_keeps_the_installed_record | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_flush_driver::test_one_pulse_clears_both_arrays | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_flush_driver::test_one_pulse_clears_every_bank | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_flush_driver::test_the_l1_and_l2_fan_out_and_the_and_guard | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_direct_call_consumes_a_target_slot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_direct_uncond_consumes_a_target_slot_and_stores_its_target | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[1-False-False-False-Return] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[2-True-False-False-CallDirect] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[3-True-True-False-CallIndirect] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[5-False-False-True-DirectUncond] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[6-False-True-False-IndirectCond] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_non_conditional_class_installs_through_the_counter_gate[7-False-True-True-IndirectUncond] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_a_return_consumes_no_target_slot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallClassesAndSlots::test_an_indirect_consumes_no_target_slot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallGateObservedTaken::test_a_not_taken_corrective_does_not_install | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallGateObservedTaken::test_an_uncond_corrective_installs_with_a_not_taken_payload | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallIssuance::test_a_non_directcond_class_ignores_the_filter | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallIssuance::test_a_nonresident_directcond_installs | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallIssuance::test_a_resident_directcond_still_emits_an_install | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallIssuance::test_the_window_test_precedes_the_bitmap_test | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallPathGating::test_a_bulk_squash_does_not_install | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallPathGating::test_the_commit_path_does_not_install | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestInstallPortDiscipline::test_the_install_is_issued_through_the_update_port | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestL5BtbInstall::test_a_taken_corrective_installs_a_btb_record | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_btb_install.TestL5BtbInstall::test_the_installed_record_lands_in_the_branchs_own_window | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_a_latency_of_three_sizes_the_ring_to_three | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_a_latency_of_two_is_constructible_and_sizes_the_ring | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_a_zero_latency_with_l2_enabled_is_rejected | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_enabling_builds_the_l2_geometry | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_l2_with_fewer_ways_than_l1_is_rejected | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_latency_below_one_without_l2_is_not_rejected | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_predict_latency_is_stored_and_defaults_to_two | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_the_default_configuration_builds_no_l2_array | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2ConfigurationSurface::test_the_way_ratio_guard_is_inert_when_l2_is_dark | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2IsInertUntilLatencyOpens::test_nothing_ever_reaches_the_l2_array | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2IsInertUntilLatencyOpens::test_the_dual_install_is_atomic_when_the_l2_update_port_refuses | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2IsInertUntilLatencyOpens::test_the_l2_ports_are_never_called_by_the_one_cycle_path | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config.TestL2IsInertUntilLatencyOpens::test_the_same_predict_gives_the_same_answer_either_way | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_l2_config::test_dark_accept_counts_every_accepted_predict | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_a_none_anchor_raises_rather_than_naming_row_zero[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_a_none_anchor_raises_rather_than_naming_row_zero[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_a_resolve_for_a_dead_row_raises[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_a_resolve_for_a_dead_row_raises[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_severing_the_arm_by_class_drives_the_census_to_zero[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_severing_the_arm_by_class_drives_the_census_to_zero[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_the_census_counts_every_counter_write_the_arm_performs[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCensusIsNonVacuous::test_the_census_counts_every_counter_write_the_arm_performs[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCounterStrengthensOnCorrectResolutions::test_a_stably_not_taken_member_pulls_its_counter_down[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCounterStrengthensOnCorrectResolutions::test_a_stably_not_taken_member_pulls_its_counter_down[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCounterStrengthensOnCorrectResolutions::test_a_stably_taken_conditional_saturates_its_counter[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestCounterStrengthensOnCorrectResolutions::test_a_stably_taken_conditional_saturates_its_counter[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestOneWriterPerOccurrence::test_a_mispredict_produces_exactly_one_counter_write[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestOneWriterPerOccurrence::test_a_mispredict_produces_exactly_one_counter_write[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestOneWriterPerOccurrence::test_the_corrective_alone_writes_no_counter[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestOneWriterPerOccurrence::test_the_corrective_alone_writes_no_counter[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainHasNoCheckpointSideEffect::test_repeated_resolves_leave_the_anchor_checkpoint_intact[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainHasNoCheckpointSideEffect::test_repeated_resolves_leave_the_anchor_checkpoint_intact[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainingPredicate::test_a_btb_miss_resolving_not_taken_trains_and_installs_nothing[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainingPredicate::test_a_btb_miss_resolving_not_taken_trains_and_installs_nothing[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainingPredicate::test_a_btb_miss_resolving_taken_installs_and_seeds_the_counter[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_resolve_train.TestTrainingPredicate::test_a_btb_miss_resolving_taken_installs_and_seeds_the_counter[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_construct_rejects_an_unknown_cpred_type | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_drain_complete_reports_drained_on_a_fresh_bpu | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_elaborates_with_bimodal | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_exposes_exactly_the_stub_bpu_port_surface | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_exposes_the_cur_bb_idx_squash_anchor | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_port_request_types_match_the_stub | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_surface::test_bpu_v2_squash_req_carries_rdy_and_returns_a_resp | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1AcceptAllocatesNothing::test_the_accept_answer_is_the_provisional_shape | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1AcceptAllocatesNothing::test_the_accept_spends_no_allocation_and_no_row_write | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1AcceptAllocatesNothing::test_the_record_carries_the_triple_the_accept_returned | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1BoundAndOrder::test_at_the_bound_a_second_accept_raises_side_effect_free | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1BoundAndOrder::test_two_windows_travel_in_order_one_emit_per_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1CensusIsSeverable::test_an_allocation_outside_finalize_raises_the_census | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1CensusIsSeverable::test_count_equality_ties_accept_to_finalize_to_allocation | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1ControlIsTheSynchronousPath::test_l2_off_rdy_still_guards_on_the_predict_record | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1ControlIsTheSynchronousPath::test_l2_off_still_answers_with_a_row_index | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1FinalizeAllocatesOnce::test_finalize_allocates_exactly_once_and_stamps_the_row | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1FinalizeAllocatesOnce::test_the_emitted_triple_is_the_records_own_one_bit_for_bit | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v2_transport_t1.TestT1FinalizeAllocatesOnce::test_the_finalized_record_is_ftqinsertreq_shaped | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aBoundRefusal::test_accept_up_to_the_bound_in_one_cycle_cannot_over_accept | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aBoundRefusal::test_the_bound_plus_one_th_accept_raises_side_effect_free | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aBoundRefusal::test_the_bound_reads_the_pending_view_not_the_committed_one | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aMaxFtPerCycleCensus::test_a_cycle_with_two_accept_marks_is_counted | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aMaxFtPerCycleCensus::test_one_accept_per_cycle_leaves_the_census_at_zero | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aMaxFtPerCycleCensus::test_the_census_counts_cycles_not_windows | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aRingHoldsTheBound::test_a_window_is_due_after_predict_latency_cycles | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aRingHoldsTheBound::test_an_empty_cycle_emits_nothing | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aRingHoldsTheBound::test_finalize_takes_the_head_first_and_the_tail_next | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aRingHoldsTheBound::test_the_ring_is_sized_from_the_bound_not_from_a_literal | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aRingHoldsTheBound::test_two_distinct_windows_travel_independently_together | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aVoidEmptiesTheRing::test_a_void_also_kills_the_accepts_of_its_own_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aVoidEmptiesTheRing::test_a_void_clears_a_COMMITTED_multi_entry_ring | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aVoidEmptiesTheRing::test_a_void_clears_every_window_in_a_two_entry_ring | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aVoidEmptiesTheRing::test_one_window_per_cycle_still_drains_at_the_wider_bound | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3aVoidEmptiesTheRing::test_the_ring_refills_and_drains_cleanly_after_a_void | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3bVoidedCensus::test_a_kill_after_a_partial_drain_splits_the_accepts | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3bVoidedCensus::test_a_kill_of_an_empty_ring_voids_nothing | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3bVoidedCensus::test_every_void_of_a_live_window_is_counted_exactly_once | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3a_skid_ring.TestT3bVoidedCensus::test_the_dark_configuration_keeps_voided_at_zero | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3b_finalize_stall.TestT3bFinalizeStall::test_a_level_left_high_stalls_every_later_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3b_finalize_stall.TestT3bFinalizeStall::test_a_stalled_finalize_does_not_allocate_emit_or_drop | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3b_finalize_stall.TestT3bFinalizeStall::test_clearing_the_stall_delivers_the_held_chain_with_no_gap | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3b_finalize_stall.TestT3bFinalizeStall::test_pools_short_stalls_the_same_condition_as_ftq_full | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3b_finalize_stall.TestT3bFinalizeStall::test_reset_drops_a_level_that_was_driven_before_the_edge | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3b_finalize_stall.TestT3bFinalizeStall::test_the_dark_configuration_never_arms_the_stall | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3b_finalize_stall.TestT3bFinalizeStall::test_the_stall_deasserts_ready_through_the_bound_not_around_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v3b_finalize_stall.TestT3bFinalizeStall::test_the_stall_holds_the_head_and_the_tail_in_order | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestAllocateAlwaysInL2::test_a_taken_resolve_installs_into_both_arrays | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestAllocateAlwaysInL2::test_the_arrays_update_if_disagreeing_rule_is_one_rule_not_two | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestFillAtFinalize::test_a_window_l1_lost_and_l2_keeps_is_filled_back | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestFillAtFinalize::test_a_window_sized_fill_needs_no_more_than_its_own_buffer_entry | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestFillAtFinalize::test_the_fill_is_not_gated_on_an_l1_hit_of_a_different_window | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestL1SubsetOfL2::test_the_census_fires_inside_a_run_not_only_in_the_end_of_run_check | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestL1SubsetOfL2::test_the_check_fails_loudly_when_l1_holds_what_l2_never_saw | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestL1SubsetOfL2::test_the_invariant_holds_after_a_mixed_run | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestL2ProbeAtAccept::test_a_probe_that_hits_promotes_l2_replacement_state | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestL2ProbeAtAccept::test_an_l1_hit_does_not_suppress_the_l2_probe | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestL2ProbeAtAccept::test_the_probe_carries_the_same_window_key_as_the_l1_read | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestL2ProbeAtAccept::test_the_probe_happens_in_the_accept_cycle_not_later | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestPortPriority::test_a_fill_and_an_update_in_one_cycle_drop_the_update_and_count_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v5_l2_access.TestPortPriority::test_an_update_of_the_same_window_as_the_fill_shares_the_port_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCheckpointsAreShared::test_both_readers_resolve_the_same_index_to_the_same_image | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCheckpointsAreShared::test_cpred_l2_owns_no_checkpoint_list | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCheckpointsAreShared::test_one_row_spends_exactly_one_checkpoint | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCpredL2TypeSelection::test_an_unknown_type_raises_naming_the_legal_set | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCpredL2TypeSelection::test_bimodal_is_a_legal_l2_engine | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCpredL2TypeSelection::test_default_is_gshare | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCpredL2TypeSelection::test_tage_is_selected_with_the_four_stage_transport | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCpredL2TypeSelection::test_tage_refuses_multiple_threads_until_its_path_is_per_thread | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCpredL2TypeSelection::test_tage_requires_latency_four | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestCpredL2TypeSelection::test_tage_requires_the_transport_armed | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestFoldIsAboveTheBankBit::test_a_colocated_pair_never_shares_a_bank | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestFoldIsAboveTheBankBit::test_cpred_l1_keeps_the_unbanked_rule | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestFoldIsAboveTheBankBit::test_four_byte_branches_do_not_pile_into_one_bank | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestFoldIsAboveTheBankBit::test_the_bank_is_a_pure_function_of_the_pc | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestFoldIsAboveTheBankBit::test_the_model_matches_the_local_banked_rule | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestFoldIsAboveTheBankBit::test_the_pair_would_change_bank_if_the_hash_reached_the_bank_bits | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestMemberDisagreementsHasTeeth::test_agreeing_tables_yield_zero | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestMemberDisagreementsHasTeeth::test_mutation_removing_the_l2_read_kills_the_census | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestMemberDisagreementsHasTeeth::test_mutation_seeding_only_l1_leaves_a_terminal_only_scheme_indistinguishable | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestMemberDisagreementsHasTeeth::test_the_interior_flip_yields_exactly_one | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestPerMemberVetting::test_both_members_are_read_not_just_the_nominated_terminal | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestPerMemberVetting::test_interior_member_disagreement_is_counted | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestPerMemberVetting::test_l2_only_member_is_not_a_direction_disagreement | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestPerMemberVetting::test_the_disagreement_changes_no_control_flow | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestReadIsAtFinalize::test_accept_issues_no_l2_direction_read | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestReadIsAtFinalize::test_the_read_appears_only_once_the_window_finalizes | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestReadIsAtFinalize::test_the_read_uses_the_records_carried_image_not_a_live_register | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestResolveTrainsBothTables::test_a_single_table_reach_counts_the_drop | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestResolveTrainsBothTables::test_both_tables_move_on_one_resolve | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestResolveTrainsBothTables::test_one_train_write_per_table_per_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestResolveTrainsBothTables::test_the_l1_leg_drop_is_also_counted | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v6_cpred_l2.TestResolveTrainsBothTables::test_the_l2_table_trains_at_the_shared_image | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCensusLaw::test_an_agreeing_pair_retries_for_no_reason | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCensusLaw::test_every_compared_window_either_finalizes_or_retries | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCensusLaw::test_the_two_reasons_are_exhaustive | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCompareConsumesNothing::test_a_shape_retry_emits_nothing_and_kills_the_window | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCompareConsumesNothing::test_an_agreeing_window_emits_the_provisional_triple_bit_for_bit | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCompareConsumesNothing::test_the_transport_dark_increments_none_of_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCompareHasTeeth::test_blinding_the_l2_probe_to_a_shorter_answer_still_vetoes | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCompareHasTeeth::test_blinding_the_l2_probe_to_an_empty_window_abstains_and_emits | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCompareHasTeeth::test_every_conditional_member_is_read_and_nothing_else_is | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCompareReadsTheFtsRange::test_a_member_behind_the_ft_start_pc_is_not_a_member_of_this_ft | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestCompareReadsTheFtsRange::test_the_l2_triple_applies_step_4bs_demote_too | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestShapeReason::test_an_interior_l2_flip_is_a_shape_retry | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestShapeReason::test_an_l2_only_not_taken_member_between_is_not_a_retry | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestShapeReason::test_an_l2_only_taken_member_between_is_a_shape_retry | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestShapeReason::test_end_pc_cannot_differ_where_the_terminal_slot_agrees | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestTargetReason::test_a_different_btb_target_for_the_same_terminal_is_the_target_reason | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7_triple_compare.TestTargetReason::test_a_returns_target_is_not_the_l2_stages_to_answer | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestArmedHistFullRejectRetired::test_a_window_is_accepted_even_when_the_pools_cannot_cover_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestArmedHistFullRejectRetired::test_the_one_cycle_configuration_keeps_its_reject | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestArmedHistFullRejectRetired::test_the_stall_instead_of_the_reject_is_what_holds_the_window | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestBacHoldsOnReady::test_a_held_cycle_issues_no_window_read_and_no_predict | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestBacHoldsOnReady::test_the_gate_is_inert_with_the_transport_dark | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestReadyPort::test_a_caller_that_ignores_ready_raises_instead_of_being_declined | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestReadyPort::test_ready_deasserts_exactly_at_the_inflight_bound | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestReadyPort::test_ready_is_not_a_second_bound | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestReadyPort::test_ready_returns_when_the_head_finalizes | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestReadyPort::test_the_transport_dark_always_answers_ready | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestStatusNames::test_idle_is_ready_then_busy_then_ready_again | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v7c_ready_states.TestStatusNames::test_retrying_is_absent_until_t7b | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8a_k_hist.TestBucketAssignment::test_a_branch_less_window_lands_in_bucket_0 | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8a_k_hist.TestBucketAssignment::test_a_one_member_window_lands_in_bucket_1_and_is_not_multimember | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8a_k_hist.TestBucketAssignment::test_a_two_member_window_lands_in_bucket_2 | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8a_k_hist.TestBucketAssignment::test_the_same_window_histograms_identically_with_the_transport_dark | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8a_k_hist.TestIdentities::test_the_buckets_sum_to_the_predicted_ft_census | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8a_k_hist.TestIdentities::test_the_distribution_this_pin_describes_is_one_two_one_in_buckets | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8a_k_hist.TestIdentities::test_the_upper_buckets_sum_to_multimember_ft | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow.TestRowCarriesTheSnapshot::test_a_correct_prediction_on_a_saturated_member_is_suppressed[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow.TestRowCarriesTheSnapshot::test_a_correct_prediction_on_a_saturated_member_is_suppressed[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow.TestRowCarriesTheSnapshot::test_a_mispredict_is_exempt_even_when_the_bit_is_set[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow.TestRowCarriesTheSnapshot::test_a_mispredict_is_exempt_even_when_the_bit_is_set[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow.TestRowCarriesTheSnapshot::test_a_pc_outside_the_rows_window_does_not_borrow_slot_zeros_bit[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow.TestRowCarriesTheSnapshot::test_a_pc_outside_the_rows_window_does_not_borrow_slot_zeros_bit[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow.TestRowCarriesTheSnapshot::test_the_sat_bit_is_keyed_by_window_slot_not_list_index[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow.TestRowCarriesTheSnapshot::test_the_sat_bit_is_keyed_by_window_slot_not_list_index[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow::test_batch_lookup_reports_saturation_from_the_read_it_already_takes | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow::test_bimodal_samples_saturation_by_the_same_rule | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8c_sat_shadow::test_strict_saturation_is_the_only_reading_that_counts | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_a_filtered_leg_writes_nothing_and_claims_no_port[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_a_filtered_leg_writes_nothing_and_claims_no_port[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_a_stale_bit_costs_one_step_and_the_next_train_pays_it_back[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_a_stale_bit_costs_one_step_and_the_next_train_pays_it_back[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_an_unsaturated_cell_in_the_predicted_direction_still_trains[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_an_unsaturated_cell_in_the_predicted_direction_still_trains[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_both_filter_rows_are_reachable_and_neither_carries_an_opposite_pair | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_both_tables_saturated_is_the_one_filtered_case | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_every_training_event_ends_in_exactly_one_of_three_censuses[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_every_training_event_ends_in_exactly_one_of_three_censuses[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_one_table_unsaturated_clears_the_shared_bit | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_opposite_saturations_do_not_stand_because_the_retry_repairs_them | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_the_mirror_pair_is_also_vetoed_before_it_can_be_filtered | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_the_one_cycle_configuration_has_no_pair_to_filter[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_the_one_cycle_configuration_has_no_pair_to_filter[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_the_table_is_never_addressed_for_a_filtered_leg[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v8d_train_filter::test_the_table_is_never_addressed_for_a_filtered_leg[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v9_retry_leg.TestDarkStaysDark::test_the_transport_dark_retries_supersede_and_pulses_nothing | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v9_retry_leg.TestFillLegs::test_a_second_disagreement_on_a_new_window_retries_again | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v9_retry_leg.TestFillLegs::test_the_retry_installs_l2s_cell_into_l1_as_a_write | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v9_retry_leg.TestRetryLeg::test_a_killed_window_leaves_the_front_view_where_it_was | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v9_retry_leg.TestRetryLeg::test_a_reissued_window_after_the_repair_finalizes | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v9_retry_leg.TestRetryLeg::test_a_triple_disagreement_kills_the_window_and_names_it_to_bac | block-BPredUnitV2 | default | PASS | - | 0 |
| test_bpu_v9_retry_leg.TestRetryLeg::test_the_retry_pulse_lives_for_exactly_one_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[br_type] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[is_call] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[is_indirect] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[is_return] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[is_uncond] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_difference_in_any_compared_field_always_writes[target] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_disagreeing_reinstall_still_promotes_its_way | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_fill_into_a_live_way_follows_the_same_way_hit_law | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_full_set_evicts_the_least_recently_used_way | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_later_install_leaves_the_windows_sibling_records_untouched | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_later_install_overwrites_the_pool_slot_it_reuses | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_record_slot_names_the_branch_end_not_its_start | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_target_repair_keeps_the_slot_it_already_held | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_a_way_hit_under_pool_pressure_keeps_its_windows_other_records | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_aliasing_windows_are_distinguished_by_tag | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_all_sixteen_slots_of_a_window_may_hold_members | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_an_agreeing_reinstall_leaves_replacement_state_untouched | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_an_identical_reinstall_leaves_the_record_undisturbed | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_direct_call_records_consume_a_slot_and_return_call_records_do_not | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_evict_to_admit_never_hard_fails_a_whole_window_replacement | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_evicting_a_slot_consumer_frees_its_slot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_flush_clears_every_way_of_every_set | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_install_is_visible_exactly_one_cycle_after_acceptance | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_invalid_ways_are_filled_before_a_valid_way_is_evicted | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_metadata_only_records_do_not_trip_the_slot_claim_assertion | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_pool_covers_a_real_dense_window_resident_plus_one | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_pool_depth_is_the_documented_null_plus_slots | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_pool_exhaustion_across_ways_is_reached_only_past_the_measured_max | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_record_fields_round_trip_through_an_install | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_record_key_is_the_window_base_plus_twice_the_offset | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_records_of_one_set_read_their_targets_from_the_shared_pool | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_retag_without_pressure_releases_the_destroyed_tenants_slots | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_retagging_a_way_without_slot_pressure_hides_the_previous_tenant | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_return_and_indirect_records_consume_no_target_slot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_same_address_slot_consuming_reinstall_reuses_its_slot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_same_window_trainings_in_one_pass_coalesce_into_one_write | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_slot_consuming_record_without_a_slot_claim_fails_the_run | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_tag_is_masked_to_cfg_tag_bits | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_the_way_hit_eviction_counter_counts_events_and_clears_on_reset | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_window_index_is_the_window_number_modulo_num_sets | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_window_read_miss_does_not_disturb_the_lru_order | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_window_read_of_an_empty_window_reports_the_base_and_no_records | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_window_read_promotes_the_hit_way_to_mru | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_window_read_returns_records_of_the_aligned_window | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_cl::test_window_req_rdy_is_false_until_the_cycle_consumes_the_read | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_bank_raises_on_a_set_it_does_not_own | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_busy_bank_refuses_its_own_read_and_its_sibling_still_accepts | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_deferred_group_is_visible_one_cycle_after_the_group_it_waited_for | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_deferred_group_waits_and_lands_it_is_not_dropped | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_fill_is_one_call_carrying_one_whole_window | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_full_install_queue_cannot_refuse_a_fill | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_reset_leaves_no_pending_write_in_either_array | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_second_fill_waits_for_the_first_to_drain | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_second_group_in_the_same_bank_is_not_placed_in_the_same_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_a_single_issue_never_defers | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_fill_records_do_not_merge_with_an_install_group | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_the_array_exposes_no_read_or_write_port_at_all | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_the_bank_count_must_be_a_power_of_two_and_no_larger_than_the_sets | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_the_bank_split_keeps_every_set_owned_exactly_once | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_two_groups_in_two_banks_are_both_placed_in_one_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_btb_v2_ports::test_two_reads_of_two_banks_buffer_two_promotions | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_config_surface::test_supported_cpred_types_elaborate[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_config_surface::test_supported_cpred_types_elaborate[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_config_surface::test_unsupported_cpred_type_raises_at_construct | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_2r1w_bank_never_defers_and_shows_its_peak_at_zero[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_2r1w_bank_never_defers_and_shows_its_peak_at_zero[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_2r1w_engine_never_defers_so_its_bypass_never_fires[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_2r1w_engine_never_defers_so_its_bypass_never_fires[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_batch_answer_and_its_saturation_bit_come_from_the_merged_value[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_batch_answer_and_its_saturation_bit_come_from_the_merged_value[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_deferred_train_does_not_write_the_cell[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_deferred_train_does_not_write_the_cell[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_fill_and_a_train_on_the_same_cell_compose_into_one_write[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_fill_and_a_train_on_the_same_cell_compose_into_one_write[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_fill_that_lands_on_a_queued_train_composes_rather_than_clobbers[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_fill_that_lands_on_a_queued_train_composes_rather_than_clobbers[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_k_member_batch_asks_for_k_cells_not_two_k[make_bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_k_member_batch_asks_for_k_cells_not_two_k[make_gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_predict_and_a_train_on_one_bank_are_two_reads_not_one_of_each | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_queued_pair_that_nets_to_zero_still_moves_the_cell[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_queued_pair_that_nets_to_zero_still_moves_the_cell[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_queued_train_is_visible_to_the_next_read_while_the_cell_is_stale[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_queued_train_is_visible_to_the_next_read_while_the_cell_is_stale[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_queued_train_lands_two_cycles_after_its_bank_frees_up[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_queued_train_lands_two_cycles_after_its_bank_frees_up[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_read_and_a_write_on_the_same_bank_in_one_cycle_is_the_read_first_case[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_read_and_a_write_on_the_same_bank_in_one_cycle_is_the_read_first_case[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_shared_port_refuses_a_fill_and_a_predict_read_in_one_cycle[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_shared_port_refuses_a_fill_and_a_predict_read_in_one_cycle[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_stationary_window_starves_its_banks_at_any_bank_count[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_stationary_window_starves_its_banks_at_any_bank_count[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_train_that_only_shares_a_bank_with_a_fill_waits_for_the_port[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_train_that_only_shares_a_bank_with_a_fill_waits_for_the_port[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_train_with_no_predict_in_the_cycle_still_asks_for_a_read[make_bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_train_with_no_predict_in_the_cycle_still_asks_for_a_read[make_gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_window_read_fits_two_read_ports_at_16_banks | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_a_window_read_is_charged_whole_not_by_the_members_the_btb_named | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_bimodal_and_gshare_put_the_same_key_in_the_same_bank | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_bimodal_bank_field_at_one_bank_reduces_to_todays_index | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_bimodal_performs_the_bank_count_it_used_to_refuse | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_bimodal_refuses_a_geometry_it_cannot_partition | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_both_engines_report_identical_traffic_for_identical_access[make_bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_both_engines_report_identical_traffic_for_identical_access[make_gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_both_engines_service_the_same_demand_under_the_same_port_class[make_bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_both_engines_service_the_same_demand_under_the_same_port_class[make_gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_both_engines_share_the_d3_key_vocabulary | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_four_byte_members_reach_every_bank | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_grey_is_not_conflict_free_for_a_window_and_that_is_why_r10_replaced_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_l1_default_of_one_bank_leaves_the_index_at_sixteen_point_two | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_one_bank_turns_every_multi_member_batch_into_collisions | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_one_install_is_reported_once_however_long_the_run_continues[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_one_install_is_reported_once_however_long_the_run_continues[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_raising_the_l1_count_moves_cells_within_banks_not_between_them | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_reads_equal_accesses_plus_collisions_over_a_mixed_run | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_reset_clears_the_port_census[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_reset_clears_the_port_census[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_bank_field_wraps_without_idling_a_bank | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_bpu_reports_both_levels_bank_counts_separately | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_buffer_drains_when_the_window_moves_at_the_shipped_geometry[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_buffer_drains_when_the_window_moves_at_the_shipped_geometry[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_bypass_reads_the_committed_queue_and_not_this_passes_working_copy[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_bypass_reads_the_committed_queue_and_not_this_passes_working_copy[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_collision_column_is_the_sum_of_its_two_fates[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_collision_column_is_the_sum_of_its_two_fates[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_fill_leg_reports_the_burst_the_port_law_has_no_answer_for[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_fill_leg_reports_the_burst_the_port_law_has_no_answer_for[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_fold_field_is_conflict_free_for_a_window_at_the_ruled_count | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_history_never_moves_a_member_off_its_bank | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_the_two_slots_of_one_group_reach_different_banks | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_two_trains_buffered_to_one_cell_compose_instead_of_overwrite[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_two_trains_buffered_to_one_cell_compose_instead_of_overwrite[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_bank_ports::test_two_trains_on_one_bank_in_one_cycle_are_counted_not_hidden | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_co_located_2b_slots_never_share_an_index[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_co_located_2b_slots_never_share_an_index[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_every_index_is_reachable_by_4b_branches[bimodal] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_every_index_is_reachable_by_4b_branches[gshare] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[10] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[11] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[12] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[1] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[2] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[3] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[4] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[5] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[6] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[7] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[8] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface.TestCounterIndexRule::test_fold_term_is_odd_in_every_legal_table[9] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface::test_cpred_v2_implementation_exposes_the_frozen_port_surface[o3.bimodal_v2_cl] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface::test_cpred_v2_implementation_exposes_the_frozen_port_surface[o3.gshare_v2_cl] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface::test_cpred_v2_implementations_have_identical_surfaces | block-BPredUnitV2 | default | PASS | - | 0 |
| test_cpred_v2_port_surface::test_cpred_v2_request_ports_carry_the_frozen_request_types | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupIsPureRead::test_batch_lookup_leaves_occupancy_next_and_alloc_counts_unchanged | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupIsPureRead::test_batch_lookup_reports_reading_beyond_count_as_zero | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupIsPureRead::test_batch_lookup_returns_counter_values | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupUsesASingleGhr::test_a_nonzero_ghr_moves_every_member_together | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestBatchLookupUsesASingleGhr::test_all_members_are_read_at_the_live_ghr | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestChkptAlloc::test_alloc_does_not_advance_the_register | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestChkptAlloc::test_alloc_reports_rdy_only_when_a_slot_is_free | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestChkptAlloc::test_stored_ghr_equals_the_value_passed | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestIntraUpProcessOrder::test_same_pass_set_ghr_and_squash_to_keeps_the_set_ghr_value | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestIntraUpProcessOrder::test_update_hist_applies_before_set_ghr_in_the_same_pass | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestReset::test_reset_clears_counters_and_checkpoints | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestReset::test_reset_seeds_both_ghr_images | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestSetGhrReq::test_set_ghr_is_masked_to_the_register_width | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestSetGhrReq::test_set_ghr_last_one_wins | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestSetGhrReq::test_set_ghr_overwrites_and_is_visible_next_cycle | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_does_not_write_the_register | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestSquashToIsTruncationOnly::test_squash_to_truncates_strictly_younger_checkpoints | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_train_does_not_write_the_register | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_train_is_a_single_step_per_occurrence | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_train_saturates_at_both_ends | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestTrainReq::test_train_updates_the_counter_at_the_ckpt_image_index | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestUpdateHistAppliesInIssueOrder::test_issue_order_not_sorted_order | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestUpdateHistAppliesInIssueOrder::test_k_pushes_apply_in_issue_order | block-BPredUnitV2 | default | PASS | - | 0 |
| test_gshare_v2_cl.TestUpdateHistAppliesInIssueOrder::test_k_pushes_are_visible_at_the_next_ff | block-BPredUnitV2 | default | PASS | - | 0 |
| test_harness_dir_conftest::test_conftest_import_strategy_resolves_real_pymtl3 | block-BPredUnitV2 | default | PASS | - | 0 |
| test_harness_dir_conftest::test_conftest_import_strategy_uses_the_o3_shim | block-BPredUnitV2 | default | PASS | - | 0 |
| test_harness_v2::test_install_window_makes_the_window_readable_from_the_dut | block-BPredUnitV2 | default | PASS | - | 0 |
| test_harness_v2::test_make_btb_v2_elaborates | block-BPredUnitV2 | default | PASS | - | 0 |
| test_harness_v2::test_mk_records_places_records_at_the_given_offsets | block-BPredUnitV2 | default | PASS | - | 0 |
| test_harness_v2::test_the_array_elaborates_its_banks | block-BPredUnitV2 | default | PASS | - | 0 |
| test_harness_v2::test_tick_advances_the_dut | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_btb_flush_req_exists | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_btb_update_v2_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_btb_update_v2_round_trips | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_inst_size_encoding_boundary | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_window_record_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_window_record_round_trips_through_to_from_dict | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_window_req_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_window_req_round_trips | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_window_resp_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_btb_v2::test_window_resp_round_trips_records | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_batch_lookup_req_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_batch_lookup_req_round_trips_keys_and_count | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_batch_lookup_resp_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_batch_lookup_resp_round_trips_taken_mask | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_chkpt_alloc_req_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_chkpt_alloc_req_round_trips | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_set_ghr_req_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_set_ghr_req_round_trips | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_squash_to_req_has_no_ghr_field | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_squash_to_req_round_trips | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_train_req_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_train_req_round_trips_all_three_fields | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_update_hist_req_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_cpred_v2::test_update_hist_req_round_trips | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_req_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_req_round_trips | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_resp_carries_a_16_bit_taken_mask | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_resp_field_set_matches_spec | block-BPredUnitV2 | default | PASS | - | 0 |
| test_ifc_predict_v2::test_predict_ft_resp_round_trips_with_defaults | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_adr_0051_exists_and_records_the_governance_clause | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_bac_0_2_cites_the_plan_that_audited_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_every_v2_frontend_spec_is_scanned[BAC_CL_v2_Block_Spec.md] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_every_v2_frontend_spec_is_scanned[BPredUnit_CL_v2_Block_Spec.md] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_every_v2_frontend_spec_is_scanned[FTQ_Fetch_Decode_CL_v2_Delta_Spec.md] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_no_spec_states_a_slot_or_end_at_the_branch_start[BAC_CL_v2_Block_Spec.md] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_no_spec_states_a_slot_or_end_at_the_branch_start[BPredUnit_CL_v2_Block_Spec.md] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_no_spec_states_a_slot_or_end_at_the_branch_start[FTQ_Fetch_Decode_CL_v2_Delta_Spec.md] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_key_slot_shape_is_not_forbidden | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BAC_CL_v2_Block_Spec.md:A CONSEQUENCE OF TERMINA] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BAC_CL_v2_Block_Spec.md:AN FT MAY BEGIN ON AN IN] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BAC_CL_v2_Block_Spec.md:ITS MEMBERS ARE EXACTLY ] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BAC_CL_v2_Block_Spec.md:KEY-OWNING FT'S] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BAC_CL_v2_Block_Spec.md:REQUIRES THE USER'S AUDI] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BAC_CL_v2_Block_Spec.md:SUPERSEDED BY (6)] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BAC_CL_v2_Block_Spec.md:THE RECORD'S OFFSET IS T] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BPredUnit_CL_v2_Block_Spec.md:EXACTLY TWO PRODUCERS AN] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BPredUnit_CL_v2_Block_Spec.md:NO WIDER READ AND NO PER] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[BPredUnit_CL_v2_Block_Spec.md:THE SLOT IS THE KEY] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[FTQ_Fetch_Decode_CL_v2_Delta_Spec.md:(KEY - WINDOW_BASE) >> 1] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_law_is_stated_not_merely_implied[FTQ_Fetch_Decode_CL_v2_Delta_Spec.md:THE FT THAT COMPLETED TH] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_start_slot_shape_is_forbidden[ft_off = (PC - WINDOW_BASE) >> 1] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_start_slot_shape_is_forbidden[ft_off = (PC-WINDOW_BASE)>>1] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_spec_last2byte_keying::test_the_start_slot_shape_is_forbidden[ft_off = (Z.pc - R.ft_wbase) >> 1] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_a_retry_restores_the_lookahead_from_the_front | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_a_squash_restores_front_and_lookahead_to_the_corrective_path | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_allocation_carries_raw_p_h_i_and_ghr | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_allocation_rejects_an_overwide_path_h_i_or_ghr | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_finalize_advances_the_front_and_leaves_the_lookahead | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_stage_4_writes_terminal_fields_only | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_stage_one_advances_only_the_lookahead | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_the_checkpoint_h_i_is_the_pre_window_image_and_the_live_folds_differ | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_the_checkpoint_path_is_the_pre_advance_front | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_the_corrective_reproduces_the_path_the_predict_used | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_the_corrective_restores_raw_p_and_reapplies_the_leading_members_and_z | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_checkpoint::test_the_payload_is_568_bits_rounded_to_576 | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_ckpt_transport::test_a_corrective_restores_the_tage_path_from_the_anchor_map | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_ckpt_transport::test_a_later_row_stores_the_front_advanced_by_the_earlier_row | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_ckpt_transport::test_a_refused_tage_train_is_held_and_reoffered | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_ckpt_transport::test_a_resolve_trains_the_tage_at_the_rows_checkpoint_image | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_ckpt_transport::test_the_finalize_writes_the_pre_window_path_and_the_terminal_map | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_ckpt_transport::test_the_tage_path_stops_at_the_terminal | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_a_flush_discards_the_in_flight_result_and_frees_the_port | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_a_held_result_fills_the_pipeline_and_lowers_rdy | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_a_refused_train_changes_nothing_and_succeeds_after_a_drain | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_a_train_indexes_at_the_checkpoints_h_i_image | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_a_train_request_updates_the_provider_and_base | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_a_train_write_is_visible_to_the_next_window | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_a_window_accepted_in_the_flush_cycle_survives_it | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_a_window_result_arrives_after_the_pipeline | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_consecutive_windows_arrive_in_order | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_counter_at_reads_the_selected_value | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_reset_clears_the_tables_and_the_pipeline | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_component::test_the_result_carries_the_terminal_provider_snapshot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_a_different_history_moves_the_within_field_not_the_bank | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_base_index_uses_no_history | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_every_ladder_length_matches_the_reference_fold | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_four_and_eight_bit_folds_are_the_newest_key_bits | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_index_is_within_above_the_bank_field | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_path_folds_returns_the_eight_ladder_folds_in_order | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_path_push_keeps_only_the_low_ten_bits_of_the_key | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_path_push_shifts_the_new_key_into_the_low_ten_bits | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_path_wraps_after_forty_branches | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_rotl10_rotates_inside_ten_bits[0] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_rotl10_rotates_inside_ten_bits[1023] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_rotl10_rotates_inside_ten_bits[1] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_rotl10_rotates_inside_ten_bits[291] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_rotl10_rotates_inside_ten_bits[341] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_rotl10_rotates_inside_ten_bits[682] | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_sixteen_bit_fold_xors_the_previous_keys_low_six_bits | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_sixteen_window_slots_use_sixteen_distinct_banks | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_tag_is_twelve_bits_and_is_the_group_xor_rotated_fold | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_the_bank_is_the_shared_contract_field | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_the_bank_is_unchanged_by_history | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_the_full_path_fold_is_the_xor_of_forty_slices | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_the_ladder_and_geometry_are_the_specs | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_the_ladder_has_one_length_per_tagged_table | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_the_slot_fold_separates_a_two_byte_pair_in_one_group | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_core::test_within_is_group_xor_slot_fold_xor_history | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_path_component::test_checkpoint_image_is_the_pre_advance_front_and_its_folds | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_path_component::test_finalize_path_advances_the_front_by_the_final_keys | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_path_component::test_retry_path_restores_the_lookahead_from_the_front | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_path_component::test_squash_path_restores_both_registers_to_the_corrective_path | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_path_component::test_two_windows_see_successive_lookahead_images | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_path_component::test_window_at_path_uses_the_pre_advance_lookahead | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_reads::test_read_window_reads_all_sixteen_slots | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_reads::test_select_window_reads_returns_the_slots_in_order | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_reads::test_the_read_carries_the_base_index_and_counter | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_reads::test_the_read_is_per_slot_not_per_btb_member | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_reads::test_the_read_merges_the_bank_buffer | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_reads::test_the_read_names_every_tables_index_and_expected_tag | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_reads::test_the_select_from_registered_reads_matches_select_slot | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_reads::test_the_select_uses_the_registered_entries_not_a_later_table_change | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_a_buffered_entry_is_visible_to_the_same_cycle_select | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_a_single_tagged_match_is_the_provider | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_a_tag_mismatch_is_not_a_match | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_an_all_base_window_uses_the_base_counters | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_each_table_uses_its_own_h_i | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_the_base_prediction_bit_is_the_counter_msb | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_the_final_value_is_the_provider_counter_not_the_base | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_the_longest_match_wins_and_the_next_is_the_alternate | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_the_provider_index_is_the_index_the_select_used | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_the_sat_bit_is_strict_saturation_in_the_final_direction | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_the_sixteen_slots_are_selected_in_order | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_the_snapshot_carries_the_alternate_identity | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_select::test_with_only_one_match_the_alternate_is_the_base | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_a_bank_holds_four_distinct_cells_and_refuses_the_fifth | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_a_buffered_write_bypasses_into_the_next_read | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_a_buffered_write_does_not_touch_another_cell | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_a_drain_frees_a_cell_for_a_new_event | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_a_drain_moves_the_oldest_entry_and_keeps_the_rest | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_a_drain_of_an_empty_bank_is_a_no_op | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_a_full_bank_refuses_the_whole_event_and_leaves_other_targets_untouched | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_an_invalid_entry_is_the_reset_value | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_each_array_has_its_own_bank_buffers | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_the_base_array_has_its_own_buffers_and_bypass | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_the_default_geometry_is_the_specs | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_the_entry_widths_are_twelve_tag_two_counter_two_useful | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_tables::test_two_writes_to_one_cell_merge_and_do_not_consume_depth | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_a_correct_agreement_steps_the_provider_and_the_base | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_a_correct_resolve_allocates_nothing | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_a_mispredict_allocates_the_two_longest_non_provider_not_useful_tables | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_a_refused_event_leaves_every_target_unchanged | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_a_taken_mispredict_allocates_a_weak_taken_counter | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_a_wrong_alternate_sets_the_provider_useful | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_a_wrong_provider_with_a_right_alternate_clears_the_useful | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_agreement_leaves_useful_unchanged_and_skips_a_saturated_provider_write | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_an_interior_member_trains_the_current_longest_match | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_d6_does_not_withhold_on_a_mispredict | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_d6_still_writes_the_useful_update | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_d6_with_a_base_provider_still_steps_the_base | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_d6_withholds_only_the_provider_counter_write | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_the_base_provider_steps_the_base_and_allocates | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_uroom_is_zero_when_every_candidate_is_useful | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_uroom_skips_useful_candidates | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_train::test_useful_saturates_at_both_ends | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_transport::test_a_branch_less_window_still_consumes_its_tage_result | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_transport::test_a_retry_drops_the_younger_window_it_kills | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_transport::test_a_squash_flushes_the_tage_pipeline_before_the_next_accept | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_transport::test_a_tage_window_flows_accept_to_finalize | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_transport::test_the_accept_gate_refuses_when_a_full_pipe_cannot_be_drained | block-BPredUnitV2 | default | PASS | - | 0 |
| test_tage_v2_transport::test_the_tage_accept_is_due_gated | block-BPredUnitV2 | default | PASS | - | 0 |
| test_v1_v2_parity::test_v1_v2_commit_value_stream_parity | block-BPredUnitV2 | default | PASS | - | 7 |
| test_csr_file_cl.TestConstruction::test_constructs_with_default_params | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestConstruction::test_exposes_read_callee_ifc | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestConstruction::test_exposes_write_callee_ifc | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestConstruction::test_read_rdy_is_true_after_reset | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestFpDirtySideEffect::test_fp_dirty_bumps_tcsr_gen | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestFpDirtySideEffect::test_fp_dirty_idempotent | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestFpDirtySideEffect::test_fp_dirty_pending_slot_carries_resolved_value | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestFpDirtySideEffect::test_fp_dirty_preserves_other_fields | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestFpDirtySideEffect::test_fp_dirty_sets_fs_dirty_and_sd_raw_storage | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestMappedFflagsRead::test_fflags_views_default_to_zero_after_reset | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestMappedFflagsRead::test_fflags_write_then_fp_view_reads | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestMappedFflagsRead::test_mapped_read_tracks_arch_map_pointed_phys | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestMappedFflagsRead::test_wb_csr_write_and_fflags_write_same_cycle_both_land | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestMultiThread::test_write_tid0_does_not_affect_tid1 | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestOverwriteAndReset::test_overwrite_csr_returns_latest_value | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestOverwriteAndReset::test_reset_restores_misa_default | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestRead::test_read_misa_returns_default_after_reset | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestRead::test_read_uninitialized_csr_returns_zero | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestSStatusAlias::test_read_sstatus_returns_mstatus_view_after_reset | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestSStatusAlias::test_write_sstatus_sie_folds_into_mstatus | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestSStatusAlias::test_write_sstatus_zero_preserves_uxl_sxl | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_read_triggers_snapshot | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_reset_disables_all_triggers | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata1_load_and_store_triggers_round_trip | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata1_type2_round_trip | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata1_unsupported_type_disabled | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata2_write_and_read | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata3_write_and_read | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tdata_indirection_across_slots | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tinfo_readonly_value | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tselect_defaults_to_zero | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tselect_out_of_range_ignored | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestTriggerCSRs::test_tselect_write_and_read | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestWrite::test_write_rdy_false_when_pending | block-CSRFile | default | PASS | - | 0 |
| test_csr_file_cl.TestWrite::test_write_then_read_returns_value_after_tick | block-CSRFile | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC2CmdFanout::test_cc_201_fanout_to_both_targets | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC2CmdFanout::test_cc_202_fanout_verbatim_across_cmds | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC2CmdFanout::test_cc_203_slow_target_holds_its_dispatch | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC2CmdFanout::test_cc_204_one_command_at_a_time | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC2CmdFanout::test_cc_205_invalid_op_asserts[0] | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC2CmdFanout::test_cc_205_invalid_op_asserts[4] | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC2CmdFanout::test_cc_205_invalid_op_asserts[5] | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC2CmdFanout::test_cc_206_unaligned_line_addr_asserts | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC3AckAggregate::test_cc_301_aggregate_fires_after_both_acks | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC3AckAggregate::test_cc_302_late_ack_target_holds_aggregate | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC3AckAggregate::test_cc_303_aggregate_tag_echoes_command | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC3AckAggregate::test_cc_304_aggregate_fires_exactly_once | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC3AckAggregate::test_cc_305_aggregate_backpressure_blocks_completion | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC3AckAggregate::test_cc_306_wrong_tag_ack_asserts | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC3AckAggregate::test_cc_307_unsolicited_ack_asserts | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC4ResetAndInteraction::test_cc_401_reset_clears_inflight_cmd | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC4ResetAndInteraction::test_cc_402_reset_intake_rdy_asserts | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_cmd.TestCC4ResetAndInteraction::test_cc_403_evict_and_cmd_paths_are_independent | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_101_single_evict_forwarded_registered | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_102_forward_order_preserved | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_103_drain_rate_one_per_cycle | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_104_backpressure_holds_without_loss | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_105_intake_rdy_deasserts_and_recovers | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_106_exactly_once_no_duplicates | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_107_order_survives_intermittent_backpressure | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_108_unaligned_line_addr_asserts | block-CacheCtrl | default | PASS | - | 0 |
| test_cache_ctrl_release.TestCC1Release::test_cc_109_reset_drops_queued_releases | block-CacheCtrl | default | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_head_trap_dict_writes_tval_unconditionally | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_head_trap_dict_writes_zero_tval_classes | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_no_capable_fu_mce_follows_fault_path | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_rob_retire_ack_semantics | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_trap_count_init_trapLatency_not_minus_1 | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005BugFixes::test_trap_state_cleanup_after_trapSquash | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005M6OptionB::test_commit_derives_prev_phys_reg_via_m6_option_b | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005M6OptionB::test_commit_skips_free_when_allocated_new_false | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005M6OptionB::test_fip_drain_during_rob_squashing_full_bandwidth | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADR0005M6OptionB::test_fip_drain_during_running_strict_priority | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_cmt_fip_full_false_when_empty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_cmt_fip_full_when_fifo_full | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_fip_clear_on_superseding_squash | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_fip_fifo_depth_matches_spec | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestADRCompliance::test_has_stores_to_wb_prev_falling_edge | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestBackwardBus::test_bc_done_seqnum | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestBackwardBus::test_bc_free_rob_entries | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestBackwardBus::test_bc_squash_broadcast | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestCommitRequiresBBIdx::test_a_head_without_a_bb_idx_fails_the_run | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_can_handle_interrupts | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_commit_status_running | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_drain_flags | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_fip_fifo_empty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_pc | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_seqnums_zero | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestConstructionAndReset::test_reset_trap_flags | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_is_store_alone_does_not_trigger_serialize_after | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_is_store_alone_does_not_trigger_strictly_ordered | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_robhi_serialize_after_field_exists | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_robhi_strictly_ordered_field_exists | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_serialize_after_sets_pending_without_is_store | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_strictly_ordered_sets_bc_without_is_store | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestEmptyROB::test_empty_rob_four_way_conjunction | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFIPDrain::test_fip_commit_frees_have_priority | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFIPDrain::test_fip_drains_to_freelist | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFIPDrain::test_fip_writes_from_rename | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_fault_guard_met_triggers_trap | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_fault_guard_not_met_stalls | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_trap_countdown_multi_cycle | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_trap_fsm_to_rob_squashing | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_trap_sets_no_squash_from_tc | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFaultTrap::test_trap_sets_trap_pending | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFenceIFlushRaise::test_fence_i_squash_raises_exactly_one_flush | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFenceIFlushRaise::test_iew_squash_raises_no_flush | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFenceIFlushRaise::test_regular_store_retire_raises_no_flush | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFenceIFlushRaise::test_trap_squash_raises_no_flush | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFpDirtySideEffect::test_faulting_head_retire_no_fp_dirty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFpDirtySideEffect::test_fflags_dest_retire_fires_fp_dirty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFpDirtySideEffect::test_fp_dest_retire_fires_fp_dirty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFpDirtySideEffect::test_fp_op_fault_head_same_window_folds_fs_dirty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFpDirtySideEffect::test_int_dest_retire_no_fp_dirty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFpDirtySideEffect::test_no_dest_retire_no_fp_dirty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestFpDirtySideEffect::test_squashed_fp_op_no_fp_dirty | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_mispredict_sets_bc_mispredict_inst | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_squash_drives_rob_squash_req | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_squash_sets_bc_squash_inst | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_squash_too_young_ignored | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestIEWSquash::test_iew_squash_validates_age | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNonSpeculative::test_non_spec_broadcasts_seqnum | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNonSpeculative::test_non_spec_clears_can_commit | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNonSpeculative::test_non_spec_stalls_when_stores_pending | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNonSpeculative::test_strictly_ordered_load_sets_bc_flag | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_advances_pc | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_broadcasts_done_seqnum | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_frees_prev_phys_reg_to_freelist | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_multiple_up_to_width | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_no_dest_no_freelist_update | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_retires_rob_head | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_single_instruction | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_store_sets_committed_stores | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestNormalCommit::test_commit_updates_renamemap | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestResolveSuppressionKey::test_a_foreign_squash_suppresses_the_resolve | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestResolveSuppressionKey::test_the_branches_own_squash_does_not_suppress_its_resolve | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_backfill_skips_empty_rob_thread | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_backfill_skips_stalled_head | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_no_backfill_past_squashed_head | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_no_backfill_past_trap_head | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_round_robin_selection | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSMTArbitration::test_rr_pointer_rotates_across_cycles | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_a_plain_commit_does_not_drive_the_btb_level | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_drives_the_serialize_after_btb_level | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_phase1_commits | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_phase1_sets_pending | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_phase2_initiates_squash | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSquashAfter::test_squash_after_phase2_squashes | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSquashedHeadRetirement::test_squashed_head_no_arch_effect | block-Commit | default | PASS | - | 0 |
| test_commit_cl.TestSquashedHeadRetirement::test_squashed_head_silently_retired | block-Commit | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_dcache_va_probe_pa_caller_ifc_exists | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_dcache_va_probe_req_caller_ifc_exists | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_dcache_va_probe_resp_callee_ifc_exists | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_dtlb_ports_param_exists | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestADR0019Ports::test_no_pa_req_ports_on_dtlb_probe | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestDTLBResp::test_dtlb_fault_sends_result | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestDTLBResp::test_dtlb_hit_sets_paddr | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestDTLBResp::test_dtlb_miss_keeps_waiting | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestInterfaces::test_callee_ports_exist | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestInterfaces::test_caller_ports_exist | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestL1Probe::test_l1_hit_sends_result | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestL1Probe::test_l1_miss_sends_result_no_data | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_both_threads_independent | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_construct_accepts_max_threads_param | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_default_max_threads_is_one_backward_compat | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_tag_space_accommodates_total_entries | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_tag_space_asymmetric_sizes_uses_max | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_translate_req_tid0_uses_tag_in_lq_partition | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestMultiThread::test_translate_req_tid1_uses_tag_in_lq_partition | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestReset::test_after_reset_all_inactive | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestReset::test_after_reset_no_pending | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestTranslateReq::test_translate_req_processed_after_tick | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestTranslateReq::test_translate_req_sets_pending | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_cancel_leg_fires_on_dtlb_fault | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_cancel_leg_fires_on_miss_recovery | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_dtlb_miss_recovery_does_not_send_va_probe_pa | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_dtlb_miss_recovery_sends_translate_result_l1_hit_false | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_l1_cancelled_on_dtlb_fault | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_l1_cancelled_on_dtlb_miss | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_l1_response_ignored_after_cancellation | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_late_real_l1_response_after_cancel_is_dropped | block-DTLBProbe | default | PASS | - | 0 |
| test_dtlb_probe_cl.TestVIPTCancellation::test_translate_req_resets_l1_cancelled | block-DTLBProbe | default | PASS | - | 0 |
| test_decode_cl.TestBPUCorrectionSignals::test_bpu_correction_includes_tid_and_bb_idx | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestBPUCorrectionSignals::test_branch_mispredict_sets_both_squash_and_mispredict | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestBPUCorrectionSignals::test_commit_squash_suppresses_bpu_correction | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestBPUCorrectionSignals::test_control_miss_sets_bpu_squash_not_mispredict | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_backpressure_resume_flow | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_preload_buffer_absorbs_when_thread_not_selected | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_preload_buffer_full_fetch_sees_not_full_false | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_rename_stall_prevents_thread_selection | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestBackpressure::test_rename_unblock_allows_thread_selection | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_custom_params_construction | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_default_construction | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_dr_buffer_empty | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_fsm_state_all_idle | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_fsm_state_multi_thread | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_no_rename_stall | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_preload_buffer_empty | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_initial_rr_ptr_zero | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_reset_clears_all_state | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestConstructionAndReset::test_wrote_to_time_buffer_initially_false | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_dr_pop_interface | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_dr_tid_count_exposed | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_dr_tid_not_empty_exposed | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_dr_tid_not_full_exposed | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDRBufferInterface::test_rename_width_limits_pop | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeErrorHandling::test_decode1_typeerror_from_regid_construction_propagates | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeErrorHandling::test_decode2_keyerror_from_decode_inst_does_not_propagate | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeErrorHandling::test_decode2_typeerror_from_decode_inst_propagates | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_count_increments | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_flush_on_squash | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_multi_thread_isolation | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_not_empty | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_not_full | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_dr_buffer_shared_pool_capacity | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestDecodeRenameBuffer::test_push_instruction_to_dr_buffer | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_conditional_branch_correct_prediction | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_conditional_branch_mispredict | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_control_miss_corrected_pc_is_fallthrough | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_control_miss_predicted_taken_not_control | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_correct_prediction_no_squash | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_direct_branch_mispredict_jal_target_mismatch | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_drives_decode_bpu_correction | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_drives_decode_squash_to_fetch | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_flushes_dr_buffer | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_flushes_preload_buffer | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_sets_squashing_state | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_mispredict_squashing_to_running_next_cycle | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestEarlyMispredict::test_single_mispredict_per_cycle_per_thread | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestExtractMemSizeRVC::test_c_fld_is_8 | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestExtractMemSizeRVC::test_c_fldsp_is_8 | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestExtractMemSizeRVC::test_c_fsd_c_fsdsp_are_8 | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestExtractMemSizeRVC::test_non_memory_rvc_returns_0 | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_activity_flag_not_set_when_idle | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_activity_flag_set_on_decode | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_backpressure_resume_flow | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_branch_not_taken_correctly_predicted | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_early_mispredict_recovery_timeline | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_fetch_decode_rename_flow | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_full_flow_with_mispredict_and_recovery | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_is_active_when_running | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_is_active_when_squashing | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_jal_always_taken_mispredict | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_multi_cycle_decode_flow | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_multiple_instructions_decode_in_one_cycle | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_preload_buffer_bypass_same_cycle | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_smt_2_threads_interleaving | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestFullPipeline::test_squash_resume_flow | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_can_issue_set_when_num_src_regs_zero | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_addi_instruction | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_branch_instruction | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_dest_reg_idx_populated | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_jal_instruction | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_nop | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_decode_width_limit_respected | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestInstructionDecode::test_forward_f_fields_unchanged | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestNewFields::test_can_issue_false_for_nonzero_src_regs | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestNewFields::test_can_issue_true_for_zero_src_regs | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestNewFields::test_op_class_populated | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestNewFields::test_static_opcode_carries_machinst | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_accumulates_when_not_selected | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_count | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_flush_on_squash | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_multi_thread_isolation | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_not_empty | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_not_full | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_pop | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_preload_buffer_shared_pool_capacity | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBuffer::test_push_instruction_to_preload_buffer | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBufferExposed::test_preload_count_exposed | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBufferExposed::test_preload_not_empty_exposed | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPreloadBufferExposed::test_preload_not_full_exposed | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPullModel::test_fd_has_data_used_for_eligibility | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPullModel::test_tid_sel_set_on_thread_selection | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPullModel::test_tid_sel_valid_false_when_no_data | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestPullModel::test_tid_sel_with_multi_thread | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_commit_squash_flushes_buffers | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_commit_squash_multi_thread | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_commit_squash_priority_over_decode_mispredict | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_commit_squash_sets_squashing_state | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_squash_while_processing_instructions | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestSquashFromCommit::test_squashing_to_running_next_cycle | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestSquashedInstruction::test_all_squashed_no_output | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestSquashedInstruction::test_squashed_instruction_skipped | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_no_eligible_thread_no_selection | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_round_robin_across_2_threads | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_rr_pointer_advances_correctly | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_single_thread_always_selected | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_skip_thread_in_squashing_state | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_skip_thread_with_dr_buffer_full | block-Decode | default | PASS | - | 0 |
| test_decode_cl.TestThreadSelection::test_skip_thread_with_rename_stall | block-Decode | default | PASS | - | 0 |
| test_decode_continuity.TestStreamContinuity::test_cross_cycle_pair_fires_once_and_record_cleared | block-Decode | default | PASS | - | 0 |
| test_decode_continuity.TestStreamContinuity::test_fault_on_a_never_anchors_the_record | block-Decode | default | PASS | - | 0 |
| test_decode_continuity.TestStreamContinuity::test_fault_on_b_skips_the_check | block-Decode | default | PASS | - | 0 |
| test_decode_continuity.TestStreamContinuity::test_pred_taken_a_continuous_to_pred_pc_does_not_fire | block-Decode | default | PASS | - | 0 |
| test_decode_continuity.TestStreamContinuity::test_pred_taken_a_discontinuous_fires_at_pred_pc | block-Decode | default | PASS | - | 0 |
| test_decode_continuity.TestStreamContinuity::test_within_cycle_continuous_negative_control | block-Decode | default | PASS | - | 0 |
| test_decode_continuity.TestStreamContinuity::test_within_cycle_discontinuity_fires_case1_acts | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestCorrectionPayloadHasNoKcnt::test_case1_correction_payload_has_no_k_cnt | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestCorrectionPayloadHasNoKcnt::test_decode_bpu_correction_req_has_no_k_cnt_field | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestLeadingMemberTakenDetectedByCase2::test_case2_fires_for_an_interior_member | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestLeadingMemberTakenDetectedByCase2::test_leading_member_with_matching_fallthrough_is_not_case_2 | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestLeadingMemberTakenDetectedByCase2::test_nt_predicted_conditional_member_is_not_a_case2_candidate | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestMemberBtbMissStaysDead::test_btb_missed_conditional_member_produces_no_btb_miss_correction | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestMemberBtbMissStaysDead::test_member_carries_its_slot_and_bitmap_identity_to_decode | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestPredictedNotTakenLeadingMember::test_predicted_nt_leading_member_is_not_a_control_miss | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestPredictedNotTakenLeadingMember::test_predicted_nt_leading_member_with_live_bb_idx_is_not_a_control_miss | block-Decode | default | PASS | - | 0 |
| test_decode_v2_members.TestPredictedNotTakenLeadingMember::test_predicted_nt_member_still_reaches_rename | block-Decode | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_backpressure_then_ready_dispatches | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_iq_not_ready_skips_dispatch | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_iq_ready_dispatches_normally | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_lsq_load_not_ready_skips_dispatch | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_lsq_load_uses_caller_ifc_port | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_lsq_store_not_ready_skips_dispatch | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestBackpressure::test_lsq_store_uses_caller_ifc_port | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_has_op_class | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_has_phys_src_reg | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_has_seqnum | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_has_tid | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchInstField::test_iq_req_inst_is_not_none | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToIQ::test_dispatch_round_robin_across_threads | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToIQ::test_dispatch_sends_iq_dispatch_req | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToLSQ::test_load_dispatched_to_lsq | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToLSQ::test_lsq_indices_passed_to_iq_req | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestDispatchToLSQ::test_store_dispatched_to_lsq | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_fsm_running_after_squash_allows_dispatch | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_non_squashed_thread_dispatches_normally | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_squash_keeps_fsm_running | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_squash_prevents_dispatch_in_same_cycle | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestMemSizeValueRangeGate::test_cbo_size_64_passes_gate | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestMemSizeValueRangeGate::test_malformed_size_load_no_lsq_illegal_path | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestMemSizeValueRangeGate::test_malformed_size_store_no_lsq_illegal_path | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestRenameReceive::test_rename_buffers_into_fifo | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestRenameReceive::test_rename_rdy_when_fifo_not_full | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestReset::test_after_reset_fifos_empty | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestReset::test_after_reset_fsm_running | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestSquash::test_squash_discards_younger_entries | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestBatchedIQDispatch::test_iq_dispatch_returns_local_indices | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestBatchedIQDispatch::test_multiple_instructions_single_batched_call | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestBatchedIQDispatch::test_single_instruction_batched_call | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIQSetDependency::test_no_set_dependency_for_ready_source | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIQSetDependency::test_set_dependency_for_multiple_distinct_producers | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIQSetDependency::test_set_dependency_for_single_not_ready_source | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInstCarriesIQMetadata::test_inst_cluster_id_set | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInstCarriesIQMetadata::test_inst_iq_local_id_set | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInterfaceExistence::test_iq_set_dependency_port_exists | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInterfaceExistence::test_sb_get_producer_port_exists | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestInterfaceExistence::test_sb_set_producer_port_exists | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIntraBatchShadow::test_same_cycle_producer_resolved_via_shadow | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestIntraBatchShadow::test_shadow_populated_by_each_dest_reg | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestPendingSrcCount::test_pending_src_count_deduped | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestPendingSrcCount::test_pending_src_count_multiple_distinct_producers | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestPendingSrcCount::test_pending_src_count_one_for_single_producer | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestPendingSrcCount::test_pending_src_count_zero_for_ready_sources | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestProducerDedup::test_dedup_same_producer_two_slots | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestSetProducerOnDestRegs::test_set_producer_called_for_multiple_dests | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestSetProducerOnDestRegs::test_set_producer_called_for_single_dest | block-Dispatch | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl_adr0033.TestSetProducerOnDestRegs::test_set_producer_uses_cluster_base_for_global_id | block-Dispatch | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_bac_backward_ctrl_bus_round_trips_none_commit_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_bpu_update_req_round_trips_none_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_bpu_update_req_still_round_trips_a_real_index | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_decode_rename_inst_round_trips_none_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_fetch_decode_inst_round_trips_none_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_ftq_ctrl_insert_req_round_trips_none_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_per_thread_fetch_tick_req_round_trips_none_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_rename_inst_round_trips_none_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_rob_head_inst_round_trips_none_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_bb_idx_none_roundtrip::test_u8_raises_on_none | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestConcurrentOperations::test_concurrent_insert_pop | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestConcurrentOperations::test_concurrent_insert_squash | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_construct_custom | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_construct_default | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_initial_state | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_reset_clears_all | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_reset_initial_signals | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestConstructionAndReset::test_status_enum_values | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestControlSignalArbitration::test_squash_from_any_state | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_bb_idx_stored_in_sram | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_insert_after_squash | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_multiple_squashes | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_single_entry_queue | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestEdgeCases::test_wrap_around | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_end_address | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_has_exceeded | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_in_range | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_is_exit_branch | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_is_exit_inst | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_size | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestFTQEntryComputedProperties::test_entry_start_address | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewAndDeletedSurfaces::test_head_view_appears_on_the_commit_cycle | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewAndDeletedSurfaces::test_head_view_has_no_pending_state_after_a_pop | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewAndDeletedSurfaces::test_head_view_initially_absent_and_no_head_surface_exists | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewAndDeletedSurfaces::test_head_view_is_the_sm_chain_after_insert | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewOperations::test_head_ready_signal | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewOperations::test_head_view_correct_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewOperations::test_head_view_empty | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewOperations::test_head_view_invalid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewOperations::test_head_view_not_valid_after_pop | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestHeadViewOperations::test_head_view_returns_entry | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_bb_idx_forwarding | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_empty_makes_head_valid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_fields | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_full_fails | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_full_status | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_invalid_fails | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_multiple | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestInsertOperations::test_insert_single | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_advances_head | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_empties_queue | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_fifo_order | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_is_unconditional | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_leaves_no_bubble | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_leaves_no_refusal_state | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestPopHeadOperations::test_pop_head_no_head_raises_caller_bug | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestRecoveryTiming::test_bac_initiated_squash_recovery | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestRecoveryTiming::test_fetch_initiated_recovery | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestResetStateOperations::test_reset_state_clears_entries | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestResetStateOperations::test_reset_state_preserves_other_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestResetStateOperations::test_reset_state_sets_valid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_dequeue_correct_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_insert_rejected_when_invalid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_is_empty_per_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_is_full_per_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_per_thread_head_view | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_per_thread_status | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_reset_state_preserves_other_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSMTMultiThread::test_squash_preserves_other_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_clears_entries | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_deasserts_head_valid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_from_invalid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_preserves_other_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_preserves_other_thread_head_view | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_resets_pointers | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_sets_valid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestSquashOperations::test_squash_single_cycle | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_empty | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_empty_per_thread | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_full | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_head_ready | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_is_ready | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_num_free_entries | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl.TestStatusQueries::test_size | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_ftq_entry_has_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_ftq_entry_no_bpred_hist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_ftq_insert_req_has_ftq_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_ftq_insert_req_no_ftq_bpred_hist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_insert_bb_idx_forwarded_to_head | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_iter_entry_resp_has_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestBbIdxRename::test_iter_entry_resp_no_bpred_hist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestControlSignalPriority::test_squash_overrides_insert | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestForAllBackwardRemoved::test_for_all_backward_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestGetOldestBpuAnchorDeleted::test_the_getter_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestIsFullPerThread::test_is_full_accepts_tid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestIsFullPerThread::test_is_full_based_on_per_thread_count | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_attribute_exists | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_count_after_one_insert | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_has_per_thread_count | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_has_per_thread_head | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_has_per_thread_tail | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_head_initially_invalid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestPerThreadStorageManager::test_sm_head_valid_after_insert | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestRemovedMethods::test_get_count_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestRemovedMethods::test_get_status_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestRemovedMethods::test_unlock_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestResetStateNoReReadHead::test_reset_state_head_valid_unconditionally_false | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_alignment.TestResetStateNoReReadHead::test_reset_state_no_head_register_surface_exists | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestControlSignalPriorityChange::test_priority_is_reset_state_squash_pop_insert | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFSMEncodingChange::test_invalid_is_0 | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFSMEncodingChange::test_locked_attribute_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFSMEncodingChange::test_valid_is_1 | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFtSeqnumWidthRemoved::test_construct_does_not_accept_ft_seqnum_width | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFtSeqnumWidthRemoved::test_ft_seqnum_width_attribute_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFtSeqnumWidthRemoved::test_head_seqnum_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestFtqLockedSignalRemoved::test_is_locked_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestIsLockedMethodRemoved::test_is_locked_method_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockMethodRemoved::test_lock_method_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockMethodRemoved::test_pending_lock_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockedStateRemoved::test_ftq_status_never_value_2 | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockedStateRemoved::test_initial_status_is_valid | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestLockedStateRemoved::test_locked_attribute_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v2.TestMaxThreadsDefaultChange::test_default_max_threads_is_1 | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestAllNotTakenEdgeFt::test_fetchs_stop_and_jump_predicate_is_false_for_the_all_nt_ft | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestAllNotTakenEdgeFt::test_is_branch_with_a_zero_pred_target_is_storable_and_readable | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_end_pc_is_exclusive | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_returns_none_when_empty | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_returns_none_when_no_entry_covers_the_pc | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_returns_none_when_the_covering_entry_has_no_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBbIdxCoveringPc::test_returns_the_covering_entrys_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBrTypeEncodingIsTheLandedBranchType::test_a_return_record_consumes_no_target_slot_but_a_direct_cond_does | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestBrTypeEncodingIsTheLandedBranchType::test_btb_v2_type_constants_equal_the_landed_enum | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestDuplicateBbIdxIsLegal::test_no_bb_idx_keyed_lookup_dict_exists | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestDuplicateBbIdxIsLegal::test_two_fts_sharing_a_bb_idx_both_queue_and_read_back | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestDuplicateBbIdxIsLegal::test_window_fields_survive_the_sram_read_bubble_after_a_pop | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestNoBbIdxInheritance::test_a_bac_to_ftq_insert_also_does_not_inherit | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestNoBbIdxInheritance::test_a_branchless_ft_keeps_its_own_bb_idx | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestNoBbIdxInheritance::test_a_branchless_ft_that_omits_bb_idx_reads_back_zero | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestNoBbIdxInheritance::test_the_propagation_state_does_not_exist | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestPopRemovesTheHead::test_a_pop_may_pair_with_an_insert_in_the_same_cycle | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestPopRemovesTheHead::test_a_popped_ft_is_not_readable | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestSlotsValidIsAbsolutelyIndexed::test_all_sixteen_slots_valid_round_trips | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestSlotsValidIsAbsolutelyIndexed::test_all_sixteen_slots_valid_with_all_two_byte_members | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestSlotsValidIsAbsolutelyIndexed::test_an_ft_starting_mid_window_keeps_its_members_at_window_offsets | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestTakenTerminalNeedsATarget::test_a_taken_terminal_with_a_target_is_not_counted | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestTakenTerminalNeedsATarget::test_a_taken_terminal_without_a_target_is_counted | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestTakenTerminalNeedsATarget::test_an_all_not_taken_edge_with_no_target_is_not_counted | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestWindowFieldsRoundTrip::test_window_base_and_slots_valid_round_trip | block-FTQ | default | PASS | - | 0 |
| test_ftq_cl_spec_v3_window.TestWindowFieldsRoundTrip::test_window_fields_default_to_zero_when_a_stale_caller_omits_them | block-FTQ | default | PASS | - | 0 |
| test_ftq_full_pending.TestPendingInclusiveFullness::test_a_pending_insert_counts_as_full_before_the_edge | block-FTQ | default | PASS | - | 0 |
| test_ftq_full_pending.TestPendingInclusiveFullness::test_a_pending_pop_makes_room_only_after_it_applies | block-FTQ | default | PASS | - | 0 |
| test_ftq_full_pending.TestRefusedInsertVisibility::test_a_control_drop_is_not_counted_as_capacity_refusal | block-FTQ | default | PASS | - | 0 |
| test_ftq_full_pending.TestRefusedInsertVisibility::test_a_normal_fill_never_refuses | block-FTQ | default | PASS | - | 0 |
| test_ftq_full_pending.TestRefusedInsertVisibility::test_a_refused_insert_is_counted | block-FTQ | default | PASS | - | 0 |
| test_ftq_pops_suppressed_witness::test_pop_alone_is_applied_so_the_counter_read_is_not_vacuous | block-FTQ | default | PASS | - | 0 |
| test_ftq_pops_suppressed_witness::test_pop_and_squash_in_one_cycle_suppresses_the_pop | block-FTQ | default | PASS | - | 0 |
| test_ftq_pops_suppressed_witness::test_squash_then_pop_in_one_cycle_suppresses_the_pop | block-FTQ | default | PASS | - | 0 |
| test_ftq_sq_flush_getter::test_reset_state_does_not_record_a_flush | block-FTQ | default | PASS | - | 0 |
| test_ftq_sq_flush_getter::test_the_getter_returns_the_committed_squash_flush_record | block-FTQ | default | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_5_clusters_present | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_float_cluster_has_fpadd_fpmult_fpdiv | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_int_cluster_has_intalu_intmult_intdiv | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_max_op_latency_is_20 | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestClusterConfig::test_mem_cluster_has_address_calc_fu | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestCompletionTiming::test_1_cycle_op_completes_next_cycle | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFaultTvalStampingF1::test_ebreak_tval_is_fault_pc | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFaultTvalStampingF1::test_illegal_fault_info_carries_encoding | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFaultTvalStampingF1::test_illegal_tval_rvc_masked_to_16_bits | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFpCsrAccessFsOff::test_fcsr_family_access_with_fs_initial_is_clean | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFpCsrAccessFsOff::test_fcsr_family_access_with_fs_off_is_illegal | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFpCsrAccessFsOff::test_non_fp_csr_access_with_fs_off_is_clean | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFreeFU::test_freefu_is_noop_in_pipelined_model | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFuCompleteBundle::test_fu_complete_bundle_default_fields | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFuCompleteBundle::test_fu_complete_bundle_has_branch_mispredict | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFuCompleteBundle::test_fu_complete_bundle_no_trap_fields | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFuOperand::test_fu_operand_squashed_bypass_skips_compute | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestFuOperand::test_fu_operand_stores_result_in_pending_compute | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_float_cluster | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_mem_cluster | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_returns_fu_idx_for_supported_opclass | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_returns_no_capable_for_unsupported_opclass | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestGetUnit::test_getunit_returns_op_latency | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestMisalignedAtomicsC9::test_aligned_atomics_do_not_raise | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestMisalignedAtomicsC9::test_faulted_atomics_never_reach_lsq | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestMisalignedAtomicsC9::test_misaligned_amo_raises_store_access_fault | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestMisalignedAtomicsC9::test_misaligned_lr_raises_load_access_fault | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestMisalignedAtomicsC9::test_misaligned_sc_raises_store_access_fault | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestPerClusterState::test_per_cluster_in_flight_arrays_exist | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestPerClusterState::test_per_cluster_pipeline_arrays_exist | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestPerClusterState::test_pipeline_stages_sized_to_max_op_latency | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_end_to_end_add_compute_and_extract | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_end_to_end_add_through_fupool | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_end_to_end_fadds_through_fupool | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_real_add_instruction_category | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestPyisaIntegration::test_real_add_instruction_compute | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestReset::test_after_reset_all_pipelines_empty | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestReset::test_after_reset_rr_ptrs_zero | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestZfhHBox16::test_fcvt_h_w_result_nan_boxed_16bit | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestZfhHBox16::test_fmv_x_h_read_unbox_bad_box_is_canonical_hnan | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl.TestZfhHBox16::test_nan_box_fp_operand_width_rules | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestFuRealCompletePort::test_fu_real_complete_is_callable | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestFuRealCompletePort::test_fu_real_complete_port_exists | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestLDACompletionNoFuRealComplete::test_lda_does_not_fire_fu_real_complete_from_fupool | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestNormalCompletionFiresFuRealComplete::test_float_completion_fires_fu_real_complete | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestNormalCompletionFiresFuRealComplete::test_int_completion_fires_fu_real_complete | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestSTA_STDDecallocAtIssue::test_sta_does_not_fire_fu_real_complete_at_issue | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestSTA_STDDecallocAtIssue::test_std_does_not_fire_fu_real_complete_at_issue | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestSquashedFastPathQ12::test_squashed_does_not_wait_for_op_latency | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033.TestSquashedFastPathQ12::test_squashed_int_fires_fu_real_complete_same_cycle | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestNormalCompletionFiresSbSetReg::test_int_completion_fires_sb_setReg_for_single_dest | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestNormalCompletionFiresSbSetReg::test_multi_dest_completion_fires_sb_setReg_per_dest | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestSbSetRegInterface::test_sb_setReg_is_callable | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestSbSetRegInterface::test_sb_setReg_port_exists | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_primary.TestSquashedCompletionSuppressesSbSetReg::test_squashed_non_lda_completion_skips_sb_setReg | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteInterface::test_fu_early_complete_is_callable | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteInterface::test_fu_early_complete_port_exists | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteMemUopRouting::test_no_early_complete_for_lda | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteTiming::test_early_complete_fires_before_real_complete | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_speculation.TestFuEarlyCompleteTiming::test_early_complete_not_fired_for_squashed | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_squash_force_ack.TestSquashForceEarlyCompleteADR0033::test_fu_pool_exposes_ic_squash_port | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_squash_force_ack.TestSquashForceEarlyCompleteADR0033::test_ic_squash_is_callable | block-FUPool | default | PASS | - | 0 |
| test_fu_pool_cl_adr0033_squash_force_ack.TestSquashForceEarlyCompleteADR0033::test_squash_mid_flight_fires_force_early_complete | block-FUPool | default | PASS | - | 0 |
| test_fetch_cl.TestAssertionANoBBLeftUnmarked::test_rv64ui_p_add_leaves_no_bb_unmarked | block-Fetch | default | PASS | - | 7 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f320_bc_has_commit_info | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f321_bc_no_dec_to_fetch | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f323_bc_no_old_flat_arrays | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f324_bc_commit_info_per_thread | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f325_bc_no_dec_to_fetch_per_thread | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f327_bc_commit_info_squash_triggers_squash | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f328_decode_squash_to_fetch_triggers_squash | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f330_bc_commit_info_interrupt | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f331_bc_commit_info_clear_interrupt | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBackwardCtrlBusRestructure::test_f332_bc_to_dict_roundtrip | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBuildPerThreadTickReq::test_f90_builds_request | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBuildPerThreadTickReq::test_f91_includes_stall_flags | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestBuildPerThreadTickReq::test_f92_includes_interrupt_from_bc | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f300_commit_info_defaults | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f301_commit_info_squash_and_pc | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f302_commit_info_interrupt_flags | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f303_commit_info_to_dict | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestCommitInfo::test_f304_commit_info_from_dict | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestConstants::test_f70_invalid_thread_id | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestCountFetchingThreads::test_f80_zero_when_all_waiting | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestCountFetchingThreads::test_f81_one_when_running | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestCountFetchingThreads::test_f82_counts_eligible_states | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDesignParameters::test_f340_max_ft_per_cycle_exists | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDesignParameters::test_f341_max_ft_per_cycle_default | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDesignParameters::test_f342_max_taken_pred_per_cycle_exists | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDesignParameters::test_f343_max_taken_pred_per_cycle_default | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueues::test_f140_drain_assigns_seqnum | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueues::test_f141_drain_respects_decode_width | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueues::test_f142_drain_respects_decode_stall | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f160_no_drain_without_tid_sel_valid | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f161_drain_when_tid_sel_valid | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f162_all_insts_same_thread | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f163_drain_only_selected_thread | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f164_drain_respects_decode_width | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f165_drain_empty_selected_thread | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f166_per_thread_status_always_provided | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f167_drain_assigns_seqnum | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f168_no_drain_priority_counter | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestDrainFetchQueuesPullModel::test_f169_drain_respects_decode_stall_pull | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFTExitPreDecodeFacts::test_a_non_resident_control_transfer_at_the_ft_exit_is_a_branch | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFTExitPreDecodeFacts::test_a_plain_instruction_at_the_ft_exit_is_not_a_branch | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFTExitPreDecodeFacts::test_the_ft_prediction_is_exit_scoped | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFenceIFlushRaiseAtFetch::test_fence_i_beat_forwards_exactly_one_flush_req | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFenceIFlushRaiseAtFetch::test_non_fence_i_squash_and_plain_beats_raise_nothing | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFenceIFlushRaiseAtFetch::test_refused_flush_port_holds_the_raise_and_delivers_once | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFenceIFlushRaiseAtFetch::test_repeated_squash_signals_do_not_re_raise | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f10_custom_decode_width | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f1_default_construction | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f2_initial_seq_num_counter | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f3_initial_global_status_inactive | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f4_initial_per_thread_components | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f5_initial_priority_list | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f6_initial_stalls_clear | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f7_initial_num_inst_zero | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f8_custom_max_threads | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestFetchCLConstruction::test_f9_custom_fetch_width | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f30_single_thread_running | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f31_single_thread_idle | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f32_no_eligible_thread | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f33_round_robin_rotation | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f34_eligible_states | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestGetFetchingThread::test_f35_ineligible_states | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestHeldIcacheRequestClear::test_a_commit_squash_of_another_thread_keeps_the_hold | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestHeldIcacheRequestClear::test_a_squash_of_the_naming_thread_clears_the_hold | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestHeldIcacheRequestClear::test_a_squash_of_the_naming_thread_frees_the_unsent_entry | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestNoCacheLineSurfaceOnTheResponse::test_nothing_in_the_model_writes_a_cache_line_field_any_more | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestNoCacheLineSurfaceOnTheResponse::test_the_response_has_no_cache_line_fields | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestResetClear::test_f50_reset_stage | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestResetClear::test_f51_reset_stage_per_thread | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestResetClear::test_f52_clear_states | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestResetClear::test_f53_clear_states_preserves_other_threads | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestResteerLegIsDeleted::test_fetch_has_no_resteer_ports | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestResteerLegIsDeleted::test_per_thread_fetch_has_no_resteering_state | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestResteerLegIsDeleted::test_the_resteer_message_module_is_gone | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestResteerLegIsDeleted::test_the_tick_response_carries_no_resteer_fields | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSequenceNumber::test_f11_first_seq_is_one | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSequenceNumber::test_f12_seq_monotonically_increasing | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSequenceNumber::test_f13_seq_counter_increments | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSequenceNumber::test_f14_seq_shared_across_threads | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSignalRenames::test_f200_fetch_to_decode_has_fd_tid_count | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSignalRenames::test_f201_fetch_to_decode_no_fq_count | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSignalRenames::test_f202_fetch_to_decode_no_fq_not_empty | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSignalRenames::test_f203_fetch_to_decode_no_fq_not_full | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f100_commit_squash_calls_do_squash | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f101_decode_squash_calls_do_squash | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f102_trap_pending_sets_flag | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f103_decode_block_removed | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f104_decode_unblock_removed | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f105_commit_squash_priority_over_decode | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f106_squash_redirects_pc | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f107_squash_clears_fetch_queue | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestSquashAtFetchCL::test_f108_squash_sets_delayed_commit | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestStallFlags::test_f20_stall_flags_initial | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestStallFlags::test_f21_stall_flags_set_decode | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestUpdateFetchStatus::test_f40_active_when_running | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestUpdateFetchStatus::test_f41_active_when_icache_access_complete | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestUpdateFetchStatus::test_f42_inactive_when_all_idle | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestUpdateFetchStatus::test_f43_active_when_all_squashing | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestWakeFromQuiesce::test_f60_wake_sets_running | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestWakeFromQuiesce::test_f61_wake_adds_to_priority_list | block-Fetch | default | PASS | - | 0 |
| test_fetch_cl.TestWakeFromQuiesce::test_f62_wake_no_duplicate_in_priority | block-Fetch | default | PASS | - | 0 |
| test_fetch_icache_ifc_roundtrip::test_a_full_cache_line_survives_the_response_round_trip | block-Fetch | default | PASS | - | 0 |
| test_fetch_icache_ifc_roundtrip::test_the_line_width_is_the_cache_block_and_not_sixty_four_bits | block-Fetch | default | PASS | - | 0 |
| test_fetch_icache_ifc_roundtrip::test_the_request_still_carries_only_address_and_transaction_identity | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCAbstraction::test_a_sealed_assembly_stalls_without_abandoning | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCAbstraction::test_the_forward_pass_over_of_a_range_marks_the_slot_used | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCAbstraction::test_the_straddle_completing_the_look_ahead_marks_BOTH_slots_used | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_an_empty_slot_holds_no_valid_information | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_c_is_per_cycle_and_is_cleared_by_the_tick_not_by_the_edge | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_no_cycle_ever_performs_two_fills[C-C-True-False-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_no_cycle_ever_performs_two_fills[C-E-True-False-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_no_cycle_ever_performs_two_fills[C-V-False-True-True-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_no_cycle_ever_performs_two_fills[E-E-True-False-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_no_cycle_ever_performs_two_fills[E-V-True-False-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_no_cycle_ever_performs_two_fills[V-E-False-True-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_no_cycle_ever_performs_two_fills[V-V-False-False-False-0] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_the_case_table_selects_exactly_one_act[C-C-True-False-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_the_case_table_selects_exactly_one_act[C-E-True-False-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_the_case_table_selects_exactly_one_act[C-V-False-True-True-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_the_case_table_selects_exactly_one_act[E-E-True-False-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_the_case_table_selects_exactly_one_act[E-V-True-False-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_the_case_table_selects_exactly_one_act[V-E-False-True-False-1] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestCaseTable::test_the_case_table_selects_exactly_one_act[V-V-False-False-False-0] | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestOnlySquashForcesEmpty::test_do_squash_forces_both_slots_empty_with_their_payload | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestRule4ThePointerIsThePosition::test_a_look_ahead_with_granules_left_continues_at_its_second_granule | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestRule4ThePointerIsThePosition::test_a_spent_look_ahead_seats_the_fill_not_a_jump | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestRule4ThePointerIsThePosition::test_a_taken_spent_look_ahead_seats_the_same_way | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestRule5Isolation::test_a_staged_target_is_not_coverage | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheFetchFaultSeal::test_a_fetch_fault_seals_and_a_squash_unseals | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheFetchFaultSeal::test_an_ialign_fault_seals_at_the_first_misaligned_position | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheFetchFaultSeal::test_no_fault_never_seals | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheFillIsTheOnlyPop::test_a_stalled_walk_still_fills_and_pops_at_the_end_of_the_cycle | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheFillIsTheOnlyPop::test_consumption_leaves_the_slot_valid_until_the_edge_decides | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheFillIsTheOnlyPop::test_the_walk_consumes_a_stage_and_touches_the_queue_never_again | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheSeatingLaw::test_a_shift_re_seats_a_target_the_assembly_never_entered | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheSeatingLaw::test_a_shift_translates_only_a_target_the_assembly_has_entered | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_d14_two_slot_fill.TestTheSeatingLaw::test_the_fill_seats_the_pointer_at_the_targets_own_first_granule | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestAbandonUnsentTopSlot::test_abandoning_the_top_slot_returns_it_to_the_free_list | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestDeliveryIsOrdered::test_a_discarded_entry_never_delivers_although_it_still_names_an_ft | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestDeliveryIsOrdered::test_a_later_fts_response_fills_no_stage | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestDeliveryIsOrdered::test_a_response_fills_no_stage_and_the_fill_loads_positionally_and_pops | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestEntryNamesItsFetchTarget::test_a_delivered_entry_names_its_target_until_its_target_is_released | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestEntryNamesItsFetchTarget::test_a_fetch_target_stamp_cannot_be_repointed | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestEntryNamesItsFetchTarget::test_a_prefetch_entry_names_the_ft_the_cursor_named | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestEntryNamesItsFetchTarget::test_no_entry_is_allocated_without_a_target_presented | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestEntryNamesItsFetchTarget::test_the_stamp_is_bound_in_the_cycle_the_request_was_made | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestLedgerIsAWorkingCopy::test_a_second_allocation_in_one_cycle_gets_its_own_index | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestLedgerIsAWorkingCopy::test_occupancy_and_the_free_list_move_together_at_the_release | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestStageIdentity::test_a_re_formed_target_over_the_same_range_keeps_the_stage_usable | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_ft_stamped_pdb.TestStageIdentity::test_a_stage_the_assembly_has_walked_off_is_abandoned_not_assembled | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_geometry::test_a_window_wider_than_the_cache_line_is_refused_at_construction | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_geometry::test_the_derivation_is_the_next_power_of_two_of_a_full_dispatch_group | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_geometry::test_the_window_is_the_dispatch_width_derived_not_four_literals | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestBlockedPortRefusal::test_blocked_precedes_the_squash_rearm_logic | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestBlockedPortRefusal::test_blocked_tick_allocates_nothing_and_advances_nothing | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestBlockedPortRefusal::test_unblocked_tick_still_grants | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestNoFetchSideCoalescing::test_the_request_names_the_window_the_fetch_target_starts_in | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestNoFetchSideCoalescing::test_two_fetch_targets_naming_one_line_yield_two_requests | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestOneClaimPerFetchTarget::test_two_presentations_of_one_target_are_two_grants_only_if_both_are_seated | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestOneRequester::test_a_presented_cursor_is_asked_for_and_the_ledger_names_its_target | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestOneRequester::test_a_request_allocates_and_consumes_the_cursor_in_one_cycle | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestOneRequester::test_a_stage_holding_the_windows_bytes_does_not_stop_the_ask | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestOneRequester::test_a_vetoed_request_leaves_the_cursor_in_place | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestOneRequester::test_an_unpresented_cursor_asks_for_nothing | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestOneRequester::test_the_walk_never_asks_for_bytes_itself | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestPrefetchBufferBound::test_the_buffer_holds_its_full_entry_count | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_peek_requester.TestPrefetchBufferBound::test_txn_id_zero_is_never_issued | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_stage_handover.TestStageHandover::test_a_real_miss_still_ends_the_cycle_with_one_request | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_stage_handover.TestStageHandover::test_the_look_aheads_target_shifts_into_the_assembly_without_a_pop | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_stage_handover.TestStageHandover::test_the_target_end_outranks_the_bytes_in_hand | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestAbsoluteSlotIndex::test_member_absent_from_slots_valid_is_not_a_member | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestAbsoluteSlotIndex::test_member_at_absolute_slot_5_of_the_window | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestAttachedFactsAndKcntAbsence::test_bb_idx_is_attached_to_every_instruction_including_members | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestAttachedFactsAndKcntAbsence::test_no_k_cnt_field_exists_anywhere | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestAttachedFactsAndKcntAbsence::test_no_k_cnt_on_the_fetch_tick_request_or_response | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestDownstreamTerminalInference::test_a_non_branch_instruction_carries_its_bb_idx_to_the_rob | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestDownstreamTerminalInference::test_an_interior_member_carries_its_bb_idx_to_the_rob | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestDownstreamTerminalInference::test_the_rob_carries_no_terminal_bit_at_all | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestFTExitFactsForBranchlessAndMemberFTs::test_all_nt_member_ft_edge_is_fetched_and_not_taken | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestFTExitFactsForBranchlessAndMemberFTs::test_branchless_ft_exit_is_not_a_branch | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestIsExitGeTest::test_an_instruction_overrunning_the_ft_end_waits_for_the_look_ahead | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestIsExitGeTest::test_no_instruction_after_the_crossing_exit_is_fetched | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestIsExitGeTest::test_the_look_ahead_completes_the_crossing_instruction_with_its_own_row | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestPredictionStaysExitScoped::test_interior_member_does_not_inherit_the_ft_prediction | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestStopAndJumpV2::test_all_nt_edge_ft_finishes_the_target_and_chooses_no_position | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestStopAndJumpV2::test_taken_terminal_seats_the_successor_instead_of_jumping_to_the_target | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestStraddleGranuleZeroIsKeyedByTheBase::test_a_mid_window_successor_waits_and_the_same_call_emits_at_the_key | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestTerminalIsStatedByTheProducer::test_a_no_terminal_view_selects_no_exit_at_all | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestTerminalIsStatedByTheProducer::test_the_deleted_assembly_side_demotion_is_now_the_producers_law | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestTerminalIsStatedByTheProducer::test_the_exit_is_the_stated_slot_and_not_the_end_address | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestTerminalIsStatedByTheProducer::test_the_kind_carries_the_direction_and_the_slot_only_the_position | block-Fetch | default | PASS | - | 0 |
| test_fetch_v2_window.TestTerminalIsStatedByTheProducer::test_the_same_stamp_with_the_producers_own_slot_marks_one_exit | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt60_build_inst_creates_dyninst | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt61_build_inst_sets_pc | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt62_build_inst_sets_pred_pc | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt63_build_inst_sets_tid | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt64_build_inst_pushes_to_queue | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt65_build_inst_with_fault | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt66_drain_fetch_queue_empty | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt67_drain_fetch_queue_partial | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt68_drain_fetch_queue_full | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestBuildInstAndDrain::test_pt69_drain_preserves_order | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestCheckSignalsPriority::test_pt110_trap_pending_overrides_running | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestCheckSignalsPriority::test_pt112_squashing_to_running | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt11_initial_stages_are_empty | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt12_initial_empty_fetch_queue | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt14_custom_tid | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt15_custom_fetch_width | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt16_custom_fetch_queue_size | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt1_default_construction | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt2_initial_status_idle | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt3_initial_pc_zero | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt4_initial_fetch_offset_zero | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt5_initial_buffer_invalid | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt8_initial_no_delayed_commit | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestConstruction::test_pt9_initial_no_fault_pending | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDecodeErrorHandling::test_keyerror_from_decoder_does_not_propagate | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDecodeErrorHandling::test_typeerror_from_decoder_propagates | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_no_assembly_position_survives_a_squash | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt50_squash_unseats_the_pointer | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt51_squash_resets_fetch_offset | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt54_squash_sets_squashing_status | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt55_squash_clears_fetch_queue | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt56_squash_sets_delayed_commit | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestDoSquash::test_pt58_squash_invalidates_buffer | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt30_running_value | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt31_idle_value | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt32_squashing_value | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt34_trap_pending_value | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt35_quiesce_pending_value | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt39_icache_access_complete_value | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt40_ftq_wait_is_deleted | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt41_no_good_addr_is_retired | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestFetchStatus::test_pt42_no_fetching_state | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt140_align_to_buffer | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt141_buffer_hit_valid | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt142_buffer_hit_invalid | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt143_buffer_hit_miss | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestInternalHelpers::test_pt144_num_insts_derived | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsBranchFromFetch::test_pt320_ft_level_branch_fact_rides_the_stage_stamp | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsBranchFromFetch::test_pt321_is_branch_default_false_without_ftq | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsDrained::test_pt70_drained_initially | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsDrained::test_pt71_not_drained_with_queue | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestIsDrained::test_pt72_not_drained_with_fault_pending | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestLatchState::test_pt120_latch_status | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestLatchState::test_pt121_latch_pointer | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestLatchState::test_pt122_fetch_offset_is_a_view | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestLatchState::test_pt123_latch_buffer_valid | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestPopHasNoFailureVocabulary::test_pt300_pop_head_response_type_is_gone | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestPopHasNoFailureVocabulary::test_pt310_tick_resp_has_no_clear_head_history | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestQuiescePending::test_pt281_quiesce_pending_no_fetch | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestQuiescePending::test_pt282_quiesce_pending_exits_on_squash | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt20_reset_stage | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt21_clear_states | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt22_clear_states_preserves_status | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt23_clear_states_preserves_position | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestResetClearStates::test_pt24_clear_states_preserves_fetch_queue | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSetters::test_pt90_set_interrupt_pending | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSetters::test_pt91_set_trap_pending | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt201_squash_clears_fault_pending | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt204_trap_pending_in_tick | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt205_trap_pending_cleared_after_tick | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt206_interrupt_pending_blocks_fetch | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt207_interrupt_with_delayed_commit | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestSquashHandling::test_pt212_squashing_delayed_commit_cleared | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt100_tick_idle_no_op | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt102_tick_running_with_valid_buffer | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt103_tick_icache_access_complete | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestTickBasic::test_pt104_tick_squashing_no_fetch | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestWakeFromQuiesce::test_pt80_wake_sets_running | block-Fetch | default | PASS | - | 0 |
| test_per_thread_fetch_cl.TestWakeFromQuiesce::test_pt81_wake_updates_pending_status | block-Fetch | default | PASS | - | 0 |
| test_frontend_v2_compose.TestCallerIcacheRequestHold::test_a_refused_request_survives_and_is_sent_with_the_same_txn | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestCallerIcacheRequestHold::test_a_squash_clears_the_held_request | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposedPathStall::test_case2_fires_and_destroys_fetchs_assembly_position | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposedPathStall::test_frontend_recovers_from_a_flushed_stream | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposedPathStall::test_mismatched_target_is_a_real_mispredict | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposedPathStall::test_the_frontend_keeps_making_progress_after_the_redirect | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_bb_idx_reaches_decode_to_rename | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_fetch_advances_past_the_first_ft | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_fetch_stamps_the_bpu_row_index | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_frontend_v2_children_are_wired | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_frontend_v2_constructs_and_resets | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_ft_flows_bac_ftq_fetch_decode | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_ftq_head_bb_idx_comes_from_the_bpu_row_allocator | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestComposition::test_the_path_does_not_park_before_the_end_of_the_run | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestScheduleSeedSweep::test_identical_outcomes_across_schedule_seeds | block-FrontEnd | default | PASS | - | 1 |
| test_frontend_v2_compose.TestScheduleSeedSweep::test_sweep_reaches_a_formed_ft | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestWindowAttach::test_member_bitmap_is_absolute_not_ft_relative | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_compose.TestWindowAttach::test_member_instruction_gets_absolute_slot | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_finalize_level_edge.TestFinalizeLevelEdge::test_the_edge_alone_orders_the_driver_ahead_of_the_finalize | block-FrontEnd | default | PASS | - | 0 |
| test_frontend_v2_finalize_level_edge.TestFinalizeLevelEdge::test_the_level_stalls_the_finalize_of_its_own_cycle_at_every_seed | block-FrontEnd | default | PASS | - | 4 |
| test_frontend_v2_finalize_level_edge.TestFinalizeLevelEdge::test_the_scenario_is_not_vacuous_without_the_level | block-FrontEnd | default | PASS | - | 1 |
| test_icache_cl.TestBackpressure::test_i51_ready_after_reset | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestBackpressure::test_i52_not_ready_when_mshr_full | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestBackpressure::test_i53_ready_after_mshr_freed | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i11_single_hit | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i12_multiple_hits_same_cycle | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i13_hit_updates_plru | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i14_hit_does_not_allocate_mshr | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheHit::test_i15_miss_after_hit_line_invalidated | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i16_miss_allocates_mshr | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i17_miss_issues_memory_request | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i18_fill_completes_miss | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i19_fill_writes_cache | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestCacheMissFill::test_i20_miss_frees_mshr_after_fill | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i36_itlb_miss_allocates_ptw_mshr | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i37_itlb_late_response_retrys_miss | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i38_itlb_late_fault_responds | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i39_itlb_late_perm_denied | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestExternalITLBMiss::test_i40_ptw_then_fill | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i41_flush_all_invalidates_everything | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i42_flush_all_ack | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i43_flush_by_va_invalidates_match | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i44_flush_by_va_preserves_unrelated | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestFlush::test_i45_flush_by_range | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i0_default_construction | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i10_custom_mshr_config | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i2_derived_parameters | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i3_initial_tag_array_invalid | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i4_initial_plru_zero | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i5_initial_mshr_free | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i6_initial_response_queue_empty | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i7_initial_asid_zero | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i8_initial_flush_inactive | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestICacheConstruction::test_i9_custom_cache_size | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestITLBFault::test_i31_translation_fault_response | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestITLBFault::test_i32_permission_denied_no_execute | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestITLBFault::test_i33_fault_does_not_allocate_mshr | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestITLBFault::test_i34_hit_permission_denied | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i61_fetch_request_port | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i62_fetch_response_port | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i63_itlb_ports | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i64_memory_ports | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestInterface::test_i65_flush_ports | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestMSHRCoalescing::test_i26_two_requests_same_line_coalesce | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestMSHRCoalescing::test_i27_coalesced_waiters_both_respond | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestMSHRCoalescing::test_i28_different_lines_allocate_separate_mshrs | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestMSHRCoalescing::test_i29_coalesce_only_same_line | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestMemoryError::test_i56_memory_error_fault | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestMemoryError::test_i57_memory_error_frees_mshr | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestMemoryError::test_i58_memory_error_does_not_fill_cache | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestPLRU::test_i46_plru_replace_initial | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestPLRU::test_i47_plru_replace_after_access | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestPLRU::test_i48_fill_uses_plru_victim | block-ICache | default | PASS | - | 0 |
| test_icache_cl.TestPLRU::test_i49_plru_updates_on_fill | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestRequestValidity::test_a_request_that_is_not_an_aligned_window_of_the_line_is_refused[4096-128-wider than the line] | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestRequestValidity::test_a_request_that_is_not_an_aligned_window_of_the_line_is_refused[4096-24-not a power of two] | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestRequestValidity::test_a_request_that_is_not_an_aligned_window_of_the_line_is_refused[4098-32-not window-aligned] | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestSizedHit::test_a_line_request_still_returns_the_whole_line | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestSizedHit::test_a_window_request_on_the_second_half_returns_the_upper_window | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestSizedHit::test_a_window_request_returns_the_lower_window_of_a_hit_line | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestSizedMiss::test_the_memory_fill_answers_with_the_window_not_the_line | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestSizedMiss::test_the_mshr_remembers_the_width_it_was_asked_for | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read.TestSizedMiss::test_two_widths_for_one_line_do_not_share_an_mshr | block-ICache | default | PASS | - | 0 |
| test_icache_v2_sized_read::test_the_memory_interface_names_no_fetch_target | block-ICache | default | PASS | - | 0 |
| test_icache_v2_cl.TestBackpressure::test_mshr_full_deasserts_req_ready_and_reasserts_after_a_fill | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestBackpressure::test_twb_full_deasserts_req_ready_and_reasserts_when_it_drains | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestCoalescing::test_different_widths_do_not_coalesce | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestCoalescing::test_same_line_same_width_coalesces_to_one_fetch_with_own_windows | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFaults::test_execute_perm_denied_is_fault_1 | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFaults::test_memory_error_faults_all_coalesced_waiters_and_frees_the_mshr | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFaults::test_translation_fault_is_mcause12_at_the_vaddr_without_mshr | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFlush::test_type0_invalidates_everything | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFlush::test_type1_flush_translation_carries_the_vm_context | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFlush::test_type1_invalidates_only_the_matching_ptag_way | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFlush::test_type2_range_invalidates_only_pages_in_the_range | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFlushVsInFlightFill::test_fill_that_postdates_the_flush_still_installs | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestFlushVsInFlightFill::test_fill_that_predates_a_flush_answers_but_never_installs | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestGeometry::test_index_plus_offset_beyond_page_offset_is_refused | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestGeometry::test_the_boundary_configuration_is_accepted | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestHitWindow::test_hit_returns_the_lower_window_too | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestHitWindow::test_hit_returns_the_requested_window_in_two_cycles | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestIntakeSlotsAndReset::test_a_full_intake_slot_deasserts_ready | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestIntakeSlotsAndReset::test_reset_clears_every_piece_of_state | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestInvalidPresentationAndReservedTxnId::test_reserved_flush_txn_id_is_rejected_on_the_fetch_path | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestInvalidPresentationAndReservedTxnId::test_valid0_fetch_is_not_a_request | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestInvalidPresentationAndReservedTxnId::test_valid0_flush_does_not_lock_the_port | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestMissFillPhysTag::test_miss_fetches_the_full_line_and_answers_with_the_window | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestMissFillPhysTag::test_synonym_va_hits_the_filled_line_and_other_ptag_misses | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestPLRU::test_fill_victim_order_is_plru | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestParkAndReLookup::test_late_translation_parks_and_relookup_sees_the_fill | block-ICacheV2 | default | PASS | - | 0 |
| test_icache_v2_cl.TestParkAndReLookup::test_out_of_order_translations_are_matched_by_txn_id | block-ICacheV2 | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestBranchClusterWiring::test_branch_cluster_has_dedicated_fus | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestBranchClusterWiring::test_branch_cluster_wires_are_connected | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRFileIntegration::test_csr_file_is_csr_file_cl_instance | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRFileIntegration::test_csr_file_uses_iew_max_threads | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRFileIntegration::test_iew_exposes_csr_file_sub_component | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringReadOperand::test_all_five_read_operand_clusters_have_csr_read_wired | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringReadOperand::test_csr_read_returns_misa_default | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringReadOperand::test_csr_read_returns_zero_for_uninitialized_csr | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringWriteBack::test_wb_csr_write_committed_to_csr_file_after_tick | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestCSRWiringWriteBack::test_wb_csr_write_rdy_follows_csr_file_write_rdy | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EFloatCluster::test_fadd_s_completes_through_float_cluster | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIcSquashFunctional::test_ic_squash_clears_iq_entries | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIcSquashFunctional::test_ic_squash_clears_lsq_load_entry | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIntCluster::test_add_completes_through_int_cluster | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIntCluster::test_addi_imm_completes_through_int_cluster | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2ELoadMemoryPath::test_load_completes_through_memory_path | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMemClusterFUExecution::test_mem_cluster_wires_fire_on_load | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMemLoadPath::test_load_inserts_into_lsq_and_mem_iq | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMemLoadPath::test_load_routes_to_mem_iq_not_int_iq | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMispredictToCommit::test_beq_mispredict_fires_iew_to_commit | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EMispredictToCommit::test_mispredict_per_thread_isolation | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureAmoAddWord::test_amo_add_creates_sq_but_not_lq | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureBackToBackIntMultSingleFU::test_two_intmult_ops_both_complete | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureBackwardBusFreeEntries::test_free_iq_entries_decrease_after_dispatch | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureBackwardBusIewBlock::test_iew_block_and_unblock | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureBranchClusterFUExecution::test_beq_through_branch_cluster_wires_fire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureCSRWrite::test_csrrw_fires_wb_csr_write | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureCommitLoadsPath::test_commit_loads_frees_lq_entry | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureCsrWriteFullSignals::test_csrrw_wb_csr_write_all_signals | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureDependentInstructions::test_dependent_adds_raw_bypass | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureDirectCompletePath::test_faulted_lw_fires_direct_complete | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFaultPreExecPath::test_pre_exec_fault_fires_wb_fault | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFaultTranslationPath::test_load_translation_fault_fires_wb_fault | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFenceExecution::test_nonSpecInstReady_clears_sq_placeholder_non_spec | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFencePassThrough::test_fence_complete_alias_removed | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureFuAllocNoContentionModel::test_two_mul_ops_both_complete_no_contention | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureIcSquashFunctional::test_squashed_add_issues_with_squashed_flag | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureIqFullBackpressure::test_iq_full_rdy_returns_false | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureLSQLoadPath::test_lw_load_path_fires_dtlb_req | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureLSQStorePath::test_sw_store_path_fires_dtlb_req | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureLoadDataReturnPath::test_load_data_flows_through_lsq_execute_resp | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureLsqInsertRdyGap::test_insert_load_rdy_always_true | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMemClusterWiresFunctional::test_lw_through_mem_cluster_wires_fire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMemViolationToCommit::test_mem_violation_fires_iew_to_commit | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMispredictToCommit::test_beq_taken_pred_not_taken_fires_iew_to_commit | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMispredictToCommit::test_bne_not_taken_pred_taken_fires_iew_to_commit | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureMispredictToCommit::test_jal_unconditional_pred_not_taken_fires_iew_to_commit | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureNonSpecInstReady::test_non_spec_inst_ready_clears_sq_entry | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSCFailurePath::test_sc_fails_when_reservation_not_set | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSCPath::test_lr_then_sc_succeeds_with_reservation | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSRETFault::test_sret_u_mode_fires_wb_fault | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSnoopInv::test_snoop_inv_reissues_inflight_load | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSplitLoadPath::test_split_load_issues_two_dcache_reqs | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashDuringFuCompute::test_fadd_squash_mid_compute_suppresses_rf_write | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashDuringLsqExecute::test_load_squash_in_lsq_suppresses_rf_write | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashEffect::test_add_squash_before_issue_suppresses_rf_write | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashEffect::test_intmult_squash_mid_flight_suppresses_rf_write | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashThreadIsolation::test_squash_tid0_isolates_tid1 | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureStoreDTLBFullSignals::test_store_dtlb_req_all_signals | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureStrictlyOrderedLoadReplay::test_strictly_ordered_load_polls_then_issues_after_commit | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureTLBIInv::test_tlbi_inv_marks_lq_entries_stale | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureTLBMissDefer::test_dtlb_miss_defers_load_then_reissue | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureTwoIndependentInstructions::test_two_independent_adds_both_complete | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureTwoThreadConcurrentDispatch::test_two_thread_adds_both_complete | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureViolationAck::test_violation_ack_clears_sticky_flag | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureViolationBeatsMispredict::test_violation_beats_mispredict_same_cycle | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureWawOrdering::test_waw_both_writeback_in_order | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureWbFaultFullSignals::test_sret_wb_fault_all_signals | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EStoreMemoryPath::test_store_pa_req_fires_with_correct_signals | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EStorePath::test_store_inserts_into_lsq_and_mem_iq | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVAProbePath::test_dcache_va_probe_resp_accepted | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVAProbePath::test_va_probe_pa_fires_on_dtlb_hit | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVAProbePath::test_va_probe_req_fires_with_load | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVectorCluster::test_vector_op_routes_to_vector_iq | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EVectorClusterFUExecution::test_vector_fu_executes_and_writes_vec_reg | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EWbCsrWritePath::test_csrrw_fires_through_pipeline | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EWbFaultPath::test_ecall_faults_through_pipeline | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EWbRobUpdateFullSignals::test_rob_update_carries_all_9_signals | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EWbRobUpdateFullSignals::test_sb_setreg_fires_with_correct_phys_reg | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_bc_iew_squash_clears_pending_in_parent | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_bc_iew_squash_per_thread_isolation | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_bc_iew_squash_propagates_to_writeback_pending | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_writeback_ic_squash_signature_is_tid_seqnum | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_dispatch_to_iq_iq_dispatch_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_dispatch_to_lsq_insert_load_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_dispatch_to_lsq_insert_store_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_fupool_to_writeback_fu_complete_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_ic_squash_fanout_to_all_sub_blocks | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_iq_to_readoperand_int_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_lsq_to_writeback_execute_resp_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_float_to_fupool_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_float_to_physregfile_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_float_to_writeback_issued_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_mem_to_writeback_direct_complete_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_to_fupool_int_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_to_physregfile_int_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestInterSubBlockInterfaces::test_readoperand_to_writeback_issued_wire | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestStructuralBackwardBusWiring::test_bc_ports_exist_and_wired | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl::test_violation_push_sink_to_mempending | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl::test_violation_queue_multi_entry_oldest_first | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestBypassQueryWiringADR0033Primary::test_all_five_ro_bypass_query_wired_to_write_back | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestBypassQueryWiringADR0033Primary::test_bypass_query_returns_hit_when_completion_pending | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestSbSetRegWiringADR0033Primary::test_fu_pool_sb_setReg_propagates_to_scoreboard | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestSbSetRegWiringADR0033Primary::test_lsq_sb_setReg_propagates_to_scoreboard | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestSbSetRegWiringADR0033Primary::test_scoreboard_has_wb_set_req_from_lsq_port | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_primary.TestSbSetRegWiringADR0033Primary::test_write_back_has_no_sb_setReg_caller | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_speculation.TestSpeculationWiringADR0033::test_fu_pool_fu_early_complete_wired_to_iq | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_speculation.TestSpeculationWiringADR0033::test_iq_has_fu_early_complete_from_lsq_port | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_speculation.TestSpeculationWiringADR0033::test_lsq_fu_early_complete_wired_to_iq_from_lsq | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl_adr0033_speculation.TestSpeculationWiringADR0033::test_lsq_fu_nack_wired_to_iq | block-IEW | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl.TestReset::test_after_reset_no_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestAddConsumer::test_add_consumer_accumulates_bits | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestAddConsumer::test_add_consumer_idempotent_same_bit | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestAddConsumer::test_add_consumer_rdy_when_producer_valid | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestAddConsumer::test_add_consumer_sets_bit_in_consumer_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_empty_list | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_entries_committed_after_tick | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_rdy_checks_capacity | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_rdy_true_when_enough_space | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_returns_local_indices | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestEntryFields::test_entry_fields_initialized_to_zero | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestEntryFields::test_entry_has_adr0033_fields_after_dispatch | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_broadcasts_consumer_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_sets_acked_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_snapshots_last_ack_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuEarlyComplete::test_fu_real_complete_after_early_complete_only_broadcasts_unacked | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuNack::test_fu_nack_broadcasts_last_ack_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuNack::test_fu_nack_clears_acked_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuNack::test_fu_nack_uses_last_ack_mask_not_current | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_broadcasts_wakeup_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_deallocates_entry | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_excludes_acked_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestIssuedField::test_fu_real_complete_clears_issued_field | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestIssuedField::test_issued_entry_does_not_block_younger_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestIssuedField::test_ready_entry_marked_issued_not_deallocated | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestIssuedField::test_select_skips_issued_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLazySquash::test_squashed_unready_entry_stays_in_iq | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLazySquash::test_sre_shadow_dispatching_state_not_squashed | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLazySquash::test_sre_shadow_squashing_state_detected | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLegacyRemoved::test_pending_wakeup_dests_attribute_removed | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLegacyRemoved::test_state_depend_graph_attribute_removed | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLegacyRemoved::test_wb_wake_destreg_attribute_removed | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbNack::test_wb_nack_increments_pending_src_count | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbNack::test_wb_nack_only_affects_matching_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_decrements_pending_src_count | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_no_match_leaves_unchanged | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_only_affects_matching_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_sets_all_srcs_ready_when_count_reaches_zero | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_empty_list_returns_empty | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_mixed_ops_returns_indices_per_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_multiple_int_reqs_one_cluster_call | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_branch_op_to_branch_iq | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_float_op_to_float_iq | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_int_op_to_int_iq | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_mem_load_to_mem_iq | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_routes_vector_op_to_vector_iq | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBroadcastNackFanout::test_broadcast_nack_fanout_calls_all_5_clusters | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBroadcastWakeupFanout::test_broadcast_wakeup_fanout_calls_all_5_clusters | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestBroadcastWakeupFanout::test_int_iq_fu_real_complete_broadcasts_to_all_clusters | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_branch_iq_cluster_base_is_36 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_float_iq_cluster_base_is_44 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_int_iq_cluster_base_is_0 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_mem_iq_cluster_base_is_24 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestClusterBase::test_vector_iq_cluster_base_is_56 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuEarlyCompleteNackRouting::test_fu_early_complete_routes_to_int_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuEarlyCompleteNackRouting::test_fu_early_complete_routes_to_mem_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuEarlyCompleteNackRouting::test_fu_nack_routes_to_int_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_branch_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_float_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_int_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_mem_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestFuRealCompleteRouting::test_fu_real_complete_routes_to_vector_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIcSquashBroadcast::test_ic_squash_broadcasts_to_all_clusters | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_branch_port_exists | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_float_port_exists | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_int_port_exists | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_mem_port_exists | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqIssuePortsExported::test_iq_issue_vector_port_exists | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqSetDependency::test_iq_set_dependency_routes_to_float_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqSetDependency::test_iq_set_dependency_routes_to_int_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestIqSetDependency::test_iq_set_dependency_routes_to_mem_cluster | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestLegacyRemoved::test_no_iq_dispatch_default_attribute | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestLegacyRemoved::test_no_pending_overflow_attribute | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestLegacyRemoved::test_no_up_drain_overflow_attribute | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_iq_cl_adr0033.TestLegacyRemoved::test_no_wb_wake_destreg_attribute | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestAddConsumer::test_add_consumer_accumulates_bits | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestAddConsumer::test_add_consumer_idempotent_same_bit | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestAddConsumer::test_add_consumer_rdy_when_producer_valid | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestAddConsumer::test_add_consumer_sets_bit_in_lda_consumer_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_empty_list | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_entries_committed_after_tick | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_load_creates_lda_entry | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_load_returns_one_index | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_rdy_true_when_two_slots_free | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_store_creates_sta_and_std_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_store_needs_two_free_slots | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_store_returns_one_index | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestBatchedDispatch::test_batched_dispatch_two_loads_returns_two_indices | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestEntryFields::test_lda_entry_fields_initialized_to_zero | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestEntryFields::test_lda_entry_has_adr0033_fields_after_dispatch | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestEntryFields::test_sta_entry_has_adr0033_fields_after_dispatch | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_broadcasts_consumer_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_sets_acked_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuEarlyComplete::test_fu_early_complete_snapshots_last_ack_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuEarlyComplete::test_fu_real_complete_after_early_complete_only_broadcasts_unacked | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuNack::test_fu_nack_broadcasts_last_ack_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuNack::test_fu_nack_clears_acked_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuNack::test_fu_nack_uses_last_ack_mask_not_current | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_broadcasts_wakeup_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_deallocates_lda_entry | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestFuRealComplete::test_fu_real_complete_excludes_acked_mask | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_fu_real_complete_clears_issued_field_lda | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_fu_real_complete_on_sta_std_is_noop | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_lda_marked_issued_not_deallocated_at_issue | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_select_skips_issued_lda_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_sta_deallocated_at_issue | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestIssuedField::test_std_deallocated_at_issue | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLazySquash::test_squashed_unready_lda_entry_stays_in_iq | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLazySquash::test_sre_shadow_dispatching_state_not_squashed | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLazySquash::test_sre_shadow_squashing_state_detected | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLegacyRemoved::test_pending_wakeup_dests_attribute_removed | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLegacyRemoved::test_state_depend_graph_attribute_removed | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLegacyRemoved::test_wb_wake_destreg_attribute_removed | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbNack::test_wb_nack_increments_pending_src_count | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbNack::test_wb_nack_only_affects_matching_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_decrements_pending_src_count | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_no_match_leaves_unchanged | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_only_affects_matching_entries | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestWbWakeup::test_wb_wakeup_sets_all_srcs_ready_when_count_reaches_zero | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_branch_is_36 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_float_is_44 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_branch | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_float | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_int | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_mem | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_for_vector | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_int_is_0 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_mem_is_24 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_unknown_raises | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_cluster_base_vector_is_56 | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_dispatch_cl_has_no_local_cluster_base_dict | block-IQ | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_params_cluster_base::test_iq_cl_has_no_local_cluster_base_constants | block-IQ | default | PASS | - | 0 |
| test_itlb_cl.TestITLBASID::test_t4_asid_mismatch_and_global | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBConstruction::test_reset_state | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBConstruction::test_resp_queue_size_precondition | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBEviction::test_t5_lru_eviction_order | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBHit::test_t2_hit_paddr_perm_and_lru_update | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBIdentity::test_t1_identity_satp_mode0 | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBIdentity::test_t1_m_mode_fetch_is_bare | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBIdentity::test_t1_two_stage_non_goal_identity | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBInvalidate::test_t10_pulse_retired_port_is_gone | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBOutOfOrder::test_t7_reverse_completion_txn_matched | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBOutOfOrder::test_t8_slow_walk_does_not_block_hit | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBOutOfOrder::test_t9_queued_misses_no_lost_requests | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBPostReset::test_post_reset_state_is_clean | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBRespQueueFull::test_respq_full_parks_walk_result | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBSuperpage::test_superpage_level1_leaf | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBSuperpage::test_superpage_level2_leaf | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBWalk::test_t3_walk_fill_then_hit | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBWalkFault::test_t6_walk_failure_fault12 | block-ITLB | default | PASS | - | 0 |
| test_itlb_cl.TestITLBWalkQueueFull::test_walkq_full_holds_request | block-ITLB | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD10Geometry::test_ld_1001_no_alias_geometry_raises | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD10Geometry::test_ld_1002_default_geometry_constructs | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD10Geometry::test_ld_1003_l2_lat_below_l1_lat_raises | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD10Geometry::test_ld_1004_reset_state_all_invalid_all_ready | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD10Geometry::test_ld_1005_multi_write_port_rejected | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD13Invariants::test_ld_1301_mixed_traffic_invariant_counters | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_701_ctrl_cmd_inval_invalidates_ack_notify | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_702_ctrl_cmd_flush_same_as_inval | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_703_ctrl_cmd_clean_is_noop | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_704_ctrl_cmd_absent_line_completes_no_notify | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_705_store_channel_inval | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_706_store_channel_flush | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_707_store_channel_clean_noop | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_708_store_channel_zero_absorbs | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_709_same_cycle_refill_suppressed_by_cbo | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD7Cbo::test_ld_710_refresh_push_suppressed_line_invalidated | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD8Evict::test_ld_801_plru_victim_evict_notify_clean_drop | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD8Evict::test_ld_802_refresh_push_emits_no_notify | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD9Backpressure::test_ld_901_resp_fifo_full_backpressures | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD9Backpressure::test_ld_902_refill_push_backpressure | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cbo_evict.TestLD9Backpressure::test_ld_903_lsq_resp_stall_holds_fifo_no_loss | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD11Probe::test_ld_1101_probe_hit_word_extraction | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD11Probe::test_ld_1102_probe_miss | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD11Probe::test_ld_1103_probe_staged_refill_forwarding | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD11Probe::test_ld_1104_pa_leg_memory_type_meaningful | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD11Probe::test_ld_1105_probe_key_mismatch_asserts | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD11Probe::test_ld_1106_probe_hits_do_not_touch_plru | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD11Probe::test_ld_1107_cancel_frees_track_and_synthesizes_abort | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD11Probe::test_ld_1108_cancel_releases_probe_track_slot | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD12Fault::test_ld_1201_load_fault_verbatim | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD12Fault::test_ld_1202_nc_store_fault_verbatim | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD12Fault::test_ld_1203_hit_paths_never_fault | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD12Fault::test_ld_1204_cacheable_store_fault_is_zero | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD1LoadHit::test_ld_101_load_hit_response_at_accept_plus_1 | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD1LoadHit::test_ld_102_load_hit_size_offset_extraction | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD1LoadHit::test_ld_103_load_hit_no_pl2_traffic_and_frag_echo | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD2LoadMiss::test_ld_201_load_miss_forwarded_want_refill | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD2LoadMiss::test_ld_202_miss_response_relayed_with_span_echo | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD2LoadMiss::test_ld_203_refill_push_allocates_later_load_hits | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD2LoadMiss::test_ld_204_no_allocation_at_miss | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD2LoadMiss::test_ld_205_push_after_phase_a_commits_its_own_line | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD3StoreHit::test_ld_301_store_absorbed_completion_before_pl2_traffic | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD3StoreHit::test_ld_302_load_hit_sees_freshest_view | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD3StoreHit::test_ld_303_store_completes_at_absorb_not_pl2_resp | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD4StoreMiss::test_ld_401_miss_absorbed_no_array_write_drain_beat | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD4StoreMiss::test_ld_402_later_push_cannot_clobber_buffered_bytes | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD5PushStoreRace::test_ld_501_push_same_cycle_store_overlay_at_commit | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD5PushStoreRace::test_ld_502_push_same_cycle_load_sees_buffered_bytes | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD5PushStoreRace::test_ld_503_push_same_cycle_probe_sees_staged_data | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD5PushStoreRace::test_ld_504_stale_fill_cannot_bypass_buffered_writes | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD5PushStoreRace::test_ld_505_store_to_victim_line_dies_with_victim | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD6NCIO::test_ld_601_nc_load_never_cached | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_cl.TestLD6NCIO::test_ld_602_io_store_pass_through | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_peek.TestL1DPeek::test_peek_absorb_writes_no_array_until_drain | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_peek.TestL1DPeek::test_peek_freshness_order_l1d_before_pl2 | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_peek.TestL1DPeek::test_peek_hit_and_miss | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_peek.TestL1DPeek::test_peek_is_read_only | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_peek.TestL1DPeek::test_peek_staged_refill_same_cycle_store_overlay | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_peek.TestL1DPeek::test_peek_staged_refill_visible | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestFreeDrainOrder::test_free_drain_younger_entry_may_overtake_older | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT14MergeOrder::test_t14_live_entry_never_replaced | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT14MergeOrder::test_t14_same_line_stores_one_entry_later_wins | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT15Forwarding::test_t15_half_buffer_half_array_word_on_load_hit | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT15Forwarding::test_t15_load_miss_response_overlay_over_stale_fill | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT15Forwarding::test_t15_peek_overlay_matrix | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT15Forwarding::test_t15_probe_word_overlay_and_hit_rule | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT16OrderedNcGate::test_t16_barrier_entry_drains_only_when_oldest | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT16OrderedNcGate::test_t16_nc_oneshot_waits_for_older_entries | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT17CmoPreReaction::test_t17_clean_drains_entry_first_no_evict | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT17CmoPreReaction::test_t17_ctrl_cmd_inval_drops_entry | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT17CmoPreReaction::test_t17_flush_drains_entry_first | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT17CmoPreReaction::test_t17_inval_drops_entry_no_writeback | block-L1DCache | default | PASS | - | 0 |
| test_l1dcache_sbuf.TestT18Backpressure::test_t18_full_deasserts_rdy_never_drops | block-L1DCache | default | PASS | - | 0 |
| test_lq_core_cl.TestADR0019Ports::test_dcache_load_pa_req_caller_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestADR0019Ports::test_dcache_load_pa_req_fires_on_translated | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestADR0019Ports::test_dcache_req_removed | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_advances_head | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_all_entries | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_callee_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_no_entries_above_threshold | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_per_thread | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestCommitLoads::test_commit_loads_pops_head_entries_with_seqnum_le_threshold | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDCacheResp::test_dcache_resp_completes_load | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_callee_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_decrements_pending_producers | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_does_not_decrement_below_zero | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_passes_sq_idx_and_bitvector | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_skips_non_matching_lq_idx | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_dependents_update_unstalls_when_counter_reaches_zero | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_insert_clears_pending_producers | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_load_gated_when_pending_producers_positive | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_load_not_gated_when_pending_producers_zero | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_lq_entry_has_pending_producers_field | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDependentsUpdate::test_multiple_producers_require_multiple_broadcasts | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDesignBComputeAgeKey::test_all_loads_older_than_store_no_violation | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDesignBComputeAgeKey::test_committed_store_rescan_distance_beyond_sqsize | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestDesignBComputeAgeKey::test_oldest_younger_wins_and_older_load_excluded | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestFSMTranslated::test_dcache_req_caller_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestFSMTranslated::test_translated_to_waiting_resp | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestFSMTranslated::test_waiting_resp_to_complete_on_dcache_resp | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestFlhNaNBox16::test_flh_float_dest_nan_boxed | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestFlhNaNBox16::test_lh_int_dest_not_boxed | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestInsert::test_insert_adds_entry | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestInterfaces::test_callee_ports_exist | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestInterfaces::test_caller_ports_exist | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_completion_no_violation_without_flag | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_completion_no_violation_without_overlap | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_completion_scans_older_entries | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_on_load_violation_dropped_if_already_valid | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_load_on_load_violation_sticky_until_ack | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_possible_load_violation_flag_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_cache_block_aligned_overlap | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_callee_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_no_match_no_flag | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_sets_possible_load_violation | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_skips_completed_loads | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestLoadOnLoadViolation::test_snoop_inv_skips_untranslated_loads | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_construct_accepts_max_threads_param | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_default_max_threads_is_one_backward_compat | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_insert_tid0_uses_partition0 | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_insert_tid1_uses_partition1 | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestMultiThreadInsert::test_violation_state_per_thread | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_full_forward_does_not_stall | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_no_forward_does_not_stall | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_partial_forward_sets_stalled_flag | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_store_complete_notify_callee_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_store_complete_notify_does_not_unstall_non_matching | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_store_complete_notify_unstalls_matching_load | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestPartialForwardingStall::test_unstalled_load_reruns_stage_b_forward | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestReset::test_after_reset_all_empty | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestReset::test_after_reset_fsm_idle | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSetPhysAddr::test_set_phys_addr_sets_eff_addr_valid | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_clears_ll_sc_reservation_on_is_lr | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_no_dtlb_retrigger | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_reissues_dcache_load_pa_req | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_skips_completed_loads | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_skips_non_overlapping | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSnoopReExec::test_snoop_reexec_tso_force_squash_younger_loads | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitSnoopScan::test_snoop_hit_frag0_only_triggers_reexec | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitSnoopScan::test_snoop_hit_frag1_only_triggers_reexec | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitSnoopScan::test_snoop_no_hit_no_reexec | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitSnoopScan::test_split_snoop_reexec_reissues_both_fragments | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_both_responses_merge_and_complete | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_frag0_response_stored_separately | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_frag1_response_stored_separately | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_fragment_flags_reset_after_merge | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_lq_entry_has_frag0_fields | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_lq_entry_has_frag1_fields | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_merge_order_independent | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_non_split_load_issues_single_dcache_request | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_partial_fault_frag0_priority | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_partial_fault_frag1_when_frag0_ok | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_split_load_issues_two_dcache_requests | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestSplitUnalignedDCacheAccess::test_split_load_sets_waiting_split_resp_fsm | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrdered::test_strictly_ordered_flag_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrdered::test_strictly_ordered_insert | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_normal_load_not_at_head_proceeds | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_at_head_proceeds | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_not_at_head_polls_internally | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_not_at_head_visible_to_snoop | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_not_at_head_visible_to_violation | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestStrictlyOrderedLoad::test_strictly_ordered_polls_internally | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_has_stale_method_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_has_stale_per_thread | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_has_stale_returns_false_when_no_stale_entries | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_has_stale_returns_true_when_stale_entries_exist | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_lq_entry_has_stale_translation_field | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_lq_entry_has_vaddr_field | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_non_stale_entry_does_not_trigger_translate_req | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_stale_amo_lq_half_retranslates_store_typed | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_stale_entry_triggers_translate_req | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_stale_flag_cleared_on_dcache_resp | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_stale_lr_retranslates_load_typed | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_callee_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_is_per_thread | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_marks_inflight_entry_stale | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_skips_completed_loads | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_tlbi_inv_skips_untranslated_loads | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestTLBIStaleRetranslation::test_translate_req_caller_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestViolationCheck::test_no_violation_on_different_addr | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestViolationCheck::test_violation_detected_on_overlap | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestViolationPayload::test_violation_ack_callee_ifc_exists | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestViolationPayload::test_violation_dropped_if_already_valid | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl.TestViolationPayload::test_violation_sticky_until_ack | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_execute_load_pushes_to_l1_shift_register | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_l1_shift_register_default_depth_matches_params | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_l1_shift_register_depth_is_l1_lat_minus_iss_lat | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_l1_shift_register_pop_fires_fu_early_complete | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_l1_shift_register_release_after_pop | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l1_shift_reg.TestL1SpeculationShiftRegisterADR0033::test_lq_core_exposes_l1_shift_register_state | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_default_depth_matches_params | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_depth_is_l2_lat_minus_iss_lat | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_pop_fires_fu_early_complete | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_push_persists_payload | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_l2_shift_register_release_after_pop | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_adr0033_l2_shift_reg.TestL2SpeculationShiftRegisterADR0033::test_lq_core_exposes_l2_shift_register_state | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_f33_shift_cancel_ordering.TestF33ShiftCancelOrdering::test_l1_shift_pop_silent_on_completion_cancel | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_f33_shift_cancel_ordering.TestF33ShiftCancelOrdering::test_l2_shift_pop_silent_on_completion_cancel | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_g10_frag.TestG10SameCycleDCacheFragMerge::test_same_cycle_frag0_then_frag1_merges_once | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_g10_frag.TestG10SameCycleDCacheFragMerge::test_same_cycle_frag1_then_frag0_merges_once | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_g10_frag.TestG10SameCycleDCacheFragMerge::test_same_cycle_merge_fault_prefers_frag0 | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_g10_frag.TestG10SameCycleDTLBPeerFrag::test_same_cycle_peer_frag_fault_on_frag0 | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_g10_frag.TestG10SameCycleDTLBPeerFrag::test_same_cycle_peer_frag_fault_on_frag1 | block-LQCore | default | PASS | - | 0 |
| test_lq_core_cl_g10_frag.TestG10SameCycleDTLBPeerFrag::test_same_cycle_peer_frag_upgrades_pending_to_ok | block-LQCore | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0017::test_store_set_violation_fires_on_violation_detection | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0017::test_violation_signal_still_fires | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_active_placeholder_holds_younger_load_positionally | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_aq_disable_barrier_releases_held_load | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_disabled_placeholder_not_counted_by_dispatch_walk | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_fence_placeholder_is_commit_gated_and_stores_nothing | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_insert_load_no_longer_accepts_is_fence_load_kwarg | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_insert_store_accepts_is_fence_store_and_barrier_kwargs | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_lq_entry_has_no_is_fence_load_field | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_no_barrier_entries_no_hold | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_no_fence_complete_chain_anywhere | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_no_separate_barrier_sets_or_insert_fence | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_placeholder_commit_marks_completed_and_clears_barrier | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_sq_entry_has_is_fence_store_and_barrier_fields | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_amo_lq_forwards_from_different_seqnum_store | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_amo_lq_skips_own_sq_goes_to_dcache | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_is_atomic_defaults_false_on_lq_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_is_atomic_field_set_on_lq_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestAmoLqSqPair::test_normal_load_stalls_on_amo_sq | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestC3AmoTranslateTyping::test_amo_lq_half_requests_store_amo_translation | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestC3AmoTranslateTyping::test_amo_readonly_fault_no_partial_result | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestC3AmoTranslateTyping::test_lr_requests_load_translation | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestC3AmoTranslateTyping::test_sc_sta_requests_store_translation | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestCommitLoads::test_commit_loads_callee_ifc_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestCommitLoads::test_commit_loads_pops_lq_head_entries | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_dependents_broadcast_wired_to_dependents_update | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_end_to_end_load_stalls_until_producer_executes | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_insert_load_no_producer_leaves_pending_producers_zero | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_insert_load_sets_dependents_bit_on_producer_sq_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_insert_load_sets_pending_producers_when_producer_predicted | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_squash_clears_dependents_on_sq_entries | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDependentLoadsIntegration::test_squash_clears_pending_producers_on_lq_entries | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_free_lq_entries_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_free_lq_entries_when_empty | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_free_sq_entries_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestDrainStatus::test_has_stores_to_wb_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_execute_store_unified_removed | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_forward_query_waiting_data_registers_dependency | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_no_data_zero_forwarding_in_waiting_data | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_sq_entry_has_data_valid_field | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_sta_sets_fsm_to_waiting_data | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_std_arrival_unstalls_dependent_load | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_std_before_sta | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration.TestSTA_STD_StoreDecomposition::test_std_transitions_waiting_data_to_executed | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_atomic_amo_lq_sq_pair | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_cbo_as_store_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_commit_loads_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_data_prefetch_skip_cam | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_dcache_resp_batch_drain | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_dcache_resp_fifo | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_dtlb_port_arbitration | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_fence_barrier_gating | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_fence_full_barrier_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_ignored_responses_counter | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_ll_sc_reservation_set_path | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_ll_sc_success | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_load_on_load_violation_tso_force_squash_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_lsq_dep_check_shift | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_multi_thread_independent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_multi_thread_smoke | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_non_spec_gating | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_predicated_false_fast_path | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_sc_failure_fast_complete | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_simple_load_completion | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_simple_store_completion | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_snoop_lr_clears_reservation_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_snoop_reexec_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_split_load_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_split_store_non_forwardable_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_split_store_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_squash_and_replay | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_squashed_bypass | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_store_backpressure_retry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_store_forwarding_to_load | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_storeset_prediction_full_cycle | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_strictly_ordered_internal_poll | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_tlbi_empty_immediate_sync | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_tlbi_full_flow | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_violation_ack_handshake_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_violation_flow | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_vipt_speculative_l1_load_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_zero_size_store_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoad::test_exec_load_processed_after_tick | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoad::test_exec_load_sets_pending | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_combined_insert_then_execute_load_preserves_size_vaddr | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_combined_insert_then_execute_store_preserves_size_vaddr_data | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_load_does_not_allocate | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_load_preserves_dispatch_fields | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_load_writes_vaddr_size_to_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_store_does_not_allocate | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteLoadStoreRefined::test_execute_store_writes_vaddr_size_data_to_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestExecuteStore::test_exec_store_sets_pending | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestGap1SingleGenerationRecord::test_newer_echo_not_dropped_by_generation_tie | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestGap1SingleGenerationRecord::test_split_frag_squash_interleave_keeps_creation_era | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestGap1SingleGenerationRecord::test_strictly_older_echo_dropped_untouched | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_load_populates_dispatch_fields | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_load_returns_one_second | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_load_returns_zero_first | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_load_tid_partition | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_store_populates_dispatch_fields | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInsertLoadStore::test_insert_store_returns_zero_first | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInterfaces::test_external_callee_ports_exist | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInterfaces::test_external_caller_ports_exist | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestInterfaces::test_stale_interfaces_removed | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestLLSCWiring::test_clear_reservation_callee_ifc_exists_on_sq_store | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestLLSCWiring::test_ll_sc_clear_reservation_wired_in_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_construct_accepts_max_threads_param | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_default_max_threads_is_one_backward_compat | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_exec_load_tid0_allocates_in_partition0 | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_exec_load_tid1_allocates_in_partition1 | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_free_lq_entries_per_thread | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_free_sq_entries_per_thread | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_squash_tid0_does_not_invalidate_tid1 | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_state_lq_alloc_is_per_thread_array | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_state_sq_alloc_is_per_thread_array | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestMultiThread::test_subblocks_get_max_threads | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_check_inst_returns_3_tuple | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_check_inst_returns_ssid_after_violation_only | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_check_inst_returns_valid_after_store_dispatch | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_end_to_end_dependent_loads_setup_via_n1 | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_insert_store_stores_ssid_on_sq_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_populate_lfst_fires_at_dispatch | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_populate_lfst_fires_for_non_spec_then_clear_lfst_at_translation | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_populate_lfst_fires_once_at_dispatch | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN1IssueStoreWiring::test_sq_entry_has_ssid_field | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_execute_load_no_longer_takes_size_or_is_lr | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_execute_store_no_longer_takes_size | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_insert_load_mem_size_defaults_to_zero | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_insert_load_takes_mem_size_and_is_lr | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_insert_store_is_sc_defaults_to_false | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_insert_store_takes_mem_size_and_is_sc | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestN2DecodeInfoAtInsert::test_sc_fast_complete_path_via_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_active_placeholder_holds_younger_load | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_aq_load_execute_disables_placeholder | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_disable_barrier_ifc_exists_fence_complete_removed | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_disabled_placeholder_transparent_to_new_loads | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_insert_store_non_atomic_has_non_spec_false | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_no_placeholder_no_hold | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_nonSpecInstReady_callee_ifc_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_nonSpecInstReady_clears_sq_non_spec | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_commit_drains_storesToWB_accounting | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_commit_releases_held_load | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_squash_invalidates_like_any_sq_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_younger_load_proceeds_at_execute_while_held | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestNonSpeculativeHandling::test_younger_store_not_execute_gated_commit_order_release | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_lq_tag_forwards_to_lq_core | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_frag0_tag_calls_store_complete | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_frag1_tag_calls_store_complete_is_frag1 | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_dcache_resp_sq_tag_reads_tid_from_sq_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestParentDcacheResp::test_parent_dcache_resp_callee_ifc_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_execute_load_rdy_false_when_all_slots_full | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_execute_load_rdy_when_all_slots_free | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_existing_single_load_still_works | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_first_free_slot_reused_after_tick | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_ports_capacity | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_slot_dict_fields | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_under_active_barrier_executes_first_cycle | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_multiple_loads_accepted_per_cycle | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_multiple_stores_accepted_per_cycle | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestPerPortExecuteArrays::test_squashed_bypass_multiple_ports | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestReset::test_after_reset_alloc_zero | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestReset::test_after_reset_no_pending | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitAccess::test_split_field_exists_on_lq | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitAccess::test_split_field_exists_on_sq | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitFragmentCompletion::test_both_frags_complete_marks_eff_addr_valid | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitFragmentCompletion::test_frag0_translate_sets_frag0_valid_only | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitFragmentCompletion::test_frag1_then_frag0_also_completes | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitFragmentCompletion::test_frag1_translate_sets_frag1_valid_only | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitStore::test_non_split_store_has_none_split | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitStore::test_split_store_both_frags_complete | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitStore::test_split_store_crossing_page_boundary | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitStore::test_split_store_issues_two_dtlb_requests | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_non_split_load_has_none_split | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_non_split_load_issues_single_dtlb_request | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_split_field_exists_on_lq_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_split_load_crossing_page_boundary | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSplitUnaligned::test_split_load_issues_two_dtlb_requests | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashHandling::test_ic_squash_callee_ifc_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashHandling::test_squash_invalidates_lq_entries | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_load_bypass | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_load_does_not_set_eff_addr_valid | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_load_entry_freed_by_squash_walk | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_store_bypass | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSquashedBypass::test_squashed_store_does_not_set_canWB | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_update_next_cycle_false_after_reset | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_update_next_cycle_false_when_no_store_popped | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestStatusSignalsM2::test_update_next_cycle_true_when_store_popped | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestStoreCommit::test_commit_stores_forwards_to_sq_store | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestStoreSetIntegration::test_insert_load_calls_check_inst | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestStoreSetIntegration::test_store_set_subblock_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestStoreSetIntegration::test_violation_trains_store_set | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSubBlocks::test_dtlb_probe_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSubBlocks::test_lq_core_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestSubBlocks::test_sq_store_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTLBI::test_tlbi_inv_callee_ifc_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTLBI::test_tlbi_sync_comp_caller_ifc_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTLBISyncComp::test_tlbi_sync_comp_fires_after_tlbi_inv_resolves | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTranslationFault::test_no_fault_load_proceeds_normally | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTranslationFault::test_translation_fault_load_completes_with_fault | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTranslationFault::test_translation_fault_load_no_dcache_req | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTranslationFault::test_translation_fault_store_completes_with_fault | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_commit_stores_sets_canwb | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_i11_drain_gate_tripwire_no_beat_before_retire_mark | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_parent_sq_commit_wired_to_commit_stores | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_store_writeback_not_directly_called | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestTwoStageStoreWriteback::test_two_stage_pipeline_commit_then_writeback | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestVaddrPropagation::test_execute_load_passes_vaddr_to_lq_insert | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestVaddrPropagation::test_execute_store_passes_vaddr_to_sq_insert | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestViolationAckParent::test_violation_ack_exists_on_parent | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestViolationAckParent::test_violation_ack_forwards_to_lq_core | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_execute_load_activates_dtlb_probe_in_flight | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_execute_load_inserts_into_lq_via_wiring | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_execute_store_activates_dtlb_probe_in_flight | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_execute_store_inserts_into_sq_via_wiring | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_lsq_execute_resp_delivered_with_separate_args | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_store_set_violation_delivered_with_separate_args | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_violation_signal_aliased_to_lq_core | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl.TestWiringIntegration::test_violation_signal_delivered_with_separate_args | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_122_exact_status.TestExactFreeCount::test_free_counts_equal_cap_minus_child_committed_count | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_122_exact_status.TestExactFreeCount::test_lq_guard_is_exact_at_capacity | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_122_exact_status.TestExactFreeCount::test_sq_guard_reads_its_own_exact_expression | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_122_exact_status.TestHasStoresPublishIsLive::test_level_moves_query_and_bus_in_the_same_cycle | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_122_exact_status.TestUpClearTripwire::test_status_register_surface_is_deleted | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_122_exact_status.TestUpClearTripwire::test_up_clear_reads_no_child_state | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestExecuteLoadAcceptsClusterArgs::test_execute_load_accepts_cluster_id_kwarg | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestExecuteLoadAcceptsClusterArgs::test_execute_load_defaults_cluster_args_to_zero | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestExecuteLoadAcceptsClusterArgs::test_execute_load_writes_cluster_id_to_lq_entry | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestFuRealCompletePort::test_fu_real_complete_caller_ifc_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestFuRealCompletePort::test_fu_real_complete_is_callable | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestNormalLDACompletionFiresFuRealComplete::test_normal_lda_fires_fu_real_complete_on_dcache_resp | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestNormalLDACompletionFiresFuRealComplete::test_normal_lda_no_fu_real_complete_before_dcache_resp | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestSquashedLDAFastPathQ13::test_squashed_lda_does_not_wait_for_dcache | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestSquashedLDAFastPathQ13::test_squashed_lda_fires_fu_real_complete_immediately | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestSquashedLDAFastPathQ13::test_squashed_lda_no_duplicate_fu_real_complete_at_completion | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033.TestTranslationFaultLDAFiresFuRealComplete::test_translation_fault_lda_fires_fu_real_complete | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_hit_cancel_l2.TestLSQParentL1HitCancelsL2::test_l1_hit_does_not_push_to_l2_shift_register | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_hit_cancel_l2.TestLSQParentL1HitCancelsL2::test_l1_miss_pushes_to_l2_shift_register | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_miss_nack.TestLSQParentL1MissFiresNack::test_l1_hit_does_not_fire_fu_nack | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_miss_nack.TestLSQParentL1MissFiresNack::test_l1_miss_fires_fu_nack | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_miss_nack.TestLSQParentL1MissFiresNack::test_translation_fault_does_not_fire_fu_nack | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentExecuteLoadPushesToL1ShiftRegister::test_execute_load_pushes_cluster_id_and_iq_local_id | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentExecuteLoadPushesToL1ShiftRegister::test_predicated_execute_load_does_not_push | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentExecuteLoadPushesToL1ShiftRegister::test_squashed_execute_load_does_not_push | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentL1ShiftRegisterParamForwarding::test_lsq_parent_accepts_l1_hit_lat_kwarg | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentL1ShiftRegisterParamForwarding::test_lsq_parent_accepts_l2_hit_lat_kwarg | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentL1ShiftRegisterParamForwarding::test_lsq_parent_default_l1_hit_lat_matches_params | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l1_push.TestLSQParentL1ShiftRegisterPopFires::test_pop_fires_fu_early_complete_with_pushed_payload | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l2_push.TestLSQParentL2ShiftRegisterPopFires::test_pop_fires_fu_early_complete_with_pushed_payload | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l2_push.TestLSQParentTranslateResultPushesL2::test_translate_result_pushes_to_l2_shift_register | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_l2_push.TestLSQParentTranslateResultPushesL2::test_translation_fault_does_not_push_to_l2 | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestNormalLDACompletionFiresSbSetReg::test_normal_lda_fires_sb_setreg_on_dcache_resp | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestNormalLDACompletionFiresSbSetReg::test_normal_lda_no_sb_setreg_before_dcache_resp | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestSbSetRegInterface::test_sb_setreg_caller_ifc_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestSbSetRegInterface::test_sb_setreg_is_callable | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestSquashedLDAFastPathSuppressesSbSetReg::test_squashed_lda_does_not_fire_sb_setreg | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestSquashedLDAFastPathSuppressesSbSetReg::test_squashed_lda_still_fires_fu_real_complete | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_primary.TestTranslationFaultLDAFiresSbSetReg::test_translation_fault_lda_fires_sb_setreg | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_early_complete_alias_shares_lq_core_object | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_early_complete_is_callable | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_early_complete_port_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_nack_alias_shares_lq_core_object | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_nack_is_callable | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_speculation.TestSpeculationInterface::test_fu_nack_port_exists | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL1::test_squash_clears_l1_shift_reg_slot_silent_pop | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL1::test_squash_does_not_fire_and_clears_l1_slot | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL2::test_squash_clears_l2_shift_reg_slot_silent_pop | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL2::test_squash_does_not_fire_and_clears_l2_slot | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckNegativeCases::test_squash_walks_only_matching_seqnum | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckNegativeCases::test_squash_with_empty_shift_regs_does_not_fire | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0045_sbuf_gate.TestSbufTermJoinsAggregation::test_absorbed_store_holds_gate_over_empty_sq | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0045_sbuf_gate.TestSbufTermJoinsAggregation::test_term_ors_with_sq_term | block-LSQParent | default | PASS | - | 0 |
| test_lsq_parent_cl_adr0045_sbuf_gate.TestSbufTermJoinsAggregation::test_tieoff_default_reports_nothing_buffered | block-LSQParent | default | PASS | - | 0 |
| test_w0_frozen_ports.TestW0FrozenPorts::test_all_frozen_ports_carry_v1_signature | block-LSQv2 | default | PASS | - | 0 |
| test_w0_frozen_ports.TestW0FrozenPorts::test_negative_added_port_fails | block-LSQv2 | default | PASS | - | 0 |
| test_w0_frozen_ports.TestW0FrozenPorts::test_negative_changed_transport_fails | block-LSQv2 | default | PASS | - | 0 |
| test_w0_frozen_ports.TestW0FrozenPorts::test_negative_dropped_port_fails | block-LSQv2 | default | PASS | - | 0 |
| test_w0_frozen_ports.TestW0FrozenPorts::test_negative_renamed_argument_fails | block-LSQv2 | default | PASS | - | 0 |
| test_w0_frozen_ports.TestW0FrozenPorts::test_negative_source_field_on_ic_squash_fails | block-LSQv2 | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestA0PagePerAdueModes::test_fetch_a0_adue0_faults_12 | block-MMU | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestA0PagePerAdueModes::test_hit_path_a0_entry_treated_as_miss | block-MMU | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestA0PagePerAdueModes::test_load_a0_adue0_faults_13 | block-MMU | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestA0PagePerAdueModes::test_load_a0_adue1_cas_sets_a | block-MMU | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestStoreToD0PageOnHitPath::test_amo_hit_d0_adue0_walks_and_faults | block-MMU | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestStoreToD0PageOnHitPath::test_store_hit_d0_adue0_walks_and_faults | block-MMU | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestStoreToD0PageOnHitPath::test_store_hit_d0_adue1_walks_cas_sets_d_then_hits | block-MMU | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestWaiterCoalescingAdCommandUnion::test_load_walk_store_waiter_adue0_split_release | block-MMU | default | PASS | - | 0 |
| test_mmu_ad_hit_gate.TestWaiterCoalescingAdCommandUnion::test_load_walk_store_waiter_adue1_cas_sets_d_and_releases_both | block-MMU | default | PASS | - | 0 |
| test_mmu_dtlb_l1.TestDTLBTrueLRU::test_65th_distinct_page_evicts_oldest_only | block-MMU | default | PASS | - | 0 |
| test_mmu_dtlb_l1.TestEchoContract::test_hint_and_epoch_echoed_unchanged_on_hit_and_walk | block-MMU | default | PASS | - | 0 |
| test_mmu_dtlb_l1.TestT06LargePages::test_dside_2m_leaf_native_hit | block-MMU | default | PASS | - | 0 |
| test_mmu_dtlb_l1.TestT06LargePages::test_iside_2m_leaf_native_hit | block-MMU | default | PASS | - | 0 |
| test_mmu_dtlb_l1.TestT08SatpChangeNoFlush::test_new_root_same_asid_still_hits_old_entries | block-MMU | default | PASS | - | 0 |
| test_mmu_dtlb_l1.TestT20Slice1G::test_dside_1g_leaf_native_hit_l2_holds_one_2m_unit | block-MMU | default | PASS | - | 0 |
| test_mmu_dtlb_l1.TestTransitionalInvalidatePulse::test_pulse_retired_port_is_gone | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ30AdWritebackGStoreDenial::test_load_walk_a_writeback_denial_inst3020_guest_load | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ30AdWritebackGStoreDenial::test_store_walk_g_denies_writeback_guest_store_addr2_inst3020 | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ30PteFetchGDenial::test_pte_fetch_g_read_denied_inst3000_no_fill | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ30PteFetchGDenial::test_pte_fetch_g_structural_fail_inst3000 | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ30TaxonomyZeros::test_final_access_g_fail_keeps_inst_zero | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ30TaxonomyZeros::test_hit_time_w_fault_keeps_addr2_and_inst_zero | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ30TaxonomyZeros::test_single_stage_fault_keeps_addr2_and_inst_zero | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ30TaxonomyZeros::test_vs_stage_fail_keeps_addr2_and_inst_zero | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ31ItlbRespFullDescriptor::test_i_side_single_stage_fault_descriptor_tails_zero | block-MMU | default | PASS | - | 0 |
| test_mmu_faultdesc_q30_q31.TestQ31ItlbRespFullDescriptor::test_i_side_two_stage_fault_carries_full_descriptor | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestNestedGWalkPerStageKeying::test_g_stage_mmutc_keying_distinct_entries_and_warm_leaf_only | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestQ24TagScopeIntersectionSweep::test_combined_fill_evicts_comatchable_single_stage | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestQ24TagScopeIntersectionSweep::test_combined_vmid_intersects_only_its_own | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestQ24TagScopeIntersectionSweep::test_global_intersects_every_asid | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestQ24TagScopeIntersectionSweep::test_single_fill_evicts_comatchable_combined | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestQ26CombinedVmidStrictMatch::test_q26_vmid_strict_match_each_combined_entry_answers_own_vmid | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestQ26CombinedVmidStrictMatch::test_q26_vmid_strict_match_l2_rows_answer_own_vmid | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestT16FaultingPointerNotCached::test_fetch_v_clear_level1_code12 | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestT16FaultingPointerNotCached::test_load_v_clear_level1_code13_no_fill_partial_pointer_stands | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestT16FaultingPointerNotCached::test_store_v_clear_level1_code15 | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestT17TwoStageCombinedEntry::test_forced_two_stage_one_combined_entry_second_hit_one_lookup | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestT17TwoStageCombinedEntry::test_permissions_folded_intersection_store_faults_guest_code | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestTwoStageFaultShapes::test_g_stage_fail_addr2_faulting_pte_gpa_shifted | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestTwoStageFaultShapes::test_two_stage_store_fault_code_is_guest_store | block-MMU | default | PASS | - | 0 |
| test_mmu_faults_twostage.TestTwoStageFaultShapes::test_vs_stage_fail_guest_code_addr2_zero | block-MMU | default | PASS | - | 0 |
| test_mmu_fences.TestQ19FenceIRaiseIsCacheLinesOnly::test_fence_i_flush_raise_touches_cache_lines_only | block-MMU | default | PASS | - | 0 |
| test_mmu_fences.TestT10GvmaVmidOnly::test_gvma_vmid_only_kills_combined_at_all_four_structures | block-MMU | default | PASS | - | 0 |
| test_mmu_fences.TestT11DrainThenSweep::test_fence_waits_sweep_kills_drain_fill_completes_after_sweep | block-MMU | default | PASS | - | 0 |
| test_mmu_fences.TestT12PostFenceMissNoAttach::test_post_fence_miss_never_attaches_and_walks_post_sweep | block-MMU | default | PASS | - | 0 |
| test_mmu_fences.TestT18CombinedDiesToBothHfences::test_vvma_all_asid_and_gvma_all_vmid_kill_combined | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestCodeContract::test_itlb_req_carries_spec_13_fields_in_order | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestCodeContract::test_itlb_resp_carries_spec_14_fields_in_order | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestCodeContract::test_mmu_ifc_module_exists_with_wire_types | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestCodeContract::test_pl2_wire_field_order | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestCodeContract::test_translate_req_field_order | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestCodeContract::test_translate_result_field_order | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestSpecText::test_all_frozen_wire_forms_carry_spec_signature | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestSpecText::test_negative_dropped_response_field_fails | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestSpecText::test_negative_flipped_transport_fails | block-MMU | default | PASS | - | 0 |
| test_mmu_frozen_ports.TestSpecText::test_negative_renamed_port_fails | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestMapPage::test_2m_mapping_places_leaf_pte_in_level1_table | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestMapPage::test_4k_mapping_places_leaf_pte_in_level0_table | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestMemModel::test_alloc_page_is_page_aligned_and_fresh | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestMemModel::test_read_counts_every_access | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestPL2Stub::test_cas_mismatch_leaves_memory_alone | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestPL2Stub::test_cas_success_writes_and_reports | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestPL2Stub::test_mshr_backpressure_at_the_wire | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestPL2Stub::test_mshr_exhaustion_holds_not_drops | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestPL2Stub::test_resp_lat_two_delays_serving | block-MMU | default | PASS | - | 0 |
| test_mmu_harness.TestPL2Stub::test_serves_pte_read_from_memmodel | block-MMU | default | PASS | - | 0 |
| test_mmu_identity::test_dside_bare_mode_identity_no_walk | block-MMU | default | PASS | - | 0 |
| test_mmu_identity::test_identity_is_never_cached_t20 | block-MMU | default | PASS | - | 0 |
| test_mmu_identity::test_iside_bare_fetch_identity_full_perm | block-MMU | default | PASS | - | 0 |
| test_mmu_identity::test_iside_mmode_fetch_identity_even_with_satp_enabled | block-MMU | default | PASS | - | 0 |
| test_mmu_overlap.TestD15ScopeEndToEnd::test_other_asid_overlap_fills_side_by_side | block-MMU | default | PASS | - | 0 |
| test_mmu_overlap.TestMixedSizeLRU::test_lru_across_mixed_sizes_no_size_bias | block-MMU | default | PASS | - | 0 |
| test_mmu_overlap.TestT19OverlapSweep::test_2m_fill_plan_evicts_covered_4k | block-MMU | default | PASS | - | 0 |
| test_mmu_overlap.TestT19OverlapSweep::test_4k_fill_plan_evicts_covering_2m | block-MMU | default | PASS | - | 0 |
| test_mmu_overlap.TestT19OverlapSweep::test_itlb_sweep_symmetric | block-MMU | default | PASS | - | 0 |
| test_mmu_overlap.TestT19OverlapSweep::test_sweep_scopes_by_asid | block-MMU | default | PASS | - | 0 |
| test_mmu_overlap.TestT19OverlapSweep::test_sweep_spares_out_of_range_same_scope | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_ad.TestF1CasMismatchReReadMshrStall::test_f1_cas_retry_mshr_exhaustion_no_hang | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_ad.TestF2WalkerLegMemoryFaultCodes::test_f2_ad_fault_access_code_load | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_ad.TestF2WalkerLegMemoryFaultCodes::test_f2_ad_fault_access_code_store | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_ad.TestF2WalkerLegMemoryFaultCodes::test_f2_pte_read_fault_access_code_fetch | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_ad.TestF2WalkerLegMemoryFaultCodes::test_f2_pte_read_fault_access_code_load | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_ad.TestT13Pl2MshrBackpressure::test_walk_stalls_at_pte_read_issue_until_an_mshr_frees | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_ad.TestT14SvaduSetDBeforeResponse::test_store_adue1_sets_d_via_pl2_cas_visible_before_response | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_ad.TestT15SvaduAdueOffFaults::test_store_adue0_faults_no_ad_update_no_fill | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_resp_hold.TestQ29NeverDrop::test_unclaimed_response_is_held_not_dropped | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_resp_hold.TestQ29SameCycleServe::test_same_cycle_serve_itlb_walk_completes | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_resp_hold.TestQ29SameCycleServe::test_same_cycle_serve_single_stage_walk_completes | block-MMU | default | PASS | - | 0 |
| test_mmu_pl2_resp_hold.TestQ29SameCycleServe::test_same_cycle_serve_two_stage_walk_completes | block-MMU | default | PASS | - | 0 |
| test_mmu_snapshot_retire.TestT21SatpSnapshotMidWalk::test_dside_walk_completes_under_latched_root_and_asid | block-MMU | default | PASS | - | 0 |
| test_mmu_snapshot_retire.TestT21SatpSnapshotMidWalk::test_iside_walk_completes_under_latched_root_and_asid | block-MMU | default | PASS | - | 0 |
| test_mmu_snapshot_retire.TestT21SatpSnapshotMidWalk::test_two_stage_fill_carries_latched_asid_and_vmid | block-MMU | default | PASS | - | 0 |
| test_mmu_snapshot_retire.TestTBWalkerRetirement::test_tb_walk_path_not_consulted_identical_responses | block-MMU | default | PASS | - | 1 |
| test_mmu_walk_cache_l2.TestT02WalkCacheResume::test_l2_hit_refills_l1_without_walk | block-MMU | default | PASS | - | 0 |
| test_mmu_walk_cache_l2.TestT02WalkCacheResume::test_neighbouring_page_same_2m_region_one_table_read | block-MMU | default | PASS | - | 0 |
| test_mmu_walk_cache_l2.TestT07L2One2MUnit::test_1g_leaf_native_hit_l2_holds_containing_unit | block-MMU | default | PASS | - | 0 |
| test_mmu_walk_cache_l2.TestT22NoSplinter::test_600_units_accrue_one_per_request | block-MMU | default | PASS | - | 0 |
| test_mmu_walkers.TestT01OneMMUBothSides::test_d_and_i_miss_concurrent | block-MMU | default | PASS | - | 0 |
| test_mmu_walkers.TestT03FiveMissesFourWalkers::test_fifth_waits_in_miss_queue_nothing_dropped | block-MMU | default | PASS | - | 0 |
| test_mmu_walkers.TestT04Coalescing::test_d_waiter_paddr_recomposes_own_page_offset | block-MMU | default | PASS | - | 0 |
| test_mmu_walkers.TestT04Coalescing::test_different_asid_same_va_walks_separately | block-MMU | default | PASS | - | 0 |
| test_mmu_walkers.TestT04Coalescing::test_i_waiter_paddr_recomposes_own_page_offset | block-MMU | default | PASS | - | 0 |
| test_mmu_walkers.TestT04Coalescing::test_second_miss_same_va_attaches_one_walk | block-MMU | default | PASS | - | 0 |
| test_mmu_walkers.TestT05RoundRobin::test_grants_alternate_while_both_sides_queued | block-MMU | default | PASS | - | 0 |
| test_mmu_walkers.TestT05RoundRobin::test_idle_side_turn_skipped_never_burns_a_walker | block-MMU | default | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_backward_ctrl_in_forwards_to_commit | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_rename_to_iew_accessible | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_rob_empty_reaches_rename | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_squash_reaches_rename | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestBackwardBusPropagation::test_squash_seqnum_reaches_rename | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_commit_reset_running | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_exported_interfaces_exist | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_nested_sub_blocks_exist | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_rename_reset_idle | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_rob_reset_empty | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestConstructionAndReset::test_sub_blocks_exist | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestEndToEndRenameCommit::test_decode_from_forwards_to_rename | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestEndToEndRenameCommit::test_rob_commit_connection_exists | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestEndToEndRenameCommit::test_rob_insert_via_rename | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestSquashRecovery::test_fip_write_connection | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestSquashRecovery::test_iew_squash_sets_commit_rob_squashing | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestSquashRecovery::test_iew_squash_sets_commit_squash | block-O3Control | default | PASS | - | 0 |
| test_o3_control_cl.TestSquashRecovery::test_squash_walk_bridge_initiated | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestBackwardBus::test_backward_ctrl_in_merges_to_output | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestBackwardBus::test_free_rob_entries_on_backward_bus | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestBackwardBus::test_rob_empty_on_backward_bus | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestCommitFlow::test_commit_frees_phys_reg | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestCommitFlow::test_commit_retires_instruction | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestCommitFlow::test_done_seqnum_on_backward_bus | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestFIPWrite::test_fip_write_connection_active | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestFIPWrite::test_fip_write_reaches_commit | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestFaultTrap::test_fault_sets_trap_pending | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestFaultTrap::test_trap_triggers_cpu_trap_call | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestNonSpeculative::test_non_spec_broadcasts_seqnum | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestNonSpeculative::test_non_spec_clears_can_commit | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestROBInsert::test_multi_inst_insert | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestROBInsert::test_rename_inserts_into_rob | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestRenamePipeline::test_multi_inst_rename_bundle | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestRenamePipeline::test_nop_renamed_to_iew_output | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestRenamePipeline::test_rename_advances_running_state | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestRenamePipeline::test_rename_to_iew_receives_output | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestSMT::test_two_thread_rename | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestSerializeBlock::test_block_signal_affects_rename | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestSerializeBlock::test_serialize_before_stall | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_iew_squash_reaches_commit | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_iew_squash_sets_bc_rename_squash | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_squash_reaches_rename_via_backward_bus | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_squash_walk_bridge_activated | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestSquashFlow::test_squash_with_instructions_in_flight | block-O3Control | default | PASS | - | 0 |
| test_o3_control_e2e.TestWBUpdate::test_wb_sets_completed | block-O3Control | default | PASS | - | 0 |
| test_pl2_cache_cl.TestGapG1Remnant::test_gap_g1_load_misses_complete_out_of_request_order | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP217DrainWrite::test_p2_17a_drain_hit_byte_merge_dirty_no_resp_no_push | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP217DrainWrite::test_p2_17b_drain_full_mask_miss_installs_no_fetch | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP217DrainWrite::test_p2_17c_drain_partial_miss_one_fetch_merged_install | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP217DrainWrite::test_p2_17d_second_drain_coalesces_into_fetch_merge | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP217DrainWrite::test_p2_17e_fetch_merge_fill_error_sticky_no_install | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP217DrainWrite::test_p2_17f_drain_writes_never_respond_or_push | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP217DrainWrite::test_p2_17g_scalar_cacheable_store_is_protocol_violation[0] | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP217DrainWrite::test_p2_17g_scalar_cacheable_store_is_protocol_violation[4] | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP21LoadMissFlow::test_p2_1a_load_miss_fill_push_resp | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP21LoadMissFlow::test_p2_1b_miss_resp_uses_fill_term_when_slow | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP21LoadMissFlow::test_p2_1c_load_miss_want_refill_false_no_push | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP22CoalescedMisses::test_p2_2a_load_load_coalesce | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP22CoalescedMisses::test_p2_2b_store_to_load_mshr_line_serialized | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP22CoalescedMisses::test_p2_2c_staged_load_coalesces_never_overlay_fill_line | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP27Uncached::test_p2_7a_nc_load_one_shot | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP27Uncached::test_p2_7b_io_identical_to_nc | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP27Uncached::test_p2_7c_nc_store_one_shot | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP27Uncached::test_p2_7d_nc_with_want_refill_asserts | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP28PushBackpressure::test_p2_8a_held_push_stalls_mshr_not_load_resp | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP28PushBackpressure::test_p2_8b_upsert_absorbs_repeated_pushes | block-PL2 | default | PASS | - | 0 |
| test_pl2_cache_cl.TestP28PushBackpressure::test_p2_8c_one_push_per_cycle_drain | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestGapG3MergedDrainWriteback::test_gap_g3_n_drain_writes_one_line_single_writeback | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP210Arbitration::test_p2_10a_one_request_per_cycle | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP210Arbitration::test_p2_10b_round_robin_fairness | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP210Arbitration::test_p2_10c_wb_credit_priority | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP210Arbitration::test_p2_10d_wb_full_backpressures_cbo | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP211Backpressure::test_p2_11a_mshr_full_backpressure_no_loss | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP211Backpressure::test_p2_11b_nc_slot_full_backpressure_no_loss | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP211Backpressure::test_p2_11c_mem_resp_slot_and_resting_rdy | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP212Faults::test_p2_12a_fill_error_faults_all_load_waiters | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP212Faults::test_p2_12c_nc_error_faults_single_response | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP212Faults::test_p2_12d_wb_error_sets_sticky_flag_and_continues | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP213ResetValidation::test_p2_13a_reset_state_census | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP213ResetValidation::test_p2_13b_first_access_misses | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP213ResetValidation::test_p2_13c_geometry_validation | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP25EvictionWriteback::test_p2_5a_dirty_victim_writes_back | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP25EvictionWriteback::test_p2_5b_clean_victim_no_memory_traffic | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP25EvictionWriteback::test_p2_5c_writeback_before_refill_same_line | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6a_inval_drops_dirty_without_writeback | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6b_inval_suppresses_queued_push_and_releases_gates | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6c_clean_writeback_keeps_line_valid | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6d_flush_writeback_and_invalidate | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6e_absent_line_completes_immediately | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6f_idempotent_retrigger | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6g_maintenance_never_allocates_or_pushes | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6h_invalid_ctrl_op_asserts | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP26CboReactions::test_p2_6i_dual_trigger_same_reaction_table | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP29Timing::test_p2_9a_hit_resp_exactly_accept_plus_lat | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP29Timing::test_p2_9b_miss_resp_floored_at_accept_plus_lat | block-PL2 | default | PASS | - | 0 |
| test_pl2_mshr_wb.TestP29Timing::test_p2_9d_construct_enforces_lat_invariant | block-PL2 | default | PASS | - | 0 |
| test_pl2_peek.TestPL2Peek::test_pl2_peek_hit_and_miss | block-PL2 | default | PASS | - | 0 |
| test_pl2_peek.TestPL2Peek::test_pl2_peek_is_read_only | block-PL2 | default | PASS | - | 0 |
| test_pl2_peek.TestPL2Peek::test_pl2_peek_pending_merge_visible | block-PL2 | default | PASS | - | 0 |
| test_pl2_peek.TestPL2Peek::test_pl2_peek_pending_slot_overlay | block-PL2 | default | PASS | - | 0 |
| test_pl2_peek.TestPL2Peek::test_pl2_peek_staged_install_visible | block-PL2 | default | PASS | - | 0 |
| test_pl2_push_full.TestP214PushQueueFull::test_p2_14a_full_queue_defers_install_push | block-PL2 | default | PASS | - | 0 |
| test_pl2_push_full.TestP214PushQueueFull::test_p2_14b_full_queue_backpressures_intake_hit_refresh | block-PL2 | default | PASS | - | 0 |
| test_pl2_push_full.TestP215CboZeroInstall::test_p2_15a_zero_block_install_without_fetch | block-PL2 | default | PASS | - | 0 |
| test_pl2_push_full.TestP216DefaultGeometry::test_p2_16a_default_geometry_miss_roundtrip | block-PL2 | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestCCClassOmission::test_cc_class_omitted_when_zero | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestCCClassOmission::test_cc_class_present_when_nonzero | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestCCClassOmission::test_cc_read_returns_zero_when_omitted | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestDuplicateIndexAssertion::test_duplicate_index_different_classes_ok | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestDuplicateIndexAssertion::test_duplicate_index_same_class_raises | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPerClassWritePortsParams::test_params_per_class_writeports | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPerClassWritePortsParams::test_write_ports_match_constructed_methods | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_read_req_dataclass | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_read_resp_dataclass | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_read_resp_default_ready_asserted | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_write_port_dataclass_default | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegFileInterfaceDataclasses::test_write_port_dataclass_set_fields | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegIdAndClassEnum::test_physreg_id_class_index_roundtrip | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestPhysRegIdAndClassEnum::test_reg_class_enum_encoding | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestReadRegCombinational::test_read_each_class_returns_zero_after_reset | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestReadRegCombinational::test_read_reg_rdy_permanently_asserted | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestReadRegCombinational::test_read_returns_zero_after_reset | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestResetClearsPending::test_reset_clears_pending | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestResetClearsPending::test_reset_clears_pending_each_class | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestTiming::test_chained_writes_each_cycle | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestTiming::test_read_latency_zero_cycles | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestTiming::test_write_latency_one_cycle | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_multi_port_write_same_cycle | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_overwrite_via_two_writes | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_per_class_isolation | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_write_to_each_class | block-PhysRegFile | default | PASS | - | 0 |
| test_phys_reg_file_cl.TestWriteRegAndCommit::test_write_visible_next_cycle_not_same_cycle | block-PhysRegFile | default | PASS | - | 0 |
| test_rob_cl.TestClearCanCommit::test_clear_can_commit | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestClearCanCommit::test_clear_then_wb_reasserts | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_max_entries_dynamic | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_max_entries_partitioned | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_reset_done_squashing_true | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_reset_head_tail_count_zero | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_reset_rob_status_idle | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestConstructionAndReset::test_reset_youngest_seqnum_zero | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestFSM::test_idle_to_running | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestFSM::test_running_to_squashing | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestFSM::test_squashing_to_running | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestFindBySeqNum::test_find_existing | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestFindBySeqNum::test_find_not_found | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestFreeEntryQuery::test_free_entries | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestFreeEntryQuery::test_is_empty | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestFreeEntryQuery::test_is_full | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestHeadRead::test_head_read_empty | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestHeadRead::test_head_read_returns_oldest | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestHeadRead::test_head_ready_reflects_can_commit | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestInsert::test_insert_ack_combinational | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestInsert::test_insert_updates_youngest_seqnum | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestInsert::test_insert_when_full | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestInsert::test_multi_slot_insert | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestInsert::test_single_insert | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestLayerSeparation::test_next_rob_entries_not_aliased_to_state_after_tick | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestLayerSeparation::test_next_rob_entries_outer_list_independent | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestRetire::test_retire_count_actual | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestRetire::test_retire_multiple | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestRetire::test_retire_single | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestRetire::test_retire_squashed_drains | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSMTArbitration::test_dynamic_multi_thread | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSMTArbitration::test_partitioned_capacity | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_done_signal | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_empty_fast_path | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_marks_entries | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_new_request_restarts | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_no_head_tail_count_change | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquash::test_squash_updates_youngest_seqnum | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquash::test_thread_exiting_override | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquash::test_youngest_seqnum_squash_overrides_insert | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_cmt_fip_full_stall | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_walk_abort | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_walk_done_with_last_beat | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_walk_fields | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalk::test_walk_youngest_to_oldest | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_ckpt_metadata_save_restore | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_ckpt_restore_falls_back_to_head_ptr | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_ckpt_save_reset_to_zero | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_insert_stores_allocated_new | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_abort_superseding | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_cmt_fip_full_stalls_phase3_only | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_empty_rob_fast_path | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_phase2_replay | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_phase3_free | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_simultaneous | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestWBUpdate::test_wb_discarded_if_squashed | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestWBUpdate::test_wb_fault_stored | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestWBUpdate::test_wb_set_can_commit | block-ROB | default | PASS | - | 0 |
| test_rob_cl.TestWBUpdate::test_wb_set_completed | block-ROB | default | PASS | - | 0 |
| test_read_operand_cl.TestFromIQ::test_fromiq_rdy_false_when_pending | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestFromIQ::test_fromiq_rdy_when_empty | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestFromIQ::test_fromiq_stores_request | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_csr_read_port_exists | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_direct_complete_port_exists | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_fromiq_port_exists | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_fu_operand_port_exists | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_rf_read_port_exists | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestInterfaces::test_ro_inst_issued_port_exists | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_create_load_factory_accepts_cluster_id_iq_local_id | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_lsq_execute_resp_has_cluster_id_field | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_lsq_execute_resp_has_iq_local_id_field | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_lsq_execute_resp_to_fu_complete_bundle_forwards_cluster_id | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestLSQExecuteRespBundleADR0033::test_lsq_execute_resp_to_fu_complete_bundle_forwards_iq_local_id | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_calls_direct_complete | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_calls_ro_inst_issued | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_check_before_fault | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_check_before_predicate_false | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestNoNeedFUShortCircuit::test_no_need_fu_skips_fupool | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestPreExecFaultShortCircuit::test_no_fault_proceeds_to_fupool | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestPreExecFaultShortCircuit::test_nonmem_fault_calls_direct_complete | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestPreExecFaultShortCircuit::test_nonmem_fault_calls_ro_inst_issued | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestPreExecFaultShortCircuit::test_nonmem_fault_skips_fupool | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestPredicateFalseShortCircuit::test_predicate_false_calls_direct_complete | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestPredicateFalseShortCircuit::test_predicate_false_calls_ro_inst_issued | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestPredicateFalseShortCircuit::test_predicate_false_skips_fupool | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestPredicateFalseShortCircuit::test_predicate_true_proceeds_to_fupool | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestProcessing::test_no_handoff_without_fromiq | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestProcessing::test_process_clears_state_after_tick | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestROInstIssuedProducer::test_ro_inst_issued_called_for_squashed | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestROInstIssuedProducer::test_ro_inst_issued_called_with_tid | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestReset::test_after_resetpending_fromiq_is_none | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestReset::test_after_resetstate_fromiq_is_none | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestRfReadWiring::test_rfread_called_for_each_source_operand | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestSquashedBypass::test_squashed_still_handed_off | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_direct_complete_bundle_carries_cluster_id_iq_local_id | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_read_operand_populates_cluster_id_default_when_absent | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_read_operand_populates_cluster_id_from_inst | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_read_operand_populates_iq_local_id_from_inst | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_wbinfo_has_cluster_id_field | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoADR0033ClusterRouting::test_wbinfo_has_iq_local_id_field | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoExtraction::test_fu_operand_req_carries_wbinfo | block-ReadOperand | default | PASS | - | 0 |
| test_read_operand_cl.TestWBInfoExtraction::test_wbinfo_dest_phys_reg_defaults_to_zero | block-ReadOperand | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestDirectComplete::test_direct_complete_called_for_fault | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestHandoff::test_fu_operand_called_after_read | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestHandoff::test_squashed_still_handed_off | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestOperandRead::test_rf_read_called_for_sources | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestReceiveIssue::test_fromiq_rdy_when_not_full | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestReceiveIssue::test_fromiq_stores_request | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestWBInfoConstruction::test_wbinfo_has_dest_phys_reg | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryCalledPerSourceReg::test_bypass_query_called_for_each_source | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryHitUsesBypassValue::test_bypass_query_hit_uses_bypass_value | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryHitUsesBypassValue::test_bypass_query_miss_uses_rf_read_value | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_caller_ifc_exists | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_is_callable | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryPrecedence::test_bypass_query_hit_suppresses_rf_read | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryPrecedence::test_bypass_query_partial_hit_suppresses_only_hit_sources | block-ReadOperandInt | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_lda_calls_fu_operand | block-ReadOperandMem | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_none_uop_calls_fu_operand | block-ReadOperandMem | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_sta_calls_fu_operand | block-ReadOperandMem | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_calls_lsq_execute_store_data | block-ReadOperandMem | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_does_not_call_fu_operand | block-ReadOperandMem | default | PASS | - | 0 |
| src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_passes_three_args | block-ReadOperandMem | default | PASS | - | 0 |
| test_free_list_cl.TestAllocFreeSameCycle::test_alloc_does_not_see_same_cycle_free | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_alloc_advances_head | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_alloc_from_empty_class | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_multi_slot_alloc_same_class | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_per_class_isolation | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestAllocation::test_single_alloc | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestBugFixes::test_alloc_empty_class_returns_invalid | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestBugFixes::test_count_single_write_alloc_and_free_same_cycle | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestBugFixes::test_free_pushes_to_correct_class | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestCapacitySignals::test_empty_flag_after_draining_class | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestCapacitySignals::test_empty_flag_false_when_class_has_regs | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestCapacitySignals::test_empty_flag_when_class_empty | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestConstructionAndReset::test_reset_count_matches_phys_regs | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestConstructionAndReset::test_reset_head_tail | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestConstructionAndReset::test_reset_loads_all_phys_regs | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestReclamation::test_free_cc_class_is_noop | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestReclamation::test_free_then_alloc_fifo_order | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestReclamation::test_single_free | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_alloc_more_than_available | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_circular_buffer_wraparound | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_circular_buffer_wrapping | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_mixed_class_multi_alloc | block-Rename | default | PASS | - | 0 |
| test_free_list_cl.TestSameCycleMultiAlloc::test_multiple_allocs_in_order | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointSaveTrigger::test_cond_branch_high_confidence_skips_save | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointSaveTrigger::test_cond_branch_triggers_checkpoint_save | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointSaveTrigger::test_indirect_branch_triggers_checkpoint_save | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointSaveTrigger::test_interval_counter_increments_on_rename | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointState::test_branch_confidence_high_default_false | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointState::test_ckpt_pool_cap_construction_assert | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005CheckpointState::test_ckpt_state_reset | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005ForwardReplay::test_allocated_new_false_skips_fip_write | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005ForwardReplay::test_phase3_walk_triggers_fip_write | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005SquashRecovery::test_mispredict_restore_rearms_and_forces_new_target_save | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005SquashRecovery::test_squash_exits_on_both_walks_done | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestADR0005SquashRecovery::test_walk_done_flags_reset_on_squash | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestBlockUnblock::test_block_on_iq_full | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestBlockUnblock::test_block_on_rob_full | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestBlockUnblock::test_unblock_when_resources_available | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestCombinationalOccupancyReadback::test_comb_occupancy_readback_default_true | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestCombinationalOccupancyReadback::test_comb_occupancy_readback_false | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestConstructionAndReset::test_rename_map_initialized | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestConstructionAndReset::test_reset_empty_queues | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestConstructionAndReset::test_reset_no_block_signals | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestConstructionAndReset::test_reset_status_idle | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestFIPBackPressure::test_fip_back_pressure_stalls_walk | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestFIPBackPressure::test_fip_clear_on_new_squash | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestFIPBackPressure::test_fip_full_reset_false | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestFIPBackPressure::test_fip_full_set_on_walk | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestMultiInstructionRename::test_intra_bundle_dependency | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestMultiInstructionRename::test_two_instructions_same_cycle | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestNormalRename::test_instruction_with_source_reg | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestNormalRename::test_nop_instruction | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestNormalRename::test_single_instruction_rename | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestShadowCounters::test_cached_state_reset | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestShadowCounters::test_shadow_counters_reset_zero | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestSkidBuffer::test_blocked_instruction_goes_to_skid | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestSquashRecovery::test_squash_clears_queues | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestSquashRecovery::test_squash_seqnum_captured | block-Rename | default | PASS | - | 0 |
| test_rename_cl.TestSquashRecovery::test_squash_sets_squashing_state | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCanRename::test_can_rename_fails_when_empty | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCanRename::test_can_rename_when_free_regs_available | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestore::test_restore_done_pulse | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestore::test_restore_returns_to_saved_state | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestoreCAMLookup::test_checkpoint_restore_cam_lookup | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestoreCAMLookup::test_checkpoint_restore_invalidates_younger | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointRestoreCAMLookup::test_checkpoint_restore_no_match_asserts | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointSave::test_save_captures_spec_map | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointSaveMetadata::test_checkpoint_save_done_pulse | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCheckpointSaveMetadata::test_checkpoint_save_stores_metadata | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCircularNextFreeAllocation::test_circular_next_free_slot_allocation | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCommitSetEntry::test_commit_updates_arch_map_only | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCommitSetEntry::test_non_commit_updates_spec_only | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestCommitSetReqOldPhysReg::test_commit_set_req_returns_old_phys_reg | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestConstructionAndReset::test_arch_map_initialized | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestConstructionAndReset::test_spec_arch_map_match_after_reset | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestConstructionAndReset::test_spec_map_initialized | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestForwardReplayPhase2::test_forward_replay_phase2_set_entry | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestIntraBundleBypass::test_inst1_source_sees_inst0_dest_rename | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestMiscReg::test_misc_reg_identity_mapping | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestMiscReg::test_misc_reg_rename_returns_identity | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP6WrapProofBoundaryKey::test_empty_rob_boot_squash_restores_boot_snapshot | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP6WrapProofBoundaryKey::test_slot0_wrap_mem_violation_restores_strictly_older | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_capped_pool_ranks_across_a_full_generation_rotation | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_d7_out_of_window_tag_never_outranks_in_window | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_distance_ordering_selects_youngest_qualifying | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_duplicate_tag_assert_still_fires | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_restore_no_valid_slots_cam_miss_asserts | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_slot0_duplicate_save_exempt | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_trap_reseed_resets_next_free_first_save_overwrites | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestP8RobIdxTagCAM::test_younger_invalidation_by_extended_distance | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestPinnedWrites::test_pin_count_zero_allocates_normally | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestPinnedWrites::test_pin_counter_not_decremented_in_cl | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestPinnedWrites::test_pinned_register_reuses_mapping | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestRenameBundle::test_basic_lookup | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestRenameBundle::test_basic_rename | block-Rename | default | PASS | - | 0 |
| test_rename_map_cl.TestSetEntry::test_set_entry_updates_spec_map_only | block-Rename | default | PASS | - | 0 |
| test_sq_store_cl.TestADR0019Ports::test_dcache_store_pa_req_caller_ifc_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestADR0019Ports::test_dcache_store_pa_req_fires_on_writeback | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestADR0019Ports::test_dcache_store_write_removed | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestBarrierFence::test_is_release_flag_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestBitFieldTagScheme::test_cfg_tag_n_field_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_includes_tag | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_tag_value_idx0 | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_tag_value_idx1 | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_clean_writeback | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_excluded_from_forwarding | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_flush_writeback | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_no_violation_scan_on_translated | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_participates_in_tso | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_two_stage_writeback_path | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_type_field_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_cbo_zero_writeback | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_dcache_store_write_carries_cbo_type | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_insert_accepts_cbo_type | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCBOType::test_normal_store_cbo_type_zero | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestCacheMaintenance::test_cache_maintenance_flag_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_broadcast_fires_even_without_dependents_bits | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_broadcast_fires_on_executed_fsm_with_dependents | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_broadcast_one_shot_does_not_refire | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_broadcast_passes_sq_idx_and_bitvector | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_cfg_lq_size_param_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_default_cfg_lq_size_is_32 | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_dependents_broadcast_caller_ifc_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_insert_clears_dependents_and_broadcast_flag | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_sq_entry_has_dependents_broadcast_flag | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestDependentsBroadcast::test_sq_entry_has_dependents_field | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_has_stores_to_wb_false_after_drain | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_has_stores_to_wb_false_when_empty | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_has_stores_to_wb_true_when_stores_pending | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_normal_store_not_blocked_by_sq_head | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_release_store_blocked_while_a_in_flight | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_release_store_fires_after_batch_pop | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_sc_store_fires_after_batch_pop | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestFenceOrdering::test_state_stores_to_wb_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestForwardQuery::test_forward_full_coverage_hit | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestForwardQuery::test_forward_no_match | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestForwardQuery::test_forward_partial_coverage | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestForwardingCAMMatrix::test_atomic_store_no_forward | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestInsert::test_insert_adds_entry | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestInsert::test_insert_advances_tail | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestInterfaces::test_callee_ports_exist | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestInterfaces::test_caller_ports_exist | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_is_data_prefetch_field_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_normal_store_still_sends_to_dcache | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_prefetch_does_not_set_storesInFlight | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_prefetch_store_skips_dcache | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_zero_size_store_skips_dcache | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM5StoreBackpressure::test_blocked_store_retries_same_packet | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM5StoreBackpressure::test_isStoreBlocked_resets | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM5StoreBackpressure::test_store_blocked_when_dcache_not_ready | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestM5StoreBackpressure::test_store_unblocks_when_dcache_ready | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_construct_accepts_max_threads_param | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_default_max_threads_is_one_backward_compat | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_insert_both_threads_independent | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_insert_tid0_uses_partition0 | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestMultiThreadInsert::test_insert_tid1_uses_partition1 | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_insert_defaults_non_spec_false | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_insert_sets_non_spec_true | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_sq_entry_has_non_spec_field | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_up_once_store_translated_proceeds_when_non_spec_cleared | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_up_once_store_translated_proceeds_when_non_spec_false | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestNonSpecFlag::test_up_once_store_translated_skipped_when_non_spec | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestPartialForwardStallSeqnum::test_forward_query_returns_6_tuple_on_partial | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestPartialForwardStallSeqnum::test_forward_query_returns_zero_seqnum_on_full_hit | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestPartialForwardStallSeqnum::test_forward_query_returns_zero_seqnum_on_no_match | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestPerFragmentViolationCheck::test_split_store_triggers_violation_check_twice | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestReset::test_after_reset_all_empty | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestReset::test_after_reset_fsm_idle | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestReset::test_after_reset_head_tail_zero | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSCLR::test_reservation_registers_exist | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSCLR::test_sc_failure_completes_without_write | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSCLR::test_set_reservation_method_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_has_stale_method_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_sq_entry_has_stale_translation_field | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_sq_entry_has_vaddr_field | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_stale_store_triggers_translate_req | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_tlbi_inv_callee_ifc_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_tlbi_inv_marks_inflight_store_stale | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreC3TLBI::test_translate_req_caller_ifc_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreClearReservation::test_clear_reservation_callee_ifc_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreClearReservation::test_clear_reservation_clears_state | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSQStoreClearReservation::test_clear_reservation_mismatched_addr_no_clear | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSetPhysAddr::test_set_phys_addr_sets_eff_addr_valid | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreNonForwardable::test_split_store_skipped_by_forward_query | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreWriteback::test_split_store_completion_requires_both_acks | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreWriteback::test_split_store_issues_two_dcache_reqs | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreWriteback::test_split_store_marks_issued_on_writeback | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestSplitStoreWriteback::test_split_store_sets_storesInFlight_on_writeback | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_batch_pop_multiple_consecutive_completed | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_batch_pop_respects_writeback_width | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_batch_pop_single_completed_entry | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_batch_pop_stops_at_non_completed | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_retire_store_removed | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteBatchPop::test_store_complete_batch_pop_in_up_clear_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteNotify::test_store_complete_fires_notify_with_head_seqnum | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteNotify::test_store_complete_notify_caller_ifc_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_completed_not_set_at_send_time | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_split_store_complete_requires_both_acks | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_split_store_pending_flags_only_after_both_acks | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_accepts_sq_idx_and_is_frag1 | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_sets_completed | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_sets_pending_flags_only_on_completion | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestStoreTranslatedContinuation::test_translated_to_executed | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestTwoStageWriteback::test_canwb_set_by_commit_stores | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestTwoStageWriteback::test_storeWBIt_iterator_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestTwoStageWriteback::test_storesInFlight_register_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestTwoStageWriteback::test_storesToWB_counter_exists | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_canWB_store_sent_to_dcache_autonomously | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_non_canWB_store_not_sent | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_store_complete_allows_next_store | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_store_complete_clears_storesInFlight | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl.TestWritebackEngine::test_storesInFlight_blocks_second_store | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl_g10_wwide.TestG10WWideStoreIssue::test_in_flight_cap_bounds_single_thread | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl_g10_wwide.TestG10WWideStoreIssue::test_single_thread_occupies_both_ports_same_cycle | block-SQStore | default | PASS | - | 0 |
| test_sq_store_cl_g10_wwide.TestG10WWideStoreIssue::test_two_threads_share_two_ports_same_cycle | block-SQStore | default | PASS | - | 0 |
| test_scoreboard_cl.TestDesignParams::test_misc_base_after_renameable | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestDesignParams::test_num_phys_regs_total | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestIntraGroupRAW::test_earlier_unset_makes_getReg_return_0_same_cycle | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestIsAlwaysReady::test_misc_reg_always_ready_after_unset | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestIsAlwaysReady::test_misc_reg_getReg_returns_1 | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestIsAlwaysReady::test_misc_reg_setReg_no_op | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestLifecycle::test_squash_recovery_reverses_busy_to_ready | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestLifecycle::test_unset_then_set_lifecycle | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestMethodExistence::test_getReg_methods_exist_for_all_slots | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestMethodExistence::test_setRegSquash_methods_exist_for_all_slots | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestMethodExistence::test_setReg_methods_exist_for_all_slots | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestMethodExistence::test_unsetReg_methods_exist_for_all_slots | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestMultiSlotPositional::test_each_squash_slot_writes_unique_pending_entry | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestMultiSlotPositional::test_each_unset_slot_writes_unique_pending_entry | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestMultiSlotPositional::test_each_wb_slot_writes_unique_pending_entry | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestMultipleReads::test_multiple_getReg_calls_same_cycle | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestNoWBBypass::test_getReg_does_not_see_wb_set_same_cycle | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestPendingSizing::test_pending_sq_set_sized_to_squash_width_x_max_dest_regs | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestPendingSizing::test_pending_unset_sized_to_max_rename_width_x_max_dest_regs | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestPendingSizing::test_pending_wb_set_sized_to_wb_width_x_max_dest_regs | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestReset::test_after_reset_all_bits_ready | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestReset::test_reset_clears_all_pending | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_clears_all_pending_buffers | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_clears_pending_after_commit | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_is_callee_ifc_cl | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_rdy_always_true | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_sets_pending_flag | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestSbResetValid::test_sb_reset_valid_sets_all_bits_to_1 | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestSetReg::test_set_visible_next_cycle | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestSetRegSquashBypass::test_squash_set_same_cycle_getReg_bypass | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestUnsetReg::test_unset_visible_next_cycle_not_same_cycle | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestWritePortPriority::test_squash_overrides_unset | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl.TestWritePortPriority::test_unset_overrides_wb | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_bypass_overrides_stale_state | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_global_id_zero_is_valid_when_not_ready | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_returns_committed_value_when_not_ready | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_returns_ready_after_reset | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestGetProducer::test_get_producer_same_cycle_bypass | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestInterfaceExistence::test_get_producer_port_exists | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestInterfaceExistence::test_set_producer_port_exists | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestPendingSetProducerBuffer::test_pending_cleared_after_tick | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestPendingSetProducerBuffer::test_pending_set_producer_exists | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestPendingSetProducerBuffer::test_set_producer_buffers_to_pending | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestProducerIdInit::test_state_producer_id_all_zero_after_reset | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestProducerIdInit::test_state_producer_id_exists | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestResetClearsProducerId::test_sb_reset_clears_producer_id | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestResetClearsProducerId::test_sim_reset_clears_producer_id | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetProducer::test_set_producer_not_visible_same_cycle | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetProducer::test_set_producer_overwrites_previous | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetProducer::test_set_producer_visible_next_cycle | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetRegClearsProducerId::test_set_reg_clears_producer_id | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetRegClearsProducerId::test_wb_set_req_clears_producer_id | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestSetRegSquashClearsProducerId::test_set_reg_squash_clears_producer_id | block-Scoreboard | default | PASS | - | 0 |
| test_scoreboard_cl_adr0033.TestUnsetRegPreservesProducerId::test_unset_reg_preserves_producer_id | block-Scoreboard | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_alloc_returns_index | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_alloc_until_full | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_get_by_index | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_get_oldest_returns_head | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_is_full_and_empty | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerBasic::test_release_head_fifo | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_combined_with_alloc | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_empty_list | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_head_as_new_head | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_mid_list | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_no_capacity | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_preserves_other_thread | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_reserves_but_does_not_write | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerInsertAfter::test_insert_after_tail | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerMultiThread::test_multi_thread_isolation | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerMultiThread::test_thread_independent_heads | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerMultiThread::test_thread_reset_isolated | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPendingAllocs::test_alloc_prevents_double_reservation | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPendingAllocs::test_alloc_reserves_but_does_not_write | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPendingAllocs::test_is_full_accounts_for_reserved | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPendingAllocs::test_reset_clears_pending | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPowerOfTwoConstraint::test_non_power_of_two_raises | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerPowerOfTwoConstraint::test_power_of_two_ok | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerReset::test_reset_clears_all | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerReset::test_reset_tid_none | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerSquash::test_squash_to_bulk | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerSquash::test_squash_to_head_keeps_all | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager.TestStorageManagerSquash::test_squash_to_invalid_anchor_asserts | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager_v2_request_cursor.TestPopIsNeverRefused::test_a_pop_ahead_of_the_cursor_leaves_the_cursor_alone | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager_v2_request_cursor.TestPopIsNeverRefused::test_a_pop_whose_entry_is_the_cursor_fires | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager_v2_request_cursor.TestPopIsNeverRefused::test_the_cursor_follows_a_pop_that_takes_it | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager_v2_request_cursor.TestReSeatIsIdempotent::test_a_peek_reset_seats_the_cursor_on_the_head | block-StorageManager | default | PASS | - | 0 |
| test_storage_manager_v2_request_cursor.TestReSeatIsIdempotent::test_a_second_peek_reset_for_a_thread_is_dropped_not_stacked | block-StorageManager | default | PASS | - | 0 |
| test_store_set_cl.TestCheckInst::test_check_inst_no_prediction_after_reset | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestCheckInst::test_check_inst_no_prediction_after_training_only | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestCheckInst::test_check_inst_returns_producer_after_training | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestClearCounter::test_ssit_cleared_at_threshold | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestPopulateLfst::test_populate_lfst_accumulates_multiple | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestPopulateLfst::test_populate_lfst_callee_ifc_exists | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestPopulateLfst::test_populate_lfst_updates_lfst | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestReset::test_clearcounter_zero_after_reset | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestReset::test_lfst_all_invalid_after_reset | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestReset::test_ssit_all_invalid_after_reset | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestReset::test_storelist_empty_after_reset | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_callee_ifc_exists | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_invalidates_lfst_when_no_survivors | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_invalidates_younger_stores | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_noop_when_no_younger_stores | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_recompute_multi_ssid | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_recompute_positional_youngest_survivor | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestSquash::test_squash_recompute_wraparound | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestViolation::test_violation_callee_ifc_exists | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestViolation::test_violation_increments_clear_counter | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestViolation::test_violation_sets_ssit_entries | block-StoreSet | default | PASS | - | 0 |
| test_store_set_cl.TestViolation::test_violation_two_distinct_storesets | block-StoreSet | default | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_cbo_inval_clean_flush_write_nothing | block-Testbench | default | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_cbo_zero_covers_block_lanes | block-Testbench | default | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_empty_pending_returns_none | block-Testbench | default | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_exit_store_suppressed_from_overlay | block-Testbench | default | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_lane_merge_partial_stores_youngest_wins_with_memory_fallback | block-Testbench | default | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_no_intersection_returns_none | block-Testbench | default | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_store_crossing_word_boundary_splits_across_words | block-Testbench | default | PASS | - | 0 |
| test_dcache_fwd_probe_lane::test_younger_full_store_supersedes_older_partial | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestDefaultOff::test_string_zero_is_off | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestDefaultOff::test_unset_leaves_legacy_path | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestEnabledConstruct::test_seed_and_header | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestLatencyDistribution::test_classes_are_90_9_1_within_two_points | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestLatencyDistribution::test_only_the_three_classes_exist | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestOutstandingCap::test_cap_is_inactive_when_random_is_off | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestOutstandingCap::test_cap_zero_is_unlimited | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestOutstandingCap::test_default_env_is_cap_zero | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestOutstandingCap::test_peak_outstanding_is_recorded | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestOutstandingCap::test_rdy_true_below_the_cap_and_false_at_it | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestPickReady::test_empty_queue_returns_none | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestPickReady::test_ineligible_entries_never_returned | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestPickReady::test_later_inserted_ready_entry_is_reachable | block-Testbench | default | PASS | - | 0 |
| test_icache_rand_latency.TestPickReady::test_none_eligible_returns_none_without_drawing | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_bne_not_taken_no_squash | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_double_beq_lifo_invalidation | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_jal_then_beq_uses_correct_checkpoint | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_jal_triggers_checkpoint_save | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationCheckpointRestore::test_taken_beq_mispredict_restores_checkpoint | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationDebug::test_debug_bare_minimum_exit | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationDebug::test_debug_single_nop_then_exit | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationRunElf::test_run_elf_exit_nonzero | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationRunElf::test_run_elf_exit_zero | block-Testbench | default | PASS | - | 0 |
| test_integration_run_elf.TestIntegrationRunElf::test_run_elf_nops_then_exit | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConfigurableLatency::test_mem_latency_2_delays_dcache_load_by_2_cycles | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConfigurableLatency::test_tlb_latency_1_default_delays_response_by_1_cycle | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConfigurableLatency::test_tlb_latency_2_delays_response_by_2_cycles | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_constructs_with_exit_addr | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_core_sub_component | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_elf_entry | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_exit_code | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_halted_flag | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestConstruction::test_exposes_pages_memory_dict | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheLoadResponder::test_load_req_4byte_size | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheLoadResponder::test_load_req_returns_data_after_tick | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_req_writes_to_memory_after_tick | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_to_exit_addr_captures_exit_code | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_to_exit_addr_does_not_write_memory | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_to_exit_addr_halts_testbench | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestDCacheStoreResponder::test_store_to_exit_addr_still_acks_store | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestELFLoading::test_load_elf_multiple_segments | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestELFLoading::test_load_elf_populates_memory_from_pt_load_segment | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestELFLoading::test_load_elf_sets_elf_entry | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestICacheFetchResponder::test_icache_req_fault_for_address_outside_loaded_range | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestICacheFetchResponder::test_icache_req_fault_on_unloaded_address | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestICacheFetchResponder::test_icache_req_no_fault_for_loaded_range | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestICacheFetchResponder::test_icache_req_returns_instruction_data_after_tick | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestIdentityTLB::test_dtlb_req_returns_identity_paddr_after_one_tick | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestIdentityTLB::test_dtlb_resp_uses_identity_translation | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestInitialPC::test_cfg_initial_pc_sets_bac_pc | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestInitialPC::test_cfg_initial_pc_sets_commit_state_pc | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestInitialPC::test_get_pc_returns_cfg_initial_pc | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_load_elf_segment_populates_memory | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_load_elf_segment_zero_fills_bss | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_load_segment_spans_multiple_pages | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_read_uninitialized_page_allocates_page | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_read_uninitialized_page_returns_zero | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_write_byte_boundary | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_write_does_not_corrupt_adjacent_bytes | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_write_then_read_returns_value | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestPagedSparseMemory::test_write_to_uninitialized_page_allocates_page | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestRunElfFactory::test_run_elf_raises_timeout_when_no_exit_store | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestRunElfFactory::test_run_elf_returns_exit_code_on_halt | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestVAProbeCoordinator::test_va_probe_miss_when_no_pa_arrives | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestVAProbeCoordinator::test_va_probe_odd_cacheline_misses | block-Testbench | default | PASS | - | 0 |
| test_o3_core_bare_metal_tb_cl.TestVAProbeCoordinator::test_va_probe_resp_fires_2_cycles_after_req | block-Testbench | default | PASS | - | 0 |
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_core_frontend_carries_the_v2_blocks | block-Testbench | default | PASS | - | 0 |
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_core_frontend_is_frontend_v2 | block-Testbench | default | PASS | - | 0 |
| test_o3_core_v2.TestCoreBuildsV2Frontend::test_v2_core_exposes_the_testbench_surface | block-Testbench | default | PASS | - | 0 |
| test_o3_core_v2.TestElfOnV2Core::test_rv64ui_p_add_passes_on_v2 | block-Testbench | default | PASS | - | 6 |
| test_o3_core_v2.TestElfOnV2Core::test_v2_core_commits_instructions_and_retires_stores | block-Testbench | default | PASS | - | 6 |
| test_o3_core_v2.TestFetchTargetPairingLaw::test_d14s_act_less_row_is_never_reached | block-Testbench | default | PASS | - | 0 |
| test_o3_core_v2.TestFetchTargetPairingLaw::test_every_claim_becomes_a_stage_or_is_destroyed_once | block-Testbench | default | PASS | - | 0 |
| test_o3_core_v2.TestFetchTargetPairingLaw::test_every_queued_fetch_target_leaves_the_queue_exactly_once | block-Testbench | default | PASS | - | 6 |
| test_o3_core_v2.TestFetchTargetPairingLaw::test_one_request_per_fetch_target_presented | block-Testbench | default | PASS | - | 0 |
| test_o3_core_v2.TestFetchTargetPairingLaw::test_the_fill_is_the_only_pop | block-Testbench | default | PASS | - | 0 |
| test_o3_core_v2.TestNackChainOrdering::test_elf_reaches_exit_on_every_schedule_seed | block-Testbench | default | PASS | - | 35 |
| test_o3_core_v2.TestNackChainOrdering::test_no_seed_stalls_the_frontend | block-Testbench | default | PASS | - | 35 |
| test_o3_core_v2.TestNackChainOrdering::test_the_sweep_actually_executed_the_frontend | block-Testbench | default | PASS | - | 7 |
| test_riscv_tests_isa::test_riscv_tests_smoke_add | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-add:R-type addition] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addi:I-type add immediate] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addiw:IW-type add immediate] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-addw:R-type add word] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-and:R-type AND] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-andi:I-type AND immediate] | block-Testbench | default | PASS | - | 3 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-auipc:add upper immediate to PC] | block-Testbench | default | PASS | - | 2 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-beq:branch equal] | block-Testbench | default | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bge:branch greater equal] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bgeu:branch greater equal unsigned] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-blt:branch less than] | block-Testbench | default | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bltu:branch less than unsigned] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-bne:branch not equal] | block-Testbench | default | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-fence_i:instruction fence] | block-Testbench | default | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-jal:jump and link] | block-Testbench | default | PASS | - | 1 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-jalr:jump and link register] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lb:load byte] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lbu:load byte unsigned] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-ld:load double] | block-Testbench | default | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lh:load half] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lhu:load half unsigned] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lui:load upper immediate] | block-Testbench | default | PASS | - | 2 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lw:load word] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-lwu:load word unsigned] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-or:R-type OR] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-ori:I-type OR immediate] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sb:store byte] | block-Testbench | default | PASS | - | 5 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sd:store double] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sh:store half] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sll:shift left logical] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slli:shift left logical immediate] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sllw:shift left logical word] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slt:set less than] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-slti:set less than immediate] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sltiu:set less than immediate unsigned] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sltu:set less than unsigned] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sra:shift right arithmetic] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srai:shift right arithmetic immediate] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sraw:shift right arithmetic word] | block-Testbench | default | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srl:shift right logical] | block-Testbench | default | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srli:shift right logical immediate] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-srlw:shift right logical word] | block-Testbench | default | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sub:R-type subtraction] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-subw:R-type sub word] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sw:store word] | block-Testbench | default | PASS | - | 6 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-xor:R-type XOR] | block-Testbench | default | PASS | - | 7 |
| test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-xori:I-type XOR immediate] | block-Testbench | default | PASS | - | 4 |
| test_riscv_tests_isa::test_rv64uziccid_p_ziccid | block-Testbench | default | PASS | - | 19 |
| test_sbuf_fence_gate_wiring::test_absorbed_store_holds_commit_gate_through_tb_wire | block-Testbench | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestEdgeCases::test_second_tlbi_req_after_first_completes | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestEdgeCases::test_sync_comp_before_inv_sent_ignored_or_buffered | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestIntegrationWithLSQ::test_integration_controller_with_lsq | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestInvSent::test_inv_sent_after_in_flight | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestMultipleTids::test_multiple_tids_independent | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiComplete::test_no_spurious_complete_without_sync_comp | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiComplete::test_state_cleared_after_complete | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiComplete::test_tlbi_complete_after_sync_comp | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiReq::test_tlbi_req_committed_in_update_ff | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiReq::test_tlbi_req_does_not_fire_immediately | block-TlbiController | default | PASS | - | 0 |
| test_tlbi_controller_cl.TestTlbiReq::test_tlbi_req_sets_pending | block-TlbiController | default | PASS | - | 0 |
| test_write_back_cl.TestBranchForwarding::test_mispredict_calls_wb_mispredict | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestBranchForwarding::test_no_mispredict_no_call | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestBranchForwarding::test_squashed_mispredict_not_forwarded | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestCSRWrite::test_csr_write_called_when_csr_write_valid_true | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestCSRWrite::test_csr_write_skipped_when_csr_write_valid_false | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestCSRWrite::test_squashed_csr_write_skipped | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestCSRWrite::test_wb_csr_write_port_exists | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestDecrWbOutstanding::test_normal_completion_ignores_decr_wb_outstanding | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_buffers_completion | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_calls_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_decrements_counter | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_marks_slot_processed | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_port_exists | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestDirectComplete::test_direct_complete_squashed_skips_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultForwarding::test_fault_calls_wb_fault | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultForwarding::test_no_fault_no_call | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultSuppressesStateWrites::test_fault_detect_csr_completion_keeps_rob_update_and_wb_fault | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultSuppressesStateWrites::test_fault_detect_csr_completion_no_csr_no_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultSuppressesStateWrites::test_fault_detect_fcsr_family_no_fflags_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultSuppressesStateWrites::test_lsq_fault_carrier_suppresses_state_writes | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultSuppressesStateWrites::test_non_faulting_csr_completion_still_writes | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultTvalF1::test_fupool_fault_forwards_stamped_tval | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFaultTvalF1::test_return_target_overloading_stays | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuComplete::test_fu_complete_buffers_into_pending | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuComplete::test_multiple_completions_buffered | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_construct_with_wbinfo | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_has_branch_fields | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_has_fault_fields | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_has_squashed_field | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_has_wbinfo_field | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_no_trap_fields | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestFuCompleteBundle::test_bundle_wbinfo_defaults_to_empty | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_after_reset_counter_is_zero | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_after_reset_squash_boundary_is_zero | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_fu_complete_decrements_counter | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_ic_squash_updates_boundary | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestInFlightCounter::test_ro_inst_issued_increments_counter | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_rf_write_called_with_two_individual_args | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_wb_csr_write_called_with_three_individual_args | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_wb_fault_called_with_three_individual_args | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_wb_mispredict_called_with_four_individual_args | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestIndividualParams::test_wb_rob_update_called_with_single_wbtorobupdate_object | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestInterfaces::test_caller_ports_exist | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestInterfaces::test_fu_complete_callee_exists | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_lsq_rdy_false_when_buffer_full | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_lsq_rdy_recovers_after_process | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_lsq_rdy_true_when_buffer_has_space | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_lsq_rejected_when_rdy_false | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestLSQBackpressure::test_squashed_completion_skips_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestLSQExecuteResp::test_lsq_execute_resp_callee_exists | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestLSQExecuteResp::test_lsq_load_completion_calls_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestLSQExecuteResp::test_lsq_store_completion_no_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPendingWBQueue::test_fifo_order_preserved | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPendingWBQueue::test_pop_time_squash_with_writeback_width | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPendingWBQueue::test_writeback_width_does_not_drop_completions | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPendingWBQueue::test_writeback_width_limits_processing_per_cycle | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_class_of_phys_reg_helper | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_float_class_dest_routes_to_float_port | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_int_class_dest_routes_to_int_port | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_int_dest_does_not_route_to_float_port | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_multi_dest_different_classes_route_to_different_ports | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestPerClassCrossbar::test_two_int_dests_use_two_int_ports | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestProcessing::test_invalid_slot_skipped | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestProcessing::test_process_clears_after_next_tick | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestProcessing::test_process_marks_processed | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestROBUpdate::test_fault_forwarded_in_rob_update | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestROBUpdate::test_normal_completion_calls_wb_rob_update | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestROBUpdate::test_squashed_completion_skips_rob_update | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestReset::test_after_reset_all_slots_empty | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestReset::test_after_reset_next_slot_zero | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestRfWriteSetReg::test_multi_dest_completion_calls_rf_write_per_dest | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestRfWriteSetReg::test_normal_completion_calls_rf_write_with_dest_phys_reg | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestRfWriteSetReg::test_normal_completion_does_not_fire_sb_setreg | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestRfWriteSetReg::test_squashed_completion_skips_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestSquashAtCompletion::test_seqnum_above_boundary_skips_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_cleared_after_all_inflight_drained | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_not_cleared_while_completion_in_buffer | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_not_cleared_while_inflight_remaining | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestSquashedBypass::test_squashed_marks_slot_processed | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_construct_with_values | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_dest_phys_reg_defaults_to_zero | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_has_csr_num_field | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_has_csr_write_valid_field | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_has_dest_phys_reg_field | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWBInfo::test_wbinfo_has_flags_field | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWritePortOverflowProtection::test_overflow_bypass_query_returns_hit_for_overflow_completion | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWritePortOverflowProtection::test_overflow_does_not_crash | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl.TestWritePortOverflowProtection::test_overflow_drops_excess_rf_write | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_misses_for_squashed_completion | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_port_exists | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_returns_hit_for_matching_phys_reg | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_returns_hit_for_second_dest | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_returns_miss_for_unknown_phys_reg | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestBypassQueryInterface::test_bypass_query_returns_miss_when_buf_empty | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestSbSetRegRemovedFromWriteBack::test_normal_completion_does_not_fire_sb_setReg | block-WriteBack | default | PASS | - | 0 |
| test_write_back_cl_adr0033_primary.TestSbSetRegRemovedFromWriteBack::test_sb_setReg_caller_ifc_removed | block-WriteBack | default | PASS | - | 0 |
| rv64mi-p-breakpoint | cosim-p | default | FAIL | - | 6 |
| rv64mi-p-csr | cosim-p | default | FAIL | - | 8 |
| rv64mi-p-illegal | cosim-p | default | FAIL | - | 6 |
| rv64mi-p-instret_overflow | cosim-p | default | PASS | - | 5 |
| rv64mi-p-ld-misaligned | cosim-p | default | PASS | - | 7 |
| rv64mi-p-lh-misaligned | cosim-p | default | PASS | - | 5 |
| rv64mi-p-lw-misaligned | cosim-p | default | PASS | - | 6 |
| rv64mi-p-ma_addr | cosim-p | default | PASS | - | 7 |
| rv64mi-p-ma_fetch | cosim-p | default | FAIL | - | 5 |
| rv64mi-p-mcsr | cosim-p | default | FAIL | - | 4 |
| rv64mi-p-pmpaddr | cosim-p | default | FAIL | - | 5 |
| rv64mi-p-sbreak | cosim-p | default | PASS | - | 5 |
| rv64mi-p-scall | cosim-p | default | FAIL | - | 5 |
| rv64mi-p-sd-misaligned | cosim-p | default | PASS | - | 7 |
| rv64mi-p-sh-misaligned | cosim-p | default | PASS | - | 5 |
| rv64mi-p-sw-misaligned | cosim-p | default | PASS | - | 6 |
| rv64mi-p-zicntr | cosim-p | default | PASS | - | 6 |
| rv64mzicbo-p-zero | cosim-p | default | PASS | - | 5 |
| rv64si-p-csr | cosim-p | default | FAIL | - | 4 |
| rv64si-p-dirty | cosim-p | default | PASS | - | 9 |
| rv64si-p-icache-alias | cosim-p | default | FAIL | - | 10 |
| rv64si-p-ma_fetch | cosim-p | default | FAIL | - | 4 |
| rv64si-p-sbreak | cosim-p | default | FAIL | - | 4 |
| rv64si-p-scall | cosim-p | default | FAIL | - | 4 |
| rv64si-p-wfi | cosim-p | default | FAIL | - | 5 |
| rv64ssvnapot-p-napot | cosim-p | default | PASS | - | 8 |
| rv64ua-p-amoadd_d | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amoadd_w | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amoand_d | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amoand_w | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amomax_d | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amomax_w | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amomaxu_d | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amomaxu_w | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amomin_d | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amomin_w | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amominu_d | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amominu_w | cosim-p | default | PASS | - | 6 |
| rv64ua-p-amoor_d | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amoor_w | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amoswap_d | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amoswap_w | cosim-p | default | PASS | - | 5 |
| rv64ua-p-amoxor_d | cosim-p | default | PASS | - | 6 |
| rv64ua-p-amoxor_w | cosim-p | default | PASS | - | 5 |
| rv64ua-p-lrsc | cosim-p | default | PASS | - | 82 |
| rv64uc-p-rvc | cosim-p | default | PASS | - | 7 |
| rv64ud-p-fadd | cosim-p | default | PASS | - | 8 |
| rv64ud-p-fclass | cosim-p | default | PASS | - | 6 |
| rv64ud-p-fcmp | cosim-p | default | PASS | - | 8 |
| rv64ud-p-fcvt | cosim-p | default | PASS | - | 8 |
| rv64ud-p-fcvt_w | cosim-p | default | PASS | - | 15 |
| rv64ud-p-fdiv | cosim-p | default | PASS | - | 7 |
| rv64ud-p-fmadd | cosim-p | default | PASS | - | 8 |
| rv64ud-p-fmin | cosim-p | default | PASS | - | 10 |
| rv64ud-p-ldst | cosim-p | default | PASS | - | 5 |
| rv64ud-p-move | cosim-p | default | PASS | - | 13 |
| rv64ud-p-recoding | cosim-p | default | PASS | - | 6 |
| rv64ud-p-structural | cosim-p | default | PASS | - | 8 |
| rv64uf-p-fadd | cosim-p | default | PASS | - | 8 |
| rv64uf-p-fclass | cosim-p | default | PASS | - | 6 |
| rv64uf-p-fcmp | cosim-p | default | PASS | - | 9 |
| rv64uf-p-fcvt | cosim-p | default | PASS | - | 7 |
| rv64uf-p-fcvt_w | cosim-p | default | PASS | - | 14 |
| rv64uf-p-fdiv | cosim-p | default | PASS | - | 7 |
| rv64uf-p-fmadd | cosim-p | default | PASS | - | 9 |
| rv64uf-p-fmin | cosim-p | default | PASS | - | 10 |
| rv64uf-p-ldst | cosim-p | default | PASS | - | 5 |
| rv64uf-p-move | cosim-p | default | PASS | - | 8 |
| rv64uf-p-recoding | cosim-p | default | PASS | - | 6 |
| rv64ui-p-add | cosim-p | default | PASS | - | 12 |
| rv64ui-p-addi | cosim-p | default | PASS | - | 8 |
| rv64ui-p-addiw | cosim-p | default | PASS | - | 8 |
| rv64ui-p-addw | cosim-p | default | PASS | - | 12 |
| rv64ui-p-and | cosim-p | default | PASS | - | 12 |
| rv64ui-p-andi | cosim-p | default | PASS | - | 7 |
| rv64ui-p-auipc | cosim-p | default | PASS | - | 5 |
| rv64ui-p-beq | cosim-p | default | PASS | - | 10 |
| rv64ui-p-bge | cosim-p | default | PASS | - | 11 |
| rv64ui-p-bgeu | cosim-p | default | PASS | - | 12 |
| rv64ui-p-blt | cosim-p | default | PASS | - | 11 |
| rv64ui-p-bltu | cosim-p | default | PASS | - | 12 |
| rv64ui-p-bne | cosim-p | default | PASS | - | 11 |
| rv64ui-p-fence_i | cosim-p | default | PASS | - | 9 |
| rv64ui-p-jal | cosim-p | default | PASS | - | 5 |
| rv64ui-p-jalr | cosim-p | default | PASS | - | 8 |
| rv64ui-p-lb | cosim-p | default | PASS | - | 8 |
| rv64ui-p-lbu | cosim-p | default | PASS | - | 8 |
| rv64ui-p-ld | cosim-p | default | PASS | - | 10 |
| rv64ui-p-ld_st | cosim-p | default | PASS | - | 24 |
| rv64ui-p-lh | cosim-p | default | PASS | - | 8 |
| rv64ui-p-lhu | cosim-p | default | PASS | - | 9 |
| rv64ui-p-lui | cosim-p | default | PASS | - | 5 |
| rv64ui-p-lw | cosim-p | default | PASS | - | 9 |
| rv64ui-p-lwu | cosim-p | default | PASS | - | 9 |
| rv64ui-p-ma_data | cosim-p | default | PASS | - | 51 |
| rv64ui-p-or | cosim-p | default | PASS | - | 13 |
| rv64ui-p-ori | cosim-p | default | PASS | - | 7 |
| rv64ui-p-sb | cosim-p | default | PASS | - | 11 |
| rv64ui-p-sd | cosim-p | default | PASS | - | 13 |
| rv64ui-p-sh | cosim-p | default | PASS | - | 11 |
| rv64ui-p-simple | cosim-p | default | PASS | - | 5 |
| rv64ui-p-sll | cosim-p | default | PASS | - | 12 |
| rv64ui-p-slli | cosim-p | default | PASS | - | 8 |
| rv64ui-p-slliw | cosim-p | default | PASS | - | 8 |
| rv64ui-p-sllw | cosim-p | default | PASS | - | 13 |
| rv64ui-p-slt | cosim-p | default | PASS | - | 12 |
| rv64ui-p-slti | cosim-p | default | PASS | - | 8 |
| rv64ui-p-sltiu | cosim-p | default | PASS | - | 8 |
| rv64ui-p-sltu | cosim-p | default | PASS | - | 12 |
| rv64ui-p-sra | cosim-p | default | PASS | - | 12 |
| rv64ui-p-srai | cosim-p | default | PASS | - | 8 |
| rv64ui-p-sraiw | cosim-p | default | PASS | - | 8 |
| rv64ui-p-sraw | cosim-p | default | PASS | - | 13 |
| rv64ui-p-srl | cosim-p | default | PASS | - | 13 |
| rv64ui-p-srli | cosim-p | default | PASS | - | 8 |
| rv64ui-p-srliw | cosim-p | default | PASS | - | 9 |
| rv64ui-p-srlw | cosim-p | default | PASS | - | 13 |
| rv64ui-p-st_ld | cosim-p | default | PASS | - | 9 |
| rv64ui-p-sub | cosim-p | default | PASS | - | 12 |
| rv64ui-p-subw | cosim-p | default | PASS | - | 12 |
| rv64ui-p-sw | cosim-p | default | PASS | - | 11 |
| rv64ui-p-xor | cosim-p | default | PASS | - | 13 |
| rv64ui-p-xori | cosim-p | default | PASS | - | 8 |
| rv64um-p-div | cosim-p | default | PASS | - | 5 |
| rv64um-p-divu | cosim-p | default | PASS | - | 6 |
| rv64um-p-divuw | cosim-p | default | PASS | - | 5 |
| rv64um-p-divw | cosim-p | default | PASS | - | 6 |
| rv64um-p-mul | cosim-p | default | PASS | - | 12 |
| rv64um-p-mulh | cosim-p | default | PASS | - | 12 |
| rv64um-p-mulhsu | cosim-p | default | PASS | - | 12 |
| rv64um-p-mulhu | cosim-p | default | PASS | - | 12 |
| rv64um-p-mulw | cosim-p | default | PASS | - | 11 |
| rv64um-p-rem | cosim-p | default | PASS | - | 5 |
| rv64um-p-remu | cosim-p | default | PASS | - | 6 |
| rv64um-p-remuw | cosim-p | default | PASS | - | 5 |
| rv64um-p-remw | cosim-p | default | PASS | - | 5 |
| rv64uzba-p-add_uw | cosim-p | default | PASS | - | 12 |
| rv64uzba-p-sh1add | cosim-p | default | PASS | - | 12 |
| rv64uzba-p-sh1add_uw | cosim-p | default | PASS | - | 12 |
| rv64uzba-p-sh2add | cosim-p | default | PASS | - | 12 |
| rv64uzba-p-sh2add_uw | cosim-p | default | PASS | - | 12 |
| rv64uzba-p-sh3add | cosim-p | default | PASS | - | 11 |
| rv64uzba-p-sh3add_uw | cosim-p | default | PASS | - | 12 |
| rv64uzba-p-slli_uw | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-andn | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-clz | cosim-p | default | PASS | - | 7 |
| rv64uzbb-p-clzw | cosim-p | default | PASS | - | 7 |
| rv64uzbb-p-cpop | cosim-p | default | PASS | - | 7 |
| rv64uzbb-p-cpopw | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-ctz | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-ctzw | cosim-p | default | PASS | - | 7 |
| rv64uzbb-p-max | cosim-p | default | PASS | - | 12 |
| rv64uzbb-p-maxu | cosim-p | default | PASS | - | 12 |
| rv64uzbb-p-min | cosim-p | default | PASS | - | 11 |
| rv64uzbb-p-minu | cosim-p | default | PASS | - | 12 |
| rv64uzbb-p-orc_b | cosim-p | default | PASS | - | 7 |
| rv64uzbb-p-orn | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-rev8 | cosim-p | default | PASS | - | 7 |
| rv64uzbb-p-rol | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-rolw | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-ror | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-rori | cosim-p | default | PASS | - | 9 |
| rv64uzbb-p-roriw | cosim-p | default | PASS | - | 7 |
| rv64uzbb-p-rorw | cosim-p | default | PASS | - | 12 |
| rv64uzbb-p-sext_b | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-sext_h | cosim-p | default | PASS | - | 7 |
| rv64uzbb-p-xnor | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-zext_h | cosim-p | default | PASS | - | 7 |
| rv64uzbc-p-clmul | cosim-p | default | PASS | - | 12 |
| rv64uzbc-p-clmulh | cosim-p | default | PASS | - | 12 |
| rv64uzbc-p-clmulr | cosim-p | default | PASS | - | 12 |
| rv64uzbkb-p-brev8 | cosim-p | default | PASS | - | 8 |
| rv64uzbkb-p-pack | cosim-p | default | PASS | - | 14 |
| rv64uzbkb-p-packh | cosim-p | default | PASS | - | 13 |
| rv64uzbkb-p-packw | cosim-p | default | PASS | - | 12 |
| rv64uzbkx-p-xperm4 | cosim-p | default | PASS | - | 13 |
| rv64uzbkx-p-xperm8 | cosim-p | default | PASS | - | 18 |
| rv64uzbs-p-bclr | cosim-p | default | PASS | - | 13 |
| rv64uzbs-p-bclri | cosim-p | default | PASS | - | 8 |
| rv64uzbs-p-bext | cosim-p | default | PASS | - | 13 |
| rv64uzbs-p-bexti | cosim-p | default | PASS | - | 8 |
| rv64uzbs-p-binv | cosim-p | default | PASS | - | 12 |
| rv64uzbs-p-binvi | cosim-p | default | PASS | - | 8 |
| rv64uzbs-p-bset | cosim-p | default | PASS | - | 14 |
| rv64uzbs-p-bseti | cosim-p | default | PASS | - | 8 |
| rv64uzfh-p-fadd | cosim-p | default | PASS | - | 8 |
| rv64uzfh-p-fclass | cosim-p | default | PASS | - | 6 |
| rv64uzfh-p-fcmp | cosim-p | default | PASS | - | 7 |
| rv64uzfh-p-fcvt | cosim-p | default | PASS | - | 7 |
| rv64uzfh-p-fcvt_w | cosim-p | default | PASS | - | 14 |
| rv64uzfh-p-fdiv | cosim-p | default | PASS | - | 7 |
| rv64uzfh-p-fmadd | cosim-p | default | PASS | - | 8 |
| rv64uzfh-p-fmin | cosim-p | default | PASS | - | 11 |
| rv64uzfh-p-ldst | cosim-p | default | PASS | - | 6 |
| rv64uzfh-p-move | cosim-p | default | PASS | - | 8 |
| rv64uzfh-p-recoding | cosim-p | default | PASS | - | 5 |
| rv64uzicond-p-czero_eqz | cosim-p | default | PASS | - | 9 |
| rv64uzicond-p-czero_nez | cosim-p | default | PASS | - | 8 |
| rv64ua-v-amoadd_d | cosim-v | default | PASS | - | 139 |
| rv64ua-v-amoadd_w | cosim-v | default | PASS | - | 116 |
| rv64ua-v-amoand_d | cosim-v | default | PASS | - | 140 |
| rv64ua-v-amoand_w | cosim-v | default | PASS | - | 141 |
| rv64ua-v-amomax_d | cosim-v | default | PASS | - | 115 |
| rv64ua-v-amomax_w | cosim-v | default | PASS | - | 112 |
| rv64ua-v-amomaxu_d | cosim-v | default | PASS | - | 105 |
| rv64ua-v-amomaxu_w | cosim-v | default | PASS | - | 114 |
| rv64ua-v-amomin_d | cosim-v | default | PASS | - | 107 |
| rv64ua-v-amomin_w | cosim-v | default | PASS | - | 117 |
| rv64ua-v-amominu_d | cosim-v | default | PASS | - | 131 |
| rv64ua-v-amominu_w | cosim-v | default | PASS | - | 144 |
| rv64ua-v-amoor_d | cosim-v | default | PASS | - | 113 |
| rv64ua-v-amoor_w | cosim-v | default | PASS | - | 112 |
| rv64ua-v-amoswap_d | cosim-v | default | PASS | - | 136 |
| rv64ua-v-amoswap_w | cosim-v | default | PASS | - | 113 |
| rv64ua-v-amoxor_d | cosim-v | default | PASS | - | 112 |
| rv64ua-v-amoxor_w | cosim-v | default | PASS | - | 116 |
| rv64ua-v-lrsc | cosim-v | default | PASS | - | 259 |
| rv64uc-v-rvc | cosim-v | default | PASS | - | 172 |
| rv64ud-v-fadd | cosim-v | default | PASS | - | 148 |
| rv64ud-v-fclass | cosim-v | default | PASS | - | 79 |
| rv64ud-v-fcmp | cosim-v | default | PASS | - | 121 |
| rv64ud-v-fcvt | cosim-v | default | PASS | - | 115 |
| rv64ud-v-fcvt_w | cosim-v | default | PASS | - | 164 |
| rv64ud-v-fdiv | cosim-v | default | PASS | - | 116 |
| rv64ud-v-fmadd | cosim-v | default | PASS | - | 118 |
| rv64ud-v-fmin | cosim-v | default | PASS | - | 121 |
| rv64ud-v-ldst | cosim-v | default | PASS | - | 129 |
| rv64ud-v-move | cosim-v | default | PASS | - | 161 |
| rv64ud-v-recoding | cosim-v | default | PASS | - | 114 |
| rv64ud-v-structural | cosim-v | default | PASS | - | 66 |
| rv64uf-v-fadd | cosim-v | default | PASS | - | 145 |
| rv64uf-v-fclass | cosim-v | default | PASS | - | 64 |
| rv64uf-v-fcmp | cosim-v | default | PASS | - | 118 |
| rv64uf-v-fcvt | cosim-v | default | PASS | - | 118 |
| rv64uf-v-fcvt_w | cosim-v | default | PASS | - | 238 |
| rv64uf-v-fdiv | cosim-v | default | PASS | - | 121 |
| rv64uf-v-fmadd | cosim-v | default | PASS | - | 154 |
| rv64uf-v-fmin | cosim-v | default | PASS | - | 155 |
| rv64uf-v-ldst | cosim-v | default | PASS | - | 114 |
| rv64uf-v-move | cosim-v | default | PASS | - | 65 |
| rv64uf-v-recoding | cosim-v | default | PASS | - | 105 |
| rv64ui-v-add | cosim-v | default | PASS | - | 70 |
| rv64ui-v-addi | cosim-v | default | PASS | - | 59 |
| rv64ui-v-addiw | cosim-v | default | PASS | - | 65 |
| rv64ui-v-addw | cosim-v | default | PASS | - | 81 |
| rv64ui-v-and | cosim-v | default | PASS | - | 87 |
| rv64ui-v-andi | cosim-v | default | PASS | - | 66 |
| rv64ui-v-auipc | cosim-v | default | PASS | - | 62 |
| rv64ui-v-beq | cosim-v | default | PASS | - | 82 |
| rv64ui-v-bge | cosim-v | default | PASS | - | 69 |
| rv64ui-v-bgeu | cosim-v | default | PASS | - | 70 |
| rv64ui-v-blt | cosim-v | default | PASS | - | 69 |
| rv64ui-v-bltu | cosim-v | default | PASS | - | 84 |
| rv64ui-v-bne | cosim-v | default | PASS | - | 70 |
| rv64ui-v-fence_i | cosim-v | default | PASS | - | 147 |
| rv64ui-v-jal | cosim-v | default | PASS | - | 77 |
| rv64ui-v-jalr | cosim-v | default | PASS | - | 63 |
| rv64ui-v-lb | cosim-v | default | PASS | - | 117 |
| rv64ui-v-lbu | cosim-v | default | PASS | - | 103 |
| rv64ui-v-ld | cosim-v | default | PASS | - | 120 |
| rv64ui-v-ld_st | cosim-v | default | PASS | - | 253 |
| rv64ui-v-lh | cosim-v | default | PASS | - | 121 |
| rv64ui-v-lhu | cosim-v | default | PASS | - | 135 |
| rv64ui-v-lui | cosim-v | default | PASS | - | 77 |
| rv64ui-v-lw | cosim-v | default | PASS | - | 118 |
| rv64ui-v-lwu | cosim-v | default | PASS | - | 117 |
| rv64ui-v-ma_data | cosim-v | default | PASS | - | 301 |
| rv64ui-v-or | cosim-v | default | PASS | - | 72 |
| rv64ui-v-ori | cosim-v | default | PASS | - | 67 |
| rv64ui-v-sb | cosim-v | default | PASS | - | 121 |
| rv64ui-v-sd | cosim-v | default | PASS | - | 218 |
| rv64ui-v-sh | cosim-v | default | PASS | - | 122 |
| rv64ui-v-simple | cosim-v | default | PASS | - | 76 |
| rv64ui-v-sll | cosim-v | default | PASS | - | 149 |
| rv64ui-v-slli | cosim-v | default | PASS | - | 62 |
| rv64ui-v-slliw | cosim-v | default | PASS | - | 67 |
| rv64ui-v-sllw | cosim-v | default | PASS | - | 103 |
| rv64ui-v-slt | cosim-v | default | PASS | - | 71 |
| rv64ui-v-slti | cosim-v | default | PASS | - | 63 |
| rv64ui-v-sltiu | cosim-v | default | PASS | - | 67 |
| rv64ui-v-sltu | cosim-v | default | PASS | - | 82 |
| rv64ui-v-sra | cosim-v | default | PASS | - | 85 |
| rv64ui-v-srai | cosim-v | default | PASS | - | 67 |
| rv64ui-v-sraiw | cosim-v | default | PASS | - | 67 |
| rv64ui-v-sraw | cosim-v | default | PASS | - | 150 |
| rv64ui-v-srl | cosim-v | default | PASS | - | 121 |
| rv64ui-v-srli | cosim-v | default | PASS | - | 66 |
| rv64ui-v-srliw | cosim-v | default | PASS | - | 68 |
| rv64ui-v-srlw | cosim-v | default | PASS | - | 147 |
| rv64ui-v-st_ld | cosim-v | default | PASS | - | 164 |
| rv64ui-v-sub | cosim-v | default | PASS | - | 86 |
| rv64ui-v-subw | cosim-v | default | PASS | - | 87 |
| rv64ui-v-sw | cosim-v | default | PASS | - | 111 |
| rv64ui-v-xor | cosim-v | default | PASS | - | 72 |
| rv64ui-v-xori | cosim-v | default | PASS | - | 56 |
| rv64um-v-div | cosim-v | default | PASS | - | 64 |
| rv64um-v-divu | cosim-v | default | PASS | - | 60 |
| rv64um-v-divuw | cosim-v | default | PASS | - | 64 |
| rv64um-v-divw | cosim-v | default | PASS | - | 73 |
| rv64um-v-mul | cosim-v | default | PASS | - | 84 |
| rv64um-v-mulh | cosim-v | default | PASS | - | 70 |
| rv64um-v-mulhsu | cosim-v | default | PASS | - | 70 |
| rv64um-v-mulhu | cosim-v | default | PASS | - | 86 |
| rv64um-v-mulw | cosim-v | default | PASS | - | 71 |
| rv64um-v-rem | cosim-v | default | PASS | - | 63 |
| rv64um-v-remu | cosim-v | default | PASS | - | 64 |
| rv64um-v-remuw | cosim-v | default | PASS | - | 75 |
| rv64um-v-remw | cosim-v | default | PASS | - | 65 |
| rv64uzba-v-add_uw | cosim-v | default | PASS | - | 87 |
| rv64uzba-v-sh1add | cosim-v | default | PASS | - | 85 |
| rv64uzba-v-sh1add_uw | cosim-v | default | PASS | - | 68 |
| rv64uzba-v-sh2add | cosim-v | default | PASS | - | 71 |
| rv64uzba-v-sh2add_uw | cosim-v | default | PASS | - | 60 |
| rv64uzba-v-sh3add | cosim-v | default | PASS | - | 72 |
| rv64uzba-v-sh3add_uw | cosim-v | default | PASS | - | 68 |
| rv64uzba-v-slli_uw | cosim-v | default | PASS | - | 67 |
| rv64uzbb-v-andn | cosim-v | default | PASS | - | 81 |
| rv64uzbb-v-clz | cosim-v | default | PASS | - | 59 |
| rv64uzbb-v-clzw | cosim-v | default | PASS | - | 66 |
| rv64uzbb-v-cpop | cosim-v | default | PASS | - | 65 |
| rv64uzbb-v-cpopw | cosim-v | default | PASS | - | 76 |
| rv64uzbb-v-ctz | cosim-v | default | PASS | - | 67 |
| rv64uzbb-v-ctzw | cosim-v | default | PASS | - | 62 |
| rv64uzbb-v-max | cosim-v | default | PASS | - | 67 |
| rv64uzbb-v-maxu | cosim-v | default | PASS | - | 72 |
| rv64uzbb-v-min | cosim-v | default | PASS | - | 72 |
| rv64uzbb-v-minu | cosim-v | default | PASS | - | 85 |
| rv64uzbb-v-orc_b | cosim-v | default | PASS | - | 80 |
| rv64uzbb-v-orn | cosim-v | default | PASS | - | 108 |
| rv64uzbb-v-rev8 | cosim-v | default | PASS | - | 66 |
| rv64uzbb-v-rol | cosim-v | default | PASS | - | 90 |
| rv64uzbb-v-rolw | cosim-v | default | PASS | - | 120 |
| rv64uzbb-v-ror | cosim-v | default | PASS | - | 124 |
| rv64uzbb-v-rori | cosim-v | default | PASS | - | 67 |
| rv64uzbb-v-roriw | cosim-v | default | PASS | - | 73 |
| rv64uzbb-v-rorw | cosim-v | default | PASS | - | 68 |
| rv64uzbb-v-sext_b | cosim-v | default | PASS | - | 64 |
| rv64uzbb-v-sext_h | cosim-v | default | PASS | - | 64 |
| rv64uzbb-v-xnor | cosim-v | default | PASS | - | 110 |
| rv64uzbb-v-zext_h | cosim-v | default | PASS | - | 67 |
| rv64uzbc-v-clmul | cosim-v | default | PASS | - | 51 |
| rv64uzbc-v-clmulh | cosim-v | default | PASS | - | 69 |
| rv64uzbc-v-clmulr | cosim-v | default | PASS | - | 69 |
| rv64uzbkb-v-brev8 | cosim-v | default | PASS | - | 67 |
| rv64uzbkb-v-pack | cosim-v | default | PASS | - | 103 |
| rv64uzbkb-v-packh | cosim-v | default | PASS | - | 81 |
| rv64uzbkb-v-packw | cosim-v | default | PASS | - | 65 |
| rv64uzbkx-v-xperm4 | cosim-v | default | PASS | - | 97 |
| rv64uzbkx-v-xperm8 | cosim-v | default | PASS | - | 92 |
| rv64uzbs-v-bclr | cosim-v | default | PASS | - | 96 |
| rv64uzbs-v-bclri | cosim-v | default | PASS | - | 66 |
| rv64uzbs-v-bext | cosim-v | default | PASS | - | 99 |
| rv64uzbs-v-bexti | cosim-v | default | PASS | - | 64 |
| rv64uzbs-v-binv | cosim-v | default | PASS | - | 103 |
| rv64uzbs-v-binvi | cosim-v | default | PASS | - | 60 |
| rv64uzbs-v-bset | cosim-v | default | PASS | - | 80 |
| rv64uzbs-v-bseti | cosim-v | default | PASS | - | 54 |
| rv64uzfh-v-fadd | cosim-v | default | PASS | - | 75 |
| rv64uzfh-v-fclass | cosim-v | default | PASS | - | 53 |
| rv64uzfh-v-fcmp | cosim-v | default | PASS | - | 92 |
| rv64uzfh-v-fcvt | cosim-v | default | PASS | - | 95 |
| rv64uzfh-v-fcvt_w | cosim-v | default | PASS | - | 135 |
| rv64uzfh-v-fdiv | cosim-v | default | PASS | - | 92 |
| rv64uzfh-v-fmadd | cosim-v | default | PASS | - | 88 |
| rv64uzfh-v-fmin | cosim-v | default | PASS | - | 73 |
| rv64uzfh-v-ldst | cosim-v | default | PASS | - | 71 |
| rv64uzfh-v-move | cosim-v | default | PASS | - | 50 |
| rv64uzfh-v-recoding | cosim-v | default | PASS | - | 93 |
| rv64uzicond-v-czero_eqz | cosim-v | default | PASS | - | 60 |
| rv64uzicond-v-czero_nez | cosim-v | default | PASS | - | 47 |
| hypervisor-p-2-stage_translation | p- | default | PASS | 1059 | 7 |
| hypervisor-p-2-stage_translation_implicit_load_error | p- | default | PASS | 1303 | 8 |
| hypervisor-p-2-stage_translation_implicit_load_error_hs | p- | default | PASS | 1460 | 9 |
| hypervisor-svadu-p-2-stage_translation_implicit_store_error | p- | default | PASS | 1417 | 9 |
| hypervisor-svadu-p-2-stage_translation_implicit_store_error_hs | p- | default | PASS | 1609 | 9 |
| rv64mi-p-breakpoint | p- | default | PASS | 2280 | 12 |
| rv64mi-p-csr | p- | default | PASS | 2254 | 12 |
| rv64mi-p-illegal | p- | default | PASS | 2688 | 14 |
| rv64mi-p-instret_overflow | p- | default | PASS | 813 | 5 |
| rv64mi-p-ld-misaligned | p- | default | PASS | 1056 | 7 |
| rv64mi-p-lh-misaligned | p- | default | PASS | 793 | 5 |
| rv64mi-p-lw-misaligned | p- | default | PASS | 843 | 6 |
| rv64mi-p-ma_addr | p- | default | PASS | 1182 | 6 |
| rv64mi-p-ma_fetch | p- | default | PASS | 1174 | 6 |
| rv64mi-p-mcsr | p- | default | PASS | 910 | 5 |
| rv64mi-p-pmpaddr | p- | default | PASS | 729 | 4 |
| rv64mi-p-sbreak | p- | default | PASS | 829 | 6 |
| rv64mi-p-scall | p- | default | PASS | 808 | 5 |
| rv64mi-p-sd-misaligned | p- | default | PASS | 1140 | 7 |
| rv64mi-p-sh-misaligned | p- | default | PASS | 811 | 5 |
| rv64mi-p-sw-misaligned | p- | default | PASS | 867 | 5 |
| rv64mi-p-zicntr | p- | default | PASS | 905 | 5 |
| rv64mzicbo-p-zero | p- | default | PASS | 851 | 6 |
| rv64si-p-csr | p- | default | PASS | 1531 | 9 |
| rv64si-p-dirty | p- | default | PASS | 1607 | 9 |
| rv64si-p-icache-alias | p- | default | PASS | 1867 | 10 |
| rv64si-p-ma_fetch | p- | default | PASS | 873 | 5 |
| rv64si-p-sbreak | p- | default | PASS | 881 | 5 |
| rv64si-p-scall | p- | default | PASS | 939 | 6 |
| rv64si-p-wfi | p- | default | PASS | 803 | 5 |
| rv64ssvnapot-p-napot | p- | default | PASS | 1245 | 8 |
| rv64ua-p-amoadd_d | p- | default | PASS | 764 | 5 |
| rv64ua-p-amoadd_w | p- | default | PASS | 806 | 5 |
| rv64ua-p-amoand_d | p- | default | PASS | 808 | 5 |
| rv64ua-p-amoand_w | p- | default | PASS | 800 | 5 |
| rv64ua-p-amomax_d | p- | default | PASS | 752 | 5 |
| rv64ua-p-amomax_w | p- | default | PASS | 768 | 5 |
| rv64ua-p-amomaxu_d | p- | default | PASS | 752 | 5 |
| rv64ua-p-amomaxu_w | p- | default | PASS | 768 | 5 |
| rv64ua-p-amomin_d | p- | default | PASS | 752 | 5 |
| rv64ua-p-amomin_w | p- | default | PASS | 768 | 5 |
| rv64ua-p-amominu_d | p- | default | PASS | 752 | 5 |
| rv64ua-p-amominu_w | p- | default | PASS | 768 | 5 |
| rv64ua-p-amoor_d | p- | default | PASS | 802 | 5 |
| rv64ua-p-amoor_w | p- | default | PASS | 802 | 5 |
| rv64ua-p-amoswap_d | p- | default | PASS | 808 | 5 |
| rv64ua-p-amoswap_w | p- | default | PASS | 800 | 5 |
| rv64ua-p-amoxor_d | p- | default | PASS | 814 | 5 |
| rv64ua-p-amoxor_w | p- | default | PASS | 822 | 6 |
| rv64ua-p-lrsc | p- | default | PASS | 16338 | 73 |
| rv64uc-p-rvc | p- | default | PASS | 1148 | 7 |
| rv64ud-p-fadd | p- | default | PASS | 1321 | 8 |
| rv64ud-p-fclass | p- | default | PASS | 880 | 5 |
| rv64ud-p-fcmp | p- | default | PASS | 1505 | 8 |
| rv64ud-p-fcvt | p- | default | PASS | 1219 | 8 |
| rv64ud-p-fcvt_w | p- | default | PASS | 2585 | 14 |
| rv64ud-p-fdiv | p- | default | PASS | 1191 | 7 |
| rv64ud-p-fmadd | p- | default | PASS | 1437 | 8 |
| rv64ud-p-fmin | p- | default | PASS | 1777 | 9 |
| rv64ud-p-ldst | p- | default | PASS | 800 | 5 |
| rv64ud-p-move | p- | default | PASS | 2335 | 12 |
| rv64ud-p-recoding | p- | default | PASS | 855 | 5 |
| rv64ud-p-structural | p- | default | PASS | 1315 | 8 |
| rv64uf-p-fadd | p- | default | PASS | 1321 | 8 |
| rv64uf-p-fclass | p- | default | PASS | 864 | 6 |
| rv64uf-p-fcmp | p- | default | PASS | 1505 | 8 |
| rv64uf-p-fcvt | p- | default | PASS | 1049 | 6 |
| rv64uf-p-fcvt_w | p- | default | PASS | 2340 | 13 |
| rv64uf-p-fdiv | p- | default | PASS | 1137 | 7 |
| rv64uf-p-fmadd | p- | default | PASS | 1437 | 9 |
| rv64uf-p-fmin | p- | default | PASS | 1777 | 10 |
| rv64uf-p-ldst | p- | default | PASS | 814 | 5 |
| rv64uf-p-move | p- | default | PASS | 1310 | 7 |
| rv64uf-p-recoding | p- | default | PASS | 808 | 5 |
| rv64ui-p-add | p- | default | PASS | 2140 | 11 |
| rv64ui-p-addi | p- | default | PASS | 1322 | 7 |
| rv64ui-p-addiw | p- | default | PASS | 1316 | 8 |
| rv64ui-p-addw | p- | default | PASS | 2132 | 11 |
| rv64ui-p-and | p- | default | PASS | 2292 | 12 |
| rv64ui-p-andi | p- | default | PASS | 1290 | 7 |
| rv64ui-p-auipc | p- | default | PASS | 701 | 5 |
| rv64ui-p-beq | p- | default | PASS | 1851 | 10 |
| rv64ui-p-bge | p- | default | PASS | 1988 | 11 |
| rv64ui-p-bgeu | p- | default | PASS | 2252 | 12 |
| rv64ui-p-blt | p- | default | PASS | 1853 | 10 |
| rv64ui-p-bltu | p- | default | PASS | 2108 | 11 |
| rv64ui-p-bne | p- | default | PASS | 1873 | 10 |
| rv64ui-p-fence_i | p- | default | PASS | 1694 | 9 |
| rv64ui-p-jal | p- | default | PASS | 714 | 5 |
| rv64ui-p-jalr | p- | default | PASS | 1395 | 8 |
| rv64ui-p-lb | p- | default | PASS | 1364 | 8 |
| rv64ui-p-lbu | p- | default | PASS | 1364 | 8 |
| rv64ui-p-ld | p- | default | PASS | 1742 | 10 |
| rv64ui-p-ld_st | p- | default | PASS | 4779 | 22 |
| rv64ui-p-lh | p- | default | PASS | 1386 | 8 |
| rv64ui-p-lhu | p- | default | PASS | 1408 | 8 |
| rv64ui-p-lui | p- | default | PASS | 756 | 5 |
| rv64ui-p-lw | p- | default | PASS | 1416 | 8 |
| rv64ui-p-lwu | p- | default | PASS | 1466 | 8 |
| rv64ui-p-ma_data | p- | default | PASS | 10346 | 48 |
| rv64ui-p-or | p- | default | PASS | 2352 | 12 |
| rv64ui-p-ori | p- | default | PASS | 1280 | 8 |
| rv64ui-p-sb | p- | default | PASS | 1944 | 10 |
| rv64ui-p-sd | p- | default | PASS | 2314 | 12 |
| rv64ui-p-sh | p- | default | PASS | 2004 | 11 |
| rv64ui-p-simple | p- | default | PASS | 680 | 5 |
| rv64ui-p-sll | p- | default | PASS | 2268 | 12 |
| rv64ui-p-slli | p- | default | PASS | 1372 | 7 |
| rv64ui-p-slliw | p- | default | PASS | 1378 | 7 |
| rv64ui-p-sllw | p- | default | PASS | 2266 | 12 |
| rv64ui-p-slt | p- | default | PASS | 2120 | 12 |
| rv64ui-p-slti | p- | default | PASS | 1308 | 7 |
| rv64ui-p-sltiu | p- | default | PASS | 1308 | 8 |
| rv64ui-p-sltu | p- | default | PASS | 2158 | 12 |
| rv64ui-p-sra | p- | default | PASS | 2218 | 12 |
| rv64ui-p-srai | p- | default | PASS | 1350 | 7 |
| rv64ui-p-sraiw | p- | default | PASS | 1444 | 8 |
| rv64ui-p-sraw | p- | default | PASS | 2290 | 12 |
| rv64ui-p-srl | p- | default | PASS | 2292 | 12 |
| rv64ui-p-srli | p- | default | PASS | 1390 | 8 |
| rv64ui-p-srliw | p- | default | PASS | 1398 | 8 |
| rv64ui-p-srlw | p- | default | PASS | 2278 | 12 |
| rv64ui-p-st_ld | p- | default | PASS | 1678 | 9 |
| rv64ui-p-sub | p- | default | PASS | 2126 | 11 |
| rv64ui-p-subw | p- | default | PASS | 2118 | 11 |
| rv64ui-p-sw | p- | default | PASS | 2040 | 11 |
| rv64ui-p-xor | p- | default | PASS | 2346 | 12 |
| rv64ui-p-xori | p- | default | PASS | 1280 | 7 |
| rv64um-p-div | p- | default | PASS | 842 | 5 |
| rv64um-p-divu | p- | default | PASS | 842 | 6 |
| rv64um-p-divuw | p- | default | PASS | 830 | 6 |
| rv64um-p-divw | p- | default | PASS | 826 | 5 |
| rv64um-p-mul | p- | default | PASS | 2128 | 11 |
| rv64um-p-mulh | p- | default | PASS | 2158 | 12 |
| rv64um-p-mulhsu | p- | default | PASS | 2158 | 11 |
| rv64um-p-mulhu | p- | default | PASS | 2218 | 12 |
| rv64um-p-mulw | p- | default | PASS | 2018 | 11 |
| rv64um-p-rem | p- | default | PASS | 826 | 5 |
| rv64um-p-remu | p- | default | PASS | 828 | 5 |
| rv64um-p-remuw | p- | default | PASS | 818 | 5 |
| rv64um-p-remw | p- | default | PASS | 826 | 5 |
| rv64uzba-p-add_uw | p- | default | PASS | 2150 | 11 |
| rv64uzba-p-sh1add | p- | default | PASS | 2156 | 12 |
| rv64uzba-p-sh1add_uw | p- | default | PASS | 2164 | 11 |
| rv64uzba-p-sh2add | p- | default | PASS | 2156 | 11 |
| rv64uzba-p-sh2add_uw | p- | default | PASS | 2164 | 12 |
| rv64uzba-p-sh3add | p- | default | PASS | 2156 | 11 |
| rv64uzba-p-sh3add_uw | p- | default | PASS | 2164 | 11 |
| rv64uzba-p-slli_uw | p- | default | PASS | 1394 | 8 |
| rv64uzbb-p-andn | p- | default | PASS | 2336 | 12 |
| rv64uzbb-p-clz | p- | default | PASS | 1188 | 7 |
| rv64uzbb-p-clzw | p- | default | PASS | 1158 | 7 |
| rv64uzbb-p-cpop | p- | default | PASS | 1188 | 7 |
| rv64uzbb-p-cpopw | p- | default | PASS | 1158 | 6 |
| rv64uzbb-p-ctz | p- | default | PASS | 1188 | 7 |
| rv64uzbb-p-ctzw | p- | default | PASS | 1158 | 7 |
| rv64uzbb-p-max | p- | default | PASS | 2130 | 11 |
| rv64uzbb-p-maxu | p- | default | PASS | 2188 | 11 |
| rv64uzbb-p-min | p- | default | PASS | 2122 | 11 |
| rv64uzbb-p-minu | p- | default | PASS | 2170 | 11 |
| rv64uzbb-p-orc_b | p- | default | PASS | 1230 | 7 |
| rv64uzbb-p-orn | p- | default | PASS | 2356 | 12 |
| rv64uzbb-p-rev8 | p- | default | PASS | 1266 | 7 |
| rv64uzbb-p-rol | p- | default | PASS | 2278 | 12 |
| rv64uzbb-p-rolw | p- | default | PASS | 2274 | 12 |
| rv64uzbb-p-ror | p- | default | PASS | 2334 | 13 |
| rv64uzbb-p-rori | p- | default | PASS | 1406 | 8 |
| rv64uzbb-p-roriw | p- | default | PASS | 1318 | 7 |
| rv64uzbb-p-rorw | p- | default | PASS | 2202 | 12 |
| rv64uzbb-p-sext_b | p- | default | PASS | 1188 | 7 |
| rv64uzbb-p-sext_h | p- | default | PASS | 1194 | 7 |
| rv64uzbb-p-xnor | p- | default | PASS | 2354 | 12 |
| rv64uzbb-p-zext_h | p- | default | PASS | 1200 | 6 |
| rv64uzbc-p-clmul | p- | default | PASS | 2130 | 11 |
| rv64uzbc-p-clmulh | p- | default | PASS | 2140 | 11 |
| rv64uzbc-p-clmulr | p- | default | PASS | 2136 | 12 |
| rv64uzbkb-p-brev8 | p- | default | PASS | 1218 | 7 |
| rv64uzbkb-p-pack | p- | default | PASS | 2588 | 13 |
| rv64uzbkb-p-packh | p- | default | PASS | 2258 | 12 |
| rv64uzbkb-p-packw | p- | default | PASS | 2128 | 12 |
| rv64uzbkx-p-xperm4 | p- | default | PASS | 2428 | 12 |
| rv64uzbkx-p-xperm8 | p- | default | PASS | 3276 | 17 |
| rv64uzbs-p-bclr | p- | default | PASS | 2474 | 13 |
| rv64uzbs-p-bclri | p- | default | PASS | 1462 | 8 |
| rv64uzbs-p-bext | p- | default | PASS | 2340 | 12 |
| rv64uzbs-p-bexti | p- | default | PASS | 1396 | 7 |
| rv64uzbs-p-binv | p- | default | PASS | 2308 | 12 |
| rv64uzbs-p-binvi | p- | default | PASS | 1400 | 7 |
| rv64uzbs-p-bset | p- | default | PASS | 2478 | 13 |
| rv64uzbs-p-bseti | p- | default | PASS | 1476 | 9 |
| rv64uzfh-p-fadd | p- | default | PASS | 1321 | 8 |
| rv64uzfh-p-fclass | p- | default | PASS | 866 | 5 |
| rv64uzfh-p-fcmp | p- | default | PASS | 1055 | 6 |
| rv64uzfh-p-fcvt | p- | default | PASS | 1189 | 8 |
| rv64uzfh-p-fcvt_w | p- | default | PASS | 2340 | 13 |
| rv64uzfh-p-fdiv | p- | default | PASS | 1137 | 6 |
| rv64uzfh-p-fmadd | p- | default | PASS | 1437 | 8 |
| rv64uzfh-p-fmin | p- | default | PASS | 1777 | 9 |
| rv64uzfh-p-ldst | p- | default | PASS | 830 | 6 |
| rv64uzfh-p-move | p- | default | PASS | 1309 | 7 |
| rv64uzfh-p-recoding | p- | default | PASS | 808 | 5 |
| rv64uziccid-p-ziccid | p- | default | PASS | 7137 | 23 |
| rv64uzicond-p-czero_eqz | p- | default | PASS | 2064 | 8 |
| rv64uzicond-p-czero_nez | p- | default | PASS | 2064 | 9 |
| rv64ua-v-amoadd_d | v- | default | PASS | 21104 | 114 |
| rv64ua-v-amoadd_w | v- | default | PASS | 21066 | 98 |
| rv64ua-v-amoand_d | v- | default | PASS | 21060 | 99 |
| rv64ua-v-amoand_w | v- | default | PASS | 21082 | 96 |
| rv64ua-v-amomax_d | v- | default | PASS | 21052 | 111 |
| rv64ua-v-amomax_w | v- | default | PASS | 21056 | 112 |
| rv64ua-v-amomaxu_d | v- | default | PASS | 21052 | 98 |
| rv64ua-v-amomaxu_w | v- | default | PASS | 21056 | 117 |
| rv64ua-v-amomin_d | v- | default | PASS | 21052 | 87 |
| rv64ua-v-amomin_w | v- | default | PASS | 21097 | 95 |
| rv64ua-v-amominu_d | v- | default | PASS | 21116 | 97 |
| rv64ua-v-amominu_w | v- | default | PASS | 21119 | 89 |
| rv64ua-v-amoor_d | v- | default | PASS | 21017 | 85 |
| rv64ua-v-amoor_w | v- | default | PASS | 21018 | 96 |
| rv64ua-v-amoswap_d | v- | default | PASS | 21061 | 111 |
| rv64ua-v-amoswap_w | v- | default | PASS | 21081 | 113 |
| rv64ua-v-amoxor_d | v- | default | PASS | 21037 | 95 |
| rv64ua-v-amoxor_w | v- | default | PASS | 21003 | 95 |
| rv64ua-v-lrsc | v- | default | PASS | 36147 | 174 |
| rv64uc-v-rvc | v- | default | PASS | 29128 | 132 |
| rv64ud-v-fadd | v- | default | PASS | 20514 | 85 |
| rv64ud-v-fclass | v- | default | PASS | 11949 | 56 |
| rv64ud-v-fcmp | v- | default | PASS | 20681 | 111 |
| rv64ud-v-fcvt | v- | default | PASS | 20305 | 110 |
| rv64ud-v-fcvt_w | v- | default | PASS | 29818 | 119 |
| rv64ud-v-fdiv | v- | default | PASS | 20385 | 93 |
| rv64ud-v-fmadd | v- | default | PASS | 20677 | 112 |
| rv64ud-v-fmin | v- | default | PASS | 21000 | 97 |
| rv64ud-v-ldst | v- | default | PASS | 20947 | 82 |
| rv64ud-v-move | v- | default | PASS | 21575 | 100 |
| rv64ud-v-recoding | v- | default | PASS | 21004 | 111 |
| rv64ud-v-structural | v- | default | PASS | 12393 | 59 |
| rv64uf-v-fadd | v- | default | PASS | 20514 | 96 |
| rv64uf-v-fclass | v- | default | PASS | 11934 | 56 |
| rv64uf-v-fcmp | v- | default | PASS | 20681 | 95 |
| rv64uf-v-fcvt | v- | default | PASS | 20134 | 112 |
| rv64uf-v-fcvt_w | v- | default | PASS | 29605 | 132 |
| rv64uf-v-fdiv | v- | default | PASS | 20355 | 119 |
| rv64uf-v-fmadd | v- | default | PASS | 20677 | 113 |
| rv64uf-v-fmin | v- | default | PASS | 21000 | 90 |
| rv64uf-v-ldst | v- | default | PASS | 21090 | 97 |
| rv64uf-v-move | v- | default | PASS | 12369 | 55 |
| rv64uf-v-recoding | v- | default | PASS | 19980 | 92 |
| rv64ui-v-add | v- | default | PASS | 13254 | 73 |
| rv64ui-v-addi | v- | default | PASS | 12395 | 61 |
| rv64ui-v-addiw | v- | default | PASS | 12396 | 71 |
| rv64ui-v-addw | v- | default | PASS | 13246 | 73 |
| rv64ui-v-and | v- | default | PASS | 13495 | 57 |
| rv64ui-v-andi | v- | default | PASS | 12458 | 59 |
| rv64ui-v-auipc | v- | default | PASS | 11815 | 66 |
| rv64ui-v-beq | v- | default | PASS | 12878 | 62 |
| rv64ui-v-bge | v- | default | PASS | 13010 | 62 |
| rv64ui-v-bgeu | v- | default | PASS | 13286 | 74 |
| rv64ui-v-blt | v- | default | PASS | 12879 | 63 |
| rv64ui-v-bltu | v- | default | PASS | 13137 | 64 |
| rv64ui-v-bne | v- | default | PASS | 12887 | 61 |
| rv64ui-v-fence_i | v- | default | PASS | 21858 | 101 |
| rv64ui-v-jal | v- | default | PASS | 11817 | 65 |
| rv64ui-v-jalr | v- | default | PASS | 12246 | 60 |
| rv64ui-v-lb | v- | default | PASS | 20660 | 119 |
| rv64ui-v-lbu | v- | default | PASS | 20630 | 114 |
| rv64ui-v-ld | v- | default | PASS | 21104 | 84 |
| rv64ui-v-ld_st | v- | default | PASS | 40031 | 181 |
| rv64ui-v-lh | v- | default | PASS | 20683 | 94 |
| rv64ui-v-lhu | v- | default | PASS | 20748 | 97 |
| rv64ui-v-lui | v- | default | PASS | 11867 | 65 |
| rv64ui-v-lw | v- | default | PASS | 20664 | 90 |
| rv64ui-v-lwu | v- | default | PASS | 20784 | 97 |
| rv64ui-v-ma_data | v- | default | PASS | 43064 | 181 |
| rv64ui-v-or | v- | default | PASS | 13571 | 57 |
| rv64ui-v-ori | v- | default | PASS | 12402 | 59 |
| rv64ui-v-sb | v- | default | PASS | 22031 | 102 |
| rv64ui-v-sd | v- | default | PASS | 30499 | 140 |
| rv64ui-v-sh | v- | default | PASS | 22128 | 119 |
| rv64ui-v-simple | v- | default | PASS | 11762 | 57 |
| rv64ui-v-sll | v- | default | PASS | 21399 | 99 |
| rv64ui-v-slli | v- | default | PASS | 12449 | 59 |
| rv64ui-v-slliw | v- | default | PASS | 12451 | 69 |
| rv64ui-v-sllw | v- | default | PASS | 21394 | 102 |
| rv64ui-v-slt | v- | default | PASS | 13233 | 64 |
| rv64ui-v-slti | v- | default | PASS | 12385 | 58 |
| rv64ui-v-sltiu | v- | default | PASS | 12384 | 59 |
| rv64ui-v-sltu | v- | default | PASS | 13265 | 74 |
| rv64ui-v-sra | v- | default | PASS | 13332 | 57 |
| rv64ui-v-srai | v- | default | PASS | 12444 | 58 |
| rv64ui-v-sraiw | v- | default | PASS | 12548 | 52 |
| rv64ui-v-sraw | v- | default | PASS | 21379 | 100 |
| rv64ui-v-srl | v- | default | PASS | 21462 | 123 |
| rv64ui-v-srli | v- | default | PASS | 12513 | 70 |
| rv64ui-v-srliw | v- | default | PASS | 12478 | 60 |
| rv64ui-v-srlw | v- | default | PASS | 21424 | 100 |
| rv64ui-v-st_ld | v- | default | PASS | 30003 | 162 |
| rv64ui-v-sub | v- | default | PASS | 13239 | 61 |
| rv64ui-v-subw | v- | default | PASS | 13231 | 63 |
| rv64ui-v-sw | v- | default | PASS | 22165 | 121 |
| rv64ui-v-xor | v- | default | PASS | 13571 | 75 |
| rv64ui-v-xori | v- | default | PASS | 12407 | 70 |
| rv64um-v-div | v- | default | PASS | 11974 | 57 |
| rv64um-v-divu | v- | default | PASS | 12007 | 57 |
| rv64um-v-divuw | v- | default | PASS | 11987 | 67 |
| rv64um-v-divw | v- | default | PASS | 11953 | 57 |
| rv64um-v-mul | v- | default | PASS | 13354 | 75 |
| rv64um-v-mulh | v- | default | PASS | 13277 | 65 |
| rv64um-v-mulhsu | v- | default | PASS | 13277 | 76 |
| rv64um-v-mulhu | v- | default | PASS | 13337 | 75 |
| rv64um-v-mulw | v- | default | PASS | 13131 | 56 |
| rv64um-v-rem | v- | default | PASS | 11952 | 50 |
| rv64um-v-remu | v- | default | PASS | 11957 | 56 |
| rv64um-v-remuw | v- | default | PASS | 11943 | 57 |
| rv64um-v-remw | v- | default | PASS | 11954 | 68 |
| rv64uzba-v-add_uw | v- | default | PASS | 13299 | 74 |
| rv64uzba-v-sh1add | v- | default | PASS | 13303 | 74 |
| rv64uzba-v-sh1add_uw | v- | default | PASS | 13312 | 57 |
| rv64uzba-v-sh2add | v- | default | PASS | 13304 | 61 |
| rv64uzba-v-sh2add_uw | v- | default | PASS | 13311 | 59 |
| rv64uzba-v-sh3add | v- | default | PASS | 13304 | 61 |
| rv64uzba-v-sh3add_uw | v- | default | PASS | 13311 | 53 |
| rv64uzba-v-slli_uw | v- | default | PASS | 12502 | 58 |
| rv64uzbb-v-andn | v- | default | PASS | 13589 | 73 |
| rv64uzbb-v-clz | v- | default | PASS | 12324 | 67 |
| rv64uzbb-v-clzw | v- | default | PASS | 12296 | 57 |
| rv64uzbb-v-cpop | v- | default | PASS | 12324 | 57 |
| rv64uzbb-v-cpopw | v- | default | PASS | 12296 | 66 |
| rv64uzbb-v-ctz | v- | default | PASS | 12325 | 58 |
| rv64uzbb-v-ctzw | v- | default | PASS | 12295 | 58 |
| rv64uzbb-v-max | v- | default | PASS | 13268 | 60 |
| rv64uzbb-v-maxu | v- | default | PASS | 13327 | 72 |
| rv64uzbb-v-min | v- | default | PASS | 13260 | 63 |
| rv64uzbb-v-minu | v- | default | PASS | 13304 | 73 |
| rv64uzbb-v-orc_b | v- | default | PASS | 12373 | 67 |
| rv64uzbb-v-orn | v- | default | PASS | 21634 | 85 |
| rv64uzbb-v-rev8 | v- | default | PASS | 12420 | 58 |
| rv64uzbb-v-rol | v- | default | PASS | 21444 | 74 |
| rv64uzbb-v-rolw | v- | default | PASS | 21466 | 82 |
| rv64uzbb-v-ror | v- | default | PASS | 21566 | 82 |
| rv64uzbb-v-rori | v- | default | PASS | 12517 | 57 |
| rv64uzbb-v-roriw | v- | default | PASS | 12423 | 67 |
| rv64uzbb-v-rorw | v- | default | PASS | 13391 | 67 |
| rv64uzbb-v-sext_b | v- | default | PASS | 12324 | 57 |
| rv64uzbb-v-sext_h | v- | default | PASS | 12334 | 45 |
| rv64uzbb-v-xnor | v- | default | PASS | 21635 | 95 |
| rv64uzbb-v-zext_h | v- | default | PASS | 12343 | 57 |
| rv64uzbc-v-clmul | v- | default | PASS | 13358 | 62 |
| rv64uzbc-v-clmulh | v- | default | PASS | 13367 | 48 |
| rv64uzbc-v-clmulr | v- | default | PASS | 13363 | 58 |
| rv64uzbkb-v-brev8 | v- | default | PASS | 12381 | 58 |
| rv64uzbkb-v-pack | v- | default | PASS | 21934 | 79 |
| rv64uzbkb-v-packh | v- | default | PASS | 13549 | 59 |
| rv64uzbkb-v-packw | v- | default | PASS | 13331 | 56 |
| rv64uzbkx-v-xperm4 | v- | default | PASS | 21703 | 63 |
| rv64uzbkx-v-xperm8 | v- | default | PASS | 22599 | 77 |
| rv64uzbs-v-bclr | v- | default | PASS | 21720 | 84 |
| rv64uzbs-v-bclri | v- | default | PASS | 12657 | 51 |
| rv64uzbs-v-bext | v- | default | PASS | 21532 | 77 |
| rv64uzbs-v-bexti | v- | default | PASS | 12551 | 56 |
| rv64uzbs-v-binv | v- | default | PASS | 21446 | 87 |
| rv64uzbs-v-binvi | v- | default | PASS | 12487 | 49 |
| rv64uzbs-v-bset | v- | default | PASS | 21724 | 73 |
| rv64uzbs-v-bseti | v- | default | PASS | 12625 | 44 |
| rv64uzfh-v-fadd | v- | default | PASS | 20544 | 71 |
| rv64uzfh-v-fclass | v- | default | PASS | 11935 | 49 |
| rv64uzfh-v-fcmp | v- | default | PASS | 20261 | 66 |
| rv64uzfh-v-fcvt | v- | default | PASS | 20265 | 68 |
| rv64uzfh-v-fcvt_w | v- | default | PASS | 29605 | 87 |
| rv64uzfh-v-fdiv | v- | default | PASS | 20325 | 69 |
| rv64uzfh-v-fmadd | v- | default | PASS | 20647 | 68 |
| rv64uzfh-v-fmin | v- | default | PASS | 21000 | 55 |
| rv64uzfh-v-ldst | v- | default | PASS | 21036 | 57 |
| rv64uzfh-v-move | v- | default | PASS | 12385 | 51 |
| rv64uzfh-v-recoding | v- | default | PASS | 19950 | 67 |
| rv64uziccid-v-ziccid | v- | default | PASS | 158125 | 481 |
| rv64uzicond-v-czero_eqz | v- | default | PASS | 13218 | 34 |
| rv64uzicond-v-czero_nez | v- | default | PASS | 13283 | 40 |

</details>

## Performance counters

| Test | Suite | Shard | TB | cycles | predicted_ft | multimember_ft | k_cnt_nonzero | mispred_squash | btb_window_hit | alloc_total | rel_commit | rel_squash | i1_violation | release_accounting_mismatch | assertion_a_violation | accept_count | finalize_count | triple_compared | retry_total | retry_shape | retry_target | fill_count | retry_fill_btb | retry_fill_cpred | btb_l1_fill_port_lost | btb_dual_install_queue_full | provisional_alloc | l1_subset_violation | l2_abstain_fallback | member_disagreements | resolve_train | cpred_train_filtered | finalize_stalled | predict_refused | pair_pop_releases | pair_pop_stale_release | stage_unstamped | pair_pop_undelivered | straddle_emitted | straddle_waited | pair_pop_mismatch | ftq_inserts | ftq_pops | ftq_pops_suppressed | ftq_pops_dropped | ftq_cleared | ftq_live | ftq_pairing_residual | ftq_term_taken_no_target | pdb_allocs | ab_fills | pdb_discarded | pdb_live | peek_consumes | icache_requests | pdb_full_refusals | pdb_live_peak | pdb_pairing_residual | fetch_fault_seal_cycles | fill_pop_residual | pop_name_mismatch | load_committed | lr_committed | store_committed | sc_committed | store_violation_squash | decode_continuity_squashes | all_squashes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| `hypervisor-p-2-stage_translation` | p- | none | default | 1059 | 839 | 0 | 0 | 15 | 6 | 43 | 27 | 8 | 0 | 1 | 0 | 839 | 839 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 670 | 0 | 0 | 0 | 0 | 0 | 0 | 839 | 670 | 0 | 0 | 166 | 3 | 0 | 0 | 794 | 670 | 122 | 2 | 794 | 794 | 0 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 13 | 0 | 0 | 0 | 28 |
| `hypervisor-p-2-stage_translation_implicit_load_error` | p- | none | default | 1303 | 1024 | 0 | 0 | 42 | 8 | 76 | 34 | 34 | 0 | 1 | 0 | 1024 | 1024 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 707 | 0 | 0 | 0 | 0 | 0 | 0 | 1024 | 707 | 0 | 0 | 314 | 3 | 0 | 0 | 924 | 707 | 215 | 2 | 924 | 924 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 38 |
| `hypervisor-p-2-stage_translation_implicit_load_error_hs` | p- | none | default | 1460 | 1152 | 0 | 0 | 45 | 4 | 80 | 38 | 37 | 0 | 0 | 0 | 1152 | 1152 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 811 | 0 | 0 | 0 | 0 | 0 | 0 | 1152 | 811 | 0 | 0 | 338 | 3 | 0 | 0 | 1044 | 811 | 231 | 2 | 1044 | 1044 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 42 |
| `hypervisor-svadu-p-2-stage_translation_implicit_store_error` | p- | none | default | 1417 | 1121 | 0 | 0 | 42 | 8 | 78 | 36 | 34 | 0 | 1 | 0 | 1121 | 1121 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 797 | 0 | 0 | 0 | 0 | 0 | 0 | 1121 | 797 | 0 | 0 | 321 | 3 | 0 | 0 | 1020 | 797 | 221 | 2 | 1020 | 1020 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 40 |
| `hypervisor-svadu-p-2-stage_translation_implicit_store_error_hs` | p- | none | default | 1609 | 1266 | 0 | 0 | 47 | 5 | 82 | 40 | 37 | 0 | 0 | 0 | 1266 | 1266 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 896 | 0 | 0 | 0 | 0 | 0 | 0 | 1266 | 896 | 0 | 0 | 367 | 3 | 0 | 0 | 1150 | 896 | 252 | 2 | 1150 | 1150 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 44 |
| `rv64mi-p-breakpoint` | p- | none | default | 2280 | 1893 | 0 | 0 | 43 | 11 | 120 | 78 | 31 | 0 | 1 | 0 | 1893 | 1893 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 1342 | 0 | 0 | 0 | 0 | 0 | 0 | 1893 | 1342 | 0 | 0 | 548 | 3 | 0 | 0 | 1760 | 1342 | 416 | 2 | 1760 | 1760 | 0 | 7 | 0 | 0 | 0 | 0 | 3 | 0 | 2 | 0 | 0 | 0 | 79 |
| `rv64mi-p-csr` | p- | none | default | 2254 | 1928 | 0 | 0 | 57 | 5 | 128 | 80 | 43 | 0 | 1 | 0 | 1928 | 1928 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 6 | 0 | 0 | 0 | 1353 | 0 | 0 | 0 | 0 | 0 | 0 | 1928 | 1353 | 0 | 0 | 572 | 3 | 0 | 0 | 1763 | 1353 | 408 | 2 | 1763 | 1763 | 0 | 7 | 0 | 0 | 0 | 0 | 1 | 0 | 1 | 0 | 0 | 0 | 81 |
| `rv64mi-p-illegal` | p- | none | default | 2688 | 2387 | 0 | 0 | 211 | 43 | 336 | 120 | 214 | 0 | 0 | 0 | 2387 | 2387 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 13 | 0 | 0 | 0 | 1339 | 0 | 0 | 0 | 0 | 0 | 0 | 2387 | 1339 | 0 | 0 | 1045 | 3 | 0 | 0 | 1890 | 1339 | 549 | 2 | 1890 | 1890 | 0 | 2 | 0 | 0 | 0 | 0 | 6 | 0 | 1 | 0 | 0 | 0 | 127 |
| `rv64mi-p-instret_overflow` | p- | none | default | 813 | 722 | 0 | 0 | 66 | 5 | 87 | 30 | 55 | 0 | 0 | 0 | 722 | 722 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 399 | 0 | 0 | 0 | 0 | 0 | 0 | 722 | 399 | 0 | 0 | 320 | 3 | 0 | 0 | 565 | 399 | 164 | 2 | 565 | 565 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64mi-p-ld-misaligned` | p- | none | default | 1056 | 841 | 0 | 0 | 18 | 2 | 39 | 25 | 10 | 0 | 1 | 0 | 841 | 841 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 691 | 0 | 0 | 0 | 0 | 0 | 0 | 841 | 691 | 0 | 0 | 148 | 2 | 0 | 0 | 791 | 691 | 99 | 1 | 791 | 791 | 0 | 7 | 0 | 0 | 0 | 0 | 8 | 0 | 1 | 0 | 0 | 0 | 26 |
| `rv64mi-p-lh-misaligned` | p- | none | default | 793 | 660 | 0 | 0 | 18 | 2 | 39 | 25 | 10 | 0 | 1 | 0 | 660 | 660 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 455 | 0 | 0 | 0 | 0 | 0 | 0 | 660 | 455 | 0 | 0 | 203 | 2 | 0 | 0 | 609 | 455 | 153 | 1 | 609 | 609 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 0 | 26 |
| `rv64mi-p-lw-misaligned` | p- | none | default | 843 | 698 | 0 | 0 | 18 | 2 | 39 | 25 | 10 | 0 | 1 | 0 | 698 | 698 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 521 | 0 | 0 | 0 | 0 | 0 | 0 | 698 | 521 | 0 | 0 | 175 | 2 | 0 | 0 | 648 | 521 | 126 | 1 | 648 | 648 | 0 | 7 | 0 | 0 | 0 | 0 | 4 | 0 | 1 | 0 | 0 | 0 | 26 |
| `rv64mi-p-ma_addr` | p- | none | default | 1182 | 982 | 0 | 0 | 50 | 9 | 75 | 25 | 43 | 0 | 1 | 0 | 982 | 982 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 729 | 0 | 0 | 0 | 0 | 0 | 0 | 982 | 729 | 0 | 0 | 250 | 3 | 0 | 0 | 864 | 729 | 133 | 2 | 864 | 864 | 0 | 2 | 0 | 0 | 0 | 0 | 59 | 0 | 12 | 0 | 0 | 0 | 26 |
| `rv64mi-p-ma_fetch` | p- | none | default | 1174 | 1018 | 0 | 0 | 102 | 20 | 143 | 52 | 84 | 0 | 1 | 0 | 1018 | 1018 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 500 | 0 | 0 | 0 | 0 | 0 | 0 | 1018 | 500 | 0 | 0 | 515 | 3 | 0 | 0 | 786 | 500 | 284 | 2 | 786 | 786 | 0 | 8 | 0 | 42 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 56 |
| `rv64mi-p-mcsr` | p- | none | default | 910 | 777 | 0 | 0 | 16 | 5 | 47 | 32 | 9 | 0 | 0 | 0 | 777 | 777 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 5 | 0 | 0 | 0 | 525 | 0 | 0 | 0 | 0 | 0 | 0 | 777 | 525 | 0 | 0 | 249 | 3 | 0 | 0 | 735 | 525 | 208 | 2 | 735 | 735 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 34 |
| `rv64mi-p-pmpaddr` | p- | none | default | 729 | 654 | 0 | 0 | 52 | 0 | 70 | 28 | 40 | 0 | 0 | 0 | 654 | 654 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 408 | 0 | 0 | 0 | 0 | 0 | 0 | 654 | 408 | 0 | 0 | 243 | 3 | 0 | 0 | 533 | 408 | 123 | 2 | 533 | 533 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 29 |
| `rv64mi-p-sbreak` | p- | none | default | 829 | 738 | 0 | 0 | 66 | 10 | 99 | 32 | 65 | 0 | 0 | 0 | 738 | 738 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 421 | 0 | 0 | 0 | 0 | 0 | 0 | 738 | 421 | 0 | 0 | 314 | 3 | 0 | 0 | 584 | 421 | 161 | 2 | 584 | 584 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 33 |
| `rv64mi-p-scall` | p- | none | default | 808 | 725 | 0 | 0 | 58 | 3 | 83 | 30 | 48 | 0 | 1 | 0 | 725 | 725 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 427 | 0 | 0 | 0 | 0 | 0 | 0 | 725 | 427 | 0 | 0 | 295 | 3 | 0 | 0 | 583 | 427 | 154 | 2 | 583 | 583 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 31 |
| `rv64mi-p-sd-misaligned` | p- | none | default | 1140 | 986 | 0 | 0 | 86 | 2 | 103 | 33 | 66 | 0 | 1 | 0 | 986 | 986 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 598 | 0 | 0 | 0 | 0 | 0 | 0 | 986 | 598 | 0 | 0 | 386 | 2 | 0 | 0 | 809 | 598 | 210 | 1 | 809 | 809 | 0 | 7 | 0 | 0 | 0 | 0 | 8 | 0 | 9 | 0 | 0 | 0 | 34 |
| `rv64mi-p-sh-misaligned` | p- | none | default | 811 | 684 | 0 | 0 | 55 | 2 | 71 | 27 | 40 | 0 | 1 | 0 | 684 | 684 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 410 | 0 | 0 | 0 | 0 | 0 | 0 | 684 | 410 | 0 | 0 | 272 | 2 | 0 | 0 | 567 | 410 | 156 | 1 | 567 | 567 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 0 | 28 |
| `rv64mi-p-sw-misaligned` | p- | none | default | 867 | 743 | 0 | 0 | 67 | 2 | 84 | 29 | 51 | 0 | 1 | 0 | 743 | 743 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 428 | 0 | 0 | 0 | 0 | 0 | 0 | 743 | 428 | 0 | 0 | 313 | 2 | 0 | 0 | 600 | 428 | 171 | 1 | 600 | 600 | 0 | 7 | 0 | 0 | 0 | 0 | 4 | 0 | 5 | 0 | 0 | 0 | 30 |
| `rv64mi-p-zicntr` | p- | none | default | 905 | 808 | 0 | 0 | 69 | 10 | 97 | 33 | 59 | 0 | 1 | 0 | 808 | 808 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 479 | 0 | 0 | 0 | 0 | 0 | 0 | 808 | 479 | 0 | 0 | 326 | 3 | 0 | 0 | 646 | 479 | 165 | 2 | 646 | 646 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 34 |
| `rv64mzicbo-p-zero` | p- | none | default | 851 | 713 | 0 | 0 | 33 | 7 | 55 | 25 | 22 | 0 | 1 | 0 | 713 | 713 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 502 | 0 | 0 | 0 | 0 | 0 | 0 | 713 | 502 | 0 | 0 | 208 | 3 | 0 | 0 | 634 | 502 | 130 | 2 | 634 | 634 | 0 | 7 | 0 | 0 | 0 | 0 | 8 | 0 | 2 | 0 | 0 | 0 | 26 |
| `rv64si-p-csr` | p- | none | default | 1531 | 1342 | 0 | 0 | 15 | 4 | 64 | 51 | 8 | 0 | 0 | 0 | 1342 | 1342 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 1047 | 0 | 0 | 0 | 0 | 0 | 0 | 1342 | 1047 | 0 | 0 | 292 | 3 | 0 | 0 | 1274 | 1047 | 225 | 2 | 1274 | 1274 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 52 |
| `rv64si-p-dirty` | p- | none | default | 1607 | 1349 | 0 | 0 | 81 | 21 | 141 | 52 | 87 | 0 | 0 | 0 | 1349 | 1349 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 6 | 0 | 0 | 0 | 859 | 0 | 0 | 0 | 0 | 0 | 0 | 1349 | 859 | 0 | 0 | 487 | 3 | 0 | 0 | 1157 | 859 | 296 | 2 | 1157 | 1157 | 0 | 7 | 0 | 0 | 0 | 0 | 6 | 0 | 4 | 0 | 0 | 0 | 54 |
| `rv64si-p-icache-alias` | p- | none | default | 1867 | 1523 | 0 | 0 | 52 | 9 | 102 | 56 | 41 | 0 | 1 | 0 | 1523 | 1523 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 1061 | 0 | 0 | 0 | 0 | 0 | 0 | 1523 | 1061 | 0 | 0 | 459 | 3 | 0 | 0 | 1391 | 1061 | 328 | 2 | 1391 | 1391 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 7 | 0 | 0 | 0 | 57 |
| `rv64si-p-ma_fetch` | p- | none | default | 873 | 766 | 0 | 0 | 84 | 16 | 108 | 37 | 67 | 0 | 0 | 0 | 766 | 766 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 387 | 0 | 0 | 0 | 0 | 0 | 0 | 766 | 387 | 0 | 0 | 376 | 3 | 0 | 0 | 587 | 387 | 198 | 2 | 587 | 587 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64si-p-sbreak` | p- | none | default | 881 | 785 | 0 | 0 | 69 | 13 | 107 | 32 | 71 | 0 | 0 | 0 | 785 | 785 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 443 | 0 | 0 | 0 | 0 | 0 | 0 | 785 | 443 | 0 | 0 | 339 | 3 | 0 | 0 | 618 | 443 | 173 | 2 | 618 | 618 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 33 |
| `rv64si-p-scall` | p- | none | default | 939 | 837 | 0 | 0 | 72 | 13 | 112 | 35 | 73 | 0 | 0 | 0 | 837 | 837 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 480 | 0 | 0 | 0 | 0 | 0 | 0 | 837 | 480 | 0 | 0 | 354 | 3 | 0 | 0 | 665 | 480 | 183 | 2 | 665 | 665 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 36 |
| `rv64si-p-wfi` | p- | none | default | 803 | 685 | 0 | 0 | 15 | 5 | 41 | 28 | 8 | 0 | 0 | 0 | 685 | 685 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 467 | 0 | 0 | 0 | 0 | 0 | 0 | 685 | 467 | 0 | 0 | 215 | 3 | 0 | 0 | 646 | 467 | 177 | 2 | 646 | 646 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 29 |
| `rv64ssvnapot-p-napot` | p- | none | default | 1245 | 989 | 0 | 0 | 19 | 1 | 49 | 34 | 13 | 0 | 0 | 0 | 989 | 989 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 769 | 0 | 0 | 0 | 0 | 0 | 0 | 989 | 769 | 0 | 0 | 217 | 3 | 0 | 0 | 931 | 769 | 160 | 2 | 931 | 931 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 5 | 0 | 0 | 0 | 35 |
| `rv64ua-p-amoadd_d` | p- | none | default | 764 | 622 | 0 | 0 | 14 | 5 | 36 | 24 | 7 | 0 | 0 | 0 | 622 | 622 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 444 | 0 | 0 | 0 | 0 | 0 | 0 | 622 | 444 | 0 | 0 | 175 | 3 | 0 | 0 | 584 | 444 | 138 | 2 | 584 | 584 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amoadd_w` | p- | none | default | 806 | 652 | 0 | 0 | 14 | 4 | 37 | 25 | 7 | 0 | 0 | 0 | 652 | 652 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 465 | 0 | 0 | 0 | 0 | 0 | 0 | 652 | 465 | 0 | 0 | 184 | 3 | 0 | 0 | 612 | 465 | 145 | 2 | 612 | 612 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-amoand_d` | p- | none | default | 808 | 652 | 0 | 0 | 14 | 5 | 37 | 25 | 7 | 0 | 0 | 0 | 652 | 652 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 466 | 0 | 0 | 0 | 0 | 0 | 0 | 652 | 466 | 0 | 0 | 183 | 3 | 0 | 0 | 612 | 466 | 144 | 2 | 612 | 612 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-amoand_w` | p- | none | default | 800 | 648 | 0 | 0 | 14 | 5 | 37 | 25 | 7 | 0 | 0 | 0 | 648 | 648 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 462 | 0 | 0 | 0 | 0 | 0 | 0 | 648 | 462 | 0 | 0 | 183 | 3 | 0 | 0 | 608 | 462 | 144 | 2 | 608 | 608 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-amomax_d` | p- | none | default | 752 | 616 | 0 | 0 | 14 | 5 | 36 | 24 | 7 | 0 | 0 | 0 | 616 | 616 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 438 | 0 | 0 | 0 | 0 | 0 | 0 | 616 | 438 | 0 | 0 | 175 | 3 | 0 | 0 | 577 | 438 | 137 | 2 | 577 | 577 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amomax_w` | p- | none | default | 768 | 631 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 631 | 631 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 465 | 0 | 0 | 0 | 0 | 0 | 0 | 631 | 465 | 0 | 0 | 163 | 3 | 0 | 0 | 592 | 465 | 125 | 2 | 592 | 592 | 0 | 7 | 0 | 0 | 0 | 0 | 3 | 0 | 4 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amomaxu_d` | p- | none | default | 752 | 616 | 0 | 0 | 14 | 5 | 36 | 24 | 7 | 0 | 0 | 0 | 616 | 616 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 438 | 0 | 0 | 0 | 0 | 0 | 0 | 616 | 438 | 0 | 0 | 175 | 3 | 0 | 0 | 577 | 438 | 137 | 2 | 577 | 577 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amomaxu_w` | p- | none | default | 768 | 631 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 631 | 631 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 465 | 0 | 0 | 0 | 0 | 0 | 0 | 631 | 465 | 0 | 0 | 163 | 3 | 0 | 0 | 592 | 465 | 125 | 2 | 592 | 592 | 0 | 7 | 0 | 0 | 0 | 0 | 3 | 0 | 4 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amomin_d` | p- | none | default | 752 | 616 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 616 | 616 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 438 | 0 | 0 | 0 | 0 | 0 | 0 | 616 | 438 | 0 | 0 | 175 | 3 | 0 | 0 | 577 | 438 | 137 | 2 | 577 | 577 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amomin_w` | p- | none | default | 768 | 631 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 631 | 631 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 465 | 0 | 0 | 0 | 0 | 0 | 0 | 631 | 465 | 0 | 0 | 163 | 3 | 0 | 0 | 592 | 465 | 125 | 2 | 592 | 592 | 0 | 7 | 0 | 0 | 0 | 0 | 3 | 0 | 4 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amominu_d` | p- | none | default | 752 | 616 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 616 | 616 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 438 | 0 | 0 | 0 | 0 | 0 | 0 | 616 | 438 | 0 | 0 | 175 | 3 | 0 | 0 | 577 | 438 | 137 | 2 | 577 | 577 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 3 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amominu_w` | p- | none | default | 768 | 631 | 0 | 0 | 14 | 5 | 36 | 24 | 7 | 0 | 0 | 0 | 631 | 631 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 465 | 0 | 0 | 0 | 0 | 0 | 0 | 631 | 465 | 0 | 0 | 163 | 3 | 0 | 0 | 592 | 465 | 125 | 2 | 592 | 592 | 0 | 7 | 0 | 0 | 0 | 0 | 3 | 0 | 4 | 0 | 0 | 0 | 25 |
| `rv64ua-p-amoor_d` | p- | none | default | 802 | 649 | 0 | 0 | 14 | 4 | 37 | 25 | 7 | 0 | 0 | 0 | 649 | 649 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 464 | 0 | 0 | 0 | 0 | 0 | 0 | 649 | 464 | 0 | 0 | 182 | 3 | 0 | 0 | 610 | 464 | 144 | 2 | 610 | 610 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-amoor_w` | p- | none | default | 802 | 649 | 0 | 0 | 14 | 5 | 37 | 25 | 7 | 0 | 0 | 0 | 649 | 649 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 464 | 0 | 0 | 0 | 0 | 0 | 0 | 649 | 464 | 0 | 0 | 182 | 3 | 0 | 0 | 610 | 464 | 144 | 2 | 610 | 610 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-amoswap_d` | p- | none | default | 808 | 652 | 0 | 0 | 14 | 4 | 37 | 25 | 7 | 0 | 0 | 0 | 652 | 652 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 466 | 0 | 0 | 0 | 0 | 0 | 0 | 652 | 466 | 0 | 0 | 183 | 3 | 0 | 0 | 612 | 466 | 144 | 2 | 612 | 612 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-amoswap_w` | p- | none | default | 800 | 648 | 0 | 0 | 14 | 4 | 37 | 25 | 7 | 0 | 0 | 0 | 648 | 648 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 462 | 0 | 0 | 0 | 0 | 0 | 0 | 648 | 462 | 0 | 0 | 183 | 3 | 0 | 0 | 608 | 462 | 144 | 2 | 608 | 608 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-amoxor_d` | p- | none | default | 814 | 656 | 0 | 0 | 14 | 5 | 37 | 25 | 7 | 0 | 0 | 0 | 656 | 656 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 469 | 0 | 0 | 0 | 0 | 0 | 0 | 656 | 469 | 0 | 0 | 184 | 3 | 0 | 0 | 616 | 469 | 145 | 2 | 616 | 616 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-amoxor_w` | p- | none | default | 822 | 661 | 0 | 0 | 14 | 4 | 37 | 25 | 7 | 0 | 0 | 0 | 661 | 661 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 473 | 0 | 0 | 0 | 0 | 0 | 0 | 661 | 473 | 0 | 0 | 185 | 3 | 0 | 0 | 622 | 473 | 147 | 2 | 622 | 622 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 2 | 0 | 1 | 0 | 26 |
| `rv64ua-p-lrsc` | p- | none | default | 16338 | 6277 | 0 | 0 | 23 | 2664 | 2743 | 1126 | 1612 | 0 | 0 | 0 | 6277 | 6277 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1029 | 1011 | 0 | 0 | 5903 | 0 | 0 | 0 | 0 | 0 | 0 | 6277 | 5903 | 0 | 0 | 371 | 3 | 0 | 0 | 6191 | 5903 | 286 | 2 | 6191 | 6191 | 0 | 7 | 0 | 0 | 0 | 0 | 4 | 1025 | 1 | 1028 | 77 | 0 | 111 |
| `rv64uc-p-rvc` | p- | none | default | 1148 | 1005 | 0 | 0 | 76 | 3 | 97 | 37 | 56 | 0 | 0 | 0 | 1005 | 1005 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 634 | 0 | 0 | 0 | 215 | 19 | 0 | 1005 | 634 | 0 | 0 | 368 | 3 | 0 | 0 | 856 | 634 | 220 | 2 | 856 | 856 | 0 | 7 | 0 | 0 | 0 | 0 | 9 | 0 | 5 | 0 | 0 | 0 | 42 |
| `rv64ud-p-fadd` | p- | none | default | 1321 | 1066 | 0 | 0 | 14 | 4 | 48 | 36 | 7 | 0 | 0 | 0 | 1066 | 1066 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 857 | 0 | 0 | 0 | 0 | 0 | 0 | 1066 | 857 | 0 | 0 | 206 | 3 | 0 | 0 | 1018 | 857 | 159 | 2 | 1018 | 1018 | 0 | 7 | 0 | 0 | 0 | 0 | 40 | 0 | 1 | 0 | 0 | 0 | 37 |
| `rv64ud-p-fclass` | p- | none | default | 880 | 714 | 0 | 0 | 14 | 4 | 38 | 26 | 7 | 0 | 0 | 0 | 714 | 714 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 562 | 0 | 0 | 0 | 0 | 0 | 0 | 714 | 562 | 0 | 0 | 149 | 3 | 0 | 0 | 673 | 562 | 109 | 2 | 673 | 673 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 27 |
| `rv64ud-p-fcmp` | p- | none | default | 1505 | 1249 | 0 | 0 | 14 | 5 | 53 | 41 | 7 | 0 | 0 | 0 | 1249 | 1249 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 1005 | 0 | 0 | 0 | 0 | 0 | 0 | 1249 | 1005 | 0 | 0 | 241 | 3 | 0 | 0 | 1196 | 1005 | 189 | 2 | 1196 | 1196 | 0 | 7 | 0 | 0 | 0 | 0 | 60 | 0 | 1 | 0 | 0 | 0 | 42 |
| `rv64ud-p-fcvt` | p- | none | default | 1219 | 1011 | 0 | 0 | 14 | 5 | 48 | 36 | 7 | 0 | 0 | 0 | 1011 | 1011 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 800 | 0 | 0 | 0 | 0 | 0 | 0 | 1011 | 800 | 0 | 0 | 208 | 3 | 0 | 0 | 964 | 800 | 162 | 2 | 964 | 964 | 0 | 7 | 0 | 0 | 0 | 0 | 17 | 0 | 1 | 0 | 0 | 0 | 37 |
| `rv64ud-p-fcvt_w` | p- | none | default | 2585 | 2358 | 0 | 0 | 14 | 4 | 72 | 60 | 7 | 0 | 0 | 0 | 2358 | 2358 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 2075 | 0 | 0 | 0 | 0 | 0 | 0 | 2358 | 2075 | 0 | 0 | 280 | 3 | 0 | 0 | 2284 | 2075 | 207 | 2 | 2284 | 2284 | 0 | 7 | 0 | 0 | 0 | 0 | 152 | 0 | 1 | 0 | 0 | 0 | 61 |
| `rv64ud-p-fdiv` | p- | none | default | 1191 | 962 | 0 | 0 | 14 | 5 | 46 | 34 | 7 | 0 | 0 | 0 | 962 | 962 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 761 | 0 | 0 | 0 | 0 | 0 | 0 | 962 | 761 | 0 | 0 | 198 | 3 | 0 | 0 | 914 | 761 | 151 | 2 | 914 | 914 | 0 | 7 | 0 | 0 | 0 | 0 | 32 | 0 | 1 | 0 | 0 | 0 | 35 |
| `rv64ud-p-fmadd` | p- | none | default | 1437 | 1165 | 0 | 0 | 14 | 4 | 50 | 38 | 7 | 0 | 0 | 0 | 1165 | 1165 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 941 | 0 | 0 | 0 | 0 | 0 | 0 | 1165 | 941 | 0 | 0 | 221 | 3 | 0 | 0 | 1113 | 941 | 170 | 2 | 1113 | 1113 | 0 | 7 | 0 | 0 | 0 | 0 | 48 | 0 | 1 | 0 | 0 | 0 | 39 |
| `rv64ud-p-fmin` | p- | none | default | 1777 | 1452 | 0 | 0 | 14 | 5 | 56 | 44 | 7 | 0 | 0 | 0 | 1452 | 1452 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 1189 | 0 | 0 | 0 | 0 | 0 | 0 | 1452 | 1189 | 0 | 0 | 260 | 3 | 0 | 0 | 1398 | 1189 | 207 | 2 | 1398 | 1398 | 0 | 7 | 0 | 0 | 0 | 0 | 72 | 0 | 1 | 0 | 0 | 0 | 45 |
| `rv64ud-p-ldst` | p- | none | default | 800 | 668 | 0 | 0 | 14 | 5 | 38 | 26 | 7 | 0 | 0 | 0 | 668 | 668 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 505 | 0 | 0 | 0 | 0 | 0 | 0 | 668 | 505 | 0 | 0 | 160 | 3 | 0 | 0 | 626 | 505 | 119 | 2 | 626 | 626 | 0 | 7 | 0 | 0 | 0 | 0 | 10 | 0 | 6 | 0 | 0 | 0 | 27 |
| `rv64ud-p-move` | p- | none | default | 2335 | 1048 | 0 | 0 | 14 | 4 | 38 | 26 | 7 | 0 | 0 | 0 | 1048 | 1048 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 924 | 0 | 0 | 0 | 0 | 0 | 0 | 1048 | 924 | 0 | 0 | 121 | 3 | 0 | 0 | 1003 | 924 | 77 | 2 | 1003 | 1003 | 0 | 8 | 0 | 983 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 27 |
| `rv64ud-p-recoding` | p- | none | default | 855 | 693 | 0 | 0 | 14 | 5 | 38 | 26 | 7 | 0 | 0 | 0 | 693 | 693 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 532 | 0 | 0 | 0 | 0 | 0 | 0 | 693 | 532 | 0 | 0 | 158 | 3 | 0 | 0 | 652 | 532 | 118 | 2 | 652 | 652 | 0 | 7 | 0 | 0 | 0 | 0 | 7 | 0 | 2 | 0 | 0 | 0 | 27 |
| `rv64ud-p-structural` | p- | none | default | 1315 | 1061 | 0 | 0 | 95 | 14 | 116 | 47 | 64 | 0 | 0 | 0 | 1061 | 1061 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 18 | 0 | 0 | 0 | 614 | 0 | 0 | 0 | 0 | 0 | 0 | 1061 | 614 | 0 | 0 | 444 | 3 | 0 | 0 | 886 | 614 | 270 | 2 | 886 | 886 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 54 |
| `rv64uf-p-fadd` | p- | none | default | 1321 | 1066 | 0 | 0 | 14 | 4 | 48 | 36 | 7 | 0 | 0 | 0 | 1066 | 1066 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 857 | 0 | 0 | 0 | 0 | 0 | 0 | 1066 | 857 | 0 | 0 | 206 | 3 | 0 | 0 | 1018 | 857 | 159 | 2 | 1018 | 1018 | 0 | 7 | 0 | 0 | 0 | 0 | 40 | 0 | 1 | 0 | 0 | 0 | 37 |
| `rv64uf-p-fclass` | p- | none | default | 864 | 707 | 0 | 0 | 14 | 5 | 38 | 26 | 7 | 0 | 0 | 0 | 707 | 707 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 555 | 0 | 0 | 0 | 0 | 0 | 0 | 707 | 555 | 0 | 0 | 149 | 3 | 0 | 0 | 666 | 555 | 109 | 2 | 666 | 666 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 27 |
| `rv64uf-p-fcmp` | p- | none | default | 1505 | 1249 | 0 | 0 | 14 | 5 | 53 | 41 | 7 | 0 | 0 | 0 | 1249 | 1249 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 1005 | 0 | 0 | 0 | 0 | 0 | 0 | 1249 | 1005 | 0 | 0 | 241 | 3 | 0 | 0 | 1196 | 1005 | 189 | 2 | 1196 | 1196 | 0 | 7 | 0 | 0 | 0 | 0 | 60 | 0 | 1 | 0 | 0 | 0 | 42 |
| `rv64uf-p-fcvt` | p- | none | default | 1049 | 870 | 0 | 0 | 14 | 5 | 46 | 34 | 7 | 0 | 0 | 0 | 870 | 870 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 662 | 0 | 0 | 0 | 0 | 0 | 0 | 870 | 662 | 0 | 0 | 205 | 3 | 0 | 0 | 826 | 662 | 162 | 2 | 826 | 826 | 0 | 7 | 0 | 0 | 0 | 0 | 8 | 0 | 1 | 0 | 0 | 0 | 35 |
| `rv64uf-p-fcvt_w` | p- | none | default | 2340 | 2115 | 0 | 0 | 14 | 5 | 67 | 55 | 7 | 0 | 0 | 0 | 2115 | 2115 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 1844 | 0 | 0 | 0 | 0 | 0 | 0 | 2115 | 1844 | 0 | 0 | 268 | 3 | 0 | 0 | 2046 | 1844 | 200 | 2 | 2046 | 2046 | 0 | 7 | 0 | 0 | 0 | 0 | 132 | 0 | 1 | 0 | 0 | 0 | 56 |
| `rv64uf-p-fdiv` | p- | none | default | 1137 | 927 | 0 | 0 | 14 | 4 | 45 | 33 | 7 | 0 | 0 | 0 | 927 | 927 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 734 | 0 | 0 | 0 | 0 | 0 | 0 | 927 | 734 | 0 | 0 | 190 | 3 | 0 | 0 | 880 | 734 | 144 | 2 | 880 | 880 | 0 | 7 | 0 | 0 | 0 | 0 | 28 | 0 | 1 | 0 | 0 | 0 | 34 |
| `rv64uf-p-fmadd` | p- | none | default | 1437 | 1165 | 0 | 0 | 14 | 4 | 50 | 38 | 7 | 0 | 0 | 0 | 1165 | 1165 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 941 | 0 | 0 | 0 | 0 | 0 | 0 | 1165 | 941 | 0 | 0 | 221 | 3 | 0 | 0 | 1113 | 941 | 170 | 2 | 1113 | 1113 | 0 | 7 | 0 | 0 | 0 | 0 | 48 | 0 | 1 | 0 | 0 | 0 | 39 |
| `rv64uf-p-fmin` | p- | none | default | 1777 | 1452 | 0 | 0 | 14 | 5 | 56 | 44 | 7 | 0 | 0 | 0 | 1452 | 1452 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 1189 | 0 | 0 | 0 | 0 | 0 | 0 | 1452 | 1189 | 0 | 0 | 260 | 3 | 0 | 0 | 1398 | 1189 | 207 | 2 | 1398 | 1398 | 0 | 7 | 0 | 0 | 0 | 0 | 72 | 0 | 1 | 0 | 0 | 0 | 45 |
| `rv64uf-p-ldst` | p- | none | default | 814 | 662 | 0 | 0 | 14 | 5 | 38 | 26 | 7 | 0 | 0 | 0 | 662 | 662 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 472 | 0 | 0 | 0 | 0 | 0 | 0 | 662 | 472 | 0 | 0 | 187 | 3 | 0 | 0 | 622 | 472 | 148 | 2 | 622 | 622 | 0 | 7 | 0 | 0 | 0 | 0 | 4 | 0 | 3 | 0 | 0 | 0 | 27 |
| `rv64uf-p-move` | p- | none | default | 1310 | 1050 | 0 | 0 | 14 | 4 | 46 | 34 | 7 | 0 | 0 | 0 | 1050 | 1050 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 890 | 0 | 0 | 0 | 0 | 0 | 0 | 1050 | 890 | 0 | 0 | 157 | 3 | 0 | 0 | 999 | 890 | 107 | 2 | 999 | 999 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 35 |
| `rv64uf-p-recoding` | p- | none | default | 808 | 664 | 0 | 0 | 14 | 5 | 38 | 26 | 7 | 0 | 0 | 0 | 664 | 664 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 490 | 0 | 0 | 0 | 0 | 0 | 0 | 664 | 490 | 0 | 0 | 171 | 3 | 0 | 0 | 623 | 490 | 131 | 2 | 623 | 623 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 0 | 27 |
| `rv64ui-p-add` | p- | none | default | 2140 | 1585 | 0 | 0 | 30 | 24 | 64 | 54 | 7 | 0 | 0 | 0 | 1585 | 1585 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1349 | 0 | 0 | 0 | 0 | 0 | 0 | 1585 | 1349 | 0 | 0 | 233 | 3 | 0 | 0 | 1533 | 1349 | 182 | 2 | 1533 | 1533 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-addi` | p- | none | default | 1322 | 1010 | 0 | 0 | 20 | 10 | 46 | 34 | 7 | 0 | 0 | 0 | 1010 | 1010 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 14 | 4 | 0 | 0 | 837 | 0 | 0 | 0 | 0 | 0 | 0 | 1010 | 837 | 0 | 0 | 170 | 3 | 0 | 0 | 964 | 837 | 125 | 2 | 964 | 964 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-addiw` | p- | none | default | 1316 | 1008 | 0 | 0 | 20 | 7 | 45 | 33 | 7 | 0 | 0 | 0 | 1008 | 1008 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 13 | 3 | 0 | 0 | 834 | 0 | 0 | 0 | 0 | 0 | 0 | 1008 | 834 | 0 | 0 | 171 | 3 | 0 | 0 | 961 | 834 | 125 | 2 | 961 | 961 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-addw` | p- | none | default | 2132 | 1588 | 0 | 0 | 29 | 23 | 64 | 52 | 7 | 0 | 0 | 0 | 1588 | 1588 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 32 | 13 | 0 | 0 | 1354 | 0 | 0 | 0 | 0 | 0 | 0 | 1588 | 1354 | 0 | 0 | 231 | 3 | 0 | 0 | 1538 | 1354 | 182 | 2 | 1538 | 1538 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-and` | p- | none | default | 2292 | 1710 | 0 | 0 | 29 | 19 | 66 | 54 | 7 | 0 | 0 | 0 | 1710 | 1710 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1482 | 0 | 0 | 0 | 0 | 0 | 0 | 1710 | 1482 | 0 | 0 | 225 | 3 | 0 | 0 | 1666 | 1482 | 182 | 2 | 1666 | 1666 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-andi` | p- | none | default | 1290 | 984 | 0 | 0 | 20 | 8 | 46 | 34 | 7 | 0 | 0 | 0 | 984 | 984 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 14 | 4 | 0 | 0 | 804 | 0 | 0 | 0 | 0 | 0 | 0 | 984 | 804 | 0 | 0 | 177 | 3 | 0 | 0 | 940 | 804 | 134 | 2 | 940 | 940 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-auipc` | p- | none | default | 701 | 592 | 0 | 0 | 45 | 4 | 67 | 26 | 36 | 0 | 0 | 0 | 592 | 592 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 350 | 0 | 0 | 0 | 0 | 0 | 0 | 592 | 350 | 0 | 0 | 239 | 3 | 0 | 0 | 488 | 350 | 136 | 2 | 488 | 488 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64ui-p-beq` | p- | none | default | 1851 | 1473 | 0 | 0 | 40 | 21 | 70 | 58 | 7 | 0 | 0 | 0 | 1473 | 1473 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 38 | 7 | 0 | 0 | 1211 | 0 | 0 | 0 | 0 | 0 | 0 | 1473 | 1211 | 0 | 0 | 259 | 3 | 0 | 0 | 1409 | 1211 | 196 | 2 | 1409 | 1409 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 51 |
| `rv64ui-p-bge` | p- | none | default | 1988 | 1594 | 0 | 0 | 49 | 38 | 89 | 71 | 13 | 0 | 0 | 0 | 1594 | 1594 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 51 | 11 | 0 | 0 | 1306 | 0 | 0 | 0 | 0 | 0 | 0 | 1594 | 1306 | 0 | 0 | 285 | 3 | 0 | 0 | 1522 | 1306 | 214 | 2 | 1522 | 1522 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 60 |
| `rv64ui-p-bgeu` | p- | none | default | 2252 | 1779 | 0 | 0 | 49 | 30 | 83 | 71 | 7 | 0 | 0 | 0 | 1779 | 1779 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 51 | 11 | 0 | 0 | 1485 | 0 | 0 | 0 | 0 | 0 | 0 | 1779 | 1485 | 0 | 0 | 291 | 3 | 0 | 0 | 1707 | 1485 | 220 | 2 | 1707 | 1707 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 60 |
| `rv64ui-p-blt` | p- | none | default | 1853 | 1473 | 0 | 0 | 40 | 32 | 77 | 62 | 10 | 0 | 0 | 0 | 1473 | 1473 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 42 | 11 | 0 | 0 | 1213 | 0 | 0 | 0 | 0 | 0 | 0 | 1473 | 1213 | 0 | 0 | 257 | 3 | 0 | 0 | 1411 | 1213 | 196 | 2 | 1411 | 1411 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 51 |
| `rv64ui-p-bltu` | p- | none | default | 2108 | 1653 | 0 | 1 | 40 | 34 | 77 | 61 | 11 | 0 | 0 | 0 | 1653 | 1653 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 42 | 11 | 0 | 0 | 1390 | 0 | 0 | 0 | 0 | 0 | 0 | 1653 | 1390 | 0 | 0 | 260 | 3 | 0 | 0 | 1591 | 1390 | 199 | 2 | 1591 | 1591 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 51 |
| `rv64ui-p-bne` | p- | none | default | 1873 | 1491 | 0 | 1 | 42 | 35 | 80 | 63 | 12 | 0 | 0 | 0 | 1491 | 1491 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 44 | 11 | 0 | 0 | 1223 | 0 | 0 | 0 | 0 | 0 | 0 | 1491 | 1223 | 0 | 0 | 265 | 3 | 0 | 0 | 1426 | 1223 | 201 | 2 | 1426 | 1426 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 53 |
| `rv64ui-p-fence_i` | p- | none | default | 1694 | 1122 | 0 | 0 | 24 | 443 | 177 | 130 | 42 | 0 | 0 | 0 | 1122 | 1122 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 104 | 62 | 0 | 0 | 880 | 0 | 0 | 0 | 0 | 0 | 0 | 1122 | 880 | 0 | 0 | 239 | 3 | 0 | 0 | 1071 | 880 | 189 | 2 | 1071 | 1071 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 5 | 0 | 0 | 0 | 37 |
| `rv64ui-p-jal` | p- | none | default | 714 | 599 | 0 | 0 | 50 | 5 | 70 | 26 | 39 | 0 | 0 | 0 | 599 | 599 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 336 | 0 | 0 | 0 | 0 | 0 | 0 | 599 | 336 | 0 | 0 | 260 | 3 | 0 | 0 | 488 | 336 | 150 | 2 | 488 | 488 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 27 |
| `rv64ui-p-jalr` | p- | none | default | 1395 | 1076 | 3 | 4 | 56 | 15 | 82 | 38 | 41 | 0 | 0 | 0 | 1076 | 1076 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 2 | 0 | 0 | 713 | 0 | 0 | 0 | 0 | 0 | 0 | 1076 | 713 | 0 | 0 | 360 | 3 | 0 | 0 | 978 | 713 | 263 | 2 | 978 | 978 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 45 |
| `rv64ui-p-lb` | p- | none | default | 1364 | 1031 | 0 | 0 | 20 | 14 | 48 | 36 | 7 | 0 | 0 | 0 | 1031 | 1031 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 853 | 0 | 0 | 0 | 0 | 0 | 0 | 1031 | 853 | 0 | 0 | 175 | 3 | 0 | 0 | 985 | 853 | 130 | 2 | 985 | 985 | 0 | 7 | 0 | 0 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-lbu` | p- | none | default | 1364 | 1031 | 0 | 0 | 20 | 12 | 47 | 35 | 7 | 0 | 0 | 0 | 1031 | 1031 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 15 | 5 | 0 | 0 | 853 | 0 | 0 | 0 | 0 | 0 | 0 | 1031 | 853 | 0 | 0 | 175 | 3 | 0 | 0 | 985 | 853 | 130 | 2 | 985 | 985 | 0 | 7 | 0 | 0 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-ld` | p- | none | default | 1742 | 1249 | 0 | 0 | 20 | 13 | 48 | 36 | 7 | 0 | 0 | 0 | 1249 | 1249 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 1081 | 0 | 0 | 0 | 0 | 0 | 0 | 1249 | 1081 | 0 | 0 | 165 | 3 | 0 | 0 | 1202 | 1081 | 119 | 2 | 1202 | 1202 | 0 | 7 | 0 | 0 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-ld_st` | p- | none | default | 4779 | 3011 | 0 | 0 | 205 | 55 | 227 | 81 | 141 | 0 | 0 | 0 | 3011 | 3011 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 61 | 0 | 0 | 0 | 2041 | 0 | 0 | 0 | 0 | 0 | 0 | 3011 | 2041 | 0 | 0 | 967 | 3 | 0 | 0 | 2727 | 2041 | 684 | 2 | 2727 | 2727 | 0 | 8 | 0 | 767 | 0 | 0 | 277 | 0 | 278 | 0 | 0 | 0 | 139 |
| `rv64ui-p-lh` | p- | none | default | 1386 | 1045 | 0 | 0 | 20 | 12 | 48 | 36 | 7 | 0 | 0 | 0 | 1045 | 1045 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 872 | 0 | 0 | 0 | 0 | 0 | 0 | 1045 | 872 | 0 | 0 | 170 | 3 | 0 | 0 | 1001 | 872 | 127 | 2 | 1001 | 1001 | 0 | 7 | 0 | 0 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-lhu` | p- | none | default | 1408 | 1058 | 0 | 0 | 20 | 13 | 48 | 36 | 7 | 0 | 0 | 0 | 1058 | 1058 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 881 | 0 | 0 | 0 | 0 | 0 | 0 | 1058 | 881 | 0 | 0 | 174 | 3 | 0 | 0 | 1011 | 881 | 128 | 2 | 1011 | 1011 | 0 | 7 | 0 | 0 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-lui` | p- | none | default | 756 | 618 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 618 | 618 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 440 | 0 | 0 | 0 | 0 | 0 | 0 | 618 | 440 | 0 | 0 | 175 | 3 | 0 | 0 | 580 | 440 | 138 | 2 | 580 | 580 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64ui-p-lw` | p- | none | default | 1416 | 1067 | 0 | 0 | 20 | 13 | 48 | 36 | 7 | 0 | 0 | 0 | 1067 | 1067 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 893 | 0 | 0 | 0 | 0 | 0 | 0 | 1067 | 893 | 0 | 0 | 171 | 3 | 0 | 0 | 1021 | 893 | 126 | 2 | 1021 | 1021 | 0 | 7 | 0 | 0 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-lwu` | p- | none | default | 1466 | 1084 | 0 | 0 | 21 | 13 | 46 | 36 | 7 | 0 | 0 | 0 | 1084 | 1084 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 917 | 0 | 0 | 0 | 0 | 0 | 0 | 1084 | 917 | 0 | 0 | 164 | 3 | 0 | 0 | 1040 | 917 | 121 | 2 | 1040 | 1040 | 0 | 7 | 0 | 0 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-ma_data` | p- | none | default | 10346 | 7912 | 0 | 0 | 295 | 122 | 491 | 249 | 237 | 0 | 0 | 0 | 7912 | 7912 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 91 | 0 | 0 | 0 | 5747 | 0 | 0 | 0 | 0 | 0 | 0 | 7912 | 5747 | 0 | 0 | 2162 | 3 | 0 | 0 | 7425 | 5747 | 1676 | 2 | 7425 | 7425 | 0 | 7 | 0 | 0 | 0 | 0 | 180 | 0 | 136 | 0 | 138 | 0 | 337 |
| `rv64ui-p-or` | p- | none | default | 2352 | 1761 | 0 | 0 | 29 | 19 | 66 | 54 | 7 | 0 | 0 | 0 | 1761 | 1761 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1527 | 0 | 0 | 0 | 0 | 0 | 0 | 1761 | 1527 | 0 | 0 | 231 | 3 | 0 | 0 | 1711 | 1527 | 182 | 2 | 1711 | 1711 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-ori` | p- | none | default | 1280 | 979 | 0 | 0 | 20 | 12 | 48 | 36 | 7 | 0 | 0 | 0 | 979 | 979 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 798 | 0 | 0 | 0 | 0 | 0 | 0 | 979 | 798 | 0 | 0 | 178 | 3 | 0 | 0 | 934 | 798 | 134 | 2 | 934 | 934 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-sb` | p- | none | default | 1944 | 1449 | 0 | 0 | 78 | 28 | 109 | 57 | 47 | 0 | 0 | 0 | 1449 | 1449 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 28 | 11 | 0 | 0 | 1053 | 0 | 0 | 0 | 0 | 0 | 0 | 1449 | 1053 | 0 | 0 | 393 | 3 | 0 | 0 | 1306 | 1053 | 251 | 2 | 1306 | 1306 | 0 | 7 | 0 | 0 | 0 | 0 | 34 | 0 | 36 | 0 | 1 | 0 | 46 |
| `rv64ui-p-sd` | p- | none | default | 2314 | 1764 | 0 | 1 | 87 | 31 | 119 | 56 | 58 | 0 | 0 | 0 | 1764 | 1764 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 28 | 11 | 0 | 0 | 1322 | 0 | 0 | 0 | 0 | 0 | 0 | 1764 | 1322 | 0 | 0 | 439 | 3 | 0 | 0 | 1599 | 1322 | 275 | 2 | 1599 | 1599 | 0 | 7 | 0 | 0 | 0 | 0 | 34 | 0 | 35 | 0 | 1 | 0 | 46 |
| `rv64ui-p-sh` | p- | none | default | 2004 | 1492 | 0 | 0 | 79 | 25 | 109 | 57 | 47 | 0 | 0 | 0 | 1492 | 1492 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 28 | 11 | 0 | 0 | 1093 | 0 | 0 | 0 | 0 | 0 | 0 | 1492 | 1093 | 0 | 0 | 396 | 3 | 0 | 0 | 1350 | 1093 | 255 | 2 | 1350 | 1350 | 0 | 7 | 0 | 0 | 0 | 0 | 34 | 0 | 36 | 0 | 1 | 0 | 46 |
| `rv64ui-p-simple` | p- | none | default | 680 | 549 | 0 | 0 | 13 | 4 | 35 | 23 | 7 | 0 | 0 | 0 | 549 | 549 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 362 | 0 | 0 | 0 | 0 | 0 | 0 | 549 | 362 | 0 | 0 | 184 | 3 | 0 | 0 | 516 | 362 | 152 | 2 | 516 | 516 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 24 |
| `rv64ui-p-sll` | p- | none | default | 2268 | 1675 | 0 | 0 | 29 | 25 | 66 | 54 | 7 | 0 | 0 | 0 | 1675 | 1675 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1440 | 0 | 0 | 0 | 0 | 0 | 0 | 1675 | 1440 | 0 | 0 | 232 | 3 | 0 | 0 | 1624 | 1440 | 182 | 2 | 1624 | 1624 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-slli` | p- | none | default | 1372 | 1033 | 0 | 0 | 20 | 13 | 48 | 36 | 7 | 0 | 0 | 0 | 1033 | 1033 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 864 | 0 | 0 | 0 | 0 | 0 | 0 | 1033 | 864 | 0 | 0 | 166 | 3 | 0 | 0 | 988 | 864 | 122 | 2 | 988 | 988 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-slliw` | p- | none | default | 1378 | 1042 | 0 | 0 | 20 | 13 | 48 | 36 | 7 | 0 | 0 | 0 | 1042 | 1042 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 873 | 0 | 0 | 0 | 0 | 0 | 0 | 1042 | 873 | 0 | 0 | 166 | 3 | 0 | 0 | 996 | 873 | 121 | 2 | 996 | 996 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-sllw` | p- | none | default | 2266 | 1671 | 0 | 0 | 29 | 21 | 63 | 51 | 7 | 0 | 0 | 0 | 1671 | 1671 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 31 | 12 | 0 | 0 | 1437 | 0 | 0 | 0 | 0 | 0 | 0 | 1671 | 1437 | 0 | 0 | 231 | 3 | 0 | 0 | 1621 | 1437 | 182 | 2 | 1621 | 1621 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-slt` | p- | none | default | 2120 | 1588 | 0 | 0 | 29 | 21 | 63 | 51 | 7 | 0 | 0 | 0 | 1588 | 1588 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 31 | 12 | 0 | 0 | 1354 | 0 | 0 | 0 | 0 | 0 | 0 | 1588 | 1354 | 0 | 0 | 231 | 3 | 0 | 0 | 1538 | 1354 | 182 | 2 | 1538 | 1538 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-slti` | p- | none | default | 1308 | 994 | 0 | 0 | 21 | 11 | 46 | 36 | 7 | 0 | 0 | 0 | 994 | 994 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 818 | 0 | 0 | 0 | 0 | 0 | 0 | 994 | 818 | 0 | 0 | 173 | 3 | 0 | 0 | 948 | 818 | 128 | 2 | 948 | 948 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-sltiu` | p- | none | default | 1308 | 994 | 0 | 0 | 21 | 8 | 44 | 34 | 7 | 0 | 0 | 0 | 994 | 994 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 14 | 4 | 0 | 0 | 818 | 0 | 0 | 0 | 0 | 0 | 0 | 994 | 818 | 0 | 0 | 173 | 3 | 0 | 0 | 948 | 818 | 128 | 2 | 948 | 948 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-sltu` | p- | none | default | 2158 | 1609 | 0 | 0 | 29 | 18 | 61 | 49 | 7 | 0 | 0 | 0 | 1609 | 1609 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 29 | 10 | 0 | 0 | 1375 | 0 | 0 | 0 | 0 | 0 | 0 | 1609 | 1375 | 0 | 0 | 231 | 3 | 0 | 0 | 1559 | 1375 | 182 | 2 | 1559 | 1559 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-sra` | p- | none | default | 2218 | 1639 | 0 | 0 | 29 | 25 | 66 | 54 | 7 | 0 | 0 | 0 | 1639 | 1639 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1405 | 0 | 0 | 0 | 0 | 0 | 0 | 1639 | 1405 | 0 | 0 | 231 | 3 | 0 | 0 | 1589 | 1405 | 182 | 2 | 1589 | 1589 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-srai` | p- | none | default | 1350 | 1028 | 0 | 0 | 20 | 12 | 47 | 35 | 7 | 0 | 0 | 0 | 1028 | 1028 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 15 | 5 | 0 | 0 | 856 | 0 | 0 | 0 | 0 | 0 | 0 | 1028 | 856 | 0 | 0 | 169 | 3 | 0 | 0 | 982 | 856 | 124 | 2 | 982 | 982 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-sraiw` | p- | none | default | 1444 | 1078 | 0 | 0 | 20 | 11 | 47 | 35 | 7 | 0 | 0 | 0 | 1078 | 1078 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 15 | 5 | 0 | 0 | 909 | 0 | 0 | 0 | 0 | 0 | 0 | 1078 | 909 | 0 | 0 | 166 | 3 | 0 | 0 | 1031 | 909 | 120 | 2 | 1031 | 1031 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-sraw` | p- | none | default | 2290 | 1689 | 0 | 0 | 29 | 25 | 66 | 54 | 7 | 0 | 0 | 0 | 1689 | 1689 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1454 | 0 | 0 | 0 | 0 | 0 | 0 | 1689 | 1454 | 0 | 0 | 232 | 3 | 0 | 0 | 1638 | 1454 | 182 | 2 | 1638 | 1638 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-srl` | p- | none | default | 2292 | 1694 | 0 | 0 | 29 | 23 | 65 | 53 | 7 | 0 | 0 | 0 | 1694 | 1694 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 33 | 14 | 0 | 0 | 1458 | 0 | 0 | 0 | 0 | 0 | 0 | 1694 | 1458 | 0 | 0 | 233 | 3 | 0 | 0 | 1642 | 1458 | 182 | 2 | 1642 | 1642 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-srli` | p- | none | default | 1390 | 1051 | 0 | 0 | 20 | 11 | 47 | 35 | 7 | 0 | 0 | 0 | 1051 | 1051 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 15 | 5 | 0 | 0 | 882 | 0 | 0 | 0 | 0 | 0 | 0 | 1051 | 882 | 0 | 0 | 166 | 3 | 0 | 0 | 1005 | 882 | 121 | 2 | 1005 | 1005 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-srliw` | p- | none | default | 1398 | 1048 | 0 | 0 | 20 | 11 | 48 | 36 | 7 | 0 | 0 | 0 | 1048 | 1048 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 881 | 0 | 0 | 0 | 0 | 0 | 0 | 1048 | 881 | 0 | 0 | 164 | 3 | 0 | 0 | 1004 | 881 | 121 | 2 | 1004 | 1004 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64ui-p-srlw` | p- | none | default | 2278 | 1671 | 0 | 0 | 29 | 23 | 64 | 52 | 7 | 0 | 0 | 0 | 1671 | 1671 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 32 | 13 | 0 | 0 | 1437 | 0 | 0 | 0 | 0 | 0 | 0 | 1671 | 1437 | 0 | 0 | 231 | 3 | 0 | 0 | 1621 | 1437 | 182 | 2 | 1621 | 1621 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-st_ld` | p- | none | default | 1678 | 991 | 0 | 0 | 17 | 5 | 39 | 24 | 10 | 0 | 0 | 0 | 991 | 991 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 849 | 0 | 0 | 0 | 0 | 0 | 0 | 991 | 849 | 0 | 0 | 139 | 3 | 0 | 0 | 943 | 849 | 92 | 2 | 943 | 943 | 0 | 8 | 0 | 408 | 0 | 0 | 70 | 0 | 71 | 0 | 0 | 0 | 25 |
| `rv64ui-p-sub` | p- | none | default | 2126 | 1588 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1588 | 1588 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1355 | 0 | 0 | 0 | 0 | 0 | 0 | 1588 | 1355 | 0 | 0 | 230 | 3 | 0 | 0 | 1539 | 1355 | 182 | 2 | 1539 | 1539 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-subw` | p- | none | default | 2118 | 1589 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1589 | 1589 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1354 | 0 | 0 | 0 | 0 | 0 | 0 | 1589 | 1354 | 0 | 0 | 232 | 3 | 0 | 0 | 1538 | 1354 | 182 | 2 | 1538 | 1538 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-sw` | p- | none | default | 2040 | 1525 | 0 | 1 | 78 | 23 | 109 | 56 | 48 | 0 | 0 | 0 | 1525 | 1525 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 28 | 11 | 0 | 0 | 1123 | 0 | 0 | 0 | 0 | 0 | 0 | 1525 | 1123 | 0 | 0 | 399 | 3 | 0 | 0 | 1379 | 1123 | 254 | 2 | 1379 | 1379 | 0 | 7 | 0 | 0 | 0 | 0 | 34 | 0 | 35 | 0 | 1 | 0 | 46 |
| `rv64ui-p-xor` | p- | none | default | 2346 | 1762 | 0 | 0 | 29 | 20 | 66 | 54 | 7 | 0 | 0 | 0 | 1762 | 1762 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1530 | 0 | 0 | 0 | 0 | 0 | 0 | 1762 | 1530 | 0 | 0 | 229 | 3 | 0 | 0 | 1714 | 1530 | 182 | 2 | 1714 | 1714 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ui-p-xori` | p- | none | default | 1280 | 981 | 0 | 0 | 20 | 12 | 48 | 36 | 7 | 0 | 0 | 0 | 981 | 981 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 800 | 0 | 0 | 0 | 0 | 0 | 0 | 981 | 800 | 0 | 0 | 178 | 3 | 0 | 0 | 936 | 800 | 134 | 2 | 936 | 936 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64um-p-div` | p- | none | default | 842 | 680 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 680 | 680 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 535 | 0 | 0 | 0 | 0 | 0 | 0 | 680 | 535 | 0 | 0 | 142 | 3 | 0 | 0 | 640 | 535 | 103 | 2 | 640 | 640 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64um-p-divu` | p- | none | default | 842 | 680 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 680 | 680 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 535 | 0 | 0 | 0 | 0 | 0 | 0 | 680 | 535 | 0 | 0 | 142 | 3 | 0 | 0 | 640 | 535 | 103 | 2 | 640 | 640 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64um-p-divuw` | p- | none | default | 830 | 668 | 0 | 0 | 14 | 5 | 36 | 24 | 7 | 0 | 0 | 0 | 668 | 668 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 514 | 0 | 0 | 0 | 0 | 0 | 0 | 668 | 514 | 0 | 0 | 151 | 3 | 0 | 0 | 629 | 514 | 113 | 2 | 629 | 629 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64um-p-divw` | p- | none | default | 826 | 663 | 0 | 0 | 15 | 2 | 34 | 24 | 7 | 0 | 0 | 0 | 663 | 663 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 508 | 0 | 0 | 0 | 0 | 0 | 0 | 663 | 508 | 0 | 0 | 152 | 3 | 0 | 0 | 623 | 508 | 113 | 2 | 623 | 623 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64um-p-mul` | p- | none | default | 2128 | 1588 | 0 | 0 | 29 | 24 | 66 | 54 | 7 | 0 | 0 | 0 | 1588 | 1588 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1354 | 0 | 0 | 0 | 0 | 0 | 0 | 1588 | 1354 | 0 | 0 | 231 | 3 | 0 | 0 | 1538 | 1354 | 182 | 2 | 1538 | 1538 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64um-p-mulh` | p- | none | default | 2158 | 1608 | 0 | 0 | 30 | 23 | 64 | 54 | 7 | 0 | 0 | 0 | 1608 | 1608 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1373 | 0 | 0 | 0 | 0 | 0 | 0 | 1608 | 1373 | 0 | 0 | 232 | 3 | 0 | 0 | 1557 | 1373 | 182 | 2 | 1557 | 1557 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64um-p-mulhsu` | p- | none | default | 2158 | 1608 | 0 | 0 | 30 | 22 | 64 | 54 | 7 | 0 | 0 | 0 | 1608 | 1608 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1373 | 0 | 0 | 0 | 0 | 0 | 0 | 1608 | 1373 | 0 | 0 | 232 | 3 | 0 | 0 | 1557 | 1373 | 182 | 2 | 1557 | 1557 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64um-p-mulhu` | p- | none | default | 2218 | 1642 | 0 | 0 | 30 | 23 | 64 | 54 | 7 | 0 | 0 | 0 | 1642 | 1642 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1407 | 0 | 0 | 0 | 0 | 0 | 0 | 1642 | 1407 | 0 | 0 | 232 | 3 | 0 | 0 | 1591 | 1407 | 182 | 2 | 1591 | 1591 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64um-p-mulw` | p- | none | default | 2018 | 1525 | 0 | 0 | 29 | 21 | 63 | 51 | 7 | 0 | 0 | 0 | 1525 | 1525 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 31 | 12 | 0 | 0 | 1291 | 0 | 0 | 0 | 0 | 0 | 0 | 1525 | 1291 | 0 | 0 | 231 | 3 | 0 | 0 | 1475 | 1291 | 182 | 2 | 1475 | 1475 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64um-p-rem` | p- | none | default | 826 | 666 | 0 | 0 | 14 | 5 | 36 | 24 | 7 | 0 | 0 | 0 | 666 | 666 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 512 | 0 | 0 | 0 | 0 | 0 | 0 | 666 | 512 | 0 | 0 | 151 | 3 | 0 | 0 | 627 | 512 | 113 | 2 | 627 | 627 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64um-p-remu` | p- | none | default | 828 | 667 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 667 | 667 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 513 | 0 | 0 | 0 | 0 | 0 | 0 | 667 | 513 | 0 | 0 | 151 | 3 | 0 | 0 | 628 | 513 | 113 | 2 | 628 | 628 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64um-p-remuw` | p- | none | default | 818 | 662 | 0 | 0 | 14 | 4 | 36 | 24 | 7 | 0 | 0 | 0 | 662 | 662 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 508 | 0 | 0 | 0 | 0 | 0 | 0 | 662 | 508 | 0 | 0 | 151 | 3 | 0 | 0 | 623 | 508 | 113 | 2 | 623 | 623 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64um-p-remw` | p- | none | default | 826 | 663 | 0 | 0 | 15 | 2 | 34 | 24 | 7 | 0 | 0 | 0 | 663 | 663 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 508 | 0 | 0 | 0 | 0 | 0 | 0 | 663 | 508 | 0 | 0 | 152 | 3 | 0 | 0 | 623 | 508 | 113 | 2 | 623 | 623 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 25 |
| `rv64uzba-p-add_uw` | p- | none | default | 2150 | 1607 | 0 | 0 | 29 | 23 | 64 | 52 | 7 | 0 | 0 | 0 | 1607 | 1607 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 32 | 13 | 0 | 0 | 1371 | 0 | 0 | 0 | 0 | 0 | 0 | 1607 | 1371 | 0 | 0 | 233 | 3 | 0 | 0 | 1555 | 1371 | 182 | 2 | 1555 | 1555 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzba-p-sh1add` | p- | none | default | 2156 | 1605 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1605 | 1605 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1372 | 0 | 0 | 0 | 0 | 0 | 0 | 1605 | 1372 | 0 | 0 | 230 | 3 | 0 | 0 | 1556 | 1372 | 182 | 2 | 1556 | 1556 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzba-p-sh1add_uw` | p- | none | default | 2164 | 1606 | 0 | 0 | 29 | 23 | 64 | 52 | 7 | 0 | 0 | 0 | 1606 | 1606 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 32 | 13 | 0 | 0 | 1372 | 0 | 0 | 0 | 0 | 0 | 0 | 1606 | 1372 | 0 | 0 | 231 | 3 | 0 | 0 | 1556 | 1372 | 182 | 2 | 1556 | 1556 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzba-p-sh2add` | p- | none | default | 2156 | 1605 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1605 | 1605 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1372 | 0 | 0 | 0 | 0 | 0 | 0 | 1605 | 1372 | 0 | 0 | 230 | 3 | 0 | 0 | 1556 | 1372 | 182 | 2 | 1556 | 1556 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzba-p-sh2add_uw` | p- | none | default | 2164 | 1606 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1606 | 1606 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1372 | 0 | 0 | 0 | 0 | 0 | 0 | 1606 | 1372 | 0 | 0 | 231 | 3 | 0 | 0 | 1556 | 1372 | 182 | 2 | 1556 | 1556 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzba-p-sh3add` | p- | none | default | 2156 | 1605 | 0 | 0 | 29 | 23 | 64 | 52 | 7 | 0 | 0 | 0 | 1605 | 1605 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 32 | 13 | 0 | 0 | 1372 | 0 | 0 | 0 | 0 | 0 | 0 | 1605 | 1372 | 0 | 0 | 230 | 3 | 0 | 0 | 1556 | 1372 | 182 | 2 | 1556 | 1556 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzba-p-sh3add_uw` | p- | none | default | 2164 | 1606 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1606 | 1606 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1372 | 0 | 0 | 0 | 0 | 0 | 0 | 1606 | 1372 | 0 | 0 | 231 | 3 | 0 | 0 | 1556 | 1372 | 182 | 2 | 1556 | 1556 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzba-p-slli_uw` | p- | none | default | 1394 | 1047 | 0 | 0 | 20 | 11 | 47 | 35 | 7 | 0 | 0 | 0 | 1047 | 1047 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 15 | 5 | 0 | 0 | 879 | 0 | 0 | 0 | 0 | 0 | 0 | 1047 | 879 | 0 | 0 | 165 | 3 | 0 | 0 | 1002 | 879 | 121 | 2 | 1002 | 1002 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64uzbb-p-andn` | p- | none | default | 2336 | 1729 | 0 | 0 | 29 | 24 | 66 | 54 | 7 | 0 | 0 | 0 | 1729 | 1729 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1497 | 0 | 0 | 0 | 0 | 0 | 0 | 1729 | 1497 | 0 | 0 | 229 | 3 | 0 | 0 | 1681 | 1497 | 182 | 2 | 1681 | 1681 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-clz` | p- | none | default | 1188 | 912 | 0 | 0 | 17 | 6 | 41 | 29 | 7 | 0 | 0 | 0 | 912 | 912 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 9 | 2 | 0 | 0 | 763 | 0 | 0 | 0 | 0 | 0 | 0 | 912 | 763 | 0 | 0 | 146 | 3 | 0 | 0 | 869 | 763 | 104 | 2 | 869 | 869 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-clzw` | p- | none | default | 1158 | 894 | 0 | 0 | 17 | 6 | 41 | 29 | 7 | 0 | 0 | 0 | 894 | 894 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 9 | 2 | 0 | 0 | 740 | 0 | 0 | 0 | 0 | 0 | 0 | 894 | 740 | 0 | 0 | 151 | 3 | 0 | 0 | 849 | 740 | 107 | 2 | 849 | 849 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-cpop` | p- | none | default | 1188 | 912 | 0 | 0 | 17 | 8 | 42 | 30 | 7 | 0 | 0 | 0 | 912 | 912 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 10 | 3 | 0 | 0 | 763 | 0 | 0 | 0 | 0 | 0 | 0 | 912 | 763 | 0 | 0 | 146 | 3 | 0 | 0 | 869 | 763 | 104 | 2 | 869 | 869 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-cpopw` | p- | none | default | 1158 | 894 | 0 | 0 | 17 | 8 | 42 | 30 | 7 | 0 | 0 | 0 | 894 | 894 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 10 | 3 | 0 | 0 | 740 | 0 | 0 | 0 | 0 | 0 | 0 | 894 | 740 | 0 | 0 | 151 | 3 | 0 | 0 | 849 | 740 | 107 | 2 | 849 | 849 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-ctz` | p- | none | default | 1188 | 912 | 0 | 0 | 17 | 6 | 41 | 29 | 7 | 0 | 0 | 0 | 912 | 912 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 9 | 2 | 0 | 0 | 763 | 0 | 0 | 0 | 0 | 0 | 0 | 912 | 763 | 0 | 0 | 146 | 3 | 0 | 0 | 869 | 763 | 104 | 2 | 869 | 869 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-ctzw` | p- | none | default | 1158 | 890 | 0 | 0 | 18 | 5 | 39 | 29 | 7 | 0 | 0 | 0 | 890 | 890 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 9 | 2 | 0 | 0 | 736 | 0 | 0 | 0 | 0 | 0 | 0 | 890 | 736 | 0 | 0 | 151 | 3 | 0 | 0 | 845 | 736 | 107 | 2 | 845 | 845 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-max` | p- | none | default | 2130 | 1587 | 0 | 0 | 29 | 19 | 62 | 50 | 7 | 0 | 0 | 0 | 1587 | 1587 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 30 | 11 | 0 | 0 | 1354 | 0 | 0 | 0 | 0 | 0 | 0 | 1587 | 1354 | 0 | 0 | 230 | 3 | 0 | 0 | 1538 | 1354 | 182 | 2 | 1538 | 1538 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-maxu` | p- | none | default | 2188 | 1623 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1623 | 1623 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1390 | 0 | 0 | 0 | 0 | 0 | 0 | 1623 | 1390 | 0 | 0 | 230 | 3 | 0 | 0 | 1574 | 1390 | 182 | 2 | 1574 | 1574 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-min` | p- | none | default | 2122 | 1587 | 0 | 0 | 29 | 24 | 66 | 54 | 7 | 0 | 0 | 0 | 1587 | 1587 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1353 | 0 | 0 | 0 | 0 | 0 | 0 | 1587 | 1353 | 0 | 0 | 231 | 3 | 0 | 0 | 1537 | 1353 | 182 | 2 | 1537 | 1537 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-minu` | p- | none | default | 2170 | 1610 | 0 | 0 | 29 | 23 | 64 | 52 | 7 | 0 | 0 | 0 | 1610 | 1610 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 32 | 13 | 0 | 0 | 1377 | 0 | 0 | 0 | 0 | 0 | 0 | 1610 | 1377 | 0 | 0 | 230 | 3 | 0 | 0 | 1561 | 1377 | 182 | 2 | 1561 | 1561 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-orc_b` | p- | none | default | 1230 | 941 | 0 | 0 | 17 | 9 | 42 | 30 | 7 | 0 | 0 | 0 | 941 | 941 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 10 | 3 | 0 | 0 | 795 | 0 | 0 | 0 | 0 | 0 | 0 | 941 | 795 | 0 | 0 | 143 | 3 | 0 | 0 | 897 | 795 | 100 | 2 | 897 | 897 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-orn` | p- | none | default | 2356 | 1736 | 0 | 0 | 29 | 23 | 66 | 54 | 7 | 0 | 0 | 0 | 1736 | 1736 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1501 | 0 | 0 | 0 | 0 | 0 | 0 | 1736 | 1501 | 0 | 0 | 232 | 3 | 0 | 0 | 1685 | 1501 | 182 | 2 | 1685 | 1685 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-rev8` | p- | none | default | 1266 | 960 | 0 | 0 | 17 | 8 | 42 | 30 | 7 | 0 | 0 | 0 | 960 | 960 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 10 | 3 | 0 | 0 | 815 | 0 | 0 | 0 | 0 | 0 | 0 | 960 | 815 | 0 | 0 | 142 | 3 | 0 | 0 | 916 | 815 | 99 | 2 | 916 | 916 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-rol` | p- | none | default | 2278 | 1675 | 0 | 0 | 29 | 24 | 65 | 53 | 7 | 0 | 0 | 0 | 1675 | 1675 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 33 | 14 | 0 | 0 | 1442 | 0 | 0 | 0 | 0 | 0 | 0 | 1675 | 1442 | 0 | 0 | 230 | 3 | 0 | 0 | 1626 | 1442 | 182 | 2 | 1626 | 1626 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-rolw` | p- | none | default | 2274 | 1671 | 0 | 0 | 29 | 21 | 63 | 51 | 7 | 0 | 0 | 0 | 1671 | 1671 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 31 | 12 | 0 | 0 | 1437 | 0 | 0 | 0 | 0 | 0 | 0 | 1671 | 1437 | 0 | 0 | 231 | 3 | 0 | 0 | 1621 | 1437 | 182 | 2 | 1621 | 1621 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-ror` | p- | none | default | 2334 | 1718 | 0 | 0 | 29 | 20 | 63 | 51 | 7 | 0 | 0 | 0 | 1718 | 1718 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 31 | 12 | 0 | 0 | 1482 | 0 | 0 | 0 | 0 | 0 | 0 | 1718 | 1482 | 0 | 0 | 233 | 3 | 0 | 0 | 1665 | 1482 | 181 | 2 | 1665 | 1665 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-rori` | p- | none | default | 1406 | 1051 | 0 | 0 | 21 | 7 | 44 | 34 | 7 | 0 | 0 | 0 | 1051 | 1051 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 14 | 4 | 0 | 0 | 881 | 0 | 0 | 0 | 0 | 0 | 0 | 1051 | 881 | 0 | 0 | 167 | 3 | 0 | 0 | 1004 | 881 | 121 | 2 | 1004 | 1004 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64uzbb-p-roriw` | p- | none | default | 1318 | 1008 | 0 | 0 | 20 | 8 | 45 | 33 | 7 | 0 | 0 | 0 | 1008 | 1008 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 13 | 3 | 0 | 0 | 835 | 0 | 0 | 0 | 0 | 0 | 0 | 1008 | 835 | 0 | 0 | 170 | 3 | 0 | 0 | 962 | 835 | 125 | 2 | 962 | 962 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64uzbb-p-rorw` | p- | none | default | 2202 | 1639 | 0 | 0 | 29 | 25 | 66 | 54 | 7 | 0 | 0 | 0 | 1639 | 1639 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1404 | 0 | 0 | 0 | 0 | 0 | 0 | 1639 | 1404 | 0 | 0 | 232 | 3 | 0 | 0 | 1588 | 1404 | 182 | 2 | 1588 | 1588 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-sext_b` | p- | none | default | 1188 | 912 | 0 | 0 | 17 | 8 | 42 | 30 | 7 | 0 | 0 | 0 | 912 | 912 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 10 | 3 | 0 | 0 | 763 | 0 | 0 | 0 | 0 | 0 | 0 | 912 | 763 | 0 | 0 | 146 | 3 | 0 | 0 | 869 | 763 | 104 | 2 | 869 | 869 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-sext_h` | p- | none | default | 1194 | 915 | 0 | 0 | 17 | 7 | 41 | 29 | 7 | 0 | 0 | 0 | 915 | 915 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 9 | 2 | 0 | 0 | 765 | 0 | 0 | 0 | 0 | 0 | 0 | 915 | 765 | 0 | 0 | 147 | 3 | 0 | 0 | 871 | 765 | 104 | 2 | 871 | 871 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbb-p-xnor` | p- | none | default | 2354 | 1736 | 0 | 0 | 29 | 22 | 66 | 54 | 7 | 0 | 0 | 0 | 1736 | 1736 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1501 | 0 | 0 | 0 | 0 | 0 | 0 | 1736 | 1501 | 0 | 0 | 232 | 3 | 0 | 0 | 1685 | 1501 | 182 | 2 | 1685 | 1685 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbb-p-zext_h` | p- | none | default | 1200 | 923 | 0 | 0 | 17 | 9 | 42 | 30 | 7 | 0 | 0 | 0 | 923 | 923 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 10 | 3 | 0 | 0 | 775 | 0 | 0 | 0 | 0 | 0 | 0 | 923 | 775 | 0 | 0 | 145 | 3 | 0 | 0 | 878 | 775 | 101 | 2 | 878 | 878 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbc-p-clmul` | p- | none | default | 2130 | 1588 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1588 | 1588 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1355 | 0 | 0 | 0 | 0 | 0 | 0 | 1588 | 1355 | 0 | 0 | 230 | 3 | 0 | 0 | 1539 | 1355 | 182 | 2 | 1539 | 1539 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbc-p-clmulh` | p- | none | default | 2140 | 1589 | 0 | 0 | 29 | 26 | 66 | 54 | 7 | 0 | 0 | 0 | 1589 | 1589 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1356 | 0 | 0 | 0 | 0 | 0 | 0 | 1589 | 1356 | 0 | 0 | 230 | 3 | 0 | 0 | 1540 | 1356 | 182 | 2 | 1540 | 1540 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbc-p-clmulr` | p- | none | default | 2136 | 1588 | 0 | 0 | 29 | 19 | 62 | 50 | 7 | 0 | 0 | 0 | 1588 | 1588 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 30 | 11 | 0 | 0 | 1355 | 0 | 0 | 0 | 0 | 0 | 0 | 1588 | 1355 | 0 | 0 | 230 | 3 | 0 | 0 | 1539 | 1355 | 182 | 2 | 1539 | 1539 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbkb-p-brev8` | p- | none | default | 1218 | 925 | 0 | 0 | 17 | 9 | 42 | 30 | 7 | 0 | 0 | 0 | 925 | 925 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 10 | 3 | 0 | 0 | 772 | 0 | 0 | 0 | 0 | 0 | 0 | 925 | 772 | 0 | 0 | 150 | 3 | 0 | 0 | 882 | 772 | 108 | 2 | 882 | 882 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 28 |
| `rv64uzbkb-p-pack` | p- | none | default | 2588 | 1909 | 0 | 0 | 29 | 22 | 66 | 54 | 7 | 0 | 0 | 0 | 1909 | 1909 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1679 | 0 | 0 | 0 | 0 | 0 | 0 | 1909 | 1679 | 0 | 0 | 227 | 3 | 0 | 0 | 1858 | 1679 | 177 | 2 | 1858 | 1858 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbkb-p-packh` | p- | none | default | 2258 | 1687 | 0 | 0 | 29 | 24 | 66 | 54 | 7 | 0 | 0 | 0 | 1687 | 1687 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1453 | 0 | 0 | 0 | 0 | 0 | 0 | 1687 | 1453 | 0 | 0 | 231 | 3 | 0 | 0 | 1637 | 1453 | 182 | 2 | 1637 | 1637 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbkb-p-packw` | p- | none | default | 2128 | 1600 | 0 | 0 | 29 | 22 | 65 | 53 | 7 | 0 | 0 | 0 | 1600 | 1600 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 33 | 14 | 0 | 0 | 1365 | 0 | 0 | 0 | 0 | 0 | 0 | 1600 | 1365 | 0 | 0 | 232 | 3 | 0 | 0 | 1549 | 1365 | 182 | 2 | 1549 | 1549 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbkx-p-xperm4` | p- | none | default | 2428 | 1784 | 0 | 0 | 29 | 24 | 66 | 54 | 7 | 0 | 0 | 0 | 1784 | 1784 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1554 | 0 | 0 | 0 | 0 | 0 | 0 | 1784 | 1554 | 0 | 0 | 227 | 3 | 0 | 0 | 1737 | 1554 | 181 | 2 | 1737 | 1737 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbkx-p-xperm8` | p- | none | default | 3276 | 2304 | 0 | 0 | 29 | 20 | 66 | 54 | 7 | 0 | 0 | 0 | 2304 | 2304 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 2072 | 0 | 0 | 0 | 0 | 0 | 0 | 2304 | 2072 | 0 | 0 | 229 | 3 | 0 | 0 | 2252 | 2072 | 178 | 2 | 2252 | 2252 | 0 | 8 | 0 | 138 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbs-p-bclr` | p- | none | default | 2474 | 1792 | 0 | 0 | 29 | 22 | 66 | 54 | 7 | 0 | 0 | 0 | 1792 | 1792 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1567 | 0 | 0 | 0 | 0 | 0 | 0 | 1792 | 1567 | 0 | 0 | 222 | 3 | 0 | 0 | 1748 | 1567 | 179 | 2 | 1748 | 1748 | 0 | 8 | 0 | 22 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbs-p-bclri` | p- | none | default | 1462 | 1096 | 0 | 0 | 20 | 12 | 48 | 36 | 7 | 0 | 0 | 0 | 1096 | 1096 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 929 | 0 | 0 | 0 | 0 | 0 | 0 | 1096 | 929 | 0 | 0 | 164 | 3 | 0 | 0 | 1051 | 929 | 120 | 2 | 1051 | 1051 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64uzbs-p-bext` | p- | none | default | 2340 | 1718 | 0 | 0 | 29 | 25 | 66 | 54 | 7 | 0 | 0 | 0 | 1718 | 1718 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1485 | 0 | 0 | 0 | 0 | 0 | 0 | 1718 | 1485 | 0 | 0 | 230 | 3 | 0 | 0 | 1669 | 1485 | 182 | 2 | 1669 | 1669 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbs-p-bexti` | p- | none | default | 1396 | 1057 | 0 | 0 | 20 | 10 | 47 | 35 | 7 | 0 | 0 | 0 | 1057 | 1057 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 15 | 5 | 0 | 0 | 884 | 0 | 0 | 0 | 0 | 0 | 0 | 1057 | 884 | 0 | 0 | 170 | 3 | 0 | 0 | 1010 | 884 | 124 | 2 | 1010 | 1010 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64uzbs-p-binv` | p- | none | default | 2308 | 1698 | 0 | 0 | 29 | 23 | 66 | 54 | 7 | 0 | 0 | 0 | 1698 | 1698 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1466 | 0 | 0 | 0 | 0 | 0 | 0 | 1698 | 1466 | 0 | 0 | 229 | 3 | 0 | 0 | 1650 | 1466 | 182 | 2 | 1650 | 1650 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbs-p-binvi` | p- | none | default | 1400 | 1053 | 0 | 0 | 20 | 9 | 46 | 34 | 7 | 0 | 0 | 0 | 1053 | 1053 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 14 | 4 | 0 | 0 | 883 | 0 | 0 | 0 | 0 | 0 | 0 | 1053 | 883 | 0 | 0 | 167 | 3 | 0 | 0 | 1006 | 883 | 121 | 2 | 1006 | 1006 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64uzbs-p-bset` | p- | none | default | 2478 | 1791 | 0 | 0 | 29 | 19 | 66 | 54 | 7 | 0 | 0 | 0 | 1791 | 1791 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1566 | 0 | 0 | 0 | 0 | 0 | 0 | 1791 | 1566 | 0 | 0 | 222 | 3 | 0 | 0 | 1747 | 1566 | 179 | 2 | 1747 | 1747 | 0 | 8 | 0 | 26 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzbs-p-bseti` | p- | none | default | 1476 | 1103 | 0 | 0 | 20 | 11 | 48 | 36 | 7 | 0 | 0 | 0 | 1103 | 1103 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 16 | 6 | 0 | 0 | 933 | 0 | 0 | 0 | 0 | 0 | 0 | 1103 | 933 | 0 | 0 | 167 | 3 | 0 | 0 | 1055 | 933 | 120 | 2 | 1055 | 1055 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 31 |
| `rv64uzfh-p-fadd` | p- | none | default | 1321 | 1066 | 0 | 0 | 14 | 5 | 48 | 36 | 7 | 0 | 0 | 0 | 1066 | 1066 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 857 | 0 | 0 | 0 | 0 | 0 | 0 | 1066 | 857 | 0 | 0 | 206 | 3 | 0 | 0 | 1018 | 857 | 159 | 2 | 1018 | 1018 | 0 | 7 | 0 | 0 | 0 | 0 | 40 | 0 | 1 | 0 | 0 | 0 | 37 |
| `rv64uzfh-p-fclass` | p- | none | default | 866 | 708 | 0 | 0 | 14 | 4 | 38 | 26 | 7 | 0 | 0 | 0 | 708 | 708 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 556 | 0 | 0 | 0 | 0 | 0 | 0 | 708 | 556 | 0 | 0 | 149 | 3 | 0 | 0 | 667 | 556 | 109 | 2 | 667 | 667 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 27 |
| `rv64uzfh-p-fcmp` | p- | none | default | 1055 | 861 | 0 | 0 | 14 | 4 | 44 | 32 | 7 | 0 | 0 | 0 | 861 | 861 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 661 | 0 | 0 | 0 | 0 | 0 | 0 | 861 | 661 | 0 | 0 | 197 | 3 | 0 | 0 | 815 | 661 | 152 | 2 | 815 | 815 | 0 | 7 | 0 | 0 | 0 | 0 | 24 | 0 | 1 | 0 | 0 | 0 | 33 |
| `rv64uzfh-p-fcvt` | p- | none | default | 1189 | 981 | 0 | 0 | 14 | 5 | 48 | 36 | 7 | 0 | 0 | 0 | 981 | 981 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 769 | 0 | 0 | 0 | 0 | 0 | 0 | 981 | 769 | 0 | 0 | 209 | 3 | 0 | 0 | 936 | 769 | 165 | 2 | 936 | 936 | 0 | 7 | 0 | 0 | 0 | 0 | 16 | 0 | 1 | 0 | 0 | 0 | 37 |
| `rv64uzfh-p-fcvt_w` | p- | none | default | 2340 | 2115 | 0 | 0 | 14 | 5 | 67 | 55 | 7 | 0 | 0 | 0 | 2115 | 2115 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 1844 | 0 | 0 | 0 | 0 | 0 | 0 | 2115 | 1844 | 0 | 0 | 268 | 3 | 0 | 0 | 2046 | 1844 | 200 | 2 | 2046 | 2046 | 0 | 7 | 0 | 0 | 0 | 0 | 132 | 0 | 1 | 0 | 0 | 0 | 56 |
| `rv64uzfh-p-fdiv` | p- | none | default | 1137 | 927 | 0 | 0 | 14 | 4 | 45 | 33 | 7 | 0 | 0 | 0 | 927 | 927 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 734 | 0 | 0 | 0 | 0 | 0 | 0 | 927 | 734 | 0 | 0 | 190 | 3 | 0 | 0 | 880 | 734 | 144 | 2 | 880 | 880 | 0 | 7 | 0 | 0 | 0 | 0 | 28 | 0 | 1 | 0 | 0 | 0 | 34 |
| `rv64uzfh-p-fmadd` | p- | none | default | 1437 | 1165 | 0 | 0 | 14 | 5 | 50 | 38 | 7 | 0 | 0 | 0 | 1165 | 1165 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 941 | 0 | 0 | 0 | 0 | 0 | 0 | 1165 | 941 | 0 | 0 | 221 | 3 | 0 | 0 | 1113 | 941 | 170 | 2 | 1113 | 1113 | 0 | 7 | 0 | 0 | 0 | 0 | 48 | 0 | 1 | 0 | 0 | 0 | 39 |
| `rv64uzfh-p-fmin` | p- | none | default | 1777 | 1452 | 0 | 0 | 14 | 4 | 56 | 44 | 7 | 0 | 0 | 0 | 1452 | 1452 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 1189 | 0 | 0 | 0 | 0 | 0 | 0 | 1452 | 1189 | 0 | 0 | 260 | 3 | 0 | 0 | 1398 | 1189 | 207 | 2 | 1398 | 1398 | 0 | 7 | 0 | 0 | 0 | 0 | 72 | 0 | 1 | 0 | 0 | 0 | 45 |
| `rv64uzfh-p-ldst` | p- | none | default | 830 | 679 | 0 | 0 | 14 | 5 | 38 | 26 | 7 | 0 | 0 | 0 | 679 | 679 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 501 | 0 | 0 | 0 | 0 | 0 | 0 | 679 | 501 | 0 | 0 | 175 | 3 | 0 | 0 | 638 | 501 | 135 | 2 | 638 | 638 | 0 | 7 | 0 | 0 | 0 | 0 | 4 | 0 | 3 | 0 | 0 | 0 | 27 |
| `rv64uzfh-p-move` | p- | none | default | 1309 | 1046 | 0 | 0 | 14 | 4 | 46 | 34 | 7 | 0 | 0 | 0 | 1046 | 1046 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 882 | 0 | 0 | 0 | 0 | 0 | 0 | 1046 | 882 | 0 | 0 | 161 | 3 | 0 | 0 | 994 | 882 | 110 | 2 | 994 | 994 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 35 |
| `rv64uzfh-p-recoding` | p- | none | default | 808 | 664 | 0 | 0 | 14 | 5 | 38 | 26 | 7 | 0 | 0 | 0 | 664 | 664 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 490 | 0 | 0 | 0 | 0 | 0 | 0 | 664 | 490 | 0 | 0 | 171 | 3 | 0 | 0 | 623 | 490 | 131 | 2 | 623 | 623 | 0 | 7 | 0 | 0 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 0 | 27 |
| `rv64uziccid-p-ziccid` | p- | none | default | 7137 | 5967 | 520 | 0 | 745 | 1386 | 1636 | 589 | 1043 | 0 | 0 | 0 | 5967 | 5967 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 380 | 180 | 0 | 0 | 3320 | 0 | 0 | 0 | 0 | 0 | 0 | 5967 | 3320 | 0 | 0 | 2644 | 3 | 0 | 0 | 4810 | 3320 | 1488 | 2 | 4810 | 4810 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 105 | 0 | 0 | 0 | 415 |
| `rv64uzicond-p-czero_eqz` | p- | none | default | 2064 | 1548 | 0 | 0 | 30 | 21 | 62 | 52 | 7 | 0 | 0 | 0 | 1548 | 1548 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 32 | 13 | 0 | 0 | 1313 | 0 | 0 | 0 | 0 | 0 | 0 | 1548 | 1313 | 0 | 0 | 232 | 3 | 0 | 0 | 1497 | 1313 | 182 | 2 | 1497 | 1497 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64uzicond-p-czero_nez` | p- | none | default | 2064 | 1551 | 0 | 0 | 29 | 24 | 66 | 54 | 7 | 0 | 0 | 0 | 1551 | 1551 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 34 | 15 | 0 | 0 | 1318 | 0 | 0 | 0 | 0 | 0 | 0 | 1551 | 1318 | 0 | 0 | 230 | 3 | 0 | 0 | 1502 | 1318 | 182 | 2 | 1502 | 1502 | 0 | 7 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 40 |
| `rv64ua-v-amoadd_d` | v- | 15/18 | default | 21104 | 7522 | 179 | 1 | 448 | 4477 | 2069 | 1279 | 775 | 0 | 0 | 0 | 7522 | 7522 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1133 | 968 | 0 | 0 | 5331 | 0 | 0 | 0 | 99 | 0 | 0 | 7522 | 5331 | 0 | 0 | 2188 | 3 | 0 | 0 | 6692 | 5331 | 1359 | 2 | 6692 | 6692 | 0 | 8 | 0 | 823 | 0 | 0 | 2891 | 0 | 1987 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amoadd_w` | v- | 16/18 | default | 21066 | 7480 | 178 | 1 | 449 | 4477 | 2067 | 1279 | 773 | 0 | 0 | 0 | 7480 | 7480 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1133 | 968 | 0 | 0 | 5301 | 0 | 0 | 0 | 14 | 0 | 0 | 7480 | 5301 | 0 | 0 | 2176 | 3 | 0 | 0 | 6655 | 5301 | 1352 | 2 | 6655 | 6655 | 0 | 8 | 0 | 837 | 0 | 0 | 2891 | 0 | 1987 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amoand_d` | v- | 17/18 | default | 21060 | 7475 | 178 | 1 | 450 | 4479 | 2061 | 1281 | 765 | 0 | 0 | 0 | 7475 | 7475 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1135 | 967 | 0 | 0 | 5304 | 0 | 0 | 0 | 14 | 0 | 0 | 7475 | 5304 | 0 | 0 | 2168 | 3 | 0 | 0 | 6650 | 5304 | 1344 | 2 | 6650 | 6650 | 0 | 8 | 0 | 837 | 0 | 0 | 2895 | 0 | 1987 | 0 | 0 | 0 | 219 |
| `rv64ua-v-amoand_w` | v- | 18/18 | default | 21082 | 7496 | 178 | 1 | 448 | 4492 | 2071 | 1281 | 775 | 0 | 0 | 0 | 7496 | 7496 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1135 | 967 | 0 | 0 | 5289 | 0 | 0 | 0 | 14 | 0 | 0 | 7496 | 5289 | 0 | 0 | 2204 | 3 | 0 | 0 | 6660 | 5289 | 1369 | 2 | 6660 | 6660 | 0 | 8 | 0 | 823 | 0 | 0 | 2895 | 0 | 1987 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amomax_d` | v- | 1/18 | default | 21052 | 7454 | 178 | 1 | 447 | 4439 | 2039 | 1278 | 746 | 0 | 0 | 0 | 7454 | 7454 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5250 | 0 | 0 | 0 | 14 | 0 | 0 | 7454 | 5250 | 0 | 0 | 2201 | 3 | 0 | 0 | 6625 | 5250 | 1373 | 2 | 6625 | 6625 | 0 | 8 | 0 | 816 | 0 | 0 | 2889 | 0 | 1988 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amomax_w` | v- | 4/18 | default | 21056 | 7509 | 178 | 1 | 446 | 4452 | 2049 | 1278 | 756 | 0 | 0 | 0 | 7509 | 7509 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5333 | 0 | 0 | 0 | 74 | 0 | 0 | 7509 | 5333 | 0 | 0 | 2173 | 3 | 0 | 0 | 6678 | 5333 | 1343 | 2 | 6678 | 6678 | 0 | 8 | 0 | 795 | 0 | 0 | 2890 | 0 | 1989 | 0 | 0 | 0 | 217 |
| `rv64ua-v-amomaxu_d` | v- | 2/18 | default | 21052 | 7454 | 178 | 1 | 447 | 4439 | 2039 | 1278 | 746 | 0 | 0 | 0 | 7454 | 7454 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5250 | 0 | 0 | 0 | 14 | 0 | 0 | 7454 | 5250 | 0 | 0 | 2201 | 3 | 0 | 0 | 6625 | 5250 | 1373 | 2 | 6625 | 6625 | 0 | 8 | 0 | 816 | 0 | 0 | 2889 | 0 | 1988 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amomaxu_w` | v- | 3/18 | default | 21056 | 7509 | 178 | 1 | 446 | 4452 | 2049 | 1278 | 756 | 0 | 0 | 0 | 7509 | 7509 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5333 | 0 | 0 | 0 | 74 | 0 | 0 | 7509 | 5333 | 0 | 0 | 2173 | 3 | 0 | 0 | 6678 | 5333 | 1343 | 2 | 6678 | 6678 | 0 | 8 | 0 | 795 | 0 | 0 | 2890 | 0 | 1989 | 0 | 0 | 0 | 217 |
| `rv64ua-v-amomin_d` | v- | 5/18 | default | 21052 | 7454 | 178 | 1 | 447 | 4439 | 2039 | 1278 | 746 | 0 | 0 | 0 | 7454 | 7454 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5250 | 0 | 0 | 0 | 14 | 0 | 0 | 7454 | 5250 | 0 | 0 | 2201 | 3 | 0 | 0 | 6625 | 5250 | 1373 | 2 | 6625 | 6625 | 0 | 8 | 0 | 816 | 0 | 0 | 2889 | 0 | 1988 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amomin_w` | v- | 8/18 | default | 21097 | 7548 | 178 | 1 | 450 | 4479 | 2059 | 1281 | 763 | 0 | 0 | 0 | 7548 | 7548 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1135 | 967 | 0 | 0 | 5361 | 0 | 0 | 0 | 74 | 0 | 0 | 7548 | 5361 | 0 | 0 | 2184 | 3 | 0 | 0 | 6712 | 5361 | 1349 | 2 | 6712 | 6712 | 0 | 8 | 0 | 795 | 0 | 0 | 2896 | 0 | 1989 | 0 | 0 | 0 | 219 |
| `rv64ua-v-amominu_d` | v- | 6/18 | default | 21116 | 7610 | 179 | 1 | 465 | 4482 | 2097 | 1280 | 802 | 0 | 0 | 0 | 7610 | 7610 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1134 | 963 | 0 | 0 | 5342 | 0 | 0 | 0 | 14 | 0 | 0 | 7610 | 5342 | 0 | 0 | 2265 | 3 | 0 | 0 | 6751 | 5342 | 1407 | 2 | 6751 | 6751 | 0 | 8 | 0 | 816 | 0 | 0 | 2891 | 0 | 1988 | 0 | 0 | 0 | 225 |
| `rv64ua-v-amominu_w` | v- | 7/18 | default | 21119 | 7662 | 179 | 1 | 466 | 4482 | 2097 | 1280 | 802 | 0 | 0 | 0 | 7662 | 7662 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1134 | 963 | 0 | 0 | 5415 | 0 | 0 | 0 | 74 | 0 | 0 | 7662 | 5415 | 0 | 0 | 2244 | 3 | 0 | 0 | 6798 | 5415 | 1381 | 2 | 6798 | 6798 | 0 | 8 | 0 | 795 | 0 | 0 | 2892 | 0 | 1989 | 0 | 0 | 0 | 225 |
| `rv64ua-v-amoor_d` | v- | 9/18 | default | 21017 | 7424 | 178 | 1 | 447 | 4439 | 2039 | 1278 | 746 | 0 | 0 | 0 | 7424 | 7424 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5226 | 0 | 0 | 0 | 77 | 0 | 0 | 7424 | 5226 | 0 | 0 | 2195 | 3 | 0 | 0 | 6595 | 5226 | 1367 | 2 | 6595 | 6595 | 0 | 8 | 0 | 823 | 0 | 0 | 2889 | 0 | 1987 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amoor_w` | v- | 10/18 | default | 21018 | 7427 | 178 | 1 | 445 | 4452 | 2049 | 1278 | 756 | 0 | 0 | 0 | 7427 | 7427 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5236 | 0 | 0 | 0 | 77 | 0 | 0 | 7427 | 5236 | 0 | 0 | 2188 | 3 | 0 | 0 | 6601 | 5236 | 1363 | 2 | 6601 | 6601 | 0 | 8 | 0 | 823 | 0 | 0 | 2889 | 0 | 1987 | 0 | 0 | 0 | 217 |
| `rv64ua-v-amoswap_d` | v- | 11/18 | default | 21061 | 7478 | 178 | 1 | 448 | 4493 | 2071 | 1281 | 775 | 0 | 0 | 0 | 7478 | 7478 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1135 | 967 | 0 | 0 | 5314 | 0 | 0 | 0 | 14 | 0 | 0 | 7478 | 5314 | 0 | 0 | 2161 | 3 | 0 | 0 | 6656 | 5314 | 1340 | 2 | 6656 | 6656 | 0 | 8 | 0 | 837 | 0 | 0 | 2895 | 0 | 1987 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amoswap_w` | v- | 12/18 | default | 21081 | 7493 | 178 | 1 | 450 | 4479 | 2061 | 1281 | 765 | 0 | 0 | 0 | 7493 | 7493 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1135 | 967 | 0 | 0 | 5279 | 0 | 0 | 0 | 14 | 0 | 0 | 7493 | 5279 | 0 | 0 | 2211 | 3 | 0 | 0 | 6654 | 5279 | 1373 | 2 | 6654 | 6654 | 0 | 8 | 0 | 823 | 0 | 0 | 2895 | 0 | 1987 | 0 | 0 | 0 | 219 |
| `rv64ua-v-amoxor_d` | v- | 13/18 | default | 21037 | 7464 | 178 | 1 | 450 | 4439 | 2044 | 1278 | 751 | 0 | 0 | 0 | 7464 | 7464 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5284 | 0 | 0 | 0 | 0 | 0 | 0 | 7464 | 5284 | 0 | 0 | 2177 | 3 | 0 | 0 | 6638 | 5284 | 1352 | 2 | 6638 | 6638 | 0 | 8 | 0 | 823 | 0 | 0 | 2889 | 0 | 1987 | 0 | 0 | 0 | 218 |
| `rv64ua-v-amoxor_w` | v- | 14/18 | default | 21003 | 7429 | 179 | 1 | 450 | 4441 | 2045 | 1278 | 752 | 0 | 0 | 0 | 7429 | 7429 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1132 | 968 | 0 | 0 | 5271 | 0 | 0 | 0 | 87 | 0 | 0 | 7429 | 5271 | 0 | 0 | 2155 | 3 | 0 | 0 | 6603 | 5271 | 1330 | 2 | 6603 | 6603 | 0 | 8 | 0 | 823 | 0 | 0 | 2889 | 0 | 1987 | 0 | 0 | 0 | 218 |
| `rv64ua-v-lrsc` | v- | 15/18 | default | 36147 | 12782 | 159 | 1 | 446 | 7087 | 4721 | 2380 | 2326 | 0 | 0 | 0 | 12782 | 12782 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 2157 | 1988 | 0 | 0 | 10567 | 0 | 0 | 0 | 74 | 0 | 0 | 12782 | 10567 | 0 | 0 | 2212 | 3 | 0 | 0 | 11925 | 10567 | 1356 | 2 | 11925 | 11925 | 0 | 8 | 0 | 793 | 0 | 0 | 2891 | 1025 | 1986 | 1028 | 77 | 0 | 296 |
| `rv64uc-v-rvc` | v- | 14/18 | default | 29128 | 10852 | 180 | 1 | 722 | 7809 | 3105 | 1984 | 1106 | 0 | 0 | 0 | 10852 | 10852 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1780 | 1635 | 0 | 0 | 7759 | 0 | 0 | 0 | 835 | 33 | 0 | 10852 | 7759 | 0 | 0 | 3090 | 3 | 0 | 0 | 9478 | 7759 | 1717 | 2 | 9478 | 9478 | 0 | 8 | 0 | 17 | 0 | 0 | 4535 | 0 | 2601 | 0 | 0 | 0 | 296 |
| `rv64ud-v-fadd` | v- | 9/18 | default | 20514 | 7396 | 156 | 1 | 387 | 7350 | 2340 | 1655 | 670 | 0 | 0 | 0 | 7396 | 7396 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5541 | 0 | 0 | 0 | 70 | 0 | 0 | 7396 | 5541 | 0 | 0 | 1852 | 3 | 0 | 0 | 6661 | 5541 | 1118 | 2 | 6661 | 6661 | 0 | 8 | 0 | 567 | 0 | 0 | 3395 | 0 | 1433 | 0 | 0 | 0 | 200 |
| `rv64ud-v-fclass` | v- | 10/18 | default | 11949 | 4471 | 149 | 1 | 270 | 4046 | 1444 | 957 | 472 | 0 | 0 | 0 | 4471 | 4471 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3253 | 0 | 0 | 0 | 0 | 0 | 0 | 4471 | 3253 | 0 | 0 | 1215 | 3 | 0 | 0 | 3970 | 3253 | 715 | 2 | 3970 | 3970 | 0 | 8 | 0 | 467 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 134 |
| `rv64ud-v-fcmp` | v- | 11/18 | default | 20681 | 7599 | 153 | 1 | 384 | 7344 | 2336 | 1660 | 661 | 0 | 0 | 0 | 7599 | 7599 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5760 | 0 | 0 | 0 | 56 | 0 | 0 | 7599 | 5760 | 0 | 0 | 1836 | 3 | 0 | 0 | 6867 | 5760 | 1105 | 2 | 6867 | 6867 | 0 | 8 | 0 | 454 | 0 | 0 | 3415 | 0 | 1433 | 0 | 0 | 0 | 205 |
| `rv64ud-v-fcvt` | v- | 12/18 | default | 20305 | 7186 | 152 | 1 | 381 | 7339 | 2325 | 1655 | 655 | 0 | 0 | 0 | 7186 | 7186 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5353 | 0 | 0 | 0 | 0 | 0 | 0 | 7186 | 5353 | 0 | 0 | 1830 | 3 | 0 | 0 | 6467 | 5353 | 1112 | 2 | 6467 | 6467 | 0 | 8 | 0 | 594 | 0 | 0 | 3372 | 0 | 1433 | 0 | 0 | 0 | 200 |
| `rv64ud-v-fcvt_w` | v- | 13/18 | default | 29818 | 11160 | 159 | 1 | 486 | 10623 | 3206 | 2367 | 824 | 0 | 0 | 0 | 11160 | 11160 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 2157 | 2009 | 0 | 0 | 8740 | 0 | 0 | 0 | 53 | 0 | 0 | 11160 | 8740 | 0 | 0 | 2417 | 3 | 0 | 0 | 10213 | 8740 | 1471 | 2 | 10213 | 10213 | 0 | 8 | 0 | 897 | 0 | 0 | 5136 | 0 | 2044 | 0 | 0 | 0 | 282 |
| `rv64ud-v-fdiv` | v- | 14/18 | default | 20385 | 7267 | 156 | 1 | 385 | 7351 | 2336 | 1653 | 668 | 0 | 0 | 0 | 7267 | 7267 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5431 | 0 | 0 | 0 | 0 | 0 | 0 | 7267 | 5431 | 0 | 0 | 1833 | 3 | 0 | 0 | 6531 | 5431 | 1098 | 2 | 6531 | 6531 | 0 | 8 | 0 | 587 | 0 | 0 | 3387 | 0 | 1433 | 0 | 0 | 0 | 198 |
| `rv64ud-v-fmadd` | v- | 15/18 | default | 20677 | 7561 | 156 | 1 | 393 | 7344 | 2346 | 1656 | 674 | 0 | 1 | 0 | 7561 | 7561 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 5682 | 0 | 0 | 0 | 51 | 0 | 0 | 7561 | 5682 | 0 | 0 | 1876 | 3 | 0 | 0 | 6815 | 5682 | 1131 | 2 | 6815 | 6815 | 0 | 8 | 0 | 521 | 0 | 0 | 3403 | 0 | 1433 | 0 | 0 | 0 | 205 |
| `rv64ud-v-fmin` | v- | 16/18 | default | 21000 | 7943 | 156 | 1 | 392 | 7344 | 2350 | 1662 | 672 | 0 | 1 | 0 | 7943 | 7943 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 6034 | 0 | 0 | 0 | 93 | 0 | 0 | 7943 | 6034 | 0 | 0 | 1906 | 3 | 0 | 0 | 7196 | 6034 | 1160 | 2 | 7196 | 7196 | 0 | 8 | 0 | 426 | 0 | 0 | 3427 | 0 | 1433 | 0 | 0 | 0 | 211 |
| `rv64ud-v-ldst` | v- | 17/18 | default | 20947 | 7508 | 158 | 1 | 461 | 4433 | 2043 | 1281 | 747 | 0 | 0 | 0 | 7508 | 7508 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1134 | 967 | 0 | 0 | 5336 | 0 | 0 | 0 | 61 | 0 | 0 | 7508 | 5336 | 0 | 0 | 2169 | 3 | 0 | 0 | 6663 | 5336 | 1325 | 2 | 6663 | 6663 | 0 | 8 | 0 | 788 | 0 | 0 | 2901 | 0 | 1991 | 0 | 0 | 0 | 226 |
| `rv64ud-v-move` | v- | 18/18 | default | 21575 | 7713 | 158 | 1 | 383 | 7361 | 2339 | 1644 | 679 | 0 | 1 | 0 | 7713 | 7713 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 6060 | 0 | 0 | 0 | 1 | 0 | 0 | 7713 | 6060 | 0 | 0 | 1650 | 3 | 0 | 0 | 6968 | 6060 | 906 | 2 | 6968 | 6968 | 0 | 8 | 0 | 1482 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 195 |
| `rv64ud-v-recoding` | v- | 1/18 | default | 21004 | 7439 | 165 | 4 | 463 | 4477 | 2078 | 1286 | 777 | 0 | 0 | 0 | 7439 | 7439 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1139 | 971 | 0 | 0 | 5335 | 0 | 0 | 0 | 63 | 0 | 0 | 7439 | 5335 | 0 | 0 | 2101 | 3 | 0 | 0 | 6590 | 5335 | 1253 | 2 | 6590 | 6590 | 0 | 8 | 0 | 852 | 0 | 0 | 2908 | 0 | 1987 | 0 | 0 | 0 | 227 |
| `rv64ud-v-structural` | v- | 2/18 | default | 12393 | 4893 | 148 | 1 | 355 | 4069 | 1537 | 978 | 544 | 0 | 0 | 0 | 4893 | 4893 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 885 | 738 | 0 | 0 | 3347 | 0 | 0 | 0 | 14 | 0 | 0 | 4893 | 3347 | 0 | 0 | 1543 | 3 | 0 | 0 | 4242 | 3347 | 893 | 2 | 4242 | 4242 | 0 | 8 | 0 | 346 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 158 |
| `rv64uf-v-fadd` | v- | 16/18 | default | 20514 | 7396 | 156 | 1 | 387 | 7350 | 2340 | 1655 | 670 | 0 | 0 | 0 | 7396 | 7396 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5541 | 0 | 0 | 0 | 70 | 0 | 0 | 7396 | 5541 | 0 | 0 | 1852 | 3 | 0 | 0 | 6661 | 5541 | 1118 | 2 | 6661 | 6661 | 0 | 8 | 0 | 567 | 0 | 0 | 3395 | 0 | 1433 | 0 | 0 | 0 | 200 |
| `rv64uf-v-fclass` | v- | 17/18 | default | 11934 | 4465 | 149 | 1 | 268 | 4058 | 1455 | 957 | 483 | 0 | 0 | 0 | 4465 | 4465 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3250 | 0 | 0 | 0 | 29 | 0 | 0 | 4465 | 3250 | 0 | 0 | 1212 | 3 | 0 | 0 | 3964 | 3250 | 712 | 2 | 3964 | 3964 | 0 | 8 | 0 | 460 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 133 |
| `rv64uf-v-fcmp` | v- | 18/18 | default | 20681 | 7599 | 153 | 1 | 384 | 7344 | 2336 | 1660 | 661 | 0 | 0 | 0 | 7599 | 7599 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5760 | 0 | 0 | 0 | 56 | 0 | 0 | 7599 | 5760 | 0 | 0 | 1836 | 3 | 0 | 0 | 6867 | 5760 | 1105 | 2 | 6867 | 6867 | 0 | 8 | 0 | 454 | 0 | 0 | 3415 | 0 | 1433 | 0 | 0 | 0 | 205 |
| `rv64uf-v-fcvt` | v- | 1/18 | default | 20134 | 6993 | 152 | 1 | 378 | 7339 | 2320 | 1653 | 652 | 0 | 0 | 0 | 6993 | 6993 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5192 | 0 | 0 | 0 | 0 | 0 | 0 | 6993 | 5192 | 0 | 0 | 1798 | 3 | 0 | 0 | 6282 | 5192 | 1088 | 2 | 6282 | 6282 | 0 | 8 | 0 | 608 | 0 | 0 | 3363 | 0 | 1433 | 0 | 0 | 0 | 198 |
| `rv64uf-v-fcvt_w` | v- | 2/18 | default | 29605 | 10992 | 160 | 1 | 494 | 10607 | 3200 | 2362 | 823 | 0 | 0 | 0 | 10992 | 10992 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 2157 | 2007 | 0 | 0 | 8582 | 0 | 0 | 0 | 8 | 0 | 0 | 10992 | 8582 | 0 | 0 | 2407 | 3 | 0 | 0 | 10035 | 8582 | 1451 | 2 | 10035 | 10035 | 0 | 8 | 0 | 824 | 0 | 0 | 5116 | 0 | 2044 | 0 | 0 | 0 | 282 |
| `rv64uf-v-fdiv` | v- | 3/18 | default | 20355 | 7226 | 156 | 1 | 389 | 7344 | 2337 | 1651 | 670 | 0 | 1 | 0 | 7226 | 7226 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 5375 | 0 | 0 | 0 | 67 | 0 | 0 | 7226 | 5375 | 0 | 0 | 1848 | 3 | 0 | 0 | 6488 | 5375 | 1111 | 2 | 6488 | 6488 | 0 | 8 | 0 | 616 | 0 | 0 | 3383 | 0 | 1433 | 0 | 0 | 0 | 200 |
| `rv64uf-v-fmadd` | v- | 4/18 | default | 20677 | 7561 | 156 | 1 | 393 | 7344 | 2346 | 1656 | 674 | 0 | 1 | 0 | 7561 | 7561 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 5682 | 0 | 0 | 0 | 51 | 0 | 0 | 7561 | 5682 | 0 | 0 | 1876 | 3 | 0 | 0 | 6815 | 5682 | 1131 | 2 | 6815 | 6815 | 0 | 8 | 0 | 521 | 0 | 0 | 3403 | 0 | 1433 | 0 | 0 | 0 | 205 |
| `rv64uf-v-fmin` | v- | 5/18 | default | 21000 | 7943 | 156 | 1 | 392 | 7344 | 2350 | 1662 | 672 | 0 | 1 | 0 | 7943 | 7943 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 6034 | 0 | 0 | 0 | 93 | 0 | 0 | 7943 | 6034 | 0 | 0 | 1906 | 3 | 0 | 0 | 7196 | 6034 | 1160 | 2 | 7196 | 7196 | 0 | 8 | 0 | 426 | 0 | 0 | 3427 | 0 | 1433 | 0 | 0 | 0 | 211 |
| `rv64uf-v-ldst` | v- | 6/18 | default | 21090 | 7527 | 165 | 4 | 467 | 4457 | 2069 | 1284 | 769 | 0 | 1 | 0 | 7527 | 7527 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1138 | 969 | 0 | 0 | 5331 | 0 | 0 | 0 | 91 | 0 | 0 | 7527 | 5331 | 0 | 0 | 2193 | 3 | 0 | 0 | 6679 | 5331 | 1346 | 2 | 6679 | 6679 | 0 | 8 | 0 | 812 | 0 | 0 | 2903 | 0 | 1988 | 0 | 0 | 0 | 232 |
| `rv64uf-v-move` | v- | 7/18 | default | 12369 | 4741 | 147 | 1 | 269 | 4041 | 1447 | 965 | 467 | 0 | 0 | 0 | 4741 | 4741 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3514 | 0 | 0 | 0 | 9 | 0 | 0 | 4741 | 3514 | 0 | 0 | 1224 | 3 | 0 | 0 | 4231 | 3514 | 715 | 2 | 4231 | 4231 | 0 | 8 | 0 | 599 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 141 |
| `rv64uf-v-recoding` | v- | 8/18 | default | 19980 | 6776 | 153 | 1 | 385 | 7339 | 2322 | 1644 | 662 | 0 | 1 | 0 | 6776 | 6776 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 4971 | 0 | 0 | 0 | 0 | 0 | 0 | 6776 | 4971 | 0 | 0 | 1802 | 3 | 0 | 0 | 6055 | 4971 | 1082 | 2 | 6055 | 6055 | 0 | 8 | 0 | 732 | 0 | 0 | 3357 | 0 | 1433 | 0 | 0 | 0 | 193 |
| `rv64ui-v-add` | v- | 1/18 | default | 13254 | 5218 | 150 | 1 | 284 | 4081 | 1486 | 986 | 485 | 0 | 0 | 0 | 5218 | 5218 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 3908 | 0 | 0 | 0 | 55 | 0 | 0 | 5218 | 3908 | 0 | 0 | 1307 | 3 | 0 | 0 | 4714 | 3908 | 804 | 2 | 4714 | 4714 | 0 | 8 | 0 | 984 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64ui-v-addi` | v- | 2/18 | default | 12395 | 4832 | 150 | 1 | 281 | 4067 | 1474 | 968 | 491 | 0 | 0 | 0 | 4832 | 4832 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 744 | 0 | 0 | 3539 | 0 | 0 | 0 | 45 | 0 | 0 | 4832 | 3539 | 0 | 0 | 1290 | 3 | 0 | 0 | 4321 | 3539 | 780 | 2 | 4321 | 4321 | 0 | 8 | 0 | 505 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 138 |
| `rv64ui-v-addiw` | v- | 3/18 | default | 12396 | 4838 | 150 | 1 | 283 | 4056 | 1463 | 967 | 481 | 0 | 0 | 0 | 4838 | 4838 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 882 | 743 | 0 | 0 | 3536 | 0 | 0 | 0 | 0 | 0 | 0 | 4838 | 3536 | 0 | 0 | 1299 | 3 | 0 | 0 | 4323 | 3536 | 785 | 2 | 4323 | 4323 | 0 | 8 | 0 | 500 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 139 |
| `rv64ui-v-addw` | v- | 4/18 | default | 13246 | 5220 | 150 | 1 | 284 | 4081 | 1486 | 986 | 485 | 0 | 0 | 0 | 5220 | 5220 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 3911 | 0 | 0 | 0 | 6 | 0 | 0 | 5220 | 3911 | 0 | 0 | 1306 | 3 | 0 | 0 | 4719 | 3911 | 806 | 2 | 4719 | 4719 | 0 | 8 | 0 | 951 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64ui-v-and` | v- | 7/18 | default | 13495 | 5337 | 150 | 1 | 287 | 4072 | 1480 | 986 | 479 | 0 | 0 | 0 | 5337 | 5337 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 4012 | 0 | 0 | 0 | 31 | 0 | 0 | 5337 | 4012 | 0 | 0 | 1322 | 3 | 0 | 0 | 4821 | 4012 | 807 | 2 | 4821 | 4821 | 0 | 8 | 0 | 1148 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64ui-v-andi` | v- | 8/18 | default | 12458 | 4882 | 150 | 1 | 284 | 4069 | 1479 | 968 | 496 | 0 | 0 | 0 | 4882 | 4882 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 744 | 0 | 0 | 3559 | 0 | 0 | 0 | 34 | 0 | 0 | 4882 | 3559 | 0 | 0 | 1320 | 3 | 0 | 0 | 4371 | 3559 | 810 | 2 | 4371 | 4371 | 0 | 8 | 0 | 497 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 139 |
| `rv64ui-v-auipc` | v- | 12/18 | default | 11815 | 4460 | 142 | 1 | 305 | 4051 | 1475 | 958 | 502 | 0 | 0 | 0 | 4460 | 4460 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3127 | 0 | 0 | 0 | 0 | 0 | 0 | 4460 | 3127 | 0 | 0 | 1330 | 3 | 0 | 0 | 3884 | 3127 | 755 | 2 | 3884 | 3884 | 0 | 8 | 0 | 313 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 132 |
| `rv64ui-v-beq` | v- | 13/18 | default | 12878 | 5288 | 147 | 2 | 306 | 4062 | 1485 | 991 | 479 | 0 | 0 | 0 | 5288 | 5288 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 907 | 747 | 0 | 0 | 3867 | 0 | 0 | 0 | 20 | 0 | 0 | 5288 | 3867 | 0 | 0 | 1418 | 3 | 0 | 0 | 4757 | 3867 | 888 | 2 | 4757 | 4757 | 0 | 8 | 0 | 450 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 158 |
| `rv64ui-v-bge` | v- | 14/18 | default | 13010 | 5524 | 147 | 2 | 313 | 4074 | 1497 | 1000 | 482 | 0 | 0 | 0 | 5524 | 5524 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 916 | 747 | 0 | 0 | 4073 | 0 | 0 | 0 | 43 | 0 | 0 | 5524 | 4073 | 0 | 0 | 1448 | 3 | 0 | 0 | 4985 | 4073 | 910 | 2 | 4985 | 4985 | 0 | 8 | 0 | 426 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 169 |
| `rv64ui-v-bgeu` | v- | 15/18 | default | 13286 | 5631 | 147 | 2 | 314 | 4088 | 1512 | 1002 | 495 | 0 | 0 | 0 | 5631 | 5631 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 918 | 749 | 0 | 0 | 4180 | 0 | 0 | 0 | 46 | 0 | 0 | 5631 | 4180 | 0 | 0 | 1448 | 3 | 0 | 0 | 5082 | 4180 | 900 | 2 | 5082 | 5082 | 0 | 8 | 0 | 507 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 166 |
| `rv64ui-v-blt` | v- | 16/18 | default | 12879 | 5291 | 147 | 2 | 304 | 4083 | 1500 | 993 | 492 | 0 | 0 | 0 | 5291 | 5291 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 909 | 749 | 0 | 0 | 3877 | 0 | 0 | 0 | 20 | 0 | 0 | 5291 | 3877 | 0 | 0 | 1411 | 3 | 0 | 0 | 4763 | 3877 | 884 | 2 | 4763 | 4763 | 0 | 8 | 0 | 450 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 157 |
| `rv64ui-v-bltu` | v- | 17/18 | default | 13137 | 5466 | 147 | 1 | 307 | 4064 | 1488 | 994 | 479 | 0 | 0 | 0 | 5466 | 5466 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 909 | 749 | 0 | 0 | 4032 | 0 | 0 | 0 | 0 | 0 | 0 | 5466 | 4032 | 0 | 0 | 1431 | 3 | 0 | 0 | 4936 | 4032 | 902 | 2 | 4936 | 4936 | 0 | 8 | 0 | 538 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 158 |
| `rv64ui-v-bne` | v- | 18/18 | default | 12887 | 5300 | 147 | 2 | 306 | 4085 | 1503 | 995 | 493 | 0 | 0 | 0 | 5300 | 5300 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 911 | 749 | 0 | 0 | 3882 | 0 | 0 | 0 | 20 | 0 | 0 | 5300 | 3882 | 0 | 0 | 1415 | 3 | 0 | 0 | 4774 | 3882 | 890 | 2 | 4774 | 4774 | 0 | 8 | 0 | 467 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 159 |
| `rv64ui-v-fence_i` | v- | 17/18 | default | 21858 | 7994 | 164 | 1 | 465 | 4911 | 2204 | 1388 | 800 | 0 | 1 | 0 | 7994 | 7994 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1237 | 1033 | 0 | 0 | 5739 | 0 | 0 | 0 | 98 | 0 | 0 | 7994 | 5739 | 0 | 0 | 2252 | 3 | 0 | 0 | 7135 | 5739 | 1394 | 2 | 7135 | 7135 | 0 | 8 | 0 | 778 | 0 | 0 | 2901 | 0 | 1990 | 0 | 0 | 0 | 228 |
| `rv64ui-v-jal` | v- | 1/18 | default | 11817 | 4455 | 148 | 1 | 305 | 4058 | 1485 | 958 | 512 | 0 | 0 | 0 | 4455 | 4455 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3127 | 0 | 0 | 0 | 25 | 0 | 0 | 4455 | 3127 | 0 | 0 | 1325 | 3 | 0 | 0 | 3882 | 3127 | 753 | 2 | 3882 | 3882 | 0 | 8 | 0 | 320 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 133 |
| `rv64ui-v-jalr` | v- | 2/18 | default | 12246 | 4735 | 150 | 4 | 316 | 4056 | 1490 | 970 | 505 | 0 | 0 | 0 | 4735 | 4735 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 740 | 0 | 0 | 3310 | 0 | 0 | 0 | 59 | 0 | 0 | 4735 | 3310 | 0 | 0 | 1422 | 3 | 0 | 0 | 4166 | 3310 | 854 | 2 | 4166 | 4166 | 0 | 8 | 0 | 388 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 152 |
| `rv64ui-v-lb` | v- | 3/18 | default | 20660 | 7430 | 158 | 1 | 409 | 7363 | 2362 | 1655 | 691 | 0 | 1 | 0 | 7430 | 7430 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1526 | 1378 | 0 | 0 | 5520 | 0 | 0 | 0 | 0 | 0 | 0 | 7430 | 5520 | 0 | 0 | 1907 | 3 | 0 | 0 | 6679 | 5520 | 1157 | 2 | 6679 | 6679 | 0 | 8 | 0 | 723 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 0 | 201 |
| `rv64ui-v-lbu` | v- | 4/18 | default | 20630 | 7400 | 158 | 1 | 404 | 7371 | 2359 | 1656 | 688 | 0 | 0 | 0 | 7400 | 7400 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1526 | 1379 | 0 | 0 | 5507 | 0 | 0 | 0 | 0 | 0 | 0 | 7400 | 5507 | 0 | 0 | 1890 | 3 | 0 | 0 | 6656 | 5507 | 1147 | 2 | 6656 | 6656 | 0 | 8 | 0 | 723 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 0 | 198 |
| `rv64ui-v-ld` | v- | 9/18 | default | 21104 | 7616 | 159 | 1 | 400 | 7366 | 2362 | 1657 | 690 | 0 | 0 | 0 | 7616 | 7616 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1527 | 1377 | 0 | 0 | 5790 | 0 | 0 | 0 | 0 | 0 | 0 | 7616 | 5790 | 0 | 0 | 1823 | 3 | 0 | 0 | 6868 | 5790 | 1076 | 2 | 6868 | 6868 | 0 | 8 | 0 | 1000 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 0 | 199 |
| `rv64ui-v-ld_st` | v- | 14/18 | default | 40031 | 13567 | 172 | 1 | 944 | 11042 | 4019 | 2710 | 1294 | 0 | 0 | 0 | 13567 | 13567 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 2474 | 2243 | 0 | 0 | 9195 | 0 | 0 | 0 | 68 | 0 | 0 | 13567 | 9195 | 0 | 0 | 4369 | 3 | 0 | 0 | 11862 | 9195 | 2665 | 2 | 11862 | 11862 | 0 | 8 | 0 | 2945 | 0 | 0 | 6422 | 0 | 3485 | 0 | 0 | 0 | 448 |
| `rv64ui-v-lh` | v- | 5/18 | default | 20683 | 7438 | 158 | 1 | 406 | 7370 | 2363 | 1656 | 692 | 0 | 0 | 0 | 7438 | 7438 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1526 | 1379 | 0 | 0 | 5533 | 0 | 0 | 0 | 44 | 0 | 0 | 7438 | 5533 | 0 | 0 | 1902 | 3 | 0 | 0 | 6683 | 5533 | 1148 | 2 | 6683 | 6683 | 0 | 8 | 0 | 722 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 0 | 198 |
| `rv64ui-v-lhu` | v- | 6/18 | default | 20748 | 7493 | 158 | 1 | 410 | 7366 | 2366 | 1655 | 695 | 0 | 1 | 0 | 7493 | 7493 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1526 | 1378 | 0 | 0 | 5580 | 0 | 0 | 0 | 44 | 0 | 0 | 7493 | 5580 | 0 | 0 | 1910 | 3 | 0 | 0 | 6733 | 5580 | 1151 | 2 | 6733 | 6733 | 0 | 8 | 0 | 731 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 0 | 201 |
| `rv64ui-v-lui` | v- | 11/18 | default | 11867 | 4413 | 149 | 1 | 269 | 4058 | 1455 | 956 | 484 | 0 | 0 | 0 | 4413 | 4413 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3174 | 0 | 0 | 0 | 8 | 0 | 0 | 4413 | 3174 | 0 | 0 | 1236 | 3 | 0 | 0 | 3910 | 3174 | 734 | 2 | 3910 | 3910 | 0 | 8 | 0 | 419 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 132 |
| `rv64ui-v-lw` | v- | 7/18 | default | 20664 | 7413 | 158 | 1 | 403 | 7369 | 2359 | 1656 | 688 | 0 | 0 | 0 | 7413 | 7413 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1526 | 1379 | 0 | 0 | 5544 | 0 | 0 | 0 | 0 | 0 | 0 | 7413 | 5544 | 0 | 0 | 1866 | 3 | 0 | 0 | 6669 | 5544 | 1123 | 2 | 6669 | 6669 | 0 | 8 | 0 | 744 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 0 | 197 |
| `rv64ui-v-lwu` | v- | 8/18 | default | 20784 | 7504 | 160 | 1 | 408 | 7366 | 2366 | 1655 | 695 | 0 | 1 | 0 | 7504 | 7504 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1526 | 1378 | 0 | 0 | 5629 | 0 | 0 | 0 | 57 | 0 | 0 | 7504 | 5629 | 0 | 0 | 1872 | 3 | 0 | 0 | 6754 | 5629 | 1123 | 2 | 6754 | 6754 | 0 | 8 | 0 | 774 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 0 | 200 |
| `rv64ui-v-ma_data` | v- | 18/18 | default | 43064 | 16038 | 168 | 1 | 1025 | 11059 | 4201 | 2851 | 1335 | 0 | 0 | 0 | 16038 | 16038 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 2505 | 2241 | 0 | 0 | 10857 | 0 | 0 | 0 | 79 | 0 | 0 | 16038 | 10857 | 0 | 0 | 5178 | 3 | 0 | 0 | 14074 | 10857 | 3215 | 2 | 14074 | 14074 | 0 | 8 | 0 | 3543 | 0 | 0 | 6327 | 0 | 3343 | 0 | 110 | 0 | 623 |
| `rv64ui-v-or` | v- | 9/18 | default | 13571 | 5336 | 151 | 1 | 287 | 4070 | 1481 | 986 | 480 | 0 | 0 | 0 | 5336 | 5336 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 4025 | 0 | 0 | 0 | 14 | 0 | 0 | 5336 | 4025 | 0 | 0 | 1308 | 3 | 0 | 0 | 4820 | 4025 | 793 | 2 | 4820 | 4820 | 0 | 8 | 0 | 1285 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64ui-v-ori` | v- | 10/18 | default | 12402 | 4848 | 150 | 1 | 287 | 4057 | 1469 | 967 | 487 | 0 | 0 | 0 | 4848 | 4848 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 882 | 742 | 0 | 0 | 3523 | 0 | 0 | 0 | 0 | 0 | 0 | 4848 | 3523 | 0 | 0 | 1322 | 3 | 0 | 0 | 4330 | 3523 | 805 | 2 | 4330 | 4330 | 0 | 8 | 0 | 498 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 140 |
| `rv64ui-v-sb` | v- | 10/18 | default | 22031 | 8580 | 161 | 1 | 637 | 4422 | 2204 | 1311 | 878 | 0 | 0 | 0 | 8580 | 8580 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1156 | 981 | 0 | 0 | 5903 | 0 | 0 | 0 | 59 | 0 | 0 | 8580 | 5903 | 0 | 0 | 2674 | 3 | 0 | 0 | 7380 | 5903 | 1475 | 2 | 7380 | 7380 | 0 | 8 | 0 | 510 | 0 | 0 | 2921 | 0 | 2021 | 0 | 1 | 0 | 245 |
| `rv64ui-v-sd` | v- | 13/18 | default | 30499 | 11447 | 176 | 1 | 822 | 7761 | 3171 | 1998 | 1158 | 0 | 0 | 0 | 11447 | 11447 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1798 | 1617 | 0 | 0 | 7989 | 0 | 0 | 0 | 4 | 0 | 0 | 11447 | 7989 | 0 | 0 | 3455 | 3 | 0 | 0 | 9879 | 7989 | 1888 | 2 | 9879 | 9879 | 0 | 8 | 0 | 795 | 0 | 0 | 4550 | 0 | 2631 | 0 | 1 | 0 | 302 |
| `rv64ui-v-sh` | v- | 11/18 | default | 22128 | 8575 | 161 | 1 | 639 | 4420 | 2206 | 1311 | 880 | 0 | 0 | 0 | 8575 | 8575 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1156 | 981 | 0 | 0 | 5890 | 0 | 0 | 0 | 41 | 0 | 0 | 8575 | 5890 | 0 | 0 | 2682 | 3 | 0 | 0 | 7374 | 5890 | 1482 | 2 | 7374 | 7374 | 0 | 8 | 0 | 679 | 0 | 0 | 2921 | 0 | 2021 | 0 | 1 | 0 | 245 |
| `rv64ui-v-simple` | v- | 16/18 | default | 11762 | 4306 | 149 | 1 | 263 | 4059 | 1447 | 955 | 477 | 0 | 0 | 0 | 4306 | 4306 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 870 | 738 | 0 | 0 | 3079 | 0 | 0 | 0 | 42 | 0 | 0 | 4306 | 3079 | 0 | 0 | 1224 | 3 | 0 | 0 | 3815 | 3079 | 734 | 2 | 3815 | 3815 | 0 | 8 | 0 | 445 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 130 |
| `rv64ui-v-sll` | v- | 17/18 | default | 21399 | 7625 | 158 | 1 | 401 | 7377 | 2362 | 1674 | 673 | 0 | 0 | 0 | 7625 | 7625 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1389 | 0 | 0 | 5795 | 0 | 0 | 0 | 0 | 0 | 0 | 7625 | 5795 | 0 | 0 | 1827 | 3 | 0 | 0 | 6889 | 5795 | 1092 | 2 | 6889 | 6889 | 0 | 8 | 0 | 1386 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 206 |
| `rv64ui-v-slli` | v- | 18/18 | default | 12449 | 4861 | 150 | 1 | 281 | 4068 | 1474 | 968 | 491 | 0 | 0 | 0 | 4861 | 4861 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 744 | 0 | 0 | 3566 | 0 | 0 | 0 | 30 | 0 | 0 | 4861 | 3566 | 0 | 0 | 1292 | 3 | 0 | 0 | 4350 | 3566 | 782 | 2 | 4350 | 4350 | 0 | 8 | 0 | 520 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 138 |
| `rv64ui-v-slliw` | v- | 1/18 | default | 12451 | 4861 | 150 | 1 | 281 | 4067 | 1474 | 968 | 491 | 0 | 0 | 0 | 4861 | 4861 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 744 | 0 | 0 | 3571 | 0 | 0 | 0 | 45 | 0 | 0 | 4861 | 3571 | 0 | 0 | 1287 | 3 | 0 | 0 | 4349 | 3571 | 776 | 2 | 4349 | 4349 | 0 | 8 | 0 | 529 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 138 |
| `rv64ui-v-sllw` | v- | 2/18 | default | 21394 | 7621 | 158 | 1 | 401 | 7378 | 2362 | 1674 | 673 | 0 | 0 | 0 | 7621 | 7621 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1389 | 0 | 0 | 5792 | 0 | 0 | 0 | 0 | 0 | 0 | 7621 | 5792 | 0 | 0 | 1826 | 3 | 0 | 0 | 6886 | 5792 | 1092 | 2 | 6886 | 6886 | 0 | 8 | 0 | 1384 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 206 |
| `rv64ui-v-slt` | v- | 13/18 | default | 13233 | 5230 | 150 | 1 | 286 | 4065 | 1473 | 983 | 475 | 0 | 0 | 0 | 5230 | 5230 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 898 | 750 | 0 | 0 | 3914 | 0 | 0 | 0 | 0 | 0 | 0 | 5230 | 3914 | 0 | 0 | 1313 | 3 | 0 | 0 | 4725 | 3914 | 809 | 2 | 4725 | 4725 | 0 | 8 | 0 | 931 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64ui-v-slti` | v- | 14/18 | default | 12385 | 4829 | 150 | 1 | 281 | 4069 | 1474 | 968 | 491 | 0 | 0 | 0 | 4829 | 4829 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 744 | 0 | 0 | 3535 | 0 | 0 | 0 | 45 | 0 | 0 | 4829 | 3535 | 0 | 0 | 1291 | 3 | 0 | 0 | 4319 | 3535 | 782 | 2 | 4319 | 4319 | 0 | 8 | 0 | 499 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 138 |
| `rv64ui-v-sltiu` | v- | 16/18 | default | 12384 | 4826 | 150 | 1 | 283 | 4056 | 1463 | 967 | 481 | 0 | 0 | 0 | 4826 | 4826 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 882 | 743 | 0 | 0 | 3525 | 0 | 0 | 0 | 45 | 0 | 0 | 4826 | 3525 | 0 | 0 | 1298 | 3 | 0 | 0 | 4313 | 3525 | 786 | 2 | 4313 | 4313 | 0 | 8 | 0 | 499 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 139 |
| `rv64ui-v-sltu` | v- | 15/18 | default | 13265 | 5208 | 150 | 1 | 286 | 4063 | 1472 | 982 | 475 | 0 | 0 | 0 | 5208 | 5208 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 897 | 749 | 0 | 0 | 3892 | 0 | 0 | 0 | 0 | 0 | 0 | 5208 | 3892 | 0 | 0 | 1313 | 3 | 0 | 0 | 4701 | 3892 | 807 | 2 | 4701 | 4701 | 0 | 8 | 0 | 1020 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64ui-v-sra` | v- | 7/18 | default | 13332 | 5162 | 150 | 1 | 284 | 4080 | 1486 | 986 | 485 | 0 | 0 | 0 | 5162 | 5162 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 3859 | 0 | 0 | 0 | 14 | 0 | 0 | 5162 | 3859 | 0 | 0 | 1300 | 3 | 0 | 0 | 4652 | 3859 | 791 | 2 | 4652 | 4652 | 0 | 8 | 0 | 1194 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64ui-v-srai` | v- | 8/18 | default | 12444 | 4858 | 150 | 1 | 283 | 4066 | 1476 | 968 | 493 | 0 | 0 | 0 | 4858 | 4858 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 744 | 0 | 0 | 3557 | 0 | 0 | 0 | 14 | 0 | 0 | 4858 | 3557 | 0 | 0 | 1298 | 3 | 0 | 0 | 4345 | 3557 | 786 | 2 | 4345 | 4345 | 0 | 8 | 0 | 516 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 139 |
| `rv64ui-v-sraiw` | v- | 9/18 | default | 12548 | 4897 | 150 | 1 | 283 | 4054 | 1462 | 966 | 481 | 0 | 0 | 0 | 4897 | 4897 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 881 | 740 | 0 | 0 | 3597 | 0 | 0 | 0 | 30 | 0 | 0 | 4897 | 3597 | 0 | 0 | 1297 | 3 | 0 | 0 | 4385 | 3597 | 786 | 2 | 4385 | 4385 | 0 | 8 | 0 | 576 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 139 |
| `rv64ui-v-sraw` | v- | 10/18 | default | 21379 | 7610 | 158 | 1 | 401 | 7377 | 2362 | 1674 | 673 | 0 | 0 | 0 | 7610 | 7610 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1389 | 0 | 0 | 5782 | 0 | 0 | 0 | 26 | 0 | 0 | 7610 | 5782 | 0 | 0 | 1825 | 3 | 0 | 0 | 6874 | 5782 | 1090 | 2 | 6874 | 6874 | 0 | 8 | 0 | 1360 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 206 |
| `rv64ui-v-srl` | v- | 3/18 | default | 21462 | 7676 | 158 | 1 | 403 | 7381 | 2367 | 1674 | 678 | 0 | 0 | 0 | 7676 | 7676 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1389 | 0 | 0 | 5835 | 0 | 0 | 0 | 0 | 0 | 0 | 7676 | 5835 | 0 | 0 | 1838 | 3 | 0 | 0 | 6934 | 5835 | 1097 | 2 | 6934 | 6934 | 0 | 8 | 0 | 1397 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 206 |
| `rv64ui-v-srli` | v- | 4/18 | default | 12513 | 4905 | 150 | 1 | 287 | 4059 | 1469 | 967 | 487 | 0 | 0 | 0 | 4905 | 4905 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 882 | 742 | 0 | 0 | 3590 | 0 | 0 | 0 | 30 | 0 | 0 | 4905 | 3590 | 0 | 0 | 1312 | 3 | 0 | 0 | 4384 | 3590 | 792 | 2 | 4384 | 4384 | 0 | 8 | 0 | 534 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 140 |
| `rv64ui-v-srliw` | v- | 5/18 | default | 12478 | 4875 | 150 | 1 | 283 | 4056 | 1463 | 967 | 481 | 0 | 0 | 0 | 4875 | 4875 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 882 | 743 | 0 | 0 | 3574 | 0 | 0 | 0 | 45 | 0 | 0 | 4875 | 3574 | 0 | 0 | 1298 | 3 | 0 | 0 | 4362 | 3574 | 786 | 2 | 4362 | 4362 | 0 | 8 | 0 | 543 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 139 |
| `rv64ui-v-srlw` | v- | 6/18 | default | 21424 | 7646 | 158 | 1 | 406 | 7370 | 2363 | 1671 | 676 | 0 | 1 | 0 | 7646 | 7646 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1542 | 1385 | 0 | 0 | 5799 | 0 | 0 | 0 | 10 | 0 | 0 | 7646 | 5799 | 0 | 0 | 1844 | 3 | 0 | 0 | 6903 | 5799 | 1102 | 2 | 6903 | 6903 | 0 | 8 | 0 | 1385 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 209 |
| `rv64ui-v-st_ld` | v- | 15/18 | default | 30003 | 11048 | 169 | 1 | 550 | 7709 | 2877 | 1965 | 897 | 0 | 0 | 0 | 11048 | 11048 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1774 | 1607 | 0 | 0 | 8643 | 0 | 0 | 0 | 30 | 0 | 0 | 11048 | 8643 | 0 | 0 | 2402 | 3 | 0 | 0 | 9975 | 8643 | 1330 | 2 | 9975 | 9975 | 0 | 8 | 0 | 863 | 0 | 0 | 4586 | 0 | 2667 | 0 | 0 | 0 | 275 |
| `rv64ui-v-sub` | v- | 5/18 | default | 13239 | 5225 | 150 | 1 | 286 | 4067 | 1474 | 984 | 475 | 0 | 0 | 0 | 5225 | 5225 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 899 | 751 | 0 | 0 | 3909 | 0 | 0 | 0 | 72 | 0 | 0 | 5225 | 3909 | 0 | 0 | 1313 | 3 | 0 | 0 | 4721 | 3909 | 810 | 2 | 4721 | 4721 | 0 | 8 | 0 | 942 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64ui-v-subw` | v- | 6/18 | default | 13231 | 5227 | 150 | 1 | 286 | 4067 | 1474 | 984 | 475 | 0 | 0 | 0 | 5227 | 5227 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 899 | 750 | 0 | 0 | 3910 | 0 | 0 | 0 | 6 | 0 | 0 | 5227 | 3910 | 0 | 0 | 1314 | 3 | 0 | 0 | 4721 | 3910 | 809 | 2 | 4721 | 4721 | 0 | 8 | 0 | 910 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64ui-v-sw` | v- | 12/18 | default | 22165 | 8618 | 163 | 1 | 644 | 4422 | 2213 | 1311 | 887 | 0 | 0 | 0 | 8618 | 8618 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1156 | 981 | 0 | 0 | 5913 | 0 | 0 | 0 | 0 | 0 | 0 | 8618 | 5913 | 0 | 0 | 2702 | 3 | 0 | 0 | 7401 | 5913 | 1486 | 2 | 7401 | 7401 | 0 | 8 | 0 | 681 | 0 | 0 | 2921 | 0 | 2020 | 0 | 1 | 0 | 246 |
| `rv64ui-v-xor` | v- | 11/18 | default | 13571 | 5351 | 151 | 1 | 285 | 4082 | 1491 | 986 | 490 | 0 | 0 | 0 | 5351 | 5351 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 4044 | 0 | 0 | 0 | 0 | 0 | 0 | 5351 | 4044 | 0 | 0 | 1304 | 3 | 0 | 0 | 4838 | 4044 | 792 | 2 | 4838 | 4838 | 0 | 8 | 0 | 1280 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64ui-v-xori` | v- | 12/18 | default | 12407 | 4846 | 151 | 1 | 285 | 4074 | 1482 | 968 | 499 | 0 | 0 | 0 | 4846 | 4846 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 744 | 0 | 0 | 3531 | 0 | 0 | 0 | 14 | 0 | 0 | 4846 | 3531 | 0 | 0 | 1312 | 3 | 0 | 0 | 4332 | 3531 | 799 | 2 | 4332 | 4332 | 0 | 8 | 0 | 507 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 139 |
| `rv64um-v-div` | v- | 5/18 | default | 11974 | 4495 | 150 | 1 | 271 | 4060 | 1458 | 956 | 487 | 0 | 0 | 0 | 4495 | 4495 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3271 | 0 | 0 | 0 | 32 | 0 | 0 | 4495 | 3271 | 0 | 0 | 1221 | 3 | 0 | 0 | 3992 | 3271 | 719 | 2 | 3992 | 3992 | 0 | 8 | 0 | 459 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 133 |
| `rv64um-v-divu` | v- | 6/18 | default | 12007 | 4527 | 150 | 1 | 275 | 4051 | 1452 | 956 | 481 | 0 | 0 | 0 | 4527 | 4527 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3287 | 0 | 0 | 0 | 0 | 0 | 0 | 4527 | 3287 | 0 | 0 | 1237 | 3 | 0 | 0 | 4016 | 3287 | 727 | 2 | 4016 | 4016 | 0 | 8 | 0 | 457 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 134 |
| `rv64um-v-divuw` | v- | 11/18 | default | 11987 | 4515 | 150 | 1 | 275 | 4051 | 1453 | 956 | 482 | 0 | 0 | 0 | 4515 | 4515 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3276 | 0 | 0 | 0 | 0 | 0 | 0 | 4515 | 3276 | 0 | 0 | 1236 | 3 | 0 | 0 | 4005 | 3276 | 727 | 2 | 4005 | 4005 | 0 | 8 | 0 | 449 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 134 |
| `rv64um-v-divw` | v- | 10/18 | default | 11953 | 4479 | 150 | 1 | 273 | 4048 | 1448 | 956 | 477 | 0 | 0 | 0 | 4479 | 4479 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3248 | 0 | 0 | 0 | 34 | 0 | 0 | 4479 | 3248 | 0 | 0 | 1228 | 3 | 0 | 0 | 3974 | 3248 | 724 | 2 | 3974 | 3974 | 0 | 8 | 0 | 453 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 134 |
| `rv64um-v-mul` | v- | 1/18 | default | 13354 | 5334 | 151 | 1 | 288 | 4068 | 1477 | 982 | 480 | 0 | 0 | 0 | 5334 | 5334 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 897 | 749 | 0 | 0 | 4010 | 0 | 0 | 0 | 0 | 0 | 0 | 5334 | 4010 | 0 | 0 | 1321 | 3 | 0 | 0 | 4826 | 4010 | 814 | 2 | 4826 | 4826 | 0 | 8 | 0 | 947 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64um-v-mulh` | v- | 2/18 | default | 13277 | 5285 | 150 | 1 | 286 | 4070 | 1476 | 986 | 475 | 0 | 0 | 0 | 5285 | 5285 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 3968 | 0 | 0 | 0 | 71 | 0 | 0 | 5285 | 3968 | 0 | 0 | 1314 | 3 | 0 | 0 | 4779 | 3968 | 809 | 2 | 4779 | 4779 | 0 | 8 | 0 | 871 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64um-v-mulhsu` | v- | 3/18 | default | 13277 | 5285 | 150 | 1 | 286 | 4070 | 1476 | 986 | 475 | 0 | 0 | 0 | 5285 | 5285 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 3968 | 0 | 0 | 0 | 71 | 0 | 0 | 5285 | 3968 | 0 | 0 | 1314 | 3 | 0 | 0 | 4779 | 3968 | 809 | 2 | 4779 | 4779 | 0 | 8 | 0 | 871 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64um-v-mulhu` | v- | 4/18 | default | 13337 | 5252 | 150 | 1 | 286 | 4070 | 1476 | 986 | 475 | 0 | 0 | 0 | 5252 | 5252 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 3935 | 0 | 0 | 0 | 55 | 0 | 0 | 5252 | 3935 | 0 | 0 | 1314 | 3 | 0 | 0 | 4745 | 3935 | 808 | 2 | 4745 | 4745 | 0 | 8 | 0 | 1031 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64um-v-mulw` | v- | 9/18 | default | 13131 | 5435 | 150 | 1 | 303 | 4065 | 1490 | 983 | 492 | 0 | 0 | 0 | 5435 | 5435 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 898 | 750 | 0 | 0 | 3989 | 0 | 0 | 0 | 48 | 0 | 0 | 5435 | 3989 | 0 | 0 | 1443 | 3 | 0 | 0 | 4912 | 3989 | 921 | 2 | 4912 | 4912 | 0 | 8 | 0 | 549 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64um-v-rem` | v- | 7/18 | default | 11952 | 4483 | 150 | 1 | 271 | 4061 | 1458 | 956 | 487 | 0 | 0 | 0 | 4483 | 4483 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3259 | 0 | 0 | 0 | 0 | 0 | 0 | 4483 | 3259 | 0 | 0 | 1221 | 3 | 0 | 0 | 3981 | 3259 | 720 | 2 | 3981 | 3981 | 0 | 8 | 0 | 451 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 133 |
| `rv64um-v-remu` | v- | 8/18 | default | 11957 | 4481 | 150 | 1 | 273 | 4048 | 1448 | 956 | 477 | 0 | 0 | 0 | 4481 | 4481 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3250 | 0 | 0 | 0 | 34 | 0 | 0 | 4481 | 3250 | 0 | 0 | 1228 | 3 | 0 | 0 | 3976 | 3250 | 724 | 2 | 3976 | 3976 | 0 | 8 | 0 | 453 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 134 |
| `rv64um-v-remuw` | v- | 13/18 | default | 11943 | 4471 | 150 | 1 | 273 | 4048 | 1448 | 956 | 477 | 0 | 0 | 0 | 4471 | 4471 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3238 | 0 | 0 | 0 | 25 | 0 | 0 | 4471 | 3238 | 0 | 0 | 1230 | 3 | 0 | 0 | 3965 | 3238 | 725 | 2 | 3965 | 3965 | 0 | 8 | 0 | 443 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 134 |
| `rv64um-v-remw` | v- | 12/18 | default | 11954 | 4482 | 150 | 1 | 271 | 4060 | 1458 | 956 | 487 | 0 | 0 | 0 | 4482 | 4482 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3258 | 0 | 0 | 0 | 34 | 0 | 0 | 4482 | 3258 | 0 | 0 | 1221 | 3 | 0 | 0 | 3980 | 3258 | 720 | 2 | 3980 | 3980 | 0 | 8 | 0 | 453 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 133 |
| `rv64uzba-v-add_uw` | v- | 3/18 | default | 13299 | 5413 | 65 | 1 | 292 | 4071 | 1477 | 983 | 480 | 0 | 0 | 0 | 5413 | 5413 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 898 | 756 | 0 | 0 | 4085 | 0 | 0 | 0 | 0 | 0 | 0 | 5413 | 4085 | 0 | 0 | 1325 | 3 | 0 | 0 | 4898 | 4085 | 811 | 2 | 4898 | 4898 | 0 | 8 | 0 | 981 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64uzba-v-sh1add` | v- | 4/18 | default | 13303 | 5407 | 65 | 1 | 292 | 4073 | 1478 | 984 | 480 | 0 | 0 | 0 | 5407 | 5407 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 899 | 757 | 0 | 0 | 4079 | 0 | 0 | 0 | 55 | 0 | 0 | 5407 | 4079 | 0 | 0 | 1325 | 3 | 0 | 0 | 4890 | 4079 | 809 | 2 | 4890 | 4890 | 0 | 8 | 0 | 991 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64uzba-v-sh1add_uw` | v- | 5/18 | default | 13312 | 5403 | 65 | 1 | 290 | 4087 | 1487 | 986 | 487 | 0 | 0 | 0 | 5403 | 5403 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 759 | 0 | 0 | 4081 | 0 | 0 | 0 | 6 | 0 | 0 | 5403 | 4081 | 0 | 0 | 1319 | 3 | 0 | 0 | 4889 | 4081 | 806 | 2 | 4889 | 4889 | 0 | 8 | 0 | 1024 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzba-v-sh2add` | v- | 6/18 | default | 13304 | 5410 | 65 | 1 | 290 | 4086 | 1487 | 986 | 487 | 0 | 0 | 0 | 5410 | 5410 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 759 | 0 | 0 | 4089 | 0 | 0 | 0 | 55 | 0 | 0 | 5410 | 4089 | 0 | 0 | 1318 | 3 | 0 | 0 | 4896 | 4089 | 805 | 2 | 4896 | 4896 | 0 | 8 | 0 | 991 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzba-v-sh2add_uw` | v- | 7/18 | default | 13311 | 5400 | 65 | 1 | 292 | 4073 | 1478 | 984 | 480 | 0 | 0 | 0 | 5400 | 5400 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 899 | 757 | 0 | 0 | 4071 | 0 | 0 | 0 | 6 | 0 | 0 | 5400 | 4071 | 0 | 0 | 1326 | 3 | 0 | 0 | 4883 | 4071 | 810 | 2 | 4883 | 4883 | 0 | 8 | 0 | 1024 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64uzba-v-sh3add` | v- | 8/18 | default | 13304 | 5410 | 65 | 1 | 290 | 4086 | 1487 | 986 | 487 | 0 | 0 | 0 | 5410 | 5410 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 759 | 0 | 0 | 4089 | 0 | 0 | 0 | 55 | 0 | 0 | 5410 | 4089 | 0 | 0 | 1318 | 3 | 0 | 0 | 4896 | 4089 | 805 | 2 | 4896 | 4896 | 0 | 8 | 0 | 991 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzba-v-sh3add_uw` | v- | 9/18 | default | 13311 | 5400 | 65 | 1 | 292 | 4073 | 1478 | 984 | 480 | 0 | 0 | 0 | 5400 | 5400 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 899 | 757 | 0 | 0 | 4071 | 0 | 0 | 0 | 6 | 0 | 0 | 5400 | 4071 | 0 | 0 | 1326 | 3 | 0 | 0 | 4883 | 4071 | 810 | 2 | 4883 | 4883 | 0 | 8 | 0 | 1024 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64uzba-v-slli_uw` | v- | 10/18 | default | 12502 | 5055 | 65 | 1 | 290 | 4062 | 1468 | 967 | 487 | 0 | 0 | 0 | 5055 | 5055 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 882 | 748 | 0 | 0 | 3738 | 0 | 0 | 0 | 0 | 0 | 0 | 5055 | 3738 | 0 | 0 | 1314 | 3 | 0 | 0 | 4530 | 3738 | 790 | 2 | 4530 | 4530 | 0 | 8 | 0 | 537 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 139 |
| `rv64uzbb-v-andn` | v- | 11/18 | default | 13589 | 5394 | 150 | 1 | 293 | 3772 | 1484 | 986 | 483 | 0 | 0 | 0 | 5394 | 5394 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 754 | 0 | 0 | 4061 | 0 | 0 | 0 | 0 | 0 | 0 | 5394 | 4061 | 0 | 0 | 1330 | 3 | 0 | 0 | 4868 | 4061 | 805 | 2 | 4868 | 4868 | 0 | 8 | 0 | 1318 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 150 |
| `rv64uzbb-v-clz` | v- | 12/18 | default | 12324 | 4805 | 150 | 1 | 281 | 3752 | 1457 | 961 | 481 | 0 | 0 | 0 | 4805 | 4805 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 876 | 740 | 0 | 0 | 3539 | 0 | 0 | 0 | 11 | 0 | 0 | 4805 | 3539 | 0 | 0 | 1263 | 3 | 0 | 0 | 4290 | 3539 | 749 | 2 | 4290 | 4290 | 0 | 8 | 0 | 555 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 136 |
| `rv64uzbb-v-clzw` | v- | 13/18 | default | 12296 | 4796 | 150 | 1 | 280 | 3752 | 1456 | 961 | 480 | 0 | 0 | 0 | 4796 | 4796 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 876 | 740 | 0 | 0 | 3532 | 0 | 0 | 0 | 36 | 0 | 0 | 4796 | 3532 | 0 | 0 | 1261 | 3 | 0 | 0 | 4283 | 3532 | 749 | 2 | 4283 | 4283 | 0 | 8 | 0 | 532 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 136 |
| `rv64uzbb-v-cpop` | v- | 14/18 | default | 12324 | 4805 | 150 | 1 | 281 | 3752 | 1457 | 961 | 481 | 0 | 0 | 0 | 4805 | 4805 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 876 | 740 | 0 | 0 | 3539 | 0 | 0 | 0 | 11 | 0 | 0 | 4805 | 3539 | 0 | 0 | 1263 | 3 | 0 | 0 | 4290 | 3539 | 749 | 2 | 4290 | 4290 | 0 | 8 | 0 | 555 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 136 |
| `rv64uzbb-v-cpopw` | v- | 15/18 | default | 12296 | 4796 | 150 | 1 | 280 | 3752 | 1456 | 961 | 480 | 0 | 0 | 0 | 4796 | 4796 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 876 | 740 | 0 | 0 | 3532 | 0 | 0 | 0 | 36 | 0 | 0 | 4796 | 3532 | 0 | 0 | 1261 | 3 | 0 | 0 | 4283 | 3532 | 749 | 2 | 4283 | 4283 | 0 | 8 | 0 | 532 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 136 |
| `rv64uzbb-v-ctz` | v- | 16/18 | default | 12325 | 4808 | 150 | 1 | 279 | 3766 | 1468 | 962 | 491 | 0 | 0 | 0 | 4808 | 4808 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 877 | 741 | 0 | 0 | 3549 | 0 | 0 | 0 | 11 | 0 | 0 | 4808 | 3549 | 0 | 0 | 1256 | 3 | 0 | 0 | 4296 | 3549 | 745 | 2 | 4296 | 4296 | 0 | 8 | 0 | 555 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 135 |
| `rv64uzbb-v-ctzw` | v- | 17/18 | default | 12295 | 4797 | 150 | 1 | 278 | 3765 | 1467 | 962 | 490 | 0 | 0 | 0 | 4797 | 4797 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 877 | 741 | 0 | 0 | 3540 | 0 | 0 | 0 | 36 | 0 | 0 | 4797 | 3540 | 0 | 0 | 1254 | 3 | 0 | 0 | 4287 | 3540 | 745 | 2 | 4287 | 4287 | 0 | 8 | 0 | 534 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 135 |
| `rv64uzbb-v-max` | v- | 18/18 | default | 13268 | 5313 | 150 | 1 | 287 | 3780 | 1488 | 986 | 487 | 0 | 0 | 0 | 5313 | 5313 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 3997 | 0 | 0 | 0 | 48 | 0 | 0 | 5313 | 3997 | 0 | 0 | 1313 | 3 | 0 | 0 | 4806 | 3997 | 807 | 2 | 4806 | 4806 | 0 | 8 | 0 | 947 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzbb-v-maxu` | v- | 1/18 | default | 13327 | 5280 | 150 | 1 | 289 | 3768 | 1476 | 984 | 477 | 0 | 0 | 0 | 5280 | 5280 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 899 | 751 | 0 | 0 | 3957 | 0 | 0 | 0 | 38 | 0 | 0 | 5280 | 3957 | 0 | 0 | 1320 | 3 | 0 | 0 | 4765 | 3957 | 806 | 2 | 4765 | 4765 | 0 | 8 | 0 | 1112 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64uzbb-v-min` | v- | 2/18 | default | 13260 | 5321 | 150 | 1 | 287 | 3781 | 1488 | 986 | 487 | 0 | 0 | 0 | 5321 | 5321 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 4005 | 0 | 0 | 0 | 0 | 0 | 0 | 5321 | 4005 | 0 | 0 | 1313 | 3 | 0 | 0 | 4814 | 4005 | 807 | 2 | 4814 | 4814 | 0 | 8 | 0 | 937 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzbb-v-minu` | v- | 3/18 | default | 13304 | 5294 | 150 | 1 | 287 | 3783 | 1488 | 986 | 487 | 0 | 0 | 0 | 5294 | 5294 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 3977 | 0 | 0 | 0 | 6 | 0 | 0 | 5294 | 3977 | 0 | 0 | 1314 | 3 | 0 | 0 | 4785 | 3977 | 806 | 2 | 4785 | 4785 | 0 | 8 | 0 | 1060 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzbb-v-orc_b` | v- | 4/18 | default | 12373 | 4839 | 150 | 1 | 279 | 3765 | 1469 | 962 | 492 | 0 | 0 | 0 | 4839 | 4839 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 877 | 741 | 0 | 0 | 3581 | 0 | 0 | 0 | 11 | 0 | 0 | 4839 | 3581 | 0 | 0 | 1255 | 3 | 0 | 0 | 4325 | 3581 | 742 | 2 | 4325 | 4325 | 0 | 8 | 0 | 567 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 135 |
| `rv64uzbb-v-orn` | v- | 5/18 | default | 21634 | 7880 | 158 | 1 | 411 | 7074 | 2370 | 1672 | 682 | 0 | 1 | 0 | 7880 | 7880 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1543 | 1387 | 0 | 0 | 6016 | 0 | 0 | 0 | 35 | 0 | 0 | 7880 | 6016 | 0 | 0 | 1861 | 3 | 0 | 0 | 7119 | 6016 | 1101 | 2 | 7119 | 7119 | 0 | 8 | 0 | 1433 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 209 |
| `rv64uzbb-v-rev8` | v- | 6/18 | default | 12420 | 4872 | 150 | 1 | 280 | 3765 | 1470 | 962 | 493 | 0 | 0 | 0 | 4872 | 4872 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 877 | 741 | 0 | 0 | 3613 | 0 | 0 | 0 | 0 | 0 | 0 | 4872 | 3613 | 0 | 0 | 1256 | 3 | 0 | 0 | 4357 | 3613 | 742 | 2 | 4357 | 4357 | 0 | 8 | 0 | 578 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 136 |
| `rv64uzbb-v-rol` | v- | 7/18 | default | 21444 | 7722 | 158 | 1 | 406 | 7081 | 2364 | 1674 | 675 | 0 | 0 | 0 | 7722 | 7722 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1389 | 0 | 0 | 5886 | 0 | 0 | 0 | 10 | 0 | 0 | 7722 | 5886 | 0 | 0 | 1833 | 3 | 0 | 0 | 6980 | 5886 | 1092 | 2 | 6980 | 6980 | 0 | 8 | 0 | 1378 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 206 |
| `rv64uzbb-v-rolw` | v- | 8/18 | default | 21466 | 7747 | 158 | 1 | 411 | 7072 | 2364 | 1670 | 678 | 0 | 1 | 0 | 7747 | 7747 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1541 | 1385 | 0 | 0 | 5894 | 0 | 0 | 0 | 26 | 0 | 0 | 7747 | 5894 | 0 | 0 | 1850 | 3 | 0 | 0 | 6998 | 5894 | 1102 | 2 | 6998 | 6998 | 0 | 8 | 0 | 1378 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 209 |
| `rv64uzbb-v-ror` | v- | 9/18 | default | 21566 | 7859 | 158 | 1 | 415 | 7095 | 2394 | 1669 | 709 | 0 | 1 | 0 | 7859 | 7859 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1540 | 1383 | 0 | 0 | 5993 | 0 | 0 | 0 | 0 | 0 | 0 | 7859 | 5993 | 0 | 0 | 1863 | 3 | 0 | 0 | 7108 | 5993 | 1113 | 2 | 7108 | 7108 | 0 | 8 | 0 | 1361 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 210 |
| `rv64uzbb-v-rori` | v- | 10/18 | default | 12517 | 4974 | 150 | 1 | 288 | 3755 | 1466 | 966 | 485 | 0 | 0 | 0 | 4974 | 4974 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 881 | 741 | 0 | 0 | 3664 | 0 | 0 | 0 | 44 | 0 | 0 | 4974 | 3664 | 0 | 0 | 1307 | 3 | 0 | 0 | 4452 | 3664 | 786 | 2 | 4452 | 4452 | 0 | 8 | 0 | 550 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 140 |
| `rv64uzbb-v-roriw` | v- | 11/18 | default | 12423 | 4933 | 150 | 1 | 285 | 3771 | 1478 | 968 | 495 | 0 | 0 | 0 | 4933 | 4933 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 744 | 0 | 0 | 3630 | 0 | 0 | 0 | 0 | 0 | 0 | 4933 | 3630 | 0 | 0 | 1300 | 3 | 0 | 0 | 4414 | 3630 | 782 | 2 | 4414 | 4414 | 0 | 8 | 0 | 499 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 138 |
| `rv64uzbb-v-rorw` | v- | 12/18 | default | 13391 | 5324 | 150 | 1 | 290 | 3796 | 1505 | 983 | 507 | 0 | 0 | 0 | 5324 | 5324 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 898 | 749 | 0 | 0 | 4001 | 0 | 0 | 0 | 31 | 0 | 0 | 5324 | 4001 | 0 | 0 | 1320 | 3 | 0 | 0 | 4805 | 4001 | 802 | 2 | 4805 | 4805 | 0 | 8 | 0 | 1140 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 150 |
| `rv64uzbb-v-sext_b` | v- | 13/18 | default | 12324 | 4805 | 150 | 1 | 281 | 3752 | 1457 | 961 | 481 | 0 | 0 | 0 | 4805 | 4805 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 876 | 740 | 0 | 0 | 3539 | 0 | 0 | 0 | 11 | 0 | 0 | 4805 | 3539 | 0 | 0 | 1263 | 3 | 0 | 0 | 4290 | 3539 | 749 | 2 | 4290 | 4290 | 0 | 8 | 0 | 555 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 136 |
| `rv64uzbb-v-sext_h` | v- | 14/18 | default | 12334 | 4818 | 150 | 1 | 281 | 3753 | 1459 | 962 | 482 | 0 | 0 | 0 | 4818 | 4818 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 877 | 741 | 0 | 0 | 3551 | 0 | 0 | 0 | 36 | 0 | 0 | 4818 | 3551 | 0 | 0 | 1264 | 3 | 0 | 0 | 4301 | 3551 | 748 | 2 | 4301 | 4301 | 0 | 8 | 0 | 549 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 136 |
| `rv64uzbb-v-xnor` | v- | 15/18 | default | 21635 | 7886 | 158 | 1 | 411 | 7078 | 2370 | 1673 | 681 | 0 | 1 | 0 | 7886 | 7886 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1388 | 0 | 0 | 6020 | 0 | 0 | 0 | 0 | 0 | 0 | 7886 | 6020 | 0 | 0 | 1863 | 3 | 0 | 0 | 7126 | 6020 | 1104 | 2 | 7126 | 7126 | 0 | 8 | 0 | 1433 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 209 |
| `rv64uzbb-v-zext_h` | v- | 16/18 | default | 12343 | 4821 | 150 | 1 | 279 | 3764 | 1469 | 962 | 492 | 0 | 0 | 0 | 4821 | 4821 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 877 | 741 | 0 | 0 | 3562 | 0 | 0 | 0 | 11 | 0 | 0 | 4821 | 3562 | 0 | 0 | 1256 | 3 | 0 | 0 | 4307 | 3562 | 743 | 2 | 4307 | 4307 | 0 | 8 | 0 | 545 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 135 |
| `rv64uzbc-v-clmul` | v- | 17/18 | default | 13358 | 5334 | 151 | 1 | 288 | 4072 | 1479 | 984 | 480 | 0 | 0 | 0 | 5334 | 5334 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 899 | 751 | 0 | 0 | 4010 | 0 | 0 | 0 | 72 | 0 | 0 | 5334 | 4010 | 0 | 0 | 1321 | 3 | 0 | 0 | 4827 | 4010 | 815 | 2 | 4827 | 4827 | 0 | 8 | 0 | 950 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 149 |
| `rv64uzbc-v-clmulh` | v- | 18/18 | default | 13367 | 5328 | 151 | 1 | 286 | 4087 | 1491 | 986 | 490 | 0 | 0 | 0 | 5328 | 5328 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 4011 | 0 | 0 | 0 | 6 | 0 | 0 | 5328 | 4011 | 0 | 0 | 1314 | 3 | 0 | 0 | 4822 | 4011 | 809 | 2 | 4822 | 4822 | 0 | 8 | 0 | 985 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzbc-v-clmulr` | v- | 1/18 | default | 13363 | 5329 | 151 | 1 | 286 | 4084 | 1491 | 986 | 490 | 0 | 0 | 0 | 5329 | 5329 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 753 | 0 | 0 | 4012 | 0 | 0 | 0 | 48 | 0 | 0 | 5329 | 4012 | 0 | 0 | 1314 | 3 | 0 | 0 | 4824 | 4012 | 810 | 2 | 4824 | 4824 | 0 | 8 | 0 | 957 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzbkb-v-brev8` | v- | 2/18 | default | 12381 | 4930 | 240 | 1 | 281 | 3755 | 1455 | 961 | 479 | 0 | 0 | 0 | 4930 | 4930 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 877 | 751 | 0 | 0 | 3640 | 0 | 0 | 0 | 11 | 0 | 0 | 4930 | 3640 | 0 | 0 | 1287 | 3 | 0 | 0 | 4410 | 3640 | 768 | 2 | 4410 | 4410 | 0 | 8 | 0 | 559 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 136 |
| `rv64uzbkb-v-pack` | v- | 3/18 | default | 21934 | 8202 | 252 | 0 | 411 | 7104 | 2374 | 1674 | 685 | 0 | 0 | 0 | 8202 | 8202 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1398 | 0 | 0 | 6310 | 0 | 0 | 0 | 48 | 0 | 0 | 8202 | 6310 | 0 | 0 | 1889 | 3 | 0 | 0 | 7451 | 6310 | 1139 | 2 | 7451 | 7451 | 0 | 8 | 0 | 1453 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 206 |
| `rv64uzbkb-v-packh` | v- | 4/18 | default | 13549 | 5588 | 240 | 0 | 292 | 3789 | 1493 | 986 | 492 | 0 | 0 | 0 | 5588 | 5588 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 763 | 0 | 0 | 4234 | 0 | 0 | 0 | 48 | 0 | 0 | 5588 | 4234 | 0 | 0 | 1351 | 3 | 0 | 0 | 5068 | 4234 | 832 | 2 | 5068 | 5068 | 0 | 8 | 0 | 1074 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzbkb-v-packw` | v- | 5/18 | default | 13331 | 5522 | 240 | 0 | 289 | 3769 | 1474 | 984 | 475 | 0 | 0 | 0 | 5522 | 5522 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 899 | 760 | 0 | 0 | 4177 | 0 | 0 | 0 | 7 | 0 | 0 | 5522 | 4177 | 0 | 0 | 1342 | 3 | 0 | 0 | 5007 | 4177 | 828 | 2 | 5007 | 5007 | 0 | 8 | 0 | 822 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzbkx-v-xperm4` | v- | 6/18 | default | 21703 | 7854 | 160 | 1 | 405 | 7384 | 2369 | 1674 | 680 | 0 | 0 | 0 | 7854 | 7854 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1388 | 0 | 0 | 6015 | 0 | 0 | 0 | 0 | 0 | 0 | 7854 | 6015 | 0 | 0 | 1836 | 3 | 0 | 0 | 7115 | 6015 | 1098 | 2 | 7115 | 7115 | 0 | 8 | 0 | 1440 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 206 |
| `rv64uzbkx-v-xperm8` | v- | 7/18 | default | 22599 | 8478 | 158 | 1 | 408 | 7384 | 2378 | 1674 | 689 | 0 | 0 | 0 | 8478 | 8478 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1388 | 0 | 0 | 6634 | 0 | 0 | 0 | 0 | 0 | 0 | 8478 | 6634 | 0 | 0 | 1841 | 3 | 0 | 0 | 7725 | 6634 | 1089 | 2 | 7725 | 7725 | 0 | 8 | 0 | 1639 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 207 |
| `rv64uzbs-v-bclr` | v- | 8/18 | default | 21720 | 7988 | 158 | 1 | 403 | 7073 | 2367 | 1674 | 678 | 0 | 0 | 0 | 7988 | 7988 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1391 | 0 | 0 | 6126 | 0 | 0 | 0 | 32 | 0 | 0 | 7988 | 6126 | 0 | 0 | 1859 | 3 | 0 | 0 | 7252 | 6126 | 1124 | 2 | 7252 | 7252 | 0 | 8 | 0 | 1360 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 208 |
| `rv64uzbs-v-bclri` | v- | 9/18 | default | 12657 | 5107 | 150 | 1 | 286 | 3796 | 1510 | 968 | 527 | 0 | 0 | 0 | 5107 | 5107 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 740 | 0 | 0 | 3791 | 0 | 0 | 0 | 46 | 0 | 0 | 5107 | 3791 | 0 | 0 | 1313 | 3 | 0 | 0 | 4590 | 3791 | 797 | 2 | 4590 | 4590 | 0 | 8 | 0 | 562 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 142 |
| `rv64uzbs-v-bext` | v- | 10/18 | default | 21532 | 7824 | 158 | 1 | 411 | 7070 | 2369 | 1673 | 680 | 0 | 1 | 0 | 7824 | 7824 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1390 | 0 | 0 | 5964 | 0 | 0 | 0 | 26 | 0 | 0 | 7824 | 5964 | 0 | 0 | 1857 | 3 | 0 | 0 | 7073 | 5964 | 1107 | 2 | 7073 | 7073 | 0 | 8 | 0 | 1364 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 211 |
| `rv64uzbs-v-bexti` | v- | 11/18 | default | 12551 | 5015 | 150 | 1 | 288 | 3756 | 1472 | 968 | 489 | 0 | 0 | 0 | 5015 | 5015 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 740 | 0 | 0 | 3689 | 0 | 0 | 0 | 31 | 0 | 0 | 5015 | 3689 | 0 | 0 | 1323 | 3 | 0 | 0 | 4491 | 3689 | 800 | 2 | 4491 | 4491 | 0 | 8 | 0 | 533 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 142 |
| `rv64uzbs-v-binv` | v- | 12/18 | default | 21446 | 7747 | 158 | 1 | 408 | 7064 | 2363 | 1671 | 676 | 0 | 1 | 0 | 7747 | 7747 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1542 | 1387 | 0 | 0 | 5893 | 0 | 0 | 0 | 11 | 0 | 0 | 7747 | 5893 | 0 | 0 | 1851 | 3 | 0 | 0 | 6999 | 5893 | 1104 | 2 | 6999 | 6999 | 0 | 8 | 0 | 1373 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 211 |
| `rv64uzbs-v-binvi` | v- | 13/18 | default | 12487 | 4958 | 149 | 1 | 284 | 3764 | 1477 | 968 | 494 | 0 | 0 | 0 | 4958 | 4958 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 740 | 0 | 0 | 3655 | 0 | 0 | 0 | 0 | 0 | 0 | 4958 | 3655 | 0 | 0 | 1300 | 3 | 0 | 0 | 4442 | 3655 | 785 | 2 | 4442 | 4442 | 0 | 8 | 0 | 548 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 140 |
| `rv64uzbs-v-bset` | v- | 14/18 | default | 21724 | 7989 | 158 | 1 | 403 | 7074 | 2367 | 1674 | 678 | 0 | 0 | 0 | 7989 | 7989 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1544 | 1391 | 0 | 0 | 6127 | 0 | 0 | 0 | 11 | 0 | 0 | 7989 | 6127 | 0 | 0 | 1859 | 3 | 0 | 0 | 7253 | 6127 | 1124 | 2 | 7253 | 7253 | 0 | 8 | 0 | 1374 | 0 | 0 | 3355 | 0 | 1433 | 0 | 0 | 0 | 208 |
| `rv64uzbs-v-bseti` | v- | 15/18 | default | 12625 | 5057 | 150 | 1 | 285 | 3765 | 1480 | 968 | 497 | 0 | 0 | 0 | 5057 | 5057 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 883 | 740 | 0 | 0 | 3745 | 0 | 0 | 0 | 0 | 0 | 0 | 5057 | 3745 | 0 | 0 | 1309 | 3 | 0 | 0 | 4541 | 3745 | 794 | 2 | 4541 | 4541 | 0 | 8 | 0 | 582 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 141 |
| `rv64uzfh-v-fadd` | v- | 16/18 | default | 20544 | 7426 | 156 | 1 | 392 | 7344 | 2343 | 1654 | 673 | 0 | 1 | 0 | 7426 | 7426 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 5554 | 0 | 0 | 0 | 70 | 0 | 0 | 7426 | 5554 | 0 | 0 | 1869 | 3 | 0 | 0 | 6684 | 5554 | 1128 | 2 | 6684 | 6684 | 0 | 8 | 0 | 567 | 0 | 0 | 3395 | 0 | 1433 | 0 | 0 | 0 | 203 |
| `rv64uzfh-v-fclass` | v- | 17/18 | default | 11935 | 4462 | 149 | 1 | 270 | 4046 | 1444 | 957 | 472 | 0 | 0 | 0 | 4462 | 4462 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3241 | 0 | 0 | 0 | 29 | 0 | 0 | 4462 | 3241 | 0 | 0 | 1218 | 3 | 0 | 0 | 3959 | 3241 | 716 | 2 | 3959 | 3959 | 0 | 8 | 0 | 461 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 134 |
| `rv64uzfh-v-fcmp` | v- | 18/18 | default | 20261 | 7121 | 153 | 1 | 389 | 7338 | 2331 | 1650 | 665 | 0 | 1 | 0 | 7121 | 7121 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 5295 | 0 | 0 | 0 | 0 | 0 | 0 | 7121 | 5295 | 0 | 0 | 1823 | 3 | 0 | 0 | 6390 | 5295 | 1093 | 2 | 6390 | 6390 | 0 | 8 | 0 | 609 | 0 | 0 | 3379 | 0 | 1433 | 0 | 0 | 0 | 199 |
| `rv64uzfh-v-fcvt` | v- | 1/18 | default | 20265 | 7131 | 152 | 1 | 380 | 7338 | 2324 | 1655 | 654 | 0 | 0 | 0 | 7131 | 7131 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5299 | 0 | 0 | 0 | 53 | 0 | 0 | 7131 | 5299 | 0 | 0 | 1829 | 3 | 0 | 0 | 6414 | 5299 | 1113 | 2 | 6414 | 6414 | 0 | 8 | 0 | 588 | 0 | 0 | 3371 | 0 | 1433 | 0 | 0 | 0 | 200 |
| `rv64uzfh-v-fcvt_w` | v- | 2/18 | default | 29605 | 10992 | 160 | 1 | 494 | 10607 | 3200 | 2362 | 823 | 0 | 0 | 0 | 10992 | 10992 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 2157 | 2007 | 0 | 0 | 8582 | 0 | 0 | 0 | 8 | 0 | 0 | 10992 | 8582 | 0 | 0 | 2407 | 3 | 0 | 0 | 10035 | 8582 | 1451 | 2 | 10035 | 10035 | 0 | 8 | 0 | 824 | 0 | 0 | 5116 | 0 | 2044 | 0 | 0 | 0 | 282 |
| `rv64uzfh-v-fdiv` | v- | 3/18 | default | 20325 | 7196 | 156 | 1 | 384 | 7350 | 2334 | 1652 | 667 | 0 | 0 | 0 | 7196 | 7196 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5362 | 0 | 0 | 0 | 67 | 0 | 0 | 7196 | 5362 | 0 | 0 | 1831 | 3 | 0 | 0 | 6465 | 5362 | 1101 | 2 | 6465 | 6465 | 0 | 8 | 0 | 616 | 0 | 0 | 3383 | 0 | 1433 | 0 | 0 | 0 | 197 |
| `rv64uzfh-v-fmadd` | v- | 4/18 | default | 20647 | 7531 | 156 | 1 | 388 | 7350 | 2343 | 1657 | 671 | 0 | 0 | 0 | 7531 | 7531 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 5669 | 0 | 0 | 0 | 51 | 0 | 0 | 7531 | 5669 | 0 | 0 | 1859 | 3 | 0 | 0 | 6792 | 5669 | 1121 | 2 | 6792 | 6792 | 0 | 8 | 0 | 521 | 0 | 0 | 3403 | 0 | 1433 | 0 | 0 | 0 | 202 |
| `rv64uzfh-v-fmin` | v- | 5/18 | default | 21000 | 7943 | 156 | 1 | 392 | 7344 | 2350 | 1662 | 672 | 0 | 1 | 0 | 7943 | 7943 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1373 | 0 | 0 | 6034 | 0 | 0 | 0 | 93 | 0 | 0 | 7943 | 6034 | 0 | 0 | 1906 | 3 | 0 | 0 | 7196 | 6034 | 1160 | 2 | 7196 | 7196 | 0 | 8 | 0 | 426 | 0 | 0 | 3427 | 0 | 1433 | 0 | 0 | 0 | 211 |
| `rv64uzfh-v-ldst` | v- | 6/18 | default | 21036 | 7475 | 165 | 4 | 467 | 4459 | 2069 | 1284 | 769 | 0 | 1 | 0 | 7475 | 7475 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1138 | 969 | 0 | 0 | 5297 | 0 | 0 | 0 | 14 | 0 | 0 | 7475 | 5297 | 0 | 0 | 2175 | 3 | 0 | 0 | 6623 | 5297 | 1324 | 2 | 6623 | 6623 | 0 | 8 | 0 | 807 | 0 | 0 | 2903 | 0 | 1988 | 0 | 0 | 0 | 232 |
| `rv64uzfh-v-move` | v- | 7/18 | default | 12385 | 4731 | 147 | 1 | 267 | 4053 | 1457 | 965 | 477 | 0 | 0 | 0 | 4731 | 4731 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 871 | 738 | 0 | 0 | 3510 | 0 | 0 | 0 | 31 | 0 | 0 | 4731 | 3510 | 0 | 0 | 1218 | 3 | 0 | 0 | 4225 | 3510 | 713 | 2 | 4225 | 4225 | 0 | 8 | 0 | 626 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 140 |
| `rv64uzfh-v-recoding` | v- | 8/18 | default | 19950 | 6746 | 153 | 1 | 380 | 7346 | 2319 | 1645 | 659 | 0 | 0 | 0 | 6746 | 6746 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1514 | 1374 | 0 | 0 | 4958 | 0 | 0 | 0 | 0 | 0 | 0 | 6746 | 4958 | 0 | 0 | 1785 | 3 | 0 | 0 | 6032 | 4958 | 1072 | 2 | 6032 | 6032 | 0 | 8 | 0 | 732 | 0 | 0 | 3357 | 0 | 1433 | 0 | 0 | 0 | 190 |
| `rv64uziccid-v-ziccid` | v- | 11/18 | default | 158125 | 57159 | 1109 | 4 | 3491 | 59105 | 18588 | 12896 | 5677 | 0 | 0 | 0 | 57159 | 57159 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 11825 | 11334 | 0 | 0 | 43267 | 0 | 0 | 0 | 0 | 0 | 0 | 57159 | 43267 | 0 | 0 | 13889 | 3 | 0 | 0 | 50630 | 43267 | 7361 | 2 | 50630 | 50630 | 0 | 8 | 0 | 203 | 0 | 0 | 29013 | 0 | 11907 | 0 | 0 | 0 | 1633 |
| `rv64uzicond-v-czero_eqz` | v- | 9/18 | default | 13218 | 5479 | 150 | 1 | 286 | 3786 | 1489 | 986 | 488 | 0 | 0 | 0 | 5479 | 5479 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 764 | 0 | 0 | 4150 | 0 | 0 | 0 | 72 | 0 | 0 | 5479 | 4150 | 0 | 0 | 1326 | 3 | 0 | 0 | 4971 | 4150 | 819 | 2 | 4971 | 4971 | 0 | 8 | 0 | 746 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 148 |
| `rv64uzicond-v-czero_nez` | v- | 10/18 | default | 13283 | 5547 | 150 | 1 | 290 | 3803 | 1502 | 986 | 501 | 0 | 0 | 0 | 5547 | 5547 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 901 | 764 | 0 | 0 | 4207 | 0 | 0 | 0 | 0 | 0 | 0 | 5547 | 4207 | 0 | 0 | 1337 | 3 | 0 | 0 | 5034 | 4207 | 825 | 2 | 5034 | 5034 | 0 | 8 | 0 | 742 | 0 | 0 | 1726 | 0 | 822 | 0 | 0 | 0 | 150 |
