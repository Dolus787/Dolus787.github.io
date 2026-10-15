---
layout: default
title:  "Tiny North"
date:   2025-08-30 11:44:38 +0200
---
![TinyNorth]({{ '/Assets/TinyNorth/FlyingSaucer_BeautyShot_v001.png' | relative_url }})

Tiny North was a game project funded by Sammes Stiftelse. I was one of two programmers working on the game, and was responsible for a lot of the gameplay, UI and sound implementation.

Tiny North is a physics based puzzle game, where you play as a small alien who has crashed in a forest outside Skellefteå. You look for parts to your spaceship all over Skellefteå and get to explore the city while solving puzzles with your trusty grapple gun.

The game project lasted two months and resulted in a fun little prototype with a grapple gun with a fully custom simulated rope and some other gameplay features to be able to create dynamic and fun puzzle levels. We have prototype tutorial level and most base gameplay-features implemented.

The most important of said features was the physically simulated rope, ropes could be shot from the grapple gun or be placed in the level ahead of time to carry level elements such as swings. The ropes used Verlet integration and had collision detection.

Here is a demo of a block hanged from four simulated ropes being shot with the grapple gun:

![RopeDemo]({{ 'Assets/TinyNorth/CurrentRopeDemo.gif' | relative_url }})

Here is a [walkthrough of the prototype tutorial level](https://drive.google.com/file/d/10X8z_sMC1FvBUGN8KjGCsR79-pdYT2wy/view?usp=sharing).

Check out the [github repo](https://github.com/tagetjerngren/TinyNorth).
