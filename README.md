# React Hangman Game

## Introduction
A classic Hangman game built using **React** and styled with **Tailwind CSS**. The game challenges players to guess a hidden word by selecting letters from the alphabet. Incorrect guesses reveal parts of the hangman figure. The game ends when the word is guessed or the figure is fully drawn. It includes visual feedback and an option to restart the game.

## Project Type
**Frontend**

## Deployed App
- **Frontend**: [https://your-deployed-site.vercel.app](https://your-deployed-site.vercel.app)
- **Backend**: _Not applicable_
- **Database**: _Not applicable_

## Directory Structure

<pre>
react-hangman/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── HangmanFigure.jsx
│   │   ├── WordDisplay.jsx
│   │   ├── Keyboard.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── tailwind.config.js
├── package.json
└── README.md
</pre>

## Video Walkthrough of the Project
📽️ [Attach a 1–3 minute video link showing gameplay and interface]

## Video Walkthrough of the Codebase
📽️ [Attach a 3–5 minute video link explaining React components and game logic]

## Features

- Random word generation
- Interactive letter guessing using an on-screen keyboard
- Visual hangman figure that updates with incorrect guesses
- Game over states (win or lose)
- Restart functionality
- Fully responsive UI with Tailwind CSS

## Design Decisions or Assumptions

- Tailwind CSS was chosen for rapid and responsive UI development
- Game logic is kept in simple React state for ease of understanding
- Word list is local; no external APIs used
- All letters are in uppercase for consistency
- No time limit for the player

## Installation & Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/react-hangman.git

# Navigate into the project directory
cd react-hangman

# Install dependencies
npm install

# Start the development server
npm run dev
