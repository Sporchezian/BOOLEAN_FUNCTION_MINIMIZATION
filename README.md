# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:25017994
```
module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**RTL realization**

<img width="1461" height="850" alt="Screenshot 2025-11-12 113827" src="https://github.com/user-attachments/assets/574a86c5-d83b-4c9a-9fd4-569c7a6e677f" />

**Output-Timing Diagram:**

<img width="1905" height="364" alt="Screenshot 2025-11-12 114533" src="https://github.com/user-attachments/assets/4c5f1a30-7f5c-40c4-8242-f80c4cc6e51d" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

