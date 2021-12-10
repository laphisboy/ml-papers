# SemanticStyleGAN
https://semanticstylegan.github.io/

### Local Generators (StyleGAN2's) + Fusion and Rendered for RGB Image and Semantic Segmentation Mask
A local generator is responsible for generating 1 class of the semantic segmentation mask (eyes, nose, mouth...),   
Generated feature map for all classes is fused and rendered for RGB Image,  
where the discriminator compares with output semantic segmantation mask to tell apart real or fake.

### Keywords:
StyleGAN2, Local Generator, Render Net, Fusion, Restyle-psp Encoder, Pixel Preservation

### Notes:
- Requiring dataset with semantic segmentation mask may be its limitation,  
- But hints possibility of generalizing semantic segmentation / or controlled generation of eyes, nose, etc on other datasets with different style but similar structure.  

### Figures:
<p float="left">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/SemanticStyleGAN_fig2.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/SemanticStyleGAN_fig3.PNG" height="400">
  <img src="https://github.com/laphisboy/ml-papers/blob/main/figures/SemanticStyleGAN_fig15.PNG" height="400">
</p>

#Others #GAN
 
