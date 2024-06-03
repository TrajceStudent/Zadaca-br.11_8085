 # Zadaca-br.11_8085
Every 30ms an isolated port with address 0Ah is read data. If bits 2 and 5 are 1 and 0 respectively in memory mapped port at address F00Ah is sent read data divided by 2, otherwise the read data is sent multiplied by 7. The frequency of the oscillator crystal is 5MHz.

If bit 2,5==1,0 If bit 2,5==1,0 If bit 2,5==1,0 F00Ah Data/2 Else F00Ah Data*7




![Screenshot (1)](  https://github.com/TrajceStudent/Zadaca-br.11_8085/blob/main/6.png)


				
		
Develop by:

[Trajce Stefanoski ](https://github.com/TrajceStudent)

Microcomputer's systems

**Built With**

This project is built using the following tools:

- [Emu8086](https://emu8086-microprocessor-emulator.en.softonic.com/): Assembler and emulator for the Intel 8086 microprocessor.

**Getting Started**

To get a local copy up and running, follow these steps.

**Prerequisites**

In order to run this project you need:

A working computer
Connection to internet
Setup

**How to Run**

To run the program, you need an 8086 emulator or assembler. You can use emulators like DOSBox or TASM (Turbo Assembler). Here's how to run the program using EMU8086:

1. Download and install Emu8086 from [here](https://emu8086-microprocessor-emulator.en.softonic.com/).
2. Clone this repository to your local machine.
3. Open Emu8086 and load the `palindrome.asm` file.
4. Assemble the code by pressing the Assemble button.
5. Run the program by pressing the Run button or by pressing F10.
