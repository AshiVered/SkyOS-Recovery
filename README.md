# SkyOS-Recovery
Hacked RECOVERY for SKyOS (from Nokia 800Tough v40)
# Goals:
* get adb working in recovery mode
* hack the recovery to install unsigned zips
* change the label from KaiOS recovery to SkyOS Recovery (SkyOS is my custom ROM for this device)
# Known bugs
* ADB works only partially (adb pull/push works. adb shell returns a strange error
```
- exec '/sbin/adbdsh' failed: No such file or directory (2) -
```
* Although I replaced ramdisk/res/keys with test keys, as explained here I still can't install unsigned zips.
* I don't know how to change the caption that is displayed in recovery mode. Does anyone know how? It is possible, in GerdaOS recovery they did it.

# its modify with Android Image Kitchen
