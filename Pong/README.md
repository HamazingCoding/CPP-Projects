# Pong Game in C++

![Pong Gameplay](https://i.imgur.com/PCELd2U.gif)

This is a simple implementation of the classic Pong game using C++. Players control paddles to bounce a ball back and forth across the screen.

## Table of Contents

- [Introduction](#introduction)
- [How to Play](#how-to-play)
- [Game Rules](#game-rules)
- [Installation](#installation)
- [Controls](#controls)
- [Running the Game](#running-the-game)
- [Credits](#credits)

## Introduction

The Pong game is a two-player game where each player controls a paddle. The goal is to prevent the ball from going past your paddle while trying to bounce it past your opponent's paddle.

The game features a simple game loop, collision detection, and basic keyboard input handling.

## How to Play

1. Player 1 controls the left paddle using the 'W' key to move up and the 'S' key to move down.
2. Player 2 controls the right paddle using the 'I' key to move up and the 'K' key to move down.
3. The game starts with the ball in the center of the screen and moves in a random direction.
4. Bounce the ball off your paddle to prevent it from going past you.
5. The game continues until one player scores enough points to win.

## Game Rules

- The ball bounces off the top and bottom walls.
- The ball bounces off paddles at different angles based on where it hits the paddle.
- If the ball goes past a player's paddle, the opponent scores a point.
- The first player to reach a certain number of points wins.

## Installation

1. Ensure you have a C++ compiler installed (e.g., MinGW or GCC).
2. Download or clone this repository to your local machine.

## Controls

- Player 1 (Left Paddle):
  - Move Up: 'W' key
  - Move Down: 'S' key
  
- Player 2 (Right Paddle):
  - Move Up: 'I' key
  - Move Down: 'K' key

## Running the Game

1. Open a terminal or command prompt.
2. Navigate to the directory where the game files are located.
3. Compile the game using the command: g++ -o pong pong.cpp

Replace `pong.cpp` with the actual filename if necessary.
4. Run the compiled executable: ./pong

5. Enjoy playing the Pong game!

## Credits

This Pong game was created using C++ and the principles of game development. It serves as a simple example of game mechanics, collision detection, and user input handling.

Feel free to modify and enhance the game as you wish. Have fun!

