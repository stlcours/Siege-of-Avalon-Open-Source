# Siege of Avalon : Open Source #

_"Siege of Avalon : Open Source is an attempt to keep this great isometric RPG game alive by continuing development on it. Our aim is to create a SDL version of the engine that will work on Win32, Linux and where ever Pascal compilers and SDL are supported."_

This is a fork from the [**gondur/Siege-of-Avalon-Open-Source**](https://github.com/gondur/Siege-of-Avalon-Open-Source) repository.

The main focus of this fork: 

1. Moving the Win32 source to newer Delphi 10.3 or later including its free Community Editons.
2. Fixing various glitches and heavy refactoring.
3. Include HD/FullHD support like already done by gondur.
4. Possibly replace DX with either SDL2/Vulkan/other to gain crossplatform support, but since the DX is maintain for latest Delphi versions - this has lower priority.

Also check out the gondur fork for changes, and the thread on SOAAmigos (in german), where Raptor/Rucksacksepp (http://soamigos.de/wbb5/forum/index.php?thread/4458-hd-und-fullhd-version-zu-siege-of-avalon-aus-dem-source-code-mit-delphi-4/&postID=91286#post91286) fixed building with Delphi 4 amoung other things.

To play the game your need additional files in the assets folder:
- soundlib.dll
- fmod.dll
- DFX_P5S.DLL
- DFX_P6S.DLL

all found in the original free playable 1. chapter/demo - http://soaos.sourceforge.net/FreePage.htm

---

### Status as of Mar 14th, 2019 ###

- Replaced 3 "corrupt/missing" assets

New branch (win32_d7onwards):

- Replaced and updated DX files - using files from unDelphiX (http://www.micrel.cz/Dx/)
- Converted source to compilable in Delphi 7, being fully playable.

### Status as of Mar 17th, 2019 ###

In win32_d7onwards branch:

- Compiles and runs in DX 10.2.3 - non-playable yet
- Character screen has glitches, but works
- Loading 90% - missing lightning/tiles

### Status as of Mar 20th, 2019 ###

- Stepped back. Now playable in Delphi 2007

...moving towards Delphi 10.3 Rio - in small steps :)
