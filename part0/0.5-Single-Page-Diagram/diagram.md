sequenceDiagram
participant browser
participant server

    browser->>server: the server just sits here for future updates or request, the HTML is manipualted in the browser
    activate server
    deactivate server
