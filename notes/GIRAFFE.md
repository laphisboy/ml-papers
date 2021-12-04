# GIRAFFE
https://m-niemeyer.github.io/project-pages/giraffe/index.html

### NeRF + Compositional 3D Scene Representation + Generative Neural Feature Fields to 2D Neural Rendering 
Generate N generative feature fields for each entity including the background --> Posed feature fields --> Weighted summation --> Volume rendering for feature fields --> 2D neural rendering

### Keywords:
NeRF, Generative Neural Feature Fields, Multi-Object Scene, Disentangling Entities, Composition Operator, 2D Neural Rendering, Controllable Scene

### Notes:
- Realistically, is it applicable to more complex scenes when generating individual feature fields for each entitiy and object poses, especially when we want to control the scene - move and rotate objects?
- The discriminator only checks whether individual images look realistic or not = cannot have smooth interpolations for video generation / different view points / object translation and rotation.
- Synthesized background seems to fill in obstructed areas - by foreground entities - somewhat better than other methods.
- But, I think it is unique that this work can add and remove entities placed on top of the background.

### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/GIRAFFE_fig1.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/GIRAFFE_fig3.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/GIRAFFE_fig5.PNG" height="400">
</p>

#Others #3D #NeRF
 
