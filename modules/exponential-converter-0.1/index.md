---
layout: module
title: Exponential Converter 0.1
description: Exponential Converter that I built for my modular synth drum machine project.
image: modules/exponential-converter-0.1/154388090_471161937385519_3133007917346548765_n.jpg
---

# Exponential Converter

*Version 0.1 from February 2021*

![](154388090_471161937385519_3133007917346548765_n.jpg)

Exponential Converter that I built for my modular synth drum machine project. I wanted a snappy release based on the linear one from the Envelope Generator (EG). This will make the snare drum sound natural.

It's based on a design by Robin Mitchell in ["DIY Synth Series Part 1 — The Exponential VCO"](https://www.allaboutcircuits.com/projects/diy-synth-series-vco/).

## Details

To find transistors with the same HFE, you have to match them. I used the instructions described in ["Transistor matching" by Kassutronics](https://kassu2000.blogspot.com/2015/10/transistor-matching.html) 👍

For the calibration I build a testing circuit with different voltage inputs (set by trimpots) and checked the output with a multimeter. You can see a photo of that and the resulting chart below. With the trimmers I set it to peak at ~10 volts input because this is where the CV of my envelope generators peak.

![](154071496_785706842365955_7819474831100190743_n.jpg)

![](153647548_2848334918766242_4271693317320118724_n.jpg)

![](chart.png)

## Links

* [Video Demo](Bumm Bumm Garage Exponential Converter 0.1 Video Demo 640p.mp4)
* [Schematic (PDF)](Bumm Bumm Garage ExpConv 0.1 Schematic.pdf)
* [Stripboard Layout (PDF)](Bumm Bumm Garage ExpConv 0.1 Stripboard Layout.pdf)
* [Front Panel (PDF)](Bumm Bumm Garage Exponential Converter 0.1 Panel.pdf)

## Improvement Potential

See the comments on [Instagram](https://www.instagram.com/p/CLwjxVGh8AB/) and [Reddit](https://www.reddit.com/r/synthdiy/comments/lt0a0m/exponential_converter_in_eurorack_format_on/).