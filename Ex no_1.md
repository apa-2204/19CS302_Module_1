# EX 1 C program to initialize the value as 5.8 & display the same.
## DATE: 28/04/2025
## AIM:
To write a program to initialize the value as 5.8 & display the same.

## Algorithm
1. Start. 
2. Declare a integer variable 
3. Define a function named dectobin. 
4. Return the integer. 
5. Read the value using scanf. 
6. Convert decimal to binary value. 
7. Print the dectobin 
8. End.

## Program:
```
 #include<stdio.h> 
  Int dectobin(int d){ 
int bin =0,base=1,rem; 
while(d>0) 
{ 
rem=d%2; 
bin=bin+rem*base; 
d=d/2; 
base=base*10; 
} 
printf(" = %d in binary",bin); 
return 0; 
} 
int main() 
{ 
int dec; 
scanf("%d",&dec); 
printf("%d in decimal",dec); 
dectobin(dec); 
return 0; 
} 
```

## Output:
![image](https://github.com/user-attachments/assets/67139251-ee82-48b6-9e64-cdc1fbaa98e0)



## Result:
Thus the program was executed and the output was verified successfully.
