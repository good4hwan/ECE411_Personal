# AG Report Generated 2020-02-09 16:13
This is a report about mp1 generated for mirecki2 at 2020-02-09 16:13. The autograder used commit ``0ff1981fa607`` as a starting point. If you have any questions about this report, please contact the TAs on Piazza.
### Quick Results:
 - Compilation: NO
 - Targeted: 0/31 (0.0%)
### Compilation ![Failure][failure]
You did not succesfully compile. Your report is below.
<details>
<summary>Compilation Report</summary>

```
Info: *******************************************************************
Info: Running Quartus Prime Analysis & Synthesis
    Info: Version 18.1.0 Build 625 09/12/2018 SJ Standard Edition
    Info: Copyright (C) 2018  Intel Corporation. All rights reserved.
    Info: Your use of Intel Corporation's design tools, logic functions 
    Info: and other software and tools, and its AMPP partner logic 
    Info: functions, and any output files from any of the foregoing 
    Info: (including device programming or simulation files), and any 
    Info: associated documentation or information are expressly subject 
    Info: to the terms and conditions of the Intel Program License 
    Info: Subscription Agreement, the Intel Quartus Prime License Agreement,
    Info: the Intel FPGA IP License Agreement, or other applicable license
    Info: agreement, including, without limitation, that your use is for
    Info: the sole purpose of programming logic devices manufactured by
    Info: Intel and sold by Intel or its authorized distributors.  Please
    Info: refer to the applicable agreement for further details.
    Info: Processing started: Sun Feb  9 22:12:42 2020
Info: Command: quartus_map mp1 -c mp1
Info (20030): Parallel compilation is enabled and will use 4 of the 4 processors detected
Info (12021): Found 1 design units, including 1 entities, in source file hdl/cmp.sv
    Info (12023): Found entity 1: cmp File: /job/student/hdl/cmp.sv Line: 3
Info (12021): Found 1 design units, including 1 entities, in source file hdl/control.sv
    Info (12023): Found entity 1: control File: /job/student/hdl/control.sv Line: 3
Info (12021): Found 1 design units, including 1 entities, in source file hdl/datapath.sv
    Info (12023): Found entity 1: datapath File: /job/student/hdl/datapath.sv Line: 5
Info (12021): Found 1 design units, including 1 entities, in source file hdl/mp1.sv
    Info (12023): Found entity 1: mp1 File: /job/student/hdl/mp1.sv Line: 3
Info (12021): Found 4 design units, including 4 entities, in source file hdl/mux.sv
    Info (12023): Found entity 1: twomux File: /job/student/hdl/mux.sv Line: 1
    Info (12023): Found entity 2: fourmux File: /job/student/hdl/mux.sv Line: 15
    Info (12023): Found entity 3: eightmux File: /job/student/hdl/mux.sv Line: 33
    Info (12023): Found entity 4: sixmux File: /job/student/hdl/mux.sv Line: 52
Info (12021): Found 1 design units, including 1 entities, in source file hdl/alu.sv
    Info (12023): Found entity 1: alu File: /job/student/hdl/alu.sv Line: 3
Info (12021): Found 1 design units, including 1 entities, in source file hdl/ir.sv
    Info (12023): Found entity 1: ir File: /job/student/hdl/ir.sv Line: 3
Info (12021): Found 1 design units, including 1 entities, in source file hdl/pc_reg.sv
    Info (12023): Found entity 1: pc_register File: /job/student/hdl/pc_reg.sv Line: 1
Info (12021): Found 1 design units, including 1 entities, in source file hdl/regfile.sv
    Info (12023): Found entity 1: regfile File: /job/student/hdl/regfile.sv Line: 2
Info (12021): Found 1 design units, including 1 entities, in source file hdl/register.sv
    Info (12023): Found entity 1: register File: /job/student/hdl/register.sv Line: 1
Info (12021): Found 5 design units, including 0 entities, in source file hdl/rv32i_mux_types.sv
    Info (12022): Found design unit 1: pcmux (SystemVerilog) File: /job/student/hdl/rv32i_mux_types.sv Line: 1
    Info (12022): Found design unit 2: marmux (SystemVerilog) File: /job/student/hdl/rv32i_mux_types.sv Line: 9
    Info (12022): Found design unit 3: cmpmux (SystemVerilog) File: /job/student/hdl/rv32i_mux_types.sv Line: 16
    Info (12022): Found design unit 4: alumux (SystemVerilog) File: /job/student/hdl/rv32i_mux_types.sv Line: 23
    Info (12022): Found design unit 5: regfilemux (SystemVerilog) File: /job/student/hdl/rv32i_mux_types.sv Line: 39
Info (12021): Found 1 design units, including 0 entities, in source file hdl/rv32i_types.sv
    Info (12022): Found design unit 1: rv32i_types (SystemVerilog) File: /job/student/hdl/rv32i_types.sv Line: 1
Info (12127): Elaborating entity "mp1" for the top level hierarchy
Info (12128): Elaborating entity "control" for hierarchy "control:control" File: /job/student/hdl/mp1.sv Line: 45
Warning (10036): Verilog HDL or VHDL warning at control.sv(34): object "trap" assigned a value but never read File: /job/student/hdl/control.sv Line: 34
Warning (10036): Verilog HDL or VHDL warning at control.sv(35): object "rs1_addr" assigned a value but never read File: /job/student/hdl/control.sv Line: 35
Warning (10036): Verilog HDL or VHDL warning at control.sv(35): object "rs2_addr" assigned a value but never read File: /job/student/hdl/control.sv Line: 35
Warning (10036): Verilog HDL or VHDL warning at control.sv(36): object "rmask" assigned a value but never read File: /job/student/hdl/control.sv Line: 36
Warning (10036): Verilog HDL or VHDL warning at control.sv(36): object "wmask" assigned a value but never read File: /job/student/hdl/control.sv Line: 36
Warning (10858): Verilog HDL warning at control.sv(37): object rs1 used but never assigned File: /job/student/hdl/control.sv Line: 37
Warning (10858): Verilog HDL warning at control.sv(38): object rs2 used but never assigned File: /job/student/hdl/control.sv Line: 38
Warning (10036): Verilog HDL or VHDL warning at control.sv(43): object "arith_funct3" assigned a value but never read File: /job/student/hdl/control.sv Line: 43
Info (10264): Verilog HDL Case Statement information at control.sv(194): all case item expressions in this case statement are onehot File: /job/student/hdl/control.sv Line: 194
Info (10264): Verilog HDL Case Statement information at control.sv(376): all case item expressions in this case statement are onehot File: /job/student/hdl/control.sv Line: 376
Info (12128): Elaborating entity "datapath" for hierarchy "datapath:datapath" File: /job/student/hdl/mp1.sv Line: 48
Info (12128): Elaborating entity "ir" for hierarchy "datapath:datapath|ir:IR" File: /job/student/hdl/datapath.sv Line: 78
Info (12128): Elaborating entity "register" for hierarchy "datapath:datapath|register:MDR" File: /job/student/hdl/datapath.sv Line: 86
Info (12128): Elaborating entity "alu" for hierarchy "datapath:datapath|alu:ALU" File: /job/student/hdl/datapath.sv Line: 101
Info (12128): Elaborating entity "pc_register" for hierarchy "datapath:datapath|pc_register:PC" File: /job/student/hdl/datapath.sv Line: 109
Info (12128): Elaborating entity "regfile" for hierarchy "datapath:datapath|regfile:REGFILE" File: /job/student/hdl/datapath.sv Line: 121
Info (12128): Elaborating entity "cmp" for hierarchy "datapath:datapath|cmp:CMP" File: /job/student/hdl/datapath.sv Line: 128
Info (12128): Elaborating entity "fourmux" for hierarchy "datapath:datapath|cmp:CMP|fourmux:cmpmux" File: /job/student/hdl/cmp.sv Line: 28
Info (12128): Elaborating entity "twomux" for hierarchy "datapath:datapath|twomux:pcmux" File: /job/student/hdl/datapath.sv Line: 165
Info (12128): Elaborating entity "eightmux" for hierarchy "datapath:datapath|eightmux:alumux2" File: /job/student/hdl/datapath.sv Line: 185
Info (12128): Elaborating entity "sixmux" for hierarchy "datapath:datapath|sixmux:regfilemux" File: /job/student/hdl/datapath.sv Line: 220
Warning (12241): 1 hierarchies have connectivity warnings - see the Connectivity Checks report folder
Warning (13024): Output pins are stuck at VCC or GND
    Warning (13410): Pin "mem_write" is stuck at GND File: /job/student/hdl/mp1.sv Line: 10
    Warning (13410): Pin "mem_byte_enable[0]" is stuck at VCC File: /job/student/hdl/mp1.sv Line: 11
    Warning (13410): Pin "mem_byte_enable[1]" is stuck at VCC File: /job/student/hdl/mp1.sv Line: 11
    Warning (13410): Pin "mem_byte_enable[2]" is stuck at VCC File: /job/student/hdl/mp1.sv Line: 11
    Warning (13410): Pin "mem_byte_enable[3]" is stuck at VCC File: /job/student/hdl/mp1.sv Line: 11
Info (286030): Timing-Driven Synthesis is running
Info (17049): 33 registers lost all their fanouts during netlist optimizations.
Info (144001): Generated suppressed messages file /job/student/output_files/mp1.map.smsg
Info (16010): Generating hard_block partition "hard_block:auto_generated_inst"
    Info (16011): Adding 0 node(s), including 0 DDIO, 0 PLL, 0 transceiver and 0 LCELL
Info (21057): Implemented 2659 device resources after synthesis - the final resource count might be different
    Info (21058): Implemented 35 input pins
    Info (21059): Implemented 70 output pins
    Info (21061): Implemented 2554 logic cells
Info: Quartus Prime Analysis & Synthesis was successful. 0 errors, 15 warnings
    Info: Peak virtual memory: 1219 megabytes
    Info: Processing ended: Sun Feb  9 22:13:03 2020
    Info: Elapsed time: 00:00:21
    Info: Total CPU time (on all processors): 00:00:42
Info: *******************************************************************
Info: Running Quartus Prime Shell
    Info: Version 18.1.0 Build 625 09/12/2018 SJ Standard Edition
    Info: Copyright (C) 2018  Intel Corporation. All rights reserved.
    Info: Your use of Intel Corporation's design tools, logic functions 
    Info: and other software and tools, and its AMPP partner logic 
    Info: functions, and any output files from any of the foregoing 
    Info: (including device programming or simulation files), and any 
    Info: associated documentation or information are expressly subject 
    Info: to the terms and conditions of the Intel Program License 
    Info: Subscription Agreement, the Intel Quartus Prime License Agreement,
    Info: the Intel FPGA IP License Agreement, or other applicable license
    Info: agreement, including, without limitation, that your use is for
    Info: the sole purpose of programming logic devices manufactured by
    Info: Intel and sold by Intel or its authorized distributors.  Please
    Info: refer to the applicable agreement for further details.
    Info: Processing started: Sun Feb  9 22:13:03 2020
Info: Command: quartus_sh -t /opt/altera/quartus/common/tcl/internal/nativelink/qnativesim.tcl --gen_script --rtl_sim mp1 mp1
Info: Quartus(args): --gen_script --rtl_sim mp1 mp1
Info: Info: Start Nativelink Simulation process
Info: Info: NativeLink has detected Verilog design -- Verilog simulation models will be used
Info: Info: Starting NativeLink simulation with ModelSim-Altera software
Info: Info: Generated ModelSim-Altera script file /job/student/simulation/modelsim/mp1_run_msim_rtl_verilog.do File: /job/student/simulation/modelsim/mp1_run_msim_rtl_verilog.do Line: 0
Info: Info: NativeLink simulation flow was successful
Info: Info: For messages from NativeLink scripts, check the file /job/student/mp1_nativelink_simulation.rpt File: /job/student/mp1_nativelink_simulation.rpt Line: 0
Info (23030): Evaluation of Tcl script /opt/altera/quartus/common/tcl/internal/nativelink/qnativesim.tcl was successful
Info: Quartus Prime Shell was successful. 0 errors, 0 warnings
    Info: Peak virtual memory: 792 megabytes
    Info: Processing ended: Sun Feb  9 22:13:04 2020
    Info: Elapsed time: 00:00:01
    Info: Total CPU time (on all processors): 00:00:00
Reading pref.tcl

# 10.5b

ModelSim> transcript on
ModelSim> > > if {[file exists rtl_work]} {
	vdel -lib rtl_work -all
}
ModelSim> vlib rtl_work
ModelSim> vmap work rtl_work
# Model Technology ModelSim - Intel FPGA Edition vmap 10.5b Lib Mapping Utility 2016.10 Oct  5 2016
# vmap work rtl_work 
# Modifying /opt/altera/modelsim_ase/linuxaloem/../modelsim.ini
ModelSim> 
> 
vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/mux.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/mux.sv 
# -- Compiling module twomux
# -- Compiling module fourmux
# -- Compiling module eightmux
# -- Compiling module sixmux
# 
# Top level modules:
# 	twomux
# 	fourmux
# 	eightmux
# 	sixmux
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/pc_reg.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/pc_reg.sv 
# -- Compiling module pc_register
# 
# Top level modules:
# 	pc_register
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/regfile.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/regfile.sv 
# -- Compiling module regfile
# 
# Top level modules:
# 	regfile
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/register.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/register.sv 
# -- Compiling module register
# 
# Top level modules:
# 	register
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/rv32i_mux_types.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/rv32i_mux_types.sv 
# -- Compiling package pcmux
# -- Compiling package marmux
# -- Compiling package cmpmux
# -- Compiling package alumux
# -- Compiling package regfilemux
# 
# Top level modules:
# 	--none--
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/rv32i_types.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/rv32i_types.sv 
# -- Compiling package rv32i_types
# -- Importing package pcmux
# -- Importing package marmux
# -- Importing package cmpmux
# -- Importing package alumux
# -- Importing package regfilemux
# 
# Top level modules:
# 	--none--
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/cmp.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/cmp.sv 
# -- Compiling package cmp_sv_unit
# -- Importing package rv32i_types
# -- Importing package pcmux
# -- Importing package marmux
# -- Importing package cmpmux
# -- Importing package alumux
# -- Importing package regfilemux
# -- Compiling module cmp
# 
# Top level modules:
# 	cmp
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/control.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/control.sv 
# -- Compiling package control_sv_unit
# -- Importing package rv32i_types
# -- Importing package pcmux
# -- Importing package marmux
# -- Importing package cmpmux
# -- Importing package alumux
# -- Importing package regfilemux
# -- Compiling module control
# 
# Top level modules:
# 	control
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/datapath.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/datapath.sv 
# -- Compiling package datapath_sv_unit
# -- Importing package rv32i_types
# -- Importing package pcmux
# -- Importing package marmux
# -- Importing package cmpmux
# -- Importing package alumux
# -- Importing package regfilemux
# -- Compiling module datapath
# 
# Top level modules:
# 	datapath
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/alu.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/alu.sv 
# -- Compiling package alu_sv_unit
# -- Importing package rv32i_types
# -- Importing package pcmux
# -- Importing package marmux
# -- Importing package cmpmux
# -- Importing package alumux
# -- Importing package regfilemux
# -- Compiling module alu
# 
# Top level modules:
# 	alu
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/ir.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/ir.sv 
# -- Compiling package ir_sv_unit
# -- Importing package rv32i_types
# -- Importing package pcmux
# -- Importing package marmux
# -- Importing package cmpmux
# -- Importing package alumux
# -- Importing package regfilemux
# -- Compiling module ir
# 
# Top level modules:
# 	ir
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hdl {/job/student/hdl/mp1.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hdl" /job/student/hdl/mp1.sv 
# -- Compiling package mp1_sv_unit
# -- Importing package rv32i_types
# -- Importing package pcmux
# -- Importing package marmux
# -- Importing package cmpmux
# -- Importing package alumux
# -- Importing package regfilemux
# -- Compiling module mp1
# 
# Top level modules:
# 	mp1
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> 
> 
vlog -sv -work work +incdir+/job/student/hvl {/job/student/hvl/top.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hvl" /job/student/hvl/top.sv 
# -- Compiling package top_sv_unit
# -- Importing package rv32i_types
# -- Importing package pcmux
# -- Importing package marmux
# -- Importing package cmpmux
# -- Importing package alumux
# -- Importing package regfilemux
# ** Warning: ./hvl/rvmodel.sv(83): (vlog-2240) Treating stand-alone use of function 'reset' as an implicit VOID cast.
# ** Warning: ./hvl/rvmodel.sv(108): (vlog-2240) Treating stand-alone use of function 'init' as an implicit VOID cast.
# ** Warning: ./hvl/rvmodel.sv(69): (vlog-2250) Function "dumpmem" has no return value assignment.
# ** Warning: ./hvl/rvmodel.sv(74): (vlog-2250) Function "reset" has no return value assignment.
# ** Warning: ./hvl/rvmodel.sv(82): (vlog-2250) Function "init" has no return value assignment.
# ** Warning: ./hvl/rvmodel.sv(103): (vlog-2250) Function "run" has no return value assignment.
# -- Compiling module mp1_tb
# ** Error: /job/student/hvl/top.sv(79): (vlog-2123) Missing argument for format specification '%p'.
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 1, Warnings: 6
# /opt/altera/modelsim_ase/linuxaloem/vlog failed.
ModelSim> vlog -sv -work work +incdir+/job/student/hvl {/job/student/hvl/tb_itf.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hvl" /job/student/hvl/tb_itf.sv 
# -- Compiling interface tb_itf
# 
# Top level modules:
# 	--none--
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hvl {/job/student/hvl/source_tb.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hvl" /job/student/hvl/source_tb.sv 
# -- Compiling module source_tb
# 
# Top level modules:
# 	source_tb
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -sv -work work +incdir+/job/student/hvl {/job/student/hvl/memory.sv}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -sv -work work "+incdir+/job/student/hvl" /job/student/hvl/memory.sv 
# -- Compiling module memory
# 
# Top level modules:
# 	memory
# End time: 22:13:05 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 0, Warnings: 0
ModelSim> vlog -vlog01compat -work work +incdir+/job/student/hvl {/job/student/hvl/rvfimon.v}
# Model Technology ModelSim - Intel FPGA Edition vlog 10.5b Compiler 2016.10 Oct  5 2016
# Start time: 22:13:05 on Feb 09,2020
# vlog -vlog01compat -work work "+incdir+/job/student/hvl" /job/student/hvl/rvfimon.v 
# -- Compiling module riscv_formal_monitor_rv32i
# -- Compiling module riscv_formal_monitor_rv32i_rob
# -- Compiling module riscv_formal_monitor_rv32i_isa_spec
# -- Compiling module riscv_formal_monitor_rv32i_insn_add
# -- Compiling module riscv_formal_monitor_rv32i_insn_addi
# -- Compiling module riscv_formal_monitor_rv32i_insn_and
# -- Compiling module riscv_formal_monitor_rv32i_insn_andi
# -- Compiling module riscv_formal_monitor_rv32i_insn_auipc
# -- Compiling module riscv_formal_monitor_rv32i_insn_beq
# -- Compiling module riscv_formal_monitor_rv32i_insn_bge
# -- Compiling module riscv_formal_monitor_rv32i_insn_bgeu
# -- Compiling module riscv_formal_monitor_rv32i_insn_blt
# -- Compiling module riscv_formal_monitor_rv32i_insn_bltu
# -- Compiling module riscv_formal_monitor_rv32i_insn_bne
# -- Compiling module riscv_formal_monitor_rv32i_insn_jal
# -- Compiling module riscv_formal_monitor_rv32i_insn_jalr
# -- Compiling module riscv_formal_monitor_rv32i_insn_lb
# -- Compiling module riscv_formal_monitor_rv32i_insn_lbu
# -- Compiling module riscv_formal_monitor_rv32i_insn_lh
# -- Compiling module riscv_formal_monitor_rv32i_insn_lhu
# -- Compiling module riscv_formal_monitor_rv32i_insn_lui
# -- Compiling module riscv_formal_monitor_rv32i_insn_lw
# -- Compiling module riscv_formal_monitor_rv32i_insn_or
# -- Compiling module riscv_formal_monitor_rv32i_insn_ori
# -- Compiling module riscv_formal_monitor_rv32i_insn_sb
# -- Compiling module riscv_formal_monitor_rv32i_insn_sh
# -- Compiling module riscv_formal_monitor_rv32i_insn_sll
# -- Compiling module riscv_formal_monitor_rv32i_insn_slli
# -- Compiling module riscv_formal_monitor_rv32i_insn_slt
# -- Compiling module riscv_formal_monitor_rv32i_insn_slti
# -- Compiling module riscv_formal_monitor_rv32i_insn_sltiu
# -- Compiling module riscv_formal_monitor_rv32i_insn_sltu
# -- Compiling module riscv_formal_monitor_rv32i_insn_sra
# -- Compiling module riscv_formal_monitor_rv32i_insn_srai
# -- Compiling module riscv_formal_monitor_rv32i_insn_srl
# -- Compiling module riscv_formal_monitor_rv32i_insn_srli
# -- Compiling module riscv_formal_monitor_rv32i_insn_sub
# -- Compiling module riscv_formal_monitor_rv32i_insn_sw
# -- Compiling module riscv_formal_monitor_rv32i_insn_xor
# -- Compiling module riscv_formal_monitor_rv32i_insn_xori
# 
# Top level modules:
# 	riscv_formal_monitor_rv32i
# End time: 22:13:06 on Feb 09,2020, Elapsed time: 0:00:01
# Errors: 0, Warnings: 0
ModelSim> 
> 
vsim -t 1ps -L altera_ver -L lpm_ver -L sgate_ver -L altera_mf_ver -L altera_lnsim_ver -L arriaii_hssi_ver -L arriaii_pcie_hip_ver -L arriaii_ver -L rtl_work -L work -voptargs="+acc"  mp1_tb
# vsim -t 1ps -L altera_ver -L lpm_ver -L sgate_ver -L altera_mf_ver -L altera_lnsim_ver -L arriaii_hssi_ver -L arriaii_pcie_hip_ver -L arriaii_ver -L rtl_work -L work -voptargs=""+acc"" mp1_tb 
# Start time: 22:13:06 on Feb 09,2020
# Loading sv_std.std
# Loading work.regfilemux
# Loading work.alumux
# Loading work.cmpmux
# Loading work.marmux
# Loading work.pcmux
# Loading work.rv32i_types
# Loading work.top_sv_unit
# Loading work.mp1_tb
# Loading work.tb_itf
# Loading work.source_tb
# Loading work.memory
# Loading work.mp1_sv_unit
# Loading work.mp1
# Loading work.control_sv_unit
# Loading work.control
# Loading work.datapath_sv_unit
# Loading work.datapath
# Loading work.ir_sv_unit
# Loading work.ir
# Loading work.register
# Loading work.alu_sv_unit
# Loading work.alu
# Loading work.pc_register
# Loading work.regfile
# Loading work.cmp_sv_unit
# Loading work.cmp
# Loading work.fourmux
# Loading work.twomux
# Loading work.eightmux
# Loading work.sixmux
# Loading work.riscv_formal_monitor_rv32i
# Loading work.riscv_formal_monitor_rv32i_isa_spec
# Loading work.riscv_formal_monitor_rv32i_insn_add
# Loading work.riscv_formal_monitor_rv32i_insn_addi
# Loading work.riscv_formal_monitor_rv32i_insn_and
# Loading work.riscv_formal_monitor_rv32i_insn_andi
# Loading work.riscv_formal_monitor_rv32i_insn_auipc
# Loading work.riscv_formal_monitor_rv32i_insn_beq
# Loading work.riscv_formal_monitor_rv32i_insn_bge
# Loading work.riscv_formal_monitor_rv32i_insn_bgeu
# Loading work.riscv_formal_monitor_rv32i_insn_blt
# Loading work.riscv_formal_monitor_rv32i_insn_bltu
# Loading work.riscv_formal_monitor_rv32i_insn_bne
# Loading work.riscv_formal_monitor_rv32i_insn_jal
# Loading work.riscv_formal_monitor_rv32i_insn_jalr
# Loading work.riscv_formal_monitor_rv32i_insn_lb
# Loading work.riscv_formal_monitor_rv32i_insn_lbu
# Loading work.riscv_formal_monitor_rv32i_insn_lh
# Loading work.riscv_formal_monitor_rv32i_insn_lhu
# Loading work.riscv_formal_monitor_rv32i_insn_lui
# Loading work.riscv_formal_monitor_rv32i_insn_lw
# Loading work.riscv_formal_monitor_rv32i_insn_or
# Loading work.riscv_formal_monitor_rv32i_insn_ori
# Loading work.riscv_formal_monitor_rv32i_insn_sb
# Loading work.riscv_formal_monitor_rv32i_insn_sh
# Loading work.riscv_formal_monitor_rv32i_insn_sll
# Loading work.riscv_formal_monitor_rv32i_insn_slli
# Loading work.riscv_formal_monitor_rv32i_insn_slt
# Loading work.riscv_formal_monitor_rv32i_insn_slti
# Loading work.riscv_formal_monitor_rv32i_insn_sltiu
# Loading work.riscv_formal_monitor_rv32i_insn_sltu
# Loading work.riscv_formal_monitor_rv32i_insn_sra
# Loading work.riscv_formal_monitor_rv32i_insn_srai
# Loading work.riscv_formal_monitor_rv32i_insn_srl
# Loading work.riscv_formal_monitor_rv32i_insn_srli
# Loading work.riscv_formal_monitor_rv32i_insn_sub
# Loading work.riscv_formal_monitor_rv32i_insn_sw
# Loading work.riscv_formal_monitor_rv32i_insn_xor
# Loading work.riscv_formal_monitor_rv32i_insn_xori
# Loading work.riscv_formal_monitor_rv32i_rob
# ** Warning: (vsim-3008) /job/student/hvl/top.sv(29): [CNNODP] - Component name (regfile) is not on a downward path.
#    Time: 0 ps  Iteration: 0  Instance: /mp1_tb File: /job/student/hvl/top.sv
# ** Error: (vsim-3043) /job/student/hvl/top.sv(29): Unresolved reference to 'regfile' in dut.datapath.regfile.
#    Time: 0 ps  Iteration: 0  Instance: /mp1_tb File: /job/student/hvl/top.sv
# ** Error (suppressible): (vsim-2997) /job/student/hvl/top.sv(29): Cannot assign a packed type 'reg' to an unpacked type 'reg[31:0]$[0:31]'.
#    Time: 0 ps  Iteration: 0  Instance: /mp1_tb File: /job/student/hvl/top.sv
# ** Warning: (vsim-3015) /job/student/hdl/datapath.sv(160): [PCDPC] - Port size (1) does not match connection size (2) for port 'select'. The port definition is at: /job/student/hdl/mux.sv(2).
#    Time: 0 ps  Iteration: 0  Instance: /mp1_tb/dut/datapath/pcmux File: /job/student/hdl/mux.sv
# Error loading design
# End time: 22:13:06 on Feb 09,2020, Elapsed time: 0:00:00
# Errors: 2, Warnings: 2

```

</details>


### Targeted Tests: 
<ul>
<li> <b>and</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>and_add_with_zero</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>beq</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>bge</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>bgeu</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>blt</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>bltu</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>bne</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>cp1_longer</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>jal</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>lb_unsigned</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>lh_signed</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>lw_aligned</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>lw_sw_all</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>or</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>ori</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>sh</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>sll</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>slli</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>slti</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>sltiu</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>srai</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>srai_neg</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>srl</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>srl_neg</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>srli</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>srli_neg</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>sw_aligned</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>waw</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>xor</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
<li> <b>xori</b> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/74/Ambox_warning_yellow.svg/40px-Ambox_warning_yellow.svg.png" alt="error" width="13" height="13" ></img><details>
<summary>Error Occurred</summary>

```
An error occured when running this test.
If your code did not successfully compile, that is likely the reason.
If your code did compile, then please reach out to a TA on Piazza
```

</details>
</li>
</ul>

[success]: https://upload.wikimedia.org/wikipedia/commons/thumb/0/03/Green_check.svg/13px-Green_check.svg.png 
[failure]: https://upload.wikimedia.org/wikipedia/en/thumb/b/ba/Red_x.svg/13px-Red_x.svg.png 