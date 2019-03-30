## Microsoft Windows 10 Media Creation Tool Helper

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40CHEF-KOCH)](https://twitter.com/FZeven)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/CHEF-KOCH)
[![Discord](https://discordapp.com/api/guilds/204394292519632897/widget.png)](https://discord.me/NVinside)

Inofficial batch helper to get and install latest Windows .esd/.iso. The project is original created under the GNU General Public License v3.0 2017 by CHEF-KOCH.


### HowTo
* Rename file original products_20xxxxx.cab to products.cab.
* Put file products.cab in the same folder where the file MediaCreationTool.exe
* And run MediaCreationTool.exe /selfhost (or via ps: .\MediaCreationTool.exe /selfhost)
* Save boot ISO..
* You can tweak the parameters as needed: MediaCreationTool.exe /Selfhost /Eula Accept /Retail /MediaLangCode en-us /MediaArch x86 /MediaEdition Enterprise
* Done.

The batch-method (as shown in the screenshot) is now optional.

![MCTS](https://raw.githubusercontent.com/CHEF-KOCH/Microsoft-Windows-10-Media-Creation-Tool-Helper/master/.github/Screenshot.png)


```bash
//Replace 1809 with the version your want (official versions which needs the batch file)
https://software-download.microsoft.com/download/pr/MediaCreationTool1809.exe

Mirror:
https://download.microsoft.com/download/9/4/E/94E04254-741B-4316-B1DF-8CAEDF2DF16C/Windows10Upgrade9252.exe
```



### Official Media Creation Tool

* https://go.microsoft.com/fwlink/?LinkId=691209
* https://software-download.microsoft.com/download/pr/MediaCreationTool1803.exe
* https://download.microsoft.com/download/C/8/E/C8E7013A-F5D5-4F9F-A94E-3B4F333F2930/Windows10Upgrade9252.exe
* https://download.microsoft.com/download/3/8/9/38926395-6FB1-4487-83DF-4241D2EA79F7/products_20171005.cab
* https://download.microsoft.com/download/F/1/2/F12AE2F0-B1CC-4A83-9529-C3D43F171C62/Products_RS4_04_20_2018.xml
