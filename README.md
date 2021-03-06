# COMP110 Coding Task 2 - Game Component

A changelog of this project is located in CHANGELOG.md, giving an overview offeature implementation and major bug fixes.

## Location
This project is being developed in the Group Desktop Game [Level Generation Branch](https://github.com/NecroReindeer/comp150-desktop-game/tree/level-generation). The commit log and the full source and component integrated into the game can be found it that repository.

Regarding the Learning Space submission: The files that contain code relevant to the level generation from the group project are included in the submission.  
The classses and methods that were developed **specifically** for the level generation component in this submisssion are as follows:

###Relevent classes and methods
####Level
* generateMaze()
* createCharacter()
* placeExit()
* clearLevel()
* getRandomCoordinatesInRoom()
* placeNPC()

####Maze
* Everything

####MazeGenerationManager
* Everything

####Room
* Everything

####LevelCell
* LevelCell()
* allEdgesInitialised()
* getRandomUninitialisedDirection()
* getBiasedUninitialisedDirection()
* getEdge()
* assignRoom()
* initialisedEdge()

####CellEdge
* None of the methods, but just its existence (so the constructor, I guess)

####CellDoor
* None of the methods, but just its existence (so the constructor, I guess) and the fact it inherits from CellEdge

####CellWall
* None of the methods, but just its existence (so the constructor, I guess) and the fact it inherits from CellEdge

####CellPassage
* None of the methods, but just its existence (so the constructor, I guess) and the fact it inherits from CellEdge

##Trello Board
###Sprint 1
![Sprint 1](https://github.com/NecroReindeer/comp110-coding-task-2/blob/master/Trello/Sprint%201.png)


###Sprint 2
![Sprint 2](https://github.com/NecroReindeer/comp110-coding-task-2/blob/master/Trello/Sprint%202.png)


###Sprint 3
![Sprint 3](https://github.com/NecroReindeer/comp110-coding-task-2/blob/master/Trello/Sprint%203.png)


##Proposal
I intend to create a procedural level generator for our COMP150 game.
It will include:
* Generating the level layout so that it is appropriate for the game, that is, a maze of rooms that isn't overly complicated
* Placing Doctors and Guards in appropriate positions
* Placing the exit in an appropriate position
* Placing collectable items in appropriate positions
* Placing doors and locked doors in appropriate positions
* Ensuring that keycards are placed on the correct side of locked doors

###Proposal Trello Board
Note that the user stories will be made more specific as we develop and playtest the game

![Initial Trello Board](https://github.com/NecroReindeer/comp110-coding-task-2/blob/master/Trello/Proposal.png)
