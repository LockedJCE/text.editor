# Text.Editor
 [![MIT license](https://img.shields.io/badge/License-MIT-white.svg)](https://lbesson.mit-license.org/)

 [![NPM Express](https://img.shields.io/badge/NPM-Express-blue.svg)](https://www.npmjs.com/package/express)
 [![NPM Mongoose](https://img.shields.io/badge/NPM-Mongoose-blue.svg)]([https://www.npmjs.com/package/pg](https://www.npmjs.com/package/mongoose))
 
https://jensentext.onrender.com
## Description

A browser-based text editor that operates as a single-page application (SPA) and meets Progressive Web App (PWA) standards. This application includes multiple data persistence methods to ensure redundancy in case some options are unsupported by the browser. Additionally, the application is designed to function offline.

## Table of Contents
  * [Acceptance-Criteria](#acceptance-criteria)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Credits](#credits)
  * [Contributing](#contributing)
## Acceptance-Criteria
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
    WHEN I deploy to Render
    THEN I should have proper build scripts for a webpack application
  ## Installation
To get started clone this repository run npm i to install all the necessary files with "mongoose" and "express".
<br>

```terminal
git clone git@github.com:LockedJCE/text.editor.git
```

```terminal
npm install
```

or use my deployed render page link at the top.

## Usage
To take notes or write code snippets regardless of internet connectivity, ensuring they are securely saved and accessible for future use.

## Credits 
Starter code provided by https://github.com/coding-boot-camp/cautious-meme

## Contributing
You can contribute via the following GitHub link.

https://github.com/LockedJCE/text.editor

Clone the repo and request a merge via push of your contributions. If you have further questions please email me at Lockinjce@gmail.com.
