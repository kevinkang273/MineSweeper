# MineSweeper

First install node modules by typing npm install.

Then run npm run build to transpile code into lib directory.

To play Minesweeper, create instances of MineSweeperGame in command line.
For example:

In command line, navigate to the lib directory and run `node`

Run `.load game.js` to load the contents of this file.

Then create a Game instance and run commands like so:

let game = new Game(3, 3, 3);

game.playMove(0, 1);

game.playMove(1, 2);

When done run `.exit`
