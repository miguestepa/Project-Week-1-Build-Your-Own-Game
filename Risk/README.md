<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Risk-like Game
*[Miguel Estepa]*

*[Data Analytics Bootcamp, Barcelona & 3-April-2020]*


<img src="https://images-na.ssl-images-amazon.com/images/I/71r4QhHAqtL._AC_SL1024_.jpg" width="300"/>


## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
Risk is a well-knwon strategy board game. This project tries to emulate a similar experience. 
I chose this game because I love strategy games and I thought this would be an excellent challenge.

## Rules
The goal of this game is to conquer the Earth. 
The player will achieve this conquering all the Earth's continents by using his/her troops.

1. At the beginning of the game, all player will roll a dice to stablish the order of turns. 
The highest roll goes first, then the second and so.

2. All players recieve 5 troops. They can place them as they want but they can just place them in a single country in their turns. 
All players must place all their troops. If a continent is already conquered they can not place their troops
(Ex: Player1 places 2 troops in Africa, then Player2 places 5 troops in Oceania, then Player1 places 3 troops in Europe.)

3. One this has been done, the game starts properly speaking. In order, players will do different actions during their turn. 
This order will be: recieving troops, placing new troops, moving troops and reinforce/discover/attack.

3.A. The player, at the beginning of the turn will recieve new troops acording to "the number of continents possessed/2". 
At least, the player will recieve 1 troop.

3.B. The player has to place the troops in a possessed continent. They can be distribuited as wanted.

3.C. Moving troops. You can only 1 group of troops in your turn. 
The movements these troops will be able to do will come determined by the continent where they are place.
(Ex: you can move your troops to Oceania in one turn if they are in Europe)
The list of possible path is this one:


When the player moves their troops 3 things can happen:
- If the continent is already conquer by the player, it will be reinforced. At least 1 troop must remain in the original continent.
- If the continent is not occupied by any player, the player will automacally conquer it. At least 1 troop must remain in the original continent.
- If the continent is already conquer by another the player there will be a dice rolls fight. The defender will roll a dice for each troop in the continent. 
  The same will do the attacker according to the troops used to attack the country. 
  If the attack wins, the defender troops will be destroy and the attacker will conquered the continent.
  If the defender wins, the attacking forces will be destroyed.

## Workflow

First I did some deep research about the game. I had not played before this game so I discovererd is quite complicated.
Then I created a Trello board to save my firsts thoughs.
The pseudo-code was created.
Then I created the first functions. Touch a little here and little there.
I discoved that was I had planned would be really difficult so I tried to simplify everything.
Then I kept programming until everything was more or less finished.


## Organization
The main tool to organize the project was Trello.

The whole program is created in a Jupyter Notebook. Different functions are created in different cells and all are run at the end in a single line.
Future iterations will improve the functions and other features.

## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/miguestepa/Project-Week-1-Build-Your-Own-Game)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/b/R1gsNu8W/ironhack-project-week1)  
