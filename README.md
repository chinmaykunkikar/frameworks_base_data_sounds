Fix AOSP sounds
===================
**Current branch** - android-6.0.1_r22

`frameworks/data/sounds` directory of AOSP sounds are too fragmented, many duplicates floating around.
The `.mk` files are fragmented and do not track some `.ogg` files and/or track deprecated sounds that are deleted from the directory.
There are also separated markdown files for different nexus devices which are not being used while building the target.
