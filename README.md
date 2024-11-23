## EXP4:FULL ADDER AND SUBTRACTOR
# NAME:JASSIR SULTHAN K
# REGISTRATION NO:24901084
Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**
![WhatsApp Image 2024-11-23 at 21 33 24_37ab2c9c](https://github.com/user-attachments/assets/5fe99ca0-3133-4012-b3aa-a733aafd82f7)


Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin
![WhatsApp Image 2024-11-23 at 21 33 46_3e267dbd](https://github.com/user-attachments/assets/43e56a33-5c45-4c66-91fe-b9e6b82f0011)

**Figure -1 FULL ADDER**

**Full Subtractor**
![WhatsApp Image 2024-11-23 at 21 34 13_e9bf9885](https://github.com/user-attachments/assets/a6dfd1f3-cfc0-4d5a-a173-21b6aeec7112)


A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.
![WhatsApp Image 2024-11-23 at 21 29 17_42f18f72](https://github.com/user-attachments/assets/a8092daf-7318-450f-9ad4-c81c199249b8)


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**
![WhatsApp Image 2024-11-23 at 21 36 42_e5219e02](https://github.com/user-attachments/assets/804c41af-d5f5-4868-b93d-b875d9511184)
![WhatsApp Image 2024-11-23 at 21 37 32_87bdff40](https://github.com/user-attachments/assets/4d420daa-341a-4b0e-b032-2a8f3c1ff47f)




