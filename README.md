# Y8 Ai Gym

This project combines Phaser 3 and TensorFlow.JS (TFJS) to create a 2d environment to test what neural networks can do for games.

![screenshot](https://raw.githubusercontent.com/Y8Games/Y8-ai-gym/master/ai-gym.png)

## Install
- Download and install Node.js
- Navigate to the project root where package.json is and run `npm install` in a
 terminal, command prompt or preferably Git Bash.

## Development
- `npm start`
- Open `http://localhost:8080` in a browser
- Client side code (everything in the src folder) is auto loaded. To restart the server, push `Ctrl + C`. The main file of interest is the src/game.js that contains the algorithm and game mechanics.

## Training and Evaluating

The demo requires a keyboard.

- E - Run single evaluation step
- T - Train using prerecorded replay data
- C - Capure more replay data
- A - Autopilot
- M - Memory info (good for finding leaks)

## Production Build
- Installing, 'npm i webpack -g' and 'npm i webpack-cli -g'
- `npm run build` (requires unix like terminal)

## Deployment
- Start server for production `pm2 start server.js`
- Suggest to make an autostart in pm2

Provided by <a href="https://y8.com">Y8 Games</a>.
