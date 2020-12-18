# Rayblocks
Cast rays on blocks in a 2D world and render this as 3D. This project is focused on how to render a semi-3D world, I spent minimal time on other aspects such as the textures, maps or actual gameplay. I used SDL2 as an interface to the GPU.

The world is represented by a seperate floor, ceiling, wall and collision 2D list, this way we can have different floor and ceiling textures on the same cell as well as walls which you can walk through or empty cells (possibly with sprites) which you can not walk through. The sprites are saved seperately in a list specifying their location and texture.  

![](misc/showcase.gif)

## Credits
I used [this](https://lodev.org/cgtutor/raycasting.html) amazing tutorial on rendering and I got all the textures from [here](http://areyep.com/RIPandMCS-TextureLibrary.html), except for the sky, I made that one myself!
