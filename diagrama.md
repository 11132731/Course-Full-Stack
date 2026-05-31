# Mi primer diagrama

```mermaid
sequenceDiagram
    participant Form
    participant server

    Form->>server: Write note and submit to server
    activate server
    server->>Form: Server receipt, insert note (push note) and response 201 wiht redirect (refresh view, load 4 files).
    deactivate server

      Note: When referring to the form, it is understood that it is part of the HTML view. A successful server response reloads all elements of the view, including the form, list of notes, styles, etc.
```
