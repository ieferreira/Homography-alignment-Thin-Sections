## Using Homography to align a video of thin sections taken with a smartphone (moto g6) in a petrographical microscope

The idea was to test the homography algorithm given by open-cv to align a rotating image of a thin section (main case: pleochroism of phlogopite, but uploaded another videos just to see how far it could go).

The program takes a video, divides into frames, aligns the frames and then using a Hough transform to discard useless images (see below for an example); finally it merges the aligned images into a gif.

## Gif without homography

![](Gif_Sin_Homografia.gif)


## Gif with homography applied

![](Gif_Con_Homografia.gif)



