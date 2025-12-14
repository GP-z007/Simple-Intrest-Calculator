# Simple Interest Calculator

A very small project that demonstrates the simple interest formula \( I = P \times R \times T / 100 \) using two implementations:
- A Bash shell script for practical use.
- A Brainfuck program as an esolang experiment. [web:1][web:5]

## Features

- Takes principal, rate, and time as inputs.
- Computes simple interest using integer arithmetic.
- Shell version prints both interest and total amount (principal + interest).
- Brainfuck version focuses on core interest calculation logic. [web:5][web:6]

## Files

- `si.sh` – Shell script implementation of the simple interest calculator. [web:6]
- `si.bf` – Brainfuck implementation of a simple interest calculator.
- `README.md` – Project documentation.

## Formula

This project uses the standard simple interest formula:  
- Interest: \( I = P \times R \times T / 100 \)  
- Amount: \( A = P + I \) [web:1][web:5]

Where:
- \( P \) is the principal.
- \( R \) is the annual rate of interest (in percent).
- \( T \) is the time period (in years or chosen unit). [web:1][web:5]

## Prerequisites

- Any POSIX-compatible shell (tested with `bash`).
- A Brainfuck interpreter (for example `bf`, `brainfuck`, or any online interpreter). [web:10][web:13]

## Usage

### Shell script
chmod +x si.sh ./si.sh

You will be prompted to enter:
- Principal amount
- Rate of interest (percent per time period)
- Time period

The script will print:
- Computed simple interest
- Final amount (principal + interest) [web:6]

### Brainfuck program

brainfuck si.bf

Typical flow (adjust to how you implemented I/O):

1. Enter principal.
2. Enter rate.
3. Enter time.
4. Program outputs the calculated simple interest (and optionally the final amount). [web:2][web:11]

## Notes

- The Brainfuck implementation is intentionally minimal and may only support small integer ranges and basic input format.
- No extensive input validation is performed in either version; invalid input can lead to undefined behavior. [web:2][web:11]


