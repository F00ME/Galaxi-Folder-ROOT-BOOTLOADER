I'm using a text translator, so the instructions can't be that good.


If you are using Linux, install heimdall from the command prompt.

If you are using Windows you will need the phone's AP, having to look for the Firmware compatible with your device, which is not that difficult to find.

What I'm going to teach will be with Heimdall

step 1:

 install magisk on your cell phone, where you will modify your boot.img, then transfer this modified version to your computer or any device that has cmd and heimdall installed.

step 2:

Hang up your device using the end call button. just press for a few seconds. Then call again to end the call together with volume+. When the loading is finished, go to the bootload option and click on it.

step 3:

with your device is at the bootload screen, connect it back to the computer and type your cmd.

To make sure your phone is connected:

heimdall detect

To add the boot modified by magisk you must copy the address where your boot is located:

heimdall flash --BOOT /example/your modified boot.img

Your cell phone should react to this and turn on normally within a few seconds. Check in magisk if your root is installed, or in any application that detects root.

If you want the bootloader unlocked, the process is similar, having to go to the bootloader screen again, check via heimdall if it is connected and type

heimdall flash --RECOVERY /example/recovery.img

When executed, you will have unlocked your bootloader and you will be able to see it if you try to turn off the cell phone with end call and turn it on with volume

the apk apps is if you don't have playstore, or want more open source apps. Good luck!!
