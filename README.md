# Conky-Minimalism-tweaked

A Simple Conky config tweaked by myself, a git repo just to save it tbh.
The whole thing use the rings_lua framework

Basically tweaked color, changed some things for a **much** better ressource consumption, added numbers to CPU temp bars and added freqs value. A lot of these things are specific to my own hardware config, you'll have to tinker (probably).

## why you would want it

You like the original conky but would like more stuff onscreen, while still keeping it minimalist, and in the same time have a decent CPU usage

**Requires:**

- ttf-roboto | [AUR](https://www.archlinux.org/packages/community/any/ttf-roboto/)
- Conky with lua support | [AUR](https://aur.archlinux.org/packages/conky-lua/)
- lm-sensors | [AUR](https://www.archlinux.org/packages/?name=lm_sensors)
- cpupower | [AUR](https://www.archlinux.org/packages/community/x86_64/cpupower/)

## Installation

1. Extract the zip file
2. Change the paths in minimalismRC & startup.sh
3. Run startup.sh

(and add startup.sh to some kind of autostarting script, or alternatively, setup your conkyrc)

## contributors and credits

It is basically a very simple fork of NoTranslation/Conky-Minimalism.
Credits to them, their repo is where I got a lot of the code

If you want a simple conky working out-of-the box with your 16+ cores CPU I'd suggest using the original repo

Note:

- If Core temps are not displayed correctly, see line 264 in clocks.lua
- you may have to specify which battery index you have (for me BAT1), replace all BAT1 by BAT0 or the appropriate in minimalismRC and clocks.lua

![](./example2.png)
