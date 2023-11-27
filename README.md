# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: DEVASANJAY N
RegisterNumber:  23013004

Logic symbol & Truthtable
RTL realization
### Code :
FHALF ADDER : ![Exp3 fa code](https://github.com/DEVASANJAY002/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152069249/1ccd0eb1-4746-43a3-98ea-7e81689e7cb4)
FULL ADDER : ![Exp3 ha code](https://github.com/DEVASANJAY002/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152069249/d4edba81-53da-4bc4-a213-3ba740d16c22)
 
### RTL
HALD ADDER : ![Exp3 ha RTL diagram](https://github.com/DEVASANJAY002/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152069249/5c2d562d-a327-45f7-9c11-1a76e5df5b65)
FULL ADDER : ![Exp3 fa RTL diagram](https://github.com/DEVASANJAY002/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152069249/6011a85f-33b0-4043-b07f-41fc9437695c)

### TIMING DIAGRAM
HALF ADDER : ![exp3 ha wave](https://github.com/DEVASANJAY002/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152069249/fd4a04a6-63a6-49f5-b498-3f519d57350f)
FULL ADDER : ![exp 3 fa wave](https://github.com/DEVASANJAY002/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152069249/a5515cda-5a39-4664-a579-fd5acf976f5d)

### TRUTH TABLE : 
HALF ADDER : ![Exp3 truthtable (ha)](https://github.com/DEVASANJAY002/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152069249/ff6a2e26-5a52-484a-a7ab-62049a2b86db)
FULL ADDER : ![Exp3 truthtable (fa)](https://github.com/DEVASANJAY002/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152069249/c487498a-3cf7-4d7c-9c24-de7ebf382d1e)


### Result: Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming
