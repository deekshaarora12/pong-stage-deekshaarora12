# Check Player Credentials

## Feature

What part of the game does this module deliver?
Verify that the player is new or existing

## Acceptance Criteria

### Scenario: Verify the new player credentials

  Given the player username,password and email

  When the user enters the details

  Then if the player is new it gets registered
  else the player is already existing and needs to login

### Scenario: Verify the existing player credentials

  Given the player username,password

  When the user enters the details

  Then if the player is existing it logins successfully
  else the player needs to create an account
