
The Phone circuit contains these parts:

- Phone playing audio
- 3.5mm audio jack (with ground, left, and right wires stripped)
- 9V battery
- Breadboard and jumper cables
- LEDs
- Resistors
- Alligator Clips

I plug in the audio jack to the phone. I wire up the LEDs and resistors on the breadboard, with jumper cables to go to ground. Power -> resistor -> LED -> GND. Then, I attach the GND of the audio jack, to the GND of the breadboard. I then attach both the left and right of the audio jack to the GND of the 9V battery. I then attach the PWR of the 9V battery to the PWR on the breadboard. 

You should then see the LEDs all light up. This is simply applying power to the breadboard because the circuit is complete. If you unplug the audio jack from the phone, you will see the LEDs turn off. If you start playing a song, you will actually be sending the data through the LEDs, but you just dont have the speaker circuit hooked up yet, so you have no way to verify it's being sent, since the LEDs modulate too fast for the eye to see.


The Speaker Circuit contains these parts:

- Solar Cell (mine is 6V)
- Speaker (Mine is a powered bluetooth speaker, but I don't use the bluetooth at all. I simply use the audio in jack)
- 2 way 3.5mm audio jack
- Alligator Clips

Make sure your speaker has power, or is charged if it contains a battery. I use the "audio in" on my speaker, so I have a 2 way 3.5mm jack, which I plug 1 end into the speaker, and the other end I connect the GND (base) and PWR (tip) to the respective GND and PWR of the solar cell.

