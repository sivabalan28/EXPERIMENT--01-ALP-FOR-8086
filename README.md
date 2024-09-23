# EXPERIMENT--01-ALP-FOR-8086
```
Name :Sivabalan S
Roll no :212222240100
Date of experiment :12-08-2024
```
## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.	 write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,DIVISION,AND,OR,NOT AND XOR operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)


9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations
## Addition  of 8 bit ALP 
```
MOV AL,77H;
MOV BL,44H;
ADD AL,BL;
HLT;
```
## Output  
![Screenshot 2024-09-23 133515](https://github.com/user-attachments/assets/9c82c208-0751-4f94-a09f-dc1d52b07dc0)


## Subtraction   of 8 bit numbers  ALP 
```
MOV AL,43H;
MOV BL,20H;
SUB AL,BL;
HLT;
```
## Output 
![Screenshot 2024-09-23 133828](https://github.com/user-attachments/assets/b4ad4db2-8d59-48f2-b9f6-8dbcd3f85f0c)


## Multiplication alp 
```
MOV AL,44H;
MOV BL,55H;
MUL AL,BL;
HLT;
```
 ## Output  
![Screenshot 2024-09-23 133953](https://github.com/user-attachments/assets/ba98f4ae-03ca-4cd8-9c05-47892bde5642)


## Division alp 
```
MOV AL,53H;
MOV BL,24H;
DIV AL,BL;
HLT;
```
## Output  
![Screenshot 2024-09-23 134537](https://github.com/user-attachments/assets/6b96b11c-afb2-4ba9-abef-a6261639a284)


# Programs for Logical operations
# Logical AND:
```
MOV AL,63H;
MOV BL,14H;
AND AL,BL;
HLT;
```
# Output:
![Screenshot 2024-09-23 134645](https://github.com/user-attachments/assets/c1ac47d7-f24e-4b19-bf24-dce29469f043)


# Logical OR:
```
MOV AL,51H;
MOV BL,22H;
OR AL,BL;
HLT;
```
# Output:
![Screenshot 2024-09-23 134747](https://github.com/user-attachments/assets/f47ff0f3-885c-40b9-a30f-fa2dad99a7f1)

# Logical Not:
```
MOV AL,53H;
NOT AL;
HLT;
```
# Output:
![Screenshot 2024-09-23 134842](https://github.com/user-attachments/assets/fac55613-43a4-4801-832d-a8f3ed75e7fa)


# Logical XOR:
```
MOV AL,33H;
MOV BL,14H;
XOR AL,BL;
HLT;
```
# OUTPUT:
![Screenshot 2024-09-23 134930](https://github.com/user-attachments/assets/4a61737a-c058-4128-aba3-6268b4f10e51)



## Result :
 
Thus the program for arithmetic operations and logical operations are complete
