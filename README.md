# Project 2 README

Student 1: William Yu 1 (921166191)
Student 2: Bowei Cheng 2 (920955332)

## Project Status
It could successfully run.

## Known Issues
The project fails in the main test, but it gives the correct answer in Lock.

## References
[Truth table]http://www.32x8.com/var5.html

## Generative AI Use
I used ChatGPT for Prompt 1 

### Prompt 1
How to use register?

### Response 1
Suppose you have a 2-bit state machine:

Add a 2-bit Register:
Place a register with 2 data bits on the canvas.
Connect a clock signal to the clock input of the register.
Set the enable input to  (or control it with a condition if necessary).1
Optionally connect a reset input to clear the register.
Connect the State Logic:
The  outputs of the register represent the current state (, ).QS1S0
Use these outputs in combinational logic to determine the next state (, ).Next S1 Next S0
Feed the output of this combinational logic into the  inputs of the register.D
Simulate:
After connecting everything, start the simulation.
The register will hold and update the state based on the clock and enable signal.

### Changes 1
Clock Input: The register will update its value on the rising edge of the clock signal. Connect a Clock component to the clock input of the register.