# Play Game

## Feature

What part of the game does this module deliver?
How the Game is played

## Acceptance Criteria

### Scenario: Player 1 hits the ball and count score

  Given the game is started, player 1 playing

  When player 1 hits the ball

  Then the score of player 1 increases by one
  and the score is checked

### Scenario: player 1 does not hit the ball

  Given the game is started, player 1 playing

  When player 1 does not hits the ball

  Then player 2 gets a chance
  
### Scenario: player 2 hits the ball and count score

  Given the game is started, player 2 playing

  When player 1 does hits the ball

  Then the score of player 2 increases by one
  and the score is checked
  
### Scenario: player 2 does not hit the ball

  Given the game is started, player 2 playing

  When player 2 does not hits the ball

  Then player 1 gets a chance
  
### Scenario: The score is checked

  Given the game is started

  When player 1 or Player 2 hits the ball

  Then the score is checked, if it is greater than
  or equal to 100
  
### Scenario: Winner is Declared

  Given the game is started, player 1 or Player 2 hits the ball 

  When the score is checked

  Then if the score is greater than or
  equal to 100, that player is winner
  
### Scenario: Game Over

  Given the score is greater than or equal to 100 

  When Player 1 or Player 2 is the winner

  Then the game is over
  
### Scenario: Play Again

  Given the game is over 

  When the user clicks play Again button

  Then the game is started again
  
### Scenario: Quit the game

  Given the game is over 

  When the user clicks quit the game button

  Then the game is quitted
  
### Scenario: Change Directions

  Given the game is started

  When player 1 or player 2 hits the ball

  Then the ball changes its direction
  left,right, diagonally up, diagonally down
  up, down
  
### Scenario: Check Collisions

  Given the game is started

  When player 1 or player 2 hits the ball

  Then either the ball collides with bars or
  the ball first collides with bars then
  with top and bottom walls
