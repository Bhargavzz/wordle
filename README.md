# Wordle Clone

A modern, responsive Wordle clone built with React. Guess the hidden 5-letter word within six attempts. Each guess provides color-coded feedback to help you solve the puzzle!



##  Features

- **Classic Wordle Gameplay**: Guess the 5-letter word in 6 attempts
- **Visual Feedback**: 
  - 🟩 Green: Correct letter in correct position
  - 🟨 Yellow: Correct letter in wrong position
  - ⬛ Gray: Letter not in the word
- **Keyboard Support**: Type on your physical keyboard or use the on-screen keyboard
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Game Statistics**: Tracks your guessing performance
- **Dark Theme**: Easy on the eyes with a sleek dark interface

##  Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd bhargavzz-wordle
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

##  How to Play

1. The game will randomly select a 5-letter word
2. Type your first guess (must be a valid English word)
3. Press Enter to submit your guess
4. The tiles will change color to show how close your guess was:
   - Green: Letter is correct and in the right position
   - Yellow: Letter is in the word but wrong position
   - Gray: Letter is not in the word
5. Use the feedback to make your next guess
6. You have 6 attempts to guess the word correctly

## 📁 Project Structure

```
bhargavzz-wordle/
├── public/
│   ├── index.html          # Main HTML template
│   ├── manifest.json       # PWA manifest
│   ├── robots.txt          # SEO configuration
│   └── wordle-bank.txt     # Dictionary of valid words
├── src/
│   ├── components/         # React components
│   │   ├── Board.js        # Game board component
│   │   ├── GameOver.js     # Game over screen
│   │   ├── Key.js          # Individual keyboard key
│   │   ├── Keyboard.js     # Virtual keyboard
│   │   └── Letter.js       # Individual letter tile
│   ├── App.css            # Main stylesheet
│   ├── App.js             # Main application component
│   ├── index.js           # Application entry point
│   ├── reportWebVitals.js # Performance monitoring
│   └── Words.js           # Word utilities and game logic
├── package.json           # Dependencies and scripts
└── README.md             # This file
```

##  Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App (one-way operation)

##  Customization

You can customize the game by modifying:

- **Word Bank**: Edit `public/wordle-bank.txt` to add/remove words
- **Styling**: Modify `src/App.css` to change colors and layout
- **Game Rules**: Adjust game logic in `src/Words.js` and component files

##  Browser Support

This app supports all modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

##  Progressive Web App

This Wordle clone is a PWA (Progressive Web App), meaning it can be installed on your device and works offline.



## 🙏 Acknowledgments

- Inspired by the original [Wordle](https://www.nytimes.com/games/wordle/index.html) by Josh Wardle
- Built with [Create React App](https://github.com/facebook/create-react-app)

---

