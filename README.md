# Task 3: Synthesis of Digital Design

## Objective

To understand the synthesis process by converting a Verilog HDL design into a gate-level netlist using a standard cell library.

## Tools Used

* Verilog HDL
* Synthesis Tool (Synopsys Design Compiler / Cadence Genus)
* Standard Cell Library

## Description

Synthesis is the process of translating an RTL design written in Verilog HDL into a gate-level netlist composed of standard cells available in a technology library.

The synthesis tool reads the RTL description, applies design constraints, maps the logic to available standard cells, and generates reports for timing and area analysis.

## Files Included

* design.sv – RTL design
* synthesis_script.tcl – Synthesis script
* synthesized_netlist.v – Generated gate-level netlist (if available)
* timing_report.txt – Timing analysis report (if available)
* area_report.txt – Area utilization report (if available)

## Flow

1. Read RTL Verilog design.
2. Load standard cell library.
3. Apply timing constraints.
4. Run synthesis.
5. Generate gate-level netlist.
6. Analyze timing and area reports.

## Result

The RTL design was successfully synthesized into a gate-level implementation using standard cells. Timing and area reports were generated to evaluate the design performance.

## Conclusion

This task provided practical exposure to the RTL-to-Gates synthesis flow, standard cell mapping, timing analysis, and generation of gate-level netlists used in ASIC design.
