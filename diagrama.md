
```mermaid
sequenceDiagram
    participant Form
    participant server

    browser->>server: Write note and submit to server
    activate server
    server-->>browser: HTML document
    deactivate server


```
