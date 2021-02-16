---
title:  New year's post and recap
tags:
  - New year's
  - Recap
---
Hey, nice to see you again.

Well this is a new year's eve post, expect a to see a lot of text (maybe not to much, but you had been forewarned)

<div class="card mb-3">
    <img class="card-img-top" src="https://lh3.googleusercontent.com/proxy/6ris4wJvA4Aj-IIgqr6IiXVuUOBi2i2UBayrDQVbsIXHnFZGYSUVNu_wb4I3PXpsjOIRMZ3JHnMZ_FXFtsDtJafCEYen3DgsNg627YGFGaRCjIP71YwvdhG-qpCzB-KwgmFtg7rz7KuRL4U1" alt="challenge accepted"/>
</div>
<!--more-->
Well, 2019 has been one of the most weirdest years of my life, by far.

If at the beggining of 2019 someone had asked me about my predicction for the future, pretty much every prediction would be wrong, almost.

the beggining of the year january and february were ok, some news about china and a novel virus were spreading, in retrospective i should have taken a little more attetion to it, but i was to busy working on many things.

***the thesis***

I studied my Bachelor of Engineering in Mechatronics in the "UPIITA"  and I really love my school (former by the time i'm writing this) is a great schoool, with nice classrooms and the best professors I've ever seen, not only they know a lot about many things (btw, i think that 80% of all the professors have a Phd), they're really humble and affable.

One of the options to graduate from UPIITA (at least the prefer one) is a thesis (senior thesis for the US and probably the rest of the world), so i got the first 6 monts of 2020 to finish my thesis, write everything, do a presentation, and finally my dissertation. My thesis title was "Octacopter for pothole detection", the project consists of two parts:
1. ***Octacopter***: the octacopter had a Jetson nano, two raspberry pi v2 cameras, a gps module,an 10DOF module I designed and a flight controller for the octacopter of course, the jetson nano would read one camera, run a mobilenet neural network for object detection (vehicles, pedestrians, etc), read the imu sensor and decide wheter it should push the throttle a little bit to get higher or just keep moving forward and use the second camera to take pictures of the pavement and store it (along side with the gps coordinates).

2. ***Convolutional Neural Network***: the neural network would take tha images taken from the pavement and predict if a pothole was present, keep the image that had one and store it in a new directory (with the gps location)

this was a lot of work, i had to process the images manually (i also create my own dataset of potholes), because the areas are not regular and vary from image to image, that alone took me a lot of time, when i finished the programming of the CNN took me a lot, i had ever in my life used keras or tensorflow (i had only seen basic NN and done some basic scripts on matlab, yup, matlab is not the best for NN).
the electronics part was actually easy, it took me like 2 weeks to have it from design to final product, and worked on the first try (yai!).

tldr?

okay :C, longs story short I finished on time, but the writing took the worst part and it became aparent on my dissertation, fortunately i passed it (althoug i still have to do corrections to the report).


***Cansat competition***

the cansat competition 2020 was interesting, this was the second time that i participated and the mission was out of the ordinary because the cansat had to transform into a delta wing plane, if the fact of launching something with all the electronics and mechanical systems is not enough, then it has to morph into something else.

We had a ton of things to design and integrate, I was in the sensor subsystem design, I had to integrate more sensors in a smaller package, take are of the energy distribution system, manufacture and test it.

If the latter sounds complicated, well that's 'cause it was, but I really enjoy working with this kind of projects and never grow tired of it and all the hard work paid off 'cause we attained the fifth place in the cansat competition, over a 100 teams enter in the first phase and over 40 teams were in the second phase.
For me this means a lot, it means that we have the capabilities to create new designs and tackle challenges, that maybe we don't have all the funding we would like to, but we got the work done and that is the point, the results 

***I'll be doing a Masters!!***

So yup, I got accepted into the master's program I wanted and I couldn't be happier, I think this is a huge opportunity to expand my horizons and stand upon the shoulders of giants, see what's next.