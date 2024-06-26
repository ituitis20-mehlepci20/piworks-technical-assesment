# User Management Screen - User Interface Specification Document

## Introduction

This document outlines the user interface specifications for the User Management Screen, which will be used by Software developers who will develop this user interface. It includes the requirements, details related to UI components, the behavior of the page when using these components, what to show to the user at the beginning,

## User Interface Components

### 1. User List View

#### Description:
The User List View displays a list of users registered in the system along with their properties.

#### Components:
- User Rows: Each user is represented as a row displaying information such as ID, username, email, and enabled/disabled status.
- Sorting Options: Enables administrators to sort users based on each parameter of their properties.
- Filtering Options: Enables administrators to filter users based on each parameter of their properties.

### 2. New User View

#### Description:
New User View enables to add news users to the system.

#### Components:
- Username Bar: Allows to add a username for the new user.
- Display Name Bar: Allows to add a display name for the new user.
- Phone: Allows to add a dphone number for the new user.
- Email: Allows to add an email for the new user.
- User Roles Bar: Allows to add a user role for the new user, which can be Guest, Admin or SuperAdmin.
- Enabled Toggle: Allows to enable the new user.

## User Interaction

### 1. Navigation

#### Components:
- New User Button: Allows the New User View to open up.
- Hide Disabled User Button: Allows to hide the disable users from the User List View.
- Save User Button: Allows to add the New User to the database, and shown on the User List View.
