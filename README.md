# Cache-Memory
A VHDL Cached Memory that supports write-through mode operation

# Specification
The cache takes in 16 bit addresses corresponding to 32 bits of data. The cache block size is 8 bits wide and data is broken into blocks of 4. Bits [15:10] are the tag bits, bits[9:2] are the set index, and bits [1:0] are the offset bits

# Testing
Within this repository is a VHDL memory and verilog testbenches testing the cache memory
