# Pig-Game
Dice Game Based off of Jonas Schmedtmann's Pig game project from his Complete JavaScript Udemy course. 

# Features
**GAME RULES**

The game has 2 players, playing in rounds
In each turn, a player rolls a dice as many times as he wishes. Each result get added to his ROUND score
BUT, if the player rolls a 1, all his ROUND score gets lost. After that, it's the next player's turn
The player can choose to 'Hold', which means that his ROUND score gets added to his GLBAL score. After that, it's the next player's turn
The first player to reach 20 points on GLOBAL score wins the game
**Extra CHALLENGES**

Change the game to follow these rules:

A player looses his ENTIRE score when he rolls two 6 in a row. After that, it's the next player's turn. (Hint: Always save the previous dice roll in a separate variable)
Add an input field to the HTML where players can set the winning score, so that they can change the predefined score of 100. (Hint: you can read that value with the .value property in JavaScript. This is a good oportunity to use google to figure this out :)
Add another dice to the game, so that there are two dices now. The player looses his current score when one of them is a 1. (Hint: you will need CSS to position the second dice, so take a look at the CSS code for the first one.)
How To Use
To clone and run this application, you'll need Git and Node.js (which comes with npm) installed on your computer. From your command line:

# Clone this repository
$ git clone https://github.com/ymer28/Pig-Game

# Install dependencies
$ npm install

# Run the app
$ npm start
Acknowledgements
The Complete JavaScript Course 2021: Build Real Projects! by Jonas Schmedtmann
