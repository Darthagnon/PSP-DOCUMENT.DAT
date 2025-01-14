# PSP-DOCUMENT.DAT
A collection of Sony PSP manual files

## Why
[isage's fork of Adrenaline](https://github.com/isage/Adrenaline/) added support in v7.1.5 for reading PSP manuals in a general way - they can now be placed alongside ISOs and read as the ISO's manual. Previously, PSP manual support was reserved for official EBOOT games only. 

I thought it would be useful for there to be a general public source of PSP manuals in the correct format (`DOCUMENT.DAT`) to save on redownloading all games.

## Usage (PS Vita)
1. Install at least v7.1.5 of isage's fork of Adrenaline on your PS Vita. 
	- **Please note that many Vita homebrews have compatibility issues with it, e.g. Adrenaline Bubble Manager, Hexflow launcher forks (see [isage's Adrenaline, Issue #7](https://github.com/isage/Adrenaline/issues/7))** 
2. Copy over your game ISO (uncertain if CSO etc. are yet supported)
3. Copy over the manual for the game to the same folder as the ISO, and rename it to the same filename. e.g. if your game is called `MyLegallyObtainedGame[xXxCONSPIRACYxXx].iso`, rename your manual to ` MyLegallyObtainedGame[xXxCONSPIRACYxXx].DAT`

## Please help
I will upload manuals for PSP games I play as I get them. I cannot build this library by myself, as I barely have time for videogames any more. Please feel free to contribute your manuals ❤

Please note that, to keep repo size down, version history is not kept. Notable changes are in [CHANGELOG.md](CHANGELOG.md). All updates will be made via: 

```
git add --all
git commit -m "PSP-DOCUMENT.DAT collection update YYYY-MM-DD" --amend
git push origin --force
```

If you fork this repository and wish to update your fork, see https://stackoverflow.com/questions/9646167/clean-up-a-fork-and-restart-it-from-the-upstream. This approach is based off other binary-heavy Git projects like [PythonWin7](https://github.com/adang1345/PythonWin7).

Manuals are sorted by region and are named according to:
`Game_Name_DEMO_ULES01213_DOCUMENT.DAT`
e.g.
`Crystal_Mines_DEMO_NPEH90047_DOCUMENT.DAT`

Demos are indicated by `DEMO`, PS1 Classics are indicated by `PS1`, Minis are indicated by `MINIS`. Punctuation invalid for file names is omitted from game titles. Japanese characters for JP-exclusive games must be romanised or translated so that the file names are searchable.

## See also
- [AdrenalineDocs](https://sites.google.com/view/adrenalinedocs/), if you'd prefer to read decrypted PSP/PS1 game manuals on your Vita in the style of Vita manuals from the game bubble.
- [PSP DocmakerGUI Remake](https://www.pspx.ru/forum/showthread.php?t=115223) (2024) is a PC program for making your own PSP manuals in `DOCUMENT.DAT` format
- [PSP instruction manual PDF archive by Renascene](https://archive.org/details/PSP-instruction-manuals-and-document-dat/101-in-1%20Megamix%20NPEH00068/) on Archive.org. Despite the repo name, it does not include `DOCUMENT.DAT` as far as I can tell.
- [Another PSP instruction manual PDF archive](https://archive.org/details/SonyPSPManuals/3rd%20Birthday%2C%20The%20%28USA%29/) on Archive.org
