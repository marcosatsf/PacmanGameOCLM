![](https://github.com/marcosatsf/PacmanGameOCLM/blob/master/imgRepo/bannerPacman.png)
> Written in Assembly x8086


![](https://github.com/marcosatsf/PacmanGameOCLM/blob/master/imgRepo/maps.gif)
> 3 different maps to play!


![](https://github.com/marcosatsf/PacmanGameOCLM/blob/master/imgRepo/ranking.png)
> Includes a ranking system for each map!

## Requirements:
- [x] TASM
- [x] TLINK
- [ ] `DOSBox` : <https://www.dosbox.com/>

## Steps for the fun (Download this repository and decompile it):
1. Install DOSBox (if it's not already) and open it;
2. Mount a directory (remember to mount it where you decompiled this repository), e.g.:
   + `MOUNT C C:\users\maxmitnet\playpac`;
3. Open it by writing the next command: 
   + `C:`;
4. Compile using one of the 2 next methods:
+ Smart method (this method runs the game automatically):
   + `c PACMAN`
+ Slave method:
   + `TASM PACMAN.ASM`
   + `TLINK PACMAN.OBJ`
5. Run it by writing `PACMAN`;
6. Have fun!

## Controls:

|   Control    |     Function    |
|------------- | ----------------|
|      W       |  Up movement    |
|      S       |  Down movement  |
|      A       |  Left movement  |
|      D       |  Right movement |
|     ESC      |  Pause / Quit   |
