8-Bit-Arithmetic-Operations-using-8085
SUNIL NATH MJ
212224053004
### Aim:
To perform 8-bit arithmetic operations such as addition, subtraction, multiplication, and division using the 8085 microprocessor.

### Apparatus Required:
• Laptop with internet connection

### Algorithm:

### For Addition (With Carry Consideration):
1.Load the first number from memory location 4200H into register A.
2.Load the second number from memory location 4201H into register B.
3.Add the contents of registers A and B.
4.If carry is generated, store carry in 4301H.
5.Store the sum in memory location 4300H.

### Program:
<img width="1488" height="772" alt="image" src="https://github.com/user-attachments/assets/db29a96d-add5-4217-8cc2-b3f20f42afe7" />


### Output:

<img width="288" height="438" alt="image" src="https://github.com/user-attachments/assets/af7bf949-4d24-42e7-9952-06ff13dbae3c" />
<img width="273" height="433" alt="image" src="https://github.com/user-attachments/assets/dc515b8d-d6d8-4856-bb92-cc4d115187a9" />

### Explanation :
![WhatsApp Image 2026-02-02 at 8 56 30 PM](https://github.com/user-attachments/assets/87998052-2081-4afc-8d9d-5633bada3c43)


### For Subtraction (Considering Greater Number):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Compare A and B.
4.	If A < B, swap the values of A and B to ensure positive result.
5.	Subtract the content of B from A.
6.	Store the result in memory location 4300H.

## Program:
<img width="1335" height="762" alt="image" src="https://github.com/user-attachments/assets/d10be1d4-530a-4971-b593-4b310606d56c" />

## Output:
<img width="298" height="430" alt="Screenshot 2026-02-02 201604" src="https://github.com/user-attachments/assets/53e8f669-6705-4084-8b86-6f8a9760021a" />
<img width="291" height="376" alt="Screenshot 2026-02-02 201616" src="https://github.com/user-attachments/assets/7e628a9e-368c-4fd0-a324-3bfffb913343" />

## Explanation :
![WhatsApp Image 2026-02-02 at 8 15 37 PM](https://github.com/user-attachments/assets/4f67d907-48a5-4ed6-ad34-d426b3e5125b)



### For Multiplication:
1.Load the first number from memory location 4200H into register A.
2.Load the second number from memory location 4201H into register B.
3.Multiply A and B using repeated addition.
4.Store the result in memory locations 4300H and 4301H (if required for higher bits).

## Program:

<img width="1421" height="519" alt="image" src="https://github.com/user-attachments/assets/f9a987ea-735c-4d06-8125-da0c2f32ba5c" />

## Output:

<img width="273" height="425" alt="image" src="https://github.com/user-attachments/assets/f681a190-e6fb-4453-a0e9-32f45ef548bf" />
<img width="273" height="404" alt="image" src="https://github.com/user-attachments/assets/52969cc3-0d51-4bdd-bae8-de3dcd421f3c" />

## Explanation :
![WhatsApp Image 2026-02-02 at 9 01 44 PM](https://github.com/user-attachments/assets/cc62bf25-2abc-4b5e-b354-8b9134d16cc8)
![WhatsApp Image 2026-02-02 at 9 01 44 PM](https://github.com/user-attachments/assets/d4db82a4-bd51-49f4-ac19-0cb0ec02c9f3)

## For Division:
1.Load the dividend from memory location 4200H into register A.
2.Load the divisor from memory location 4201H into register B.
3.Perform division using repeated subtraction.
4.Store the quotient in 4300H and remainder in 4301H.

## Program:
<img width="1439" height="867" alt="image" src="https://github.com/user-attachments/assets/1ad6a522-af97-4324-9ae6-80ca661c3d44" />

## Output:
<img width="277" height="412" alt="image" src="https://github.com/user-attachments/assets/e94886b1-d089-4084-9e96-925365b61f85" />
<img width="277" height="423" alt="image" src="https://github.com/user-attachments/assets/442ee881-412a-46a7-8981-8a953d7b123d" />


## Explanation :
![WhatsApp Image 2026-02-02 at 8 57 21 PM](https://github.com/user-attachments/assets/a78586f9-6818-49b0-a4d6-9b774e6efed8)

### Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.
