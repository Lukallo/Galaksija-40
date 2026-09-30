# Instructions for assembly
This is a translation of the original Serbian language instructions for assembling the 40th year anniversary Galaksija.

The original can be found [here](https://racunari.com/galaksija/uputstvo-za-sklapanje/lemljenje/)

The translation follows the original as closely as possible.
However a few details which only work in Serbian, such as colloquial terms given in quotes and some wordplay, have been left out or adapted.

## Soldering
In electronics, soldering is a simple and routine task which can be mastered in a short time. 
It's all a matter of practice, however many try to mystify soldering, and to make it seem more complicated than it is.
Nevertheless, some mistakes made when soldering are hard to fix, so if you don't have experience, it's best to experiment at least 20 minutes on some "harmless" project,
before you move on to a project which is important.
But ideally, you would have someone who has experience present, who will intervene only when needed.

To start, you will need a desk, preferably as large as possible, because sooner or later, you will see that you need more working space.
Lighting must be perfect, and a lamp which can be moved in all directions is a must, so that its position can be adjusted as needed.
An extension lead with a few sockets is also necessary, as you will soon find out that you're missing just one socket, and then another...

### Soldering iron

![](images/soldering_iron.webp)

The soldering iron, is of course the most important tool.
While not necessary, it can be handy to have a soldering iron, with a separate station for controlling the temperature.
A holder which will hold your soldering iron securely while you're not using it, is also necessary.
You can improvise a holder with a piece of sheet metal, or even a piece of wood with two crossed nails in it.
Any solution will be better than a soldering iron sitting at the edge of your table, waiting to hurt or damage everything which touches it, or on which it falls.

### Solder wire

Soldering wire is the next important item.
You can choose whether you want to use lead free solder, or regular solder with lead.
However, you should know that lead free solder is much harder to work with, as it requires a much higher temperature to melt.
It's easier to use regular solder with lead, and you can easily avoid it's harmful effects by ensuring your workspace is well ventilated, or even using a fan.
Special extractors for fumes exist, but it's easy to improvise a small fan, for example from a computer power supply.

When buying soldering wire, pay attention to it's thickness.
For soldering the Galaksija, a wire around 0.5mm thick will be fine.

### Soldering tip

The most important detail, in all of the tools, is the quality of the soldering iron's tip.
It's impossible to do a good job with a greasy and corroded tip, even if you've bought the best, most expensive tools.
Luckily, all manufacturers of soldering irons also sell spare tips, which should be changed regularly.
It's good to know that when first heating a new soldering iron and tip, the tip should be "tinned" as soon as possible, ideally as soon as the iron is hot enough to melt solder.
If you miss this step, the tip will oxidise very quickly, but just one drop of solder applied at the right moment can save the tip.

### Flux

Alongside good-quality solder wire, a little flux will also be useful: a substance which cleans solder pads, removes metal oxides and evens out the surface tension of the melted solder.
Here (in Serbia), it's sold under the name "solder paste" or "paste for soldering".
> **Translator's note:** In English, this is sold as "flux" or "flux paste"

Avoid old-style fluxes in big tubes, they are only good for soldering gutters.

In the past, a natural resin called rosin was used just as successfully, but synthetic flux is far more versatile.
It's true that every solder wire already contains a certain amount of flux, which you can easily see in the core of the wire, but for some jobs, especially soldering SMD (surface-mount device) components, extra flux is needed.

Along with these "cosmetics", it's also useful to have a special compound for reconditioning your soldering iron's tip, sold under the name "Tip Tinner", but it's harder to find in Serbia.
This substance, which is actually a mix of a special solid flux and microscopic grains of solder, can extend the tip's lifespan and prepare it well before you start work.

### Other tools

A few other tools will be of use, so you ought to have them at hand.
Small side cutters, a few different screwdrivers, a magnifying glass for inspecting fine details, a small pair of tweezers and a desoldering pump for removing solder.

The pump has a plunger with a spring that compresses, and when it's released by pressing the trigger, it sucks up all the solder from the solder joint (once you've melted it with the iron).
This simple tool is a standard part of every professional's toolbox, as it's handier to use than any complicated and expensive desoldering station.

