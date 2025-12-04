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
module BOOLEAN (
    input A,
    input B,
    output F
);

assign F = A | B;

endmodule
```


Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

**Developed by:** Jeeva Nivas M 
**RegisterNumber:** 25015894 


**RTL realization**
![RTL EX2 I](https://github.com/user-attachments/assets/190ee793-b9de-4b82-aad8-8af51c0cc643)
![RTL EX2 II](https://github.com/user-attachments/assets/fe0253e1-fe3e-4695-a735-c84406c04961)


**Output:**

**RTL**

**Timing Diagram**
![WAVE EX2 I](https://github.com/user-attachments/assets/5a26b7d1-74bd-441d-a581-f2bb3aae299e)
![WAVE EX2 II](https://github.com/user-attachments/assets/21a7186b-4827-4305-b073-bf804a4a7961)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

