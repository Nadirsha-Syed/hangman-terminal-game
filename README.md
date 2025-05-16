# 🕹️ Hangman Terminal Game

A classic Hangman word-guessing game built in Python. This game runs in the terminal and features ASCII art, input validation, and randomly selected challenging words. It's a fun way to practice Python basics like loops, conditionals, lists, and sets.

# 📸 Preview
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 _
| |
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |
                   |___/

The solution is flyby.
Guess a letter: a
❌ The letter 'a' is not in the word. Lives left: 5

Word: _ _ _ _ _

  +---+
  |   |
  O   |
      |
      |
      |
=========

Guess a letter: f

Word: f _ _ _ _

  +---+
  |   |
  O   |
      |
      |
      |
=========

Guess a letter:
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🚀 Features

- ✅ 100+ random words
- ✅ ASCII art to visualize progress
- ✅ Tracks correct and incorrect guesses
- ✅ Input validation (only single letters)
- ✅ Displays win/loss message and the correct word

## 🛠️ Requirements

- Python 3.x

## 🔧 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Nadirsha-Syed/hangman-game.git

2. **Navigate the project directory**:
   cd hangman-game
3. **Run the game**:
   python hangman.py

## ▶️ How to Use

Once you run the game, a random word will be chosen, and each letter in that word will be hidden by underscores.

You'll be prompted to guess one letter at a time.

- If your guess is correct, the letter will appear in the correct position(s) in the word.
- If your guess is incorrect, you'll lose one of your remaining attempts (lives), and a part of the hangman will be drawn.

You’ll continue guessing letters until you either:
- Complete the word (and win the game), or
- Run out of lives (and lose the game).

Be careful not to repeat guesses — only one letter per turn is allowed!


## File Structure
  hangman-terminal-game/
  │
  ├── hangman.py        # Main game script
  ├── README.md         # Project documentation


---

Let me know if you want this to support **replay mode**, **GUI with Tkinter**, or a **web version** too!


