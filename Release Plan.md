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
* Revision number: 1.0
* revision date: Jan 26, 2017

## Notice

This project is based on the CMPS 115 project [Kitty War Card Game](https://github.com/brucedsu/KittyWar). We already have a working server and an iOS app. For CMPS 183, we plan to fix old bugs, add more cats, abilities and chance cards and add more functionalities such as supporting two more players battling in one game. We also plan to create a web app and an android app to play the game.

## High Level Goals

* Users are able to register their accounts, view their profiles and play the game via both the web app and mobile apps (iOS app and android app).
* The server matches multiple players (two or more than two players) with closing level of skill into one game.
* During the game, two players choose their representing cat and battle against each other by following the Kitty War Game Rule.
* Add more cats, abilities and chance cards.

## User Stories

### Sprint 1

* As a back-end developer, I need to fix old server bugs.
* As a back-end developer, I need to create APIs on the server side for the web app.
* As an iOS developer, I need to fix old bugs.
* As a player, I want to view my profile from the iOS app.
* As a player, I want to battle against multiple players in one game.
* As a player, I want to view my profile from the web app.
* As a web developer, I need to design user interface for playing the game.

### Sprint 2

* As a back-end developer, I need to add more cats, abilities and chance cards to the database.
* As an iOS developer, I need to update the corresponding code to support more than two players battling in one game.
* As a web developer, I need to use APIs provided by the server to send requests and receive responds. Then I make the web app update UI and internal data structures according to the returned data from the server.
* As a player, I am able to register my account and view my profile via the android app.
* As an android developer, I need to design the user interface for registration and displaying user profile.
* As an android developer, I need to do some research on the frameworks for creating the game.
* As an android developer, I need to design the user interface for playing the game.

### Sprint 3

* As an iOS developer, I need to keep polishing the app, fix bugs and add more animations.
* As an android developer, I need to code the main game logics and make the game playable.
* As an android developer, I need to keep polishing the game, fix bugs and add more animations.
* As a player, the game now is playable via web. Game logics are correct. The animation is clear and intuitive.
* As a back-end developer, I need to keep improving all the algorithms to make the whole system more stable.

## Product Backlog

* As a designer, I need to design more cat, ability and chance cards.

## Architecture

* Registration from both website and mobile apps
* Play the game via both website and mobile apps
* Server for storing data and doing algorithms

## Challenges/Risks

* Animation effects
* Server compatibility
* Fault tolerance

## Technologies

* Web application: HTML/CSS/Javascript
* Server: Django, Python, MySQL
* iPhone App: Swift, Xcode

