
# Arch-final-project
***VISUALIZING VERILOG***

# Project Goals and Description

Our team consists of Michelle Ding, Jasper Lee, Luke Lu, and Cooper Wilk.

We designed a fully-functional Verilog interpreter and visualizer to display Verilog circuits.

We achieved our end goal of sucessfully applying it to our pipelined preprocessor.

# Verifun
- Parser: Parses a “.v” Verilog file into intermediate Verifun™ format.
Outputs a “.vf” file.

- Verifun: Takes the interpreted output file from the parser and feeds it into the visualizer.
(named after the fun-like semantics and based off Verilog)

- Visualizer: Take intermediate Verifun™ file as input.
Displays a window with the circuit design.


# Formats
- wire/reg: "wire/reg" [num_bits]name operand arg1[bitrange] arg2[bitrange]...

- literal assignment: wire y = 5 
wire .temp1 -- 5
wire y = .temp1

- bit select: wire a = s0[1:0]
wire .temp2 [1:0] s0
wire a = .temp2

- modules: module name .ouput1 .output2 ... # .input1 .input2 ...

# Future Work
- Manual checking only
- Dark mode :)
- 2D arrays (registers and memory)
- For-loops
- Blocking assignments
- Multi-input gates
- Expand modules
- Intermediate wire sizes
- Optimizing if-else statements
- Wire highlighting
- GTKWave-style debugger


# References
https://zetcode.com/gfx/java2d/

https://class.ece.uw.edu/cadta/verilog/operators.html

