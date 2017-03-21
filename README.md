# Android Mic Fix
Fixes in call Mic issues for various Android devices.

Tested on OnePlus One running both Android 6 and 7 Roms

**Note: Originally designed for the OnePlus One but will work for some others. Your mileage will vary.**

## Prerequisites
* Rooted Android Device
* Magisk v11.6 or higher

## How it works
Uses the tool "resetprop" to modify the following values found in build.prop:

Removes:

	ro.qc.sdk.audio.fluencetype=fluence

Adds:

	persist.audio.fluence.voicerec=true  
	persist.audio.fluence.speaker=false  
	use.voice.path.for.pcm.voip=true

## Links
* [Magisk](http://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445)
* [Support](http://forum.xda-developers.com/apps/magisk/module-oneplus-one-bacon-mic-fix-t3503128)
* [Github](https://github.com/Magisk-Modules-Repo/bacon-mic-fix)
* [Donate](https://www.paypal.me/Nomelas)

## Change Log 
#### v2
* Name changed from OnePlus One (bacon) Mic Fix
* Updated template to v3
#### v1
* Initial Release
