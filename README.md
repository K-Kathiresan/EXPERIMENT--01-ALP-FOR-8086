# EXPERIMENT-01

### Name : Kathiresan K
### Roll no : 212223110021


## Aim: To Write and execute ALP on fundamental arithmetic and logical operations

## Components required: 8086  emulator 


## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

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

## Addition  of 16 bit numbers ALP 
```assembly
MOV AX,3A25H
MOV BX,7F45H
RET
```
## Output  
 <img width="1297" height="812" alt="add" src="https://github.com/user-attachments/assets/376464c1-5683-40e2-8e21-9ebf3e28aec3" />


## Subtraction  of 16 bit numbers  ALP 
```assembly
MOV AX,4B36H
MOV BX,5F74H
SUB AX,BX
RET
``` 
## Output 
<img width="1310" height="806" alt="sub" src="https://github.com/user-attachments/assets/51df4566-29d9-4d04-afe2-4be3b6b7b435" />


## Multiplication of  16 bit numbers  ALP
```assembly
MOV AX,0005H
MOV BX,2000H
MOV,CX,[BX]
MUL CX
RET
```
## Output  

<img width="1593" height="742" alt="mul exp-1" src="https://github.com/user-attachments/assets/4a54d374-cbf8-4f7f-9b80-0bd34e60de03" />

## Division of 16 bit numbers  ALP
```assembly
MOV AX,0X5A55H
MOV BX,0X5E42H
DIV BX
RET
```
## Output  

<img width="1482" height="795" alt="div" src="https://github.com/user-attachments/assets/e02c820a-eb3c-4100-a309-781132ae9b7b" />

## And of 16 bit numbers ALP
```assembly
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## Output
<img width="1443" height="826" alt="And" src="https://github.com/user-attachments/assets/d6076bcf-f739-465f-8059-d5aa2debdc63" />

## OR of 16 bit numbers ALP
```assembly
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## Output
<img width="1378" height="820" alt="or" src="https://github.com/user-attachments/assets/ed2f3a3b-d4a0-47a9-8e47-e192bd866c1a" />

## NOT of 16 bit number ALP
```assembly
MOV AL,65H
NOT AL
HLT
```
## Output
<img width="1358" height="814" alt="not" src="https://github.com/user-attachments/assets/6c29a41e-69c5-4a58-87d1-b30c9fd0dc9c" />

## XOR of 16 bit number ALP
```assembly
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output
<img width="1334" height="806" alt="xor" src="https://github.com/user-attachments/assets/f55e22ae-2ae6-4e6a-8ab6-6c331380a0b5" />


## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
