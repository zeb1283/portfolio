---
layout: project
type: project
image: img/png-transparent-atari-2600-breakout-logo-video-game-volleyball-miscellaneous-text-logo.png
title: "Zebtari Breakout"
date: 2023
published: true
labels:
  - Python
  - pygame
summary: "In-progress clone of Atari Breakout"
---

## Overview
This is a project that I started recently, and I plan to complete by the end of the semester. It uses pygame to create a clone of atari breakout, a popular arcade game that I used to play in the browser when I was bored in class. Currently, I have game time working, a working window and background, and a sprites file that will eventually hold all of my in-game objects (i.e. the ball, bricks, powerups). I already have the player platform that can move back and forth with the left and right arrow keys.

## Mechanics
Speaking of the platform, I'm handling movement using Vector2 pygame objects, which will pay dividends in the future when I add some little powerups(or powerdowns, really) that were not necessarily included in the base game. Currently, movespeed is handled by a system that includes a base value that is changed based on whether the player wants to move the platform left or right. This value is multiplied by a base speed value and can possibly be changed with the addition of a speedup/down power modifier.

## Why I haven't finished it
I don't want to deal with object collision right now :P

## Screencap of Current Gamestate
<img src="">
