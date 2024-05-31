# Dev-Manav-Asur

**Dev-Manav-Asur** is an interactive web-based game inspired by the classic Rock-Paper-Scissors, with a unique twist. In this game, players choose between three characters: Dev, Manav, and Asur, each with distinct strengths and weaknesses. The objective is to outsmart the computer by making strategic choices to win the maximum number of rounds.

## Gameplay Mechanics

- **Choices:**
  - **Dev:** Symbolizes a divine entity.
  - **Manav:** Represents a human being.
  - **Asur:** Embodies a demonic force.

- **Winning Conditions:**
  - Dev wins against Asur and Manav.
  - Manav wins against Asur but loses to Dev.
  - Asur loses to both Dev and Manav.

## Game Flow

1. **User Selection:** The player selects one of the three options by clicking on the corresponding image.
2. **Computer Selection:** The computer randomly selects its choice from the three characters.
3. **Result Evaluation:** The game compares the user’s choice with the computer’s choice to determine the winner of the round.
   - If both choices are the same, the round is a draw. points 0.
   - If the user’s choice defeats the computer’s choice, the user wins the round. points : user 1.
   - If the computer’s choice defeats the user’s choice, the computer wins the round points :computer 1.
4. **Score Tracking:** The scores for both the user and the computer are updated and displayed on the screen.
5. **Round Limit:** The game continues for a total of 6 rounds. After 6 rounds, the game displays the overall winner based on the highest score.
6. **Reset Mechanism:** After declaring the final winner, the game resets automatically, allowing players to start a new game.

## Technologies Used

- **HTML:** Structures the content and layout of the game interface.
- **CSS:** Styles the game elements to create an engaging user experience.
- **JavaScript:** Implements the game logic, handles user interactions, and updates the game state dynamically.

## Project Files

- **index.html:** Contains the structure of the game interface, including headings, images, and score display sections.
- **style.css:** Provides styling for the game interface, including layout, colors, and fonts.
- **script.js:** Implements the game logic, including user input handling, random computer choice generation, score updating, and game reset functionality.

## Usage

Click on one of the three options (Dev, Manav, Asur) to make your move and see if you can outsmart the computer. The game will keep track of scores and announce the winner after 6 rounds.

