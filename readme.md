## WeakAuras Arcane Readme

This repository contains several World of Warcraft® Mage Arcane interface improvements and some firing events.

## Working version

V 10.X (current, as long i'm updating)

## Installation

1) Import the crypted codes to your WeakAuras Interface
2) Unpack the soundFiles.rar into your WoW folder : _retail\Interface\Addons so it looks like __retail\Interface\Addons\soundFiles_
3) There's a text code in __codeFunctions_crypted__ working with the activation of a global variable, you'll maybe need to create a macro to activate that variable : By default it's deactivated and keeps __false__ after reloading

- I'll be nice, i give you the code here :)

		/run if CMTActive == nil or not CMTActive then CMTActive = true else CMTActive = false end
		/dump CMTActive


4) __Be wared__, __lots of timers use sounds__ : you may want to check what sound is triggered for specific spells, i tried to make choices unique in order to make them more memorable. Some sounds are incorporated within script itself.

## Files

1) __arcane_crypted__ : dashboard containing several datas (Charges, Spec Auras, Stacks, timed buffs, Health, Prismatic barrier, harmony, touch of the magi, radian spark etc..)
2) __arcaneDefensive_crypted__ : timers for defensive CDs
3) __acaneOffensive_crypted__ : timers for offensive CDs
4) __mmAffixes_crypted__ : current tracker (with voice) for the current mm+ affix
5) __stats_crypted__ : tracker for the stats
6) __trinkets_crypted__ : track some of the trinkets, but miss some of them, you'll probably check another one

## Updates

The content of this WeakAuras is updated when the author (me) has new features or modifications to implement

Free to bring personnal modifications

## Special Thanks

https://www.curseforge.com/wow/addons/weakauras-2 -- AddOn Resource

https://www.sounds-resource.com -- sound resources
