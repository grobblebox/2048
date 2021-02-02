# 2048
Modified 2048 code at https://github.com/gabrielecirulli/2048

# 2049
### Motivation:
The original 2048 game is an interesting concept but in my opinion lacks depth of gameplay.

### Solution:
I believe I have addressed this by reducing RNG and increasing the variety of tiles spawned.

#### Specifics:
Tiles spawn every 3 turns (the location is still random), in the order 4, 16, -1.

#### Explanation:
These changes give the player more moves (3 moves of 4 swipes each gives a maximum of 4^3 choices in the best case) in between random events (versus only 1 move of 4 for 4^1).
The variety of tiles also creates more dynamic and interesting gameplay, and makes an attempt to discourage more degenerate/repetitive strategies. (ie: piling all the tiles into one corner)


## License
2048 is licensed under the [MIT license.](https://github.com/grobblebox/2048/blob/master/LICENSE.txt)
