# DarkCloud-Toolkit

![image1](https://user-images.githubusercontent.com/2998314/199367562-37bade17-42bb-4641-a6ec-0388942acc89.png)

-----------------------------------------

![](images/image1.png)

Toolkit v1.00

Assembled by Dayuppy - 05.15.2020

# Toolkit Download: 

[https://github.com/Gundorada-Workshop/DarkCloud-Toolkit/releases/download/Releases/DarkCloud_Toolkit.zip](https://github.com/Gundorada-Workshop/DarkCloud-Toolkit/releases/download/Releases/DarkCloud_Toolkit.zip)

Overview
========

This document aims to cover the tools and resources available for modding Dark Cloud as well as provide manual techniques for which no tool is yet available.

Goals
=====

1.  Consolidate all the information regarding modifying Dark Cloud into one place.
2.  Include a copy of all known publicly available tools available for modding Dark Cloud into one kit.

Milestones - TODO
=================

1.  Custom tools for repacking
    --------------------------
    

Create tools for repacking files without patching them in by manual hex editing.

2.  Easy Patch Creator
    ------------------
    

Make a utility to patch an ISO for distributing mods without the end user needing the entire toolkit to rebuild the ISO.

Table of Contents
=================

[Overview](#h.au51mny0sx6)        [0](#h.au51mny0sx6)

[Goals](#h.3at9u9s4e0vp)        [0](#h.3at9u9s4e0vp)

[Milestones - TODO](#h.yyrhu7ml5bea)        [0](#h.yyrhu7ml5bea)

[Custom tools for repacking](#h.xl19yzu8vrq9)        [0](#h.xl19yzu8vrq9)

[Easy Patch Creator](#h.p2nityf5kx5q)        [0](#h.p2nityf5kx5q)

[Table of Contents](#h.q324xisygqsh)        [1](#h.q324xisygqsh)

[Included Tools:](#h.8zg5t1w0ps7v)        [2](#h.8zg5t1w0ps7v)

[Initial Setup](#h.50lrdsd3wus1)        [3](#h.50lrdsd3wus1)

[Modifying the Files](#h.9ko42nxz1w4u)        [4](#h.9ko42nxz1w4u)

[Editing the .TM2s](#h.37n2lplafjjv)        [5](#h.37n2lplafjjv)

[File Formats](#h.jcbh1bv3srol)        [6](#h.jcbh1bv3srol)

[Dark Cloud Communities](#h.6b11zyhl4x5p)        [7](#h.6b11zyhl4x5p)

* * *

Included Tools:
===============

[7Zip](https://www.google.com/url?q=https://www.7-zip.org/&sa=D&source=editors&ust=1667352831095052&usg=AOvVaw1l0_uQneASij-orIDPi9Ku)

BATCH Scripts - Dayuppy

[dcmds](https://www.google.com/url?q=https://gitlab.com/panzer_maya/mds/snippets/1773438&sa=D&source=editors&ust=1667352831095539&usg=AOvVaw0E3B07ckZNZrruv4AymXn-) - [悠里マヤ (Yuri Maya)](https://www.google.com/url?q=https://gitlab.com/panzer_maya&sa=D&source=editors&ust=1667352831095711&usg=AOvVaw1TqhOEcNpVcphuK6544a16)

[Deswizzle](https://www.google.com/url?q=https://www.reddit.com/r/DarkCloud/comments/9ikdiq/found_this_in_dark_cloud_2s_texture_files_look/ecj65vt/&sa=D&source=editors&ust=1667352831095980&usg=AOvVaw23NluJuJOhu68xIEWclk8d) - Kojin

[Generic Header Creator](https://www.google.com/url?q=https://sourceforge.net/p/genericheader/code/HEAD/tree/Generic%2520Header%2520Creator%25204/bin/Release/&sa=D&source=editors&ust=1667352831096255&usg=AOvVaw2xdxNpjUBwJUZCoW88WXhx)

[HxD](https://www.google.com/url?q=https://mh-nexus.de/en/hxd/&sa=D&source=editors&ust=1667352831096476&usg=AOvVaw0QRE-uyzahMPWiHdInFfef)

[ImgBurn](https://www.google.com/url?q=https://www.imgburn.com/&sa=D&source=editors&ust=1667352831096666&usg=AOvVaw0YujLH3ZEZZxt1UhBexCsc)

[Imextract](https://www.google.com/url?q=https://www.reddit.com/r/DarkCloud/comments/9ikdiq/found_this_in_dark_cloud_2s_texture_files_look/ecj65vt/&sa=D&source=editors&ust=1667352831096894&usg=AOvVaw13bfhcmKNRh9wCxfLGFjJl) - Kojin

[LightCloud](https://www.google.com/url?q=https://github.com/Xeeynamo/DarkCloud&sa=D&source=editors&ust=1667352831097142&usg=AOvVaw2h6_773-Px9yNuFzXbFJHU) - Xeeynamo

[MES\_Decrypt](https://www.google.com/url?q=https://cdn.discordapp.com/attachments/532012137590292490/708285790060544010/MES_Decrypt.zip&sa=D&source=editors&ust=1667352831097401&usg=AOvVaw3dzVhLoTzjDTkJYBq15jqb) - MrManifold / Dayuppy

[Noesis](https://www.google.com/url?q=http://www.richwhitehouse.com/index.php?content%3Dinc_projects.php&sa=D&source=editors&ust=1667352831097715&usg=AOvVaw1j-GoIuIblL3VrEKUIbHqg)

[Pakextract](https://www.google.com/url?q=https://www.reddit.com/r/DarkCloud/comments/9ikdiq/found_this_in_dark_cloud_2s_texture_files_look/ecj65vt/&sa=D&source=editors&ust=1667352831098033&usg=AOvVaw3UHdzWvjtwLgw4AFOe49_y) -  Kojin

[PCSX2 1.6.0 RC](https://www.google.com/url?q=https://github.com/PCSX2/pcsx2&sa=D&source=editors&ust=1667352831098263&usg=AOvVaw04HWg7iFCEje8mOm7te0vW)

[PSF2Kit](https://www.google.com/url?q=https://web.archive.org/web/20110907040038/http://www.neillcorlett.com/psf/utilities.html&sa=D&source=editors&ust=1667352831098484&usg=AOvVaw1M_BfgnzKCG82MkSYHx2S1)

[PSound](https://www.google.com/url?q=http://snailrush.online.fr/&sa=D&source=editors&ust=1667352831098686&usg=AOvVaw2kCApyPgxBLms2Ovka3F-i)

[QuickBMS](https://www.google.com/url?q=https://aluigi.altervista.org/quickbms.htm&sa=D&source=editors&ust=1667352831098879&usg=AOvVaw3xTl4UOmllC4i2RD3mZW6D)

QuickBMS Scripts - Dayuppy, aluigi, others

[Rainbow](https://www.google.com/url?q=https://github.com/marco-calautti/Rainbow&sa=D&source=editors&ust=1667352831099125&usg=AOvVaw2dRUG9CxBTYwKOceTIwmd3)

[SageThumbs](https://www.google.com/url?q=https://sourceforge.net/projects/sagethumbs/&sa=D&source=editors&ust=1667352831099330&usg=AOvVaw1JXdlwezJ7aD4d3FTT2iW0)

[TextER](https://www.google.com/url?q=http://www.romhacking.net/utilities/659&sa=D&source=editors&ust=1667352831099536&usg=AOvVaw00wY8hqJatM1LT91SLWL0Z)

[TM2 Photoshop Plug-in](https://www.google.com/url?q=https://www.ps2-home.com/forum/viewtopic.php?t%3D638&sa=D&source=editors&ust=1667352831099752&usg=AOvVaw3nPsF9E3cru1fmKx1HFU2c)

[Video GameSound Converter](https://www.google.com/url?q=https://github.com/puggsoy/VGSC&sa=D&source=editors&ust=1667352831099951&usg=AOvVaw2WcJkVdUVdTUHUkg5ZeROf)

[WhiteCloud](https://www.google.com/url?q=https://github.com/Xeeynamo/DarkCloud&sa=D&source=editors&ust=1667352831100146&usg=AOvVaw2nsfiLYGr10nApD3xQtn2w) \- Xeeynamo

[XMPlay](https://www.google.com/url?q=https://www.un4seen.com/&sa=D&source=editors&ust=1667352831100423&usg=AOvVaw38CG5p2T5Bj9BaRq5szG3S)

[XMPlay PSF2 Plug-in](https://www.google.com/url?q=https://support.xmplay.com/files_view.php?file_id%3D507&sa=D&source=editors&ust=1667352831100659&usg=AOvVaw2RRRwuOfe5KhCZfMpxery3)

[XNView](https://www.google.com/url?q=https://www.xnview.com/en/&sa=D&source=editors&ust=1667352831100900&usg=AOvVaw3rHXPExVXvrWd9n2T8rdnT)

* * *

Initial Setup
=============

Create a new folder somewhere.

Extract the contents of DarkCloud\_Toolkit.zip into the root directory of the new folder.

Place your Dark Cloud ISO into the ISOS folder. Rename the ISO to “DarkCloud.iso”. Run UNPACK\_ORIG.BAT and enter y to create the new directory for the first time.

Place your PS2 BIOS dump into Tools\\PCSX2 1.6.0 RC\\bios .

Enter to close the window once extraction is completed.

Run the BUILD.BAT and then PLAY.BAT to verify that you are able to repack the files and launch the game.  

NOTE: PCSX2 may need to be launched at least once outside of PLAY.BAT in order to set the configs.

TODO: Make a video demonstrating initial setup.

* * *

Modifying the Files
===================

After running UNPACK\_ORIG.BAT for the first time, it will have created four new directories.  

When you modify the files within the extracted .chr, .img, .pac or .pak files etc., you will need to manually insert the binary data by hex editing before repacking until tools can be made to do this automatically.

* * *

Editing the .TM2s
=================

Open Tools\\rainbow\_win32\_bin\_1.2.1-3\\Rainbow.App.exe.

File > Open > DarkCloud\_MOD\_DAT\\img\_1

Choose MT01 - MT301.tm2 and open.

File > Export > Save

Navigate to DarkCloud\_MOD\_DAT\\img\_1 and open the .png copy of the file you just exported. You may then modify the file. Ensure that you do not enlarge the image or else it will fail to be injected back into the game's .DAT when we go to repack.

File > Import > .xml of the file you just modified.

File > Save as the original .tm2 name, overwriting the original.

Run the BUILD.BAT and then PLAY.BAT, check to see if the texture loaded successfully.

If it does not, copy the original .tm2 from DarkCloud\_ORIG\_DAT and place it back into your DarkCloud\_MOD\_DAT. Copy the DATA.DAT from DarkCloud\_ORIG into DarkCloud\_MOD. Run BUILD.BAT and PLAY.BAT again.

Go back and try a different image editor with the same process.

* * *

File Formats
============

.DAT - Game Archive

.HD2

.HED

.BIN

.11 - ELF Executable

.IMG - Image Archive

.EDT

.INI

.STB

.TXT

.CHR - Character Archive - MDS & TM2

.PAK

.PAC

.MDS - Model Format

.TM2 - Image Format

.MOT - Animation Data ?

.WGT

.BBP

.MES - Localization & Strings

.SCN - Scene Archive - MDS & TM2

.OLD

.SCR

.PIM

.MPK

.MPD

.SND - Sound Archive

.PK3

.IPK

.PKG

* * *

Dark Cloud Communities
======================

[https://www.reddit.com/r/DarkCloud/](https://www.google.com/url?q=https://www.reddit.com/r/DarkCloud/&sa=D&source=editors&ust=1667352831105027&usg=AOvVaw1CW11l6FPSe2G88O-8MPoV)

[https://discord.gg/PNXqAZ5](https://www.google.com/url?q=https://discord.gg/PNXqAZ5&sa=D&source=editors&ust=1667352831105302&usg=AOvVaw0ggQzEIZwZiXeGoPPIO9P6) - r/DarkCloud discord

[https://discord.gg/3QqYyEWjYD](https://www.google.com/url?q=https://discord.gg/3QqYyEWjYD&sa=D&source=editors&ust=1667352831105833&usg=AOvVaw2YN2b8OX9EQmOs0J3TB6ks) - DC1 Resource Server
