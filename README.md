# digispark-mouse-jiggler
A USB stick that makes the mouse on the PC it's plugged into jiggle. Useful for preventing screensavers without changing settings.

# **⚠️ I AM NOT RESPONSIBLE TO ANY DAMAGE CAUSED BY THESE USBS. ANY USAGE WITH MALLICIOUS INTENT IS NOT CONDONED BY ME. ALL OF THE CODE FOR THESE USBS ARE MEANT FOR EDUCATIONAL PURPOSES.**
# Digispark USB Code
## Requirements:
[Digispark USBs ($20 for 5)](https://www.amazon.com/AiTrip-Digispark-Kickstarter-Attiny85-Development/dp/B0836WXQQR)

[A computer](https://i.ebayimg.com/images/g/kpIAAOSwhrRfxT2F/s-l300.jpg)

[Digispark Drivers](https://github.com/digistump/DigistumpArduino/releases)

[Arduino IDE](https://www.arduino.cc/en/software)

## Setup:
File>Prefrences then add https://raw.githubusercontent.com/digistump/arduino-boards-index/master/package_digistump_index.json to Additional Boards Manager URLs

Tools >Board "somethinghere">Boards Manager

Type: Contributed

Install Digistump AVR Boards then close out of that window

Tools >Board "somethinghere">Digistump AVR Boards>Digispark (Default - 16.5mhz)

## Uploading Code:
Paste in the code from main.ino from the repo into the Arduino code editor.

Hit the upload (->) button on the top.

When it says to plug in the USB, plug it in.

As soon as it is done, unplug the USB otherwise the code will execute.

Enjoy.
