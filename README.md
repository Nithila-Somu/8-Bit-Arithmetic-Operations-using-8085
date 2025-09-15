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
   
### Program:<img width="893" height="533" alt="image" src="https://github.com/user-attachments/assets/aa400736-7be2-413d-9c89-d515407eb2a2" />


### Output:<img width="892" height="435" alt="image" src="https://github.com/user-attachments/assets/06dfd0d8-583d-4915-b547-76697bdb801a" />
<img width="910" height="404" alt="image" src="https://github.com/user-attachments/assets/56581e06-6028-4398-8a7a-d425f9ffe0b2" />


### For Subtraction (Considering Greater Number):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Compare A and B.
4.	If A < B, swap the values of A and B to ensure positive result.
5.	Subtract the content of B from A.
6.	Store the result in memory location 4300H.

### Program:<img width="905" height="533" alt="image" src="https://github.com/user-attachments/assets/3ea546aa-42a8-48d9-9ccb-a3cee99fc210" />


### Output:<img width="891" height="443" alt="image" src="https://github.com/user-attachments/assets/93a2ef5d-ceeb-44cc-9f75-b83d27f872e9" />
<img width="894" height="407" alt="image" src="https://github.com/user-attachments/assets/b41b006f-79cf-4e03-ba10-1c4214aa0c9f" />


### For Multiplication:
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Multiply A and B using repeated addition.
4.	Store the result in memory locations 4300H and 4301H (if required for higher bits).

### Program:<img width="894" height="480" alt="image" src="https://github.com/user-attachments/assets/368361ca-ba09-4f30-9079-28d61b625009" />


### Output:<img width="890" height="422" alt="image" src="https://github.com/user-attachments/assets/e1b988fa-90ef-44ca-a431-e661e1532068" />
<img width="889" height="413" alt="image" src="https://github.com/user-attachments/assets/91b48ce2-652b-482f-a305-351d13b68d5f" />


### For Division:
1.	Load the dividend from memory location 4200H into register A.
2.	Load the divisor from memory location 4201H into register B.
3.	Perform division using repeated subtraction.
4.	Store the quotient in 4300H and remainder in 4301H.

### Program:<img width="883" height="502" alt="image" src="https://github.com/user-attachments/assets/b7716c94-1420-4331-888a-ebb5fb2bcc1f" />


### Output:<img width="887" height="428" alt="image" src="https://github.com/user-attachments/assets/6a9ec192-b43d-41df-aea2-6f252b2a9ec8" />
<img width="881" height="421" alt="image" src="https://github.com/user-attachments/assets/eb41bc70-5f1a-4482-9cd8-4e1d5d8c8344" />


## Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.

