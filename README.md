# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:swetha.c 
RegisterNumber:24901183*/
```
```
module exp2(f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and(f_and,a,b);
or(f_or,a,b);
not(f_not,a);
nor(f_nor,a,b);
nand(f_nand,a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule
```

**Output:**
![exp2logicgatediagramWhatsApp Image 2024-11-06 at 02 25 40_b0f64381](https://github.com/user-attachments/assets/3edf40a5-80d0-4fbd-bb3e-8d8e79abbf3e)


**Timing Diagram**
![exp2logicgate2WhatsApp Image 2024-11-05 at 08 20 32_928fab7a](https://github.com/user-attachments/assets/f69d77d0-59e4-4ed8-b003-babf66be48d7)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

