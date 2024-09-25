# User Login Process

The diagram below visualizes a typical user login process in a web application. The system checks the credentials entered by the user and either grants access or displays an error message.

```mermaid
flowchart TD
    A[User Login Page] --> B{User Credentials Correct?}
    B -- Yes --> C[Show Dashboard]
    B -- No --> D[Show Error Message]
    C --> E[Allow Access to Resources]

