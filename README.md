AOSP+OMS-EXTENDED MarshMallow
===========

To initialize your local repository using the AOSP-OMS-EXTENDED trees, use a command like this:
````bash
repo init -u git://github.com/ishubhamsingh/manifest.git -b marshmallow
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
```

Device specific local manifest's are in this repo in the format <codename>.xml
