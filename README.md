AOSP+RRO MarshMallow
===========

To initialize your local repository using the AOSP-RRO trees, use a command like this:
````bash
repo init -u git://github.com/AOSP-RRO/manifest.git -b marshmallow
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
```

### repo sync
[![Build Status](http://blazingphoenix.in:8484/buildStatus/icon?job=AOSP-RRO-Sync)](http://blazingphoenix.in:8484/job/AOSP-RRO-Sync/)

### rom build
[![Build Status](http://blazingphoenix.in:8484/buildStatus/icon?job=AOSP-RRO)](http://blazingphoenix.in:8484/job/AOSP-RRO/)

Device specific local manifest's are in this repo in the format <codename>.xml
