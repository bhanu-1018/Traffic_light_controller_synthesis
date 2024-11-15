# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus# Traffic_light_controller_Synthesis

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

Synthesis RTL Schematic :
![WhatsApp Image 2024-11-15 at 13 14 20_9d248232](https://github.com/user-attachments/assets/ed888820-9fe6-4e37-8310-7797526cdb38)

Area report:
![image](https://github.com/user-attachments/assets/71b90651-bfe5-46bd-b5b9-61d0484ccfdd)

Power Report:
![image](https://github.com/user-attachments/assets/0ee7b4a5-61da-4244-a62f-23495cdeafd7)

Timing report:
![image](https://github.com/user-attachments/assets/44835b2a-e225-433d-8984-a1b0369ea276)

Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.


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

Synthesis RTL Schematic :

Area report:

Power Report:

Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
