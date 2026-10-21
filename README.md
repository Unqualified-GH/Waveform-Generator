# Waveform Generator

## How to get the waveform generator

1. Download the files by clicking on code -> download ZIP
2. Extract the files
3. Go to the Waveform Generator folder
4. Open Waveform Generator.blend

## Creating your own waveform

1. In Waveform Generator.blend, delete the existing waveform by clicking on it and pressing `x`
2. Import the image you want to use by pressing `SHIFT` + `A` and under 'image' select 'mesh plane'
3. Browse to find the image you want to use
4. Once imported, select the image plane and go to the properties panel and select 'modifiers'
5. Click 'add modifier' and select 'geometry nodes'
6. To the left of the 'new' button, click the node icon (hovering over it will show 'browse node trees to be linked')
7. Select 'waveform generator'
8. Click the 'open' button and select the same image you imported again

## Adjusting your waveform

BLUR: controls the smoothness of the waveform
RESOLUTION: controls the density of the points (would not suggest going above 8 on most computers)
POINT SCALE: the size of each individual point
WAVE SCALE: the height of the waveform
MATERIAL: the material to apply to the waveform.
  - you can use this to show the original image on the waveform by selecting the texture of the imported image; this may however require some mapping to be done within the image texture.

## Exporting your waveform

1. The camera is already set up to capture it, however if it does not fit in the frame you can change the frame by going to the properties panel -> data -> orthographic scale
2. Rendering the image will show a purely white outline of the waveform, if you applied a custom texture then go to the compositing tab and at the top select "new compositing node group" (to the right of "compositing nodetree")
