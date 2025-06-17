# number-guessing

## 🎯 Number Guessing Game

A fun and interactive command-line game built in Python where the user has 7 chances to guess a randomly selected number between two bounds.

![Python](https://img.shields.io/badge/Python-3.6%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📋 Game Overview

The computer randomly selects a number between a user-defined lower and upper bound. The player has **7 attempts** to guess the correct number. Hints like *"Too high"* or *"Too low"* are provided after each guess.

---

## 🕹️ Sample Output

```
Hi! Welcome to the Number Guessing Game.
You have 7 chances to guess the number. Let's start!

Enter the Lower Bound: 1
Enter the Upper Bound: 50

You have 7 chances to guess the number between 1 and 50. Let's start!
Enter your guess: 25
Too high! Try a lower number.
Enter your guess: 15
Too low! Try a higher number.
...
Correct! The number is 19. You guessed it in 5 attempts.
```

---

## 📁 Project Structure

```
number-guessing-game/
├── number_guessing_game.py   # Main game script
├── README.md                 # Project documentation
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/number-guessing-game.git
cd number-guessing-game
```

### 2. Run the game

```bash
python number_guessing_game.py
```

No additional dependencies required — works with standard Python libraries.

---

## 🔑 Features

* User-defined number range
* 7 limited attempts
* Hints after every wrong guess
* Clean and interactive interface
* Minimal and beginner-friendly code

---

## 💡 Learning Concepts

* Random number generation
* Conditional logic and loops
* User input handling
* Basic error-proof logic for guessing games

---

## 🔄 Possible Enhancements

* Add input validation (e.g., check if user entered a number)
* Allow custom number of attempts
* Implement score tracking
* Create a GUI version using Tkinter or web version with Flask

---

## 📄 License

This project is for educational purpose only.
