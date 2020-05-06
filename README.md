# Description: 
A Gomoku Omok Game for SENG 513, where 
  each player must aim to align 5 of their pieces 
  either horizontally, vertically, or diagonally. 
  The player to first achieve this wins the game!

- Built with HTML, CSS, Javascript, Bootstrap, JQuery, 
NodeJS, Express, and Socket.io.  

- Program uses white and black pieces statically, 
lets the player to have the option of choosing 3 color themes and 
a new user name. The users selected color theme and username are stored 
in cookies.

- Note: Small bug where first row buttons are hard to click
and unpressable on corners, because of the placement of the Bootstrap buttons.
Random join may also be buggy but tested and should work. 

Instructions: 
- Download the necessary packages with npm install:
must install Socket.io and Express to run.

- cd into gomoku directory, and run node server.js to start the server side  

- go to http://localhost:3000/ in web browser to access app,
open another browser and repeat the steps to play with another user.

- Tested with 2 concurrent users using Google Chrome and Firefox. 

           

