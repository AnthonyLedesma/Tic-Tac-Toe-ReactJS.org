# Tic-Tac-Toe-ReactJS.org
React Js dot org offers react turorial on building a Tic-Tac-Toe game. These are the results of following the tutorial.

<div align="center">
  <img src="https://raw.githubusercontent.com/paranoia1906/Tic-Tac-Toe-ReactJS.org/master/Tic-Tac-Tie-ractjsorg-project.PNG?raw=true" alt="Tic-Tac-Toe" width="300" height="300">
</div>

[ReactJS.org Tutorial](https://reactjs.org/tutorial/tutorial.html)

If You Prefer to Write Code in Your Editor:

If you want to do it, here are the steps to follow:

Make sure you have a recent version of Node.js installed.
Follow the installation instructions to create a new project.

    npm install -g create-react-app
    create-react-app my-app
    
Delete all files in the src/ folder of the new project (don’t delete the folder, just its contents).

    cd my-app
    rm -f src/*
    
Add a file named index.css in the src/ folder with [this CSS code.](https://codepen.io/gaearon/pen/oWWQNa?editors=0100)

Add a file named index.js in the src/ folder with [this JS code.](https://codepen.io/gaearon/pen/oWWQNa?editors=0010)

Add these three lines to the top of index.js in the src/ folder:

    import React from 'react';
    import ReactDOM from 'react-dom';
    import './index.css';
    
Now if you run npm start in the project folder and open http://localhost:3000 in the browser, you should see an empty tic-tac-toe field.

### Features list. Existing features are checked.

- [x] lets you play tic-tac-toe,
- [x] indicates when one player has won the game,
- [x] stores the history of moves during the game,
- [x] allows players to jump back in time to see older versions of the game board.

- [ ] Display the location for each move in the format (col, row) in the move history list.
- [ ] Bold the currently selected item in the move list.
- [ ] Rewrite Board to use two loops to make the squares instead of hardcoding them.
- [ ] Add a toggle button that lets you sort the moves in either ascending or descending order.
- [ ] When someone wins, highlight the three squares that caused the win.
- [ ] When no one wins, display a message about the result being a draw.
