Steps to install supersu:

Prerequisite:
  Download:
    factory image: https://developers.google.com/android/nexus/images?hl=en
    Supersu: http://forum.xda-developers.com/showpost.php?p=63197935&postcount=2
    twrp: http://forum.xda-developers.com/nexus-5x/general/guides-how-to-guides-beginners-t3206930


1. fastboot flash system system.img (from factory image, unzip 2 times)
2. fastboot flash boot boot.img (from bullhead systemless zip)
3. flash supersu-v2.56 in twrp
4. enter recovery mode
5. adb push SuperSU-v2.56-20151030013730.zip /sdcard/Download/
6. Install SuperSU
7. When the installation is finished, it would ask if you want to swipe to install it again, PRESS "Do not install"
