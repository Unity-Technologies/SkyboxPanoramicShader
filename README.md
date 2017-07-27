# Panoramic 2D and 3D Video
## Panoramic Shader
This Skybox Panoramic Shader will help display 180 and 360 degree videos in either equirectangular (latitude longitude) or cubemap (6 frames) layouts as a scene backdrop.

A video in one of these formats can be played by the Video Player component and output to a Render Texture (ideally of the exact same resolution). That texture can then be fed to the Panoramic Shader for proper mapping onto the scene’s Skybox.

This work will ship as part of Unity 2017.3.

## 3D 180/360 Content
When Player Settings include “Virtual Reality Support”,  the Skybox Panoramic Shader also offers 3D (stereo) support for 360/180 degree content. The right and left eye content are taken either from the right and left sides of the video by setting the shader options to Side by Side, or, from the top and bottom of the video with the Over Under option.

## Documentation
Detailed instructions on how to use this shader are available [here](https://docs.google.com/document/d/1JjOQ0dXTYPFwg6eSOlIAdqyPo6QMLqh-PETwxf8ZVD8)

## Feedback and Bug Reporting
Until this feature is officially shipped, please submit your feedback in [this thread in the Unity VR forum](https://forum.unity3d.com/threads/how-to-integrate-360-video-with-unity.485405/)
