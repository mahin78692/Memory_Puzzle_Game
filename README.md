# Memory Puzzle Game

Enjoy a thrilling and challenging Memory Puzzle Game with immersive background music and satisfying click sounds.

## How to Play

- **Objective**: Match all pairs of cards to win.
- Click on cards to reveal their images.
- Match pairs of identical images to remove them from the board.
- Choose from three difficulty levels:
  - **Easy**: 4x6 grid
  - **Medium**: 6x8 grid
  - **Hard**: 8x10 grid

## Features

- **Immersive Experience**: Background music enhances gameplay ambiance.
- **Satisfying Interactions**: Enjoy delightful click sounds when revealing and matching cards.
- **User-Friendly Interface**: Navigate effortlessly with intuitive buttons for restarting the game and accessing information.
- **Explore Card Details**: Learn more about each card with a simple click.

## Screenshots

![Main Screen](https://github.com/mahin78692/Memory_Puzzle_Game/blob/main/Main%20Screen.png)

![Final Screen](https://github.com/mahin78692/Memory_Puzzle_Game/blob/main/Final.png)

```css
/* Cool CSS for Memory Puzzle Game */

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f0f0f0;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 800px;
  margin: auto;
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}

h1 {
  text-align: center;
  color: #4b0082;
  font-size: 3em;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
}

.game-board {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.card {
  width: 100px;
  height: 100px;
  margin: 10px;
  background-color: #6495ed;
  border-radius: 15px;
  box-shadow: 0 0 10px rgba(100, 149, 237, 0.3);
  cursor: pointer;
  transition: transform 0.3s ease;
}

.card:hover {
  transform: scale(1.1);
  box-shadow: 0 0 15px rgba(100, 149, 237, 0.5);
}

.card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 15px;
}
