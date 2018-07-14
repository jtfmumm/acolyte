\[If you're looking for the Pony roguelike, go to [novitiate](https://github.com/jtfmumm/novitiate).\]

# Acolyte

A graphical procedurally generated RPG inspired by Rogue and written in Rust.

This game is still in its early stages, but it is a complete game with
increasing difficulty and new elements as you move deeper into the dungeon.
Because everything is procedurally generated, it's a different game
every time you play.

* [Acolyte Instructions](#acolyte-instructions)
* [Installation](#installation)
* [Reporting Bugs](#reporting-bugs)

## Acolyte Instructions

The object of the game is to find the Staff of Eternity.

### Commands

NORMAL MODE (moving around map):  
  \<arrows\> - movement / attack  
  . - wait (turn passes without action)      
  a - F(A)ST MODE  
  c - (c)lose adacent door                   
  e - (e)nter staircase, town, etc.          
  f - (f)ire a missile (ranged weapon)       
  i - (I)NVENTORY MODE  
  m - view (m)ap  
  q - (q)uit  
  r - (r)estart game  
  t - (t)ake item on tile  
  x - swap last weapon equipped  
  \<enter\> - inspect tile you're on  
  \<mouse\> - Click on a tile to view it.  
    
FAST MODE:  
  (fast mode exits when you are next to something interesting)  
  \<arrows\> - rapid movement  
  . - rapid turn passing  
  \<any other key\> - return to NORMAL MODE  
    
INVENTORY MODE:  
  \<arrows\> - move through items  
  \<enter\> - equip/drink/use  
  d - (d)rop item  
  l - (l)ook at item  
  x - swap last weapon equipped  
  i/\<esc\> - return to NORMAL MODE  

## Installation

Acolyte is available on OSX, Windows, and Linux. 

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

If you don't want to run it through the terminal, right-click `acolyte` and click Open to start the game 
(double clicking will probably lead to a window saying you can't run the application). 

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
