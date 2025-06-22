Application Overview
This application will be a two-player dice game based on simplified Craps rules. Players take turns rolling two dice, earning points based on the roll and an established number. The game continues until one player reaches a predetermined score, with special rules to handle changes in the leading player.

Core Feature Categories
1. Game Play
1.1 Dice Rolling
1.1.1 On user action, simulate the roll of two six-sided dice.
1.1.2 Display an animation of the dice rolling.
1.1.3 Display the result of each die and their sum prominently.
1.2 Turn Management
1.2.1 Alternate turns between two players.
1.2.2 Indicate the current player's turn visually.
1.3 Rule Enforcement
1.3.1 Initial Roll (No Established Number):
1.3.1.1 If the roll is 7 or 11, the current player scores a point and their turn continues. Reset the established number.
3.1.2 If the roll is 2, 3, or 12, the current player's turn ends without scoring.
3.1.3 If the roll is any other number, that number becomes the "established number."
1.3.2 Subsequent Rolls (Established Number Exists):
1.3.2.1 If the player rolls the established number, they score a point. Reset the established number. Their turn continues.
3.2.2 If the player rolls a 7, their turn ends without scoring.
3.2.3 If the player rolls any other number, their turn continues.
1.4 Scoring
1.4.1 Track the scores of both players.
1.4.2 Apply points based on the game rules.
1.4.2.1 If the leading player scores, add a point to their score.
4.2.2 If the non-leading player scores, subtract a point from the leading player's score.
1.4.3 Ensure that scores do not go below 0.
1.4.4 Manage "leading player" status correctly.
1.4.4.1 If the score is 0, the next player to score becomes the leading player.
1.5 Game Over
1.5.1 Determine the predetermined score before the game starts (see Settings section).
1.5.2 When a player reaches the predetermined score, end the game.
1.5.3 Display a "game over" message indicating the winner.
2. User Interface (UI)
2.1 Player Information
2.1.1 Allow users to enter names for each player.
2.1.2 Display player names and current scores prominently.
2.1.3 Visually differentiate the current player.
2.2 Game Status
2.2.1 Display the established number, if any.
2.2.2 Display messages indicating the outcome of each roll (e.g., "Rolled a 7!", "Crap Out!", "Established Number is 5").
2.3 Controls
2.3.1 A "Roll" button to initiate a dice roll.
2.3.2 Visual indication to the player that it is their turn.
3. Settings
3.1 Player Names
3.1.1 Allow entry of player names.
3.2 Target Score
3.2.1 Allow the user to select or enter the score needed to win the game.
3.2.2 Provide a default target score if none is selected.
3.3 Reset Game
3.3.1 Provide a "Reset Game" button to reset scores to 0 and clear any established number. Retain player names.
4. Persistence
4.1 Player Names
4.1.1 Store player names locally on the device.
4.1.2 Load player names when the application starts.