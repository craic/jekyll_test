---
layout: post
title:  "Power Tool Batteries as USB Power Sources"
date:   2019-01-24 08:52:37 -0800
categories: jekyll update
---

This post describes how to use high capacity power batteries from cordless power tools to power microcontroller projects via USB.
This is a great way to power standalone projects for longer periods of time than are possible with typical **Li Poly** batteries.

If you have an interest in Do-It-Yourself projects, carpentry, building etc then you probably have a set of
cordless power tools.

These are powered by substantial batteries and with each generation of the technology these have become lighter and more powerful.

My current set of tools are from **Makita** and have **18V Lithium Ion** batteries. 

![Makita power tools](/assets/images/20190124_makita_power_tools.png)

These batteries are available with several capacities. I have **2.0 Ah** and **4.0 Ah** (amp hours).

This capacity comes at a price, however, at **$50** to **$60** for each battery. 

![Makita batteries](/assets/images/20190124_makita_batteries.png)

Makita and several of the other manufacturers realized that there was a market for an adapter that would let people charge their
phones or tablets via a USB cable, using their batteries as the power source - ideal for a builder needing to charge a phone on site
without access to regular power.

Makita's version of this is the [Makita ADP05 18V LXT Lithium-Ion Cordless Power Source](https://www.amazon.com/dp/B019WI5XXO) which 
costs around **$ 20** from Amazon. This unit slides onto a battery just like a power tool. It has two USB ports covered by dust caps, 
an On/Off slide switch and a belt clip.


![Makita battery with USB adapter](/assets/images/20190124_makita_battery_w_usb_adapter.png)

The unit can deliver **2.1A** at 5 V per USB port and you can connect two ports with a suitable cable to deliver **4.2 A** which is more than 
capable of powering a Raspberry Pi, a display and then some.

![Makita battery with Raspberry Pi](/assets/images/20190124_makita_battery_w_raspberry_pi.png)

How long a battery will power your project obviously depends on the load but you run a Raspberry Pi for 24 hours with the 4.0 Ah battery with no problem.

The output is USB so you can just treat it as a regular power source. In my experiments I measured a voltage of **4.99 V** which was low enough to 
trigger the low voltage warning on a Raspberry Pi (*the yellow lightning bolt in the top right of a console display*) but this did 
not seem to affect the operation of the Pi in the least.

The adapter is pretty simple in design with just two prongs that connect to the battery. The battery itself has those as well as a
seven pin connector that only appears to be used by the battery charger - probably to measure charging progress or faults.

![Makita battery with Raspberry Pi](/assets/images/20190124_makita_battery_next_to_adapter.png)

A nice feature of the batteries is a series of red leds that show how much pwer is left when you push the small button below them.
This turns out to be very useful.

![Makita battery with Raspberry Pi](/assets/images/20190124_makita_battery_power_indicator.png)

Because they are designed for use with power tools, these batteries are pretty rugged. There does not appear to be any problem with 
running the battery all the way down and then recharging it. 

If you need more than **2.1 A** then you can connect the two USB ports using a special USB 'Y' cable to get **4.2 A** - for example 
[StarTech.com 3 ft USB Y Cable for External Hard Drive USB A to Micro B](https://www.amazon.com/StarTech-com-Cable-External-Drive-Micro/dp/B0047AALS0)

![Makita battery with Raspberry Pi](/assets/images/20190124_makita_battery_w_double_usb_cable.png)


These batteries would be an expensive solution to powering your projects if you don't already have a set of power tools. 
But if you already made that investment then an additional $20 gives you a very useful capability.

*As a bonus you have a nice way to charge your phone or tablet next time you lose power !*

My gear is all Makita but **Dewalt** and **Milwaukee** power tools have effectively the same thing and there are multiple third party 
copycat devices available on Amazon.
