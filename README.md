# tic-tac-toe

A Tic Tac Toe that can be played in the browser!

Store gameboard as an array inside of a Gameboard object
* players stored in objects
* object to control flow of the game itself
* main goal is to have as little global code as possible
* tuck everything inside factories
* if need a single instance of something (e.g. the gameboard, the displayController, etc...) then wrap the factory inside an IIFE (module patten) so it cannot be reused to create additional instances
* each piece of functionality should be able to fit in the game, player or gameboard objects

Focus on getting a working game in console first
* logic checks, for all winning 3-in-a-row and ties
* avoid thinking about the DOM and your HTML/CSS until game is working

Once working console game
* create an object that will handle the display/DOM logic
* function to render the contents of the gameboard array to the webpage

Write functions that allow players to add marks to a specific spot on the board by interacting with the appropriate DOM elements
* logic that keeps players from playing in spots that are already taken!

Clean up the interface to allow players to put their names
* button to start/restart the game
* display element that shows the results upon game end