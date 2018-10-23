---
title: Mario Game
link: https://colorlessenergy.github.io/mario-game-refactor/
layout: project
image: /images/mario-game.png
published: september 2017
meta: This is a mario game that taught me a lot about how games infrastructure are designed and built.
description: Front End Technologies
---

# Mario Game

I remember playing Mario when I was younger. Doing this project taught me a lot about how powerful plain JavaScript can be when you understand what is happening. I usually
used atom when I code but I decided to use vs code for the first time on this project. I chose to replicate Mario to see if any improvements could be made.

to play use the arrows key to move and jump.

[Live Version](https://colorlessenergy.github.io/mario-game-refactor/)

<a href="https://colorlessenergy.github.io/mario-game-refactor/">
    ![mario game]({{ site.baseurl }}/images/mario-game.png "mario game")
</a>


## Built with

* HTML
* CSS
* JavaScript

## Challenges

The first challenge I faced was loading the sprites and having the
characters animate. I started it off with just displaying a goomba on the the canvas. Then after it was displayed I made it animate with movement. The goomba at first wasn't being animated properly it was wonky so I had to fix it. I fixed this problem by just messing around with the time it starts animating after a animation is finished. Then I decided to load a map with the sprites I had. This was hard at first to figure out how to load a map with just sprites. What I ended up doing was setting up an array with different numbers which represents different blocks in the game. Then I chose to start implementing mario in the game. At first I decided to just display mario on the screen. Then add events to make mario move with the arrows keys. I used the same technique I used with animating the goomba but with mario.

The second challenge I faced was having the screen move properly when mario is moving across the screen. I tried many ways to implement. The first way was change the origin point which the background was getting render to the center. This was really nice solution but it split the screen when mario first showed up the left half was just black. You had to move a little to fix it. I found the best solution on google which was to implement a camera. At first I felt lost but I just read and tried to understand the math. I understood it after looking at it for a while. Now I have the best implementation of a camera which is nice.

The third challenge I had was trying to make hitboxes. I broke this problem into smaller problems I could solve. the first part was just having mario collide with a goomba. I did this by just doing a check of where mario current location was at and where the goomba current location was. The collison is really nice so I decided to use this with everything.

I am very proud of this project because it was the first time i tried something i thought it was out of my scope with just javascript. :)
