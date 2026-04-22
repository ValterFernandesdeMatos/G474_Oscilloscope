Simple two-channel oscilloscope using the STM32G474 running at 170MHz with a 3.5" ILI9488 display.
It is possible to measure frequencies up to 1.5MHz with some accuracy.
The code was ported from the STM32G476 with some changes.
Credits to the excellent work of Dominik Workshop
https://github.com/Dominik-Workshop/KD-23MTS
Frequency calculation changed.
Added outputs for attenuation selector activation.
I will soon add the front-end circuit with attenuation activated by pins PB3 and PB4 for channel 1 and pins PB10 and PB11 for channel 2.
The input circuit I used has been added. Attenuation is achieved by activating the AQY210 via the encoder. I used resistors with common values, and the VPP difference is corrected in the code.
