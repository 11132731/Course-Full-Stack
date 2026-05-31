```mermaid
sequenceDiagram
    participant Form
    participant server

    Form->>server: Write note and submit to server
    activate server
    server->>Form: Server receipt, insert note and response 201 with redirect
    deactivate server
    
    note over Form,server: Server response reloads all view elements
