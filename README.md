# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

F1


![image](https://github.com/user-attachments/assets/8eafb114-4ecd-44ea-bcea-cbe7e61f098f)


F2


![image](https://github.com/user-attachments/assets/c4c3dbc9-8dda-4305-9386-86cfa1e4f270)



**Procedure**
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**Program:**


![Screenshot 2025-04-23 200323](https://github.com/user-attachments/assets/49913369-7f10-46bf-ac2f-ff67de9add0e)



/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 


Developed by: V.B.Laksha


Register Number:212224220051

**RTL Schematic**

Boolean function minimization f1


![image](https://github.com/user-attachments/assets/d29fb2b7-2145-4e51-b2cf-ef1fecd8aecf)


Boolean function minimization f2


![image](https://github.com/user-attachments/assets/f3499a15-d06b-45e1-aada-e33f72efa522)



**Output Timing Waveform**


Boolean function minimization f1


![image](https://github.com/user-attachments/assets/a23628cf-0448-4d96-a77f-e23301018956)


Boolean function minimization f2


![image](https://github.com/user-attachments/assets/097e5681-851e-4a93-ad39-1ffc525187d5)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



