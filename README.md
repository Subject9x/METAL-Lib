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


### Requirements
--------------------
One of the following Quake Source ports.
* Darkplaces
* FTEQW
* Quakespasm Spiked (pending).

Compiler I personally used for writing this code base.
* FTEQCCGUI