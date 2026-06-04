# GDIM 33 In-Class Activities
## W10
### Activity 1

Goal(s): Find remaining bugs in core gameplay loop. Game is straight forward enough to where playtesters can get to the end. Means that tutorial makes sense.

New:
Shader graph applies over tiles now, making them change color over time. 

[Link](https://tornadofirewave.itch.io/a-little-star-part-4)
Pass: m3

Notes/Feedback: Add speedrun timer.

### Activity 2

A strategy I would give a student to follow would be definitely defining what the core "toy" the player will be doing and ensuring that is fun. For example, if you're making a turn-based RPG, what do the turns do that would make the player have fun without any particles, juice, etc.? Create an object diagram/bubble diagram of that toy, then once the toy is created and playtested to be fun, expand upon that bubble diagram to build upon that fundamental toy to make that toy even more fun. An example would be that while a platformer can be fun by just moving from platform to platform, ensuring that the core sensation of moving is fun before anything else. Basically taking a note out of Super Mario 64 where the act of moving and jumping around is fun before any puzzles or complications are added. Once that's established, add things on it to make that core gameplay loop more fun. Through this, you can keep the scope small enough to get an achievable prototype easily then can adjust the scope as needed with how far you want to take the game.

### Activity 3

I added a feature that my playtester wanted from my game, which was a timer. They see that this game has a lot of speedrun potential, so being able to keep track of time is really important. In a future commit, I'd like to be able to make it so the timer pauses on every single transition point and resets at each level's new bubble.

Added the timer and also made it reset after every platform for easy time tracking,
