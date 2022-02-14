---
title:  3D printer goes prrr
tags:
  - 3D printer
  - PSU
  - fail
---
Hey.

So I guess that at this point everybody knows or knows somebody who knows or has a 3D printer, in case you've missed it (somehow ?) I present to you the 3D printer

<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/prusa.jpg" width="400" height="500"/>
</p>
Now that We've the same idea I'll continue, so I have a 3D printer that helped me many times through college, many projects (and way too many internet memes) were done on that printer, eventually I had to leave it cause I graduated and didn't need more pieces, so all is hunky-dory in the story c:.

Fast-forward to some months, I wanted to print a chassis for a robot, sliced the model, fired up the printer and let it go but after a couple of minutes the printer's buzzer starts to sound, it rebooted, and I was left wondering What the hell happened.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/clueless.jpg" width="400" height="400" class="center"/>
</p>
So naturally I tried again, because if something fails you must try again under the same circumstances to see if it was a fluke (sometimes it is but most of the time it doesn't :sadface: ) I ended up with 3 fail prints and me wondering why it failed out of the blue, this is what happened next.

1. Wondered if a cockroach eat the wires
2. delete the last idea
3. Maybe it was the software (sure, working software will blow up just because it's a Monday)
4. Recompile the software
5. Upload the software (perhaps I solved it)
6. tried again C: (I think I got it)
7. Resets :c
8. Repeat steps 3 to 7 four more times

Ok, at that point I was mad, how on earth did that happen? Dunno, but it did.

I concluded that the main board was fried, so I went to AliExpress and bought a new one (I had the SKR 1.4 with apparently is now deprecated so I had to choose the SKR 2.0)

After a couple of weeks it arrived at my door, I got excited because I could print again, so I teared it apart and replace the board, flash the firmware (I'll write another post about it cause it's actually quite interesting) and got another reset, by that point I was like this.

<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/ralp.jpg" width="700" height="400" class="center"/>
</p>


After all the mumbo jumbo I resourced to google, I don't remember how I search for it, it was something like "3D printer turns off help me :sadface:" maybe not, but you got the idea. Some googling after I stumble upon an old forum post where they said that eventually the output capacitors in the PSU die after sometime, thus they don't regulate the voltage as good and a brownout occurs (the voltage in the microcontroller goes below a certain threshold, the microcontroller sees this a problem and turns off everything including itself).

Now I have two working boards and a faulty PSU, I mean at least I know what's broken


bye.

