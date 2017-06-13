# Astral Records
  _Starlynne Start, 6.11.17_

## Description

_A record store POS app created to practice Angular CLI, dynamic routing, and learn AngularFire._


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.1.1.

## Setup/Installation
* Clone this repository
* Navigate to repository in command line
* Run npm install
* Open project in editor
* Create a file in src/app called api-keys.ts
* Follow instructions below to set-up Firebase
* Run ng serve

## Firebase

_In order to run this app, you will need a Firebase account and credentials._
* Go to https://firebase.google.com/ and set up an account
* Create a new project
* Select "Add Firebase To Your Website"
* Copy the credentials
* In the cloned project file src/api/api-keys.ts, type:
  * export var masterFirebaseConfig = {
    apiKey: "xxxx",
    authDomain: "xxxx.firebaseapp.com",
    databaseURL: "https://xxxx.firebaseio.com",
    storageBucket: "xxxx.appspot.com",
    messagingSenderId: "xxxx"
  };
  *  Place your Firebase credentials in the appropriate spots.
* Return to Firebase Console, select project's name from the list.
* Visit the Database area by selecting the Database option from the navbar on the left-hand side.
* Near the top of the page, there should be a blue navbar reading Realtime Database. Below this, select the option that reads RULES.
* Change both the ".read", and ".write" properties here to "true"

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
