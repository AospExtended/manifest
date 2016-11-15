AospExtended Nougat
===========
This project is based on 
[**AOSP-OMS**](https://github.com/AOSP-RRO).Huge thanks to [**Akhil 
Narang**](https://github.com/akhilnarang) and [**Sri 
Surya**](https://github.com/srisurya95) for the development of 
AOSP-OMS.AospExtended is just an extension to AOSP-OMS,through which we 
are trying to provide a stock aosp experience along with some important 
customization features.We have cherry-picked the features from many 
other projects and hence we are very thankful to them.

##Credits
* [**AOSP-OMS(Base Rom)**](https://github.com/AOSP-RRO)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**AOSiP**](https://github.com/AOSIP)
* [**Temasek**](https://github.com/temasek)
* [**ZephyrOS**](https://github.com/Zephyr-OS)
* [**TurboROM**](https://github.com/TurboROM)
* [**TeamSubstratum(Theme Engine)**](https://github.com/TeamSubstratum)

##How to Build?

To initialize your local repository using the AospExtended trees, use a 
command like this:
````bash
repo init -u git://github.com/AospExtended/manifest.git -b nougat
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
