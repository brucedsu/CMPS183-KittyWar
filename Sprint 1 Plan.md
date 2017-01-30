# Sprint 1 Plan

* Product name: Kitty War
* Team name: Dog & Koala Bear
* Sprint completion date: Feb 13, 2017
* Revision number: 1.0
* Revision date: Jan 26, 2017

## Goal

* Fix old bugs (server and iOS app).
* Enable user to view his or her profile via both website and iPhone app.
* Design user interface to support more than two players in one game.

## User Stories

### As a server developer, I need to fix old server bugs.

* (2) Fix bug: sometimes user can't use chance card
* (5) Fix other unknown/known bugs
* Total story points: 7

### As a server developer, I need to create APIs on the server side for the web app.

### As a iOS developer, I need to fix old bugs.

* (2) Fix bug: sometimes go to next phase unexpectedly
* (5) Fix other unknown/known bugs
* Total story points: 7

### As a player, I want to view my profile on the iOS app.

* (3) Design user interface for displaying user name, skill level, unlocked cats and wins
* (1) Add required data columns including skill level and wins to database
* (3) Create API on the server side to send required user profile data to the iOS app
* (3) Use the API provided by the server to fetch all required data
* Total story points: 10

### As a player, I want to battle against multiple players in one game on the iOS app.

* (5) Redesign user interface to support battling against multiple players
* (3) Create API on the server side to let player select one target from multiple enemies
* (3) Enable player choose a target for specific movement on the iOS app
* (3) Use the API provided by the server to show strategies of multiple enemies
* (3) Update player and enemies' status at the end of each phase
* Total story points: 17

### As a player, I want to view my profile from the web app.

* (3) Design user interface for displaying user name, skill level, unlocked cats and wins
* (3) Create API on the server side to send required user profile data to the web app
* (3) Use the API provided by the server to fetch all required data
* Total story points: 9

### As a web developer, I need to design user interface for playing the game.

* (3) Design the user interface for finding a match
* (5) Design the user interface for playing the game
* Total story points: 8

#### Grand Total Story Points: 58

## Team roles

* :bowtie: Hejia Su (iOS & Server & Web Developer)
* :blush: Yueqiao Zhang (Web Developer)
* :smirk: Juan Gonzalez (Server & Android Developer)
* :sleeping: Eric Martinez (Server & Android Developer)
* :sunglasses: Jiahua You (Web Developer)
* :yum: Jiahao Xu (iOS & Android Developer)

## Initial Tasks

### Hejia Su

#### As a back-end developer, I need a user database to store user information and card a database to store card data

* Configure SQL server
* Develop working SQL model for this information
* Configure Django server to process these requests

### Yueqiao Zhang

#### As a player, I want to be able to register an account via an iPhone app

* Build front end of iPhone app to accept registration
* Build protocol between iPhone app and server

### Juan Gonzalez

#### As a player, I want to be able to register an account via an iPhone app

* Configure custom python server to accept registration requests and forward to database

### Eric Martinez

#### As a player, I want to be able to register an account via a website

* Build basic website to handle registration
* Store data into a database to track who has registered

## Initial Burnup Chart
![Alt text](https://docs.google.com/spreadsheets/d/1cR18Zlbq7eRBpJ_cUE_FLFMCvzjE2VScGuYUP0Wnkp8/pubchart?oid=1455941923&format=image "Burnup Chart")

## Scrum Times

* Tuesday, Thursday, Friday
* Times: 1:00 pm - 2:00pm

