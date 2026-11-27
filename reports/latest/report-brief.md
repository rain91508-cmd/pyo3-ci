# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 50 of 4148 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#45953011587](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/45953011587) |
| Commit | `8189409876` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1795761539, 1795761540, 1795761542, 1795761543, 1795761544, 1795761545, 1795761546, 1795761547, 1795761548, 1795761549, 1795761633, 1795761816, 1795761823, 1795761826, 1795761832, 1795761833, 1795761848, 1795761859, 1795761862, 1795761864, 1795761867, 1795761873, 1795761875, 1795761889, 1795761922, 1795761958, 1795761992, 1795761996, 1795762330, 1795762336, 1795762373 |
| Testbench | default |
| Generated | 2026-11-27 07:22 UTC |

## Suites

| Suite | Shard | TB | PASS | FAIL | TIMEOUT | ERROR | MISSING | XFAIL-NOTRUN | Total | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| arch-test-p | 1/20 | default | 6 | 0 | 0+8 | 0 | 0 | 0 | 14 | FAIL |
| arch-test-p | 10/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 11/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 12/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 13/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 14/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 15/20 | default | 8 | 0 | 0+5 | 0 | 0 | 0 | 13 | FAIL |
| arch-test-p | 16/20 | default | 8 | 0 | 0+5 | 0 | 0 | 0 | 13 | FAIL |
| arch-test-p | 17/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 18/20 | default | 9 | 1 | 0+3 | 0 | 0 | 0 | 13 | FAIL |
| arch-test-p | 19/20 | default | 8 | 0 | 0+5 | 0 | 0 | 0 | 13 | FAIL |
| arch-test-p | 2/20 | default | 14 | 0 | 0+0 | 0 | 0 | 0 | 14 | PASS |
| arch-test-p | 20/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 3/20 | default | 10 | 0 | 0+4 | 0 | 0 | 0 | 14 | FAIL |
| arch-test-p | 4/20 | default | 14 | 0 | 0+0 | 0 | 0 | 0 | 14 | PASS |
| arch-test-p | 5/20 | default | 6 | 0 | 0+7 | 0 | 0 | 0 | 13 | FAIL |
| arch-test-p | 6/20 | default | 6 | 0 | 0+7 | 0 | 0 | 0 | 13 | FAIL |
| arch-test-p | 7/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 8/20 | default | 13 | 0 | 0+0 | 0 | 0 | 0 | 13 | PASS |
| arch-test-p | 9/20 | default | 10 | 0 | 0+3 | 0 | 0 | 0 | 13 | FAIL |
| block-BACV2 | none | default | 134 | 0 | 0+0 | 0 | 0 | 0 | 134 | PASS |
| block-BPredUnitV2 | none | default | 698 | 0 | 0+0 | 0 | 0 | 0 | 698 | PASS |
| block-CSRFile | none | default | 53 | 0 | 0+0 | 0 | 0 | 0 | 53 | PASS |
| block-CacheCtrl | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-Commit | none | default | 97 | 0 | 0+0 | 0 | 0 | 0 | 97 | PASS |
| block-DTLBProbe | none | default | 32 | 0 | 0+0 | 0 | 0 | 0 | 32 | PASS |
| block-Decode | none | default | 126 | 0 | 0+0 | 0 | 0 | 0 | 126 | PASS |
| block-Dispatch | none | default | 50 | 0 | 0+0 | 0 | 0 | 0 | 50 | PASS |
| block-FTQ | none | default | 159 | 0 | 0+0 | 0 | 0 | 0 | 159 | PASS |
| block-FUPool | none | default | 63 | 0 | 0+0 | 0 | 0 | 0 | 63 | PASS |
| block-Fetch | none | default | 272 | 0 | 0+0 | 0 | 0 | 0 | 272 | PASS |
| block-FrontEnd | none | default | 21 | 0 | 0+0 | 0 | 0 | 0 | 21 | PASS |
| block-ICache | none | default | 63 | 0 | 0+0 | 0 | 0 | 0 | 63 | PASS |
| block-ICacheV2 | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-IEW | none | default | 113 | 0 | 0+0 | 0 | 0 | 0 | 113 | PASS |
| block-IQ | none | default | 132 | 0 | 0+0 | 0 | 0 | 0 | 132 | PASS |
| block-ITLB | none | default | 19 | 0 | 0+0 | 0 | 0 | 0 | 19 | PASS |
| block-L1DCache | none | default | 73 | 0 | 0+0 | 0 | 0 | 0 | 73 | PASS |
| block-LQCore | none | default | 131 | 0 | 0+0 | 0 | 0 | 0 | 131 | PASS |
| block-LSQParent | none | default | 272 | 0 | 0+0 | 0 | 0 | 0 | 272 | PASS |
| block-LSQv2 | none | default | 10 | 0 | 0+0 | 0 | 0 | 0 | 10 | PASS |
| block-MMU | none | default | 103 | 2 | 0+0 | 0 | 0 | 0 | 105 | FAIL |
| block-O3Control | none | default | 45 | 0 | 0+0 | 0 | 0 | 0 | 45 | PASS |
| block-PL2 | none | default | 60 | 0 | 0+0 | 0 | 0 | 0 | 60 | PASS |
| block-PhysRegFile | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-ROB | none | default | 59 | 0 | 0+0 | 0 | 0 | 0 | 59 | PASS |
| block-ReadOperand | none | default | 43 | 0 | 0+0 | 0 | 0 | 0 | 43 | PASS |
| block-ReadOperandInt | none | default | 14 | 0 | 0+0 | 0 | 0 | 0 | 14 | PASS |
| block-ReadOperandMem | none | default | 6 | 0 | 0+0 | 0 | 0 | 0 | 6 | PASS |
| block-Rename | none | default | 96 | 0 | 0+0 | 0 | 0 | 0 | 96 | PASS |
| block-SQStore | none | default | 119 | 0 | 0+0 | 0 | 0 | 0 | 119 | PASS |
| block-Scoreboard | none | default | 57 | 0 | 0+0 | 0 | 0 | 0 | 57 | PASS |
| block-StorageManager | none | default | 33 | 0 | 0+0 | 0 | 0 | 0 | 33 | PASS |
| block-StoreSet | none | default | 22 | 0 | 0+0 | 0 | 0 | 0 | 22 | PASS |
| block-Testbench | none | default | 137 | 0 | 0+0 | 0 | 0 | 0 | 137 | PASS |
| block-TlbiController | none | default | 11 | 0 | 0+0 | 0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | default | 101 | 0 | 0+0 | 0 | 0 | 0 | 101 | PASS |
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
| **all** |  |  | 4098 | 3 | 0+47 | 0 | 0 | 0 | 4148 | FAIL |

