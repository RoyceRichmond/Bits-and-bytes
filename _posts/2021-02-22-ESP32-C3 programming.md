---
title:  Programming the ESP32-C3
tags:
  - ESP32-C3
  - ESP-IDF
  - Programming
---
Hey, nice to see you again.

Last time we installed the latest version of the ESP-IDF, now we will program the board with to programs (just to get started, in the future I'll upload more as I progress). We'll go the easy way and use the included software and made some minor tweaks.

***Blink***

Ahh nothing says hello world! as a blinking LED, maybe the "Hello world!" itself. First go to the esp folder, then the examples folder and then the get-started folder
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/p0-0222.jpg"/>
</p>
Copy the blink folder to another location (after compiling the project some files are overwrite and trying to compile it for another target like the esp32 or the esp32-s2 will result in failure, if you won't change the target microcontroller, you can use the same folder without any problem).

Next you'll open the ESP-IDF command prompt that we installed the last time and change the directory to the new blink folder.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/p1-0222.jpg"/>
</p>
Next you'll enter the next commands:
```
idf.py set-target esp32c3
idf.py menuconfig
```
the first command will change the target microcontroller to the ESP32-C3 and the second command will open a menu where you can change the settings of the example program without to much hassle, this is mainly for quick and easy tweaks, bigger changes will have to be made in the source code.

On this menu go to the Example configuration, here you can change the pin that will be used as an output, I'll be using the pin 8 but any pin will do, enter the new pin, hit 'esc', hit s, enter again and you're good to go. You can skip this step and go right ahead to the programming part
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/p2-0222.jpg"/>
</p>
Type
```
idf.py flash -p COM9
```
replace with your respective COM port and the program will start compiling the project automatically, this might take a while the first time (couple of minutes maybe)
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/p3-0222.jpg"/>
</p>
After compilation is done it will upload the code automatically, at the end you should see a log message like this.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/p4-0222.jpg"/>
</p>
And just like that, you have a blinking LED.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/gif.gif" width="300" height="300"/>
</p>

***RGB led***

Now that you've some experience with the basics you can actually make the included RGB led flash (it's kinda like a ws2812, not sure if that's the correct part) very easily.

Again will do a copy but now from this folder examples\peripherals\rmt\led_strip

if you haven't closed the ESP command window just change the path with cd and the configuration, the addressable led is wired on the pin 8, and change the number of leds to 1, the window should look like this.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/p5-0222.jpg"/>
</p>
finish, save and like before upload the code with 
```
idf.py flash -p COM9
```
Just like that you can have the on board LED flashing.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/gif2.gif" width="400" height="300"/>
</p>

Running the examples is really easy, but this are just examples, next time i'll add some colour to it.

bai