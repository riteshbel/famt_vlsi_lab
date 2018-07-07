# Introduction: github repository for maintaining FAMT's VLSI Lab experiments

This github repository contains the following FPGA based lab experiments
- Hashing algorithm implementation
- Sorting algorithm implementation
- SPI sensor integration to FPGA

The experiments are targeted to be implemented in Intel MAX10 FPGA. We will use Intel's MAX10 FPGA development kit
(https://www.altera.com/products/boards_and_kits/dev-kits/altera/max-10-fpga-development-kit.html)

The projects are organised in the following structure
- project_name
  - src - contains VHDL source code
  - par - Place & Route folder. This folder contains all the Quartus tool generated files. 
  - doc - documents and project setting files
