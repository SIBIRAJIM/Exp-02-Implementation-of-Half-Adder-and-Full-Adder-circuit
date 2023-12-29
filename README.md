## NAME:SIBIRAJI
## REG NO:212223050048

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

### Program:

## HALF ADDER
~~~
module halfadder(sum,a,b,carry)
input a,b,c;
output sum,carry;
xor(sum,a,b);
and(carry,a,b)
endmodule
~~~

## FULL ADDER
~~~
module fulladder(a,b,c,sum,carry);
input a,b,c;
output sum,carry;
xor(sum,a,b);
assign carry=a&b|b&c|a&c;
endmodule
~~~

### RTL
## HALF ADDER
![Screenshot 2023-12-21 233642](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/25e1c0c5-659e-40d1-aa3c-ff69195c91c2)
## FULL ADDER
![Screenshot 2023-12-21 234109](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/16850b8b-b4a2-4aeb-bd8f-331e935fef7c)

### TIMING DIAGRAM
## HALF ADDER
![Screenshot 2023-12-21 233909](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/198863db-2433-4208-9f5a-d64a4959cdd0)
## FULL ADDER
![Screenshot 2023-12-21 234352](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/25f0ba6d-138e-4957-bd1b-7a147a0a09bb)

### TRUTH TABLE 
## HALF ADDER
![Screenshot 2023-12-29 115700](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/4071574b-1bfe-4279-baa8-4edd6b010e32)

## FULL ADDER
![Screenshot 2023-12-29 115707](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154588445/63569a5a-feca-421f-9df0-a1265886ed64)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
