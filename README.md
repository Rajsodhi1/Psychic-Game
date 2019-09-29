# Psychic-Game
Here is a simple in-browser guesssing game. The object is to see if you can guess the random letter the computer has chosen. You only have 9 total guess otherwise you lose. Wins, losses, letters guessed and guesses remaining are displayed for the user.

screenshot of website:
![site](https://raw.githubusercontent.com/Rajsodhi1/Psychic-Game/master/delpoyedsite.png)

This code snippet shows how the app get a random letter for you to guess. FIrst we have an array with all the possible guesses(the letters of the alphabet).Using math.random produces a random number, math.floor rounds that to a whole number. We then multiply that by the length of our possible letter array. All of this will produce a number that will correspond to the index number of a letter in that array. That letter is the one you have to guess. 
![snippet](https://raw.githubusercontent.com/Rajsodhi1/Psychic-Game/master/snippet.png)

Learning points:
* This was good practice for basic HTML layouts.
* This assignment was also great for utilizing JavaScript logic. One take away from this assignment was that in the future I should get in the habit of keeping my JS logic in a separate .js file. While this was a pretty simple app with minimal code, things could get very messy as the app complexity goes up so it is good practice to just keep things separated.




Technologies used:
The admittedly simple layout was made using HTML, but you can dress it up using the Bootstrap library as well as CSS techniques.
The game mechanics were made using Javascript. 

Play the game here:
 https://rajsodhi1.github.io/Psychic-Game/.

 Find my repository here:
  https://github.com/Rajsodhi1