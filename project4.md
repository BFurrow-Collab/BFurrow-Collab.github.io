[Back to Portfolio](./)

Project 4 Title
===============

-   **Class:** Procedural Programming (CSCI 235)
-   **Grade:** 105
-   **Language(s):** C++
-   **Source Code Repository:** [BFurrow-Collab/Portfolio-Project4](https://github.com/BFurrow-Collab/Portfolio-Project4)  
    (Please [email me](mailto:BPFurrow@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project is simple - to program the game of Battleship. 
The game takes place within two 10 x 10 grids, one for the player and one for the AI. Each tile on the grid is represented by a row letter and column number (e.g. B3). Each ship takes up consecutive tiles, arranged either horizontally or vertically. The ships cannot overlap, and there is one type of each of varying lengths. 
<br/><br/>
Ship Name	        Length<br/>
Aircraft Carrier    5<br/>
Battleship	        4<br/>
Submarine	        3<br/>
Destroyer	        3<br/>
Patrol Boat	        2<br/>
<br/><br/>
In this program, the ship placement on the board will be randomly generated, and the user will have a yes/no choice on if they want to use the board. This will continue until the player says yes. The player and the enemy AI then take turns choosing which tile on the board to target. If that tile had a ship, it's a hit signified by an 'X'. If it's a miss, it displays a '~'. When all tiles of a ship are hit, the ship is sunk, and the sinking is announced (e.g. "You sank the enemy's battleship!"). Whoever sinks all the opponent's ships first wins.
<br/>
The programmed AI for the enemy was provided by the professor due to it being above the level of the class. The sections to work on included ... [[NEED PROMPT EMAIL]]. [[FURTHER EXPLANATIONS]] 

... (describe the Battleship game, describe what is being worked on specifically)

## How to compile and run the program

How to compile (if applicable) and run the project.

```bash
cd ./project
python setup.py
```

If the programming language does not require compilation, the update the heading to be “How to run the program.” If your application is deployed on a remote service, including instructions on how to deploy it.

## UI Design

Due to the nature of this project as a turn-based game, user interaction is a constant throughout rather than being of minimal input and output (which is the case for many other program projects). As it was stated within the game rules in the project description, the user will start off by having a yes/no choice on a starting board with randomized ship placements (see Fig 1). The user will be prompted with new boards continuously so long as they say 'n' for no. Once they say 'y' for yes, the game will start. The enemy turns will be independent - out of the player's control. The player only has control of which letter-number tile they wish to target, an action prompted in text after the AI's turn (see Fig 2 and 3). This will continue until all the ships of either the user or the AI are sunk (see Fig 4 and 5). [[???]] After this, the player will be given another yes/no quesstion on if they wish to play another game. [[???]]

<br/>


Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Lorem ipsum dolor sit amet (see Fig 1), consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat (see Fig 2). Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum (see Fig 3).

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen [[Battleship starting screen]]

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed. [[Enemy action]]

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs. [[User action]]

![screenshot](images/dummy_thumbnail.jpg)  
Fig 4. Feedback when an error occurs. [[User loses (?)]]

![screenshot](images/dummy_thumbnail.jpg)  
Fig 5. Feedback when an error occurs. [[User wins]]

![screenshot](images/dummy_thumbnail.jpg)  
Fig 5. Feedback when an error occurs. [[Continue? prompt - ???]]

[Back to Portfolio](./)
