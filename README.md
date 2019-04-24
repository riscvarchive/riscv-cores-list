# RISC-V Cores and SoC Overview

This document captures the status of various cores and SoCs that endeavor to implement the RISC-V specification. Note that none of these cores/SoCs have passed the in-development RISC-V compliance suite.

Please add to the list and fix inaccuracies.

## Cores

Name | Links | Priv. spec | User spec | License | Supplier
---- | ----- | ---------- | --------- | ------- | --------
rocket | [GitHub](https://github.com/freechipsproject/rocket-chip) | 1.11-draft | 2.3-draft | BSD | SiFive, UCB Bar
freedom | [GitHub](https://github.com/sifive/freedom) | 1.11-draft | 2.3-draft | BSD | SiFive
Berkeley Out-of-Order Machine (BOOM) | [GitHub](https://github.com/ucb-bar/riscv-boom) | 1.11-draft | 2.3-draft | BSD | Esperanto, UCB Bar
ORCA | [GitHub](https://github.com/vectorblox/orca) |  | RV32IM | BSD | VectorBlox
RI5CY | [GitHub](https://github.com/pulp-platform/riscv) |  | RV32IMC | Solderpad Hardware License v. 0.51 | ETH Zurich, Università di Bologna
Zero-riscy | [GitHub](https://github.com/pulp-platform/zero-riscy) |  | RV32IMC | Solderpad Hardware License v. 0.51 | ETH Zurich, Università di Bologna
Ariane | [Website](https://pulp-platform.github.io/ariane/docs/home/),[GitHub](https://github.com/pulp-platform/ariane) |  | RV64IMC | Solderpad Hardware License v. 0.51 | ETH Zurich, Università di Bologna
Riscy Processors | [Website](http://csg.csail.mit.edu/riscy-e/),[GitHub](https://github.com/csail-csg/riscy) |  | | MIT | MIT CSAIL CSG
RiscyOO | [GitHub](https://github.com/csail-csg/riscy-OOO) | 1.10 | RV64IMAFD | MIT | MIT CSAIL CSG
Minerva | [GitHub](https://github.com/lambdaconcept/minerva) | 1.10 | RV32I | BSD | LambdaConcept
OPenV/mriscv | [GitHub](https://github.com/onchipuis/mriscv) |  | RV32I(?) | MIT | OnChipUIS
VexRiscv | [GitHub](https://github.com/SpinalHDL/VexRiscv) |  | RV32I[M][C] | MIT | SpinalHDL
Roa Logic RV12 | [GitHub](https://github.com/roalogic/RV12) | 1.9.1 | 2.1 | Non-Commercial License | Roa Logic
SCR1 | [GitHub]( https://github.com/syntacore/scr1) | 1.10 | 2.2, RV32I/E[MC] | Solderpad Hardware License v. 0.51 | Syntacore
Hummingbird E200 | [GitHub](https://github.com/SI-RISCV/e200_opensource) | 1.10 | 2.2, RV32IMAC | Apache 2.0 | Bob Hu
Shakti | [Website](http://shakti.org.in/),[GitLab](https://gitlab.com/shaktiproject) | 1.11 | 2.2, RV64IMAFDC | BSD | IIT Madras
ReonV | [GitHub](https://github.com/lcbcFoo/ReonV) |  |  | GPL v3 |
PicoRV32 | [GitHub](https://github.com/cliffordwolf/picorv32) | | RV32I/E[MC] | ISC | Clifford Wolf
MR1 | [GitHub](https://github.com/tomverbeure/mr1) | | RV32I | Unlicense | Tom Verbeure
SERV | [GitHub](https://github.com/olofk/serv) | | RV32I | ISC | Olof Kindgren
SweRV EH1 | [GitHub](https://github.com/westerndigitalcorporation/swerv_eh1) | | RV32IMC | Apache 2.0 | Western Digital Corporation
Reve-R | [GitHub](https://github.com/atthecodeface/cdl_hardware) | 1.10 | RV32IMAC | Apache 2.0 | Gavin Stark

## SoC platforms

Name | Links | Core | License | Supplier
---- | ----- | ---- | ------- | --------
Rocket Chip | [GitHub](https://github.com/freechipsproject/rocket-chip),[Simulator](https://fires.im) | Rocket | BSD | SiFive, UCB BAR
LowRISC | [GitHub](https://github.com/lowRISC/lowrisc-chip) | RV32IM | BSD | LowRISC CIC
PULPino | [Website](http://www.pulp-platform.org),[GitHub](https://github.com/pulp-platform/pulpino) | RI5CY, Zero-riscy, Ariane | Solderpad Hardware License v. 0.51 | ETH Zurich, Università di Bologna
PULPissimo | [Website](http://www.pulp-platform.org),[GitHub](https://github.com/pulp-platform/pulpissimo) | RI5CY, Zero-riscy, Ariane | Solderpad Hardware License v. 0.51 | ETH Zurich, Università di Bologna
OpenPiton + Ariane | [Website](https://parallel.princeton.edu/openpiton/),[GitHub](https://github.com/PrincetonUniversity/openpiton) | Ariane | BSD | Princeton Parallel Group
Briey | [GitHub](https://github.com/SpinalHDL/VexRiscv#briey-soc) | VexRiscv | MIT | SpinalHDL
Riscy | [GitHub](https://github.com/AleksandarKostovic/Riscy-SoC) | RV64I | MIT | AleksandarKostovic
Raven | [GitHub](https://github.com/efabless/picorv32-soc-raven) | PicoRV32 | ISC | RTimothyEdwards, mkkassem (efabless.com)
PicoSoC | [GitHub](https://github.com/cliffordwolf/picorv32/tree/master/picosoc) | PicoRV32 | ISC | Clifford Wolf
Icicle | [GitHub](https://github.com/grahamedgecombe/icicle) | RV32I | ISC | Graham Edgecombe

## SoCs

Include a chip if it has been fabricated and is either available for sale, available for preorder, or running production workloads internally, and if it has at least one RISC-V hard core (no FPGAs, but non-"SoC" products 
 with controller cores are allowed).

Name | Supplier | Core | ISA | Devkit | Availability | Links
---- | -------- | ---- | --- | ------ | ------------ | -----
FE310-G000 | SiFive | E31 | RV32IMAC | [HiFive1](https://www.sifive.com/boards/hifive1) | public since 2016Q4 | [Datasheet](https://static.dev.sifive.com/FE310-G000.pdf)
FE310-G002 | SiFive | E31 | RV32IMAC | [HiFive1 Rev B](https://www.sifive.com/boards/hifive1-rev-b) | announced 2019Q1, available for preorder | [Product page](https://www.sifive.com/boards/hifive1) 
Freedom U540 | SiFive | U54 (4 cores), E51 (1 management core) | RV64GC (application cores), RV64IMAC (management core) | [HiFive Unleashed development board](https://www.sifive.com/boards/hifive-unleashed) | public since 2018Q1 | [Product page](https://www.sifive.com/products/hifive-unleashed/)
GAP8 | GreenWaves Technologies | PULP / 1 + 8 RI5CY | RV32IMC (+ Priviledged and custom ISA extensions) | [GAPuino development board](https://greenwaves-technologies.com/product/gapuino/) | public since 2018Q1 | [Product page](https://greenwaves-technologies.com/en/gap8-product/)
K210 | Kendryte | K210 | RV64GC | KD233 development board, Sipeed MAIX/M1 development boards | public since 2018Q4 | [Kendryte](https://kendryte.com/), [Datasheet](https://s3.cn-north-1.amazonaws.com.cn/dl.kendryte.com/documents/kendryte_datasheet_20181011163248_en.pdf), [GitHub](https://github.com/kendryte)
RV32M1 | NXP | RI5CY + Zero RI5CY + Arm Cortex M4F + Arm Cortex M0+ | RV32IMC | [VEGAboard](https://open-isa.org/) | available for preorder as of 2018Q4 | [Reference Manual and Datasheet](https://github.com/open-isa-org/open-isa.org/tree/master/Reference%20Manual%20and%20Data%20Sheet)
RavenRV32 | efabless | PicoRV32 | RV32IMAC | RavenRV32 DevKit | Limited Quantity | [Datasheet](https://ef.link/raven), [GitHub](https://github.com/efabless/raven-picorv32)
