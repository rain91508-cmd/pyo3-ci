# pyo3 CI report

|  |  |
|---|---|
| **Result** | **PASS** |
| Run | [rain91508-cmd/pyo3-ci#46014509943](https://github.com/rain91508-cmd/pyo3-ci/actions/runs/46014509943) |
| Commit | `71c3e25da2` (pycpu) |
| Triggered by | rain91508-cmd |
| Base seed | 1795789396, 1795789420, 1795789438, 1795789439, 1795789440, 1795789442, 1795789444, 1795789445, 1795789446, 1795789448, 1795789454, 1795789498, 1795789502, 1795789527, 1795789534, 1795789541, 1795789549, 1795789554 |
| Testbench | default |
| Generated | 2026-11-27 14:36 UTC |

## Suites

| Suite | Shard | TB | PASS | FAIL | TIMEOUT | ERROR | MISSING | XFAIL-NOTRUN | Total | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| cosim-p | none | default | 198 | 0 | 0+0 | 0 | 0 | 0 | 198 | PASS |
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
| **all** |  |  | 370 | 0 | 0+0 | 0 | 0 | 0 | 370 | PASS |

## Failures

None.

## All 370 results

<details>
<summary>Full per-test table</summary>

| Test | Suite | TB | Status | cycles | wall |
|---|---|---|---|---|---|
| rv64mi-p-breakpoint | cosim-p | default | PASS | - | 16 |
| rv64mi-p-csr | cosim-p | default | PASS | - | 16 |
| rv64mi-p-illegal | cosim-p | default | PASS | - | 17 |
| rv64mi-p-instret_overflow | cosim-p | default | PASS | - | 8 |
| rv64mi-p-ld-misaligned | cosim-p | default | PASS | - | 8 |
| rv64mi-p-lh-misaligned | cosim-p | default | PASS | - | 6 |
| rv64mi-p-lw-misaligned | cosim-p | default | PASS | - | 7 |
| rv64mi-p-ma_addr | cosim-p | default | PASS | - | 10 |
| rv64mi-p-ma_fetch | cosim-p | default | PASS | - | 8 |
| rv64mi-p-mcsr | cosim-p | default | PASS | - | 8 |
| rv64mi-p-pmpaddr | cosim-p | default | PASS | - | 7 |
| rv64mi-p-sbreak | cosim-p | default | PASS | - | 7 |
| rv64mi-p-scall | cosim-p | default | PASS | - | 7 |
| rv64mi-p-sd-misaligned | cosim-p | default | PASS | - | 8 |
| rv64mi-p-sh-misaligned | cosim-p | default | PASS | - | 7 |
| rv64mi-p-sw-misaligned | cosim-p | default | PASS | - | 7 |
| rv64mi-p-zicntr | cosim-p | default | PASS | - | 7 |
| rv64mzicbo-p-zero | cosim-p | default | PASS | - | 7 |
| rv64si-p-csr | cosim-p | default | PASS | - | 12 |
| rv64si-p-dirty | cosim-p | default | PASS | - | 11 |
| rv64si-p-icache-alias | cosim-p | default | PASS | - | 12 |
| rv64si-p-ma_fetch | cosim-p | default | PASS | - | 7 |
| rv64si-p-sbreak | cosim-p | default | PASS | - | 7 |
| rv64si-p-scall | cosim-p | default | PASS | - | 7 |
| rv64si-p-wfi | cosim-p | default | PASS | - | 7 |
| rv64ssvnapot-p-napot | cosim-p | default | PASS | - | 10 |
| rv64ua-p-amoadd_d | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amoadd_w | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amoand_d | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amoand_w | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amomax_d | cosim-p | default | PASS | - | 6 |
| rv64ua-p-amomax_w | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amomaxu_d | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amomaxu_w | cosim-p | default | PASS | - | 6 |
| rv64ua-p-amomin_d | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amomin_w | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amominu_d | cosim-p | default | PASS | - | 6 |
| rv64ua-p-amominu_w | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amoor_d | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amoor_w | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amoswap_d | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amoswap_w | cosim-p | default | PASS | - | 7 |
| rv64ua-p-amoxor_d | cosim-p | default | PASS | - | 6 |
| rv64ua-p-amoxor_w | cosim-p | default | PASS | - | 7 |
| rv64ua-p-lrsc | cosim-p | default | PASS | - | 105 |
| rv64uc-p-rvc | cosim-p | default | PASS | - | 8 |
| rv64ud-p-fadd | cosim-p | default | PASS | - | 10 |
| rv64ud-p-fclass | cosim-p | default | PASS | - | 8 |
| rv64ud-p-fcmp | cosim-p | default | PASS | - | 12 |
| rv64ud-p-fcvt | cosim-p | default | PASS | - | 10 |
| rv64ud-p-fcvt_w | cosim-p | default | PASS | - | 20 |
| rv64ud-p-fdiv | cosim-p | default | PASS | - | 10 |
| rv64ud-p-fmadd | cosim-p | default | PASS | - | 11 |
| rv64ud-p-fmin | cosim-p | default | PASS | - | 13 |
| rv64ud-p-ldst | cosim-p | default | PASS | - | 7 |
| rv64ud-p-move | cosim-p | default | PASS | - | 17 |
| rv64ud-p-recoding | cosim-p | default | PASS | - | 8 |
| rv64ud-p-structural | cosim-p | default | PASS | - | 10 |
| rv64uf-p-fadd | cosim-p | default | PASS | - | 10 |
| rv64uf-p-fclass | cosim-p | default | PASS | - | 8 |
| rv64uf-p-fcmp | cosim-p | default | PASS | - | 11 |
| rv64uf-p-fcvt | cosim-p | default | PASS | - | 9 |
| rv64uf-p-fcvt_w | cosim-p | default | PASS | - | 19 |
| rv64uf-p-fdiv | cosim-p | default | PASS | - | 10 |
| rv64uf-p-fmadd | cosim-p | default | PASS | - | 11 |
| rv64uf-p-fmin | cosim-p | default | PASS | - | 13 |
| rv64uf-p-ldst | cosim-p | default | PASS | - | 7 |
| rv64uf-p-move | cosim-p | default | PASS | - | 11 |
| rv64uf-p-recoding | cosim-p | default | PASS | - | 8 |
| rv64ui-p-add | cosim-p | default | PASS | - | 15 |
| rv64ui-p-addi | cosim-p | default | PASS | - | 10 |
| rv64ui-p-addiw | cosim-p | default | PASS | - | 10 |
| rv64ui-p-addw | cosim-p | default | PASS | - | 16 |
| rv64ui-p-and | cosim-p | default | PASS | - | 16 |
| rv64ui-p-andi | cosim-p | default | PASS | - | 10 |
| rv64ui-p-auipc | cosim-p | default | PASS | - | 6 |
| rv64ui-p-beq | cosim-p | default | PASS | - | 13 |
| rv64ui-p-bge | cosim-p | default | PASS | - | 14 |
| rv64ui-p-bgeu | cosim-p | default | PASS | - | 16 |
| rv64ui-p-blt | cosim-p | default | PASS | - | 13 |
| rv64ui-p-bltu | cosim-p | default | PASS | - | 14 |
| rv64ui-p-bne | cosim-p | default | PASS | - | 14 |
| rv64ui-p-fence_i | cosim-p | default | PASS | - | 12 |
| rv64ui-p-jal | cosim-p | default | PASS | - | 7 |
| rv64ui-p-jalr | cosim-p | default | PASS | - | 10 |
| rv64ui-p-lb | cosim-p | default | PASS | - | 11 |
| rv64ui-p-lbu | cosim-p | default | PASS | - | 10 |
| rv64ui-p-ld | cosim-p | default | PASS | - | 13 |
| rv64ui-p-ld_st | cosim-p | default | PASS | - | 29 |
| rv64ui-p-lh | cosim-p | default | PASS | - | 11 |
| rv64ui-p-lhu | cosim-p | default | PASS | - | 11 |
| rv64ui-p-lui | cosim-p | default | PASS | - | 7 |
| rv64ui-p-lw | cosim-p | default | PASS | - | 11 |
| rv64ui-p-lwu | cosim-p | default | PASS | - | 11 |
| rv64ui-p-ma_data | cosim-p | default | PASS | - | 64 |
| rv64ui-p-or | cosim-p | default | PASS | - | 16 |
| rv64ui-p-ori | cosim-p | default | PASS | - | 10 |
| rv64ui-p-sb | cosim-p | default | PASS | - | 14 |
| rv64ui-p-sd | cosim-p | default | PASS | - | 17 |
| rv64ui-p-sh | cosim-p | default | PASS | - | 14 |
| rv64ui-p-simple | cosim-p | default | PASS | - | 6 |
| rv64ui-p-sll | cosim-p | default | PASS | - | 16 |
| rv64ui-p-slli | cosim-p | default | PASS | - | 11 |
| rv64ui-p-slliw | cosim-p | default | PASS | - | 10 |
| rv64ui-p-sllw | cosim-p | default | PASS | - | 15 |
| rv64ui-p-slt | cosim-p | default | PASS | - | 15 |
| rv64ui-p-slti | cosim-p | default | PASS | - | 10 |
| rv64ui-p-sltiu | cosim-p | default | PASS | - | 10 |
| rv64ui-p-sltu | cosim-p | default | PASS | - | 14 |
| rv64ui-p-sra | cosim-p | default | PASS | - | 14 |
| rv64ui-p-srai | cosim-p | default | PASS | - | 10 |
| rv64ui-p-sraiw | cosim-p | default | PASS | - | 10 |
| rv64ui-p-sraw | cosim-p | default | PASS | - | 15 |
| rv64ui-p-srl | cosim-p | default | PASS | - | 16 |
| rv64ui-p-srli | cosim-p | default | PASS | - | 10 |
| rv64ui-p-srliw | cosim-p | default | PASS | - | 10 |
| rv64ui-p-srlw | cosim-p | default | PASS | - | 15 |
| rv64ui-p-st_ld | cosim-p | default | PASS | - | 12 |
| rv64ui-p-sub | cosim-p | default | PASS | - | 14 |
| rv64ui-p-subw | cosim-p | default | PASS | - | 14 |
| rv64ui-p-sw | cosim-p | default | PASS | - | 13 |
| rv64ui-p-xor | cosim-p | default | PASS | - | 16 |
| rv64ui-p-xori | cosim-p | default | PASS | - | 9 |
| rv64um-p-div | cosim-p | default | PASS | - | 7 |
| rv64um-p-divu | cosim-p | default | PASS | - | 7 |
| rv64um-p-divuw | cosim-p | default | PASS | - | 7 |
| rv64um-p-divw | cosim-p | default | PASS | - | 7 |
| rv64um-p-mul | cosim-p | default | PASS | - | 14 |
| rv64um-p-mulh | cosim-p | default | PASS | - | 14 |
| rv64um-p-mulhsu | cosim-p | default | PASS | - | 14 |
| rv64um-p-mulhu | cosim-p | default | PASS | - | 14 |
| rv64um-p-mulw | cosim-p | default | PASS | - | 12 |
| rv64um-p-rem | cosim-p | default | PASS | - | 6 |
| rv64um-p-remu | cosim-p | default | PASS | - | 6 |
| rv64um-p-remuw | cosim-p | default | PASS | - | 7 |
| rv64um-p-remw | cosim-p | default | PASS | - | 7 |
| rv64uzba-p-add_uw | cosim-p | default | PASS | - | 13 |
| rv64uzba-p-sh1add | cosim-p | default | PASS | - | 13 |
| rv64uzba-p-sh1add_uw | cosim-p | default | PASS | - | 13 |
| rv64uzba-p-sh2add | cosim-p | default | PASS | - | 14 |
| rv64uzba-p-sh2add_uw | cosim-p | default | PASS | - | 14 |
| rv64uzba-p-sh3add | cosim-p | default | PASS | - | 13 |
| rv64uzba-p-sh3add_uw | cosim-p | default | PASS | - | 14 |
| rv64uzba-p-slli_uw | cosim-p | default | PASS | - | 9 |
| rv64uzbb-p-andn | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-clz | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-clzw | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-cpop | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-cpopw | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-ctz | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-ctzw | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-max | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-maxu | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-min | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-minu | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-orc_b | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-orn | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-rev8 | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-rol | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-rolw | cosim-p | default | PASS | - | 14 |
| rv64uzbb-p-ror | cosim-p | default | PASS | - | 14 |
| rv64uzbb-p-rori | cosim-p | default | PASS | - | 10 |
| rv64uzbb-p-roriw | cosim-p | default | PASS | - | 9 |
| rv64uzbb-p-rorw | cosim-p | default | PASS | - | 13 |
| rv64uzbb-p-sext_b | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-sext_h | cosim-p | default | PASS | - | 8 |
| rv64uzbb-p-xnor | cosim-p | default | PASS | - | 14 |
| rv64uzbb-p-zext_h | cosim-p | default | PASS | - | 8 |
| rv64uzbc-p-clmul | cosim-p | default | PASS | - | 13 |
| rv64uzbc-p-clmulh | cosim-p | default | PASS | - | 13 |
| rv64uzbc-p-clmulr | cosim-p | default | PASS | - | 13 |
| rv64uzbkb-p-brev8 | cosim-p | default | PASS | - | 8 |
| rv64uzbkb-p-pack | cosim-p | default | PASS | - | 15 |
| rv64uzbkb-p-packh | cosim-p | default | PASS | - | 14 |
| rv64uzbkb-p-packw | cosim-p | default | PASS | - | 13 |
| rv64uzbkx-p-xperm4 | cosim-p | default | PASS | - | 14 |
| rv64uzbkx-p-xperm8 | cosim-p | default | PASS | - | 19 |
| rv64uzbs-p-bclr | cosim-p | default | PASS | - | 15 |
| rv64uzbs-p-bclri | cosim-p | default | PASS | - | 9 |
| rv64uzbs-p-bext | cosim-p | default | PASS | - | 15 |
| rv64uzbs-p-bexti | cosim-p | default | PASS | - | 10 |
| rv64uzbs-p-binv | cosim-p | default | PASS | - | 15 |
| rv64uzbs-p-binvi | cosim-p | default | PASS | - | 10 |
| rv64uzbs-p-bset | cosim-p | default | PASS | - | 15 |
| rv64uzbs-p-bseti | cosim-p | default | PASS | - | 10 |
| rv64uzfh-p-fadd | cosim-p | default | PASS | - | 9 |
| rv64uzfh-p-fclass | cosim-p | default | PASS | - | 7 |
| rv64uzfh-p-fcmp | cosim-p | default | PASS | - | 8 |
| rv64uzfh-p-fcvt | cosim-p | default | PASS | - | 9 |
| rv64uzfh-p-fcvt_w | cosim-p | default | PASS | - | 16 |
| rv64uzfh-p-fdiv | cosim-p | default | PASS | - | 9 |
| rv64uzfh-p-fmadd | cosim-p | default | PASS | - | 10 |
| rv64uzfh-p-fmin | cosim-p | default | PASS | - | 13 |
| rv64uzfh-p-ldst | cosim-p | default | PASS | - | 7 |
| rv64uzfh-p-move | cosim-p | default | PASS | - | 11 |
| rv64uzfh-p-recoding | cosim-p | default | PASS | - | 7 |
| rv64uzicond-p-czero_eqz | cosim-p | default | PASS | - | 12 |
| rv64uzicond-p-czero_nez | cosim-p | default | PASS | - | 9 |
| rv64ua-v-amoadd_d | cosim-v | default | PASS | - | 130 |
| rv64ua-v-amoadd_w | cosim-v | default | PASS | - | 82 |
| rv64ua-v-amoand_d | cosim-v | default | PASS | - | 124 |
| rv64ua-v-amoand_w | cosim-v | default | PASS | - | 83 |
| rv64ua-v-amomax_d | cosim-v | default | PASS | - | 123 |
| rv64ua-v-amomax_w | cosim-v | default | PASS | - | 83 |
| rv64ua-v-amomaxu_d | cosim-v | default | PASS | - | 81 |
| rv64ua-v-amomaxu_w | cosim-v | default | PASS | - | 132 |
| rv64ua-v-amomin_d | cosim-v | default | PASS | - | 84 |
| rv64ua-v-amomin_w | cosim-v | default | PASS | - | 104 |
| rv64ua-v-amominu_d | cosim-v | default | PASS | - | 102 |
| rv64ua-v-amominu_w | cosim-v | default | PASS | - | 101 |
| rv64ua-v-amoor_d | cosim-v | default | PASS | - | 83 |
| rv64ua-v-amoor_w | cosim-v | default | PASS | - | 82 |
| rv64ua-v-amoswap_d | cosim-v | default | PASS | - | 83 |
| rv64ua-v-amoswap_w | cosim-v | default | PASS | - | 74 |
| rv64ua-v-amoxor_d | cosim-v | default | PASS | - | 80 |
| rv64ua-v-amoxor_w | cosim-v | default | PASS | - | 90 |
| rv64ua-v-lrsc | cosim-v | default | PASS | - | 251 |
| rv64uc-v-rvc | cosim-v | default | PASS | - | 126 |
| rv64ud-v-fadd | cosim-v | default | PASS | - | 132 |
| rv64ud-v-fclass | cosim-v | default | PASS | - | 46 |
| rv64ud-v-fcmp | cosim-v | default | PASS | - | 136 |
| rv64ud-v-fcvt | cosim-v | default | PASS | - | 86 |
| rv64ud-v-fcvt_w | cosim-v | default | PASS | - | 139 |
| rv64ud-v-fdiv | cosim-v | default | PASS | - | 145 |
| rv64ud-v-fmadd | cosim-v | default | PASS | - | 90 |
| rv64ud-v-fmin | cosim-v | default | PASS | - | 113 |
| rv64ud-v-ldst | cosim-v | default | PASS | - | 108 |
| rv64ud-v-move | cosim-v | default | PASS | - | 128 |
| rv64ud-v-recoding | cosim-v | default | PASS | - | 84 |
| rv64ud-v-structural | cosim-v | default | PASS | - | 48 |
| rv64uf-v-fadd | cosim-v | default | PASS | - | 89 |
| rv64uf-v-fclass | cosim-v | default | PASS | - | 41 |
| rv64uf-v-fcmp | cosim-v | default | PASS | - | 87 |
| rv64uf-v-fcvt | cosim-v | default | PASS | - | 95 |
| rv64uf-v-fcvt_w | cosim-v | default | PASS | - | 231 |
| rv64uf-v-fdiv | cosim-v | default | PASS | - | 88 |
| rv64uf-v-fmadd | cosim-v | default | PASS | - | 135 |
| rv64uf-v-fmin | cosim-v | default | PASS | - | 91 |
| rv64uf-v-ldst | cosim-v | default | PASS | - | 122 |
| rv64uf-v-move | cosim-v | default | PASS | - | 49 |
| rv64uf-v-recoding | cosim-v | default | PASS | - | 84 |
| rv64ui-v-add | cosim-v | default | PASS | - | 83 |
| rv64ui-v-addi | cosim-v | default | PASS | - | 49 |
| rv64ui-v-addiw | cosim-v | default | PASS | - | 61 |
| rv64ui-v-addw | cosim-v | default | PASS | - | 65 |
| rv64ui-v-and | cosim-v | default | PASS | - | 62 |
| rv64ui-v-andi | cosim-v | default | PASS | - | 49 |
| rv64ui-v-auipc | cosim-v | default | PASS | - | 45 |
| rv64ui-v-beq | cosim-v | default | PASS | - | 50 |
| rv64ui-v-bge | cosim-v | default | PASS | - | 45 |
| rv64ui-v-bgeu | cosim-v | default | PASS | - | 51 |
| rv64ui-v-blt | cosim-v | default | PASS | - | 54 |
| rv64ui-v-bltu | cosim-v | default | PASS | - | 82 |
| rv64ui-v-bne | cosim-v | default | PASS | - | 50 |
| rv64ui-v-fence_i | cosim-v | default | PASS | - | 127 |
| rv64ui-v-jal | cosim-v | default | PASS | - | 45 |
| rv64ui-v-jalr | cosim-v | default | PASS | - | 73 |
| rv64ui-v-lb | cosim-v | default | PASS | - | 87 |
| rv64ui-v-lbu | cosim-v | default | PASS | - | 85 |
| rv64ui-v-ld | cosim-v | default | PASS | - | 145 |
| rv64ui-v-ld_st | cosim-v | default | PASS | - | 188 |
| rv64ui-v-lh | cosim-v | default | PASS | - | 110 |
| rv64ui-v-lhu | cosim-v | default | PASS | - | 113 |
| rv64ui-v-lui | cosim-v | default | PASS | - | 56 |
| rv64ui-v-lw | cosim-v | default | PASS | - | 90 |
| rv64ui-v-lwu | cosim-v | default | PASS | - | 87 |
| rv64ui-v-ma_data | cosim-v | default | PASS | - | 188 |
| rv64ui-v-or | cosim-v | default | PASS | - | 48 |
| rv64ui-v-ori | cosim-v | default | PASS | - | 47 |
| rv64ui-v-sb | cosim-v | default | PASS | - | 95 |
| rv64ui-v-sd | cosim-v | default | PASS | - | 211 |
| rv64ui-v-sh | cosim-v | default | PASS | - | 86 |
| rv64ui-v-simple | cosim-v | default | PASS | - | 67 |
| rv64ui-v-sll | cosim-v | default | PASS | - | 87 |
| rv64ui-v-slli | cosim-v | default | PASS | - | 68 |
| rv64ui-v-slliw | cosim-v | default | PASS | - | 46 |
| rv64ui-v-sllw | cosim-v | default | PASS | - | 86 |
| rv64ui-v-slt | cosim-v | default | PASS | - | 84 |
| rv64ui-v-slti | cosim-v | default | PASS | - | 47 |
| rv64ui-v-sltiu | cosim-v | default | PASS | - | 60 |
| rv64ui-v-sltu | cosim-v | default | PASS | - | 60 |
| rv64ui-v-sra | cosim-v | default | PASS | - | 60 |
| rv64ui-v-srai | cosim-v | default | PASS | - | 48 |
| rv64ui-v-sraiw | cosim-v | default | PASS | - | 47 |
| rv64ui-v-sraw | cosim-v | default | PASS | - | 90 |
| rv64ui-v-srl | cosim-v | default | PASS | - | 73 |
| rv64ui-v-srli | cosim-v | default | PASS | - | 46 |
| rv64ui-v-srliw | cosim-v | default | PASS | - | 51 |
| rv64ui-v-srlw | cosim-v | default | PASS | - | 144 |
| rv64ui-v-st_ld | cosim-v | default | PASS | - | 117 |
| rv64ui-v-sub | cosim-v | default | PASS | - | 77 |
| rv64ui-v-subw | cosim-v | default | PASS | - | 50 |
| rv64ui-v-sw | cosim-v | default | PASS | - | 133 |
| rv64ui-v-xor | cosim-v | default | PASS | - | 50 |
| rv64ui-v-xori | cosim-v | default | PASS | - | 46 |
| rv64um-v-div | cosim-v | default | PASS | - | 75 |
| rv64um-v-divu | cosim-v | default | PASS | - | 45 |
| rv64um-v-divuw | cosim-v | default | PASS | - | 57 |
| rv64um-v-divw | cosim-v | default | PASS | - | 53 |
| rv64um-v-mul | cosim-v | default | PASS | - | 64 |
| rv64um-v-mulh | cosim-v | default | PASS | - | 50 |
| rv64um-v-mulhsu | cosim-v | default | PASS | - | 50 |
| rv64um-v-mulhu | cosim-v | default | PASS | - | 51 |
| rv64um-v-mulw | cosim-v | default | PASS | - | 44 |
| rv64um-v-rem | cosim-v | default | PASS | - | 44 |
| rv64um-v-remu | cosim-v | default | PASS | - | 48 |
| rv64um-v-remuw | cosim-v | default | PASS | - | 71 |
| rv64um-v-remw | cosim-v | default | PASS | - | 45 |
| rv64uzba-v-add_uw | cosim-v | default | PASS | - | 76 |
| rv64uzba-v-sh1add | cosim-v | default | PASS | - | 50 |
| rv64uzba-v-sh1add_uw | cosim-v | default | PASS | - | 77 |
| rv64uzba-v-sh2add | cosim-v | default | PASS | - | 49 |
| rv64uzba-v-sh2add_uw | cosim-v | default | PASS | - | 49 |
| rv64uzba-v-sh3add | cosim-v | default | PASS | - | 82 |
| rv64uzba-v-sh3add_uw | cosim-v | default | PASS | - | 50 |
| rv64uzba-v-slli_uw | cosim-v | default | PASS | - | 60 |
| rv64uzbb-v-andn | cosim-v | default | PASS | - | 59 |
| rv64uzbb-v-clz | cosim-v | default | PASS | - | 55 |
| rv64uzbb-v-clzw | cosim-v | default | PASS | - | 45 |
| rv64uzbb-v-cpop | cosim-v | default | PASS | - | 45 |
| rv64uzbb-v-cpopw | cosim-v | default | PASS | - | 47 |
| rv64uzbb-v-ctz | cosim-v | default | PASS | - | 41 |
| rv64uzbb-v-ctzw | cosim-v | default | PASS | - | 43 |
| rv64uzbb-v-max | cosim-v | default | PASS | - | 51 |
| rv64uzbb-v-maxu | cosim-v | default | PASS | - | 69 |
| rv64uzbb-v-min | cosim-v | default | PASS | - | 50 |
| rv64uzbb-v-minu | cosim-v | default | PASS | - | 77 |
| rv64uzbb-v-orc_b | cosim-v | default | PASS | - | 45 |
| rv64uzbb-v-orn | cosim-v | default | PASS | - | 132 |
| rv64uzbb-v-rev8 | cosim-v | default | PASS | - | 46 |
| rv64uzbb-v-rol | cosim-v | default | PASS | - | 74 |
| rv64uzbb-v-rolw | cosim-v | default | PASS | - | 118 |
| rv64uzbb-v-ror | cosim-v | default | PASS | - | 90 |
| rv64uzbb-v-rori | cosim-v | default | PASS | - | 60 |
| rv64uzbb-v-roriw | cosim-v | default | PASS | - | 51 |
| rv64uzbb-v-rorw | cosim-v | default | PASS | - | 41 |
| rv64uzbb-v-sext_b | cosim-v | default | PASS | - | 45 |
| rv64uzbb-v-sext_h | cosim-v | default | PASS | - | 43 |
| rv64uzbb-v-xnor | cosim-v | default | PASS | - | 69 |
| rv64uzbb-v-zext_h | cosim-v | default | PASS | - | 31 |
| rv64uzbc-v-clmul | cosim-v | default | PASS | - | 35 |
| rv64uzbc-v-clmulh | cosim-v | default | PASS | - | 53 |
| rv64uzbc-v-clmulr | cosim-v | default | PASS | - | 66 |
| rv64uzbkb-v-brev8 | cosim-v | default | PASS | - | 46 |
| rv64uzbkb-v-pack | cosim-v | default | PASS | - | 90 |
| rv64uzbkb-v-packh | cosim-v | default | PASS | - | 45 |
| rv64uzbkb-v-packw | cosim-v | default | PASS | - | 78 |
| rv64uzbkx-v-xperm4 | cosim-v | default | PASS | - | 72 |
| rv64uzbkx-v-xperm8 | cosim-v | default | PASS | - | 76 |
| rv64uzbs-v-bclr | cosim-v | default | PASS | - | 123 |
| rv64uzbs-v-bclri | cosim-v | default | PASS | - | 47 |
| rv64uzbs-v-bext | cosim-v | default | PASS | - | 90 |
| rv64uzbs-v-bexti | cosim-v | default | PASS | - | 49 |
| rv64uzbs-v-binv | cosim-v | default | PASS | - | 74 |
| rv64uzbs-v-binvi | cosim-v | default | PASS | - | 42 |
| rv64uzbs-v-bset | cosim-v | default | PASS | - | 59 |
| rv64uzbs-v-bseti | cosim-v | default | PASS | - | 32 |
| rv64uzfh-v-fadd | cosim-v | default | PASS | - | 50 |
| rv64uzfh-v-fclass | cosim-v | default | PASS | - | 39 |
| rv64uzfh-v-fcmp | cosim-v | default | PASS | - | 72 |
| rv64uzfh-v-fcvt | cosim-v | default | PASS | - | 89 |
| rv64uzfh-v-fcvt_w | cosim-v | default | PASS | - | 104 |
| rv64uzfh-v-fdiv | cosim-v | default | PASS | - | 82 |
| rv64uzfh-v-fmadd | cosim-v | default | PASS | - | 57 |
| rv64uzfh-v-fmin | cosim-v | default | PASS | - | 97 |
| rv64uzfh-v-ldst | cosim-v | default | PASS | - | 52 |
| rv64uzfh-v-move | cosim-v | default | PASS | - | 40 |
| rv64uzfh-v-recoding | cosim-v | default | PASS | - | 97 |
| rv64uzicond-v-czero_eqz | cosim-v | default | PASS | - | 45 |
| rv64uzicond-v-czero_nez | cosim-v | default | PASS | - | 43 |

</details>
