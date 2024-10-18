```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->> server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    Note right of server: in this case, the server doesn't ask <br/> the browser to reload the page

```