![](images/tools.webp)

It's nice to have good tools, but the best helper for soldering is patience.
Every experienced electrician will recognise a hastily soldered board.

Generally, the rule is that the tip of the soldering iron, solder wire, solder hole and component lead meet at one point, as close as possible.


### Soldering technique

If you can overcome the desire to work quickly,
at each soldered joint, wait at least one extra second, where you don't move anything, just hold the iron on the joint you're soldering.
Don't worry about damaging the components by holding the iron a bit extra, electronic components are much more resistant to heat than you might think.
The Galaksija has exactly 700 solder joints, so holding your iron extra will cost you a bit more than 10 minutes, however it will vastly improve the quality.

### Common soldering mistakes

![](images/soldering_mistakes.webp)

The most common mistakes made when soldering, are the following:
<ol type="A">
  <li>Not enough solder. This connection is very weak, but fortunately it's easy to notice and fix.</li>
  <li>
      Too much solder and not enough heating. This is the worst joint you can make, and it is known as a "cold joint".
      The internal forces from cooling will probably
  </li>
  <li>Third item</li>
  <li>
      Too much solder. You'll need a bit of experience to be able to gauge how much solder to use for each joint.
      This type of joint is not by itself bad, at least if it hasn't made a short circuit, but it's ugly, and every professional will know at first sight, that whoever soldered it is a beginner.
  </li>
  <li>The solder pad on the PCB is destroyed with a </li>
  <li>A short circuit between two adjacent connections. This is a common mistake, so after soldering you should carefully inspect your board.</li>
  <li>
      A missed spot during soldering. 
      Whether it's because of hastiness or poor concentration, this is a mistake which even the most experienced professionals make.
  </li>
  <li>There's no mistake here. The connection is soldered correctly.</li>
</ol>

<img src="images/joints.webp" style="width:60%; height:auto; margin:auto;">

### Soldering SMD Components

If you don't have much experience with soldering, the most challenging part will be the small EEPROM in an SMD package.
But don't worry! 
It's good if you already have experience, but patience and paying careful attention will help much more.

<img src="images/smd.webp" style="width:60%; height:auto; margin:auto;">

