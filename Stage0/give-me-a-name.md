# Edit Player Credentials

## Feature

What part of the game does this module deliver?
Edit User Details

## Acceptance Criteria

### Scenario: Change UserDetails

  Given username and email, the user is loggedin

  When the user enters newusername not equal to old one,
  after clicking change UserDetails

  Then the newusername is changed

### Scenario: Change Password

  Given username,email and password, user is loggedin

  When the user clicks on change password,
  entern new password

  Then the new password is verified through email
