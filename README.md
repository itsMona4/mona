# TargetCLIP- official pytorch implementation of the paper Image-Based CLIP-Guided Essence Transfer

This repository finds a *global direction* in StyleGAN's space to edit images according to a target image.
We transfer the essence of a target image to any source image.

## Pretrained directions notebook:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hila-chefer/TargetCLIP/blob/main/TargetCLIP_CLIP_guided_image_essence_transfer.ipynb)

The notebook allows to use the directions on the sources presented in the examples. In addition, there's an option to edit your own inverted images with the pretrained directions, by uploading your latent vector to the `dirs` folder.

## Examples:

*NOTE: all the examples presented are available in our colab notebook. The recommended coefficient to use is between 0.5-1*
### Trump
Transfering the semantic essence of Trump to source images using our method's global direction:
<p align="center">
  <img src="https://github.com/hila-chefer/TargetCLIP/blob/main/examples/Trump.png">
</p>

### Keanu Reeves 
Transfering the semantic essence of Keanu Reeves to source images using our method's global direction:
<p align="center">
  <img src="https://github.com/hila-chefer/TargetCLIP/blob/main/examples/keanu.png">
</p>


We show that our method can transfer essence even for out of domain targets, such as animated targets:

### Elsa
<p align="center">
  <img src="https://github.com/hila-chefer/TargetCLIP/blob/main/examples/elsa.png">
</p>

### Pocahontas
<p align="center">
  <img src="https://github.com/hila-chefer/TargetCLIP/blob/main/examples/pocahontas.png">
</p>


### Credits
The code in this repo draws from the [StyleCLIP](https://github.com/orpatashnik/StyleCLIP) code base. 
