User Management Screen UI Specification
=======================================

Requirements
------------

*   The user management screen should allow the user to view and add users.
*   The user should be able to hide disabled users.
*   The user should be able to sort the list of users by id, username, email, and enabled or disabled state.
*   The user should be able to filter the list of users by role (Guest, Admin, SuperAdmin).
*   The user should be able to toggle new user panel with a button.

UI Components
-------------

*   User Table: A table that displays the list of users, with columns for is, username, email, role, and enabled or disabled state. The table should have the ability to sort and filter the list of users.
*   New User button: A button that opens a modal for adding a new user.
*   Hide Disabled Users checkbox: A checkbox that hides the disabled user.

Behavior
--------

*   When the user clicks the "New User" button, a side panel should appear with a form for adding a new user. The form should include fields for Username, Display Name, Phone, Email, Userrole selection, and enabled checkbox.
*   When the user sorts or filters the list of users, the table should update to reflect the new sorting or filtering criteria.
*   When the user checks Hide Disabled Users checkbox, disabled users should disappear from the list.

Note
----

*   The above-mentioned functionalities can be achieved using the library like TailwindCSS, React Table, React-Bootstrap, etc.
*   The developer should take care of the validation of the form fields and handling the errors.
*   The developer should also handle the necessary server calls to fetch/update the data.
