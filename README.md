# Note-Taker
Note Taker

## User Story

AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete


## Acceptance Criteria

GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column

## Description

A node.js application that takes in user input to store notes. When the note is generated, it is saved and stored in the local storage. With a option to delete later if needed. 

## Installation

First git clone this repo: `git clone git@github.com:kmarie0420/Note-Taker.git`
Then run npm i at the root of this project in your local directory. Additionally you will run npm i express. 

  * Uses the [Express package](https://www.npmjs.com/package/express).
  
  * Uses the [Server.js](https://www.npmjs.com/package/server.js).

## Usage Information

To run this application, use the command line to navigate to the directory of the application, install all dependencies (npm i), then type the command `node server.js`. You will then get a prompt saying `API server now on port 3001.` Once you navigate to the port on your UI, you can input notes that will be stored in your local storage. With the ability to delete current notes as well.

## Mock-Up 

The following images show the web application's appearance and functionality:

![Existing notes are listed in the left-hand column with empty fields on the right-hand side for the new note’s title and text.] ![Alt text](images/mock-up(1).png)

![Note titled “Balance accounts” reads, “Balance account books by end of day Monday,” with other notes listed on the left.] ![Alt text](images/mock-up(2).png)


## Contributions

Kalynn Powell

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Github Repository

https://github.com/kmarie0420/Note-Taker

## Questions

If you have any questions or concerns, please email `kpowell0420@gmail.com` or https://github.com/kmarie0420 .  

## Credits

https://www.npmjs.com/package/server.js
https://www.npmjs.com/package/express
