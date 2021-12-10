# Mip-NeRF
https://jonbarron.info/mipnerf/

### NeRF + Casting Cones and Rendering Conical Frustrum + Integrated Position Encoding 
Casting and rendering rays may work for fixed scale 3d scene synthesis, but fails on multiple scales.  
This is because a pixel on an image should be rendered from multiple rays that fill up the area for a single pixel.
But sampling multiple rays is inefficient, so uses Gaussian distribution approximation for expected value for radiance and density in connical frustrum.


### Keywords:
NeRF, Multi-Scale, Aliasing, Conical Frustrum, Cone Tracing, Integrated Position Encoding (IPE)

### Notes:
- Replace deterministic input can be approximated with stochastic input (or just replaced)

### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/Mip_NeRF_fig1.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/Mip_NeRF_fig4.PNG" height="400">
</p>

#Others #3D #NeRF
 
