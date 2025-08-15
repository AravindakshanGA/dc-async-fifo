# dc-async-fifo
A Dual Clock Asynchronous FIFO design in Verilog

RTL Written by ARAVINDAKSHAN G A

◦ Designed a 32-bit wide asynchronous FIFO with a Depth of 256, featuring Pessimistic Full and Empty flags
◦ Realized 2-flop Synchronizers and Gray Code Encoding to avoid Metastability and Multi-bit Transitions
◦ Validated with 50 MHz write & 40 MHz read clock rates for various patterns of 512-burst input in ModelSim
