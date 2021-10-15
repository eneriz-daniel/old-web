---
layout: page
title: instin
description: a Raspberry-based wireless instrumentation control system
img: /assets/img/oscilloscope.jpg
importance: 3
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/instin-scheme.png' | relative_url }}" data-zoomable alt="" title="Instin's scheme"/>
    </div>
</div>
<div class="caption">
    Instin-based system scheme. Each gateway can be connected to up to four instruments.
</div>

**Instin** is a wireless instrumentation control system based on gateways, which are in charge of receive the instrumentation commands from the host computer, send them to the instruments and reply the requested information (if any) to the host.

The gateways are based on SBCs (*Single Board Computers*), concretely Raspberries Pi Zero W, which are extremely low-cost. To ease the connection of the instruments to the raspberries, a USB hub specifically engineered for these SBCs, the Zero4U hub, was coupled to each RPi, thus allowing the connection of up to four instruments using type-A-to-type-B USB buses.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/instin-gw.jpg' | relative_url }}" data-zoomable alt="" title="Gateway"/>
    </div>
</div>
<div class="caption">
    Complete gateway (Raspberry Pi Zero W + Zero4U USB hub) with two instruments connected through the type-A USB ports.
</div>
