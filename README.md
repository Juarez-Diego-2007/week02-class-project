# Ohm's Law Calculator

## Purpose
A C++ terminal application that calculates electrical current using Ohm's law.

## Input
Enter voltage in volts followed by resistance in ohms.

Example:
`12 4`

## Output
The program calculates current using `I = V / R`.

Example output:
`Current: 3 A`

If the input is invalid or resistance is zero or negative, the program prints `Invalid input`.

## Build
Compile the program from the project root:

`g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o build/app`

## Run
Run the program with:

`./build/app`

## Test
Run the automated acceptance tests with:

`bash test.sh`

## Limitations
The program calculates current from voltage and resistance. It does not provide a graphical interface or additional circuit analysis.

## AI-use disclosure
AI assistance was used to help understand Git commands, project setup, and automated testing. The code and project should be reviewed by the student for correctness.