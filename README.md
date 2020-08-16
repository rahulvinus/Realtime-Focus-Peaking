# GSOC-Realtime-Focus-Peaking
The VHDL kernel implements Realtime focus peaking algorithm on a stream of incoming pixels <br/>
Implementation: Zedboard (Xilinx ZYNQ-SoC), Organization: Apertus - Google Summer of Code 2018 <br/>
Project overview: https://medium.com/@rahul.vinus/google-summer-of-code-2018-c65625c65f97  <br/>
(1) GSOC_18_presentation.pdf gives a detailed description of the project <br/>
(2) kernel_top.vhd is the top level module of the focus peaking module<br/>
(3) line_buffer_one_two.vhd is the vhdl entity for line buffer module<br/>
(4) line_buffer_test.vhd is the test bench for line buffer module<br/>
(5) sobel_kernel.vhd is the arithematic unit of the peaking module<br/>
(6) sobel_test.vhd is the test bench for the sobel_kernel<br/>
(7) top_kernel_tb.vhd is the test bech for the top level module<br/>
