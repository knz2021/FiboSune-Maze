Fibo-Snake Maze

A browser-based educational maze game combining Snake, Fibonacci-style arithmetic, and enemy chasers.
Play directly in any modern web browser.

🎮 Game Overview

Fibo-Snake Maze is a maze-based snake game where the player must solve incrementing arithmetic questions while avoiding enemies.
Each correct answer appears as food inside the maze, along with several incorrect choices. Eating the correct food increases your score and generates the next question.

The maze, enemies, and food positions are randomized every game.

✨ Features

Three difficulty modes: Easy, Normal, Hard

Auto-generated mazes with dynamic pathways

Arithmetic sequence puzzle (1 → 1 → 2 → 3 → 5 → 8 → … style progression)

Three independent enemy snakes with different movement speeds

Touch and keyboard controls

Local ranking system (scores saved per difficulty)

Responsive design (works on mobile and desktop)

🧠 How the Question System Works

The game uses a simplified Fibonacci-like rule:

First question starts with:

Current value = 1

Add value = 1

Each time you answer correctly:

Add value increases by +1

Next result = current value + add value

Example progression:
1 → 1 → 2 → 3 → 5 → 8 → 13 …

Your goal is to eat the pink tile with the correct number.

🕹️ Controls
Keyboard

Arrow Keys: Move the snake

Touch (Mobile)

Swipe in any direction to move

⚠️ Game Over Conditions

You lose if:

You eat the wrong number

You collide with a wall

You hit an enemy snake

After game over, you can:

Enter a nickname

Save your score

View rankings

Play again

📁 Files

This project consists of a single file:

index.html — contains all game logic, CSS, and HTML in one page.

To run it, simply open index.html in any browser.

🚀 How to Play Locally

Download index.html

Double-click the file to open it in Chrome, Safari, Firefox, etc.

Choose a difficulty and start playing

No server or installation required.
