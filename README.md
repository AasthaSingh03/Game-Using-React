#  Tic-Tac-Toe Game (React + TypeScript + Vite)

A simple and responsive Tic-Tac-Toe game built with **React**, **TypeScript** Play the classic Xs and Os game in your browser with a clean and interactive UI.

## Project Structure

tictactoe/
├── public/
│ └── vite.svg
├── src/
│ ├── assets/
│ ├── App.tsx # Main game component
│ ├── Square.tsx # Individual square component
│ ├── main.tsx # Entry point
│ ├── App.css # Game-specific styling
│ ├── index.css # Global styles
│ └── vite-env.d.ts # Vite TypeScript declarations
├── index.html
├── package.json
├── tsconfig.json
└── vite.config.ts

## Technologies Used

- React
- TypeScript
- CSS for styling

## Install dependencies

npm install

## Run the development server

npm run dev

## How to Play
-Players alternate placing X or O on the 3x3 board.
-The first to get 3 in a row (horizontally, vertically, or diagonally) wins.
-If all cells are filled without a winner, it's a draw.
-Refresh or use a "Restart" button (if implemented) to play again.

## License
This project is licensed under the MIT License.
