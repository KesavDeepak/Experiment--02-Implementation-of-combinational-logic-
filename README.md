# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2= xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory:
 A combinational circuit is a circuit in which the output depends on the present combination of inputs. Combinational circuits are made up of logic gates. The output of each logic gate is determined by its logic function. Combinational circuits can be made using various logic gates, such as AND gates, OR gates, and NOT gates.


## Procedure:
Create a New Project:

Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA). Create a New Design File:

Once the project is created, right-click on the project name in the Project Navigator and select "Add

New File." Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description

language. Write the Combinational Logic Code:

Open the newly created Verilog or VHDL file and write the code for your combinational logic. Compile the Project:

To compile the project, click on "Processing"> "Start Compilation" in the menu. Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

Analyze and Fix Errors:

If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window. Review and fix any issues in your code if necessary. View the RTL diagram 6.Verification:

Click on "File"> "New"> "Verification/Debugging Files" > "University Program VWF Once Waveform is created Right Click on the Input/Output Panel>" Insert Node or Bus" > Click on Node Finder > Click On "List"> Select All. Give the Input Combinations according to the Truth Table and then simulate the Output waveform
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
### Developed by: KESAV DEEPAK SRIDHARAN
### RegisterNumber: 23002011
*/
![c34618a5-a6a4-4370-ab6f-1b0d6a772c41](https://github.com/KesavDeepak/Experiment--02-Implementation-of-combinational-logic-/assets/139336019/dd940350-8537-4ccf-b5d5-9d1063d1a0ef)
## Truth Table:
![ca6dff1e-c520-4585-aa2f-53836ef62271](https://github.com/KesavDeepak/Experiment--02-Implementation-of-combinational-logic-/assets/139336019/1a5196fd-cf2f-4e10-a8d0-5f0457b0d8b1)

## RTL realization:
![b1139b8a-174a-4643-83c8-abf927cc2e43](https://github.com/KesavDeepak/Experiment--02-Implementation-of-combinational-logic-/assets/139336019/8aa2a79b-d8cd-475b-b354-91ab46964349)

## Output:

## Timing Diagram:
![bd1ea460-50d9-4315-93f4-ae935139b123](https://github.com/KesavDeepak/Experiment--02-Implementation-of-combinational-logic-/assets/139336019/2886b087-9b9c-4d6c-a1d2-93ec02cc1f9f)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
