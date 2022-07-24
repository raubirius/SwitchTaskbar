# SwitchTaskbar

This is not my project. I only made an icon. | Toto nie je môj projekt. Ja som vyrobil len ikonu.

*Slovenský text je nižšie (for Slovak scroll/look down).* 

**Story:** On one computer I needed to toggle the autohide state of the taskbar very often. It was a problem that had been ignored for a long time… Until one day I set out to find a solution. Various tips and suggestions did not work or worked only one-sidedly, or they chose such a brutal approach that it was unacceptable. The remains of the quest are in the [@Trash.7z](https://github.com/raubirius/SwitchTaskbar/blob/main/%40Trash.7z) package.

Finally, the [solution](https://stackoverflow.com/a/31416792/2036423) posted by user [ooga](https://stackoverflow.com/users/3213868/ooga) in answer to the question [windows&nbsp;– How to auto-hide the taskbar from the command line&nbsp;– Stack Overflow](https://stackoverflow.com/questions/31416438/how-to-auto-hide-the-taskbar-from-the-command-line) worked.

I also adapted it to the Lazarus project solution (inside the [@Trash.7z](https://github.com/raubirius/SwitchTaskbar/blob/main/%40Trash.7z) package&nbsp;– it would still need to be switched from window to console mode), but since C produces a shorter .exe file, I stuck with the original solution. So much for a short story.

**Warning!** Windows Defender marks any .exe file created with the source codes of this project (Pascal or C) as malicious. This is because OS functions are used that are usually reserved for other purposes, but in reality this code is completely harmless.

## Slovenský text (Slovak description)… 

**Príbeh:** Na jednom počítači som potreboval veľmi často prepínať stavom skrývania panela úloh. Bol to dlhodobo ignorovaný problém… Až som sa jedného dňa vydal pátrať po riešení. Rôzne tipy a&nbsp;návrhy nefungovali alebo fungovali len jednostranne, prípadne volili taký brutálny prístup, že to bolo neakceptovateľné. Zvyšky pátrania sú v&nbsp;balíčku [@Trash.7z](https://github.com/raubirius/SwitchTaskbar/blob/main/%40Trash.7z).

Nakoniec fungovalo [riešenie,](https://stackoverflow.com/a/31416792/2036423) ktoré zverejnil používateľ [ooga](https://stackoverflow.com/users/3213868/ooga) v&nbsp;odpovedi na otázku [windows&nbsp;– How to auto-hide the taskbar from the command line&nbsp;– Stack Overflow.](https://stackoverflow.com/questions/31416438/how-to-auto-hide-the-taskbar-from-the-command-line)

Adaptoval som ho aj do riešenia projektu Lazarusa (vo vnútri balíčka [@Trash.7z](https://github.com/raubirius/SwitchTaskbar/blob/main/%40Trash.7z)&nbsp;– bolo by ho treba ešte preklopiť z&nbsp;oknoidného do konzolového režimu), ale keďže C produkuje kratší .exe súbor, zostal som pri pôvodnom riešení. Toľko ku krátkemu príbehu.

**Upozornenie!** Windows Defender označuje akýkoľvek .exe súbor vytvorený zdrojovými kódmi tohto projektu (Pascal alebo C) za škodlivý. Je to preto, lebo sú používané funkcie OS, ktoré sú obvykle rezervované na iné účely, ale v&nbsp;skutočnosti je tento kód úplne neškodný.

