# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 120 of 2845 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#36266852518](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/36266852518) |
| Commit | `f1bc4e2e2f` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1790451741, 1790451742, 1790451743, 1790451744, 1790451745, 1790451746, 1790451748, 1790451749, 1790451751 |
| Generated | 2026-09-26 19:56 UTC |

## Suites

| Suite | Shard | PASS | FAIL | TIMEOUT | ERROR | MISSING | Total | Status |
|---|---|---|---|---|---|---|---|---|
| block-BACV2 | none | 82 | 0 | 0+0 | 0 | 0 | 82 | PASS |
| block-BPredUnitV2 | none | 246 | 0 | 0+0 | 0 | 0 | 246 | PASS |
| block-CSRFile | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Commit | none | 64 | 6 | 0+0 | 0 | 0 | 70 | FAIL |
| block-DTLBProbe | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Decode | none | 115 | 0 | 0+0 | 0 | 0 | 115 | PASS |
| block-Dispatch | none | 43 | 4 | 0+0 | 0 | 0 | 47 | FAIL |
| block-FTQ | none | 168 | 0 | 0+0 | 0 | 0 | 168 | PASS |
| block-FUPool | none | 50 | 1 | 0+0 | 0 | 0 | 51 | FAIL |
| block-Fetch | none | 208 | 0 | 0+0 | 0 | 0 | 208 | PASS |
| block-FrontEnd | none | 16 | 0 | 0+0 | 0 | 0 | 16 | PASS |
| block-ICache | none | 53 | 0 | 0+0 | 0 | 0 | 53 | PASS |
| block-IEW | none | 103 | 9 | 0+0 | 0 | 0 | 112 | FAIL |
| block-IQ | none | 130 | 2 | 0+0 | 0 | 0 | 132 | FAIL |
| block-LQCore | none | 113 | 5 | 0+0 | 0 | 0 | 118 | FAIL |
| block-LSQParent | none | 230 | 35 | 0+0 | 0 | 0 | 265 | FAIL |
| block-O3Control | none | 45 | 0 | 0+0 | 0 | 0 | 45 | PASS |
| block-PhysRegFile | none | 27 | 0 | 0+0 | 0 | 0 | 27 | PASS |
| block-ROB | none | 50 | 9 | 0+0 | 0 | 0 | 59 | FAIL |
| block-ReadOperand | none | 48 | 0 | 0+0 | 0 | 0 | 48 | PASS |
| block-ReadOperandInt | none | 14 | 0 | 0+0 | 0 | 0 | 14 | PASS |
| block-ReadOperandMem | none | 6 | 0 | 0+0 | 0 | 0 | 6 | PASS |
| block-Rename | none | 84 | 7 | 0+0 | 0 | 0 | 91 | FAIL |
| block-SQStore | none | 80 | 37 | 0+0 | 0 | 0 | 117 | FAIL |
| block-Scoreboard | none | 54 | 0 | 0+0 | 0 | 0 | 54 | PASS |
| block-StorageManager | none | 28 | 0 | 0+0 | 0 | 0 | 28 | PASS |
| block-StoreSet | none | 22 | 0 | 0+0 | 0 | 0 | 22 | PASS |
| block-Testbench | none | 116 | 0 | 0+0 | 0 | 0 | 116 | PASS |
| block-TlbiController | none | 11 | 0 | 0+0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | 84 | 5 | 0+0 | 0 | 0 | 89 | FAIL |
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
| v- | 3/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 4/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 5/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 6/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 8/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| **all** |  | 2725 | 120 | 0+0 | 0 | 0 | 2845 | FAIL |

## Failures

