# stm32f4_discovery_vocoder
A simple record & playback vocoder using the STM32F4 Discovery

Features currently implemented:

<<<<<<< HEAD
Features currently working:
1.Audio output using the DAC and DMA
2.Audio input using the ADC and DMA
3.Recording and playback at different sampling rates
=======
* Audio output using the DAC and DMA
* Audio input using the ADC and DMA
* Recording and playback at different sampling rates
* Amplitude modulation with sine, square and triangle waves
* Adding echo and vibrato to signals
* LCD screen output
>>>>>>> origin/master

###Pins used on the board:

<<<<<<< HEAD
Planned features:
4.Modifiable output settings
=======
* A4 - DAC Audio Output
* C2 - ADC Audio Input
* D0,D1,D2 - Pushbutton Inputs
* E9,E10,E11,E12,E13,E14 - LCD Sceen Output

###LCD Screen
The LCD Screen being is the QC1602A. This makes use of the HD44780 controller so any LCD using this controller with similar pins would work as well.
The wiring guide for the LCD Screen is as follows:
* Pin1(VSS) - Connect to ground
* Pin2(VDD) - Connect to 5V
* Pin3(VO) - Connect through a potentiometer to ground (for contrast adjustment)
* Pin4(RS) - Connect to Pin E10 on the microcontroller
* Pin5(RW) Connect to ground
* Pin6(E) - Connect to Pin E9 on the microcontroller
* Pin7(D0) - Not Connected
* Pin8(D1) - Not Connected
* Pin9(D2) - Not Connected
* Pin10(D3) - Not Connected
* Pin11(D4) - Connect to Pin E11 on the microcontroller
* Pin12(D5) - Connect to Pin E12 on the microcontroller
* Pin13(D6) - Connect to Pin E13 on the microcontroller
* Pin14(D7) - Connect to Pin E14 on the microcontroller
* Pin15(A) - Connect to 5V
* Pin16(K) - Connect to ground
>>>>>>> origin/master
 
  
To run this project, open the project files using Atollic True Studio.
