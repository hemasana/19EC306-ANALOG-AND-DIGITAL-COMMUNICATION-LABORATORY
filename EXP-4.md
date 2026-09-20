# Aim:
To obtain Pulse Width Modulation & Demodulation using PCM trainer kit.

# THEORY:
Pulse Width Modulation
This technique of modulation controls the variation of duty cycle of the square wave (With some fundamental frequency) according to the input modulating signal. Here the amplitude variation of the modulation signal is reflected in the ON period variation of square wave. Hence, it is a technique of V to T conversion.
Pulse Width Demodulation
The input signal is Pulse Width Modulated, so the ON time of the signal is changing according to the modulating signal. In this demodulation technique during the ON time of PWM signal one counter is enabled. At the end of ON time, counter gives a particular count, which directly corresponds to- the amplitude -of input signal. Then this count is fed to a DAC. The output of DAC corresponds to
the amplitude of input signal. Thus train of varying pulse widths gives varying count values and accordingly DAC give outputs, which is directly proportional to amplitude of input signal. This is then filtered to get original signal. Thus at the output we get the original modulating signal extracted from PWM wave.
 
# EQUIPMENTS:
Experimental kit DCL -08 Connecting chords
Power supply
20 MHz Dual trace oscilloscope
NOTE: Keep The Switch Faults In Off Position.
 

# PROCEDURE:
Refer to the block diagram (Fig. 2) and carry out the following connections	and switch Connect the Power Supply with proper polarity to the kit DCL-08 and switch it on.
Put jumper JP3 to 2nd position.
Keep CH1 knob of CRO on 1 Volt/ divac. Keep CH2 knob of CRO on 2 Volts/ divac. Keep Times/ div knob on 1 msec.
Keep the CRO in Dual channel (Auto/ TV mode). Use X10 for expansion. After proper triggering of CRO, observe both the signals PWM IN and PWM

# BLOCK DIAGRAM:
<img width="803" height="922" alt="image" src="https://github.com/user-attachments/assets/2b5805a5-8c98-4a76-a244-c704b97bba63" />

# Tabulation:
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/45d2295c-3252-44e7-b0c9-b348c6c6f7a6" />

# Model Graph:
<img width="697" height="81" alt="image" src="https://github.com/user-attachments/assets/aa4034f9-a0d1-46b9-a323-56edaa038f22" />

# OUTPUT GRAPH:
<img width="1080" height="1479" alt="image" src="https://github.com/user-attachments/assets/278f264b-5191-47e5-a211-017c461b5812" />

# Result:
Thus the pulse width modulated and demodulated signals is generated and output is verified.

