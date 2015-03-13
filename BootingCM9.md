/data needs to be mounted at boot:
```
--------- beginning of /dev/log/main
I/DEBUG   (  920): debuggerd: Nov 25 2011 16:10:39
E/installd(  930): Could not create directories; exiting.
E/keystore(  931): chdir: /data/misc/keystore: No such file or directory
```

The file /init.<ro.hardware>.rc is loaded from init. ro.hardware is read from /proc/cpuinfo's "Hardware:" line with spaces removed and undercased. The CM repos appear to have a init.nvidia.rc, but no init.harmony.rc as would be necessary; this will need to be added with the correct mount for /data. Note that these are in the root directory and so pulled from the ramdisk, meaning boot.img will need to be updated for this to take effect.

Also, changes can be made to /system/etc/init.local.rc through recovery rather than rebuilding boot.img.

Files that appear to be missing:

  * F/BatteryStatsImpl( 1027): Caused by: java.io.FileNotFoundException: /proc/net/xt\_qtaguid/stats: open failed: ENOENT (No such file or directory)
  * E/CommandListener(  927): Failed to open /proc/sys/net/ipv6/conf/wlan0/disable\_ipv6: No such file or directory