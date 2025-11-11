```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/notes/new_note_spa
    activate server
    server-->>browser: JSON data
    deactivate server
```