## Failures

| Test | Suite | TB | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|---|
| `D-D-fadd.d-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 306846591 | - |
| `D-D-fadd.d-02` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 671830801 | - |
| `D-D-fadd.d-04` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 426287610 | - |
| `D-D-fdiv.d-02` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 215433781 | - |
| `D-D-fle.d-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 183947386 | - |
| `D-D-fmadd.d-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 938668814 | - |
| `D-D-fmadd.d-02` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 303400107 | - |
| `D-D-fmadd.d-04` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 57569428 | - |
| `D-D-fmadd.d-05` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 128569926 | - |
| `D-D-fmadd.d-08` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 896145957 | - |
| `D-D-fmin.d-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 576479236 | - |
| `D-D-fmsub.d-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 411048986 | - |
| `D-D-fmsub.d-01` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 337518359 | - |
| `D-D-fmsub.d-03` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 219023987 | - |
| `D-D-fmsub.d-05` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 887011985 | - |
| `D-D-fmsub.d-07` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 220324684 | - |
| `D-D-fmsub.d-08` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 411462542 | - |
| `D-D-fmul.d-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 204389742 | - |
| `D-D-fnmadd.d-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 773694076 | - |
| `D-D-fnmadd.d-02` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 568812517 | - |
| `D-D-fnmadd.d-04` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 331735215 | - |
| `D-D-fnmadd.d-06` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 587049314 | - |
| `D-D-fnmadd.d-07` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 416310664 | - |
| `D-D-fnmsub.d-05` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 654466330 | - |
| `D-D-fnmsub.d-06` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 474016954 | - |
| `D-D-fnmsub.d-08` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 740526106 | - |
| `D-D-fsgnjx.d-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 254877642 | - |
| `F-F-fadd.s-01` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 708038056 | - |
| `F-F-fadd.s-02` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 489057200 | - |
| `F-F-fadd.s-04` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 269463677 | - |
| `F-F-fdiv.s-04` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 301528145 | - |
| `F-F-feq.s-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 30709117 | - |
| `F-F-fmadd.s-01` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 843989755 | - |
| `F-F-fmadd.s-05` | arch-test-p | default | TIMEOUT-ERR | - | - | 901s | 845291206 | - |
| `F-F-fmadd.s-06` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 691463777 | - |
| `F-F-fmsub.s-01` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 792115722 | - |
| `F-F-fmsub.s-02` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 367841240 | - |
| `F-F-fmsub.s-05` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 100339405 | - |
| `F-F-fmsub.s-07` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 973191218 | - |
| `F-F-fmul.s-01` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 754708991 | - |
| `F-F-fmul.s-02` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 52136223 | - |
| `F-F-fnmadd.s-04` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 905373789 | - |
| `F-F-fnmadd.s-05` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 568536465 | - |
| `F-F-fnmadd.s-07` | arch-test-p | default | FAIL | 3 | 25347 | 192s | 931172280 | exit=3 cycles=25347 status=FAIL l2=0 l2type=gshare |
| `F-F-fnmadd.s-08` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 189146576 | - |
| `F-F-fnmsub.s-00` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 277604931 | - |
| `F-F-fnmsub.s-04` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 262811326 | - |
| `F-F-fnmsub.s-05` | arch-test-p | default | TIMEOUT-ERR | - | - | 900s | 798023199 | - |
| `test_mmu_frozen_ports.TestSpecText::test_all_frozen_wire_forms_carry_spec_signature` | block-MMU | default | FAIL | - | - | 0s | - | AssertionError: MMU frozen-port contract broken (MMU_Block_Spec.md Section 1):     - translate_req: args signature missi... |
| `test_mmu_frozen_ports.TestSpecText::test_negative_dropped_response_field_fails` | block-MMU | default | FAIL | - | - | 0s | - | AssertionError: mutation anchor not in subsection 1.2: '(tag, paddr, fault, l1_hit, l1_data, memory_type, epoch, tlb_hin... |

_Full 4148-test table: see the `pyo3-ci-report.md` asset._
