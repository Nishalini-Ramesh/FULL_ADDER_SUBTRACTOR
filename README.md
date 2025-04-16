# NAME : NISHALINI R
# REG NO: 212224040222

# EXP4 FULL ADDER SUBTRACTOR


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

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

Write the detailed procedure here

**Program:**

![Screenshot 2025-04-15 110501](https://github.com/user-attachments/assets/240412f7-6141-4786-97be-418aea4ba8b2)

**TRUTH TABLE**

![Screenshot 2025-04-15 114141](https://github.com/user-attachments/assets/cc240f67-1151-4115-8939-0005cc1d5600)

![Screenshot 2025-04-15 114216](https://github.com/user-attachments/assets/fa4d499e-32fd-4583-9ef2-1d7ad4afa9e0)

**RTL**

![Screenshot 2025-04-15 113013](https://github.com/user-attachments/assets/3845111a-23b4-4b6e-901a-8cdd65710e79)


**Waveform**

![Screenshot 2025-04-16 084155](https://github.com/user-attachments/assets/0c997d1d-9148-462b-8de8-d15572a85c48)

**RESULT**


Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



