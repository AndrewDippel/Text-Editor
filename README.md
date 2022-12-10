# Text-Editor
## [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## introduction
for this project i have created a text editior that can be used both in the browser and installed to your computer and able to be run offline.

## Table of Conents

- [User Story](#User-Story)
- [Acceptance Criteria](#Acceptance-Criteria)
- [Usage](#Usage)
- [Links](#links)
- [License](#license)


## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
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


## Usage
follow the deployed link from Heroku: https://radiant-escarpment-30419.herokuapp.com/

![Alt text](Assets/Screenshot%202022-12-10%20at%203.03.20%20pm.png)

here is a preview of the application running in the browser. as you can see we have an install button in our top nav bar and if we click on that we will be prompted t install our application as shown below

![Alt text](Assets/Screenshot%202022-12-10%20at%203.04.25%20pm.png)


here you can see thatour application has been installed and presented with a similar layout that is able to still be used when offline

## Links

* github: https://github.com/AndrewDippel/Social-Network-API.git
* heroku deployment: https://radiant-escarpment-30419.herokuapp.com/

## Credits

* Andrew Dippel

* Trainer and Training Assistant

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.