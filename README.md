# GDIM 33 In-Class Activities
## W5
### Activity 1

Step 1: Create the hierarchy assets necessary for the timeline to activate properly.
1. Create the background asset that will travel alongside the player as they progress. Attach a sprite renderer, animator, and a script that tracks how much distance it's moved until it needs to be destroyed. The script will also move the background asset at the same speed as the player movement until it reaches a certain X value differing from it's starting position.
2. Create an animation clip that plays during the actual animation and assign it within the animator.
3. Create a collider that will serve as a trigger for the background asset to begin following the player. A script begins the timeline and tracks if the player is the one that ran into the collider by utilizing the player tag.
4. Create a director asset that holds the playable director component.
5. Test that the collider script fires a debug log that the sequence should be triggered.

Step 2: Create the timeline
1. Go into the asset library and create a timeline asset.
2. Drag the animation clip into the timeline, resize if fitting in additional animations.
3. Assign the timeline asset to the playable director object and the collider script (so it can identify the timeline to play the animation sequence)
4. Test by playing the game, running into the collider, and seeing if the object follows the player up until a point where it gets destroyed (where it would be hidden behind a wall in practice).

Achievement:
I created a timeline asset that allows me to activate objects that will play within the background as the player progresses through a level. The object will follow the player up until a certain X value that differs from it's starting position, reaching a certain point of world space then destroying itself. This will likely be able to allow me to create environmental animations in the background that will aid me in creating an immersive environments, animals moving in the background, stars twinkling or exploding at certain points once running into certain colliders, or when a player moves a certain amount to trigger a background animation. By utilizing a timeline, I can make these animations occur in sequence, while still allowing the player to maintain the immersion of exploring on their own through usage of colliders rather than freezing the player in a cinematic. Destroying the object at the end may have not been necessary as opposed to hiding the object and having it start at the beginning in case the player comes back to the collider and progresses through the area again, but it can also have an effect of the world being alive if the sequence only occurs once.
