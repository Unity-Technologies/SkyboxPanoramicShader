# Panoramic 2D and 3D Video
## Panoramic Shader
This Skybox Panoramic Shader will help display 180 and 360 degree videos in either equirectangular (latitude longitude) or cubemap (6 frames) layouts as a scene backdrop.

A video in one of these formats can be played by the Video Player component and output to a Render Texture. That texture can then be fed to the Panoramic Shader for proper mapping onto the scene’s Skybox.

## 3D 180/360 Content
When Player Settings include “Virtual Reality Support”,  the Skybox Panoramic Shader also offers 3D (stereo) support for 360/180 degree content. The right and left eye content are taken either from the right and left sides of the video by setting the shader options to Side by Side, or, from the top and bottom of the video with the Over Under option.

## Documentation
Detailed instructions on how to use this shader are available [here](https://docs.google.com/document/d/1JjOQ0dXTYPFwg6eSOlIAdqyPo6QMLqh-PETwxf8ZVD8)
