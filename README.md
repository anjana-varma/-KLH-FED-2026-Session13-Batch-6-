# Binary-to-Gray Code Converter

## Project Description
This project demonstrates the design and working of a 4-bit Binary-to-Gray Code Converter using combinational logic. The circuit converts a 4-bit binary input into its corresponding Gray code output.

Gray code is a coding system in which two consecutive values differ by only one bit. It helps reduce errors during transitions in digital systems.

## Objectives
- To understand binary and Gray code.
- To design a Binary-to-Gray Code Converter using XOR gates.
- To implement and simulate the circuit using Logisim.
- To verify the output using a truth table.

## Working Principle
The most significant bit (MSB) of the binary input is copied directly to the Gray code output. Each remaining Gray code bit is obtained by XORing two adjacent binary bits.

For binary inputs \(B_3, B_2, B_1, B_0\), the outputs are:

- \(G_3 = B_3\)
- \(G_2 = B_3 \oplus B_2\)
- \(G_1 = B_2 \oplus B_1\)
- \(G_0 = B_1 \oplus B_0\)

## Components Used
- XOR gates
- Input pins
- Output pins
- Logisim simulation software

## Applications
- Rotary encoders for measuring rotation and position.
- Position sensors for detecting movement.
- Digital counters and state-transition circuits.
- Selected digital communication systems.

## Simulation
The circuit was designed and simulated using Logisim. The outputs were checked against the truth table for all 16 possible 4-bit binary inputs.

## Files in the Repository
- `README.md` — Project description and working principle.
- `binary_to_gray.circ` — Logisim circuit file.
- `images/` — Circuit and simulation screenshots.

## Conclusion
The 4-bit Binary-to-Gray Code Converter was designed using three XOR gates and one direct connection. The circuit converts binary inputs into Gray code outputs and demonstrates the use of combinational logic in digital electronics.

## Team Members
- Anjana Varma
- Divija Laxmi
- Ganesh Goud
- Bindu Sri
