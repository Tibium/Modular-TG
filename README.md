# Modular-TG
Modular Terrain Generator for Unity in C Sharp

This allows you to edit from unity the following Variables:
- Width
- Height
- Scale
- Offset Z
- Terrain Material used
- Octaves
- Persistence
- Lacunarity
- Offset (X,Y)
- Base Height
- Object Prefabs (Rocks,Trees,Etc)
- Number of objects spawned


Variables Explained:

Width & Height: These parameters define the dimensions of the terrain. The terrain will be generated over a grid of Width x Height.

Scale: This parameter determines the scale of the noise. A smaller scale will result in larger, more spaced-out features on the terrain, while a larger scale will produce finer, more detailed features.

Offset Z: This could be a way to shift or slide the noise generation along the Z-axis. By changing this value, different slices or sections of the noise can be sampled, resulting in a varied appearance of the terrain.

Terrain Material: Specifies the visual appearance or texture of the terrain.

Octaves: This refers to the number of layers of noise that will be combined. Multiple octaves produce more detailed terrains with both large-scale and small-scale features.

Persistence: Determines how much each octave contributes to the final shape of the terrain. A value less than 1 will reduce the impact of higher octaves, making the terrain smoother. A value greater than 1 will make the terrain rougher.

Lacunarity: A higher lacunarity value will increase the frequency with each octave, resulting in more detailed terrain.

Offset X & Y: These are used to pan or slide the noise generation along the X and Y axes. This allows the user to sample different parts of the noise space and achieve various terrain looks.

Base Height: This will set height value for the terrain, ensuring that even the lowest points of the terrain do not go below this value.

Object Prefabs: This is a list where you can add objects or assests that will be automatically placed on the terrain.

Number Of Objects To Spawn: This is the number of objects (from the Object Prefabs list) that the script will attempt to spawn or place on the generated terrain.

