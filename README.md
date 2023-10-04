# RV32I Datapath with Instructions - Logisim

## Introduction

This GitHub repository contains a RV32I Datapath built using Logisim, a popular digital circuit design and simulation tool. The RV32I architecture is a 32-bit RISC-V architecture that is widely used in the embedded systems and microcontroller domains. This project provides a visual representation of the RV32I datapath and includes a set of sample instructions to help you understand how the datapath processes instructions.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Project Structure](#project-structure)
3. [Using the Datapath](#using-the-datapath)
4. [Understanding the Datapath](#understanding-the-datapath)
5. [Contributing](#contributing)
6. [License](#license)

## Getting Started

To get started with this RV32I Datapath project, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/rv32i-datapath-logisim.git
   ```

2. **Open in Logisim**: Open Logisim and load the project by opening the `.circ` file located in the `logisim` directory of this repository.

3. **Simulate the Datapath**: You can now simulate the RV32I datapath and execute instructions to observe the flow of data through the pipeline.

## Project Structure

The project structure is organized as follows:

- `logisim/`: Contains the Logisim project file (`rv32i-datapath.circ`) and the associated circuit components.
- `instructions/`: Includes a set of sample RV32I instructions in text format. These instructions can be used to test and observe the datapath's behavior.

## Using the Datapath

Once you have opened the project in Logisim, follow these steps to use the RV32I datapath:

1. **Load Instructions**: Load a set of instructions from the `instructions/` directory by editing the instruction memory component in Logisim. You can copy and paste instructions from the text files provided.

2. **Run the Simulation**: Start the simulation and observe how each instruction is processed by the datapath. Pay attention to the flow of data through the various pipeline stages.

3. **Inspect Registers**: Use the register file component in Logisim to inspect the contents of registers before and after executing instructions. This will help you understand how instructions affect the register values.

4. **Analyze Data Path**: Analyze the datapath by following the connections and signals through various components like the ALU, control unit, and memory stages.

## Understanding the Datapath

To gain a deeper understanding of the RV32I datapath and how instructions are executed, refer to the documentation or comments within the Logisim project file (`rv32i-datapath.circ`). Additionally, you can study the provided sample instructions in the `instructions/` directory to see how different instruction types (e.g., R-type, I-type) are processed.

## Contributing

Contributions to this project are welcome! If you have improvements, bug fixes, or additional features to add, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and test them.
4. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to explore the RV32I datapath and experiment with different instructions. If you have any questions or encounter any issues, please don't hesitate to open an issue on this GitHub repository. Happy simulating!
