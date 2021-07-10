+++
title = "My Blog Post"
date = 2020-11-26T12:53:34-05:00
draft = true
+++

My mother loves gardening. She converted the mudroom in her house into a plantroom/ greenhouse. Naturally, she has a lot of growing lights hanging in the room, all attached to a single power strip. She has the power strip attached to a timer, but the outlet is in a really inconvenient location and the timer itself is no less than 20 years old.

I promised her a while back that I would try and think of a better solution for her. So, as a Christmas present, I'm going to build my mom a simple interface to turn her lights on/off and set her light timers.

My preliminary list of equipment is:

- a [Raspberry Pi 3 B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/?resellerType=home) that I have lying around from an old project
- a touch screen display for the Pi (I'm using a [OneNineDesign case](https://thepihut.com/products/raspberry-pi-official-7-touchscreen-case) I picked up from a friend)
- a smart outlet/plug, preferably one with an open API

In terms of the application itself, the functionality will be fairly simple:

- let user turn lights on and off at will
- let user schedule times that lights will turn on/off
- display the current status of the lights
- display how long the lights will be on with given light schedule

I'm planning to write the application in [Go](https://golang.org/] using the [Fyne](https://developer.fyne.io/index.html) package to handle the GUI.

I'll write another post soon as I get started.
