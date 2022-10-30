# The Snake Game in Go
playable :snake:

![](https://raw.githubusercontent.com/ungtb10d/go-snake/master/screenshot.png)

Snake = white<br>
Food = red

## why, what, how, where
for fun!

inspired by 
- The Coding Train - coding challenge #3: The Snake Game: https://www.youtube.com/watch?v=AaGK-fj-BAM
  - http://thecodingtrain.com/CodingChallenges/003-snake-game-p5.html
- justforfunc #6: Flappy Gopher: https://www.youtube.com/watch?v=aYkxFbd6luY
  - https://github.com/campoy/flappy-gopher 

## Installation
The game depends on the Go Binding of SDL2: https://github.com/veandco/go-sdl2.
This needs to be [installed](https://github.com/veandco/go-sdl2#requirements) first (OS depened).

```
go get github.com/ungtb10d/go-snake
go build
```

## Playing
Run the binary:

```
./go-snake
```

Game stops when snake eats itself and a `GAME OVER!` is printed on the command line.

## Licensing

The code in this project is licensed under MIT license.