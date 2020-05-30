# Crystal Palace Shader

![Crystal Palace: Screenshot](https://user-images.githubusercontent.com/25379378/83323172-db8fce80-a211-11ea-9fd8-990728d9aeb4.png)

This shader applies stereo raymarching to render a variant of the mandelbox function
https://en.wikipedia.org/wiki/Mandelbox#Generation with camera position and time dependant features. As the geometry projects a different shape into the 3-dimensional vector space from each camera angle, we can achieve a sense of visualization for this higher dimensional object in virtual reality. An uncleared color buffer is stacked with multisampling anti-aliasing and reflection captures to produce a crystal-like material.

Interactive demo (Use the spacebar or XR controller to move forward):