It's not hard to solder the SMD chip, especially if you have a soldering iron with a fine and clean tip.
First of all, a thin layer of solder needs to be applied to two diagonally opposite pads on the PCB for chip U19.
Then, you position the chip (making sure it's correctly oriented), and press the soldering iron on the pins where solder is already on the pad.
When the heat transfers from the pin to the solder, the pin will be soldered, not very securely, but enough to keep the chip in place.

When you're sure that the chip's position is good

<img src="images/smd_vs_th.webp" style="width:100%; height:auto; margin:auto;">

### Recap and extra details

If you don't have any flux for soldering, the one already inside the solder wire will be enough.
You need to be skilled, so that the flux from the centre of the solder wire spreads precisely over the solder hole.


A few things here are very important, so we'll repeat them.
The soldering will be more successful, if your solder wire is not thick.
For soldering all of the components on Galaksija, it would be best to have two types of solder wire, around 0.4mm and around 0.6mm, but one wire of 0.5mm will be a good alternative.
However, the most important detail is the quality of the soldering iron's tip.
All modern soldering irons have swap-able tips, so it might be worthwhile to buy at least one new tip.
Straight away after turning the iron on, you should put solder on the tip, as otherwise, a dry tip can oxidize and become unusable in only a few minutes.

There also exists an alternative method for soldering SMD components, using a special paste which holds miniature, barely visible balls of solder in flux

### Order of Soldering Components

![](images/order.webp)

You might think that the order in which you solder the components doesn't matter, but you can save yourself a lot of trouble, if you organize your work properly.
The visibility of each stage of work will be best, if you at first solder the components which are lowest: 
the resistors and the diodes (at least D1-D4, leave D5 till later as it's bigger).
When you flip the board so as to solder the components, it'll be clear why you didn't rush to place the larger components as well: the resistors and diodes, which are the smallest and lowest components, won't fall out, but they'll be pressed against the table.

When you cut the excess wires after soldering, you'll see that everything is in it's place, and that none of the resistors are "hanging" by their wires.

![](images/resistors_done.webp)

Now you can solder the integrated circuits and IC sockets, which are currently empty, then the capacitors with 5mm lead pitch, which are a bit taller, and finally the connectors and vertical button (for a hard-break).
Now would also be a good time to place the programmed EPROMs in their sockets.

![](images/sockets_done.webp)

![](images/eeproms_done.webp)

## Connecting and Getting Started

It's simple to launch the Galaksija. Before all else, you need a monitor. Any modern TFT monitor or television will suit, which will be connected easily if it has a composite video input, which you can recognise by the RCA connector, like the one shown below:

![](images/cinch.webp)

If you don't have a monitor with a composite video input, you can use a monitor with an HDMI input (which all monitors have nowadays) paired with a video converter to HDMI, which will be easily found in the Serbian market, under a name which looks like AV to HDMI adapter and isn't too expensive.
Before buying, pay attention to the label, these adapters usually convert in one direction, so you would be making a mistake if you buy an HDMI to AV adapter.
Apart from that, keep in mind that this device is active, that is, it needs power, which is normally provided with a USB charger.
You will also need an RCA cable to carry the video from the Galaksija to the adapter, as well as an HDMI cable for the connection between the adapter and monitor.

![](images/adapter.webp)

While the Galaksija will work with any modern monitor, its 32 symbols per line and capital letters look a bit unusual on a screen 32" and bigger.
That's why if you can choose, buy a monitor 8, 9 or 10" in size, with a screen ratio of 4:3 as opposed to the usual ratio of 16:9.
Such monitors are usually sold for CCTV monitoring.

![](images/led.webp)

The Galaksija will work as soon as you plug it in, which is indicated by the LED on the left side of the board, 
and the message "READY" will immediately show up on the screen.

![](images/buttons.webp)

So, if everything is fine, the message will show on the screen after turning on.

![](images/ready.webp)

## Keyboard

A mechanical keyboard with standard dimensions proved itself to be a good choice for the original Galaksija computer, so there wasn't a reason to change that practice now.
In the meanwhile, Cherry created a good standard for mechanical keyboard switches, so it was easy to settle on the hole and pad positions for the PCB.

![](images/keycaps.webp)

56 switches are needed for the Galaksija, but you should buy at least 60, and keep the extras as spares.
The actual switches (this does not apply to the keycaps) come in 8 different colours.
Actually, those are only the colours of the central stems, which can't be seen after you put the keycaps on, but they serve the purpose of differentiating between different switch weights.
For example, red and brown are the softest (45g) and the most quiet (the first is completely silent), while white and clear are the hardest (80g) and noisiest.
Blue and green are popular with gamers, as they have a moderate weight and a hard "click", while black are the same weight, but without a click, so they're good for professionals in offices with many people.

## Mask for the keyboard

It depends on you, whether you will precisely position each key switch using the keyboard mask.
Everything will be alright, even if you do not use it, you just have to be careful when soldering switches, so that they're parallel.
If you do use the mask, it's easiest to cut it from a sheet of plexiglass, which is also sold as acrylic or perspex.
A thickness between 1.5 and 3mm is recommended, but every other thickness will also be fine.
These sheets are cut easiest on a laser cutter, which many workshops in larger cities have.
Many stamp makers also work with these machines.
You just need to bring them the file for cutting, which was made in the program CorelDraw.
This file, with the name: KBD_MASK.CDR, can be found in the section for downloading programs.

It the mask is thinner than 1.5mm, every switch can be put in its place, as there are teeth which click into place in the mask.
However, you should not do this before soldering the switches, as it will be hard to place all the switches at once, in the 108 holes on the PCB.
Instead, it's easier to solder 4 switches to start, one in each corner, and to then place and solder the others one by one.

<img src="images/keyboard_mask.webp" style="width:60%; height:auto; margin:auto;">

If the mask is thicker than 1.5mm, then it's even easier, as there is no reason to
Instead of that, the mask just needs to be placed onto the PCB, and then you place the switches one by one and solder them.
The mask will always remain in place on the PCB.
This is shown in the picture above.

The drawing for cutting the keyboard mask has holders for 3 switches for the space key.
Depending on which option you have chosen, you will need one or two, you can leave the third one, or cut it off if it annoys you.
For this, it's best to use a small circular cutting tool (they're best known in Serbia as a Dremel) or a regular hand saw.
If you want just one switch to remain for the space bar, cut the yellow area on the drawing, or for two cut the red area.
You need to cut the blue areas, if for the Enter key you will use a keycap which spreads across two switches.

<img src="images/mask_cutout.webp" style="width:60%; height:auto; margin:auto;">

### The problem of the Space Bar's stability

One of the problems will be brought by the switch for the SPACE bar.
The keycap for it is 118mm wide, so it's necessary to have a mechanism for stabilizing it, so that the space bar can only be moved up and down, without any rotation across any other axes.

Some companies manufacture and offer suitable stabilisers, but the questi
Search "Space bar stabilizer" on google, and you'll see which solutions exist.

Here, we'll describe 3 ways that this problem can be solved, sorted by complexity, and the quality of the solution.

1) Use a smaller keycap for the Space bar.
    That way it wont bend and get stuck.
    When you buy a keycap set, you'll get a large selection of different dimensions, so it won't be too hard to choose.

