# Edit Player Credentials

## Feature

What part of the game does this module deliver?
Edit User Details

## Acceptance Criteria

### Scenario: Change User Details

  Given username and email
  the user is logged in

  When the user enters new username not equal to old one
  after clicking change User Details

  Then the new username is changed

### Scenario: Change Password

  Given username and email and password
  user is logged in

  When the user clicks on change password
  enters new password

  Then the new password is verified through email
