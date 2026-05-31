
```mermaid
sequenceDiagram
    participant Write Note and Submit
    participant server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/notes
    activate server
    server-->>browser: HTML document
    deactivate server


```
