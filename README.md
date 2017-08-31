<p align="center">
<img src="https://raw.githubusercontent.com/DOSP-Project/Desi_Goodness/n7x/DOSP-Logo.png" width="1000px" height="180px" alt="DOSP logo" > 
</p>


DOSP-OS (The Desi OS)
---------------

Getting Started
---------------
To get started with the DOSP-OS sources, you'll need to get familiar with [Git and Repo](https://source.android.com/source/using-repo). 

Initialize the Repositories 
---------------------------
```bash
    repo init -u https://github.com/DesiOS/Desi_Goodness.git -b nougat
```

Initialize the Repositories with reduced download size
------------------------------------------------------
```bash
    repo init --depth=1 -u https://github.com/DesiOS/Desi_Goodness.git -b nougat
```
Then to sync up:
---------------
```bash
    repo sync --force-sync --force-broken --no-clone-bundle -jxx (Ur Choice)
```

Finally to build:
-----------------
```bash
    . build/envsetup.sh
     lunch desi_<device>-userdebug
     mka desi
```
  
Credits
-------
* [**AOSP-JDC (Base)**](https://github.com/AOSP-JF-MM)
* [**LineageOS**](https://github.com/LineageOS)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**SlimRoms**](https://github.com/SlimRoms)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**Pure Nexus**](https://github.com/PureNexusProject)
* [**OmniROM**](https://github.com/omnirom/)


