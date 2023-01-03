# Tic-Tac-Toe-Chat
A online multiplayer Tic-Tac-Toe game with Live Chat-box and Highscores.

* Tic-Tac-Toe game and ChatBox is developed using socket.io.
* Game board is disabled when there is your opponent's turn and again gets enabled when your turn comes.
* Typing status is visible at top of ChatBox when opponent is typing a message.
* Highscore gets incremented by 1 when you win a game.
* Time and Username are available with Chats.
* App is responsive. It can be played on both pc and mobiles.

## Live Demo
https://tic-tac-toe-chat.onrender.com

## Installation & Running App
```
git clone https://github.com/Pranav122002/Tic-Tac-Toe-Chat.git
cd .\Tic-Tac-Toe-Chat\
npm install
node index.js
```
Go to your localhost:5000
```
http://localhost:5000/
```

## Tools used
* HTML
* CSS
* Javascript
* Node.js
* Express
* Socket.io
* jQuery

## jQuery basics
Using $ as jQuery - catch html elements in order to add attributes / read their values
$('#abc') - catch html item by id=abc
$('.abc') - catch html item by class=abc

$(function() {...}) - SHORT FOR 'The Document Ready Event':
$(document).ready(function() { ... });

This is to prevent any jQuery code from running before the document is finished loading (is ready).

