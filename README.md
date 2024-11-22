# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

# Synthesis RTL Schematic :
![WhatsApp Image 2024-11-22 at 12 02 44_a79b1e66](https://github.com/user-attachments/assets/ee1540a0-f849-4aa1-ba63-b01ed6092ac5)

# Area report:
![WhatsApp Image 2024-11-22 at 12 02 43_6552f55f](https://github.com/user-attachments/assets/636538a3-b627-41b7-9f73-adac0a3f9f5b)

# Power Report:
![WhatsApp Image 2024-11-22 at 12 02 43_f331eb51](https://github.com/user-attachments/assets/634c4dee-a013-4915-b585-770cc61f450e)

# Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
