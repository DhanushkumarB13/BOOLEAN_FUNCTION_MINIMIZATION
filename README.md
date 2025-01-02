### NAME: B. DHANUSH KUMAR
### REG NO: 24900615
# EXPERIMENT NO 2 - Boolean function implementation
# BOOLEAN FUNCTION MINIMIZATION

# AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

# Equipment Required:

Hardware – PCs, Cyclone II , USB flasher </br>
Software – Quartus prime

# Theory

Implementing Boolean functions in Verilog HDL (Hardware Description Language) involves translating the simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The basic building blocks in Verilog is module. The module represent a combinationa circuit. Use logical operators (&, \, ~, ^) to implement Boolean functions directly. Use built-in gate primitives for basic functions: Use University program VWF to verify the functionality of your Verilog modules. Create waveform and check outputs against expected results.

# Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# Program:
![15503ac6-1c5c-4c27-ac37-d050276d14c9](https://github.com/user-attachments/assets/176b4be3-45e6-41f5-ac2b-ed16231ee86c)


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


# TRUTH TABLE
![a0b65e26-bc1f-4264-829d-8c8d6e75ef6a](https://github.com/user-attachments/assets/a4068887-cd6a-4683-b3d1-ac40a7e8bcee)

**RTL**
![b56e66a7-080f-4c56-ad0f-93ebabbefc0c](https://github.com/user-attachments/assets/cfd309b1-529d-456d-9ae8-e5cd12624559)

**Timing Diagram**
![88f2c270-a535-468a-ac7c-b7536251a5c7](https://github.com/user-attachments/assets/be4290d8-761f-4283-9acd-77c14c76fc2d)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

