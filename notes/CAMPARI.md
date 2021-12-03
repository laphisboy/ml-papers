# CAMPARI
https://arxiv.org/abs/2103.17269

### NeRF + Camera Generator + BG/FG Decomposition + Shape/Texture Code X 2 + Progressive Growing 
Partition space into sphere within foreground radius(foreground model) and outside unit sphere (background model), 
Reserved space for possible camera location.
Camera generator generates both camera intrinsics and pose using residual function.
Training is performed with progressive growing (= increasing image resolution and deeper discriminator).

### Keywords:
NeRF, Camera Generator, Foreground/Background Decomposition, Foreground/Background Shape and Appearance Codes, Progressive Growing,

### Notes:
- 2D based discriminator?
- Elevation is easier than rotation? 
- How to encourage exploring larger camera ranges?

### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/CAMPARI_fig2.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/CAMPARI_fig3.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/CAMPARI_fig7.PNG" height="400">

</p>

#Others #NeRF
