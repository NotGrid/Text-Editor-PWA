# Text-Editor-PWA

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Screenshots](#screenshots)
  - [Links](#links)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

To build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria.

### User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

### Screenshots
## Image of Application homepage
![Screenshot 2022-09-24 161426](https://user-images.githubusercontent.com/102490542/192121868-777dfe43-0fb8-4e45-b111-1a1636f66dc1.png)

## Image of Installation
![Screenshot 2022-09-24 161620](https://user-images.githubusercontent.com/102490542/192121899-36b1814b-7328-458d-b6aa-1461c8b8d9ac.png)

## Shows the manifest.json
![Screenshot 2022-09-24 161858](https://user-images.githubusercontent.com/102490542/192121971-4022dbc4-254f-4a96-b191-842b170a8641.png)

## Shows the active service worker
![Screenshot 2022-09-24 161948](https://user-images.githubusercontent.com/102490542/192121981-17466e79-90bc-4fb4-95d1-115c95a9788d.png)

### Links

- Github REPO: https://github.com/NotGrid/Text-Editor-PWA
- Deployed Application: https://sheltered-fortress-09321.herokuapp.com/

### Built with

- Webpack

### Continued development

I plan to create different types of applications using the methods I learned from this project.

## Author

- Github - https://github.com/NotGrid
- LinkedIn - https://www.linkedin.com/in/andrew-white-053803235/
