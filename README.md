# 4-bit-register

Created a register capable of storing a 4-bit binary value, with a clocked load input that stores the data on the rising edge of the clock signal.

First I needed to make the basic of sequential logic which is an SR-Latch:
![Screenshot 2024-11-05 115523](https://github.com/user-attachments/assets/592ece20-4056-4032-87fc-fe7ca01fe990)

Secondly, I continued by adding 2 AND gates and a NOT gates to make a D-Latch which is an essential part for the continuation of the project.
![Screenshot 2024-11-05 115754](https://github.com/user-attachments/assets/4c749d84-6fad-4939-935d-07b54028a4db)

Thirdly, I made a D-Flip-Flop, which is constituate of two D-Latch (master and a slave), linked to a clock because the register will be synchronous. 
![Screenshot 2024-11-05 120016](https://github.com/user-attachments/assets/3bee2756-a703-4d1f-a2af-f5d325060683)

After, I was able to make a 1 bit register by linking a D-Flip-Flop and some logic gate(AND, OR, NOT). 
![Screenshot 2024-11-05 120314](https://github.com/user-attachments/assets/bc9bda91-9345-4716-af53-06affbf03907)

Finally, by linking 4 1 bit register together, we get the 4 bit-register
![Screenshot 2024-11-05 120406](https://github.com/user-attachments/assets/17935048-9bbf-4b13-838d-c446827afe75)
