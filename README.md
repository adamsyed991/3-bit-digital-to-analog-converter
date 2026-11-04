# 3-Bit Digital-to-Analog Converter (DAC)

Designed, simulated, and physically tested a 3-bit DAC. The project uses a binary-weighted resistor network, voltage-follower buffers, and an op-amp summing amplifier to convert 3-bit digital inputs into 8 analog output levels.

## Tools
- LTspice
- Digilent Analog Discovery 3 (AD3)
- WaveForms

## Results
- Tested all 8 input codes and observed monotonic output with no missing codes.
- Measured a maximum differential non-linearity (DNL) of +0.196 LSB.
- Measured a 16.61 mV offset error (0.027 LSB).
- Measured a gain error of +0.89 LSB, attributed to resistor tolerance.

## Project Overview
The design was simulated in LTspice and then built and tested using the AD3 and WaveForms. Measured output levels were compared with ideal values to evaluate converter performance and identify potential sources of error, including resistor tolerances and amplifier gain.

## Author
Adam Syed
