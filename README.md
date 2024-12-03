# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24002206

i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

**RTL**
f1

![exp2 f1](https://github.com/user-attachments/assets/9d4a3525-bf91-45d1-87ab-c0af294fed15)

f2

![exp2 f2 logic gate](https://github.com/user-attachments/assets/c68bb9e8-a1e4-4631-bb83-954d92994b8a)



**Output:**
f1

![exp2 f1 op](https://github.com/user-attachments/assets/52e655d5-7c1e-4e15-b0e6-28f0825708b1)

f2

![exp2 f2 op](https://github.com/user-attachments/assets/07dcd22d-fbb0-42e8-acb7-98b8392b7cc7)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

