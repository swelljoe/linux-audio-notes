# linux-audio-notes
My notes about making things work on Linux for my own future reference

# My current setup

Fedora 32 x86_64 installation, running either Reaper or Renoise (Linux 64 bit builds), Wine 5.10, Carla (2.1.1, sort of,built from git checkout on July 1, 2020).

Important: Wine and nearly everything else fails under Wayland. You have to use an X session to use any Windows apps with GUIs or VSTs.

# Windows VSTs that work with Wine and Carla or other bridge

|Plugin|Version|Notes|
|------|-------|-----|
|Synthmaster|2.9|Works. License registration happens on first load (during scan in Carla) and needs a restart, but afterward is fine.|
|Synthmaster Player|2.9|Ditto above|
|Union|1.0.3|VST2 and VST3 both work, but at least VST3 crashes periodically.|
|Scaler|2|Installs OK, seems to communicate, but mouse pointer disappears making it nigh impossible to use.|
|iZotope Iris|2|Licensing fails (via product portal, online reg, and offline reg, haven't tried iLok). This is true of seemingly all of their plugins.|
