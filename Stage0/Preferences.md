# Preferences

## Feature

User can preferences settings like number of players, graphics

## Acceptance Criteria

### Scenario: User wants to change graphics

  Given user is in the graphics preferences screen

  When user changes the graphics in the menu

  Then module determines if the graphics setting chosen by the user is feasible
  if the settings are indeed feasible then the system updates the preference
  in memory.
