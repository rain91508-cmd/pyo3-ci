# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 50 of 2664 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#34065818096](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/34065818096) |
| Commit | `33b12449fa` (main) |
| Triggered by | rain91508-cmd |
| Base seed | 1788735953, 1788735954, 1788735955, 1788735956, 1788735957, 1788735958, 1788735959 |
| Generated | 2026-09-06 23:31 UTC |

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
| block-Testbench | none | 99 | 1 | 0+0 | 0 | 0 | 100 | FAIL |
| block-TlbiController | none | 11 | 0 | 0+0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | 89 | 0 | 0+0 | 0 | 0 | 89 | PASS |
| p- | none | 204 | 0 | 0+0 | 0 | 0 | 204 | PASS |
| v- | 1/18 | 9 | 0 | 0+0 | 1 | 0 | 10 | FAIL |
| v- | 10/18 | 9 | 0 | 0+0 | 1 | 0 | 10 | FAIL |
| v- | 11/18 | 8 | 0 | 1+0 | 1 | 0 | 10 | FAIL |
| v- | 12/18 | 7 | 0 | 1+0 | 1 | 0 | 9 | FAIL |
| v- | 13/18 | 7 | 0 | 1+0 | 1 | 0 | 9 | FAIL |
| v- | 14/18 | 8 | 0 | 0+0 | 1 | 0 | 9 | FAIL |
| v- | 15/18 | 6 | 0 | 1+0 | 2 | 0 | 9 | FAIL |
| v- | 16/18 | 8 | 0 | 0+0 | 1 | 0 | 9 | FAIL |
| v- | 17/18 | 7 | 0 | 1+0 | 1 | 0 | 9 | FAIL |
| v- | 18/18 | 5 | 0 | 3+0 | 1 | 0 | 9 | FAIL |
| v- | 2/18 | 9 | 0 | 0+0 | 1 | 0 | 10 | FAIL |
| v- | 3/18 | 9 | 0 | 0+0 | 1 | 0 | 10 | FAIL |
| v- | 4/18 | 7 | 0 | 2+0 | 1 | 0 | 10 | FAIL |
| v- | 5/18 | 8 | 0 | 1+0 | 1 | 0 | 10 | FAIL |
| v- | 6/18 | 9 | 0 | 0+0 | 1 | 0 | 10 | FAIL |
| v- | 7/18 | 8 | 0 | 1+0 | 1 | 0 | 10 | FAIL |
| v- | 8/18 | 9 | 0 | 0+0 | 1 | 0 | 10 | FAIL |
| v- | 9/18 | 8 | 0 | 1+0 | 1 | 0 | 10 | FAIL |
| **all** |  | 2614 | 18 | 13+0 | 19 | 0 | 2664 | FAIL |

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
| `test_riscv_tests_isa::test_rv64ui_p[rv64ui-p-sw:store word]` | block-Testbench | FAIL | - | - | 4s | - | AssertionError: [MEMIQ_SINGLEFIRE] cyc=1398 idx=0 double fu_real_complete in one tick riscv_tests_elf_dir = '/home/runne... |
| `rv64ua-v-amoadd_d` | v- | ERROR | - | - | 124s | 743469819 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoadd_w` | v- | ERROR | - | - | 68s | 371724577 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoand_d` | v- | ERROR | - | - | 123s | 704907951 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoand_w` | v- | ERROR | - | - | 123s | 144343980 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amomax_d` | v- | ERROR | - | - | 121s | 390336667 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amomax_w` | v- | ERROR | - | - | 118s | 884608798 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amomaxu_d` | v- | ERROR | - | - | 118s | 902842881 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amomaxu_w` | v- | ERROR | - | - | 127s | 473364013 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amomin_d` | v- | ERROR | - | - | 121s | 561039112 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amomin_w` | v- | ERROR | - | - | 119s | 46812683 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amominu_d` | v- | ERROR | - | - | 116s | 237870798 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amominu_w` | v- | ERROR | - | - | 116s | 580826329 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoor_d` | v- | ERROR | - | - | 117s | 500219534 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoor_w` | v- | ERROR | - | - | 64s | 922699995 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoswap_d` | v- | ERROR | - | - | 118s | 184135068 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoswap_w` | v- | ERROR | - | - | 76s | 534906358 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoxor_d` | v- | ERROR | - | - | 128s | 538363321 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-amoxor_w` | v- | ERROR | - | - | 120s | 31410242 | exit=None cycles=-1 status=ERROR |
| `rv64ua-v-lrsc` | v- | ERROR | - | - | 224s | 443064678 | exit=None cycles=-1 status=ERROR |
| `rv64ud-v-fcmp` | v- | TIMEOUT | - | - | 938s | 626996165 | - |
| `rv64ud-v-fcvt` | v- | TIMEOUT | - | - | 551s | 758431344 | - |
| `rv64ud-v-fcvt_w` | v- | TIMEOUT | - | - | 989s | 155036621 | - |
| `rv64ud-v-fmadd` | v- | TIMEOUT | - | - | 958s | 284376522 | - |
| `rv64uf-v-fcmp` | v- | TIMEOUT | - | - | 983s | 933044524 | - |
| `rv64uf-v-fmadd` | v- | TIMEOUT | - | - | 947s | 196371563 | - |
| `rv64ui-v-ma_data` | v- | TIMEOUT | - | - | 1284s | 573470024 | - |
| `rv64ui-v-sll` | v- | TIMEOUT | - | - | 966s | 766540669 | - |
| `rv64uzbb-v-orn` | v- | TIMEOUT | - | - | 921s | 412636335 | - |
| `rv64uzbb-v-ror` | v- | TIMEOUT | - | - | 895s | 967275208 | - |
| `rv64uzbkx-v-xperm8` | v- | TIMEOUT | - | - | 875s | 997075023 | - |
| `rv64uzfh-v-fcmp` | v- | TIMEOUT | - | - | 1119s | 967290358 | - |
| `rv64uzfh-v-fmadd` | v- | TIMEOUT | - | - | 874s | 196505013 | - |

_Full 2664-test table: see the `pyo3-ci-report.md` asset._
