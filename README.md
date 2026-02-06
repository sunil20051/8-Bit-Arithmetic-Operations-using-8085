# 8-Bit-Odd-or-Even-Using-8085
## Aim:
To write an 8085 microprocessor program to check whether a given 8-bit number is odd or even.
## Apparatus Required:
•	Laptop with an internet connection
## Algorithm:
1.	Load the number from a specified memory location into register A.
2.	Perform an AND operation with 01H to check the least significant bit (LSB).
3.	If the result is 0, the number is even; otherwise, it is odd.
4.	Store the result in a specific memory location (odd or even flag).


### Program:
```
LDA 4200H       
ANI 01H         
JZ EVEN 
JMP ODD
EVEN:
MVI A, 01H  
STA 4201H
HLT       
ODD: MVI A,02H
STA 4201H
HLT  
```

## Output:
<img width="1898" height="915" alt="Screenshot 2026-02-06 080653" src="https://github.com/user-attachments/assets/45ff287c-9438-4da3-97dd-11d27b88e3d8" />

### Verification:


## Result:
The 8085 microprocessor successfully checks whether a given number is odd or even and stores the result in memory.
