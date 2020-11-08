\[If you're looking for the Pony roguelike, go to [novitiate](https://github.com/jtfmumm/novitiate).\]

# Acolyte

A graphical, procedurally generated roguelike RPG written in Rust.

This game is still in its early stages, but it is a complete game with
an overworld and dungeons of increasing difficulty as you progress. In order to discover new regions of the overworld, you must find Runes hidden in the dungeons. Because the game is procedurally generated, maps, locations, and dialogue will differ across games. 

* [Acolyte Instructions](#acolyte-instructions)
* [Installation](#installation)
* [Reporting Bugs](#reporting-bugs)

## Acolyte Instructions

The object of the game is to find the Staff of Eternity.

### Commands

The following commands are for the latest version. You can always
use the (h)elp command to check the list for your version.

```
NORMAL MODE (moving around map):
  <arrows> - movement / attack               a - F(A)ST MODE
  . - wait (turn passes without action)      i - (I)NVENTORY MODE
  c - (c)lose adacent door                   m - view (m)ap
  f - (f)ire a missile (ranged weapon)       q - (q)uit
  t - (t)ake item on tile                    r - (r)estart game
  x - swap last weapon equipped
  <enter> - inspect tile you're on
  <mouse> - Click on a tile to view it.
  
FAST MODE:
  (fast mode exits when you are next to something interesting)
  <arrows> - rapid movement
  . - rapid turn passing
  <any other key> - return to NORMAL MODE
  
INVENTORY MODE:
  <arrows> - move through items
  <enter> - equip/drink/use
  l - (l)ook at item
  d - (d)rop item
  x - swap last weapon equipped
  i/<esc> - return to NORMAL MODE  
```

## Installation

Acolyte is available on OSX, Windows, and Linux (Ubuntu Bionic binary for the time being). The versions with an overworld are only available for OSX currently.

Go to [https://github.com/jtfmumm/acolyte/releases](https://github.com/jtfmumm/acolyte/releases) and 
right click the latest release for your operating system. Click "Save Link As..." or something to that
effect (depends on browser) and save the zipped release somewhere on your computer. Extract the files
into a folder. 

### OSX
Open a Terminal, navigate to the folder where you put `acolyte`, and then run 
```
chmod +x acolyte
./acolyte
```

### Windows
Double-click `acolyte.exe` to start the game.

### Linux
You might be able to double-click `acolyte` to start the game.
Otherwise, open a Terminal, navigate to the folder where you put `acolyte`, and then run 
```
chmod +x acolyte
./acolyte
```

## Reporting Bugs

If you find a bug, please open an issue on this repository or e-mail me at jtfmumm{at}gmail.com. 
