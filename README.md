This is a special branch for RockChip rk3368 platform. First of all, you need the lastest verson of rk3368 sdk.
The implement of decoder and render are same as Amlogic. 
It request a library name "librkffplayer.so", you can find it on lastest version rk3368 sdk.

And the more important thing is, you need a device run with rk3368, such as Zidoo X6, 
which had deep modified to meet this new speicial version. 


After clone this repository, apply the ffmpeg patch "kodi-ffmpeg-patch-20150910.patch" to your ffmpeg.
Then build the apk, and install to run it.

You'd better to run your apk on Zidoo X6, we are not sure if it run well on other devices.


Have fun and enjoy!
