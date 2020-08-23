# Main Menu

## Feature

This module acts as an interface between the user and the game where the user
can do 3 things:
(i) Change Preferences (ii). Change game controls (iii). Start the game

## Acceptance Criteria

### Scenario: User wants to change settings

  Given that the game is supported by the computer on which the is running on
  and the game has been installed on the computer and is running currently

  When user wants to change settings

  Then system redirects to settings module

### Scenario: User wants to change preferences

  Given that the game is supported by the computer on which the is running on
  and the game has been installed on the computer and is running currently

  When user wants to change game preferences

  Then system redirects to preferences module

### Scenario: User wants to start the game

  Given that the game is supported by the computer on which the is running on
  and the game has been installed on the computer and is running currently

  When user wants to start the game

  Then system redirects game to the initialization module

### Scenario: User wants to exit

Given that the game is supported by the computer on which the is running on
and the game has been installed on the computer and is running currently

When user clicks on exit

then game closes
