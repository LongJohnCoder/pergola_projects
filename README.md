# Pergola projects

[Pergola](https://github.com/pergola-fpga/pergola) is an ECP5 FPGA development board.

These are my personal projects that run on Pergola. They are unsupported, probably full of bugs and most likely doing some things incorrectly.

Verilog projects are located in `verilog`. Change working directory to a project and type `make` to build, `make prog` to build and program.

nMigen projects are in `pergola`. To explore the cli, remain in this directory and run `python -m pergola --help` and read the docs for more help. Running blinky is done like so `python -m pergola run blinky`.

Run tests and proofs with `python -m unittest -v`.