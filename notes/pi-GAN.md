# pi-GAN
https://marcoamonteiro.github.io/pi-GAN-website/

### NeRF + GAN framework + Mapping Network + FiLM SIREN 
Generator conditioned on input noise, input noise is processed through mapping network and applied with FiLM conditioning.

### Keywords:
SIREN, Periodic Activation Function, Volumetric Rendering, FiLM Feature-Wise Linear Modulation, Mapping Network, Progressive Growing  

### Notes:
- Difference from NeRF is that is is trained based on adversarial loss,
- Mapping network - more expressive?   
- FiLM increase image fidelty? Why is sinusoidal activation better?  
- 
- Progressive growing where generator size is fixed and sampled ray density increases instead.  
- Learns to generate CelebA in different viewing direction even when no viewing direction label is given and the dataset is biased to front view.

### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/pi-GAN_fig2.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/pi-GAN_fig9.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/pi-GAN_fig11.PNG" height="400">
</p>

#Others #3D #GAN
 
