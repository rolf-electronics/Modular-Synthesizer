# Modular-Synthesizer
Self build Synthesizer with what I can find on the internet

The **LFO** is based on an **Arduino Uno** with a **Sallen Key low pass filter** and two opamps. One for *level offset* and *span* adjustment and a last stage opamp for inverting the signal.

**First Pictures** **https://github.com/rolf-electronics/Modular-Synthesizer/issues/1**

Faceplate
![LFO faceplate](https://user-images.githubusercontent.com/64435848/89296541-c47eba00-d662-11ea-9461-e2585dc7a448.JPG)

The almost full bread board model
![DSCF8330](https://user-images.githubusercontent.com/64435848/89454321-cfb80f80-d760-11ea-9655-173efd9ca126.JPG)

**Video of the different Wave types** **https://youtu.be/yQFZsXjjzXU**
(video quality can be better)

* Green dial   (a rotary encoder) is for selecting a wavetype, currently 43 types are available
* White dials  are for the LFO range (a rotary encoder) and frequency (a potmeter)
* Yellow dial  (a rotary encoder ) is for distortion (still to be programmed)
* Blue dials   are for voltage level offset and range

The switch is for free running or synch mode.

Output jack on top is LFO output. 
Output jack on the bottom left is synch in. 
Output jack on the bottom right, fixed 0-10 volt.

* The **green**  rotary encoder has a switch. Pushing is sets wave type to no 0, which is a triangle.
* The **grey**   rotary encoder has a switch. Pushing is sets wave type to mid range, type 21 for now.
* The **yellow** rotary encoder has a switch. Pushing is sets wave type to ADSR.

In **ADSR mode** the yellow rotary encoder selects A - D - S or R, with the pushbuttons the levels can be increased and decreased.

* Top LED is for LFO frequency and level indication.
* Mid LED is over or under range when using the rotary encoders. (and should be placed a little more to the right for the next one)
