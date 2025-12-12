**ENCODER 8 TO 3 DATAFLOW MODELLING**

**AIM:**

To implement Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables.

**SOFTWARE REQUIRED:**     

Quartus Prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.


![alt text](<Block Diagram Of Encoder.png>)


Figure 01 Block Diagram of Encoder 8 * 3


**Truth Table**

![alt text](<Truth Table of Encoder.png>)



The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:


![alt text](<Screenshot 2025-11-29 113229.png>)


Figure 02 Encoder 8 * 3


**Procedure:**

1.	Type the program in Quartus software.
2.	Compile and run the program.
3.	Generate the RTL schematic and save the logic diagram.
4.	Create nodes for inputs and outputs to generate the timing diagram.
5.	For different input combinations generate the timing diagram.


**Program:**

![alt text](<8 to 3 Encoder Program.png>)

Developed By : Sandya S              Register Number: 25017264

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**


![alt text](<RTL Logic for 3 to 8 Encoder.png>)

**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![alt text](<8 to 3 encoder timing diagram.png>)

**RESULTS**

Thus, the given logic functions are implemented using and their operations are verified using Verilog programming.



....



....





.....






.....





....





.....





......





.....




......






......





.....




.....





....





.....





......






.....





.....






.....




.....




....




.....





.....
