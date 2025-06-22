Build a type of Craps game.  The game will be similar to the normal Craps game, but will follow the following set of rules to keep score between two alternating players rolling the two dice.

Rules: 
- A user gets a point if they roll a 7 or 11 on their roll if there is no established number.  When the player gets a point from this they then start over with no established number and it remains their turn.
- A user can "Crap Out" if they role a 2,3, or 12 on their role if there is no established number.  When a user "Craps Out" they do not lose a point but the turn changes to the next player.  The next player does not receive a point.
- If there user doesn't role 7 or 11 and if they don't role 2, 3, or 12 when no number is established then the number they have rolled becomes the established number.  
- Once there is a established number, the user must roll that same number again to get a point.  If they roll a 7 before they role that number again then the turn changes to the next player and neither player receives a point.  If they role the established number then the user gets a point and the number resets to no established number.
- Points are applied by either adding a point to the leading player if they score a point or taking a point from the leading player if the non-leading player gets the point.
- The game is over when a player reaches a predetermined score.
- The score should not go below 0.  When the score is 0 then the next player to get a point takes the lead and becomes the leading player

The game should show an animation of two dices rolling when the user hits "Roll" and this should result in a random combination of dice faces showing the result of the roll.  It should allow users to enter names for each player and display them with what points the user has.  The users names should be retained if the game is reset either by the app being restarted or by a user choosing to reset the scores.  When a user has won the game it should display that the games has ended and which user won.

## Platforms
- [x] iOS
- [ ] iPadOS
- [ ] tvOS
- [ ] Android
- [ ] Android Tablet
- [ ] AndroidTV
- [ ] Responsive Web
- [ ] API Service
- [ ] Background Service
- [ ] Data Service
