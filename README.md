# Blackjack App

A simple object oriented Blackjack game built in Java. This project models the core mechanics of Blackjack including card dealing, hand scoring, user decisions, and dealer logic. It is designed as a clean console based application that demonstrates strong fundamentals in Java classes, methods, and game flow.

## Features

The app includes several core features that reflect the rules of Blackjack.  
Players receive two cards and can choose to hit or stand.  
The dealer reveals cards and draws until reaching the minimum threshold.  
The program evaluates the final hands and announces the result.  
The deck, card values, and game structure follow standard Blackjack logic.

## How It Works

The game creates a deck of cards and shuffles it.  
Cards are dealt to both the player and dealer.  
Player choices are read from console input and processed.  
The dealer plays after the player stands.  
Scores are calculated and compared to decide the winner.  
The game ends by showing both hands and declaring the outcome.

## File Overview

### `BlackJack.java`

Contains the full game loop and handles user interaction, card dealing, dealer behaviour, and scoring.

### `App.java`

Contains the main entry point for running the program.


javac App.java BlackJack.java
java App```
