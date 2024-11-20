# Name : GOPINATHAN P
# Reg no :212222060068
# Exp-5: 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :![Screenshot (51)](https://github.com/user-attachments/assets/e6ef9ff2-b501-4da9-8d38-54382e6de4d5)




#### Area report:![Screenshot (52)](https://github.com/user-attachments/assets/e1b500ad-1479-44a5-bab1-a1a0944ac0ce)



#### Power Report:![Screenshot (53)](https://github.com/user-attachments/assets/55451136-f053-423b-8df8-9850d68c0951)



#### Timing Report:![Screenshot (54)](https://github.com/user-attachments/assets/34ef4661-0510-4e8c-a076-11d76ad2ec1e)



#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
