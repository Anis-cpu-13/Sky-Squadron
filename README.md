# Sky-Squadron

## Introduction

This project is a Tower Defense mini-game. The player must defend their territory against enemies that arrive in waves.

## Features

The project includes the following features:



    Real-time graphics display
    Creation of enemies with different characteristics (speed, health, etc.)
    Movement of enemies along predefined trajectories
    Detection of collisions between enemies and projectiles launched by the player
    Creation of player-launched projectiles with different characteristics (speed, firing frequency, etc.)
    Management of enemy waves through different levels of the game
    Player points and lives system
    Display of an animation when an enemy is hit

## Usage

To launch the game, follow these steps:

    Install java script on your computer.

  Open a command prompt in the folder containing the project files.

  Launch the following command to start the server:

    python3 -m http.server

  Open a web browser and type the following URL:

    http://localhost:8080/

The game should now be running in the browser.

## Code

The code is written in JavaScript and uses the HTML5 Canvas framework to display the graphics.

The project is divided into several classes, each managing a different part of the game:


    The "Sgt" class manages straight segments used to detect collisions between enemies and projectiles.
    The "Pt" class manages points used to create straight segments.
    The "Game" class manages the game as a whole and is used to move from one level to another.
    The "Levels" class manages the different waves of enemies in a level.
    The "Wave" class manages a particular wave of enemies.
    The "Enemy" class manages the enemies themselves, their position, health, and movement.
    The "Decors" class manages the display of background images in the game.
    The "Player" class manages the player's character and their characteristics.
    The "Projectile" class manages the projectiles launched by the player.
There are also several functions used to manage enemy and player shots, as well as collision detection.

## Conclusion

This project is a good introduction to creating video games using JavaScript and HTML5 Canvas. It provides an understanding of the fundamental principles of creating a Tower Defense game. Although the project is relatively simple, it offers a starting point for further exploration into creating video games using these technologies.
