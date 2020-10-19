# TI4 Map Generator

Generate fair maps for TI4.

## Features of this fork:

### Deployment changes:
* TODO: Containerize app for heroku deployment
* TODO: Allow saving, sharing, commenting on maps

### Additional features:
* TODO: Include all tech skips
* TODO: Spread out wormholes
  * No A and B wormholes adjacent to each other, at least 3 spaces between all wormholes
* TODO: Spread out planet traits
  * "Highest one-move cluster of planet traits"
  
### Frontend enhancements:
* click-to-copy
* Localstorage save settings
* Save previously generated maps

## Build Instructions:
apt-get install cmake clang libbfd 

pip install pillow

cmake ./

make
