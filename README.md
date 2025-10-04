# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
ORG 00H 

MOV R0,#50H 

MOV A,@R0 

MOV B,A 

MUL AB 

INC R0 

MOV @R0,A 

END

## OUTPUT
![WhatsApp Image 2025-10-04 at 10 24 47_c314fd24](https://github.com/user-attachments/assets/951f7ed0-b59a-4ac6-809a-dffa796f340b)



## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
ORG 00H
 MOV R0,#50H
 MOV A,@R0
 MOV B,A
 MUL AB
 MOV B,@R0
 MUL AB
 INC R0
 MOV @R0,A
 INC R0
 MOV @R0,A
 END


## OUTPUT
![WhatsApp Image 2025-10-04 at 10 28 10_6c32954e](https://github.com/user-attachments/assets/aa478baa-ad28-4e5d-b608-1618ff200d05)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
