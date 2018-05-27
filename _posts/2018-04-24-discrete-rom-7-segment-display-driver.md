---
layout: post
title: Discrete ROM 7-segment display driver
author: Matej Lajcik
categories: Diode-ROM
---
Did you ever wonder what memory looks like? Sure we all know the story of ones and zeros traveling through wires but there is a fair bit of hand wriggling accompanying it.

It's actually not that difficult to understand once you get the hang of the system. And taking a look at some prehistoric computer will definitely help.

The idea is that you have a net and putting voltage on one wire will result in either a voltage or a lack of it on another wire. That is your one or a zero.

Note we can't use just a wire net because all the wires would be connected. So putting voltage on one wire will have voltage anywhere and everywhere.

So let's separate all the rows and all the columns. This way we have a control over what is connected and what isn't. Connection is one and no connection is zero. The rule is to only connect rows to columns. All the rows are separated and so are all the columns. A link from one row to one column is a logic one.

That's all good and well but wires are conducting in both directions. So the signal we apply will backfeed to something else. Damn wires!

The system is solid it only needs a wire link that doesn't let the signal to feed back. <i>Diodes are kinda one way wires. </i>Yes! And honestly that's all there's to it. Some skilful connections and to made yourself a read-only memory - a <i>diode matrix.</i>

Bare in mind the voltage drop of the particular kind of diode you're using if you want to go down this path with me. Transistors are your pals, because pulling the signal high when active will ensure the output is strong enough to drive other things. Say, LEDs or GPIOs of your favourite micro.

This board I'm working on has two more parts other than the memory itself. An LED display to output the stored data (digits) and a clock that steps through the memory addresses.

Talking about it as if it was a real memory. That's because it is! Sure it's not exactly applicable in today's situations but I like learning bottom-up. And you might too.

So what are the actual specs of this thing? It's a ten word ROM. Word is a fancy byte. As we know, a byte is eight bits. Word is basically the same thing just not eight bits long. In case of this memory, a word is seven bits long. Because the LED display has seven separate segments. One bit for each segment. Ten digits - ten sets of seven ones and zeros.

I streamed bits of the process of designing such board and will do some steams in the future. <a href="https://www.youtube.com/watch?v=RcjmDCiezr0">The first one</a> was mostly about the schematics and <a href="https://www.youtube.com/watch?v=VZ6lebWdtbo">the second</a> was layout. You can also get the latest updates on the <a href="/Discrete-7-segment-driver">Github</a> project site.

Of course I would love you to join in on the design but I'm no Bob Ross and the happy little diodes sometimes go to places they shouldn't during those steams. All I want you to do is to understand. Hopefully I can achieve with these posts and when you watch the video you will know what I'm doing and be able to call me out when it's wrong. I'll find out but checking if stud actually works is not as interesting on stream so I do that later.
