# FlatPort
Teensy 2.0 Risc-V dropin Arduino promicro lookalike with special features.

It has a in-plane Type-C USB receptacle - it does not show much but it doubles as a full featured Type-C post - in this case a reversible USB 2.0 spec port only.

It also features in plane Reset and Boot0 tasters - they are shorted by touching with a pointy metal object.<br>
  Do note they are not to be touched mutually by a same metal object: one shorts pin Boot0 to ground the other pulls the reset pin to Vcc.<br>
  In effect this means one of the contacts is gound and the other is Vcc - shorting them mutually would blow the fuse!

![Top view assembled](https://github.com/fire-h0und/FlatPort/blob/main/photos/IMG_20250111_110740_134.jpg "A top view of the FlatPort R1.03")

![Bottom View](https://github.com/fire-h0und/FlatPort/blob/main/photos/IMG_20250111_110723_833.jpg "A clumsy lit back view of the FlatPort")

![View of the FlatPort](https://github.com/fire-h0und/FlatPort/blob/main/photos/IMG_20250111_110654_295.jpg "Lying flat on the deskpad")

I picked to make this project for the alleged compatibility with QMK firmware - to be a future keyboard daughter board.
As i get to that point expect more updates here, it is on my ever growing TODO list :o}
