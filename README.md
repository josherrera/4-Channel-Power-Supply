# 4-Channel-Power-Supply
Single output power supply to four outputs 

This project is the first step in creating a smart-watch with the features i use the most but with higher battery life.

The objective of the project is to take a single output power supply and create an adapter that generates four different output voltages.

Channels 1, 3, and 4:
Output range: 2-12V
Max current: 1A
Noise: 39 uVrms

Channel 2:
Output range: -2 to -12V
Max current: 250mA
Noise: 360 uV

The noise in the system is negligible when used for logic devices, but it is significant when used for high sensitivity analog circuits needing low noise. The system will however be sufficient if op-amps with PSRR > 80dB are used. It is recommended to use a combination of voltage references and buffers for added noise reduction when needed. The system can be upgraded with higher PSRR linear regulators for greater noise performance, but this design is driven by low cost. The calculations for the noise performance are attached. 

