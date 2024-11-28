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

![Screenshot 2024-11-28 111223](https://github.com/user-attachments/assets/0f2461d2-88bf-4ee2-8b89-87e577e1d264)

**Procedure**

**Full Adder:**
1.Open Quartus II and create a new project.
2. Use schematic design entry to draw the full adder circuit.
3. The circuit consists of XOR, AND, and OR gates.
4. Compile the design, verify its functionality through simulation.
5. Implement the design on the target device and program it.

**Full Subtractor:**
1. Follow the same steps as for the full adder.
2. Draw the full subtractor circuit using schematic design.
3. The circuit includes XOR, AND, OR gates to perform subtraction.
4. Compile, simulate, implement, and program the design similarly to the full adder.
   
**Program:**

Full Adder

![Screenshot 2024-11-28 105515](https://github.com/user-attachments/assets/d0a90119-ab18-418e-ad02-786eed1b51f3)

Full Subtractor

![Screenshot 2024-11-28 111346](https://github.com/user-attachments/assets/260ff7cf-cef5-430d-945e-5cafb09eb247)


Developed by:Arunsamy D, RegisterNumber:24900591


**RTL Schematic**

Full Adder

![Screenshot 2024-11-28 105527](https://github.com/user-attachments/assets/88edcd81-36b3-45ab-a744-ef3106289230)


Full Subtractor

![Screenshot 2024-11-28 110526](https://github.com/user-attachments/assets/ea5d366f-0ba7-4737-87ca-a4141dd45271)


**Output Timing Waveform**

Full Adder

![Screenshot 2024-11-28 105504](https://github.com/user-attachments/assets/2857563a-8147-4320-ac9f-647b3f760367)

Full Subtractor

![Screenshot 2024-11-28 110709](https://github.com/user-attachments/assets/73307672-02e9-4e38-9864-7aa26a69a1a0)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



