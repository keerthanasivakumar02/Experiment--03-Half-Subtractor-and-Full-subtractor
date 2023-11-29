# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: KEERTHANA S
RegisterNumber: 23010209 
*/

## Output:

## HALF SUBTRACTOR

## CODE:

![image](https://github.com/keerthanasivakumar02/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150827397/6d5eeb5f-8ab4-4ab8-9ed6-fab5b95002d3)

## RTL DIAGRAM:

![image](https://github.com/keerthanasivakumar02/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150827397/4030dc4e-9e5e-413c-9631-347fb5112d7e)

## TRUTH TABLE:

![image](https://github.com/keerthanasivakumar02/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150827397/3549f39a-6fad-41ec-9a08-59938f437e44)

## TIMING DIAGRAM:


![image](https://github.com/keerthanasivakumar02/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150827397/64b0bf2e-4371-4b5a-a5f8-a84c701a8f7c)

## FULL SUBTRACTOR

## CODE:


![image](https://github.com/keerthanasivakumar02/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150827397/b933a984-f0e0-476b-a699-ee2a65c10d4e)

## RTL DIAGRAM:


![image](https://github.com/keerthanasivakumar02/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150827397/18dd15ed-a9ac-47c2-b214-b26136c07914)

## TRUTH DIAGRAM:


![image](https://github.com/keerthanasivakumar02/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150827397/9ad8632c-e24e-4164-8866-c3d28bc36563)

## TIMING DIAGRAM:


![image](https://github.com/keerthanasivakumar02/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150827397/84df0ac2-28f0-424e-bb47-eaaf16f58c5c)





## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
