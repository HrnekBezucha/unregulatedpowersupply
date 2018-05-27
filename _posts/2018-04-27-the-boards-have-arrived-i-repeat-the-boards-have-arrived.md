---
layout: post
title: The boards have arrived, I repeat, the boards have arrived!
author: Matej Lajcik
categories: TinyBoard84100

---

![Imgur](https://i.imgur.com/laLoemy.jpg)

![Imgur](https://i.imgur.com/bHRxv2v.jpg)


Remember when I said that I want you to learn from my mistakes? I have a lesson to teach.

But first things first.

The boards for TinyBoard84100 arrived. PCBway made them for me. For some reason I really like white PCBs but if you have a look at the close-up, the silkscreen was worn off at places and off centre. It really is a service for prototypes and not for manufacture. I wouldn't feel too confident sending boards looking this way. Even if they worked but again, we're skipping ahead. It might be just because of the less used black colour. This didn't happen with any of the previous PCBs I ordered from them.

The lesson I've learned is: check your footprints. Then check them again and again. And pinouts of schematic symbols you created. Check if they match the parts you already have or the parts you want to order.

I know I'm hasty when the layout is done. I want the thing to be made asap. But that also means I don't take the time to check if things are actually going to work.

And these boards will not.

Just to add salt to the wound, I remember being hasty with the discrete ROM boards as well. I already know about one screwup I did with them - no current limiting. But if that's the only thing it's still going work.

So what actually happened?

The voltage regulator, which goes to the bottom of the board (78L05) is usually in SOT-89 package. For some inexplicable reason I choose SOT-23. That is not a complete disaster, the regulators are sold in this package but if I got those, the pinout would be all wrong.

I'll probably try to bridge it all in one board and assemble it just to see if the rest is working correctly. Then I can rework only that part. And order them again. After that I check and re-check and then check again couple more times to avoid making stupid mistake like this.

I hope you appreciate my honesty and won't repeat my mistakes. Make your own.

I don't know how much of this you get taught at school, I didn't get any of it. Didn't go to school.
