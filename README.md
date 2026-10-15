# MG3
## Devlog
1. I checked the variables in the Inspector. The default value of a float is 0, the default value of an int is 0, the default value of a bool is false, and the default value of a string is empty.
2. The Update() method is called automatically by Unity every frame. I do not need to call it myself. As long as the script is active, Unity keeps running Update() while the game is playing.
3. TimerText uses Timer to control the game time. At the beginning, it starts the timer. In Update(), it checks the time every frame and changes the timer text. When the time is finished, the game goes to Game Over.
https://qingw7.itch.io/mini-game3
## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
