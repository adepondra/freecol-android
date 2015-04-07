## Preparation ##

1 Get game data (3 options)

> a. Download FreeCol from [here](http://www.freecol.org/download.html) and unpack it.

> b. You can also get FreeCol source from Git
```
git://freecol.git.sourceforge.net/gitroot/freecol/freecol
```
> c. You can also get FreeCol source from SVN
```
svn co https://freecol.svn.sourceforge.net/svnroot/freecol freecol
```
See http://sourceforge.net/scm/?type=svn&group_id=43225 .

2 Make sure that you have your PC set up to access the device via ADB.

## Install data files ##

  1. adb shell mkdir /sdcard/freecol
  1. adb shell mkdir /sdcard/freecol/data
  1. adb shell mkdir /sdcard/freecol/save
  1. Go to the location where you unpacked FreeCol
  1. adb push data /sdcard/freecol/data

## Option 1: Building from source ##

  1. Download the source from http://code.google.com/p/freecol-android/source/checkout
  1. Set up a new Android project based on existing source code (and point it to where you downloaded the freecol-android source).
  1. Add the j2se-src as an additional source folder.

## Option 2: Download the latest APK ##

  1. Download the latest APK from here: http://code.google.com/p/freecol-android/downloads/list
  1. Install using "adb install -r <APK name>"