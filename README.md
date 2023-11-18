# 21 Savage Fan Board with user authentication

This is a full-stack application with user authentication that allows users to like, unlike, post and delete comments on the message board.

## How It's Made:

Node.js: Used for server-side development.
JavaScript (JS): Utilized for both client and server-side functionality.
APIs: Integrated to enhance the application's features.
MongoDB: Employed as the database to store habit data.
The core functionality is implemented on the server side using CRUD (Create, Read, Update, Delete) operations. This involves sending requests to the server to handle habit data. On the client side, event listeners are utilized. Users click buttons to initiate CRUD functions and interact with the application.

## Key packages used:
1. express
2. passport
3. mongoose

## What I learned:
User authentication provides extra security not only to the user themselves, but to other users on the application. By using passport, authentication was seamless as the packages were already created and ready for use by anyone, highlighting the importance of open-source code.

## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:8080`

## Credit

Modified from Scotch.io's auth tutorial
