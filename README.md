# Wordcatcher Text Editor

## Description
Wordcatcher Text Editor is a single page application that runs in a the browswer and meets the PWA criteria. 

It is a simple text editor app that can function both online and offline and features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. 


## Table of Contents
- [Wordcatcher Text Editor](#wordcatcher-text-editor)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Mock-Up](#mock-up)
  - [Technologies](#technologies)
  - [License](#license)
  - [Questions](#questions)
  - [Author](#author)


## Installation 

Open Heroku deployed application : 
Go to the link and hit the "install" button to install the app locally.
  
For repo clone or download:

Download or clone repository to use this application on local machine.

  Before attempting to use this application, you must have the follow programs installed to your computer: 

  - VS Code
  - Node.js
  
  In the terminal of VS Code please run the following command to install dependencies: 
  ```bash
npm install 
```

To start run the following command in terminal 
```bash
npm run start:dev
npm run start
```
Then go to http://localhost:3000/ to run this application on your local machine.

## Usage
Use Heroku deployed link:
and install if you want to use it offline.

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

## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

## Technologies
- HTML
- CSS
- JavaScript
- express.js
- Node.js
- idb
- webpack
- workbox

## License 
![License](https://img.shields.io/github/license/lalalaviv/wordcatcher-text-editor)

## Questions

  Feel free to reach out if you have any enquiries
  <br/>
  GitHub: [@lalalaviv](https://github.com/lalalaviv)
  Email: lalala.viv@hotmail.com


## Author

  Vivian Lee