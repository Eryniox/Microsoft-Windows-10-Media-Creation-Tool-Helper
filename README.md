## Microsoft Windows 10 Media Creation Tool Helper

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40CHEF-KOCH)](https://twitter.com/FZeven)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/CHEF-KOCH)
[![Discord](https://discordapp.com/api/guilds/204394292519632897/widget.png)](https://discord.me/NVinside)

Inofficial batch helper to get and install latest Windows .esd/.iso. The project is original created under the GNU General Public License v3.0 2017 by CHEF-KOCH.


### How-To
* Rename file original `products_20xxxxx.cab to products.cab`.
* Put file products.cab in the same folder where the file `MediaCreationTool.exe`
* And run `MediaCreationTool.exe /selfhost` (or via PowerShell: `.\MediaCreationTool.exe /selfhost`)
* Save boot ISO..
* You can tweak the parameters as needed: `MediaCreationTool.exe /Selfhost /Eula Accept /Retail /MediaLangCode en-us /MediaArch x86 /MediaEdition Enterprise`

The batch-method (as shown in the screenshot) is now optional.

![MCTS](https://raw.githubusercontent.com/CHEF-KOCH/Microsoft-Windows-10-Media-Creation-Tool-Helper/master/.github/Screenshot.png)


```bash
//latest Versions
//Replace 1809 with the version your want (official versions which needs the batch file)
https://software-download.microsoft.com/download/pr/MediaCreationTool1809.exe

Mirror:
https://download.microsoft.com/download/9/4/E/94E04254-741B-4316-B1DF-8CAEDF2DF16C/Windows10Upgrade9252.exe

Cab:
https://download.microsoft.com/download/8/E/8/8E852CBF-0BCC-454E-BDF5-60443569617C/products_20190314.cab
```


### Official Media Creation Tool (direct link)

* https://go.microsoft.com/fwlink/?LinkId=691209

### Unofficial Media Creation Tool Batch 

* [Universal MediaCreationTool.bat wrapper for all Windows 10 Redstone versions: 1607,1703,1709,1803,1809 with business (Enterprise) edition support](https://gist.github.com/AveYo/c74dc774a8fb81a332b5d65613187b15)


### Archive

```
1809
http://download.microsoft.com/download/B/6/E/B6E8893F-ECE0-42E5-A9ED-69A13DD0BA95/products_20181105.cab
http://software-download.microsoft.com/download/pr/MediaCreationTool1809.exe

1803
http://download.microsoft.com/download/5/C/B/5CB83D2A-2D7E-4129-9AFE-353F8459AA8B/products_20180705.cab
http://software-download.microsoft.com/download/pr/MediaCreationTool1803.exe
goto process

1709
http://download.microsoft.com/download/3/2/3/323D0F94-95D2-47DE-BB83-1D4AC3331190/products_20180105.cab
http://download.microsoft.com/download/A/B/E/ABEE70FE-7DE8-472A-8893-5F69947DE0B1/MediaCreationTool.exe


1703
http://download.microsoft.com/download/9/5/4/954415FD-D9D7-4E1F-8161-41B3A4E03D5E/products_20170317.cab
http://download.microsoft.com/download/1/C/4/1C41BC6B-F8AB-403B-B04E-C96ED6047488/MediaCreationTool.exe
http://download.microsoft.com/download/C/F/9/CF9862F9-3D22-4811-99E7-68CE3327DAE6/MediaCreationTool.exe


1607
http://wscont.apps.microsoft.com/winstore/OSUpgradeNotification/MediaCreationTool/prod/Products_20170116.cab
http://download.microsoft.com/download/C/F/9/CF9862F9-3D22-4811-99E7-68CE3327DAE6/MediaCreationTool.exe
```