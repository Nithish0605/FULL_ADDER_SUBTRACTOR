NAME: NITHISH S 

REGISTER NO: 212224240105

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

**Procedure**
1. Type the program in Quartus software.

2. Compile and run the program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combinations generate the timing diagram.


**Program:**
NAME : NITHISH S
REGNO : 212224240105

![434139500-757fc223-a773-4fe1-9bc1-0c960a93248a](https://github.com/user-attachments/assets/bc90bceb-74ca-4eee-a296-79f8ad98cb58)



**TRUTH TABLE**

![434139607-7a090a19-e76d-4284-ac53-3fb7645767f7](https://github.com/user-attachments/assets/d1e8562f-78d3-45c0-87c4-2f2c8fdaa742)


![434139655-78a262a0-ab01-49f4-a98b-e65a1aa074ec](https://github.com/user-attachments/assets/810cdbc8-4d5c-4814-bc92-ecdb319c97f4)


**RTL**

![434139760-2d6ada3a-7882-48f7-ad3b-379cb4550b1f](https://github.com/user-attachments/assets/da4b73f3-016c-4135-ad48-10e45dcc767c)

**WAVEFORM**

![434140391-944bfec1-e456-4da9-8313-a7dd466eabd1](https://github.com/user-attachments/assets/44b36c12-c5d9-43c2-9683-8842a65d8f27)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



