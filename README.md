# Ultimate Soccer Manager 2020

This repo includes the game and tools such as:

| Tool | Description |
|---|---|
| USM Data Editor (USDMDE) | Edit Teams and Players |
| USM Explorer | Find Wonderkids in your game save |
| USM Tweaker | Change the starting Year and turn on cheats |
| USM 98-88 | The game, with 2019 data | 

More information on tools a datasets visit the [USM community](http://usm.dynamic-mess.com/downloads/tools/).

The USM 98-88 game, USM Data Editor and USM Explorer have to be run on Windows. USM Tweaker can be run on Mac as it is just a Java file, as you can just select the exe file.

The USM 98-88 EXE file has had its hashes edited according [this spreadsheet](https://docs.google.com/spreadsheets/d/17TogN3t7KEJG2iqTcW-Yw57upIHOR9e5NWLWhP6Dsq8/edit?fbclid=IwAR06JqrBO7tsmDdjwzfzbQGSjMY1l_-4p8SrMlgV5sCH8OSgP0IkvOCJCbA#gid=427331404). To edit hashes further install [HxD](https://mh-nexus.de/en/hxd/).

# Getting the damn game working on a Mac

## Virtual Machine

* Use a Windows XP image, not 95/98 - XP is the smallest image you can get that still lets you easily connect to the internet via the host
* Use the following image for VMWare: COMING SOON
* Using the following image for Parallels: COMING SOON

## Compatibility

* Download Repo, put on your desktop or something
* Boot up the XP image in VMWare or Parallels
* Make sure Desktop is a shared drive to your running Vmware / Parallels image in Vmware / Parallels seetings 
* In the repo, DxWnd EXE is included along with a config file for DxWnd. Open DxWnd.exe in XP and import the USM98-99.dxw file.
* Download and Install [Microsoft Windows Application Compatibility Toolkit](https://download.cnet.com/Microsoft-Windows-Application-Compatibility-Toolkit/3000-2352_4-10067306.html)
* Open Compatibility Administrator
* Inside Compatibility Administrator open USM98-99.sdb
* Inside Compatibility Administrator click Run and select USM98-99.exe

