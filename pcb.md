# xG1000 PCB

## The Design

I have played with Arduinos for years and done the basics of learning how to wire a simple button, rotary encoder, potentiometer, LED etc.  So, to make a G1000, or xG1000 as I am calling it to avoid any over-zealous lawyer, it was quite simple.  The real life G1000 is made up of a mixture of these.  I built and created by schema using EasyEDA which is a fantastic PCB prototyping application (https://www.easyeda.com) and simply connected each component to a pin on an Arduino Mega2560.  I used Mega2560 as they have the most pins to use, are cheap (approx £7 each) and most Flight Sim software use these.  I tend to have several laying around.

The idea design meant that it would attach 2 x Mega2560s to a solid, single PCB where all of the components were attached.  Basically, creating a complex Arduino Shield.  I have seen many homemade G1000s over the years with 100s of wires; whilst they are fantastic and work perfectly, the amount of effort, problems with alignment, near-impossible troubleshooting, simply was not worth it.  I tried.  Failed.  Wasted a lot of time.  

This time, I wanted to do it efficiently.


## The Fabrication

Once I had gone through each pin - and there are nearly 400 on this board - I had them fabricated in China.

A note on errors and wastage.  I went through 4 fabrication cycles to get this final one to work.  At cost.  And about 3 weeks delivery per cycle.  It happens.  I have spent £1000s over the last 2 years with prototypes due to wiring mistakes - never a manufacturing error.

## The Awkward Conversation

Ok.  I'll cut to the chase.  I will not be releasing the EasyEDA Source Files or the Gerber Files (the exported files that the fabricators use to make the boards).  Don't ask.  I won't be doing it.  And here is why.

A couple of years back, I spent months, and months building various Flight Sim PCBs and panels.  I also spent £100s of fabrication costs to iterate on the design, remove wiring errors, component alignment etc.  I was happy to share everything as I see this as a hobby and wanted to share the enjoyment with others who want to build flight simulators at home.  

However, I shared the sources files with a caveat saying "please don't change these too much, please don't sell the source code, or the PCB schematics, and definitely do not have these fabricated and then sell them for profit".

A few months later, I received a load of abuse, lots of requests telling me my product was rubbish and that I am a rip-off mechant.  And some people just asking for support.

Obviously, someone went against my wishes, against the spirit of the flight simulator home community, made my PCBs and didn't even remove my name/email/website from the PCB... and sold them at a ridiculous cost.

So, please feel free to use the concept, the ideas, but I will not be releasing the source of the PCB into the wild.  I will, however, release the source code of the logic.lua for the AirManager component.

At some point, I ***may*** do a limited run of the PCBs and sell them at cost plus postage etc.

## The PCBs

![IMG_1798](https://user-images.githubusercontent.com/19530895/129242232-9c695b85-11e8-442b-94fc-3f9775552836.jpg)

![IMG_1797](https://user-images.githubusercontent.com/19530895/129242239-cfabf30a-43c3-4ae3-9b06-a3a065a29b53.jpg)

  
