# Paul's HappyBird. A colorful game for the Atari 2600.

HeppyBird has been written in C using cc2600. 
It's a 16KB ROM (classical ATARI bankswitching scheme) that has been
tested on Harmony cart and PlusCart (but in PAL version only). 

HappyBird implements :

- 60Hz NTSC and a 50Hz PAL/secam versions

- Highscore save on SaveKey (high score reset by pulling the Settings switch for 5 seconds)

- Amateur and Pro modes

- Pause with the W/B switch 

- Reach 100, 200, 300, etc and some colorful animations will start

Technically, it's using an assymetric playfield scrolling with a big main sprite with 3 colors
on the same (using all available sprites + the ball).

# How to build it :

With cc2600 installed :

`cc2600 bird.c` to build the NTSC version

`cc2600 bird.c -DPAL` to build the PAL/SECAM version

# TODO

- [ ] implement PlusROM version for high score registering

- [ ] AtariVox sounds when I'll have received mine...
