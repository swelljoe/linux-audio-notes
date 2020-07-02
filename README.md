# linux-audio-notes
My notes about making things work on Linux for my own future reference

# My current setup

Fedora 32 x86_64 installation, running either Reaper or Renoise (Linux 64 bit builds), Wine 5.10, Carla built from git checkout on July 1, 2020.

Important: Wine and nearly everything else fails under Wayland. You have to use an X session to use any Windows apps with GUIs or VSTs.

# Windows VSTs that work with Wine and Carla or other bridge

|Plugin|Notes|
|Synthmaster|Works. License registration happens on first load (during scan in Carla) and needs a restart, but afterward is fine.|
|Synthmaster Player|Ditto above|
|Union|VST2 and VST3 both work, but at least VST3 crashes periodically.|
