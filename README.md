# Tic-Tac-Toe Game or People also call it as X,O Game

A modern, interactive Tic-Tac-Toe game built with React and Vite. This project demonstrates React fundamentals including state management, component composition, and event handling.

## 🎮 Features

- **Interactive Gameplay**: Classic 3x3 Tic-Tac-Toe with turn-based gameplay
- **Player Customization**: Players can customize their names during the game
- **Real-time Game State**: Visual indicators show whose turn it is
- **Game History**: Complete log of all moves made during the game
- **Win Detection**: Automatic detection of winning combinations
- **Draw Detection**: Recognizes when the game ends in a draw
- **Restart Functionality**: Easy game reset to start a new round
- **Responsive Design**: Works on desktop and mobile devices

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd tic-tac-toe-project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to play the game

## 🎯 How to Play

1. **Start the Game**: The game begins with Player 1 (X) going first
2. **Take Turns**: Players click on empty squares to place their symbol (X or O)
3. **Win Conditions**: Get three of your symbols in a row (horizontally, vertically, or diagonally)
4. **Customize Names**: Click on player names to customize them during gameplay
5. **Restart**: When a game ends, click "Restart" to begin a new game

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 📁 Project Structure

```
tic-tac-toe-project/
├── public/
│   ├── bg-pattern-dark.png
│   ├── bg-pattern.png
│   └── game-logo.png
├── src/
│   ├── components/
│   │   ├── GameBoard.jsx      # Main game board component
│   │   ├── GameOver.jsx       # Game over modal
│   │   ├── Log.jsx           # Move history log
│   │   ├── player.jsx        # Player component
│   │   └── winning-combination.js # Winning patterns
│   ├── App.jsx               # Main application component
│   ├── index.jsx             # Application entry point
│   └── index.css             # Global styles
├── index.html                # HTML template
├── package.json              # Project dependencies and scripts
└── vite.config.js           # Vite configuration
```

## 🧩 Key Components

- **App.jsx**: Main application logic, state management, and game flow
- **GameBoard.jsx**: Renders the 3x3 game grid and handles square clicks
- **Player.jsx**: Displays player information and handles name editing
- **Log.jsx**: Shows the complete history of moves
- **GameOver.jsx**: Modal displayed when game ends
- **winning-combination.js**: Contains all possible winning patterns

## 🎨 Technologies Used

- **React 19.0.0** - Frontend framework
- **Vite 4.4.5** - Build tool and development server
- **ESLint** - Code linting and quality assurance
- **CSS3** - Styling and responsive design

## 🔧 Development

This project uses modern React patterns including:
- Functional components with hooks
- State management with `useState`
- Component composition
- Event handling
- Conditional rendering

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you have any questions or issues, please open an issue in the repository.

---

**Enjoy playing Tic-Tac-Toe! 🎮**
