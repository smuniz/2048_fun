# 2048 Fun

Super simple 2048 game solver using Python and some simple code (based on Python
implementation called [term2048](https://github.com/bfontaine/term2048/))

## About the code

<p>Basically all the movements in the next couple of rounds are calculated (yes,
all of them, tons of resources but doable) and the one with more score will be kept.
</p>

<p>The usage of PyPy is recommended as the performance will drastically improve.
</p>

<p>Lots of improvements could be done but this solution just took one day
to be implemented & tested. The code works ok and solves the game in minutes so I'm satisfied :-)
</p>

## Usage

All the interesting code is located in ai_tester.py and the file itself runs the
solving code as shown next:

> cd term2048/term2048
>
> python ./ai_tester.py

