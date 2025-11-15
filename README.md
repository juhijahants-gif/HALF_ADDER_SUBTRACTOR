# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

**Half adder**
<img width="490" height="264" alt="Screenshot 2025-11-15 200337" src="https://github.com/user-attachments/assets/429a11d2-0c02-4e11-9ba2-005ca4156aa2" />

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
**Half subtractor**
<img width="563" height="246" alt="Screenshot 2025-11-15 200610" src="https://github.com/user-attachments/assets/26fd9e26-a5ee-455a-a3c6-8d7ea586d199" />

Developed by: JUHI JAHAN T S RegisterNumber: 25011334*/

**RTL Schematic**
**Half adder**
![WhatsApp Image 2025-11-15 at 20 06 37_78c84c6b](https://github.com/user-attachments/assets/e7ab6f14-32d7-4573-a145-ddf676130404)

**Half subtractor**
![WhatsApp Image 2025-11-15 at 20 13 58_a4d0d746](https://github.com/user-attachments/assets/ff6f2d03-8509-46ba-894d-b3186d311058)


**Output/TIMING Waveform**
**Half adder**

![WhatsApp Image 2025-11-15 at 20 15 46_f6463ce1](https://github.com/user-attachments/assets/65d41484-8fd0-472f-a330-1c158abe7868)

**Half subtractor**
![WhatsApp Image 2025-11-15 at 20 17 03_9d71325b](https://github.com/user-attachments/assets/5611e632-1867-4064-9a06-6ac730cc35bc)



**Result:** Thus the a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using Verilog programming .
