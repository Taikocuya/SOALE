![Skies of Arcadia Legends Encore](doc/logomlt.png)

# Skies of Arcadia Legends Encore

Skies of Arcadia Legends Encore also known as Eternal Arcadia Legends Encore 
(エターナルアルカディアレジェンドＥｎｃｏｒｅ) is a rebalancing and difficulty hack.

## Prerequisites

* GCM or ISO image of Skies of Arcadia Legends or Eternal Arcadia Legends
  (エターナルアルカディアレジェンド)
* [GCRebuilder](http://www.romhacking.net/utilities/619/)

## Download

* Latest official release on the
  [SourceForge project website](https://sf.net/projects/soale)
* Current development version from the
  [GitHub repository](https://github.com/Taikocuya/SOALE)

## Installation

1. Obtain a GCM or an ISO of Skies of Arcadia Legends or Eternal Arcadia 
   Legends (エターナルアルカディアレジェンド).
2. Download [GCRebuilder](http://www.romhacking.net/utilities/619/) from
   ROMhacking.net.
3. Run GCRebuilder, select `Image > Open` and choose your GCM or ISO image.
4. Note the content of the `Region` attribute for later, which may be 
   `EUR/PAL`, `JAP/NTSC` or `USA/NTSC`.
   ![GCRebuilder](doc/install4.png)
5. Right-click on `root` in the tree structure, select `Export` and extract 
   the files to any directory wherever you want. A new folder called `root` 
   with all game contents will be created. After the export is finished, 
   choose `Image > Close`.
   ![GCRebuilder](doc/install5.png)
6. Open the correct `dist/gc-*-final/gameroot` directory which match with 
   your `Region` attribute from step 4 and copy all contents of that folder.
    * `dist/gc-eu-final/gameroot` for `EUR/PAL` region 
    * `dist/gc-jp-final/gameroot` for `JAP/NTSC` region 
    * `dist/gc-us-final/gameroot` for `USA/NTSC` region 
7. Paste all contents into your extracted `root` folder from step 5 and 
   replace the files.
   ![File Explorer](doc/install7.png)
8. In GCRebuilder, select `Root > Open` and choose your modified `root`
   folder from step 7. If you have done everything right, you are able to 
   read `Encore` in the `Name` and `Banner` attributes.
   ![GCRebuilder](doc/install8.png)
9. Select `Root > Save`, save the file wherever you want and run 
   `Root > Rebuild`. GCRebuilder will compile a new working ISO image that you 
   can use in Dolphin Emulator, Nintendont or any other Gamecube emulation 
   software.

## Element Efficiency

| Vulnerable To | Element | Strong Against | Weak Against   |
|--------------:|:-------:|:---------------|:---------------|
|  ![][G]![][S] | ![][GC] | ![][B]![][Y]   | [[R]] ![][S]   |
|  ![][P]![][B] | ![][RC] | ![][G]![][P]   |    |
|  ![][R]![][Y] | ![][PC] | ![][R]![][B]   |    |
|  ![][G]![][P] | ![][BC] | ![][R]![][S]   |    |
|  ![][G]![][S] | ![][YC] | ![][P]![][S]   |    |
|  ![][B]![][Y] | ![][SC] | ![][G]![][Y]   |    |

[[doc/greenstone.png]]

[G]: doc/greenstone.png "Green"
[R]: doc/redstone.png "Red"
[P]: doc/purplestone.png "Purple"
[B]: doc/bluestone.png "Blue"
[Y]: doc/yellowstone.png "Yellow"
[S]: doc/silverstone.png "Silver"
[GC]: doc/greencrest.png "Green"
[RC]: doc/redcrest.png "Red"
[PC]: doc/purplecrest.png "Purple"
[BC]: doc/bluecrest.png "Blue"
[YC]: doc/yellowcrest.png "Yellow"
[SC]: doc/silvercrest.png ""Silver"

## Resources

![Title](doc/title.png)
![Antonio](doc/antonio.png)
![Recumen](doc/recumen.png)
![Rik'talish](doc/riktalish.png)

## Acknowledgments

See [CREDITS.md](CREDITS.md) for a full list of the awesome people, groups and 
software that made this project possible.

## License

Copyright (C) 2022 Marcel Renner. Skies of Arcadia Legends Encore is 
licensed under the zlib license. See [LICENSE.md](LICENSE.md) for the full 
license text.
