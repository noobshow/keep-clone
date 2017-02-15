# Keep clone

![Homepage screenshot](https://github.com/rafaelklaessen/keep-clone/raw/master/screenshots/homepage.jpg "Homepage")

An effort to make a clone of [Google Keep](https://keep.google.com) in play-scala with Firebase.
Version 1 should have:

- A login system that saves user data to Firebase
- A note system that allows logged-in users to create notes, which are saved to Firebase
- A settings page in which a user can edit his/her settings and delete his/her account

## About
The project's main focus is to learn Scala/Play and Firebase.

## Setup

#### Requirements to run the project locally:
- Activator 1.3.12 including Play 2.5.12 (requires JDK 1.8)
- NodeJS with Babel if you want to compile the ES6

#### Setup instructions
- Clone the repo
- Cd into the repo folder and run `activator ui`
- In Activator, go to the run tab and run the project after it's compiled
- The project now runs at [localhost:9000](http://localhost:9000)
- If you want to compile the ES6 because you're changing it, cd into the public folder and run `babel es6 --watch --out-file javascripts/main.js`
- You're all set! You should be able to register an account at [localhost:9000/register](http://localhost:9000/register) and login at [localhost:9000/login](http://localhost:9000/login)
