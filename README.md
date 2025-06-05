# Digital Communication - Part I: Line Coding Comparison

This part of the project implements and compares two types of line codes using Octave:

- **Unipolar NRZ**
- **AMI (Bipolar NRZ)**

## Overview

- A 256-bit random bitstream is generated.
- The signal is encoded using both line coding techniques.
- Time-domain plots are created to visualize pulse shapes.
- Frequency-domain analysis is done via FFT to study the spectrum.

## Files

- `part1_line_coding_comparison.m`: Main script to generate, encode, and analyze the signals.

## How to Run

1. Open Octave.
2. Navigate to the `digital` directory.
3. Run:

```octave
part1_line_coding_comparison
