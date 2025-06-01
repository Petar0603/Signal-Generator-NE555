# Analog signal generator
Realization of a signal generator using NE555 counter IC and passive components.

---
## About
- This project shows the realization of a signal generator using NE555, LM2902 quad-operational amplifier and RC low pass filters.
- Generated frequency range for this signal generator is 50 Hz to 4 kHz.
- Duty cycle of the square signal and of symmetry of the triangle signal is in range of 0.9% to 99.1%.
- Amplitude range and added offset both depend on the supply voltage of the circuit.
- Parameters of the waveform (amplitude, frequency and offset) are adjusted by the use of potentiometers.
- Manual control of the generator by short-circuiting the correct parts of the circuit.
- Three blocks in the circuit: Oscillator block , RC Filters block (for sine wave generation) and
Signal modification block.
---
## Photos
Circuit on a breadboard
<div align="center"> <img src="/Images/Circuit/circuit_on_breadboard.jpeg"> </div>

---
## Schematic
Oscillator block
<div align="center"> <img src="/Images/Circuit/oscillator_block.png"> </div>
RC Filters block
<div align="center"> <img src="/Images/Circuit/rc_filters_block.png"> </div>
Signal Modification block
<div align="center"> <img src="/Images/Circuit/signal_modification_block_block.png"> </div>

---
## Signals
All signals (sine, triangle and square)
<div align="center"> <img src="/Images/Oscilloscope signals/square_triangle_sine.png"> </div>
