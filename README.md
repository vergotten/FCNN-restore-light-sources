## FCNN-restore-light-sources
using fully-convolutional neural network in tasks of restoring optical properties 

<p align="center">
  <img width="460" height="240" src="https://user-images.githubusercontent.com/20153742/68948337-b7febc80-07c8-11ea-8998-15bd747954bb.PNG">
</p>

Due to the rapid development of virtual and augmented reality systems the solu-tion of the problem of formation of the natural illumination conditions for virtual world objects in the real environment becomes more relevant. To recover a light sources position and their optical parameters authors propose to use the fully-convolutional neural network (FCNN), which allows catching the 'behavior of light' features. The output of the FCNN is a segmented image with luminance lev-els. As an encoder it was taken the architecture of VGG-16 with layers that pools and convolves an input and wisely classifies it to one of a class which characterizes its luminance. The image dataset was synthesized with use of the physically correct photorealistic rendering software. Dataset consists of HDR images that were rendered and then presented as image in color contours, where each color corresponds to the luminance level. Designed FCNN decision can be used in tasks of definition of illuminated areas of a room, restoring illumination parameters, analyzing its secondary illumination and their classification to one of a luminance level, which nowadays is one of a major task in designing of mixed reality systems to place a synthesized object to the real environment and match the speci-fied optical parameters and lighting of a room. 

## Achieved results:

<p align="center">
  <img width="460" height="260" src="https://user-images.githubusercontent.com/20153742/68948336-b7febc80-07c8-11ea-820d-75ba92997d0a.PNG">
</p>

The full paper via link http://ceur-ws.org/Vol-2344/short1.pdf
