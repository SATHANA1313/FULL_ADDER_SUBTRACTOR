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


![Screenshot 2024-12-27 211914](https://github.com/user-attachments/assets/8c23fb11-f03f-45b0-9342-04997c3ca392)



**Program:**

![Screenshot 2024-12-27 211927](https://github.com/user-attachments/assets/8302f706-94a2-4a1c-9a0b-12de35e12494)

 
 Developed by:SATHANA.V
 
 RegisterNumber:24901144


**RTL Schematic**


![Screenshot 2024-12-27 211954](https://github.com/user-attachments/assets/d1887f9f-6b0e-42a6-9755-e716d2edb646)

**Output Timing Waveform**

![Screenshot 2024-12-27 212009](https://github.com/user-attachments/assets/8bf7a40e-5af3-45eb-8956-ba0d6700b6e0)

**result**


Thus the full adder and full sudractor circuits are designed and truth table is verified using quartus software.


