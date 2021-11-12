<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-o/About.png" > 
</p>

--------------------------------------------------------------

 Dot OS 2.x - Oreo
 ==========

Downloads:
=========

[![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dd/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

[![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dw/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

[![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dm/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

[![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dt/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

 Credits
 =======
 * [**JDCTeam**](https://github.com/AOSP-JF-MM)
 * [**ABC**](https://github.com/ezio84?tab=repositories)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**Nitrogen-Project**](https://github.com/nitrogen-project)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)


-----------------------------------------------------------------------------
 
 Gerrit
 ==============
 Submit your All patches through our [Gerrit Code Review](http://gerrit.droidontime.com/).

 Getting Started
 ==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/lostsuryansh/manifest.git -b dot-o
```

Then to sync up:

```bash
    repo sync  -f --force-sync --no-clone-bundle
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -jX --force-sync --no-clone-bundle  ( X is the number of parallel download repo should do choose depending on your cpu )
```

----------------------------------
 
 Compilation of Dot OS
 ==================

From root directory of Project, perform following commands in terminal


```bash
	. build/envsetup.sh
   
        lunch dot_<codename>
   
	brunch <codename>
```


<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-n/dotlogo.png" > 
</p>

--------------------------------------------------------------------------------------------------------------------------

For maintainership & to submit patches refer [**HERE**](https://github.com/DotOS/android_vendor_dot/blob/dot-o/README.md)

--------------------------------------------------------------------------------------------------------------------------



