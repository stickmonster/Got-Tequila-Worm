# CPPND: GOT TEQUILA WORM


(a spin-off Snake Game based on a starter repo for the Capstone project in the [Udacity C++ Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213) which in turn originates in [this](https://codereview.stackexchange.com/questions/212296/snake-game-in-c-with-sdl) excellent StackOverflow post and set of responses.)


It's called GOT TEQUILA WORM because you've GOT TO KILL A WORM.

Your worm loves Tequila. It is drinking itself into oblivion, dissolving into the drink it loves with every measure of the beautiful spirit. You have to help it do this. In your way will be other tequila worms who want to PARTY PARTY PARTY on your tequila. They get in the way, and are confusing (especially the drunker your worm gets).

With every drink of TEQUILA your worm gets shorter until, eventually, its body disintigrates into a blob of red blood, and you win.

Es Muerte!

Gracias!

Your score will be measured in Mexican seconds.


My major changes to Udacity's repo are:

1) Your worm shrivels as it drinks.
2) Your score is in seconds rather than length.
3) Other worm-bots arrive to get in the way.

There are no additional dependencies or libraries, and it builds just the same as the original. (See bottom of page.)

<img src="snake_game.gif"/>


## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  * Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source.
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.