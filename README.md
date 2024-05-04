
## 32-bit Non-Pipelined RISC-V Processor Design

Welcome to my 32-bit non-pipelined RISC-V processor design project! This project showcases my individual effort in designing a RISC-V processor using microprogramming techniques, featuring a 3-bus structure.

## Overview

In this project, I implemented the RV32I instruction set architecture, covering various classes of instructions:

- Computational instructions (types R and I)
- Memory access instructions (types I and S)
- Control flow instructions (type SB)

Additionally, I extended the basic implementation by introducing support for two new instructions:

1. **MEMCOPY**: Efficiently copies arrays of size N from one location to another, with N > 1. I also determined the maximum feasible N for this operation.
2. **MUL**: Implements unsigned multiplication functionality, addressing the absence of native multiplication instructions in RV32I.

## Repository Structure

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `src/` directory and explore the source code files.
3. Run simulations using a Verilog simulator (e.g., ModelSim) to verify the functionality.
4. Check out the `testbench/` directory for pre-written test cases to validate the design.

## Future Improvements

In the future, I plan to enhance this project by:

- Implementing additional instructions from the RISC-V ISA extension sets.
- Optimizing the design for performance and efficiency.
- Exploring pipelined architecture for improved throughput.

## Connect with Me

If you're interested in collaborating on this project or discussing processor design, feel free to connect with me on LinkedIn: https://www.linkedin.com/in/isuru-deshapriya-b1a4b2265/

Happy coding! 🚀


