# I3wm and picom configs

Here are my config files for [i3wm](https://i3wm.org/)  and [picom](https://github.com/yshui/picom) that i use on my two machines.   
I use the main brach of picom, and the [i3-gaps](https://github.com/Airblader/i3) fork, which at the moment of writing is planned to be (but not yet) merged into i3wm with the release of the 4.22 version.

## I3wm+Plasma

I use this setup on Ubuntu 20.04.5 LTS, allowing me to have all the pros of i3wm without the hassle of having to set up anything else system-wise, at the small price of some jankyness that i have (mostly) found a solution for. 

I followed [this guide](https://github.com/heckelson/i3-and-kde-plasma) by heckleson to set it up.

In addition some custom scripts were added, for quality of life improvements:

1. [Autotiling](https://github.com/nwg-piotr/autotiling) by Piotr Miller
2. [Terminal swallowing](https://gist.github.com/windwp/b46e8bdeac793867b34d2191e66a6f44) by windwp

and for bug patching, both made by me (a colossal effort, i know)

1. `nitrolol.sh` to fix nitrogen bugging on dual monitor setup
2. `plasmalol.sh` to fix plasma bugging out on startup, as better explained in the config

(yeah, the names are kinda on the nose)

## I3wm

Nothing much to say here, i use this more bare version of i3-gaps on my machine running Arch Linux. Why? Because ~~I'm lazy~~ I wanted to try and being comfortabloe with both a more customized and a more stripped version of i3wm.
