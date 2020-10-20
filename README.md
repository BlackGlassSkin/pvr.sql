# Kodi's Internet Protocol Television SQL Client Addon w/ Recording Support
IPTV Live TV and Radio PVR Client Addon for [Kodi] (http://kodi.tv)

## Build instructions

### Linux

### First step's 

# A. # cd ./Downloads  or any location and git clone kodi + pvr.sql
# B. change downloaded pvr.sql name to pvr.iptvsimple
# C. Example command for rename file name and compilation
# ↓ ↓ ↓ ↓

mv ./Downloads/pvr.sql ./Downloads/pvr.iptvsimple


git clone --branch Leia https://github.com/xbmc/xbmc.git
git clone https://github.com/BlackGlassSkin/pvr.sql.git
cd pvr.iptvsimple && mkdir build && cd build
cmake -DADDONS_TO_BUILD=pvr.iptvsimple -DADDON_SRC_PREFIX=../.. -DCMAKE_BUILD_TYPE=Debug -DCMAKE_INSTALL_PREFIX=../../xbmc/addons -DPACKAGE_ZIP=1 ../../xbmc/cmake/addons
make

### Windows

Coming Soon.

##### Useful links

* [Kodi's PVR User Support] (http://forum.kodi.tv/forumdisplay.php?fid=167)
* [Kodi's PVR Development Support] (http://forum.kodi.tv/forumdisplay.php?fid=136)
* [PVR SQL Discord Page] (https://discord.gg/n83a83V)
* [FFmpeg Binaries w/ Codecs, ARM] (https://johnvansickle.com/ffmpeg/)

##### Gonzalo Vega (gonzalo-hvega) modification

##### Features
1. Time Shifting Support
2. EPG Timers Support
3. Recordings Folder Integration
4. Resume Playback & Watched List
5. Records Management (Delete Recordings from Kodi Interface)
6. Multi-Recording
7. Client & Server

##### Requirements
1. FFMPEG Binary for System
2. Kodi 18.8

##### Tested with
1. Ubuntu 16.04 LTS ,18.04
2. Windows 10 (64-bit)
3. Windows 10 (32-bit)
4. LibreElec ARM (Raspberry Pi)
5. LibreElec x86
6. CoreELEC

##### Credits
Credit to the Following Authors/Projects who I Borrowed Some Ideas and/or Code:
1. Anton Fedchin, Official PVR IPTV Simple for Kodi
2. Radek Kubera, Branched Version of IPTV Simple with Recording (Basis of this Project)
3. DBViewer
4. SQLite
5. Lib_NetSockets by Pedro Vicente
