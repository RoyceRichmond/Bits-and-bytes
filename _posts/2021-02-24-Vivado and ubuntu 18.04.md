---
title:  Vivado and the shortcut problem
tags:
  - Vivado
  - Xilinx
  - Ubuntu
---
Hey, nice to see you again.

A new (online) semester has begun and with it new projects, challenges and bugs await (i can almost taste the time I'll have to spend debugging or smashing my head againts the wall 'cause something doesn't work)
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/bb.jpg"/>
</p>

This is my first semester as a master's student and I have choosen the high performance computing branch, this means that this semester I'll be having the course "Microtechnology and processors architecture".

As a final project I should implement a processor on an FPGA (during my B.E. I had two courses were I worked with FPGA boards). Now I have to use a new IDE, Vivado.

***Vivado 2020 installation***

Installing vivado was pretty straight forward, by request of our professor it had to be done on linux (I choose ubuntu), the thing is that after the installation finished I got no shortcuts on the desktop. I could use the command line every time to start the program (but tbh I'm a little lazy about that regard and i like the ease of clicking an icon and getting it working).

So i had to create the shortcut manually and here is what you should do if you want to do it too.

***Create the run command***

First we'll create the run command file, use the following command

```
sudo gedit /usr/local/bin/run-vivado-run #(you could use any other name)
```
Next put the following command (this is the installation path of vivado) on the text editor then hit save
```
#!/bin/bash
. /opt/Xilinx/Vivado/2020.2/settings64.sh
vivado &
```
***Create the shortcut***
Now we'll create a shortcut, run the following command.
```
cd ~/Desktop/
sudo gedit "Vivado 2020.2.desktop"
```
This will open a text editor window, and there you can paste the following command.
```
[Desktop Entry]
Version=1.0
Type=Application
Terminal=false
Icon=/opt/Xilinx/Vivado/2020.2/doc/images/vivado_logo.ico
Name[en_US]=Vivado 2020.2
Exec=/usr/local/bin/run-vivado
Name=Vivado 2020.2
StartupNotify=true
```

Save the file and you're almost good to go, next we have to change the permission to execute the file.
```
sudo chown $USER:$USER "Vivado 2020.2.desktop"
```

Now you can click on the shortcut on the desktop and a windows like this should pop out
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/ab.png"/>
</p>

Hit trust and launch there you go, a handmade shortcut for vivado (only in case that the installer doesn't install it for you)

<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/ac.png"/>
</p>

That's everythin for this entry.

Bye.
