
```mermaid
sequenceDiagram
    participant Form
    participant server

    Form->>Form: Write note and submit to server
    activate server
    server-->>server: Write note and submit to server
    deactivate server


```
