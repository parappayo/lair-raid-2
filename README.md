
# Lair Raid 2: Battle in the Deep Dark

Project for [Ludum Dare 29](http://www.ludumdare.com/compo/ludum-dare-29/), Theme: Under the Surface

## Acknowledgements

All art assets used under Creative Commons license terms.

* [Dungeon Tiles](http://opengameart.org/content/dungeon-tileset) by [Buch](http://blog-buch.rhcloud.com)
* Musical Score [1](https://soundcloud.com/stevenobrien/solemn-choral-piece-no-2-2010), [2](https://soundcloud.com/stevenobrien/epic-theme-no-4), [3](https://soundcloud.com/stevenobrien/epic-orchestral-piece), [4](https://soundcloud.com/stevenobrien/majestic-epic-orchestral-piece) by [Steven O'Brien](https://soundcloud.com/stevenobrien/)
* Font is [Comic Neue](http://comicneue.com/)
* [Ogmo Editor](http://www.ogmoeditor.com/) by Maddy Thorson used to create level data
* Licensed version of [TexturePacker](http://www.codeandweb.com/texturepacker) used to create texture atlas files
* [FlashDevelop](http://www.flashdevelop.org/) used as an IDE
* [Starling](http://gamua.com/starling/) library used for Flash graphics
* [WinLame](http://winlame.sourceforge.net/) was used to re-encode mp3s to save swf space
* [Wyvern-Tail](https://code.google.com/p/wyvern-tail/) is a Flash game library and framework by Jason Estey
* Tile Chopper (under tools dir) is a quick n dirty C# tool by Jason Estey

## How to Play

The UI is a bit obtuse, sorry about that.

Click a dwarf to begin moving or fighting. With a dwarf selected, click an adjacent opponent to attack, and/or move to a square adjacent to an opponent to charge. A dwarf can charge and attack in the same turn.

Use the spacebar to end your turn.

## How to Build

Install FlashDevelop 5, open the `game_project.as3proj` and click the play button. You may also need to install the Java runtime environment.

## Project Structure

* assets - sprites, fonts, etc.
* lib - dependencies: Starling, Feathers, Wyvern-Tail
* src - game source code
* tools - contains the Tile Chopper tool used to break up sprite sheets
