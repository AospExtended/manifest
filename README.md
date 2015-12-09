AOSP+RRO MarshMallow
===========

To initialize your local repository using the AOSP-RRO trees, use a command like this:
````bash
repo init -u git://github.com/AOSP-RRO/manifest.git -b marshmallow
```
Add Moto G 2013/2014 resources by typing this:
````bash
curl --create-dirs -L -o .repo/local_manifests/moto-msm8226.xml -O -L https://raw.githubusercontent.com/AOSP-RRO/manifest/lollipop-5.1/moto-msm8226.xml
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
