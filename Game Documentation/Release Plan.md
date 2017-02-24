# Release Plan

## Basic Information

* Product name: Kitty War
* Team name: Dog & Koala Bear
* Team members:
    1. Hejia Su (Bruce) (Product Owner)
    2. Yueqiao Zhang (Janet)
    3. Juan Gonzalez
    4. Eric Martinez
    5. Jiahua You (Gawa)
    6. Jiahao Xu (Alex)
* Release date: Mar 30, 2017
* Revision number: 1.1
* revision date: Jan 30, 2017

## Notice

This project is based on the CMPS 115 project [Kitty War Card Game](https://github.com/brucedsu/KittyWar). We already have a working server and an iOS app. For CMPS 183, we plan to fix old bugs, add more cats, abilities and chance cards and add more functionalities such as supporting two more players battling in one game. We also plan to create a web app and an android app to play the game.

## High Level Goals

* Users are able to register their accounts, view their profiles and play the game via both the web app and mobile apps (iOS app and android app).
* The server matches multiple players (two or more players) with closing level of skill into one game.
* One server to support cross platform matches (Android, iOS, web app)
* Add more cats, abilities and chance cards.

## User Stories

### Sprint 1

* As a server developer, I need to polish server code
* As an iOS developer, I need to polish iOS code
* As a server developer, I need to accept connections from the browser web app
* As a player, I want to view my profile on the iOS and web app.
* As a web developer, I would like to connect to the python game server.
* As an android developer, I would like to have the project setup and design

### Sprint 2

* As a server developer, I need to add more cats, abilities and chance cards to the database.
* As an iOS developer, I need to update the corresponding interface and code to support more than two players battling in one game
* As a web developer, I need to use APIs provided by the server to receive responses and react accordingly.
* As a player, I am able to register my account and view my profile via the android app.
* As an android developer, I need to design the game and start building a basic connection to the server

### Sprint 3

#### (Sprint 3 Tentative)
* As an iOS developer, I need to keep polishing the app, fix bugs and add more animations.
* As an android developer, I need to code the main game logics and make the game playable.
* As an android developer, I need to keep polishing the game, fix bugs and add more animations.
* As a player, the game now is playable via web. Game logics are correct. The animation is clear and intuitive.
* As a server developer, I need to keep improving all the algorithms to make the whole system more stable.

## Technologies

* Web application: HTML/CSS(Bootstrap)/Javascript
* Server: Django, Python, MySQL
* iPhone App: Swift, Xcode
* Android App: Java, libGDX

