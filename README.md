# MecServerDesign

## Intel CPU for MecServer (survey)
  - [Skylake-sp buyer's guide](https://www.pugetsystems.com/labs/hpc/Intel-Scalable-Processors-Xeon-Skylake-SP-Purley-Buyers-Guide-1077/)

### Price vs Performance 
  - Multi-threaded : 6154 ($3543,18C) : it has great performance and value
    8168 6154, 6148, 6140, 6130, 6126, 4114 These have 24, 18, 20, 18, 16, 12, and 10 cores.
  - Memory I/O Bound : 8168 ($5890, 24C), 6148 ($3078, 20C), 6140($2451, 18C)
    6144, 6134, 5122 or 8168, 6148, 6140 The first group has large Cache per Core, and the second has higher core count and larger overall shared L3 Cache.
  - GPU based (CPU doesn't Matter) : 6128 ($1697)
    6128, 5122, 4114, 4112 The first 2 would be excellent for supporting a system using GPU's for compute where there is still need for fast CPU processing and fast memory transport to and from the GPU's. The last 2 are simply the lowest cost processors on my list and would be good when CPU really doesn't matter much. 

## Xilinx FPGA for Acceleration
### SKT NUGU Acceleration with KCU1500
   - [KCU1500] (https://www.xilinx.com/products/boards-and-kits/dk-u1-kcu1500-g.html#hardware)
   - [Xilinx FPGA Open Source ] (https://github.com/Xilinx/SDAccel_Examples)

### FPGA Acceleration Presentation
   - [ACAP Presentation I] (https://www.nimbix.net/wp-content/uploads/2018/06/Adopting-Cloud-FPGAs-to-Accelerate-Enterprise-Workloads-Xilinx.pdf)
   - [ACAP Presentation II](files.shareholder.com/downloads/XLNX/0x0x975133/E4C64D2B-F39F-4A04-AB7E-7B5E0B04122B/Xilinx_Press_Presentation.pdf)

