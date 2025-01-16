# Biquadris

Biquadris is a tetris clone with support for multiplayer player-versus-player games. The game was created as a final project submission for CS 246 (Objected Oriented Software Development) at the University of Waterloo. Our project totaled 2,500 lines of code across 21 modules, and it received a final mark of 105% - this demonstrates our knowledge of software design, strong command of C++ programming, and appropriate use of design patterns.

We have both text and graphic displays. The graphic display was implemented using the observer pattern and ultilized the XWindow library. Players interact with the blocks through the command line. There are seven types of blocks which are spawned on the board using the factory method pattern. The player is able to move the blocks horiztonally and downwards, to rotate them, and to drop them.

(INSERT GAMEPLAY HERE)

There are multiple levels: levels 0, 1, 2, 3, and 4. On level 0, blocks are generated deterministically. In levels 1 and 2, they are generated randomly. On levels 3, blocks are generated randomly, and they are also heavy, meaning they fall down after every action. Level 4 is the same as level 3, but with the added feature that new blocks will spawn automatically onto the board if old blocks are not cleared quickly.

(INSERT GAMEPLAY HERE OF DIFFERENT LEVELS)

Clearing rows scores points, and a high-score is to facilate more friendly competition between players.

(INSERT GAMEPLAY OF HIGH SCORES)

Due to the University's Policy 71 regulations, we cannot provide the code to the project.
