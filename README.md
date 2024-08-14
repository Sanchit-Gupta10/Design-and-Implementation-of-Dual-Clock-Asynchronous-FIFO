# Design-and-Implementation-of-Dual-Clock-Asynchronous-FIFO
Dual Clock Asynchronous FIFO with synchronizers
Created a 64 X 8 Asynchronous FIFO for burst data transfer between different clock domains.
Used 7-bit gray code counter and 2-flop synchronizer for clock domain crossing synchronization.
Verified FIFO operation for Full & Empty conditions using a 50 MHz write clock and 10 MHz read
clock, achieving positive setup and hold timing slacks with Intel Timing Analyzer.
