# rock-paper-scissors

A Rock Paper Scissors game built with HTML, CSS and JavaScript.
You play against the computer, which picks a random move.
The score is saved in the browser (localStorage), so it is still there after refreshing the page.

## Features

- Play rock, paper or scissors against the computer
- Shows the result (win, lose or tie) and both moves
- Score saved between visits
- Reset button to set the score back to 0
- Modern design with a gradient background and a glass-style card
- Responsive: works on desktop and phones

## How to run

Download the files and open `index.html` in your browser.
No installation needed.

## How to play

1. Click **Rock**, **Paper** or **Scissors**.
2. The computer picks a random move.
3. The result and the score update on the page.
4. Click **Reset score** to start again from 0.

## Rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
- Same move on both sides is a tie

## Project structure

```
rock-paper-scissors/
├── index.html   # the page and the buttons
├── style.css    # the design and layout
├── learn.js     # the game logic, score saving and display
└── README.md
```

## Technologies

- HTML5
- CSS3 (flexbox, gradients, transitions, media queries)
- JavaScript (DOM, localStorage)
