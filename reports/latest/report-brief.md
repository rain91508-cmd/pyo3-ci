# pyo3 CI report

|  |  |
|---|---|
| **Result** | **FAIL** -- 370 of 4139 tests not passing |
| Run | [rain91508-cmd/pyo3-ci#44198909122](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/44198909122) |
| Commit | `6b437e966f` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1794958198, 1794958237, 1794958247, 1794958254, 1794958255, 1794958265, 1794958273, 1794958279, 1794958287, 1794958292, 1794958334, 1794958338, 1794958345, 1794958400, 1794958430, 1794958438, 1794958440, 1794958444, 1794958473, 1794958485, 1794958498, 1794958519, 1794958521, 1794958527, 1794958531, 1794958534, 1794958536, 1794958546, 1794958660, 1794958675, 1794958679, 1794958684, 1794958702, 1794958704, 1794958711, 1794958834, 1794959101 |
| Testbench | default |
| Generated | 2026-11-17 23:45 UTC |

## Suites

| Suite | Shard | TB | PASS | FAIL | TIMEOUT | ERROR | MISSING | XFAIL-NOTRUN | Total | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| block-BACV2 | none | default | 110 | 0 | 0+0 | 0 | 0 | 0 | 110 | PASS |
| block-BPredUnitV2 | none | default | 695 | 0 | 0+0 | 0 | 0 | 0 | 695 | PASS |
| block-CSRFile | none | default | 30 | 0 | 0+0 | 0 | 0 | 0 | 30 | PASS |
| block-CacheCtrl | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-Commit | none | default | 78 | 0 | 0+0 | 0 | 0 | 0 | 78 | PASS |
| block-DTLBProbe | none | default | 32 | 0 | 0+0 | 0 | 0 | 0 | 32 | PASS |
| block-Decode | none | default | 126 | 0 | 0+0 | 0 | 0 | 0 | 126 | PASS |
| block-Dispatch | none | default | 50 | 0 | 0+0 | 0 | 0 | 0 | 50 | PASS |
| block-FTQ | none | default | 159 | 0 | 0+0 | 0 | 0 | 0 | 159 | PASS |
| block-FUPool | none | default | 49 | 0 | 0+0 | 0 | 0 | 0 | 49 | PASS |
| block-Fetch | none | default | 272 | 0 | 0+0 | 0 | 0 | 0 | 272 | PASS |
| block-FrontEnd | none | default | 21 | 0 | 0+0 | 0 | 0 | 0 | 21 | PASS |
| block-ICache | none | default | 63 | 0 | 0+0 | 0 | 0 | 0 | 63 | PASS |
| block-ICacheV2 | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-IEW | none | default | 110 | 0 | 0+0 | 0 | 0 | 0 | 110 | PASS |
| block-IQ | none | default | 132 | 0 | 0+0 | 0 | 0 | 0 | 132 | PASS |
| block-ITLB | none | default | 19 | 0 | 0+0 | 0 | 0 | 0 | 19 | PASS |
| block-L1DCache | none | default | 73 | 0 | 0+0 | 0 | 0 | 0 | 73 | PASS |
| block-LQCore | none | default | 127 | 0 | 0+0 | 0 | 0 | 0 | 127 | PASS |
| block-LSQParent | none | default | 268 | 0 | 0+0 | 0 | 0 | 0 | 268 | PASS |
| block-LSQv2 | none | default | 6 | 0 | 0+0 | 0 | 0 | 0 | 6 | PASS |
| block-MMU | none | default | 105 | 0 | 0+0 | 0 | 0 | 0 | 105 | PASS |
| block-O3Control | none | default | 45 | 0 | 0+0 | 0 | 0 | 0 | 45 | PASS |
| block-PL2 | none | default | 60 | 0 | 0+0 | 0 | 0 | 0 | 60 | PASS |
| block-PhysRegFile | none | default | 27 | 0 | 0+0 | 0 | 0 | 0 | 27 | PASS |
| block-ROB | none | default | 59 | 0 | 0+0 | 0 | 0 | 0 | 59 | PASS |
| block-ReadOperand | none | default | 43 | 0 | 0+0 | 0 | 0 | 0 | 43 | PASS |
| block-ReadOperandInt | none | default | 14 | 0 | 0+0 | 0 | 0 | 0 | 14 | PASS |
| block-ReadOperandMem | none | default | 6 | 0 | 0+0 | 0 | 0 | 0 | 6 | PASS |
| block-Rename | none | default | 94 | 0 | 0+0 | 0 | 0 | 0 | 94 | PASS |
| block-SQStore | none | default | 119 | 0 | 0+0 | 0 | 0 | 0 | 119 | PASS |
| block-Scoreboard | none | default | 54 | 0 | 0+0 | 0 | 0 | 0 | 54 | PASS |
| block-StorageManager | none | default | 33 | 0 | 0+0 | 0 | 0 | 0 | 33 | PASS |
| block-StoreSet | none | default | 22 | 0 | 0+0 | 0 | 0 | 0 | 22 | PASS |
| block-Testbench | none | default | 137 | 0 | 0+0 | 0 | 0 | 0 | 137 | PASS |
| block-TlbiController | none | default | 11 | 0 | 0+0 | 0 | 0 | 0 | 11 | PASS |
| block-WriteBack | none | default | 89 | 0 | 0+0 | 0 | 0 | 0 | 89 | PASS |
| cosim-p | none | default | 0 | 198 | 0+0 | 0 | 0 | 0 | 198 | FAIL |
| cosim-v | 1/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 10/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 11/18 | default | 0 | 9 | 0+0 | 0 | 0 | 0 | 9 | FAIL |
| cosim-v | 12/18 | default | 0 | 9 | 0+0 | 0 | 0 | 0 | 9 | FAIL |
| cosim-v | 13/18 | default | 0 | 9 | 0+0 | 0 | 0 | 0 | 9 | FAIL |
| cosim-v | 14/18 | default | 0 | 9 | 0+0 | 0 | 0 | 0 | 9 | FAIL |
| cosim-v | 15/18 | default | 0 | 9 | 0+0 | 0 | 0 | 0 | 9 | FAIL |
| cosim-v | 16/18 | default | 0 | 9 | 0+0 | 0 | 0 | 0 | 9 | FAIL |
| cosim-v | 17/18 | default | 0 | 9 | 0+0 | 0 | 0 | 0 | 9 | FAIL |
| cosim-v | 18/18 | default | 0 | 9 | 0+0 | 0 | 0 | 0 | 9 | FAIL |
| cosim-v | 2/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 3/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 4/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 5/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 6/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 7/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 8/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
| cosim-v | 9/18 | default | 0 | 10 | 0+0 | 0 | 0 | 0 | 10 | FAIL |
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
| **all** |  |  | 3769 | 370 | 0+0 | 0 | 0 | 0 | 4139 | FAIL |

## Failures

| Test | Suite | TB | Status | exit | cycles | wall | perm | detail |
|---|---|---|---|---|---|---|---|---|
| `rv64mi-p-breakpoint` | cosim-p | default | FAIL | - | - | 3s | 757055992 | (3s): rv64mi-p-breakpoint: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444507... |
| `rv64mi-p-csr` | cosim-p | default | FAIL | - | - | 3s | 435460419 | (3s): rv64mi-p-csr: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64mi-p-illegal` | cosim-p | default | FAIL | - | - | 3s | 453910401 | (3s): rv64mi-p-illegal: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64mi-p-instret_overflow` | cosim-p | default | FAIL | - | - | 3s | 235370492 | (3s): rv64mi-p-instret_overflow: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7... |
| `rv64mi-p-ld-misaligned` | cosim-p | default | FAIL | - | - | 3s | 321669545 | (3s): rv64mi-p-ld-misaligned: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444... |
| `rv64mi-p-lh-misaligned` | cosim-p | default | FAIL | - | - | 3s | 498618391 | (3s): rv64mi-p-lh-misaligned: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444... |
| `rv64mi-p-lw-misaligned` | cosim-p | default | FAIL | - | - | 3s | 50854165 | (3s): rv64mi-p-lw-misaligned: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444... |
| `rv64mi-p-ma_addr` | cosim-p | default | FAIL | - | - | 3s | 91719056 | (3s): rv64mi-p-ma_addr: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64mi-p-ma_fetch` | cosim-p | default | FAIL | - | - | 2s | 444240319 | (2s): rv64mi-p-ma_fetch: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64mi-p-mcsr` | cosim-p | default | FAIL | - | - | 3s | 675346712 | (3s): rv64mi-p-mcsr: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64mi-p-pmpaddr` | cosim-p | default | FAIL | - | - | 3s | 703095778 | (3s): rv64mi-p-pmpaddr: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64mi-p-sbreak` | cosim-p | default | FAIL | - | - | 3s | 59847702 | (3s): rv64mi-p-sbreak: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64mi-p-scall` | cosim-p | default | FAIL | - | - | 3s | 294140639 | (3s): rv64mi-p-scall: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64mi-p-sd-misaligned` | cosim-p | default | FAIL | - | - | 2s | 27491165 | (2s): rv64mi-p-sd-misaligned: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444... |
| `rv64mi-p-sh-misaligned` | cosim-p | default | FAIL | - | - | 2s | 499211823 | (2s): rv64mi-p-sh-misaligned: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444... |
| `rv64mi-p-sw-misaligned` | cosim-p | default | FAIL | - | - | 2s | 344966961 | (2s): rv64mi-p-sw-misaligned: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444... |
| `rv64mi-p-zicntr` | cosim-p | default | FAIL | - | - | 3s | 417069349 | (3s): rv64mi-p-zicntr: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64mzicbo-p-zero` | cosim-p | default | FAIL | - | - | 3s | 523685365 | (3s): rv64mzicbo-p-zero: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64si-p-csr` | cosim-p | default | FAIL | - | - | 3s | 413562976 | (3s): rv64si-p-csr: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64si-p-dirty` | cosim-p | default | FAIL | - | - | 3s | 314339684 | (3s): rv64si-p-dirty: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64si-p-icache-alias` | cosim-p | default | FAIL | - | - | 3s | 618311084 | (3s): rv64si-p-icache-alias: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445... |
| `rv64si-p-ma_fetch` | cosim-p | default | FAIL | - | - | 3s | 446153789 | (3s): rv64si-p-ma_fetch: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64si-p-sbreak` | cosim-p | default | FAIL | - | - | 3s | 853661138 | (3s): rv64si-p-sbreak: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64si-p-scall` | cosim-p | default | FAIL | - | - | 3s | 864113611 | (3s): rv64si-p-scall: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64si-p-wfi` | cosim-p | default | FAIL | - | - | 2s | 402472257 | (2s): rv64si-p-wfi: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ssvnapot-p-napot` | cosim-p | default | FAIL | - | - | 3s | 97853319 | (3s): rv64ssvnapot-p-napot: MISMATCH at commit 38 pc=0x800000e4 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744450... |
| `rv64ua-p-amoadd_d` | cosim-p | default | FAIL | - | - | 3s | 304179484 | (3s): rv64ua-p-amoadd_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amoadd_w` | cosim-p | default | FAIL | - | - | 3s | 941677141 | (3s): rv64ua-p-amoadd_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amoand_d` | cosim-p | default | FAIL | - | - | 2s | 799167267 | (2s): rv64ua-p-amoand_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amoand_w` | cosim-p | default | FAIL | - | - | 3s | 236457571 | (3s): rv64ua-p-amoand_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amomax_d` | cosim-p | default | FAIL | - | - | 3s | 88262537 | (3s): rv64ua-p-amomax_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amomax_w` | cosim-p | default | FAIL | - | - | 3s | 586777545 | (3s): rv64ua-p-amomax_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amomaxu_d` | cosim-p | default | FAIL | - | - | 3s | 533585283 | (3s): rv64ua-p-amomaxu_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-p-amomaxu_w` | cosim-p | default | FAIL | - | - | 3s | 99520053 | (3s): rv64ua-p-amomaxu_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-p-amomin_d` | cosim-p | default | FAIL | - | - | 3s | 928058752 | (3s): rv64ua-p-amomin_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amomin_w` | cosim-p | default | FAIL | - | - | 3s | 418075200 | (3s): rv64ua-p-amomin_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amominu_d` | cosim-p | default | FAIL | - | - | 3s | 863801525 | (3s): rv64ua-p-amominu_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-p-amominu_w` | cosim-p | default | FAIL | - | - | 2s | 213753596 | (2s): rv64ua-p-amominu_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-p-amoor_d` | cosim-p | default | FAIL | - | - | 2s | 427260533 | (2s): rv64ua-p-amoor_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64ua-p-amoor_w` | cosim-p | default | FAIL | - | - | 3s | 919144764 | (3s): rv64ua-p-amoor_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64ua-p-amoswap_d` | cosim-p | default | FAIL | - | - | 3s | 350771754 | (3s): rv64ua-p-amoswap_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-p-amoswap_w` | cosim-p | default | FAIL | - | - | 3s | 699869560 | (3s): rv64ua-p-amoswap_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-p-amoxor_d` | cosim-p | default | FAIL | - | - | 3s | 913625318 | (3s): rv64ua-p-amoxor_d: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-amoxor_w` | cosim-p | default | FAIL | - | - | 2s | 398429350 | (2s): rv64ua-p-amoxor_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-p-lrsc` | cosim-p | default | FAIL | - | - | 2s | 833881563 | (2s): rv64ua-p-lrsc: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uc-p-rvc` | cosim-p | default | FAIL | - | - | 3s | 598877765 | (3s): rv64uc-p-rvc: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ud-p-fadd` | cosim-p | default | FAIL | - | - | 3s | 431902521 | (3s): rv64ud-p-fadd: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-p-fclass` | cosim-p | default | FAIL | - | - | 3s | 174534101 | (3s): rv64ud-p-fclass: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64ud-p-fcmp` | cosim-p | default | FAIL | - | - | 3s | 864473724 | (3s): rv64ud-p-fcmp: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-p-fcvt` | cosim-p | default | FAIL | - | - | 3s | 126433940 | (3s): rv64ud-p-fcvt: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-p-fcvt_w` | cosim-p | default | FAIL | - | - | 3s | 441177153 | (3s): rv64ud-p-fcvt_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64ud-p-fdiv` | cosim-p | default | FAIL | - | - | 3s | 838465094 | (3s): rv64ud-p-fdiv: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-p-fmadd` | cosim-p | default | FAIL | - | - | 3s | 34389987 | (3s): rv64ud-p-fmadd: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ud-p-fmin` | cosim-p | default | FAIL | - | - | 3s | 801747800 | (3s): rv64ud-p-fmin: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-p-ldst` | cosim-p | default | FAIL | - | - | 3s | 486393059 | (3s): rv64ud-p-ldst: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-p-move` | cosim-p | default | FAIL | - | - | 3s | 157268816 | (3s): rv64ud-p-move: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-p-recoding` | cosim-p | default | FAIL | - | - | 3s | 705856674 | (3s): rv64ud-p-recoding: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ud-p-structural` | cosim-p | default | FAIL | - | - | 2s | 481821440 | (2s): rv64ud-p-structural: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444507... |
| `rv64uf-p-fadd` | cosim-p | default | FAIL | - | - | 3s | 890822619 | (3s): rv64uf-p-fadd: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-p-fclass` | cosim-p | default | FAIL | - | - | 3s | 405057612 | (3s): rv64uf-p-fclass: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uf-p-fcmp` | cosim-p | default | FAIL | - | - | 3s | 388775840 | (3s): rv64uf-p-fcmp: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-p-fcvt` | cosim-p | default | FAIL | - | - | 3s | 798190977 | (3s): rv64uf-p-fcvt: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-p-fcvt_w` | cosim-p | default | FAIL | - | - | 3s | 133790184 | (3s): rv64uf-p-fcvt_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uf-p-fdiv` | cosim-p | default | FAIL | - | - | 3s | 288992975 | (3s): rv64uf-p-fdiv: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-p-fmadd` | cosim-p | default | FAIL | - | - | 3s | 116196636 | (3s): rv64uf-p-fmadd: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uf-p-fmin` | cosim-p | default | FAIL | - | - | 3s | 490315452 | (3s): rv64uf-p-fmin: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-p-ldst` | cosim-p | default | FAIL | - | - | 3s | 740860970 | (3s): rv64uf-p-ldst: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-p-move` | cosim-p | default | FAIL | - | - | 3s | 403352773 | (3s): rv64uf-p-move: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-p-recoding` | cosim-p | default | FAIL | - | - | 3s | 570362432 | (3s): rv64uf-p-recoding: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ui-p-add` | cosim-p | default | FAIL | - | - | 3s | 594495453 | (3s): rv64ui-p-add: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-addi` | cosim-p | default | FAIL | - | - | 3s | 281093804 | (3s): rv64ui-p-addi: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-addiw` | cosim-p | default | FAIL | - | - | 3s | 278723878 | (3s): rv64ui-p-addiw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-p-addw` | cosim-p | default | FAIL | - | - | 3s | 280092635 | (3s): rv64ui-p-addw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-and` | cosim-p | default | FAIL | - | - | 3s | 407074027 | (3s): rv64ui-p-and: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-andi` | cosim-p | default | FAIL | - | - | 2s | 252403968 | (2s): rv64ui-p-andi: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-auipc` | cosim-p | default | FAIL | - | - | 2s | 874519552 | (2s): rv64ui-p-auipc: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-p-beq` | cosim-p | default | FAIL | - | - | 3s | 961345129 | (3s): rv64ui-p-beq: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-bge` | cosim-p | default | FAIL | - | - | 3s | 252744701 | (3s): rv64ui-p-bge: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-bgeu` | cosim-p | default | FAIL | - | - | 3s | 712767564 | (3s): rv64ui-p-bgeu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-blt` | cosim-p | default | FAIL | - | - | 3s | 245133578 | (3s): rv64ui-p-blt: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-bltu` | cosim-p | default | FAIL | - | - | 3s | 821503407 | (3s): rv64ui-p-bltu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-bne` | cosim-p | default | FAIL | - | - | 3s | 32754528 | (3s): rv64ui-p-bne: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-fence_i` | cosim-p | default | FAIL | - | - | 3s | 445035393 | (3s): rv64ui-p-fence_i: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64ui-p-jal` | cosim-p | default | FAIL | - | - | 3s | 810433152 | (3s): rv64ui-p-jal: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-jalr` | cosim-p | default | FAIL | - | - | 2s | 24569644 | (2s): rv64ui-p-jalr: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-lb` | cosim-p | default | FAIL | - | - | 3s | 844486269 | (3s): rv64ui-p-lb: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-lbu` | cosim-p | default | FAIL | - | - | 3s | 503138118 | (3s): rv64ui-p-lbu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-ld` | cosim-p | default | FAIL | - | - | 3s | 492514766 | (3s): rv64ui-p-ld: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-ld_st` | cosim-p | default | FAIL | - | - | 3s | 494787156 | (3s): rv64ui-p-ld_st: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-p-lh` | cosim-p | default | FAIL | - | - | 3s | 419375562 | (3s): rv64ui-p-lh: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-lhu` | cosim-p | default | FAIL | - | - | 3s | 688986652 | (3s): rv64ui-p-lhu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-lui` | cosim-p | default | FAIL | - | - | 3s | 797505342 | (3s): rv64ui-p-lui: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-lw` | cosim-p | default | FAIL | - | - | 3s | 914111381 | (3s): rv64ui-p-lw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-lwu` | cosim-p | default | FAIL | - | - | 3s | 382596209 | (3s): rv64ui-p-lwu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-ma_data` | cosim-p | default | FAIL | - | - | 3s | 233157998 | (3s): rv64ui-p-ma_data: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64ui-p-or` | cosim-p | default | FAIL | - | - | 3s | 81982208 | (3s): rv64ui-p-or: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-ori` | cosim-p | default | FAIL | - | - | 3s | 216885575 | (3s): rv64ui-p-ori: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-sb` | cosim-p | default | FAIL | - | - | 3s | 16676419 | (3s): rv64ui-p-sb: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-sd` | cosim-p | default | FAIL | - | - | 3s | 790054035 | (3s): rv64ui-p-sd: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-sh` | cosim-p | default | FAIL | - | - | 3s | 658769149 | (3s): rv64ui-p-sh: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-simple` | cosim-p | default | FAIL | - | - | 3s | 614622415 | (3s): rv64ui-p-simple: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64ui-p-sll` | cosim-p | default | FAIL | - | - | 2s | 311242708 | (2s): rv64ui-p-sll: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-slli` | cosim-p | default | FAIL | - | - | 2s | 845418896 | (2s): rv64ui-p-slli: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-slliw` | cosim-p | default | FAIL | - | - | 3s | 608797554 | (3s): rv64ui-p-slliw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-p-sllw` | cosim-p | default | FAIL | - | - | 3s | 6544603 | (3s): rv64ui-p-sllw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-slt` | cosim-p | default | FAIL | - | - | 3s | 893248517 | (3s): rv64ui-p-slt: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-slti` | cosim-p | default | FAIL | - | - | 3s | 588821848 | (3s): rv64ui-p-slti: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-sltiu` | cosim-p | default | FAIL | - | - | 3s | 764100326 | (3s): rv64ui-p-sltiu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-p-sltu` | cosim-p | default | FAIL | - | - | 2s | 569444663 | (2s): rv64ui-p-sltu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-sra` | cosim-p | default | FAIL | - | - | 3s | 467883079 | (3s): rv64ui-p-sra: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-srai` | cosim-p | default | FAIL | - | - | 3s | 735348449 | (3s): rv64ui-p-srai: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-sraiw` | cosim-p | default | FAIL | - | - | 3s | 1032262 | (3s): rv64ui-p-sraiw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-p-sraw` | cosim-p | default | FAIL | - | - | 3s | 825780685 | (3s): rv64ui-p-sraw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-srl` | cosim-p | default | FAIL | - | - | 3s | 653850414 | (3s): rv64ui-p-srl: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-srli` | cosim-p | default | FAIL | - | - | 3s | 604867714 | (3s): rv64ui-p-srli: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-srliw` | cosim-p | default | FAIL | - | - | 2s | 499592439 | (2s): rv64ui-p-srliw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-p-srlw` | cosim-p | default | FAIL | - | - | 3s | 954151980 | (3s): rv64ui-p-srlw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-st_ld` | cosim-p | default | FAIL | - | - | 3s | 624120726 | (3s): rv64ui-p-st_ld: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-p-sub` | cosim-p | default | FAIL | - | - | 3s | 226712589 | (3s): rv64ui-p-sub: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-subw` | cosim-p | default | FAIL | - | - | 2s | 179870436 | (2s): rv64ui-p-subw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-p-sw` | cosim-p | default | FAIL | - | - | 3s | 278726867 | (3s): rv64ui-p-sw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-p-xor` | cosim-p | default | FAIL | - | - | 3s | 989253079 | (3s): rv64ui-p-xor: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-p-xori` | cosim-p | default | FAIL | - | - | 3s | 91180075 | (3s): rv64ui-p-xori: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-p-div` | cosim-p | default | FAIL | - | - | 3s | 440071745 | (3s): rv64um-p-div: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64um-p-divu` | cosim-p | default | FAIL | - | - | 3s | 538454866 | (3s): rv64um-p-divu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-p-divuw` | cosim-p | default | FAIL | - | - | 3s | 366339826 | (3s): rv64um-p-divuw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64um-p-divw` | cosim-p | default | FAIL | - | - | 3s | 225796936 | (3s): rv64um-p-divw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-p-mul` | cosim-p | default | FAIL | - | - | 3s | 352075994 | (3s): rv64um-p-mul: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64um-p-mulh` | cosim-p | default | FAIL | - | - | 3s | 882885038 | (3s): rv64um-p-mulh: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-p-mulhsu` | cosim-p | default | FAIL | - | - | 3s | 546315068 | (3s): rv64um-p-mulhsu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64um-p-mulhu` | cosim-p | default | FAIL | - | - | 3s | 808774524 | (3s): rv64um-p-mulhu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64um-p-mulw` | cosim-p | default | FAIL | - | - | 3s | 446403509 | (3s): rv64um-p-mulw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-p-rem` | cosim-p | default | FAIL | - | - | 3s | 926951204 | (3s): rv64um-p-rem: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64um-p-remu` | cosim-p | default | FAIL | - | - | 3s | 138679444 | (3s): rv64um-p-remu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-p-remuw` | cosim-p | default | FAIL | - | - | 3s | 808492315 | (3s): rv64um-p-remuw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64um-p-remw` | cosim-p | default | FAIL | - | - | 3s | 457374886 | (3s): rv64um-p-remw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uzba-p-add_uw` | cosim-p | default | FAIL | - | - | 2s | 235218987 | (2s): rv64uzba-p-add_uw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzba-p-sh1add` | cosim-p | default | FAIL | - | - | 3s | 258940762 | (3s): rv64uzba-p-sh1add: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzba-p-sh1add_uw` | cosim-p | default | FAIL | - | - | 3s | 102235911 | (3s): rv64uzba-p-sh1add_uw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744450... |
| `rv64uzba-p-sh2add` | cosim-p | default | FAIL | - | - | 3s | 833640622 | (3s): rv64uzba-p-sh2add: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzba-p-sh2add_uw` | cosim-p | default | FAIL | - | - | 3s | 855269945 | (3s): rv64uzba-p-sh2add_uw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744450... |
| `rv64uzba-p-sh3add` | cosim-p | default | FAIL | - | - | 3s | 642793522 | (3s): rv64uzba-p-sh3add: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzba-p-sh3add_uw` | cosim-p | default | FAIL | - | - | 3s | 532540268 | (3s): rv64uzba-p-sh3add_uw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744450... |
| `rv64uzba-p-slli_uw` | cosim-p | default | FAIL | - | - | 3s | 191432439 | (3s): rv64uzba-p-slli_uw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64uzbb-p-andn` | cosim-p | default | FAIL | - | - | 3s | 598573374 | (3s): rv64uzbb-p-andn: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-clz` | cosim-p | default | FAIL | - | - | 3s | 808199044 | (3s): rv64uzbb-p-clz: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-p-clzw` | cosim-p | default | FAIL | - | - | 3s | 355018818 | (3s): rv64uzbb-p-clzw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-cpop` | cosim-p | default | FAIL | - | - | 3s | 54136576 | (3s): rv64uzbb-p-cpop: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-cpopw` | cosim-p | default | FAIL | - | - | 3s | 577377358 | (3s): rv64uzbb-p-cpopw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbb-p-ctz` | cosim-p | default | FAIL | - | - | 2s | 493914044 | (2s): rv64uzbb-p-ctz: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-p-ctzw` | cosim-p | default | FAIL | - | - | 3s | 248476827 | (3s): rv64uzbb-p-ctzw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-max` | cosim-p | default | FAIL | - | - | 3s | 384421784 | (3s): rv64uzbb-p-max: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-p-maxu` | cosim-p | default | FAIL | - | - | 3s | 202861084 | (3s): rv64uzbb-p-maxu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-min` | cosim-p | default | FAIL | - | - | 3s | 264300553 | (3s): rv64uzbb-p-min: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-p-minu` | cosim-p | default | FAIL | - | - | 2s | 584668418 | (2s): rv64uzbb-p-minu: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-orc_b` | cosim-p | default | FAIL | - | - | 3s | 756520808 | (3s): rv64uzbb-p-orc_b: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbb-p-orn` | cosim-p | default | FAIL | - | - | 3s | 764729126 | (3s): rv64uzbb-p-orn: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-p-rev8` | cosim-p | default | FAIL | - | - | 3s | 917116365 | (3s): rv64uzbb-p-rev8: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-rol` | cosim-p | default | FAIL | - | - | 3s | 406062947 | (3s): rv64uzbb-p-rol: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-p-rolw` | cosim-p | default | FAIL | - | - | 3s | 346594764 | (3s): rv64uzbb-p-rolw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-ror` | cosim-p | default | FAIL | - | - | 3s | 150925126 | (3s): rv64uzbb-p-ror: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-p-rori` | cosim-p | default | FAIL | - | - | 3s | 817951776 | (3s): rv64uzbb-p-rori: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-roriw` | cosim-p | default | FAIL | - | - | 3s | 975802067 | (3s): rv64uzbb-p-roriw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbb-p-rorw` | cosim-p | default | FAIL | - | - | 2s | 739040386 | (2s): rv64uzbb-p-rorw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-sext_b` | cosim-p | default | FAIL | - | - | 3s | 105475253 | (3s): rv64uzbb-p-sext_b: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbb-p-sext_h` | cosim-p | default | FAIL | - | - | 3s | 728697239 | (3s): rv64uzbb-p-sext_h: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbb-p-xnor` | cosim-p | default | FAIL | - | - | 3s | 665667695 | (3s): rv64uzbb-p-xnor: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-p-zext_h` | cosim-p | default | FAIL | - | - | 3s | 798555430 | (3s): rv64uzbb-p-zext_h: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbc-p-clmul` | cosim-p | default | FAIL | - | - | 3s | 383369089 | (3s): rv64uzbc-p-clmul: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbc-p-clmulh` | cosim-p | default | FAIL | - | - | 3s | 698345040 | (3s): rv64uzbc-p-clmulh: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbc-p-clmulr` | cosim-p | default | FAIL | - | - | 3s | 145776259 | (3s): rv64uzbc-p-clmulr: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbkb-p-brev8` | cosim-p | default | FAIL | - | - | 3s | 752591096 | (3s): rv64uzbkb-p-brev8: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbkb-p-pack` | cosim-p | default | FAIL | - | - | 3s | 359461716 | (3s): rv64uzbkb-p-pack: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbkb-p-packh` | cosim-p | default | FAIL | - | - | 3s | 222240771 | (3s): rv64uzbkb-p-packh: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbkb-p-packw` | cosim-p | default | FAIL | - | - | 3s | 111238105 | (3s): rv64uzbkb-p-packw: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbkx-p-xperm4` | cosim-p | default | FAIL | - | - | 3s | 594943806 | (3s): rv64uzbkx-p-xperm4: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64uzbkx-p-xperm8` | cosim-p | default | FAIL | - | - | 2s | 300223072 | (2s): rv64uzbkx-p-xperm8: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64uzbs-p-bclr` | cosim-p | default | FAIL | - | - | 3s | 150963465 | (3s): rv64uzbs-p-bclr: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbs-p-bclri` | cosim-p | default | FAIL | - | - | 3s | 305953045 | (3s): rv64uzbs-p-bclri: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbs-p-bext` | cosim-p | default | FAIL | - | - | 3s | 485092858 | (3s): rv64uzbs-p-bext: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbs-p-bexti` | cosim-p | default | FAIL | - | - | 3s | 296387895 | (3s): rv64uzbs-p-bexti: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbs-p-binv` | cosim-p | default | FAIL | - | - | 3s | 94588181 | (3s): rv64uzbs-p-binv: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbs-p-binvi` | cosim-p | default | FAIL | - | - | 3s | 570079850 | (3s): rv64uzbs-p-binvi: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbs-p-bset` | cosim-p | default | FAIL | - | - | 3s | 55368271 | (3s): rv64uzbs-p-bset: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbs-p-bseti` | cosim-p | default | FAIL | - | - | 3s | 958320559 | (3s): rv64uzbs-p-bseti: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzfh-p-fadd` | cosim-p | default | FAIL | - | - | 3s | 811150009 | (3s): rv64uzfh-p-fadd: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-p-fclass` | cosim-p | default | FAIL | - | - | 3s | 442328850 | (3s): rv64uzfh-p-fclass: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzfh-p-fcmp` | cosim-p | default | FAIL | - | - | 3s | 306672893 | (3s): rv64uzfh-p-fcmp: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-p-fcvt` | cosim-p | default | FAIL | - | - | 3s | 897491251 | (3s): rv64uzfh-p-fcvt: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-p-fcvt_w` | cosim-p | default | FAIL | - | - | 3s | 173448422 | (3s): rv64uzfh-p-fcvt_w: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzfh-p-fdiv` | cosim-p | default | FAIL | - | - | 3s | 404521390 | (3s): rv64uzfh-p-fdiv: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-p-fmadd` | cosim-p | default | FAIL | - | - | 3s | 129956438 | (3s): rv64uzfh-p-fmadd: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzfh-p-fmin` | cosim-p | default | FAIL | - | - | 3s | 222963185 | (3s): rv64uzfh-p-fmin: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-p-ldst` | cosim-p | default | FAIL | - | - | 2s | 980769402 | (2s): rv64uzfh-p-ldst: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-p-move` | cosim-p | default | FAIL | - | - | 3s | 310155208 | (3s): rv64uzfh-p-move: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-p-recoding` | cosim-p | default | FAIL | - | - | 3s | 697829917 | (3s): rv64uzfh-p-recoding: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444507... |
| `rv64uzicond-p-czero_eqz` | cosim-p | default | FAIL | - | - | 2s | 497954547 | (2s): rv64uzicond-p-czero_eqz: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744... |
| `rv64uzicond-p-czero_nez` | cosim-p | default | FAIL | - | - | 2s | 402158345 | (2s): rv64uzicond-p-czero_nez: MISMATCH at commit 38 pc=0x800000e0 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744... |
| `rv64ua-v-amoadd_d` | cosim-v | default | FAIL | - | - | 3s | 302093878 | (3s): rv64ua-v-amoadd_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amoadd_w` | cosim-v | default | FAIL | - | - | 3s | 140349266 | (3s): rv64ua-v-amoadd_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amoand_d` | cosim-v | default | FAIL | - | - | 3s | 293532100 | (3s): rv64ua-v-amoand_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amoand_w` | cosim-v | default | FAIL | - | - | 4s | 908968664 | (4s): rv64ua-v-amoand_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amomax_d` | cosim-v | default | FAIL | - | - | 2s | 972960805 | (2s): rv64ua-v-amomax_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amomax_w` | cosim-v | default | FAIL | - | - | 2s | 478232962 | (2s): rv64ua-v-amomax_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amomaxu_d` | cosim-v | default | FAIL | - | - | 4s | 675467582 | (4s): rv64ua-v-amomaxu_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-v-amomaxu_w` | cosim-v | default | FAIL | - | - | 3s | 82988225 | (3s): rv64ua-v-amomaxu_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-v-amomin_d` | cosim-v | default | FAIL | - | - | 3s | 143663243 | (3s): rv64ua-v-amomin_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amomin_w` | cosim-v | default | FAIL | - | - | 2s | 767437235 | (2s): rv64ua-v-amomin_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amominu_d` | cosim-v | default | FAIL | - | - | 3s | 402496675 | (3s): rv64ua-v-amominu_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-v-amominu_w` | cosim-v | default | FAIL | - | - | 5s | 324450943 | (5s): rv64ua-v-amominu_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-v-amoor_d` | cosim-v | default | FAIL | - | - | 3s | 245844154 | (3s): rv64ua-v-amoor_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64ua-v-amoor_w` | cosim-v | default | FAIL | - | - | 2s | 518324165 | (2s): rv64ua-v-amoor_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64ua-v-amoswap_d` | cosim-v | default | FAIL | - | - | 3s | 924759680 | (3s): rv64ua-v-amoswap_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-v-amoswap_w` | cosim-v | default | FAIL | - | - | 3s | 996530133 | (3s): rv64ua-v-amoswap_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64ua-v-amoxor_d` | cosim-v | default | FAIL | - | - | 3s | 87987353 | (3s): rv64ua-v-amoxor_d: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-amoxor_w` | cosim-v | default | FAIL | - | - | 3s | 627034419 | (3s): rv64ua-v-amoxor_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ua-v-lrsc` | cosim-v | default | FAIL | - | - | 3s | 1688737 | (3s): rv64ua-v-lrsc: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uc-v-rvc` | cosim-v | default | FAIL | - | - | 3s | 243096886 | (3s): rv64uc-v-rvc: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ud-v-fadd` | cosim-v | default | FAIL | - | - | 3s | 496326431 | (3s): rv64ud-v-fadd: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-v-fclass` | cosim-v | default | FAIL | - | - | 4s | 581111658 | (4s): rv64ud-v-fclass: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64ud-v-fcmp` | cosim-v | default | FAIL | - | - | 2s | 211620302 | (2s): rv64ud-v-fcmp: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-v-fcvt` | cosim-v | default | FAIL | - | - | 2s | 351055505 | (2s): rv64ud-v-fcvt: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-v-fcvt_w` | cosim-v | default | FAIL | - | - | 4s | 930661338 | (4s): rv64ud-v-fcvt_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64ud-v-fdiv` | cosim-v | default | FAIL | - | - | 4s | 921869091 | (4s): rv64ud-v-fdiv: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-v-fmadd` | cosim-v | default | FAIL | - | - | 3s | 866000657 | (3s): rv64ud-v-fmadd: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ud-v-fmin` | cosim-v | default | FAIL | - | - | 2s | 252134287 | (2s): rv64ud-v-fmin: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-v-ldst` | cosim-v | default | FAIL | - | - | 3s | 952768938 | (3s): rv64ud-v-ldst: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-v-move` | cosim-v | default | FAIL | - | - | 5s | 331409539 | (5s): rv64ud-v-move: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ud-v-recoding` | cosim-v | default | FAIL | - | - | 3s | 214469206 | (3s): rv64ud-v-recoding: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ud-v-structural` | cosim-v | default | FAIL | - | - | 2s | 689857579 | (2s): rv64ud-v-structural: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444507... |
| `rv64uf-v-fadd` | cosim-v | default | FAIL | - | - | 3s | 324501759 | (3s): rv64uf-v-fadd: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-v-fclass` | cosim-v | default | FAIL | - | - | 3s | 432382076 | (3s): rv64uf-v-fclass: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uf-v-fcmp` | cosim-v | default | FAIL | - | - | 3s | 480668550 | (3s): rv64uf-v-fcmp: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-v-fcvt` | cosim-v | default | FAIL | - | - | 3s | 804616378 | (3s): rv64uf-v-fcvt: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-v-fcvt_w` | cosim-v | default | FAIL | - | - | 3s | 185536021 | (3s): rv64uf-v-fcvt_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uf-v-fdiv` | cosim-v | default | FAIL | - | - | 3s | 751659411 | (3s): rv64uf-v-fdiv: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-v-fmadd` | cosim-v | default | FAIL | - | - | 4s | 785995722 | (4s): rv64uf-v-fmadd: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uf-v-fmin` | cosim-v | default | FAIL | - | - | 4s | 761439087 | (4s): rv64uf-v-fmin: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-v-ldst` | cosim-v | default | FAIL | - | - | 2s | 993981402 | (2s): rv64uf-v-ldst: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-v-move` | cosim-v | default | FAIL | - | - | 2s | 798230203 | (2s): rv64uf-v-move: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uf-v-recoding` | cosim-v | default | FAIL | - | - | 4s | 507727637 | (4s): rv64uf-v-recoding: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64ui-v-add` | cosim-v | default | FAIL | - | - | 4s | 486149478 | (4s): rv64ui-v-add: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-addi` | cosim-v | default | FAIL | - | - | 3s | 594310153 | (3s): rv64ui-v-addi: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-addiw` | cosim-v | default | FAIL | - | - | 2s | 813096111 | (2s): rv64ui-v-addiw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-v-addw` | cosim-v | default | FAIL | - | - | 3s | 213742200 | (3s): rv64ui-v-addw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-and` | cosim-v | default | FAIL | - | - | 5s | 706440547 | (5s): rv64ui-v-and: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-andi` | cosim-v | default | FAIL | - | - | 3s | 630070888 | (3s): rv64ui-v-andi: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-auipc` | cosim-v | default | FAIL | - | - | 2s | 102995177 | (2s): rv64ui-v-auipc: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-v-beq` | cosim-v | default | FAIL | - | - | 3s | 893217219 | (3s): rv64ui-v-beq: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-bge` | cosim-v | default | FAIL | - | - | 3s | 461526391 | (3s): rv64ui-v-bge: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-bgeu` | cosim-v | default | FAIL | - | - | 3s | 963031830 | (3s): rv64ui-v-bgeu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-blt` | cosim-v | default | FAIL | - | - | 3s | 763395972 | (3s): rv64ui-v-blt: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-bltu` | cosim-v | default | FAIL | - | - | 3s | 890756894 | (3s): rv64ui-v-bltu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-bne` | cosim-v | default | FAIL | - | - | 3s | 883182666 | (3s): rv64ui-v-bne: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-fence_i` | cosim-v | default | FAIL | - | - | 3s | 901032628 | (3s): rv64ui-v-fence_i: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64ui-v-jal` | cosim-v | default | FAIL | - | - | 4s | 325393117 | (4s): rv64ui-v-jal: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-jalr` | cosim-v | default | FAIL | - | - | 2s | 904507688 | (2s): rv64ui-v-jalr: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-lb` | cosim-v | default | FAIL | - | - | 2s | 401512875 | (2s): rv64ui-v-lb: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-lbu` | cosim-v | default | FAIL | - | - | 4s | 345869310 | (4s): rv64ui-v-lbu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-ld` | cosim-v | default | FAIL | - | - | 4s | 817361413 | (4s): rv64ui-v-ld: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-ld_st` | cosim-v | default | FAIL | - | - | 3s | 473772928 | (3s): rv64ui-v-ld_st: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-v-lh` | cosim-v | default | FAIL | - | - | 2s | 226098850 | (2s): rv64ui-v-lh: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-lhu` | cosim-v | default | FAIL | - | - | 3s | 651201286 | (3s): rv64ui-v-lhu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-lui` | cosim-v | default | FAIL | - | - | 4s | 416730020 | (4s): rv64ui-v-lui: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-lw` | cosim-v | default | FAIL | - | - | 3s | 384250090 | (3s): rv64ui-v-lw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-lwu` | cosim-v | default | FAIL | - | - | 3s | 257945948 | (3s): rv64ui-v-lwu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-ma_data` | cosim-v | default | FAIL | - | - | 3s | 311094620 | (3s): rv64ui-v-ma_data: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64ui-v-or` | cosim-v | default | FAIL | - | - | 3s | 35131100 | (3s): rv64ui-v-or: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-ori` | cosim-v | default | FAIL | - | - | 3s | 774895360 | (3s): rv64ui-v-ori: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-sb` | cosim-v | default | FAIL | - | - | 3s | 98056495 | (3s): rv64ui-v-sb: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-sd` | cosim-v | default | FAIL | - | - | 2s | 606088488 | (2s): rv64ui-v-sd: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-sh` | cosim-v | default | FAIL | - | - | 2s | 896570994 | (2s): rv64ui-v-sh: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-simple` | cosim-v | default | FAIL | - | - | 3s | 752101552 | (3s): rv64ui-v-simple: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64ui-v-sll` | cosim-v | default | FAIL | - | - | 4s | 530165343 | (4s): rv64ui-v-sll: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-slli` | cosim-v | default | FAIL | - | - | 3s | 872776316 | (3s): rv64ui-v-slli: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-slliw` | cosim-v | default | FAIL | - | - | 3s | 282635047 | (3s): rv64ui-v-slliw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-v-sllw` | cosim-v | default | FAIL | - | - | 5s | 252514192 | (5s): rv64ui-v-sllw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-slt` | cosim-v | default | FAIL | - | - | 3s | 85856700 | (3s): rv64ui-v-slt: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-slti` | cosim-v | default | FAIL | - | - | 4s | 584344394 | (4s): rv64ui-v-slti: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-sltiu` | cosim-v | default | FAIL | - | - | 3s | 264034871 | (3s): rv64ui-v-sltiu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-v-sltu` | cosim-v | default | FAIL | - | - | 3s | 601403730 | (3s): rv64ui-v-sltu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-sra` | cosim-v | default | FAIL | - | - | 4s | 349247149 | (4s): rv64ui-v-sra: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-srai` | cosim-v | default | FAIL | - | - | 2s | 285304889 | (2s): rv64ui-v-srai: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-sraiw` | cosim-v | default | FAIL | - | - | 3s | 981466971 | (3s): rv64ui-v-sraiw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-v-sraw` | cosim-v | default | FAIL | - | - | 3s | 259689299 | (3s): rv64ui-v-sraw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-srl` | cosim-v | default | FAIL | - | - | 2s | 985663126 | (2s): rv64ui-v-srl: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-srli` | cosim-v | default | FAIL | - | - | 3s | 958170830 | (3s): rv64ui-v-srli: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-srliw` | cosim-v | default | FAIL | - | - | 2s | 491650948 | (2s): rv64ui-v-srliw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-v-srlw` | cosim-v | default | FAIL | - | - | 3s | 212915293 | (3s): rv64ui-v-srlw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-st_ld` | cosim-v | default | FAIL | - | - | 2s | 383693458 | (2s): rv64ui-v-st_ld: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64ui-v-sub` | cosim-v | default | FAIL | - | - | 4s | 612830372 | (4s): rv64ui-v-sub: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-subw` | cosim-v | default | FAIL | - | - | 5s | 711823618 | (5s): rv64ui-v-subw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64ui-v-sw` | cosim-v | default | FAIL | - | - | 3s | 988769269 | (3s): rv64ui-v-sw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order=... |
| `rv64ui-v-xor` | cosim-v | default | FAIL | - | - | 3s | 182582156 | (3s): rv64ui-v-xor: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64ui-v-xori` | cosim-v | default | FAIL | - | - | 5s | 697401412 | (5s): rv64ui-v-xori: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-v-div` | cosim-v | default | FAIL | - | - | 3s | 714478591 | (3s): rv64um-v-div: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64um-v-divu` | cosim-v | default | FAIL | - | - | 4s | 791165226 | (4s): rv64um-v-divu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-v-divuw` | cosim-v | default | FAIL | - | - | 3s | 665985643 | (3s): rv64um-v-divuw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64um-v-divw` | cosim-v | default | FAIL | - | - | 3s | 692157197 | (3s): rv64um-v-divw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-v-mul` | cosim-v | default | FAIL | - | - | 4s | 969201511 | (4s): rv64um-v-mul: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64um-v-mulh` | cosim-v | default | FAIL | - | - | 3s | 461866893 | (3s): rv64um-v-mulh: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-v-mulhsu` | cosim-v | default | FAIL | - | - | 3s | 743358260 | (3s): rv64um-v-mulhsu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64um-v-mulhu` | cosim-v | default | FAIL | - | - | 3s | 223533293 | (3s): rv64um-v-mulhu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64um-v-mulw` | cosim-v | default | FAIL | - | - | 2s | 354760574 | (2s): rv64um-v-mulw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-v-rem` | cosim-v | default | FAIL | - | - | 3s | 736636118 | (3s): rv64um-v-rem: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 order... |
| `rv64um-v-remu` | cosim-v | default | FAIL | - | - | 2s | 203482964 | (2s): rv64um-v-remu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64um-v-remuw` | cosim-v | default | FAIL | - | - | 3s | 59377691 | (3s): rv64um-v-remuw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64um-v-remw` | cosim-v | default | FAIL | - | - | 2s | 63249340 | (2s): rv64um-v-remw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 orde... |
| `rv64uzba-v-add_uw` | cosim-v | default | FAIL | - | - | 3s | 466894303 | (3s): rv64uzba-v-add_uw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzba-v-sh1add` | cosim-v | default | FAIL | - | - | 5s | 722514580 | (5s): rv64uzba-v-sh1add: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzba-v-sh1add_uw` | cosim-v | default | FAIL | - | - | 3s | 522357385 | (3s): rv64uzba-v-sh1add_uw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744450... |
| `rv64uzba-v-sh2add` | cosim-v | default | FAIL | - | - | 3s | 159833924 | (3s): rv64uzba-v-sh2add: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzba-v-sh2add_uw` | cosim-v | default | FAIL | - | - | 5s | 462902812 | (5s): rv64uzba-v-sh2add_uw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744450... |
| `rv64uzba-v-sh3add` | cosim-v | default | FAIL | - | - | 3s | 950269644 | (3s): rv64uzba-v-sh3add: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzba-v-sh3add_uw` | cosim-v | default | FAIL | - | - | 4s | 491266453 | (4s): rv64uzba-v-sh3add_uw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744450... |
| `rv64uzba-v-slli_uw` | cosim-v | default | FAIL | - | - | 3s | 53076454 | (3s): rv64uzba-v-slli_uw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64uzbb-v-andn` | cosim-v | default | FAIL | - | - | 3s | 302266711 | (3s): rv64uzbb-v-andn: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-clz` | cosim-v | default | FAIL | - | - | 4s | 304356828 | (4s): rv64uzbb-v-clz: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-v-clzw` | cosim-v | default | FAIL | - | - | 3s | 536500038 | (3s): rv64uzbb-v-clzw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-cpop` | cosim-v | default | FAIL | - | - | 3s | 22637926 | (3s): rv64uzbb-v-cpop: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-cpopw` | cosim-v | default | FAIL | - | - | 2s | 395141055 | (2s): rv64uzbb-v-cpopw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbb-v-ctz` | cosim-v | default | FAIL | - | - | 2s | 306676495 | (2s): rv64uzbb-v-ctz: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-v-ctzw` | cosim-v | default | FAIL | - | - | 3s | 165701768 | (3s): rv64uzbb-v-ctzw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-max` | cosim-v | default | FAIL | - | - | 2s | 255668765 | (2s): rv64uzbb-v-max: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-v-maxu` | cosim-v | default | FAIL | - | - | 3s | 233763954 | (3s): rv64uzbb-v-maxu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-min` | cosim-v | default | FAIL | - | - | 2s | 948349217 | (2s): rv64uzbb-v-min: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-v-minu` | cosim-v | default | FAIL | - | - | 3s | 11457349 | (3s): rv64uzbb-v-minu: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-orc_b` | cosim-v | default | FAIL | - | - | 5s | 232253918 | (5s): rv64uzbb-v-orc_b: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbb-v-orn` | cosim-v | default | FAIL | - | - | 3s | 993260467 | (3s): rv64uzbb-v-orn: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-v-rev8` | cosim-v | default | FAIL | - | - | 3s | 14588255 | (3s): rv64uzbb-v-rev8: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-rol` | cosim-v | default | FAIL | - | - | 5s | 577382953 | (5s): rv64uzbb-v-rol: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-v-rolw` | cosim-v | default | FAIL | - | - | 3s | 861590413 | (3s): rv64uzbb-v-rolw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-ror` | cosim-v | default | FAIL | - | - | 4s | 549899339 | (4s): rv64uzbb-v-ror: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ord... |
| `rv64uzbb-v-rori` | cosim-v | default | FAIL | - | - | 3s | 375024345 | (3s): rv64uzbb-v-rori: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-roriw` | cosim-v | default | FAIL | - | - | 3s | 488071097 | (3s): rv64uzbb-v-roriw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbb-v-rorw` | cosim-v | default | FAIL | - | - | 4s | 154221483 | (4s): rv64uzbb-v-rorw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-sext_b` | cosim-v | default | FAIL | - | - | 3s | 326443380 | (3s): rv64uzbb-v-sext_b: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbb-v-sext_h` | cosim-v | default | FAIL | - | - | 2s | 892087651 | (2s): rv64uzbb-v-sext_h: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbb-v-xnor` | cosim-v | default | FAIL | - | - | 3s | 947294385 | (3s): rv64uzbb-v-xnor: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbb-v-zext_h` | cosim-v | default | FAIL | - | - | 2s | 886420413 | (2s): rv64uzbb-v-zext_h: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbc-v-clmul` | cosim-v | default | FAIL | - | - | 3s | 473943347 | (3s): rv64uzbc-v-clmul: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbc-v-clmulh` | cosim-v | default | FAIL | - | - | 2s | 27604971 | (2s): rv64uzbc-v-clmulh: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbc-v-clmulr` | cosim-v | default | FAIL | - | - | 2s | 348352212 | (2s): rv64uzbc-v-clmulr: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbkb-v-brev8` | cosim-v | default | FAIL | - | - | 2s | 243688950 | (2s): rv64uzbkb-v-brev8: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbkb-v-pack` | cosim-v | default | FAIL | - | - | 2s | 819761950 | (2s): rv64uzbkb-v-pack: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbkb-v-packh` | cosim-v | default | FAIL | - | - | 2s | 798253661 | (2s): rv64uzbkb-v-packh: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbkb-v-packw` | cosim-v | default | FAIL | - | - | 1s | 772488827 | (1s): rv64uzbkb-v-packw: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzbkx-v-xperm4` | cosim-v | default | FAIL | - | - | 2s | 786790347 | (2s): rv64uzbkx-v-xperm4: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64uzbkx-v-xperm8` | cosim-v | default | FAIL | - | - | 3s | 772699733 | (3s): rv64uzbkx-v-xperm8: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073... |
| `rv64uzbs-v-bclr` | cosim-v | default | FAIL | - | - | 2s | 489460307 | (2s): rv64uzbs-v-bclr: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbs-v-bclri` | cosim-v | default | FAIL | - | - | 2s | 579773987 | (2s): rv64uzbs-v-bclri: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbs-v-bext` | cosim-v | default | FAIL | - | - | 2s | 975664435 | (2s): rv64uzbs-v-bext: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbs-v-bexti` | cosim-v | default | FAIL | - | - | 1s | 123910677 | (1s): rv64uzbs-v-bexti: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbs-v-binv` | cosim-v | default | FAIL | - | - | 3s | 670906062 | (3s): rv64uzbs-v-binv: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbs-v-binvi` | cosim-v | default | FAIL | - | - | 2s | 422993438 | (2s): rv64uzbs-v-binvi: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzbs-v-bset` | cosim-v | default | FAIL | - | - | 2s | 280805915 | (2s): rv64uzbs-v-bset: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzbs-v-bseti` | cosim-v | default | FAIL | - | - | 2s | 91796766 | (2s): rv64uzbs-v-bseti: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzfh-v-fadd` | cosim-v | default | FAIL | - | - | 2s | 786332802 | (2s): rv64uzfh-v-fadd: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-v-fclass` | cosim-v | default | FAIL | - | - | 2s | 705614821 | (2s): rv64uzfh-v-fclass: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzfh-v-fcmp` | cosim-v | default | FAIL | - | - | 2s | 563914531 | (2s): rv64uzfh-v-fcmp: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-v-fcvt` | cosim-v | default | FAIL | - | - | 1s | 252733286 | (1s): rv64uzfh-v-fcvt: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-v-fcvt_w` | cosim-v | default | FAIL | - | - | 2s | 582092513 | (2s): rv64uzfh-v-fcvt_w: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 ... |
| `rv64uzfh-v-fdiv` | cosim-v | default | FAIL | - | - | 2s | 506725554 | (2s): rv64uzfh-v-fdiv: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-v-fmadd` | cosim-v | default | FAIL | - | - | 2s | 961129697 | (2s): rv64uzfh-v-fmadd: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 o... |
| `rv64uzfh-v-fmin` | cosim-v | default | FAIL | - | - | 2s | 502966312 | (2s): rv64uzfh-v-fmin: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-v-ldst` | cosim-v | default | FAIL | - | - | 2s | 107848940 | (2s): rv64uzfh-v-ldst: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-v-move` | cosim-v | default | FAIL | - | - | 3s | 486945915 | (3s): rv64uzfh-v-move: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x74445073 or... |
| `rv64uzfh-v-recoding` | cosim-v | default | FAIL | - | - | 2s | 348562887 | (2s): rv64uzfh-v-recoding: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x7444507... |
| `rv64uzicond-v-czero_eqz` | cosim-v | default | FAIL | - | - | 2s | 450355476 | (2s): rv64uzicond-v-czero_eqz: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744... |
| `rv64uzicond-v-czero_nez` | cosim-v | default | FAIL | - | - | 2s | 499359627 | (2s): rv64uzicond-v-czero_nez: MISMATCH at commit 36 pc=0x80000094 field=trap.tval | [1] trap.tval: CL 0x0 | Spike 0x744... |

_Full 4139-test table: see the `pyo3-ci-report.md` asset._
