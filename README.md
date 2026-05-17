# Quick Quiz App

A browser-based quiz game built with HTML, CSS, and JavaScript.

## Files

- `index.html` - Home page with links to play and view high scores.
- `game.html` - Quiz game page that loads trivia questions.
- `end.html` - End screen for saving your score.
- `highscores.html` - High scores page.
- `game.js` - Quiz game logic, question loading, scoring, and navigation.
- `end.js` - Score submission and high score save logic.
- `highscores.js` - Displays saved high scores.
- `app.css`, `game.css`, `highscores.css` - Styling for the app pages.
- `questions.json` - Example question file (not currently used by the live game).

## How to use

1. Open `index.html` in your browser.
2. Click **Play** to start the quiz.
3. Answer the questions, then submit your name on the end screen.
4. View saved high scores on the **High Scores** page.

## Notes

- The game currently loads questions from the Open Trivia Database API.
- High scores are stored in browser `localStorage`.
- Navigation links are relative so the app works when opened locally from the project folder.
