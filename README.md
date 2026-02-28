# Build-a-CPU-Project
This repository contains all the code for all projects in the book "Mission Impossible - Build your own CPU from Scratch".  Projects are organized by chapter.  

Each project folder is a complete FPGA project with all files necessary to build the project on Alchitry Au FPGA board.  The constraints files need to be updated to run on the Au v2 boards.

IMPORTANT CORRECTION:  In the code listed in the book (prior to v1.6), references to the uart transmit module contain the code line: uart.tx.block = 0.  The block parameter has been removed from the module since the book was published.  This line now gives a error, and can simply be removed.  All code here in this repository has been corrected. 

Here are some useful links, referred to in the book:

[Alchitry Boards](https://shop.alchitry.com/collections/products)

[Lucid Reference](https://alchitry.com/tutorials/lucid-reference/)

[Alchitry Labs](https://alchitry.com/alchitry-labs/)

[Vivado Download](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools.html)

[Alchitry Setup Tutorials](https://alchitry.com/tutorials/setup/)
