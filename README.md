# Verilog-Project-
make 4 operations between 2integers in 3-bit 
## The Instructions
##
### The input is two selection inputs, and two signed integers in 2's complement form: A and B, each integer is 3-bits.
### The output is a signed integer in 2's complement from: G, its size is 3-bits.
### When the selection inputs are 00, G = A-1
### When the selection inputs are 01, G = A+B
### When the selection inputs are 10, G = A-B
### When the selection inputs are 11, G = -B
##
## How to Run:
### 1-open CMD in the project folder
### 2-write --> iverilog -o circuit.vl.out circuit.vl
### 3-write --> vvp circuit.vl.out
