# RK3128-EE-Fix
DTB repository for the RK3128 EE "clones" + Kernel Fix

Kernel Source:
https://www.seefunplay.com/handheld/XF43.html

----------------------------------------------------

The G28, the XF43 and the R43S all suffer an issue in which ocasionally buttons are not regitered when pressed (dpad or abxy). To fix this issue the kernel must be updated. To update the kernel downlaod the kernel + kerneld.md5 and paste them them in your "EMUELEC" partition from your stock SD card (the orginal files will be replaced, so make a back-up before replacing them just in case). 

* The XF43 comes with a card that only works as a "roms" card, which means it doesnt have the "emuelec" partition on it (it uses the OS stored in the emmc). Im this case it is esier to acces the link above and dowload the full OS image, which you can directly flash into an SD card.

----------------------------------------------------

I have also added and experimental dtb with a slight refresh rate cahnge. The original dtb had it set to 55hz, and in the experimental it is set 60hz. In fast scrolling games like SMW you should notice the difference. *This dtb is experimental so use at your own risk. That said, I believe the screen is perfectly set to accept it and was just using a lower RR becasue it was copied from the dtb of a previous weaker console that used the same screen (but that is just a guess).