2) Solder two switches onto the PCB, where the space for this solution was planned.
    The middle switch in this case should not be soldered.
    This way, you'll get a usable Space bar, but the solution is far from ideal.

3) A solution with a mechanism is the best, so it might be worth it to make the     effort.
    First of all you have to dissasemble two key switches, so that you can remove the central stems, which are needed here (shown on the drawing in brown).
    Then you need to drill two holes of around 1mm in diameter, or a bit wider.
    The drawing shows where the holes need to be positioned.
    These 

Now you have to drill two similar holes on two "IN-IN" distancers M3*8, which are colored gray on the photo.
Be precise!

The wire (blue on the image) has to be steel, 1mm in diameter or a bit thicker.
Such wire is difficult to find for sale, but you can find it at a metal workshop, welder or some freelancer who manufacturers metal.


Some small corrections of the angle 

## Case

10 years ago, the publishing company Springer published a book Hacking Europe - From Computer Cultures to Demoscenes (ISBN 978-1-4471-5492-1).
Bruno Jakić, in an extensive article titled: "" says that 
In the hands of the creative, young people who were building them, many computers were equipped with some fairly creative and artistic housings, which is a characteristic which won't be repeated in the industry even decades later.


Now, 4 decades have passed, and we're faced with the same problem

Whether someone wants to make a case or not, the decision is theirs.
The opinion of the whole team which tested the computer, is that the case is not necessary especially if you have a good plexiglass base, screwed to the PCB with M3 bolts and distancers around 3-5mm.


<img src="images/base_plate.webp" style="width:60%; height:auto; margin:auto;">

Today, many people have access to 3D printers, if they don't already own one.
Why not try? or, if you're skilled at making cases from plexiglass, you can try hand at this challenge as well


## Power

The Galaksija is powered by
The power consumption is around 150mA (or a bit more if you don't use a CMOS, but a NMOS processor)
It's best to get a USB cable, and cut it so that the "big" USB-A conector remains.

For connecting the power, a 2.1mm barrel connector with a positive middle is used, the most standard type, which can be easily found in whichever shop that sells electronic components.

The D5 diode can be any
It's only purpose is to create a short circuit, and to save the other components, if you accidentaly connect the Galaksija with reversed polarity.

This 
But, if you are sure that you won't make a mistake with the charging polarity, you can leave this diode out.

The Diodes are polarised, so you have to be careful of their orientation before soldering.
The printed ring always marks the cathode, so with a little bit of care, you won't make any mistakes, paired with the fact that the ring is also marked on the PCB.
This applies not only for the big D5, but for all the other diodes aswell.

For the diodes D1-D4, the BOM says that they're Schottky diodes, also known as a Hot Carrier diode.
That is a special manufacturing technology, which gives a much lower loss in power in the allowed direction.
The recommendation is therefore, the the diodes D1-D3 are of the Schottky type.
For the diodes D4 and D5, it doesn't matter if they're Schottky or ordinary silicon ones.