Spectral Normalization for Keras
================================
The **simple** Keras implementation of ICLR 2018 paper, [Spectral Normalization for Generative Adversarial Networks](https://openreview.net/forum?id=B1QRgziT-)

**CIFAR10 epoch 245 (DCGAN architecture)**

![](https://raw.githubusercontent.com/IShengFang/SpectralNormalizationKeras/master/generated_img_CIFAR10_DCGAN/SN_epoch_245.png "CIFAR10 epoch 245")

How to use?
----
1. Move SpectralNormalizationKeras.py in your dir
2. Import these layer class
``` python
from SpectralNormalizationKeras import DenseSN, ConvSN1D, ConvSN2D, ConvSN3D
```
3. Use these layers in your discriminator as usual

Example notebook
------
![CIFAR10 with DCGAN architecture](http://nbviewer.jupyter.org/github/ishengfang/SpectralNormalizationKeras/blob/master/CIFAR10%28DCGAN%20Structure%29.ipynb)


Issue
-----
1. Add ResNet architecture 
2. Compare with SELU and WGAN-GP
3. Projection Discriminator
