# Biquadris

Biquadris is a tetris clone with support for multiplayer player-versus-player games. The game was created as a final project submission for CS 246 (Objected Oriented Software Development) at the University of Waterloo. Our project totaled 2,500 lines of code across 21 modules, and it received a final mark of 105% - this demonstrates our knowledge of software design, strong command of C++ programming, and appropriate use of design patterns.

We have both text and graphic displays. The graphic display was implemented using the observer pattern and ultilized the XWindow library. Players interact with the blocks through the command line. There are seven types of blocks which are spawned on the board using the factory method pattern. The player is able to move the blocks horiztonally and downwards, to rotate them, and to drop them.

<img width="1024" alt="bq1" src="https://github.com/user-attachments/assets/6cbfc0d8-1143-4aed-9b17-d9c60ee8dc05" />

There are multiple levels: levels 0, 1, 2, 3, and 4. On level 0, blocks are generated deterministically. In levels 1 and 2, they are generated randomly. On levels 3, blocks are generated randomly, and they are also heavy, meaning they fall down after every action. Level 4 is the same as level 3, but with the added feature that new blocks will spawn automatically onto the board if old blocks are not cleared quickly.

<img width="838" alt="bq2" src="https://github.com/user-attachments/assets/69f3bbc8-29c4-41cf-963f-13e32396b315" /> <img width="486" alt="bq3" src="https://github.com/user-attachments/assets/031c66d7-8f95-4d64-8f28-9d25f76584f6" />

Clearing rows scores points, and a high-score feature was added to facilate more friendly competition between players.

<img width="400" alt="bq4" src="https://github.com/user-attachments/assets/316596d9-41ba-4cb9-a5dc-6351c661791a" /> <img width="410" alt="bq5" src="https://github.com/user-attachments/assets/3ee3e318-a5c7-4476-a56d-de45d6c05450" />


Due to the University's Policy 71 regulations, we cannot provide the code to the project.
