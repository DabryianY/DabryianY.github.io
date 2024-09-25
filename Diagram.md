***mermaid
flowchart TD
    A[User Login Page] --> B{User Credentials Correct?}
    B -- Yes --> C[Show Dashboard]
    B -- No --> D[Show Error Message]
    C --> E[Allow Access to Resources]