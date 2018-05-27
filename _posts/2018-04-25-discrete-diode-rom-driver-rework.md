---
layout: post
title: Discrete diode ROM driver rework
author: Matej Lajcik
categories: Diode-ROM

---

![Imgur](https://i.imgur.com/5bftrTy.png)

Isn't the new render sexy?

The board won't actually be green but were getting ahead of ourselves.

This morning before going to work I decided to tackle those bugs I found in the memory. Hardware bugs. Isn't that funny. Well anyways.. at this point the Github project site should be up to date and bug-free. If you want to get a schematics or something else, go there and get the newest version.

The dead space _-no not that one-_ was also sorted so I don't feel like I'm wasting FR-4. Everything is neatly packed together while retaining the structure of the data array.

So the board I designed is in the process of creating and when I get it and test it, few well be available on Tindie. Considering it will work of course. I'm no secret squirrel over here so if/when I fall flat on my face, I'll write about it so you can all have a good laugh. And possibly avoid making the same mistake. Make your own mistakes.

Now one important thing is power supply. This little thing is meant to be used with a modified USB cable.

It's extremely simple and just as much useful. Not only for my projects that I try to keep compatible with it but for many other ones.

If you've been buying diy soldering kits (and if not I would suggest you to do so) then you noticed that many of them have standard 2 pins of 0.1" header sticking out for power input. That alone is a good enough reason to make this cable. Expect a how-to about that. Did I mention it's super cheap and easy? Well it is super cheap and easy.

The reason I mention this is that the circuit it's carefully balanced to work with 5V power supply. If you connect it to more than that it will die. That might not be the brightest decision on my part. That's actually pretty daft as I think about it more and more.

You can clearly see that I suck at marketing.

If the names of my projects aren't making that point clear enough.
