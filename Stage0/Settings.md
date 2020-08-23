# Settings

## Feature

User can change settings like sound and display

## Acceptance Criteria

### Scenario: User wants to change font size

  Given user is in the display settings screen

  When user changes the font size

  Then module updates the font size in memory and updates font size in the screen

### Scenario: User wants to change background color

Given user is in the display settings screen

  When user changes the background color

  Then module updates the background in memory and updates background in the screen

### Scenario: User wants to change number of players

  Given user is in the players settings screen

  When user changes the number of players (Either 1 or 2)

  Then module updates the number of players in memory
  which is later accessed by the initialization module
  