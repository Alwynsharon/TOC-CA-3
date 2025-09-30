# GitHub Assignment

1. Implement a program that detects redundant computations, dead code, and strength reduction.
Input:
 x = 2 * 8
 y = x * 1
 z = y + 0
Output (after optimization):
 x = 16
 z = x
2. Implement a simple code generator that translates arithmetic expressions into target assembly for a
stack machine.
Input: (a+b)*c
Output:
 PUSH a
 PUSH b
 ADD
 PUSH c
 MUL
