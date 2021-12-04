# StyleNeRF
https://arxiv.org/abs/2110.08985
### NeRF++ + Mapping Network + Camera Predictor
To increase rate if 3D consistent image synthesis, volume rendering - or 2D Aggregation - is done earlier,
but aggregates to a feature map which is upsampled with MLP and reduced to RGB output.

### Keywords:
NeRF++, 2D Aggregation, Mapping Network, Camera Predictor, NeRF Path Regularization

### Notes:
- Viewing direction input in the middle of NeRF has been removed - but camera pose is inputted at the beginning
- Why is mapping network necessary? Not clearly explained...?
- Generated images not consistent with different camera poses = not well disentangled ... because camera pose is inputted at the beginning?
- Progressive growing of generator by changing original layer to upsampling layer.
- NeRF Path Regularizer to encourage 3D consistent image synthesis of StyleNeRF output just as an original NeRF would generate. 

### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/StyleNeRF_fig3.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/StyleNeRF_fig9.PNG" height="400">
</p>

#Others #3D #NeRF
 
