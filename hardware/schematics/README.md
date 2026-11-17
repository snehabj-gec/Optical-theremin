Circuit Schematic

Optical Theremin

This folder contains the circuit schematic of the Optical Theremin project, a fully analog musical instrument that generates sound by detecting changes in light intensity.

Circuit Overview

The circuit consists of the following main stages:

1. NE555 Timer: Configured in astable mode to generate a square-wave signal. The oscillation frequency changes according to the resistance of the pitch-control LDR.
2. LM358 Op-Amp: Used for signal buffering and conditioning.
3. Volume Control: A second LDR controls the output volume based on the amount of light falling on it.
4. LM386 Audio Amplifier: Amplifies the generated audio signal to drive the speaker.
5. Power Supply: The circuit operates using a 9V supply.

Working Principle

The Optical Theremin uses two Light Dependent Resistors (LDRs) to provide contactless control over sound.

- The pitch-control LDR changes the oscillation frequency of the NE555 timer.
- The volume-control LDR controls the amplitude of the audio output.
- The generated signal is processed and amplified before being delivered to the speaker.

Moving your hands over the LDRs changes the amount of light reaching them, thereby changing the sound.

Components Used

- NE555 Timer IC
- LM358 Operational Amplifier
- LM386 Audio Amplifier
- 2 × LDRs
- Resistors
- Capacitors
- Speaker
- 9V Battery / Power Supply

Schematic

The circuit schematic is provided in this folder.

Notes

This project was designed as a simple, low-cost, fully analog implementation of an Optical Theremin for educational purposes.

Total project expenditure: ₹457
