---
title:  ESP32-C3 is here, what should I do ?
tags:
  - ESP32
  - ESP-IDF
  - Wifi
---
Hey, nice to see you again.

About three months ago Espressif leaked the specs of a new IC, the esp32-c3. We're talking about the same company that is responsible for the ESP8266 (the best thing that could have ever happened to the IoT scene) and has single-handed sparked the new iot wave.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/esp.jpg" width="300" height="300"/>
</p>
So a couple of weeks ago [@John Lee](https://twitter.com/espressifsystem) post a this tweet
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/esp1.jpg" />
</p>
I mean, dev boards (obviously engineering samples or pre-production ones) with the new chip, how could I say no?
So I send him an email and got a response some days later. Fast forward to today and I have in my dry hands (a side effect of hand sanitiser and lots of soap) the esp32-c3, before we begin with all the fun and stuff. This is an engineering sample, therefore, it lacks some of the final features as described by the letter sent to me.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/esp2.jpg" />
</p>

***ESP-IDF***

So if you wanna program this IC you're in for a ride (I did and stumble against the wall for a couple of hours) but don't worry here you will find the easy way.
First of all, you need to install ESP-IDF this is the framework that will allow you to compile for the new RISCv processor, but it works only with the latest version (4.3). You're going to download the prerequisites you can find it [here](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html#get-started-get-prerequisites).

Download for your OS and next you'll find a window that looks very similar to the following one (I'm doing it on windows but it should be the same for any OS)
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/esp3.jpg" />
</p>
Click accept and then next, and also next on the following window. Then a window will ask you if you wanna install GIT or use one that you already have (git is in charge of downloading the info from the repositories), the next window will ask you if you wanna download ESP-IDF, and next which version, you should select the master branch
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/esp4.jpg" />
</p>
the master branch is the only one that has the definitions to use de c3 chip, the rest of the instructions are pretty straight forward, just leave it as is and click next when prompted.

In the end, you should see a new icon on your desktop or startup menu named ESP-IDF, when you click on it, a new command window opens and it adds temporarily the tools path and leaves you a nice message

<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/esp5.jpg" />
</p>

now you can compile and upload the projects, use this window always.

***VSCODE extension***

Is there a Vscode extension, right?, yes, Does it work? absolutely.

But here is the kicker, it only works with the stable version of the ESP-IDF (4.2 and below) so if you try to use the master branch it will fail on installation, if you try to replace the files, it won't recognize the configuration and prompt you to start over (I did this, and is really frustrating to see it failing over an over).

Please don't use the extension if you wanna use the C3 chipset, otherwise is an excellent tool that simplifies the process of coding, compiling, flashing and monitoring (I tried it with a normal esp32 and it's wonderful, feels like an Arduino uploading process but with so much more power), kudos to all the Espressif team for that extension, love it.

On the next post i'll walk you throug the programming of the esp and some examples anc configuration.

bye.
