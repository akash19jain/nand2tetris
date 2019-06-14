# nand2tetris

## Implementation of a complete computer from Nand gates on up as described in the book, "The Elements of Computing Systems" by Nisan and Schocken.  

### PROJECT 01:  
Building the Chipset That will be later used to construct the Computer's Arithmetic Logic Unit and Memory System.  
The following Chipsets were built with NAND as the Primitive Gate.  
1. And  
2. Or  
3. Xor  
4. Mux  
5. DMux  
6. Not16  
7. And16  
8. Or16  
9. Mux16  
10. Or8Way  
11. Mux4Way16  
12. Mux8Way16  
13. DMux4Way  
14. DMux8Way  
15. Not  
The `.hdl` (Hardware Descriptor Language) file contains the code for the chipset and the `.out` file contains the output for the corresponding chipsets.  

### PROJECT 02:  
Gradually Building a set of Chips, culminating in the construction of the the ALU Chip of the Hack Computer.  
1. Half Adder  
2. Full Adder  
3. Add16  
4. Inc16  
5. ALU  
The `.hdl` (Hardware Descriptor Language) file contains the code for the chipset and the `.out` file contains the output for the corresponding chipsets.  

### PROJECT 3  
Gradually building a RAM unit. The only building blocks that you use are primitive DFF gates.  
1. 1 Bit Register  
2. 16 Bit Register  
3. RAM8  
4. RAM64  
5. RAM512  
6. RAM4K  
7. RAM16K
8. PC  
The `.hdl` (Hardware Descriptor Language) file contains the code for the chipset and the `.out` file contains the output for the corresponding chipsets.  

### PROJECT 4  
Writing a program in Assembly Language and having them translated into binary code by using an assembler. Two low-level programs were written:  
1. Multiplication  
2. Fill - illustrates low level handling of the screen and keyboard devices. If a key is pressed, the screen turns fully black else white.  
The `.asm` file contains the code for the chipset in Assembly Language and the `.out` file contains the output for the corresponding chipsets, while the `.hack` file contains the `.asm` file converted into binary code.  

### PROJECT 5  
Building the complete Hack Hardware Platform that can run programs written in the Hack Machine language.  
1. Memory - The Entire RAM address Space  
2. CPU - The Hack CPU  
3. Computer - The Platform's Top most Chip.   
The `.hdl` (Hardware Descriptor Language) file contains the code for the chipset and the `.out` file contains the output for the corresponding chipsets, , while the `.hack` file contains the binary code.  The `.tst` files are the test scripts that are used to perform a test (here we are performing 6 such tests to test the `Computer.hdl` chip.. The resulting outputs are stored in the `.out` file. I have used the Hardware Simulator to test chips written in HDL.  

### PROJECT 6  
Writing an Assembler Program that translates programs written in the symbolic Hack assembly language into Binary Code that can execute on Hack Hardware platform built previously. 
Test Programs:  
1. Add.asm  
2. Max.asm  
3. Rect.asm  
4. Pong.asm





