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

The elements have been significantly balanced compared to the original game, 
which opens up new strategic possibilities. Also, your party members now have 
strengths and weaknesses against certain attributes, which must be considered 
when choosing the right strategy. Each attribute affects one another in certain 
ways, and you will be able to give greater damages by attacking with the 
attribute which the enemy is more vulnerable with. The effects differ according 
to the combination of attributes. The chart below indicates the effects of 
attacking with attributes and defending with certain party members.

| Attack With  | Avoid Attacking | Enemy   | Defend As      | Avoid Defending |
|-------------:|----------------:|:-------:|:---------------|:----------------|
| ![][R]![][S] | ![][B]![][Y]    | ![][Gr] | ![][Vy]![][Ai] | ![][Fi]![][Gi]  |
| ![][P]![][B] | ![][G]![][R]    | ![][Re] | ![][Dr]![][En] | ![][Vy]![][Gi]  |
| ![][R]![][Y] | ![][P]![][B]    | ![][Pu] | ![][Vy]![][Gi] | ![][Ai]![][En]  |
| ![][G]![][P] | ![][R]![][S]    | ![][Bl] | ![][Fi]![][Gi] | ![][Dr]![][En]  |
| ![][G]![][S] | ![][P]![][Y]    | ![][Ye] | ![][Fi]![][En] | ![][Ai]![][Dr]  |
| ![][B]![][Y] | ![][G]![][S]    | ![][Si] | ![][Ai]![][Dr] | ![][Vy]![][Fi]  |

| Attack With  | Avoid Attacking | Enemy   | Defend As      | Avoid Defending |
|:------------:|:---------------:|:-------:|:--------------:|:---------------:|
| ![][R]![][S] | ![][B]![][Y]    | ![][Gr] | ![][Vy]![][Ai] | ![][Fi]![][Gi]  |
| ![][P]![][B] | ![][G]![][R]    | ![][Re] | ![][Dr]![][En] | ![][Vy]![][Gi]  |
| ![][R]![][Y] | ![][P]![][B]    | ![][Pu] | ![][Vy]![][Gi] | ![][Ai]![][En]  |
| ![][G]![][P] | ![][R]![][S]    | ![][Bl] | ![][Fi]![][Gi] | ![][Dr]![][En]  |
| ![][G]![][S] | ![][P]![][Y]    | ![][Ye] | ![][Fi]![][En] | ![][Ai]![][Dr]  |
| ![][B]![][Y] | ![][G]![][S]    | ![][Si] | ![][Ai]![][Dr] | ![][Vy]![][Fi]  |

| Enemy   | Attack With  | Avoid Attacking | Defend As      | Avoid Defending |
|:-------:|:------------:|:---------------:|:--------------:|:---------------:|
| ![][Gr] | ![][R]![][S] | ![][B]![][Y]    | ![][Vy]![][Ai] | ![][Fi]![][Gi]  |
| ![][Re] | ![][P]![][B] | ![][G]![][R]    | ![][Dr]![][En] | ![][Vy]![][Gi]  |
| ![][Pu] | ![][R]![][Y] | ![][P]![][B]    | ![][Vy]![][Gi] | ![][Ai]![][En]  |
| ![][Bl] | ![][G]![][P] | ![][R]![][S]    | ![][Fi]![][Gi] | ![][Dr]![][En]  |
| ![][Ye] | ![][G]![][S] | ![][P]![][Y]    | ![][Fi]![][En] | ![][Ai]![][Dr]  |
| ![][Si] | ![][B]![][Y] | ![][G]![][S]    | ![][Ai]![][Dr] | ![][Vy]![][Fi]  |

[G]: doc/greenstone.png "Green"
[R]: doc/redstone.png "Red"
[P]: doc/purplestone.png "Purple"
[B]: doc/bluestone.png "Blue"
[Y]: doc/yellowstone.png "Yellow"
[S]: doc/silverstone.png "Silver"
[Vy]: doc/vyse.png "Vyse (Blue)"
[Ai]: doc/aika.png "Aika (Yellow)"
[Fi]: doc/fina.png "Fina (Silver)"
[Dr]: doc/drachma.png "Drachma (Green)"
[En]: doc/enrique.png "Enrique (Purple)"
[Gi]: doc/gilder.png "Gilder (Red)"
[Gr]: doc/greencrest.png "Green"
[Re]: doc/redcrest.png "Red"
[Pu]: doc/purplecrest.png "Purple"
[Bl]: doc/bluecrest.png "Blue"
[Ye]: doc/yellowcrest.png "Yellow"
[Si]: doc/silvercrest.png "Silver"

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
