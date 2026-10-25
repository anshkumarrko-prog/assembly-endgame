# Assembly: Endgame

A word-guessing game with a programming-language twist. Guess the hidden word before you run out of attempts and Assembly takes over!

## How to play

- Guess the word one letter at a time using the on-screen keyboard.
- Correct guesses reveal every matching letter.
- Each incorrect guess eliminates a programming language.
- You have eight incorrect guesses to solve the word.
- Win the round to celebrate with confetti, or start a new game after it ends.

## Features

- A randomly selected word for each round
- Visual feedback for correct and incorrect guesses
- Programming-language status chips that show your remaining chances
- Win and loss messages, including the word revealed when you lose
- Accessible status announcements for screen readers
- Responsive layout for different screen sizes

## Getting started

### Prerequisites

- [Node.js](https://nodejs.org/) and npm
- [Git](https://git-scm.com/) to clone the repository

### Run locally

```bash
git clone <repository-url>
cd <repository-folder>
npm install
npm run dev
```

Open the local URL printed in your terminal to play.

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Build the app for production |
| `npm run preview` | Preview the production build locally |

## Built with

- React
- Vite
- CSS
- `react-confetti`
- `clsx`
