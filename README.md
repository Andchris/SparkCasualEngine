# SparkCasualEngine
## THIS IS SPARK CASUAL GAME ENGINE 
I DO NOT OWN ANY OF THE ASSETS , EVERYTHING IS MADE BY ARTIFLEX MUNDI.DECOMPILED FROM THEIR GAMES

## CUB format 
All of the games made in this engine have the files encoded in a format named CUB , <ins>Data.cub</ins> and <ins>Game.cub</ins>.
To decode I used an BMS script I found online , it worked for me for an older game and a newer one

## Spark format
<ul>
  <li><b>.sparkeffect</b></li>
  <li>.sparkatlas</li>
  <li>.stex</li>
  <li>.cubemap</li>
  <li>.cubebin</li>
</ul>

cubemap and cubebin are related , spark are more for the data
cubemap and cubebin are related to CUB.

BMP's are used for <b>placeholders</b> , in HOG scenes , puzzles , or the inventory.

Cubebin is the lua code for the exe.

## Lua Implementation 
The actual game code is actually stored in cubebin files and the acutal executable is the engine itself.
Cubebin files are in theory just lua scripts but encrypted , yet they are still pretty readable , which helps a lot in decompiling the actual game.
