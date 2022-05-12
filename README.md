# Full-Stack-Open-Part-0
  Exercises from Part 0 of the course Full Stack Open 

0.4 New note:

browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note
server-->browser: HTTP 302

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes
server-->browser: HTML-code #With 'notes' and 'new_note'#
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js
server-->browser: main.js

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
server-->browser: [{ content: "exercise 4 part 0" date: 2022-05-12}, ...]

0.5 Single page app:

browser-->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
server-->browser: spa
server-->browser: main.css
server-->browser: spa.js
server-->browser: data.json 

0.6 New Note: 

browser-->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
server-->browser: new_note_spa 

