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
```
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module exp22(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```
Developed by: KIRUPASAGAR
RegisterNumber:212224230126

**Output:**

**RTL**
![424071003-9a351987-210d-483a-89a6-22d283e8eb68](https://github.com/user-attachments/assets/f1c3102d-16e8-4429-baa6-0b678c5717f6)
![424071070-51e89129-d92e-4037-a80e-57af3d512a09](https://github.com/user-attachments/assets/1620f5dd-c449-4760-85ba-b883753b6c1e)

**Timing Diagram**
![424071171-80c85123-284c-44ee-8561-a50df9cbf2a8](https://github.com/user-attachments/assets/c71b5853-4019-4152-b67c-405b4b18d510)
![424072566-1ef0b161-5b87-48b7-b2cb-b8101a26209e](https://github.com/user-attachments/assets/4189f966-9638-42bf-b469-f9e057a4b223)

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

