# ULA-videogame-programming
Repositorio para asignaciones de Programación de Videojuegos

# Changelog: 
## V1 28-01.2023
  
  * pong.c
    * Created `is_inside()` function to check if the ball is inside of the Paddle Height https://github.com/JAAG4/ULA-videogame-programming-1/blob/4e81c9ac8fe07fbf2eb94f6da278b0058e6ee027/pong.c#L20-L28
    * Added AI controls https://github.com/JAAG4/ULA-videogame-programming-1/blob/4e81c9ac8fe07fbf2eb94f6da278b0058e6ee027/pong.c#L124-L140
    * Added Custom "CPU Player Won" 
    * Added Paddle Behaviour to only move when `if (pong.ball.vx < 0)` 
    * Added "Match Point!" Text when A player is about to win https://github.com/JAAG4/ULA-videogame-programming-1/blob/4e81c9ac8fe07fbf2eb94f6da278b0058e6ee027/pong.c#L250-L253
* paddle.c paddle.h
    * Added Custom Color Rendering
