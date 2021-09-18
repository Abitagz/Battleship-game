# Battleship Game

Battleship game is a python game which runs in the Code Institute mock terminal on Heroku.
Users can try to beat the computer by finding all of the computer's battleship before the computer finds theirs.

## How to play
## Features
### Existing Features
   * Random board generation
     * Ships are randomly placed on both the player and both the player and computer boards
     * The player cannot see where the coputer's ships are
   * Play against the computer 
   * Accepts user input
   * Maintains scores
   * Input Validation and error-checking 
     * You must enter numbers
     * You cannot enter the same guess twice
   * Data maintained in class instances

  ### Future Features
   * Allow player to select the board size and number of ships
   * Allow player to position ships themselves
   * Have ship large than 1 * 1

## Data Model
  I decided to use a Board class as my model. The game creats two instance of the board class to hold the player's and the computer's board

## Testing
  I have manually tested this project by doing the following
  * Passed the code through a PEP8 linter and confirmed there are no problem
  * Given invalid inputs: strings when numbers are expected, out of bounds inputs, same input twice
  * Tested in my local terminal and the Code Institute Heroku Terminal

## Bugs
  Solved Bugs
   * When i wrote the project i was getting index........
   * My validate coordinates.......

## Remaining Bugs
   * No bugs remaning

## Validator Testing
   * PEP8
   * No errors wre returned from PEP8online.com

## Deployment
  This project was deployed using Code Institute's mock terminal for heroku
  * Steps for deployment
    * Fork or clon this repository
    * Create a new Heroku app
    * set the buildbacks to python and Node Js in that order
    * link the Heroku app to the repository
    * Click on Deploy
## Credits 
  * Code Institute for the deployment terminal
  * Wikipedia for the details of the Battleship game          
    