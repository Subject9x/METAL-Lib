# _METAL-Lib_

## Overview
----------------------
This is a series of API and include files for adding the following features to any desired QuakeC mod.
* a common GUI API to build off of.
* Menu.dat progs for custom Main Menus.
* CSQC menu system.
* customizable HUD.

The desired goal is that the systems are somewhat discrete, allowing the modder to only really add what
they'd want. This repo though is the main source - bug fixes, updates, etc would all be here and
then shared with release packages.

Also included is documentation for implementing each of these main features into your existing quake mods.

The full working example can be found in the game https://github.com/Subject9x/battleMETAL which I also developed.

### Requirements
--------------------
One of the following Quake Source ports.
* Darkplaces
* FTEQW
* Quakespasm Spiked (pending).

Compiler I personally used for writing this code base.
* FTEQCCGUI

### Visual Examples
#### CSQC Menus
![steam6](https://user-images.githubusercontent.com/12732481/135560954-22d2c4e8-74b0-4d78-8ca3-1d6b64887513.png)

![image](https://user-images.githubusercontent.com/12732481/135561009-66dfb8eb-3482-4190-8908-498f457e4ea5.png)

#### Main Menu
![image](https://user-images.githubusercontent.com/12732481/135561054-0c7d46eb-1c2f-42c7-b6f5-a946c0cf2da6.png)
![image](https://user-images.githubusercontent.com/12732481/135561064-519b3916-47a1-468f-9e49-13ec7341f521.png)
![image](https://user-images.githubusercontent.com/12732481/135561084-71a217f7-772c-4bf4-a88a-7c87920ddefe.png)

#### Hud System (soon)

