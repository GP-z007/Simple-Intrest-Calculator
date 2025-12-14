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

