# PostProcessingTextureOverlay

Unity Post Processing Layer for Textures.

## Requirements
1. You need to use a Scriptable Render Pipeline (SRP) in order to use this package (see: https://github.com/Unity-Technologies/ScriptableRenderPipeline/wiki/Installing-LWRP-into-an-existing-Project)
2. You need to have the post processing for the scriptable render pipeline (see: https://www.youtube.com/watch?v=Ts2F2SxeRSY)

_The easiest way to meet the requirement is to select the LWRP with a sample scene during the creation of a new project_

## Usage
Minimum Import: /Scripts/*
1. Just select the gameobject with the post processing volume attached to it.
2. Click on "Add Effect" > "DitzelGames" > "Texture Overlay"
3. Activate the texture and choose it. You can either use a static image or a render texture.

## Options
- Tiling: You can set the width/height of an image - default is full screen
- Offset: You can set the pivot point of the image - default is full screen
- Keep Offset Ratio: You can set the aspect ratio depending on your input texture
- Alpha Is Transparent: Toggle Transparency

## Links:
Github: https://github.com/ditzel/PostProcessingTextureOverlay
Youtube: https://www.youtube.com/c/ditzelgames