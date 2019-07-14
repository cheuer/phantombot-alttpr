# phantombot-alttpr
This is a script for PhantomBot that lets you run a guessing game for A Link to the Past Randomizer.

## Main Functions

* !bk or !bk start
  Starts the Ganon's Tower Big Key guessing game

* !bk stop
  Ends the guessing period, no more guesses in chat will be recorded
  
* !bk <number>
  Declares one or more winners as the chat users with the exact right guess or the closest to it. Preference is given to the number lower than the correct answer in case of a tie. Also prints the leaderboard.
  
* !bb
  Same as !bk, but for blue ball attacks from Agahnim
  
## Utility Functions
All of these can be preceded by !bk or !bb, doesn't matter

* !bk cancel
  Cancels the guessing game and deletes the saved guesses. Useful if you started it accidentally, or want to start over for some reason.
  
* !bk print
  Prints the leaderboard
  
* !bk reset
  Resets the leaderboard
  
* !bk set <name> <number>
  Sets a specific number of wins on the leaderboard for a user
  
* !bk timer
  Shows the current timer setting
  
* !bk timer <number>
  Sets the timer length, in seconds. This will automatically end the game after the given number of seconds. This setting persists across games, so you can set it and forget it. You can still call !bk stop to stop the timer early.
