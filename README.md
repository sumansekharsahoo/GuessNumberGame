# Guess-Number-Game
#page-link: https://sumansekharsahoo.github.io/Guess-Number-Game/
-My first project using JavaScript

About Game:

The player has to guess a number (btw 1-20) that the system has generated randomly. On every unsuccessful guess, the user will be told if:
(i) the guess was "Too high!"- if number entered was larger than answer.
(ii) the guess was "Too low!"- if number entered was smaller than answer.
On every wrong guess, 1 pt will be decducted. The player can play the game multiple times by pressing "Again!". Until we refresh the page, the Highest score scored will be stored.


About Code:

I have used JavaScript to handle click events, selecting and manipulate the DOM elements-
(i) Message Displayed: "Too Low!"/"Too high!"/"Start guessing..."
(ii) background-color: "black"/"green"
(iii) score: deducted by 1 on every wrong guess.
(iv) highscore: increased to present score if previous highscore is lower than current score.
(v) Answer: "?" changed to <answer> on correct guess
