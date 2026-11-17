Optical Theremin

An Analog Light-Controlled Musical Instrument

An analog electronic musical instrument that uses variations in ambient light to control sound pitch and volume.

Project Overview

The Optical Theremin is an analog electronics project developed using light-dependent resistors (LDRs), timer circuits, operational amplifiers, and an audio amplifier.

The system converts changes in light intensity into variations in an electrical signal, enabling contactless control of audio pitch and volume.

Objectives

- Develop a light-controlled analog musical instrument.
- Generate an audio-frequency signal using an NE555 timer.
- Implement optical pitch and volume control using LDRs.
- Condition and amplify audio signals using analog integrated circuits.
- Design, assemble, and test a functional hardware prototype.

System Architecture

The system consists of four primary functional stages:

1. Signal Generation: NE555 astable multivibrator.
2. Pitch Control: LDR-based timing resistance variation.
3. Signal Conditioning: LM358 operational amplifier.
4. Audio Amplification: LM386 audio amplifier.

A second LDR-based control stage regulates audio volume.

Hardware Components

Component| Function
NE555| Astable signal generation
LM358| Signal buffering and conditioning
LM386| Audio amplification
LDRs| Light sensing and control
Resistors and capacitors| Timing and signal conditioning
Speaker| Audio output
9V supplies| Circuit power

Development Process

- Circuit design and component selection
- Breadboard prototyping
- Functional testing and troubleshooting
- Dot PCB implementation
- Hardware verification

Tools

- KiCad
- Electronic test and prototyping equipment

Repository Structure

- "docs/" – Technical documentation and calculations
- "hardware/" – Circuit schematics and hardware implementation
- "images/" – Project development photographs

Project Status

Hardware prototype developed and functional testing completed. Dot PCB implementation undertaken.

Future Improvements

- Quantitative measurement of pitch response
- Improved frequency stability
- Enhanced optical sensitivity
- Refined hardware layout

Author

Undergraduate Electrical and Electronics Engineering Project
