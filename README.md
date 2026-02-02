# 8-Bit-Arithmetic-Operations-using-8085
## Aim:
To perform 8-bit arithmetic operations such as addition, subtraction, multiplication, and division using the 8085 microprocessor.

## Apparatus Required:
•	Laptop with internet connection

## Algorithm:

### For Addition (With Carry Consideration):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Add the contents of registers A and B.
4.	If carry is generated, store carry in 4301H.
5.	Store the sum in memory location 4300H.
   
### Program:
<img width="1488" height="772" alt="image" src="https://github.com/user-attachments/assets/8d95f88e-a27c-4c4f-abd5-b49d4f0a29d6" />



### Output:
<img width="288" height="438" alt="image" src="https://github.com/user-attachments/assets/1a1b91d9-82ce-4e0f-8aad-78ee22dc19e6" />
<img width="273" height="433" alt="image" src="https://github.com/user-attachments/assets/73dca145-2c66-4328-b772-d0f2caca0c20" />



Explanation :
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/8e57e9cd-f29f-40f5-a604-de8f879d62f2" />



### For Subtraction (Considering Greater Number):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Compare A and B.
4.	If A < B, swap the values of A and B to ensure positive result.
5.	Subtract the content of B from A.
6.	Store the result in memory location 4300H.

### Program:
<img width="1524" height="749" alt="Screenshot 2026-02-02 201552" src="https://github.com/user-attachments/assets/5d021ac5-59c4-4d07-8c3b-c253ede4dd3c" />


### Output:
<img width="298" height="430" alt="Screenshot 2026-02-02 201604" src="https://github.com/user-attachments/assets/8dd9aa36-b359-4d1c-978a-fd8a4f5b7406" />
<img width="291" height="376" alt="Screenshot 2026-02-02 201616" src="https://github.com/user-attachments/assets/9be083ef-fd28-43ba-aa1e-44b7ca3d9e18" />

Explanation :



<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/89f648d9-b146-48c3-b527-61af519582b9" />




### For Multiplication:
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Multiply A and B using repeated addition.
4.	Store the result in memory locations 4300H and 4301H (if required for higher bits).

### Program:
<img width="1421" height="519" alt="image" src="https://github.com/user-attachments/assets/037985aa-e8ab-459a-b42a-c45bbbf0a757" />


### Output:
<img width="273" height="425" alt="image" src="https://github.com/user-attachments/assets/3e8f6f0c-fb9d-4b89-a9ee-d4a2748e09c0" />
<img width="273" height="404" alt="image" src="https://github.com/user-attachments/assets/2a042f1c-91a8-45cc-8160-c17410d0df04" />

Explanation :
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/2cc1124b-639a-41ab-9916-c5c4990f4b2c" />
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/8e47d150-9e60-41b5-891a-d8fbb3d1cb5d" />







### For Division:
1.	Load the dividend from memory location 4200H into register A.
2.	Load the divisor from memory location 4201H into register B.
3.	Perform division using repeated subtraction.
4.	Store the quotient in 4300H and remainder in 4301H.

### Program:
<img width="1439" height="867" alt="image" src="https://github.com/user-attachments/assets/ce0dccbe-7404-40e4-8ce9-5de20d5b5dd4" />


### Output:
<img width="277" height="412" alt="image" src="https://github.com/user-attachments/assets/0227b9f9-e415-47d0-a4b2-c755ce7a6dd4" />
<img width="277" height="423" alt="image" src="https://github.com/user-attachments/assets/953e0dab-6286-41bd-a467-efb06c5d385d" />

Explanation :
<img width="1503" height="1529" alt="image" src="https://github.com/user-attachments/assets/7b54776b-0ccf-4345-94cb-f82fa2fa569c" />




## Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.

