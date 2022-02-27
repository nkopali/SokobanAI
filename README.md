# SokobanAI
This project is about creating an agent which can play the game of Sokoban

# How to run?
1. Clone this repository

2. Install dependencies:

```
pip3 install selenium chromedriver_autoinstaller numpy
```

3. Open a terminal window in the root folder of the repository and enter the following:

```
py main.py
```
You can choose between 2 Algorithms, Uniform Cost Search & A Star Search

# Limitations

*The map was manually written in the level1.txt file. The map is the same as the map which opens when the algorithms are done searching.

*Sometimes the player spawns in a different location, this leads to the game not being solved correctly because as I mentioned the map is hard-coded
