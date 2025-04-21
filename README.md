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

**Procedure**
1. Type the program in Quartus software.

2. Compile and run the program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combinations generate the timing diagram.


**Program:**

Developed by: VARUN J C  

RegisterNumber:212224240179

![434139500-757fc223-a773-4fe1-9bc1-0c960a93248a](https://github.com/user-attachments/assets/0e4491f1-5c36-4e1b-9422-a4df14be47b8)


**TRUTH TABLE**

![434139607-7a090a19-e76d-4284-ac53-3fb7645767f7](https://github.com/user-attachments/assets/7230eee9-39a6-448b-aafc-ce80e951e272)

![434139655-78a262a0-ab01-49f4-a98b-e65a1aa074ec](https://github.com/user-attachments/assets/57681e2f-b884-4b34-9990-e706a2575d1c)

**RTL**

![434139760-2d6ada3a-7882-48f7-ad3b-379cb4550b1f](https://github.com/user-attachments/assets/b58e5a12-810a-45fc-bf90-ea5b4d46cda0)

**WAVEFORM**

![434140391-944bfec1-e456-4da9-8313-a7dd466eabd1](https://github.com/user-attachments/assets/eaaf2cec-a5c3-4c54-8b69-a90b5064c32f)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



