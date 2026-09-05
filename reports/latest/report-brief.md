# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 34 of 2664 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#33985164392](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/33985164392) |
| Commit | `c897d389fe` (main) |
| Triggered by | rain91508-cmd |
| Base seed | 1788634163, 1788634164, 1788634165, 1788634166, 1788634167, 1788634168, 1788634169, 1788634177, 1788634196 |
| Generated | 2026-09-05 19:08 UTC |

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
| block-ReadOperand | none | 46 | 2 | 0+0 | 0 | 0 | 48 | FAIL |
| block-ReadOperandInt | none | 5 | 9 | 0+0 | 0 | 0 | 14 | FAIL |
| block-ReadOperandMem | none | 0 | 6 | 0+0 | 0 | 0 | 6 | FAIL |
| block-Rename | none | 84 | 0 | 0+0 | 0 | 0 | 84 | PASS |
| block-SQStore | none | 117 | 0 | 0+0 | 0 | 0 | 117 | PASS |
| block-Scoreboard | none | 54 | 0 | 0+0 | 0 | 0 | 54 | PASS |
| block-StorageManager | none | 28 | 0 | 0+0 | 0 | 0 | 28 | PASS |
| block-StoreSet | none | 19 | 0 | 0+0 | 0 | 0 | 19 | PASS |
| block-Testbench | none | 100 | 0 | 0+0 | 0 | 0 | 100 | PASS |
| block-TlbiController | none | 11 | 0 | 0+0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | 80 | 9 | 0+0 | 0 | 0 | 89 | FAIL |
| p- | none | 204 | 0 | 0+0 | 0 | 0 | 204 | PASS |
| v- | 1/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 10/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 11/18 | 9 | 0 | 1+0 | 0 | 0 | 10 | FAIL |
| v- | 12/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 13/18 | 8 | 0 | 1+0 | 0 | 0 | 9 | FAIL |
| v- | 14/18 | 8 | 0 | 1+0 | 0 | 0 | 9 | FAIL |
| v- | 15/18 | 8 | 0 | 1+0 | 0 | 0 | 9 | FAIL |
| v- | 16/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 17/18 | 8 | 0 | 1+0 | 0 | 0 | 9 | FAIL |
| v- | 18/18 | 9 | 0 | 0+0 | 0 | 0 | 9 | PASS |
| v- | 2/18 | 9 | 0 | 1+0 | 0 | 0 | 10 | FAIL |
| v- | 3/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 4/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 5/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 6/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 7/18 | 9 | 0 | 1+0 | 0 | 0 | 10 | FAIL |
| v- | 8/18 | 10 | 0 | 0+0 | 0 | 0 | 10 | PASS |
| v- | 9/18 | 9 | 0 | 1+0 | 0 | 0 | 10 | FAIL |
| **all** |  | 2630 | 26 | 8+0 | 0 | 0 | 2664 | FAIL |

## Failures

| Test | Suite | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|
| `test_read_operand_cl.TestROInstIssuedProducer::test_ro_inst_issued_called_for_squashed` | block-ReadOperand | FAIL | - | - | 0s | - | assert (0,) == (99, 0)      At index 0 diff: 0 != 99   Right contains one more item: 0      Full diff:     (   -     99,... |
| `test_read_operand_cl.TestROInstIssuedProducer::test_ro_inst_issued_called_with_seqnum_and_tid` | block-ReadOperand | FAIL | - | - | 0s | - | assert (1,) == (42, 1)      At index 0 diff: 1 != 42   Right contains one more item: 1      Full diff:     (   -     42,... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestHandoff::test_fu_operand_called_after_read` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestHandoff::test_squashed_still_handed_off` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestOperandRead::test_rf_read_called_for_sources` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl.TestWBInfoConstruction::test_wbinfo_has_dest_phys_reg` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryCalledPerSourceReg::test_bypass_query_called_for_each_source` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryHitUsesBypassValue::test_bypass_query_hit_uses_bypass_value` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryHitUsesBypassValue::test_bypass_query_miss_uses_rf_read_value` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryPrecedence::test_bypass_query_hit_suppresses_rf_read` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandInt.test_read_operand_int_cl_adr0033_primary.TestBypassQueryPrecedence::test_bypass_query_partial_hit_suppresses_only_hit_sources` | block-ReadOperandInt | FAIL | - | - | 0s | - | TypeError: make_read_operand_int.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_lda_calls_fu_operand` | block-ReadOperandMem | FAIL | - | - | 0s | - | TypeError: make_read_operand_mem.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_none_uop_calls_fu_operand` | block-ReadOperandMem | FAIL | - | - | 0s | - | TypeError: make_read_operand_mem.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTALDARouting::test_sta_calls_fu_operand` | block-ReadOperandMem | FAIL | - | - | 0s | - | TypeError: make_read_operand_mem.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_calls_lsq_execute_store_data` | block-ReadOperandMem | FAIL | - | - | 0s | - | TypeError: make_read_operand_mem.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_does_not_call_fu_operand` | block-ReadOperandMem | FAIL | - | - | 0s | - | TypeError: make_read_operand_mem.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `src.cpu.pyo3.pymtl3.o3-block-tests.ReadOperandMem.test_read_operand_mem_cl.TestSTDRouting::test_std_passes_inst_list_idx_zero` | block-ReadOperandMem | FAIL | - | - | 0s | - | TypeError: make_read_operand_mem.<locals>.<lambda>() missing 1 required positional argument: 'tid' self = <test_read_ope... |
| `test_write_back_cl.TestDirectComplete::test_direct_complete_decrements_counter` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `test_write_back_cl.TestInFlightCounter::test_fu_complete_decrements_counter` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `test_write_back_cl.TestInFlightCounter::test_ic_squash_updates_boundary` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `test_write_back_cl.TestInFlightCounter::test_ro_inst_issued_increments_counter` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `test_write_back_cl.TestPendingWBQueue::test_pop_time_squash_with_writeback_width` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `test_write_back_cl.TestSquashAtCompletion::test_seqnum_above_boundary_skips_rf_write` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_cleared_after_all_inflight_drained` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_not_cleared_while_completion_in_buffer` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `test_write_back_cl.TestSquashBoundaryAutoClear::test_boundary_not_cleared_while_inflight_remaining` | block-WriteBack | FAIL | - | - | 0s | - | TypeError: WriteBackCL.construct.<locals>._make_ro_issued_method.<locals>.method() got an unexpected keyword argument 's... |
| `rv64ua-v-lrsc` | v- | TIMEOUT | - | - | 778s | 680760106 | - |
| `rv64ud-v-fdiv` | v- | TIMEOUT | - | - | 618s | 524940225 | - |
| `rv64ui-v-sd` | v- | TIMEOUT | - | - | 992s | 253159754 | - |
| `rv64ui-v-sll` | v- | TIMEOUT | - | - | 959s | 973236004 | - |
| `rv64ui-v-sllw` | v- | TIMEOUT | - | - | 1122s | 699584865 | - |
| `rv64uzbb-v-ror` | v- | TIMEOUT | - | - | 888s | 175970542 | - |
| `rv64uzbkx-v-xperm8` | v- | TIMEOUT | - | - | 690s | 205770357 | - |
| `rv64uziccid-v-ziccid` | v- | TIMEOUT | - | - | 765s | 333256481 | - |

_Full 2664-test table: see the `pyo3-ci-report.md` asset._
