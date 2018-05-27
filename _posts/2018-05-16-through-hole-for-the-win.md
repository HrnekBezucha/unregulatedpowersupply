---
layout: post
title: Through hole for the win!
author: Matej Lajcik
categories: Diode-ROM

---

![Imgur](https://i.imgur.com/cIfVq9c.png)

![Imgur](https://i.imgur.com/eIgBRBA.png)

 present you - once again redesigned - _Diode Matrix ROM with a 7 segment display all using exclusively hobbyist-friendly through hole components!_

It's a working title..

As you can see, we have few extra things in the design and I'd like to get through them with you.

5 volt regulator, just to be sure it's not going to let the smokey. I mean it still might but it would be the regulator, not the display itself, so .. hurray? That's how it's supposed to be done. Regulated power supply, current regulating resistors (R3-R9) to protect the aforementioned display, the display is a self-contained unit now. No discrete components if necessary. Also I wanted to meet the size requirements, which are 10x10cm board size.

There is also a ten pin header for a direct access to the memory from your favourite microcontroller, just send digital high on the pin and you'll get the display to show the chosen number.

Switch for automatic / manual clock - you have now complete controll over the clock if you so desire. Again with an Arduino or really any MCU board of choice. You can actually step through the numbers human-unnoticably fast so it's entirely possible to controll the board just from this one CLK pin.

Pull-up transistors in use are the ever-present BC547 (NPN) or any other pin compatible ones you might have.

