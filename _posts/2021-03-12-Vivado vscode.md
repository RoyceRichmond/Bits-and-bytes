---
title:  Vivado and Vscode is such a great combo
tags:
  - Vivado
  - Vscode
  - Vhdl
  - Verilog
---
Hey.
it's has been a while since my last post, I've been working on some new stuff, here's a brief post about what I think is a mod anyone should if using Vivado.

Vivado is a good software, its definetly an upgrade from ISE (I worked with it for about a year and a half) the work flow feels different, each stage can be run separately and you get a result which is more user friendly.

So what ? whats the problem ?, otherwise you wouldn't be writing this.
well the thing is that the editor is bad, its not the worse I've seen but it lacks a lot of features that a modern editor would have.

<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/mp.png" width="800" height="400"/>
</p>

As you can see the workspace is full of other stuff, of course you can minimize a lot of that extra windows and end up with something like this

<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/mp2.png" width="800" height="400"/>
</p>

Great, right ? well no, the think is that you can't increase the font size right away, if you want to do that you have to click on tool -> settings ->Text editor ->Fonts and colors and modify the size of the font, in a window like this

<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/mp3.png" width="800" height="700"/>
</p>

There's an easy fix for that, use Vscode as an external editor and get all the goodies you're used to.
First thing first, you need to change the settings to open un an external editor go to tools -> Settings -> Text editor choose "Custom editor" from the dropout menu and then click on the three dots a new window like this should pop up 
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/mp4.png" width="800" height="700"/>
</p>

there, where you will put these command
```c
code [file name]
```
Now eveytime you click on any source file vscode will open up and have that file to edit, now the next step is to add the extensions that will make your workflow smooth as the blues.

Go to the extensions icon and write "verilog" and the next extension will appear, this is a nice one and has a linter for vivado yai.
<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/mp5.png" width="800" height="450"/>
</p>

Next, search "vhdl" and the next extension will appear.

<p class="aligncenter">
    <img src="{{site.baseurl}}/assets/mp6.png" width="800" height="450"/>
</p>

I like to have VHDL and Verilog, in case I have to switch from one to another and just like that you have vscode working with vivado, you can change everything you want, hit save, after that go to vivado and a small icon will appear letting you know its updating.

have fun programming

