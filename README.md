# RK3128-EE-Fix
DTB repository for the RK3128 EE "clones" + Kernel Fix

Kernel Source:
https://www.seefunplay.com/handheld/XF43.html

----------------------------------------------------

The G28, the XF43 and the R43S all suffer an issue in which ocasionally buttons are not regitered when pressed (dpad or abxy). To fix this issue the kernel must be updated. To update the kernel downlaod the kernel + kerneld.md5 and paste them them in your "EMUELEC" partition from your stock SD card (the orginal files will be replaced, so make a back-up before replacing them jsut in case). 

* The XF43 uses a card that works only as a "roms" card, which means it doesnt have the "emuelec" partition on the card (it uses the OS stored in the emmc). Im this case it is esier to acces the link above and dowload the full OS image, which you can directly flash into an SD card.
