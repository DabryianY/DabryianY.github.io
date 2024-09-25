# User Login Process

The diagram below visualizes a typical user login process in a web application. The system checks the credentials entered by the user and either grants access or displays an error message.Entities in this diagram:

A: The login page where the user enters credentials.
B: A decision point where the system checks if the credentials are correct.
C: The dashboard page shown when the credentials are correct.
D: An error message shown when the credentials are incorrect.
E: Resources available to the user after successful login.

```mermaid
flowchart TD
    A[User Login Page] --> B{User Credentials Correct?}
    B -- Yes --> C[Show Dashboard]
    B -- No --> D[Show Error Message]
    C --> E[Allow Access to Resources]

