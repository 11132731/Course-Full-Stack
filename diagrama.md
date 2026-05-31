
```mermaid
sequenceDiagram
    participant Form
    participant server

    browser->>Form: Write note and submit to server
    activate server
    server-->>server: Write note and submit to server
    deactivate server


```
