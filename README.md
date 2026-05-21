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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

i) module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii) module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule

Developed by: VISHNU.V
RegisterNumber: 212225040494


**RTL realization**

<img width="762" height="398" alt="image" src="https://github.com/user-attachments/assets/3c7f08ea-0bf7-4276-af3f-d8a6b8d911e3" />


**Output:**

<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/65398ce1-1144-4bb5-9d2a-4bbb5e4b057c" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

