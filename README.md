# GDIM 33 In-Class Activities
## W1
### Activity 1
[Inspo Board](https://canva.link/oy5ldpkuvjbhxz5)

1. A pattern that emerges from my inspiration sources definitely stem from a more relaxed, atmospheric game that has a consistent goal, even if it's the not the most high-stakes goal. One thing that I notice has captured my attention significantly during my inspiration process was atmospheric lighting, even leaking into enemy designs as I drew inspiration from Chinese Drone shows. I definitely had a fascination with side scrollers or more metroidvania-esk aesthetics, with a bit of action but most of the player experience centering around exploration.

    Brandon Johnston and I's taste in games seemed to have somewhat little overlap, but one thing we shared is the aesthetic of space worlds and slower paced exploration. While mine was an attempt to keep things more leisurely and allow for wonder to come out as the environment unveils itself to the player, his was to provide a sense of fear from being unable to escape from enemies.

    The LA's taste in games was more related to fighting games and rhythm games. It was the matter of accountability and agency within the games that made them particularly interested in these genres and their effects on them. Being able to feel in control was the key aspect, and I feel like that would be able to emulate in my own planned game through the ability to explore however you want and approach different tasks as they embark on their long journey with meaningful play coming from the decisions they made during their journey to help an NPC or progress further. We also shared an interest in rhythm games, and I recently added a plan to incorporate rhythm game-inspired QTEs for the combat.


2. Please keep the proper list format.


### Activity 2
<img width="1920" height="1080" alt="Genre (1)" src="https://github.com/user-attachments/assets/a8d27f9c-585e-42ec-b8f4-20a2989e4052" />


## W2
Activity 1

<img width="962" height="657" alt="image" src="https://github.com/user-attachments/assets/6b95e27e-2b74-4e77-81f1-f3331a2e5a49" />

Activity 2
1. Why is it advantageous to save the event name for the explore-to-dialogue state transitions as Scene variable ("clickNpcEventName")?

There is a reliable way to get the correct name to call dialogue transitions for separate NPCs within the scene. Also for other graphs to call the variable, not just the state machine.

2. Describe how using at least one Debug.Log() node helped you test your Graphs at an intermediate step.

Utilizing the mouseclick debug log helped me understand that the key press for the click wasn't the source of the issue, but the issue lied within calling the dialogue panel as I debugged.

3. Is the Set Cursor Lock State relevant to your Vertical Slice? Why or why not?

Yes. It is a 2D platformer that's beauty comes from the environment, so it should be locked and not visible during exploration. However, within the pause menu, it should be unlocked so the player can navigate the pause menu options.

4. Is the concept of a "game state" relevant to your Vertical Slice? Why or why not?

It's very relevant. A clear usage of the game state is between dialogue and exploration, not too different from the current activity. The player must not be able to move during dialogue and have certain key presses mean something else to progress dialogue rather than attacking in exploration.
