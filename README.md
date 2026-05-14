# GDIM 33 In-Class Activities
## W7
### Activity 1

1. Vertex color is stored as data in every vertex of a mesh.
2. Everything between the vertices are just filled in and blended together because of the vertices filling in the empty space.
3. To help artists verify that their mesh data is accurate. Shaders can't be debugged like traditional code because the GPU doesn't work in the same way, so this is a good way to test.
4. Yes. The rash on his ass.
5. UV data, ensure that the model being mapped onto has accurate optimizations.
6. The dot product is in conflict with our ideal lighting for the shiba. We had to multiply it by -1 to get the proper method of lighting so the light shines on the proper side of the model.
7. We have the goal to make the fire effect become more transparent as it goes up. Through setting it to additive we can achieve this effect but trying, say, multiplying, we get a different effect since the values will just be decreasing since values are from 0-1. Making it additive allows us to get an effect where it becomes more transparent as it goes up. Making it multiplicative makes it more transparent overall.
