# RISC-V Cores and SoC Overview

This document captures the status of various cores and SoCs that endeavor to implement the RISC-V specification. Note that none of these cores/SoCs have passed the in-development RISC-V compliance suite.

Please add to the list and fix inaccuracies - see our [CONTRIBUTING file](https://github.com/riscv/riscv-cores-list/blob/master/CONTRIBUTING.md) for details.

## Cores

Name | Supplier | Links | Priv. spec | User spec | Primary Language | License
---- | -------- | ----- | ---------- | --------- | ---------------- | -------
RV32EC_P2 | IQonIC Works | [Website](http://iqonicworks.com/risc-v-ip/) | 1.11 | RV32E[M]C/RV32I[M]C | SystemVerilog | IQonIC Works Commercial License
RV32IC_P5 | IQonIC Works | [Website](http://iqonicworks.com/risc-v-ip/) | 1.11 | RV32I[M][N][A]C | SystemVerilog | IQonIC Works Commercial License
RV32EC_FMP5 | IQonIC Works | [Website](http://iqonicworks.com/risc-v-ip/) | Custom | RV32EC | SystemVerilog | IQonIC Works Commercial License
rocket | SiFive, UCB Bar| [GitHub](https://github.com/freechipsproject/rocket-chip) | 1.11-draft | 2.3-draft | Chisel | BSD
freedom | SiFive | [GitHub](https://github.com/sifive/freedom) | 1.11-draft | 2.3-draft | Chisel | BSD
Berkeley Out-of-Order Machine (BOOM) | UCB BAR | [Website](https://boom-core.org/),[GitHub](https://github.com/riscv-boom/riscv-boom) | 1.11-draft | 2.3-draft | Chisel | BSD
ORCA | VectorBlox | [GitHub](https://github.com/vectorblox/orca) |  | RV32IM | VHDL | BSD
RI5CY | ETH Zurich, Università di Bologna | [GitHub](https://github.com/pulp-platform/riscv) |  | RV32IMC | SystemVerilog | Solderpad Hardware License v. 0.51
Ibex (formerly Zero-riscy) | lowRISC | [GitHub](https://github.com/lowRISC/ibex) | 1.11 | RV32I[M]C/RV32E[M]C | SystemVerilog | Apache 2.0
Ariane | ETH Zurich, Università di Bologna | [Website](https://pulp-platform.github.io/ariane/docs/home/),[GitHub](https://github.com/pulp-platform/ariane) | 1.11-draft | RV64GC | SystemVerilog | Solderpad Hardware License v. 0.51
Riscy Processors | MIT CSAIL CSG | [Website](http://csg.csail.mit.edu/riscy-e/),[GitHub](https://github.com/csail-csg/riscy) | | | Bluespec | MIT
RiscyOO | MIT CSAIL CSG | [GitHub](https://github.com/csail-csg/riscy-OOO) | 1.10 | RV64IMAFD | Bluespec | MIT
Lizard | Cornell CSL BRG | [GitHub](https://github.com/cornell-brg/lizard) | | RV64IM | PyMTL | BSD
Minerva | LambdaConcept | [GitHub](https://github.com/lambdaconcept/minerva) | 1.10 | RV32I | nMigen | BSD
OPenV/mriscv | OnChipUIS | [GitHub](https://github.com/onchipuis/mriscv) | | RV32I(?) | Verilog | MIT
VexRiscv | SpinalHDL | [GitHub](https://github.com/SpinalHDL/VexRiscv) | | RV32I[M][C] | SpinalHDL | MIT
Roa Logic RV12 | Roa Logic | [GitHub](https://github.com/roalogic/RV12) | 1.9.1 | 2.1 | SystemVerilog | Non-Commercial License
SCR1 | Syntacore | [GitHub](https://github.com/syntacore/scr1) | 1.10 | 2.2, RV32I/E[MC] | SystemVerilog | SHL v. 2.0
SCR3 | Syntacore | [Website](https://syntacore.com/page/products/processor-ip/scr3) | 1.10 | RV[32/64]IMC[A], 2.2, milticore | SystemVerilog | commercial
SCR4 | Syntacore | [Website](https://syntacore.com/page/products/processor-ip/scr4) | 1.10 | RV[32/64]IMCF[DA], 2.2, milticore | SystemVerilog | commercial
SCR5 | Syntacore | [Website](https://syntacore.com/page/products/processor-ip/scr5) | 1.10 | RV[32/64]IMC[FDA], 2.2, milticore | SystemVerilog | commercial
SCR7 | Syntacore | [Website](https://syntacore.com/page/products/processor-ip/scr7) | 1.10 | RV64GC, 2.2, milticore | SystemVerilog | commercial
Hummingbird E200 | Bob Hu | [GitHub](https://github.com/SI-RISCV/e200_opensource) | 1.10 | 2.2, RV32IMAC | Verilog | Apache 2.0
Shakti | IIT Madras | [Website](http://shakti.org.in/),[GitLab](https://gitlab.com/shaktiproject) | 1.11 | 2.2, RV64IMAFDC | Bluespec | BSD
ReonV | Lucas Castro | [GitHub](https://github.com/lcbcFoo/ReonV) | | | VHDL | GPL v3
PicoRV32 | Clifford Wolf | [GitHub](https://github.com/cliffordwolf/picorv32) | | RV32I/E[MC] | Verilog | ISC
MR1 | Tom Verbeure | [GitHub](https://github.com/tomverbeure/mr1) | | RV32I | SpinalHDL | Unlicense
SERV | Olof Kindgren | [GitHub](https://github.com/olofk/serv) | | RV32I | Verilog | ISC
SweRV EH1 | Western Digital Corporation | [GitHub](https://github.com/chipsalliance/Cores-SweRV) | | RV32IMC | SystemVerilog | Apache 2.0
Reve-R | Gavin Stark | [GitHub](https://github.com/atthecodeface/cdl_hardware) | 1.10 | RV32IMAC | CDL | Apache 2.0
Bk3 | Codasip | [Website](http://www.codasip.com) | 1.10 | RV32EMC / RV32IM[F]C | Verilog | Codasip EULA
Bk5 | Codasip | [Website](http://www.codasip.com) | 1.10 | RV32IM[F]C / RV64IM[F]C | Verilog | Codasip EULA
Bk7 | Codasip | [Website](http://www.codasip.com) | 1.10 | RV64IMA[F][D][C] | Verilog | Codasip EULA
DarkRISCV | Darklife | [GitHub](https://github.com/darklife/darkriscv) | | most of RV32I | Verilog | BSD
RPU | Domipheus Labs | [GitHub](https://github.com/Domipheus/RPU) | | RV32I | VHDL | Apache 2.0
RV01 | Stefano Tonello | [OpenCores](https://opencores.org/projects/rv01_riscv_core) | 1.7 | 2.1, RV32IM | VHDL | LPGL
N22 | Andes | [Website](http://freestart.andestech.com/) | 1.11 | RV32IMAC/EMAC + Andes V5/V5e ext. | Verilog | Andes FreeStart IPEA
N25F | Andes | [Website](http://www.andestech.com/en/products-solutions/andescore-processors/riscv-n25f/) | 1.11 | RV32GC + Andes V5 ext. | Verilog | Andes Commercial License
D25F | Andes | [Website](http://www.andestech.com/en/products-solutions/andescore-processors/riscv-d25f/) | 1.11 | RV32GCP + Andes V5 ext. | Verilog | Andes Commercial License
A25 | Andes | [Website](http://www.andestech.com/en/products-solutions/andescore-processors/riscv-a25/) | 1.11 | RV32GCP + SV32 + Andes V5 ext. | Verilog | Andes Commercial License
A25MP | Andes | [Website](http://www.andestech.com/en/products-solutions/andescore-processors/riscv-a25mp/) | 1.11 | RV32GCP + SV32 + Andes V5 ext. + Multi-core | Verilog | Andes Commercial License
NX25F | Andes | [Website](http://www.andestech.com/en/products-solutions/andescore-processors/riscv-nx25f/) | 1.11 | RV64GC + Andes V5 ext. | Verilog | Andes Commercial License
AX25 | Andes | [Website](http://www.andestech.com/en/products-solutions/andescore-processors/riscv-ax25/) | 1.11 | RV64GCP + SV39/48 + Andes V5 ext. | Verilog | Andes Commercial License
AX25MP | Andes | [Website](http://www.andestech.com/en/products-solutions/andescore-processors/riscv-ax25mp/) | 1.11 | RV64GCP + SV39/48 + Andes V5 ext. + Multi-core | Verilog | Andes Commercial License
Instant SoC | FPGA Cores | [Website](http://www.fpga-cores.com/instant-soc/) |  | RV32IM | VHDL | Free Non Commercial
Taiga | Reconfigurable Computing Lab, Simon Fraser University | [GitLab](https://gitlab.com/sfu-rcl/Taiga) |  | RV32IMA | SystemVerilog | Apache 2.0
Maestro | João Chrisóstomo | [GitHub](https://github.com/Artoriuz/maestro) | | RV32I | VHDL | MIT
XuanTie C910 | T-Head (Alibaba group) | [Website](https://www.t-head.cn/product/c910?spm=a2ouz.12987052.0.0.5c5c6245WIbjoG) | 1.10 |  RV64GCV + SV39 + ISA Extension + Memory model Extension + multi-core & multi-cluster(16 cores maximum) | Verilog | Alibaba commercial license
XuanTie E902 | T-Head (Alibaba group) | [Website](https://www.t-head.cn/product/e902?spm=a2ouz.12987052.0.0.5c5c6245R2yhfA) | 1.10 | RV32EMC/IMC/EC | Verilog | Alibaba commercial license
BM-310 | CloudBEAR | [Website](https://cloudbear.ru/bm_310.html) | 1.10 | RV32IMC | SystemVerilog | CloudBEAR Commercial License
BI-350 | CloudBEAR | [Website](https://cloudbear.ru/bi_350.html) | 1.10 | RV32IMAFC + multi-core | SystemVerilog | CloudBEAR Commercial License
BI-651 | CloudBEAR | [Website](https://cloudbear.ru/bi_651.html) | 1.10 | RV64GC + multi-core | SystemVerilog | CloudBEAR Commercial License
BI-671 | CloudBEAR | [Website](https://cloudbear.ru/bi_671.html) | 1.10 | RV64GC + multi-core | SystemVerilog | CloudBEAR Commercial License
SSRV | risclite | [Website](https://risclite.github.io/),[GitHub](https://github.com/risclite/SuperScalar-RISCV-CPU) | 1.10 | RV32IMC | Verilog | Apache 2.0
RSD | rsd-devel | [GitHub](https://github.com/rsd-devel/rsd) | | RV32IM | SystemVerilog | Apache 2.0
Pluto | PQShield | [Website](https://pqsoc.com) | 1.11 | RV32I[M][C] / RV32E[M][C] + Crypto Functions | Verilog | PQShield Commercial License

## SoC platforms

Name | Supplier | Links | Core | License
---- | -------- | ----- | ---- | -------
Rocket Chip | SiFive, UCB BAR | [GitHub](https://github.com/freechipsproject/rocket-chip),[Simulator](https://fires.im) | Rocket | BSD
LowRISC | lowRISC | [GitHub](https://github.com/lowRISC/lowrisc-chip) | RV32IM | BSD
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
MIV RV32IMA L1 AHB | Microchip | [Documentation](http://www.microsemi.com/index.php?option=com_docman&task=doc_download&gid=1243779), [IDE](https://www.microsemi.com/product-directory/design-tools/4879-softconsole), [Development Environment](https://www.microsemi.com/product-directory/design-resources/1750-libero-soc) | Rocket RV32IMA | Apache 2.0
MIV RV32IMA L1 AXI | Microchip | [Documentation](http://www.microsemi.com/index.php?option=com_docman&task=doc_download&gid=1243780), [IDE](https://www.microsemi.com/product-directory/design-tools/4879-softconsole), [Development Environment](https://www.microsemi.com/product-directory/design-resources/1750-libero-soc) | Rocket RV32IMA | Apache 2.0
MIV RV32IMAF L1 AHB | Microchip | [Documentation](http://www.microsemi.com/index.php?option=com_docman&task=doc_download&gid=1243781), [IDE](https://www.microsemi.com/product-directory/design-tools/4879-softconsole), [Development Environment](https://www.microsemi.com/product-directory/design-resources/1750-libero-soc) | Rocket RV32IMAF | Apache 2.0
FreeStart AE250 | Andes | [Website](http://freestart.andestech.com/) | N22 | Andes FreeStart: Free for Evaluation
Standard AE250 | Andes | [Website](http://www.andestech.com/en/products-solutions/andeshape-platforms/ae250-ahb-based-platform-pre-integrated-with-n22/), [IDE](http://www.andestech.com/en/products-solutions/andesight-ide/) | N22 | Andes Commerical License
AE350 | Andes | [Website](http://www.andestech.com/en/products-solutions/andeshape-platforms/ae350-axi-based-platform-pre-integrated-with-n25f-nx25f-a25-ax25/), [IDE](http://www.andestech.com/en/products-solutions/andesight-ide/) | N25F, D25F, A25, A25MP, NX25F, AX25, AX25MP | Andes Commerical License
SCR1 SDK | Syntacore | [GitHub](https://github.com/syntacore/scr1-sdk) | SCR1, SCRx | SHL 2.0
ESP | SLD Group, Columbia University | [Website](https://esp.cs.columbia.edu), [GitHub](https://github.com/sld-columbia/esp) | Ariane | Apache 2.0
Chipyard | UCB BAR | [GitHub](https://github.com/ucb-bar/chipyard),[Documentation](https://chipyard.readthedocs.io/en/latest/) | Rocket, BOOM | BSD
PQSoC | PQShield | [Website](https://pqsoc.com) | Pluto | PQShield Commercial License

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
PolarFire SoC | Microchip | [Product Page](https://www.microsemi.com/product-directory/soc-fpgas/5498-polarfire-soc-fpga), [IDE with Renode platform](https://www.microsemi.com/product-directory/design-tools/4879-softconsole) | U54 (4 cores), E51 (management core) | RV64GC(U54), RV64IMAC(E51) | Linux | [HiFive Unleashed Expansion Board](https://www.microsemi.com/hifive-unleashed-expansion-board), PolarFire SoC | HiFive Unleased Expansion Board - Q2 2018, PolarFire Soc – announced December 2018
GD32VF103 | GigaDevice | [Product listing](https://www.gigadevice.com/products/product-finder/?fwp_processor_type=risc-v&fwp_microcontrollers_product_line=mainstream&fwp_microcontrollers_product_series=gd32vf103),[Datasheets](https://github.com/riscv-mcu/GD32VF103_DataSheets) | [Bumblebee Core](http://dl.sipeed.com/LONGAN/Nano/DOC/Bumblebee%20core%20datasheet_en.pdf) | RV32IMAC | RTOS | GD32VF103V-EVAL, [Longan Nano](http://longan.sipeed.com/) etc.| Public since 2019Q4
