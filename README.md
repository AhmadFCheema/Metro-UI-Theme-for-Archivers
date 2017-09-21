# Metro-UI-Theme-for-Archivers

This theme was made to mirror the [WinRAR Metro UI Theme by Dubaku](https://dubaku.deviantart.com/art/WinRAR-Metro-UI-Theme-by-Dubaku-313192927) for other archive applications ([7-Zip](http://www.7-zip.org/), [PeaZip](http://www.peazip.org/), [Zipware](https://www.zipware.org/), [Bandizip](https://www.bandisoft.com/bandizip/)).

<p align="center">
<img src="https://user-images.githubusercontent.com/20906143/30675733-90643a44-9e9b-11e7-9616-c35e8f400f8d.png" alt="Metro-UI-Theme, Filetypes icons" title="Metro-UI-Theme-for-Archivers, Filetype icons" width="400">
</p>

## Installation

### 7-Zip
* Download and extract [7-Zip Theme Manager](http://www.7ztm.de/) [2.1.1](http://www.7ztm.de/download.php?cat=00_German&file=7zTM_2.1.1_hotfix.7z).
* Copy the `filetype` and `toolbar` folders from this project and paste them in the directory containing `7zTM.exe`.
* Run `7zTM.exe` > select `Metro UI` from both *Toolbar Themes* and *Filetype Themes* menus > Click on *Activate theme*.
* For changing toolbar icons size in 7-Zip, run *7-Zip* > *View* > *Toolbars* > *Large Buttons*.

![Metro-UI-Theme, 7-Zip toolbar](toolbar/Metro%20UI/preview.jpg?raw=true "Metro-UI-Theme-for-Archivers, 7-Zip toolbar")

### PeaZip
* Replace the default PeaZip filetype icons present in `C:\Program Files\PeaZip\res\icons` by the Metro UI theme icons from `filtype (PeaZip-special)` folder.

### Zipware
* Replace the default Zipware filetype icons present in `C:\Program Files (x86)\Zipware\Resources\Images` (OR `C:\Program Files\Zipware\Resources\Images` for 32-bit Windows) by the Metro UI theme icons from `filetype/Metro UI` and `filtype (Zipware-special)` folders.
* Run *Zipware* > *Options* > *Extension Association* > *Apply*

### Bandizip
* Compress folder *filetype/Metro UI* to a format recognised by Bandizip (e.g. *.Zip*).
* Change the newly created archive's extension to `.iconpack`.
* Double-click on this `.iconpack` file.

## Testing
Tested to be working on, 64-bit Microsoft Windows10 Version 1607 (OS Build [14393.1593](https://support.microsoft.com/en-us/help/4034658/windows-10-update-kb4034658)) on applications,
* 7-Zip 16.04 through 7-Zip Theme Manager 2.1.1
* PeaZip release 6.4.1 - Win64 Build
* Zipware 1.5.0.0 (Build 2017-06-17)
* Bandizip 6.09 (Build# 24540, 2017/09/06, x64)

## Development

Development work on this theme is detailed at [Metro UI Theme for Archivers (Dev notes)](https://github.com/AhmadFCheema/Metro-UI-Theme-for-Archivers/wiki/Metro-UI-Theme-for-Archivers-(Dev-notes)).

## License

To the best of my understanding, this collection is, at the very least, **free for personal use** (subject to the additional legally unbinding request by the compiler to [Criticise, not insult](https://islamwiki.org/wiki/islamWiki:Criticise_not_insult)).
* The theme is inspired from the *[WinRAR Metro UI Theme by Dubaku](https://dubaku.deviantart.com/art/WinRAR-Metro-UI-Theme-by-Dubaku-313192927)*. The theme creator claims the metro icons are taken from [zainadeel's Metro2 for Superbar](https://zainadeel.deviantart.com/art/Metro2-for-Superbar-294707841) but I was unable to find them present there. In contrast, identical or similar icons *were* found in [Metro UI Icon Set by dAKirby309](https://dakirby309.deviantart.com/art/Metro-UI-Icon-Set-725-Icons-280724102) ([CC BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/)).
* Additionally, the following free icons were modified or used as is,
	* Icon *[appbar.page.copy.svg](https://github.com/Templarian/WindowsIcons/blob/master/WindowsPhone/svg/appbar.page.copy.svg)* - [Licensed](https://github.com/Templarian/WindowsIcons/#windows-icons) under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
	* Icon *[folder-move](https://github.com/Templarian/MaterialDesign/blob/master/icons/svg/folder-move.svg)*, claimed to be [from Google](https://materialdesignicons.com/icon/folder-move) - [Licensed](https://github.com/Templarian/MaterialDesign#license) under [Apache License 2.0](https://github.com/Templarian/MaterialDesign#license)
	* [Icons](https://icomoon.io/#preview-free) *[arrow-right](https://github.com/Keyamoon/IcoMoon-Free/blob/master/SVG/309-arrow-right.svg)*, *[box-remove](https://github.com/Keyamoon/IcoMoon-Free/blob/master/SVG/096-box-remove.svg)*, *[copy](https://github.com/Keyamoon/IcoMoon-Free/blob/master/SVG/045-copy.svg)* - [Licensed](https://github.com/Keyamoon/IcoMoon-Free/blob/master/License.txt) under [GPL](http://www.gnu.org/licenses/gpl.html) / [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
	* Icon *[Live, mail icon](https://www.iconfinder.com/icons/98092/live_mail_icon)* and *[Programs alt](https://dakirby309.deviantart.com/art/Metro-UI-Icon-Set-725-Icons-280724102)* -  Licensed under CC BY-NC 3.0
	* Icon *[module, kcmdf icon](https://www.shareicon.net/module-kcmdf-319675)* - Licensed under [GNU GPL](https://www.gnu.org/licenses/licenses.en.html#GPL)
	* Icon *[iso](http://findicons.com/icon/85430/iso)* - Licensed under "Creative Commons Attribution (BY)"
	* Icon *[Document-save](https://commons.wikimedia.org/wiki/File:Document-save.svg)* - Public domain
* Wallpaper [Spectral Oils](https://www.flickr.com/photos/x1brett/7163154415/in/photostream/), used as background for *toolbar/preview.jpg*  - Licensed under [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/)

In the event an individual becomes aware of any copyright infringement, open an issue on the project, and if possible, the problematic icon will be replaced by a free alternative.
