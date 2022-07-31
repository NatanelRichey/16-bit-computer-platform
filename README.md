# 16-bit-computer-platform written in HDL
Von-Neumann architecture, designed to execute programs written in HACK machine language (written by Shimon Schocken and Noam Nisan, professors in the Hebrew University of Jerusalem). Platform is written in HDL, built from logic gates.

Main parts of the Hack computer:
1. Instruction memory (ROM)
2. Memory (RAM):
  • Data memory
  • Screen (memory map)
  • Keyboard (memory map)
3. CPU
4. Computer (the logic that holds everything together).

Memory: This chip includes three chip-parts: RAM16K, Screen, and Keyboard.
Hack ALU: Produces two kinds of outputs: a "main" 16-bit output resulting from operating on the two 16-bit inputs, and two 1-bit "status outputs" named 'zr' and 'ng'.
RAM16K: 16-bit / 16384-register memory
CPU: This chip is constructed according using the ALU and register chips specified.

Note: Assumed implementation for DFF (data flip-flop) and ROM32K.
