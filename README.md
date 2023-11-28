# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 A combinational circuit is a circuit in which the output depends on the present combination of
inputs. Combinational circuits are made up of logic gates. The output of each logic gate is
determined by its logic function. Combinational circuits can be made using various logic gates,
such as AND gates, OR gates, and NOT gates.

## Procedure
1. Create a New Project:
Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the
wizard's instructions to set up your project, including specifying the project name, location, and
target device (FPGA).
2. Create a New Design File:
Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the
wizard's instructions to set up your project, including specifying the project name, location, and
target device (FPGA).
3. Write the Combinational Logic Code:
README.md
*Open the newly created Verilog or VHDL file and write the code for your combinational logic.
4.Compile the Project:
*To compile the project, click on "Processing" > "Start Compilation" in the menu. *Quartus will
analyze your code, synthesize it into a netlist, and perform optimizations based on your target
FPGA device.
5.Analyze and Fix Errors:
*If there are any errors or warnings during the compilation process, Quartus will display them
in the Messages window. *Review and fix any issues in your code if necessary. *View the RTL
diagram.
6.Verification: *Click on "File" > "New" > "Verification/Debugging Files" > "University Program
VWF".
*Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" >
Click on Node Finder > Click On "List" > Select All. Program: *Give the Input Combinations
according to the Truth Table and then simulate the Output Waveform.
## Program:


Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: keerthivasan M
RegisterNumber: 23014067
![de2 2](https://github.com/rdxkeerthi/Experiment--02-Implementation-of-combinational-logic-/assets/147473120/c2ed5ab6-70f5-415e-8840-a7d62660bcae)
## RTL realization
![de2 3](https://github.com/rdxkeerthi/Experiment--02-Implementation-of-combinational-logic-/assets/147473120/9defe58e-3984-4fd8-90d5-70dbd2504888)

## Output:

## Truth Table
![de2](https://github.com/rdxkeerthi/Experiment--02-Implementation-of-combinational-logic-/assets/147473120/09af1344-a15e-4442-87d1-a6178e78d7f4)


## Timing Diagram
![de2 4](https://github.com/rdxkeerthi/Experiment--02-Implementation-of-combinational-logic-/assets/147473120/bb9e1b09-69d2-4f78-897b-c858dc59ac3a)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
