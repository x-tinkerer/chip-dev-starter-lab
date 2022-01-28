# Hybrid

## 01. Computer-Architecture

    - Arithmetic Logic Unit
    - Data Memory, Instruction Memory, and Register File
    - RISC-V Single-Cycle CPU
    - RISC-V 5-stage Pipelined CPU
    - Peripheral Memory Association
    - RISC-V Pipelined CPU Exception Handling

## 02. Verilog Projects

    Half Adder: This half adder adds two 1-bit binary numbers and outputs the sum of the input and its corresponding carry.

    Full Adder: This full adder takes 3-bits for the input (A, B and carry in) and outputs a 2-bit Sum and its corresponding Carry Out. The Sum will be the lowest value output and the Carry Out is the highest value output as well as where other full adders could be joined together.

    Four Bit Ripple Adder: This 4-bit adder takes advantage of the full adder module by taking four full adders and linking them together to add 2 four bit inputs. In the 4-bit adder, the first carry bit is set to zero because there is no initial carry bit as an input.

    Four Bit Look Ahead Adder: This 4-bit look ahead adder is an improved implementation of a 4-bit ripple adder by eliminating the propagation delay found in the 4-bit ripple adder. For each output, this implementation computes each previous carry simultaneously instead of waiting for the previous adder module to yield a carry. In this adder, the first carry bit is set to zero and simplifies the logic because there is no initial carry bit as the input. While this implementation uses more gates and more complex logic to accomplish the same task as the ripple adder, this implementation would add two 4-bit numbers much faster than the 4-bit ripple adder.

    3-bit Comparator: This 3-bit comparator requires two 3-bit inputs and outputs whether the first input is greater than / less than / or equal to the second input. In practice, the 3-bit comparator would compare two numbers and output the relation between them. To verify this module, the binary input bits were converted into their decimal representation and compared mathematically, example: inputs of 010 and 010 represent, 2 and 2, which the module would output 001 for the outputs: GT, LT, and EQ, respectively.

    4-16 Decoder: This 4-to-16 decoder takes one 4-bit input and outputs a 16-bit representation of the input. This module uses the concept of one-hot decoding where each output would have one output that would correspond to the input. An application for this decoder would be to convert a 4-bit binary value to its hexadecimal representation. To verify this module, the binary bits of the input is converted into their decimal representation and compared to the output’s decimal representation to see if they match.

    Priority Encoder: This priority encoder takes one 4-bit input and then outputs the binary representation of the index of the active input bit with the highest priority. Also, the module will indicate if the output generated is valid by toggling the valid bit, VLD. This solves the issue of having two inputs active at the same time by having the input of the highest priority take precedence.

    4-1 Multiplexer: This 4-1 multiplexer takes an input of four bits and another input of 2-bits and outputs based on the selected input. In this module, the two bits are the select bits that would select which one the inputs should be designated as the output.

    Traffic Light Controller: The aim of this project is to design a digital controller to control traffic at an intersection of a busy main street (North-South) and an occasionally used side street (East-West).

    64-Bit Adder: This project contains three different implementations of a 64-Bit Adder module using: ripple-carry adders, 2-bit look ahead adders, and a behavioral design.

## 03. 32-Verilog-Mini-Projects

    Implementing 32 Verilog Mini Projects. 32 bit adder, Array Multiplier, Barrel Shifter, Binary Divider 16 by 8, Booth Multiplication, CRC Coding, Carry Select and Carry Look Ahead Adder, Carry Skip and Carry Save Adder, Complex Multiplier, Dice Game, FIFO, Fixed Point Adder and Subtractor, Fixed Point Multiplier and Divider, Floating Point IEEE 754 Addition Subtraction, Floating Point IEEE 754 Division, Floating Point IEEE 754 Multiplication, Fraction Multiplier, High Radix Multiplier, I2C and SPI Protocols, LFSR and CFSR, Logarithm Implementation, Mealy and Moore State Machine Implementation of Sequence Detector, Modified Booth Algorithm, Pipelined Multiplier, Restoring and Non Restoring Division, Sequential Multiplier, Shift and Add Binary Multiplier, Traffic Light Controller, Universal_Shift_Register, BCD Adder, Dual Address RAM and Dual Address ROM