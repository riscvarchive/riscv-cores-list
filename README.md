# RISC-V Cores and SoC Overview

This document captures the status of various cores and SoCs that endeavor to implement the RISC-V specification. Note that none of these cores/SoCs have passed the in-development RISC-V compliance suite.

Please add to the list and fix inaccuracies.

## Cores

Name | Supplier | Links | Priv. spec | User spec | License
---- | -------- | ----- | ---------- | --------- | -------
rocket | SiFive, UCB Bar| [GitHub](https://github.com/freechipsproject/rocket-chip) | 1.11-draft | 2.3-draft | BSD
freedom | SiFive | [GitHub](https://github.com/sifive/freedom) | 1.11-draft | 2.3-draft | BSD
Berkeley Out-of-Order Machine (BOOM) | Esperanto, UCB Bar | [GitHub](https://github.com/ucb-bar/riscv-boom) | 1.11-draft | 2.3-draft | BSD
ORCA | VectorBlox | [GitHub](https://github.com/vectorblox/orca) |  | RV32IM | BSD
RI5CY | ETH Zurich, Università di Bologna | [GitHub](https://github.com/pulp-platform/riscv) |  | RV32IMC | Solderpad Hardware License v. 0.51
Zero-riscy | ETH Zurich, Università di Bologna | [GitHub](https://github.com/pulp-platform/zero-riscy) |  | RV32IMC | Solderpad Hardware License v. 0.51
Ariane | ETH Zurich, Università di Bologna | [Website](https://pulp-platform.github.io/ariane/docs/home/),[GitHub](https://github.com/pulp-platform/ariane) | 1.11-draft | RV64GC | Solderpad Hardware License v. 0.51
Riscy Processors | MIT CSAIL CSG | [Website](http://csg.csail.mit.edu/riscy-e/),[GitHub](https://github.com/csail-csg/riscy) | | | MIT
RiscyOO | MIT CSAIL CSG | [GitHub](https://github.com/csail-csg/riscy-OOO) | 1.10 | RV64IMAFD | MIT
Lizard | Cornell CSL BRG | [GitHub](https://github.com/cornell-brg/lizard) | | RV64IM | BSD
Minerva | LambdaConcept | [GitHub](https://github.com/lambdaconcept/minerva) | 1.10 | RV32I | BSD
OPenV/mriscv | OnChipUIS | [GitHub](https://github.com/onchipuis/mriscv) | | RV32I(?) | MIT
VexRiscv | SpinalHDL | [GitHub](https://github.com/SpinalHDL/VexRiscv) | | RV32I[M][C] | MIT
Roa Logic RV12 | Roa Logic | [GitHub](https://github.com/roalogic/RV12) | 1.9.1 | 2.1 | Non-Commercial License
SCR1 | Syntacore | [GitHub]( https://github.com/syntacore/scr1) | 1.10 | 2.2, RV32I/E[MC] | Solderpad Hardware License v. 0.51
Hummingbird E200 | Bob Hu | [GitHub](https://github.com/SI-RISCV/e200_opensource) | 1.10 | 2.2, RV32IMAC | Apache 2.0
Shakti | IIT Madras | [Website](http://shakti.org.in/),[GitLab](https://gitlab.com/shaktiproject) | 1.11 | 2.2, RV64IMAFDC | BSD
ReonV | Lucas Castro | [GitHub](https://github.com/lcbcFoo/ReonV) | | | GPL v3
PicoRV32 | Clifford Wolf | [GitHub](https://github.com/cliffordwolf/picorv32) | | RV32I/E[MC] | ISC
MR1 | Tom Verbeure | [GitHub](https://github.com/tomverbeure/mr1) | | RV32I | Unlicense
SERV | Olof Kindgren | [GitHub](https://github.com/olofk/serv) | | RV32I | ISC
SweRV EH1 | Western Digital Corporation | [GitHub](https://github.com/westerndigitalcorporation/swerv_eh1) | | RV32IMC | Apache 2.0
Reve-R | Gavin Stark | [GitHub](https://github.com/atthecodeface/cdl_hardware) | 1.10 | RV32IMAC | Apache 2.0
Bk3 | Codasip | [Website](http://www.codasip.com) | 1.10 | Bk3-32EMC-id / Bk3-32IMC-pid / Bk3-32IMC-IDpid / Bk3-32IMFC-pid / Bk3-32IMFC-IDpid | Codasip EULA
Bk5 | Codasip | [Website](http://www.codasip.com) | 1.10 | Bk5-32IMC-pbid / Bk5-32IMC-IDpbid / Bk5-32IMFC-pbid / Bk5-32IMFC-IDpbid / Bk5-64IMFDC-IDpbid | Codasip EULA
Bk7 | Codasip | [Website](http://www.codasip.com) | 1.10 | Bk7-64GC-IDbid | Codasip EULA

## SoC platforms

Name | Supplier | Links | Core | License
---- | -------- | ----- | ---- | -------
Rocket Chip | SiFive, UCB BAR | [GitHub](https://github.com/freechipsproject/rocket-chip),[Simulator](https://fires.im) | Rocket | BSD
LowRISC | LowRISC CIC | [GitHub](https://github.com/lowRISC/lowrisc-chip) | RV32IM | BSD
PULPino | ETH Zurich, Università di Bologna | [Website](http://www.pulp-platform.org),[GitHub](https://github.com/pulp-platform/pulpino) | RI5CY, Zero-riscy | Solderpad Hardware License v. 0.51
PULPissimo | ETH Zurich, Università di Bologna | [Website](http://www.pulp-platform.org),[GitHub](https://github.com/pulp-platform/pulpissimo) | RI5CY, Zero-riscy | Solderpad Hardware License v. 0.51
Ariane SoC | ETH Zurich, Università di Bologna | [Website](http://www.pulp-platform.org),[GitHub](https://github.com/pulp-platform/ariane) | Ariane | Solderpad Hardware License v. 0.51
OPENPULP | ETH Zurich, Università di Bologna | [Website](http://www.pulp-platform.org),[GitHub](https://github.com/pulp-platform/pulp) | RI5CY, Zero-riscy | Solderpad Hardware License v. 0.51
HERO | ETH Zurich, Università di Bologna | [Website](http://www.pulp-platform.org),[GitHub](https://github.com/pulp-platform/bigpulp) | RI5CY, Zero-riscy | Solderpad Hardware License v. 0.51
OpenPiton + Ariane | Princeton Parallel Group, ETH Zurich, Università di Bologna | [Website](https://parallel.princeton.edu/openpiton/),[GitHub](https://github.com/PrincetonUniversity/openpiton) | Ariane | Solderpad Hardware License v. 0.51, BSD
Briey | SpinalHDL | [GitHub](https://github.com/SpinalHDL/VexRiscv#briey-soc) | VexRiscv | MIT
Riscy | AleksandarKostovic | [GitHub](https://github.com/AleksandarKostovic/Riscy-SoC) | RV64I | MIT
Raven | RTimothyEdwards, mkkassem (efabless.com) | [GitHub](https://github.com/efabless/picorv32-soc-raven) | PicoRV32 | ISC
PicoSoC | Clifford Wolf | [GitHub](https://github.com/cliffordwolf/picorv32/tree/master/picosoc) | PicoRV32 | ISC
Icicle | Graham Edgecombe | [GitHub](https://github.com/grahamedgecombe/icicle) | RV32I | ISC

## SoCs

Include a chip if it has been fabricated and is either available for sale, available for preorder, or running production workloads internally, and if it has at least one RISC-V hard core (no FPGAs, but non-"SoC" products
 with controller cores are allowed).

Name | Supplier | Links | Core | ISA | OS | Devkit | Availability
---- | -------- | ----- | ---- | --- | -- | ------ | ------------
FE310-G000 | SiFive | [Datasheet](https://static.dev.sifive.com/FE310-G000.pdf) | E31 | RV32IMAC | RTOS | [HiFive1](https://www.sifive.com/boards/hifive1) | public since 2016Q4
FE310-G002 | SiFive | [Product page](https://www.sifive.com/boards/hifive1)  | E31 | RV32IMAC | RTOS | [HiFive1 Rev B](https://www.sifive.com/boards/hifive1-rev-b) | announced 2019Q1, available for preorder
Freedom U540 | SiFive | [Product page](https://www.sifive.com/products/hifive-unleashed/) | U54 (4 cores), E51 (1 management core) | RV64GC (application cores), RV64IMAC (management core) | Linux | [HiFive Unleashed development board](https://www.sifive.com/boards/hifive-unleashed) | public since 2018Q1
GAP8 | GreenWaves Technologies | [Product page](https://greenwaves-technologies.com/en/gap8-product/) | PULP / 1 + 8 RI5CY | RV32IMC (+ Priviledged and custom ISA extensions) | RTOS | [GAPuino development board](https://greenwaves-technologies.com/product/gapuino/) | public since 2018Q1
K210 | Kendryte | [Product page](https://kendryte.com/#products), [Datasheet](https://s3.cn-north-1.amazonaws.com.cn/dl.kendryte.com/documents/kendryte_datasheet_20181011163248_en.pdf), [GitHub](https://github.com/kendryte) | K210 | RV64GC | RTOS | [KD233 development board](https://www.analoglamb.com/product/dual-core-risc-v-64bit-k210-ai-board-kendryte-kd233/), [Sipeed MAIX/M1 development boards](https://www.seeedstudio.com/Artificial-Intelligence/Machine-Learning-c-1220/Computer-Vision-c-1221.html?product_list_order=name) | public since 2018Q4
RV32M1 | NXP | [Reference Manual and Datasheet](https://github.com/open-isa-org/open-isa.org/tree/master/Reference%20Manual%20and%20Data%20Sheet) | RI5CY + Zero RI5CY + Arm Cortex M4F + Arm Cortex M0+ | RV32IMC | RTOS | [VEGAboard](https://open-isa.org/) | available for preorder as of 2018Q4
RavenRV32 | efabless | [Datasheet](https://ef.link/raven), [GitHub](https://github.com/efabless/raven-picorv32) | PicoRV32 | RV32IMAC | RTOS | RavenRV32 DevKit | Limited Quantity
