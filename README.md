AOSP+OMS Nougat
===========

To initialize your local repository using the AOSP-OMS trees, use a 
command like this:
````bash
repo init -u git://github.com/AEX-tmp/manifest.git -b 7.1.1
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
./build.sh device_codename
```
Example:
````bash
./build.sh falcon
./build.sh titan
./build.sh osprey
