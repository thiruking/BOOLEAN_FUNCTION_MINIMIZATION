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
module experiment2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/
**TRUTH TABLE**
![image](https://github.com/user-attachments/assets/b2e6f509-64de-444c-a5fa-e40898d2b160)
![image](https://github.com/user-attachments/assets/0ff0cc8d-a388-4297-ac03-7771303160b7)



**RTL realization**
![Screenshot 2024-11-05 165148](https://github.com/user-attachments/assets/67542647-c6fb-4065-9d0f-0ce48d11cae0)


**Output:**

**RTL**
![Screenshot 2024-11-19 142646](https://github.com/user-attachments/assets/4bfc069b-5f93-4d1a-b89d-8529cbe889b7)



**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

