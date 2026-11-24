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

_Full 4184-test table: see the `pyo3-ci-report.md` asset._
