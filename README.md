# OR Gate using Verilog

This project implements a basic OR gate using Verilog HDL and verifies it using Icarus Verilog and GTKWave.

# Files
- or_gate.v:OR gate design
- tb_or_gate.v:Testbench
- or.vcd:Waveform output

# How to Run
```bash
iverilog -o or or_gate.v.txt tb_or_gate.v.txt
vvp or
gtkwave or.vcd
