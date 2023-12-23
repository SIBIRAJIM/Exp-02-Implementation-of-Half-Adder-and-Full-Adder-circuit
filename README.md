# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

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

Half adder 

![Screenshot 2023-12-23 105103](https://github.com/SIBIRAJIM/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/b2c01367-8b87-4e6f-a580-af4bf1d39ee9)

Full adder

![Screenshot 2023-12-23 105110](https://github.com/SIBIRAJIM/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/498905e1-aa5b-47a4-9a97-5cb407b1f879)


/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: SIBIRAJIM
RegisterNumber: 212223050048
*/

RTL realization
Half adder 
![Screenshot 2023-12-23 105122](https://github.com/SIBIRAJIM/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/ab0af1f1-30bd-4abc-ac47-7641fcbe5fb9)

Full adder
![Screenshot 2023-12-23 105133](https://github.com/SIBIRAJIM/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/af09750c-258e-4a39-aae0-9fc7517bad47)


Truthtable
Half adder 
![Screenshot 2023-12-23 105142](https://github.com/SIBIRAJIM/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/876051a8-74b4-4869-952f-5aa9677dc9d2)


Full adder

![Screenshot 2023-12-23 105152](https://github.com/SIBIRAJIM/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/a59f5842-cf15-4a4d-9561-e36032165b64)


### Output:
### TIMING DIAGRAM
Half adder
![Screenshot 2023-12-23 105203](https://github.com/SIBIRAJIM/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/bdc5380e-46f7-4306-831f-e4aca03a63b3)

Full adder

![Screenshot 2023-12-23 105214](https://github.com/SIBIRAJIM/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/437f43fe-2013-48fe-a7cb-ff0d42550598)


### Result:
Thus a Half Adder and Full Adder is designed and its truthtables are verified in Quartus usingVerilog programming.
