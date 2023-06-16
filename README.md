![alt Computer in Logisim](https://camo.githubusercontent.com/195a52b6e347048ce0b0c7442fa4aa5bf2be8022a24400fe58e82c3846a970c6/68747470733a2f2f692e696d6775722e636f6d2f61494c333973372e706e67)
# 8bitComputer
The aim of this project is to create an 8-bit computer in the simulation program Logisim. All parts of the processor (computer) are composed of (N)AND, (N)OR, and NOT gates. The exception is the ROM memory, which was implemented using the ROM memory component in Logisim. The computer is based on the von Neumann architecture. 
## ISA
The computer is capable of executing the following instructions: NOP, LDA, ADD, SUB, STA, LDI, JMP, JC, JZ, OUT, and HALT.
## Programming
The program can be loaded into RAM using a RAM programmer. Instructions in machine language just need to be loaded into this ROM memory, then the clock can be started in Logisim, and the RAM programmer can be activated by pressing the PROG_RAM button.
In the project, there is an executable program called ROMProgrammer.exe written in C++. This program serves as an assembler between assembly language and the machine language of this computer. To use the program correctly, you need to have your code written in assembly language in a file named ram.as, which must be located in the same directory as the executable file. Upon running the program, an image for the ROM memory will be created, which you can load into Logisim.

The project was inspired by Ben Eater's computer (https://www.youtube.com/c/BenEater).
