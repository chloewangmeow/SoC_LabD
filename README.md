# SoC LabD Group 10
## Introduction
In this lab, we replace the BRAM with SDRAM to store the data and the firmware code. We’ve done three tasks in this lab: 
1. Replace the adder with matrix multiplier
2. Add the prefetch function in SDRAM controller
3. Separate data and firmware into two banks in SDRAM

## File arrangement
### Design sources
* **firmware**: `testbench/counter_la/counter_la.c`
* **testbench**: `testbench/counter_la/counter_la_tb.v`
* **sdram_controller**: `rtl/user/sdram_controller.v`
* **sections.lds**: `firmware/sections.lds`
### Report
* `Report.pdf`

## Simulation
Run iverilog simulation
```sh
cd ~/testbench/counter_la
source run_sim
```

