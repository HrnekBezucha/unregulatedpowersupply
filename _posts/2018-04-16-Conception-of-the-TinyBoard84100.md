---
layout: post
title: Conception of the TinyBoard84100
author: Matej Lajcik
categories: TinyBoard84100
---
![Conception](https://i.imgur.com/kOMooa8.png)

This little guy is the most recent variation of the TinyBoard84100. There was one before but it's currently busy catching dust on my desk and I don't want to interrupt. It will come to picture once this little bugger is summoned into a physical form. Sure I could go out at night kidnapping virgins for blood to use in the secret rites of PCB production but there are people doing just that for living. I'll leave it to the professionals.

Places like PCBway in China will happily make the boards but charge per piece and minimal dimensions and quantity. So if your boards are as small as this you'll make them extra money for no good value. Because there are ways or getting around this.

Panelisation.

Essentially, instead of getting design made as is and wasting money, the design can be duplicated and triplicated and more-plicated one right next to the other. Then they can be snapped off to separate them. It's also easier to populate the boards all at one. The reason I'm saying it is that the design may be finished but I still need to get to panelise it. And send off and pray to the dark overload that they'll accept my offering with no extra charge.

Look at that - I said so much about it but not what it actually is. Naughty me.

The TinyBoard84100 is a ATtiny841(-SSU) breakout with a voltage regulator, reset button and AVR ISP programming header. The 6 pin one.

ATtiny841 was chosen because it has 14 pins for you to play with, more 16-bit counters, more PWM channels, more UARTs, more ADCs, more of all the good stuff. More so than the all-present ATtiny84. Which itself is a more-pinned version of yet more all-present ATtiny85.

But afaik the ATtiny84 has the same pinout so if you use that instead you should be just fine.

It's all open source on my Github and talked about here. If you'll watch the site, you'll get all the information about it. Because I like talking about it but my friends don't speak electro-gibberish.)
