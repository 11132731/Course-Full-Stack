
```mermaid
sequenceDiagram
    participant Form
    participant server

    Form->>server: Write note and submit to server
    activate server
    server->>Form: Server receipt, insert note (push note) and response 201 wiht redirect (refresh view, load 4 files).
    deactivate server


```
