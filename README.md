# EXPERIMENT 01- ARITHMETIC OPERATION AND LOGICAL OPERATION IN 8086
## Name : EZHILARASI N
## Reg No : 212224040088
## Date of experiment : 31.10.2026


## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
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







## Programs for arithmetic  operations (16 bit)

### Addition
```
ORG 100H
MOV AX, 1234H
MOV BX, 1111H
ADD AX, BX
HLT
```

### Output
<img width="1920" height="1200" alt="Screenshot (485)" src="https://github.com/user-attachments/assets/ac1fb119-c148-4641-833e-2e706991dc4a" />


### Subtraction
```
ORG 100H
MOV AX, 2345H
MOV BX, 1111H
SUB AX, BX
HLT
```

### Output  
<img width="1920" height="1200" alt="Screenshot (486)" src="https://github.com/user-attachments/assets/bd1652d8-390f-4280-8b23-1bf029fe68f7" />


### Multiplication

```
ORG 100H
MOV AX, 0012H
MOV BX, 0003H
MUL BX
HLT
```

### Output
<img width="1920" height="1200" alt="Screenshot (487)" src="https://github.com/user-attachments/assets/d149be89-0bbc-4be3-a379-0efea5694b24" />


### Division
```
ORG 100H

MOV AX, 0036H
MOV BX, 0003H

XOR DX, DX
DIV BX

HLT
```

### Output
<img width="1920" height="1200" alt="Screenshot (480)" src="https://github.com/user-attachments/assets/ff2a086e-d9fe-4828-b2d6-5518f9bd47f2" />



## Programs for logical  operations (16 bit)



### AND
```
ORG 100H

MOV AX, 1234H
MOV BX, 00FFH

AND AX, BX

HLT
```
### Output
<img width="1920" height="1200" alt="Screenshot (481)" src="https://github.com/user-attachments/assets/83f28dd0-e983-4fd4-aa62-ecbe9e8a1640" />


### OR
```
ORG 100H

MOV AX, 1234H
MOV BX, 00FFH

OR AX, BX

HLT
```

### Output
<img width="1920" height="1200" alt="Screenshot (482)" src="https://github.com/user-attachments/assets/3278c043-73be-4fe5-a575-faf0eae5334e" />



### XOR
```
ORG 100H

MOV AX, 1234H
MOV BX, 00FFH

XOR AX, BX

HLT
```

### Output
<img width="1920" height="1200" alt="Screenshot (483)" src="https://github.com/user-attachments/assets/78db9bdf-b3f3-4c70-a814-7c63fa805b5a" />


### NOT
```
ORG 100H

MOV AX, 1234H

NOT AX

HLT
```

### Output
<img width="1920" height="1200" alt="Screenshot (484)" src="https://github.com/user-attachments/assets/87fa1288-64fc-4bfa-bf6a-0d887b37d461" />




## Result :
 Thus to Write and execute ALP on fundamental arithmetic and logical operations is successfully executed.








