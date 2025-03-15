I wanted to share modified recoveries, which includes ADB enabled by default upon boot. 

I created this recovery because my phone had a broken touchscreen, which made it difficult to interact with the recovery and perform tasks like data recovery.

This should help anyone who needs to recover data from their device or needs ADB access in recovery mode without relying on a functional touchscreen.

Changes:

    Modified the init.recovery.usb.rc

    Added adbd to /sbin
