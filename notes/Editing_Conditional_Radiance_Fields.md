# Editing Conditional Radiance Fields
http://editnerf.csail.mit.edu/

### Complicated NeRF Architecture + Partial parameter and code update for editing
By training with reconstruction loss on areas where the user has locally edited (foreground), and areas that the user doesn't want to be editied (background),  
The hybrid-fine-tuned network generate 3D synthesized images on differnt view points, where the local edit has been applied globally.

### Keywords:
NeRF, Shared Shape Network, Instance-Specific Network, Fusion Shape Network, Output Density Network, Output Radiance Network, Color/Shape Editing, Reconstruction Loss, Density Loss, Entropy

### Notes:
- Cannot apply complicated edits : Editing on complicated color and shape variations. 
- Shape code follows pre-defined distribution, is this beneficial?

### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/Editing_Conditional_Radiance_Fields_fig1.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/Editing_Conditional_Radiance_Fields_fig2c.PNG" height="400">
</p>

#Others #3D #NeRF #Editing
 
