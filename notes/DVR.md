# DVR Differentiable Volumentric Rendering
https://arxiv.org/abs/1912.07372

### Contruct 2D image of 3D object by predicting color on the surface only.
Instead of predicting density of all sample points along a casted ray,  
DVR predicts depth until the nearest surface, and predicts color on the surface.  
  
Single-view reconstruction where encoder network aggregates information over multiple objects -  
with only a single image, depth, and camera information - and creates global descriptor,  
and the model uses it to infer 3D shape and texture of the object, even in novel viewpoints.

### Keywords:
Differentiable, Volumetric Rendering, Occupancy Network, Single-View Reconstruction, Multi-View Reconstruction

### Notes:
- Single-view reconstruction worked with depth and camera information,   
can the dependency of depth and camera information be resolved for single-view reconstruction with only 2D images?    
- In multi-view reconstruction, there seems to be a trade off between completeness and accuracy,  
which can fill in missing parts of the 3D object from dataset with sparse depth maps.
- 


### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/DVS_fig2.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/GIRAFFE_fig3.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/GIRAFFE_fig5.PNG" height="400">
</p>

#Others #NeRF
