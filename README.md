# Baja Craps

Welcome to the Baja Craps mobile game project! This is a React Native Expo application for a two-player dice game with a unique scoring system.

This project is managed on [Linear](https://linear.app/brainivy/project/baja-craps-955133f3f6cb).

## Game Rules

The game is a two-player dice game based on simplified Craps rules. Players take turns rolling two dice, earning points based on the roll and an established number.

- **Starting a Turn**: A player starts their turn with no "established number."
- **Rolling a 7 or 11**: If the player rolls a 7 or 11 on their first roll, they score a point, and their turn continues.
- **Crapping Out**: If the player rolls a 2, 3, or 12 on their first roll, their turn ends, and it passes to the next player. No points are scored.
- **Establishing a Number**: If the player rolls any other number (4, 5, 6, 8, 9, 10), that number becomes the "established number."
- **Scoring a Point**: Once a number is established, the player must roll that same number again to score a point. After scoring, the established number is cleared, and their turn continues for a new first roll.
- **Losing a Turn**: If a player has an established number and rolls a 7, their turn ends, and play passes to the next player. No points are scored.

## Scoring System

- Points are tracked centrally. If the leading player scores, a point is added to their lead.
- If the non-leading player scores, a point is subtracted from the leading player's score.
- The score cannot go below 0. If the score is 0, the next player to score takes the lead with 1 point.
- The game is won when a player reaches a predetermined score.

## Getting Started with Development

1.  **Install dependencies**
    ```bash
    npm install
    ```

2.  **Start the app**
    ```bash
    npx expo start
    ```

This will open the Expo developer tools, where you can run the app on an iOS simulator, Android emulator, or on your own device using the Expo Go app.

### Project Structure

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app). It uses file-based routing with [Expo Router](https://docs.expo.dev/router/introduction/). Key directories include:

-   `app/`: Contains all the screens and routes for the application.
-   `components/`: Shared components used across the application.
-   `constants/`: Global constants like colors and environment variables.
-   `hooks/`: Custom hooks for shared logic.

