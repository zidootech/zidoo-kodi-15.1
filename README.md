#### zidoo-kodi-15.1

This is a special branch for RockChip rk3368 platform. First of all, you need the lastest verson of rk3368 sdk.
The implement of decoder and render are same as Amlogic. 
It request a library name "librkffplayer.so", you can find it on lastest version rk3368 sdk.
And the more important thing is, you need a device run with rk3368, such as Zidoo X6, 
which had deep modified to meet this new speicial version.

Our modifies were commited to branch zidoo-15.1, so please checkout it after you clone repository.

$git clone https://github.com/zidootech/zidoo-kodi-15.1.git
$git checkout -b zidoo-15.1 origin/zidoo-15.1

We modified ffmpeg too, so after checkout branch, apply the ffmpeg patch "kodi-ffmpeg-patch-20150910.patch" to your ffmpeg.
Then build the apk, and install to run it.

You'd better to run your apk on Zidoo X6, we are not sure if it run well on other devices.


Have fun and enjoy!

#### About Kodi

Kodi is an award-winning free and open source (GPL) software media player and
entertainment hub for digital media. Kodi is available for multiple platforms.
Created in 2003 by a group of like minded programmers, Kodi is a non-profit
project run and developed by volunteers located around the world.
More than 450 software developers have contributed to Kodi to date, and 100-plus
translators have worked to expand its reach, making it available in more
than 65 languages.

While Kodi functions very well as a standard media player application for your
computer, it has been designed to be the perfect companion for your HTPC.
Supporting an almost endless range of remote controls, and combined with its
beautiful interface and powerful skinning engine, Kodi feels very natural to
use from the couch and is the ideal solution for your home theater.

Currently Kodi can be used to play almost all popular audio and video formats
around. It was designed for network playback, so you can stream your multimedia
from anywhere in the house or directly from the internet using practically any
protocol available.

Use your media as-is: Kodi can play CD's and DVD's directly
from the disk or image file, almost all popular archive formats from your hard
drive, and even files inside ZIP and RAR archives. It will even scan all of
your media and automatically create a personalized library complete with box
covers, descriptions, and fanart. There are playlist and slideshow functions, a
weather forecast feature and many audio visualizations. Once installed, your
computer will become a fully functional multimedia jukebox.

***

##### Installation

See [docs/README.xxx] (https://github.com/xbmc/xbmc/tree/master/docs) for specific platform build information.

##### Quick Kodi development links

* [Contributing] (https://github.com/xbmc/xbmc/blob/master/CONTRIBUTING.md)
* [Submitting a patch] (http://kodi.wiki/view/HOW-TO_submit_a_patch) 
* [Code guidelines] (http://kodi.wiki/view/Official:Code_guidelines_and_formatting_conventions)
* [Kodi development] (http://kodi.wiki/view/Development)

##### Useful links

* [Kodi wiki] (http://kodi.wiki/)
* [Kodi community forums] (http://forum.kodi.tv/)
* [Kodi website] (http://kodi.tv)

#### Enjoy Kodi and help us improve it today. :)
