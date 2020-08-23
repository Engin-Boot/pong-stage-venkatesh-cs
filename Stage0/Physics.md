# Preferences

## Feature

Module defines the physics behind the game
Module defines behaviour of the ball

## Acceptance Criteria

### Scenario Change in direction of ball

  Given that the game launched sucessfully
  user/users is/are playing the game

  When the ball hits the upper and lower parts of the rectangle

  Then module calculates the new direction of the ball
  and and changes the direction of the ball accordingly
  and updates it on the screen

### Scenario when user/computer miss the ball

  Given that the game launched sucessfully
  user/users is/are playing the game

  When user/computer miss the ball

  Then module determines who scored and informs the score module
