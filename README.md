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

![WhatsApp Image 2025-10-08 at 16 04 34_bce71ac1](https://github.com/user-attachments/assets/bc81acb5-16a9-49d6-bdf0-943cbed9964b)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 
```
``` Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Himadri S
RegisterNumber:25011498
```

**RTL realization**


<img width="741" height="630" alt="image" src="https://github.com/user-attachments/assets/12ec2885-19ee-4f0f-88f8-4e91206e1474" />



**RTL**


<img width="928" height="555" alt="image" src="https://github.com/user-attachments/assets/f1f21016-129f-4ee7-ba6d-698c57300328" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

