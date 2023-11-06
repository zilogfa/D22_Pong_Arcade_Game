# Pong - Classic Arcade Game

Welcome to the Pong game repository! This codebase is a modern recreation of the classic arcade game Pong, featuring two paddles and a ball, designed for two players.

## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Files in the Project](#files-in-the-project)
- [Setup](#setup)
- [Gameplay](#gameplay)
- [Features](#features)
- [Developer](#developer)

## Introduction

Pong is one of the earliest arcade video games and is a tennis sports game featuring simple two-dimensional graphics. The goal is to defeat your opponent by being the first to score 10 points, a player gets a point once the opponent fails to return the ball to the other side.

## Technologies

This game was created with:
- Python 3.8+
- Turtle Module

## Files in the Project

- `main.py` - The main game file that includes the game loop.
- `paddle.py` - Contains the Paddle class that defines paddle behavior.
- `ball.py` - Contains the Ball class that controls the ball's movement.
- `scoreboard.py` - Contains the Scoreboard class that keeps track of and displays the score.

## Setup

To run this game, Python 3 must be installed on your computer. To start the game, run the following command in a terminal or command prompt:

```bash
python main.py
```

## Gameplay

The game starts immediately upon running the script.
The right paddle is controlled with the Up and Down arrow keys.
The left paddle is controlled with the W and S keys.
Players must move their paddles to hit the ball back to their opponent's side.
If a player misses the ball and it hits their edge of the screen, the opponent scores a point.
The first player to reach 10 points wins the game.


## Features
2-player gameplay
Score tracking and display
Ball speed increases with each hit

## Developer

Ali Jafarbeglou
