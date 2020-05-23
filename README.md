# Normal mapping, procedural bump mapping and reflection mapping

The background is part of a skybox. A skybox is used to show the supposedly-infinitely-faraway
surroundings of a 3D scene. It is made of a 3D cube texture-mapped with an environment map (a
cubemap), and the cube encloses the 3D scene and the camera.

The cube on the left side of the sample image is rendered with a brick texture map and a corresponding
normal map. The color texture map is used to provide the ambient and diffuse material for the Phong
lighting computation.

The cube on the right is rendered with a wood texture map, where it provides the ambient and diffuse
material for the Phong lighting computation. The cube also has an array of hemispherical mirrors,
and these mirrors reflect the environment (same environment map as used for the skybox). 
The mirrors are produced using procedural bump mapping, and their reflection of the environment is
produced using reflection mapping with a cubemap.

<img src=https://github.com/Futuramistic/BumpMappingAndTexturing/blob/master/images/textures.PNG>
