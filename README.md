<p align="center">
<img src="https://github.com/AospExtended/manifest/raw/7.1.1/aex_logo.png" width="320px" height="320px" > 
</p>

AospExtended Pie
===========
AospExtended is just an extension to AOSP, through which we 
are trying to provide a stock AOSP experience along with some important 
customization features. We have cherry-picked the features from many 
other projects and hence we are very thankful to them.

Credits
-------
* [**JDCTeam**](https://github.com/AOSP-JF-MM)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**ABC ROM**](https://github.com/ezio84)
* [**GZOSP**](https://github.com/GZOSP)
* [**Pure Nexus**](https://github.com/PureNexusProject)
* [**OmniROM**](https://github.com/omnirom/)
* [**AOSPA**](https://github.com/aospa/)
* [**BlissRoms**](https://github.com/BlissRoms)

How to Build?
-------------

To initialize your local repository using the AospExtended trees, use a 
command like this:

```bash
  repo init -u git://github.com/AospExtended/manifest.git -b 9.x
```
  
Then to sync up:
----------------

```bash
  repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch aosp_device_codename-userdebug
  mka aex -j$(nproc --all)
```


Please do not forget to go through our [Documentation, Official Devices & Thread Template](https://github.com/AospExtended/Documentation_and_thread-template/) where
we have our specific guidelines regarding Official Device, Template, Gerrit etc.

## Important Links:

- [Our Website, Downloads and Usage Statistics](http://www.aospextended.com/) 
- [Our Github](https://github.com/AospExtended/)  
- [Gerrit Code Review](http://gerrit.aospextended.com/) 
- [Documentation, Official Devices & Thread Template](https://github.com/AospExtended/Documentation_and_thread-template/) 
- [Apply for Offiical devices](https://github.com/AospExtended/official_devices) 
- [Device official builds & changelog](https://github.com/AospExtended-Devices/official_builds)
- [Help us translate AospExtended ROM and bring it to the world!](http://translate.aospextended.com/)
- [Our Blog](https://blog.aospextended.com/)
- [Telegram Channel](https://telegram.me/aospextended/) 
- [Theme Resources](https://github.com/AospExtended/AEX-Scripts/) 
- [Extended Devices](https://github.com/AospExtended-devices/) 
- [Markdown editor](http://dillinger.io/) 
- [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 
- [JSON formatter](https://jsonformatter.curiousconcept.com/)
- [Gerrit Manual for AospExtended OS](http://gerrit.aospextended.com/Documentation/intro-user.html) 
- [AospExtended Gallery](https://aospextended.imgur.com/) 
- [Facebook page!](https://www.facebook.com/aospextended/) 


