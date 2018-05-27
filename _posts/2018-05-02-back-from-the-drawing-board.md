---
layout: post
title: Back from the drawing board
author: Matej Lajcik
categories: TinyBoard84100

---

![Imgur](https://i.imgur.com/YGnXr8t.png)

This time, everything should be just fine.

Yesterday I finished the board layout and today took time to check if everything is in order. Correct footprints, proper connections, pinouts and all that good stuff.

The board didn't really need to be laid out again from scratch but I did it anyways. One of the changes from the last version was choosing wider button solder pads. Or rather choosing the right sized footprint to be fair. Which wouldn't fit in between the side pin headers. So shuffling things around made it a bit more interesting.

PCBway's instant quotes also don't seem very reliable. Giving them dimensions for the panel and type, they eventually came back with price that's more than double. As an explanation was dramatically increasing board size and reducing quantity. I believe my fault was having the panel ended up larger than 10x10cm, which is one of the limits. But that still doesn't explain why individual board is supposed to be more than three times as big. I'll try it either tonight or tomorrow morning again with a different panel layout and see what they say.

My personal rule of not doing more than two projects at a time is firmly in place. This way I don't get too fractured between countless different projects and stay focused on what's at hand. Or soon will be.

Another thing to take care of is burning optiboot bootloader on the chips. So far the GUIness of Arduino IDE is fighting against me so moving in the direction of avr-gcc package will be one of the near targets to aim for.

And as always, the newest version is on my Github, all the talk and experiences here and that's that.
