The Android Open Source Project Lollipop 5.1
===========

To initialize your local repository using the AOSP trees, use a command like this:
````bash
repo init -u git://github.com/F-AOSP/manifest.git -b aosp-5.1
```
Add Moto G resources by typing this:
````bash
curl --create-dirs -L -o .repo/local_manifests/moto-msm8226.xml -O -L https://raw.githubusercontent.com/F-AOSP/manifest/aosp-5.1/moto-msm8226.xml
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
. build/build.sh device_codename
```
Example:
````bash
. build/build.sh falcon
```
