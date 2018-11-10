# Those Funny Funguloids!

(Original README follows)

# Fork of Fork:
## ADDED:
* Speed control with up/down keys
* Speed boost with space bar
* 10 lives each level
* 16 instead of 3 extra mushrooms in special level (catch the whirler)
* Tested with Linux Mint 19

### Build Instructions

```
  sudo apt install build-essential autoconf ogre-1.9-tools libogre-1.9-dev libois-dev liblua5.1-0-dev 
  ./configure
  make
  make install
```

--  
Karl Zeilhofer, 2018


# Fork of unmaintained "Those Funny Funguloids!"

## DONE:
 * make required changes for Ogre 1.9.
 * make it buildable on Ubuntu 16.04.
 * build mpk files from mpk/ directories on "make"
 * more Ogre 1.9 updates
 * drop cg

## TODO:
 * upgrade to Ogre 1.10

## LONG-TERM TODO:
  * run it on Andriod :)

--  
thektulu, 2016

***

"Those Funny Funguloids!"
Copyright (c) 2006-2007, Mika Halttunen & Teemu Ruokolainen

This Linux version (v1.06) is based on my initial, preliminary attempt, and has
been since dremendously improved (i.e. made to use the standard autotools,
support for OpenAL added, etc..) by Piet (<funguloids@superpiet.de>). So big
cheers for him making Funguloids on Linux possible! =)

Please refer to INSTALL on how to build and install the game properly. You have
the option to use either OpenAL or the proprietary FMOD Ex for the audio output.
Ogre 1.4 or later, along with OIS and Lua 5.1 are needed as well.

See bin/readme.html for the rest of the documentation.


Thanks for the interest, have fun! :)


Contact me at: lsoft@mbnet.fi
http://funguloids.sourceforge.net

--  
Mika Halttunen
