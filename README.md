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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Priyanka S

RegisterNumber:24900022


**RTL realization**

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

![Screenshot 2024-12-07 105732](https://github.com/user-attachments/assets/febb306d-7ba0-44b2-ad6e-6ddb093c360a)


**Output:**

![Screenshot 2024-12-07 103138](https://github.com/user-attachments/assets/ad5488d7-faf2-4641-81bc-45fdb7680300)

![Screenshot 2024-12-07 104121](https://github.com/user-attachments/assets/bb7a7516-7f58-472c-bfd5-3fd9cb98a291)


**RTL**
![Screenshot 2024-12-07 103034](https://github.com/user-attachments/assets/8942ca71-7b10-468b-a121-87bcb3a46e43)

![Screenshot 2024-12-07 110535](https://github.com/user-attachments/assets/2df2765c-3a03-406d-a65d-f5c4cc1f85d5)


**Timing Diagram**



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

