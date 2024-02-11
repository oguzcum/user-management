# User Management Interface Specification

## Overview
The user management interface consists of two main sections: a user list on the left and a user editing form on the right.

### User List
The user list section displays a list of users with the following columns:
- ID
- Username
- Email
- Enabled (boolean indicating if the user is active)
Additionally, it includes the following buttons:
- "New User": Allows the user to add a new user.
- "Hide Disabled Users": Filters out disabled users from the list.

### User Editing Form
The user editing form allows users to add a new user or edit existing user details. It includes the following fields:
- Username
- Display Name
- Phone
- Email
- User Roles (a dropdown or multi-select field for selecting user roles)
There's also a "Save User" button to save the changes.

## Initial Behavior
Upon loading, the user list should be populated with existing users, and the user editing form should be empty.

## Page Interactions
### Adding a New User
1. Clicking the "New User" button should clear the user editing form and allow the user to input new user details.
2. After entering the required information, the user can click the "Save User" button to add the new user to the system.

### Editing an Existing User
1. Clicking on a user from the user list should populate the user editing form with that user's details.
2. The user can then modify the necessary fields.
3. Clicking the "Save User" button should update the user details with the changes made.

### Hiding Disabled Users
1. Clicking the "Hide Disabled Users" button should filter out disabled users from the user list.
2. Clicking the button again should revert the list to its original state, displaying all users.

## Requirements
- The interface should support adding, editing, and viewing user details.
- Usernames and emails must be unique.
- User roles should be selectable from a predefined list.
- Input fields should have proper validation to prevent incorrect data entry.
- Changes made to user details should be reflected immediately in the user list.

