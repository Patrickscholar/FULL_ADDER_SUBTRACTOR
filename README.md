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
i)FULL ADDER

<img width="781" alt="Screenshot 2024-11-29 at 7 45 10 PM" src="https://github.com/user-attachments/assets/37c65e89-80b6-4edd-82d8-ae786043fdb8">

ii)FULL SUBTRACTOR

<img width="787" alt="Screenshot 2024-11-29 at 7 48 00 PM" src="https://github.com/user-attachments/assets/ee87a839-25cd-40b1-ae8e-7b702da30d28">

**Procedure**

Write the detailed procedure here

**Program:**
i)FULL ADDER

<img width="352" alt="Screenshot 2024-11-29 at 7 18 28 PM" src="https://github.com/user-attachments/assets/d59a2b21-059e-4d99-a96e-2d90ce319d59">

ii)FULL SUBTRACTOR

<img width="416" alt="Screenshot 2024-11-29 at 7 10 25 PM" src="https://github.com/user-attachments/assets/52d4407d-7688-4264-b141-475bc3d56fa3">

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
<img width="1470" alt="Screenshot 2024-11-29 at 7 20 00 PM" src="https://github.com/user-attachments/assets/cf94ce51-daf9-4af6-9ec2-12e1169b4c08">
<img width="1458" alt="Screenshot 2024-11-29 at 7 01 43 PM" src="https://github.com/user-attachments/assets/7e654765-a97e-4c98-881a-9d9891e22edc">

**Output Timing Waveform**

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



