# SRN Scene Representation Networks
https://arxiv.org/abs/1906.01618

### Finding Intersection Coordinate and Generate Pixel RGB
Trained end-to-end, supervised by set of posed 2D images of a scene.  
Uses LSTM to sample points along ray, iteratively updating distance (depth) until the point on ray intersects with surface on the scene,  
the final scene representation is assumed to be based on coordinate of intersection, which is converted to RGB by Pixel Generator.  

### Keywords:
Scene Representation Network, Hypernetwork, Latent Code, Ray Marching LSTM, Pixel Generator

### Notes:
- One latent code for shape and appearance = no controllability 
- Is iterative process using LSTM more efficient?
- Is iterative process without LSTM more efficient? This case would just use a threshold. <--> compared to stratified sampling scheme (... and hierarchcial sampling)?

### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/SRN_fig5.PNG" height="400">
</p>

#Others #3D
