# Cricket Game

This project is a simple web-based Cricket game where users can choose between Bat, Ball, and Stump to play against the CPU. The score of wins, losses, and ties is stored in the local storage.

## Features

- User can enter their name.
- Three game choices: Bat, Ball, and Stump.
- Score tracking for wins, losses, and ties.
- Scores are stored in local storage to maintain state across sessions.
- Responsive design for various screen sizes.

## Files

- `index.html`: The main HTML file containing the structure of the web page.
- `style.css`: The main CSS file for styling the web page.
- `responsive.css`: The CSS file for responsive design.
- `script.js`: The main JavaScript file for game logic and interactivity.

## Instructions

1. Clone the repository or download the zip file.
    ```sh
    git clone https://ahmadaltamash.github.io/MiniProject_Cricket/
    cd cricket-game
    ```
2. Open `index.html` in your web browser.

## How to Play

1. Enter your name in the text box and press Enter.
2. Click on one of the three buttons (Bat, Ball, Stump) to make your choice.
3. The CPU will randomly choose one of the three options.
4. The result of the match (Win, Loss, or Tie) will be displayed.
5. The score will be updated and stored in the local storage.
6. To reset the score, click on the "Clear Score" button.

## Code Structure

### HTML (`index.html`)

- Contains the main structure of the game including the name input, score display, game buttons, and clear score button.

### CSS (`style.css` and `responsive.css`)

- Styles the game elements and ensures responsive design for different screen sizes.

### JavaScript (`script.js`)

- Contains the game logic, including:
  - CPU's random choice function.
  - Event listeners for user choices.
  - Score updating and storing in local storage.
  - Displaying the result of each match.
  - Clearing the score and resetting the game.

## Responsive Design

- The game is designed to be responsive and works well on various screen sizes. Media queries are used in `responsive.css` to adjust the layout and styles for smaller screens.

## Example Usage

1. Open the game in your browser.
2. Enter your name in the input box.
3. Click on any of the game options (Bat, Ball, Stump) to start playing.
4. View the result and updated score.
5. Clear the score using the "Clear Score" button if needed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

[Altamash Ahmad](https://github.com/AhmadAltamash)

Feel free to customize this readme file further according to your preferences and additional information.
