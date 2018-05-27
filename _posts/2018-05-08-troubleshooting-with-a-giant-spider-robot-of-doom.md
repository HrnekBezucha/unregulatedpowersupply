---
layout: post
title: Troubleshooting with a giant spider robot of doom
author: Matej Lajcik
categories: Diode-ROM

---

![Imgur](https://i.imgur.com/rkaNIOk.jpg)


As it happens, the board wasn't quite flawless. Once again. But that's okay, these are prototypes. Hence the giant spider robot of doom.

Everybody knows the 555 circuits, right? Right.. Everybody knows that astable multivibrator has two resistors and two capacitors. But not always. You can leave pin 5 to just flap about. It's not like it's going to run away in a search for a better and more fulfilling life anytime soon. But is important to give it the freedom to do so. To make its own decisions in life. And become responsible member of a circuit that way. Or you can tether it to the ground with a 10nF cap. Tying it right to the ground is just bad. Don't do that, me.

I won't.

If the thing that Dark Souls taught me was that you only lose when you give up trying, then electronics taught me that failure has a cost and it's worth being careful and attentive, rather than pouring another point in strength and charging to the the frontline.

When I tried to put the board together I didn't realise how bad it is to have tilted bench. Those minimelfs.. they just roll off and vanish from the face of earth never to be seen again. A case for Phil Marlow. Perhaps if I had solder paste I'd just sit them in it like a stick in a dogshit. But I don't have solder paste, nor do I have a dog. Or the industrial hair drier to melt it with - meaning the solder paste obviously.

Now allow me to explain the giant spider looming above the board like a huge steaming iron. The worst is when a board kinda works but not really. All the diodes are the right way around, all the LEDs too, resistors and ceramic capacitor are unpolarised. And it didn't work. Not well enough. The number lit on the display and nothing happened. Shorting pins 1 and 3 increased the count. So the 4017 was working correctly. The only other suspect was the 555. I pulled it off only to find out I didn't have any other SMD ones. But I do have DIP! Dead bug style would not help because could already see myself getting the pins jumbled up and shorting something.

So there it is. Very much an alive bug now. With eight legs - a spider. Currently, with seven legs, actually. I offered a 100nF cap to the pin 5, which as I mentioned was causing trouble. And then, finding out it works just right I chopped it right off. Pin 5 has all the freedom it can ever get. Just hanging there overlooking the board, giant seven legged spider of doom. Robot.

Robot is a cool word.
