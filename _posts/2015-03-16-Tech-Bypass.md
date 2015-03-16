---
layout:     post
title:      Technological Bypass
date:       2015-03-16 13:31:19
summary:    It seems smart to focus on the pain point you’re trying to solve, rather than the first-order technological problem at hand.
categories: notes
permalink: /techbypass/
---

Problem: There’s a HDMI cable running between my laptop and living room tv whenever I want to stream movies or shows.

There’s plenty of options available, but there’s two that seem interesting:

Solution 1: Some form of wireless broadcasting from my laptop to the screen.

Solution 2: Controlling a cheap device connected to my tv that can stream directly from the internet.

Solution 1 probably involves messing around with Codecs, Drivers, Streaming, Compression, Encryption and Networking. All complex stuff. Solution 2 needs a little piece of standard hardware, running a small server function to communicate with the internet and local devices.

Which of these has a bigger research cost to prototype and develop? 

Moore’s Law is compacting our devices, down to the point that streaming 1080P and beyond can be handled by a fanless chip on a stick.

Creating a whole new encoding method, drivers and hardware to wirelessly use a television as a second screen for a laptop is a whole different beast. There’s so many limits to fight. First of all, the local network is streaming high quality content to the users laptop. Then, you’re trying to relay that content from the laptop, back to the router and into the fancy piece of kit plugged in to the tv. This is a nightmare for I/O and bandwidth.

It’s much simpler to have the laptop tell the chip on a stick (a) what video stream and (b) when to do it. That’s lightweight. Much simpler, much less intensive.

There’s something intriguing about a chip on a stick ([ChromeCast](https://www.google.co.uk/chrome/devices/chromecast/)) bypassing problems that are complicated ([Check out Airtame](https://airtame.com/)).

Part of this comes from using a process like [5 Why’s](http://en.wikipedia.org/wiki/5_Whys) to figure out what pain point you’re actually trying to solve. Don’t take the first-order why. Figure what you’re actually trying to do. *I.e. Control a big screen from the comfort of your sofa*. This is not the same task as *develop the capability to mount your television as a second monitor*.

Focus on the use cases you’re solving - because the problems that you can technologically bypass are limited by the needs of said group.