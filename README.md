I wanted to share modified recoveries, which includes ADB enabled by default upon boot. 

I created this recovery because my phone had a broken touchscreen, which made it difficult to interact with the recovery and perform tasks like data recovery.

This should help anyone who needs to recover data from their device or needs ADB access in recovery mode without relying on a functional touchscreen.

Changes:

    Modified the init.recovery.usb.rc

    Added adbd to /sbin

Recovery Sources:
    Android 12 TWRP: https://xdaforums.com/t/recovery-3-...table-twrp-team-win-recovery-project.4452031/
    Android 14-15 TWRP: https://sourceforge.net/projects/yucellmustafa-builds/files/toco/recovery/toco_twrp_3.7.1.img/
    Android 14-15 OrangeFox: https://github.com/AndroidHQ254/Action-OFRP-Builder/releases/tag/9215890328

Thanks for everyone who contributed to creating these recoveries.
