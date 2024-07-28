# Game of 24

## Demo

https://walty8.github.io/game-of-24/


## How to play?

1. open the website, a random question will be generated
2. use the rules of [game of 24](https://en.wikipedia.org/wiki/24_%28puzzle%29) to solve the question. In short, the four numbers in the question are used, once and only once, to get the result of `24` with basic math operators: `+, - , * , /`. There is no limit on the usage of operators. E.g. for `2, 4, 6, 8`, one of possible solution is `((8*4)-6)-2`. 
3. if you failed to figure out the solution, click 'show partial answer' or 'show answer'.
4. click 'next question' to get to the next one 
5. change the value of text input and click 'show answer' to solve a custom question.


## Features
1. every question can be solved (algorithm by [auntyellow](https://github.com/auntyellow/24))
2. all possible distinct solutions will be shown
3. the site can work offline after opened once (using service worker)
4. responsive layout, work on mobile phone

## Why build this
Just want to play the game with my kid any time. It's especially useful to kill the time on a flight :) 

There is no button to click when one player figures out the solution, he/she only needs to shout it out (or say it lightly).
