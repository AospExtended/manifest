The Android Open Source Project Lollipop 5.1
===========

To initialize your local repository using the AOSP trees, use a command like this:

    repo init -u git://github.com/F-AOSP/manifest.git -b aosp-5.1

Then to sync up:

    repo sync

Finally to build:

    . build/envsetup.sh
    lunch aosp_falcon-userdebug
    make bacon -j#

 #=PC core number+thread number

