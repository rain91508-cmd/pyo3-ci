# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 30 of 2830 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#36090716613](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/36090716613) |
| Commit | `ef62259234` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1790307210, 1790307211, 1790307212, 1790307213, 1790307214, 1790307215, 1790307216, 1790307218 |
| Generated | 2026-09-25 03:48 UTC |

## Suites

| Suite | Shard | PASS | FAIL | TIMEOUT | ERROR | MISSING | Total | Status |
|---|---|---|---|---|---|---|---|---|
| block-BACV2 | none | 82 | 0 | 0+0 | 0 | 0 | 82 | PASS |
| block-BPredUnitV2 | none | 246 | 0 | 0+0 | 0 | 0 | 246 | PASS |
| block-CSRFile | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Commit | none | 44 | 21 | 0+0 | 0 | 0 | 65 | FAIL |
| block-DTLBProbe | none | 29 | 0 | 0+0 | 0 | 0 | 29 | PASS |
| block-Decode | none | 115 | 0 | 0+0 | 0 | 0 | 115 | PASS |
| block-Dispatch | none | 47 | 0 | 0+0 | 0 | 0 | 47 | PASS |
| block-FTQ | none | 168 | 0 | 0+0 | 0 | 0 | 168 | PASS |
| block-FUPool | none | 51 | 0 | 0+0 | 0 | 0 | 51 | PASS |
| block-Fetch | none | 208 | 0 | 0+0 | 0 | 0 | 208 | PASS |
| block-FrontEnd | none | 16 | 0 | 0+0 | 0 | 0 | 16 | PASS |
| block-ICache | none | 53 | 0 | 0+0 | 0 | 0 | 53 | PASS |
| block-IEW | none | 111 | 1 | 0+0 | 0 | 0 | 112 | FAIL |
| block-IQ | none | 132 | 0 | 0+0 | 0 | 0 | 132 | PASS |
| block-LQCore | none | 118 | 0 | 0+0 | 0 | 0 | 118 | PASS |
| block-LSQParent | none | 263 | 2 | 0+0 | 0 | 0 | 265 | FAIL |
| block-O3Control | none | 39 | 6 | 0+0 | 0 | 0 | 45 | FAIL |
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
| block-Testbench | none | 116 | 0 | 0+0 | 0 | 0 | 116 | PASS |
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
| v- | 3/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 4/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 5/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 6/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 8/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| **all** |  | 2800 | 30 | 0+0 | 0 | 0 | 2830 | FAIL |

## Failures

| Test | Suite | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|
| `test_commit_cl.TestADR0005BugFixes::test_rob_retire_ack_semantics` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestADR0005M6OptionB::test_commit_derives_prev_phys_reg_via_m6_option_b` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestADR0005M6OptionB::test_commit_skips_free_when_allocated_new_false` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestADR0005M6OptionB::test_fip_drain_during_running_strict_priority` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestBackwardBus::test_bc_done_seqnum` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_is_store_alone_does_not_trigger_serialize_after` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestDedicatedFlagsCOMMIT_S1_S3::test_serialize_after_sets_pending_without_is_store` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestFIPDrain::test_fip_commit_frees_have_priority` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_advances_pc` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_broadcasts_done_seqnum` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_frees_prev_phys_reg_to_freelist` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_multiple_up_to_width` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_no_dest_no_freelist_update` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_retires_rob_head` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_single_instruction` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_store_sets_committed_stores` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestNormalCommit::test_commit_updates_renamemap` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestSMTArbitration::test_oldest_ready_selection` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestSMTArbitration::test_round_robin_selection` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestSquashAfter::test_squash_after_phase1_sets_pending` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_commit_cl.TestSquashAfter::test_squash_after_phase2_initiates_squash` | block-Commit | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.IEW.test_iew_cl::test_violation_push_sink_to_mempending` | block-IEW | FAIL | - | - | 0s | - | ValueError: not enough values to unpack (expected 4, got 3) def test_violation_push_sink_to_mempending():         """Ver... |
| `test_lsq_parent_cl.TestADR0017::test_violation_signal_still_fires` | block-LSQParent | FAIL | - | - | 0s | - | TypeError: TestADR0017.test_violation_signal_still_fires.<locals>.capture_vs() takes 3 positional arguments but 4 were g... |
| `test_lsq_parent_cl.TestWiringIntegration::test_violation_signal_delivered_with_separate_args` | block-LSQParent | FAIL | - | - | 0s | - | TypeError: TestWiringIntegration.test_violation_signal_delivered_with_separate_args.<locals>.capture() takes 3 positiona... |
| `test_o3_control_cl.TestBackwardBusPropagation::test_squash_reaches_rename` | block-O3Control | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_o3_control_cl.TestBackwardBusPropagation::test_squash_seqnum_reaches_rename` | block-O3Control | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_o3_control_cl.TestEndToEndRenameCommit::test_rob_insert_via_rename` | block-O3Control | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_o3_control_e2e.TestNonSpeculative::test_non_spec_broadcasts_seqnum` | block-O3Control | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_o3_control_e2e.TestRenamePipeline::test_rename_advances_running_state` | block-O3Control | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |
| `test_o3_control_e2e.TestWBUpdate::test_wb_sets_completed` | block-O3Control | FAIL | - | - | 0s | - | AssertionError: Commit §3.4 precondition (should-never-fire, 2026-09-25 ruling 5): the committing ROB head carries NO bb... |

_Full 2830-test table: see the `pyo3-ci-report.md` asset._
