---------------------------------------------------------------------------------------
 Komodo OS Rom (Android Pie) Source
 ==============

![SourceForge](https://img.shields.io/sourceforge/dm/komodos-rom.svg?color=red&label=Komodo%20OS%20Downloads&style=popout-square&labelColor=121217&logo=sourceforge)

To get started with manifest/KomodOS, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/KomodOS-Rom/platform_manifest.git -b pie

```

Then to sync up:

```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

---------------------------------------------------------------------------------------
 Compilation of  KomodOS ROM:
 ==================

From root directory of project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch komodo_$device-userdebug
$ mka bacon komodo
```


---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**DotOS**](https://github.com/DotOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**CypherOS**](https://github.com/CypherOS)
 * [**Xtended**](https://github.com/Xtended-Pie)
 * [**LeanOS**](https://github.com/LeanOS-Project)
 * [**BeastROMs**](https://github.com/BeastRoms)

---------------------------------------------------------------------------------------