| Test | Suite | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|
| `test_commit_cl.TestSMTArbitration::test_backfill_skips_empty_rob_thread` | block-Commit | FAIL | - | - | 0s | - | IndexError: list assignment index out of range self = <Commit.test_commit_cl.TestSMTArbitration object at 0x7fad0359c140... |
| `test_commit_cl.TestSMTArbitration::test_backfill_skips_stalled_head` | block-Commit | FAIL | - | - | 0s | - | IndexError: list assignment index out of range self = <Commit.test_commit_cl.TestSMTArbitration object at 0x7fad0359e690... |
| `test_commit_cl.TestSMTArbitration::test_no_backfill_past_squashed_head` | block-Commit | FAIL | - | - | 0s | - | IndexError: list assignment index out of range self = <Commit.test_commit_cl.TestSMTArbitration object at 0x7fad0359d310... |
| `test_commit_cl.TestSMTArbitration::test_no_backfill_past_trap_head` | block-Commit | FAIL | - | - | 0s | - | IndexError: list assignment index out of range self = <Commit.test_commit_cl.TestSMTArbitration object at 0x7fad0359cb60... |
| `test_commit_cl.TestSMTArbitration::test_round_robin_selection` | block-Commit | FAIL | - | - | 0s | - | IndexError: list assignment index out of range self = <Commit.test_commit_cl.TestSMTArbitration object at 0x7fad0359edb0... |
| `test_commit_cl.TestSMTArbitration::test_rr_pointer_rotates_across_cycles` | block-Commit | FAIL | - | - | 0s | - | IndexError: list assignment index out of range self = <Commit.test_commit_cl.TestSMTArbitration object at 0x7fad0359d700... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_fsm_running_after_squash_allows_dispatch` | block-Dispatch | FAIL | - | - | 0s | - | RuntimeError: P7: dispatch FIFO drain without a boundary position (pending_drain_pos is None) — the seqnum fallback was ... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_squash_keeps_fsm_running` | block-Dispatch | FAIL | - | - | 0s | - | RuntimeError: P7: dispatch FIFO drain without a boundary position (pending_drain_pos is None) — the seqnum fallback was ... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestFSMSquashTransitions::test_squash_prevents_dispatch_in_same_cycle` | block-Dispatch | FAIL | - | - | 0s | - | RuntimeError: P7: dispatch FIFO drain without a boundary position (pending_drain_pos is None) — the seqnum fallback was ... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.Dispatch.test_dispatch_cl.TestSquash::test_squash_discards_younger_entries` | block-Dispatch | FAIL | - | - | 0s | - | RuntimeError: P7: dispatch FIFO drain without a boundary position (pending_drain_pos is None) — the seqnum fallback was ... |
| `test_fu_pool_cl_adr0033_squash_force_ack.TestSquashForceEarlyCompleteADR0033::test_squash_mid_flight_fires_force_early_complete` | block-FUPool | FAIL | - | - | 0s | - | RuntimeError: P7: FUPool ic_squash without a boundary position — the seqnum fallback was removed by directive self = <FU... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EIcSquashFunctional::test_ic_squash_clears_iq_entries` | block-IEW | FAIL | - | - | 0s | - | RuntimeError: P7: SRE shadow lacks position meta (max_entries=0, keys=['alloc_count', 'boundary', 'boundary_pos', 'max_e... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureCommitLoadsPath::test_commit_loads_frees_lq_entry` | block-IEW | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureIcSquashFunctional::test_squashed_add_issues_with_squashed_flag` | block-IEW | FAIL | - | - | 0s | - | RuntimeError: P7: SRE shadow lacks position meta (max_entries=0, keys=['alloc_count', 'boundary', 'boundary_pos', 'max_e... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSCFailurePath::test_sc_fails_when_reservation_not_set` | block-IEW | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSCPath::test_lr_then_sc_succeeds_with_reservation` | block-IEW | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureSquashThreadIsolation::test_squash_tid0_isolates_tid1` | block-IEW | FAIL | - | - | 0s | - | RuntimeError: P7: SRE shadow lacks position meta (max_entries=0, keys=['alloc_count', 'boundary', 'boundary_pos', 'max_e... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EPureStrictlyOrderedLoadReplay::test_strictly_ordered_load_polls_then_issues_after_commit` | block-IEW | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestE2EStoreMemoryPath::test_store_pa_req_fires_with_correct_signals` | block-IEW | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl.TestIcSquashFanOut::test_writeback_ic_squash_signature_is_tid_seqnum` | block-IEW | FAIL | - | - | 0s | - | TypeError: TestIcSquashFanOut.test_writeback_ic_squash_signature_is_tid_seqnum.<locals>._spy() takes 3 positional argume... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_int_iq_cl_adr0033.TestLazySquash::test_squashed_unready_entry_stays_in_iq` | block-IQ | FAIL | - | - | 0s | - | RuntimeError: P7: SRE shadow lacks position meta (max_entries=0, keys=['boundary', 'counter', 'oldest', 'state', 'younge... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IQ.test_mem_iq_cl_adr0033.TestLazySquash::test_squashed_unready_lda_entry_stays_in_iq` | block-IQ | FAIL | - | - | 0s | - | RuntimeError: P7: SRE shadow lacks position meta (max_entries=0, keys=['boundary', 'counter', 'oldest', 'state', 'younge... |
| `test_lq_core_cl.TestCommitLoads::test_commit_loads_advances_head` | block-LQCore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lq_core_cl.TestCommitLoads::test_commit_loads_all_entries` | block-LQCore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lq_core_cl.TestCommitLoads::test_commit_loads_no_entries_above_threshold` | block-LQCore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lq_core_cl.TestCommitLoads::test_commit_loads_per_thread` | block-LQCore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lq_core_cl.TestCommitLoads::test_commit_loads_pops_head_entries_with_seqnum_le_threshold` | block-LQCore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lsq_parent_cl.TestADR0041BarrierPlaceholder::test_placeholder_commit_marks_completed_and_clears_barrier` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestCommitLoads::test_commit_loads_pops_lq_head_entries` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lsq_parent_cl.TestDependentLoadsIntegration::test_squash_clears_dependents_on_sq_entries` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl.TestDependentLoadsIntegration::test_squash_clears_pending_producers_on_lq_entries` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_atomic_amo_lq_sq_pair` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_cbo_as_store_via_parent` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_commit_loads_via_parent` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_fence_barrier_gating` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_fence_full_barrier_via_parent` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_multi_thread_independent` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_simple_store_completion` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_split_store_via_parent` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_squash_and_replay` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_store_backpressure_retry` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestEndToEndIntegration::test_e2e_zero_size_store_via_parent` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestMultiThread::test_squash_tid0_does_not_invalidate_tid1` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_commit_drains_storesToWB_accounting` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_commit_releases_held_load` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestNonSpeculativeHandling::test_placeholder_squash_invalidates_like_any_sq_entry` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl.TestNonSpeculativeHandling::test_younger_store_not_execute_gated_commit_order_release` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestPerPortExecuteArrays::test_load_under_active_barrier_executes_first_cycle` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestSquashHandling::test_squash_complete_pulses` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl.TestSquashHandling::test_squash_invalidates_lq_entries` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl.TestSquashedBypass::test_squashed_load_entry_freed_by_squash_walk` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl.TestStatusSignalsM2::test_ldstq_count_decreases_on_commit` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_loads pop without a retire position (pending_commit_load_pos=-1) — the seqnum fallback was remo... |
| `test_lsq_parent_cl.TestStatusSignalsM2::test_update_next_cycle_true_when_store_popped` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestTranslationFault::test_translation_fault_store_completes_with_fault` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestTwoStageStoreWriteback::test_commit_stores_sets_canwb` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl.TestTwoStageStoreWriteback::test_two_stage_pipeline_commit_then_writeback` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL1::test_squash_clears_l1_shift_reg_slot_silent_pop` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL1::test_squash_does_not_fire_and_clears_l1_slot` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL2::test_squash_clears_l2_shift_reg_slot_silent_pop` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckL2::test_squash_does_not_fire_and_clears_l2_slot` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckNegativeCases::test_squash_walks_only_matching_seqnum` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_lsq_parent_cl_adr0033_squash_force_ack.TestLSQParentSquashForceAckNegativeCases::test_squash_with_empty_shift_regs_does_not_fire` | block-LSQParent | FAIL | - | - | 0s | - | RuntimeError: P7: LQ force_ack_squashed_speculation without a boundary position — the seqnum fallback was removed by dir... |
| `test_rob_cl.TestSquash::test_squash_marks_entries` | block-ROB | FAIL | - | - | 0s | - | assert not True  +  where True = <o3.rob_cl.ROBEntry object at 0x7f0b990cb9a0>.is_squashed  +    where <o3.rob_cl.ROBEnt... |
| `test_rob_cl.TestSquashRecoveryWalk::test_cmt_fip_full_stall` | block-ROB | FAIL | - | - | 0s | - | assert 4 == 2  +  where 4 = sum([True, True, True, True, False, False, ...])  +    where [True, True, True, True, False,... |
| `test_rob_cl.TestSquashRecoveryWalk::test_walk_done_with_last_beat` | block-ROB | FAIL | - | - | 0s | - | assert 4 == 3 self = <ROB.test_rob_cl.TestSquashRecoveryWalk object at 0x7f0b99ac9ac0>      def test_walk_done_with_last... |
| `test_rob_cl.TestSquashRecoveryWalk::test_walk_youngest_to_oldest` | block-ROB | FAIL | - | - | 0s | - | assert False  +  where False = RenameROBSquashWalkResp(rob_squash_walk_valid=[True, True, True, True, False, False, Fals... |
| `test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_ckpt_metadata_save_restore` | block-ROB | FAIL | - | - | 0s | - | assert 1 == 3  +  where 1 = <function ROBCL.construct.<locals>.get_ckpt_slot_index at 0x7f0b991bac00>(0)  +    where <fu... |
| `test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_cmt_fip_full_stalls_phase3_only` | block-ROB | FAIL | - | - | 0s | - | assert 5 == 8 self = <ROB.test_rob_cl.TestSquashRecoveryWalkADR0005 object at 0x7f0b99ac5e20>      def test_rob_squash_w... |
| `test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_phase2_replay` | block-ROB | FAIL | - | - | 0s | - | assert 4 == 2 self = <ROB.test_rob_cl.TestSquashRecoveryWalkADR0005 object at 0x7f0b99ac67b0>      def test_rob_squash_w... |
| `test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_phase3_free` | block-ROB | FAIL | - | - | 0s | - | assert False  +  where False = RenameROBSquashWalkResp(rob_squash_walk_valid=[True, True, True, True, False, False, Fals... |
| `test_rob_cl.TestSquashRecoveryWalkADR0005::test_rob_squash_walk_simultaneous` | block-ROB | FAIL | - | - | 0s | - | assert 8 == 2 self = <ROB.test_rob_cl.TestSquashRecoveryWalkADR0005 object at 0x7f0b99ac6330>      def test_rob_squash_w... |
| `test_rename_cl.TestADR0005ForwardReplay::test_allocated_new_false_skips_fip_write` | block-Rename | FAIL | - | - | 0s | - | RuntimeError: P7: rename received walk beat (slot=0, seq=10) without a phase bit (rob_squash_walk_phase=-1) — the seqnum... |
| `test_rename_cl.TestADR0005ForwardReplay::test_phase3_walk_triggers_fip_write` | block-Rename | FAIL | - | - | 0s | - | RuntimeError: P7: rename received walk beat (slot=0, seq=10) without a phase bit (rob_squash_walk_phase=-1) — the seqnum... |
| `test_rename_cl.TestADR0005SquashRecovery::test_squash_exits_on_both_walks_done` | block-Rename | FAIL | - | - | 0s | - | RuntimeError: P7: rename received walk beat (slot=0, seq=10) without a phase bit (rob_squash_walk_phase=-1) — the seqnum... |
| `test_rename_cl.TestADR0005SquashRecovery::test_walk_done_flags_reset_on_squash` | block-Rename | FAIL | - | - | 0s | - | RuntimeError: P7: rename received walk beat (slot=0, seq=10) without a phase bit (rob_squash_walk_phase=-1) — the seqnum... |
| `test_rename_cl.TestFIPBackPressure::test_fip_back_pressure_stalls_walk` | block-Rename | FAIL | - | - | 0s | - | RuntimeError: P7: rename received walk beat (slot=0, seq=10) without a phase bit (rob_squash_walk_phase=-1) — the seqnum... |
| `test_rename_cl.TestFIPBackPressure::test_fip_clear_on_new_squash` | block-Rename | FAIL | - | - | 0s | - | RuntimeError: P7: rename received walk beat (slot=0, seq=10) without a phase bit (rob_squash_walk_phase=-1) — the seqnum... |
| `test_rename_cl.TestFIPBackPressure::test_fip_full_set_on_walk` | block-Rename | FAIL | - | - | 0s | - | RuntimeError: P7: rename received walk beat (slot=0, seq=10) without a phase bit (rob_squash_walk_phase=-1) — the seqnum... |
| `test_sq_store_cl.TestADR0019Ports::test_dcache_store_pa_req_fires_on_writeback` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_includes_tag` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_tag_value_idx0` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestBitFieldTagScheme::test_dcache_store_pa_req_tag_value_idx1` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestCBOType::test_cbo_clean_writeback` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestCBOType::test_cbo_flush_writeback` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestCBOType::test_cbo_participates_in_tso` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestCBOType::test_cbo_two_stage_writeback_path` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestCBOType::test_cbo_zero_writeback` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestCBOType::test_dcache_store_write_carries_cbo_type` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestFenceOrdering::test_has_stores_to_wb_false_after_drain` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestFenceOrdering::test_has_stores_to_wb_true_when_stores_pending` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestFenceOrdering::test_normal_store_not_blocked_by_sq_head` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestFenceOrdering::test_release_store_blocked_while_a_in_flight` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestFenceOrdering::test_release_store_fires_after_batch_pop` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestFenceOrdering::test_sc_store_fires_after_batch_pop` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_normal_store_still_sends_to_dcache` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_prefetch_does_not_set_storeInFlight` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_prefetch_store_skips_dcache` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestM4PrefetchZeroSizeSkip::test_zero_size_store_skips_dcache` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestM5StoreBackpressure::test_blocked_store_retries_same_packet` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestM5StoreBackpressure::test_store_blocked_when_dcache_not_ready` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestM5StoreBackpressure::test_store_unblocks_when_dcache_ready` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestSplitStoreWriteback::test_split_store_completion_requires_both_acks` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestSplitStoreWriteback::test_split_store_issues_two_dcache_reqs` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestSplitStoreWriteback::test_split_store_marks_committed_on_writeback` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestSplitStoreWriteback::test_split_store_sets_storeInFlight_on_writeback` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestStoreCompleteNotify::test_store_complete_fires_notify_with_head_seqnum` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestStoreCompleteSignature::test_completed_not_set_at_send_time` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_accepts_sq_idx_and_is_frag1` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_sets_completed` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestStoreCompleteSignature::test_store_complete_sets_pending_flags_only_on_completion` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestTwoStageWriteback::test_canwb_set_by_commit_stores` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestWritebackEngine::test_canWB_store_sent_to_dcache_autonomously` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestWritebackEngine::test_storeInFlight_blocks_second_store` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestWritebackEngine::test_store_complete_allows_next_store` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_sq_store_cl.TestWritebackEngine::test_store_complete_clears_storeInFlight` | block-SQStore | FAIL | - | - | 0s | - | RuntimeError: P7: commit_stores canWB pass without a retire position (pending_commit_stores_pos=-1) — the seqnum fallbac... |
| `test_write_back_cl.TestPendingWBQueue::test_pop_time_squash_with_writeback_width` | block-WriteBack | FAIL | - | - | 0s | - | RuntimeError: P7: WB main-loop active window without its position twin (bnd=15) — the seqnum fallback was removed by dir... |
| `test_write_back_cl.TestSquashAtCompletion::test_seqnum_above_boundary_skips_rf_write` | block-WriteBack | FAIL | - | - | 0s | - | RuntimeError: P7: WB main-loop active window without its position twin (bnd=50) — the seqnum fallback was removed by dir... |
| `test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_cleared_after_all_inflight_drained` | block-WriteBack | FAIL | - | - | 0s | - | RuntimeError: P7: WB main-loop active window without its position twin (bnd=5) — the seqnum fallback was removed by dire... |
| `test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_not_cleared_while_completion_in_buffer` | block-WriteBack | FAIL | - | - | 0s | - | RuntimeError: P7: WB main-loop active window without its position twin (bnd=5) — the seqnum fallback was removed by dire... |
| `test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_not_cleared_while_inflight_remaining` | block-WriteBack | FAIL | - | - | 0s | - | RuntimeError: P7: WB main-loop active window without its position twin (bnd=5) — the seqnum fallback was removed by dire... |

_Full 2845-test table: see the `pyo3-ci-report.md` asset._
