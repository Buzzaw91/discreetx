# discreetX chat
DiscreetX is a simple end-to-end encrypted chat utilizing Virgil Security SDK and stream chat API

## Screenshots

TBD

## IMPORTANT
You must use node.js version 11.14.0
Later version do not yet support Virgil security SDK

You also need to have MongoDB available either locally or hosted

To run this project you will need accounts for both
Stream: https://getstream.io/accounts/signup/
and
Virgil: https://dashboard.virgilsecurity.com/signup
Once you've created
your accounts, place your credentials in `backend/.env`. You can use 
`backend/.env.example` as a reference for what credentials are required.

## Installation

To run the app please follow these instructions:
```
1. Clone the repository

git clone https://github.com/Buzzaw91/discreetx.git


2. Install the dependencies
use of yarn package manager is required for the front end
recommend using it for both front- and backend

install dependencies for both front- and backend


```
## Run the chat app
In the backend 'npm run dev' to start the server and connect to mongoDB
In the frontend 'npm start' to run a development server, you can run run multiple instances of the client
and start sending messages between them


## Tech Stack
* React
* Node.js
* Express.js
* Virgil SDK
* Stream React Chat
* MongoDB
* mongoose
