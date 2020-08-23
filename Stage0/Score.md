# Preferences

## Feature

Module keeps score for the duration of the game

## Acceptance Criteria

### Scenario change in score

  Given that the game launched successfully
  user/users is/are playing the game
  and the physics module informs the score module
  when a player/computer scores

  When a player/computer scores

  Then module increments the score of the player/computer

### Scenario: Win

  Given that the game launched successfully
  user/users is/are playing the game
  and the physics module informs the score module

  When the score of the player/computer is 10

  then display the winner and redirect to main menu module.
