# GDIM 33 In-Class Activities
## W9
### Activity 1

1. Subnautica
2. We decided to pick the texture animation that plays on the camera when the player exits water onto the surface and color of the water when entering new biomes. Our first guess regarding the animation that plays when exiting the swimming state is that when the player reaches a hitbox (ocean ceiling, any point where entering land), they exit the swimming state and a full screen effect plays where an animation of a texture plays. Regarding the color of the water when entering new biomes, we believe it's a post-processing effect that applies and lerps from two different ocean colors depending on their distance from the biome. For the color, it is also affected by position and depth to determine how much of that color is present. 

The major features of the camera transition effect between water and land would be the animated texture. Whether this is a series of frames or a gif, this is likely a full screen effect that plays on the camera material when it is activated.

Regarding the color of the water, we believe it's a post-processing effect that is manipulated based on the player's proximity to a biome border. The closer they are, the more the "water" effect changes.

### Activity 2

<img width="1343" height="736" alt="image" src="https://github.com/user-attachments/assets/37971cf9-97e9-4e9b-907b-e9af4597596b" />

A problem I ran into earlier today when I was adding a feature where I wanted to turn the "doors" and progression platforms to be tiles instead of normal square sprites. I wanted these to look like proper platforms, but it didn't look as natural anymore when a door has to open. The way doors used to work was that once all buttons for an area were pressed, the collider would disable and the object would move either X or Y to get out of the way. However, with this tilemap system I decided to take a new approach to solve this issue of a lapse in immersion, which was to make the sprite fade out. This changed a fair bit of the game's progression, adding a rooms system to make sure the previous room faded out as well whenever the player progresses. The creation of the fading out visual effect solved the issue of immersion as it gives the impression that it's fading out into the night sky, which is fitting for a star based game.
