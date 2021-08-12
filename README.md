# MixerGANsformer: Can We Built A Strong GAN with Transformers and MLP-Mixers?

Official implementation of MixerGANsformer in PyTorch. A novel GAN model which consists of Transformers and MLP-Mixer. Preprint will be published soon.

<p align="center"><img width="100%" src="https://github.com/asarigun/MixerGANsformer/blob/main/images/model_detailed.png"></p>

## Overview

In this model, generator is the the same structure in [TransGAN](https://arxiv.org/abs/2102.07074)'s generator and the discriminator is from [MLP-Mixer](https://arxiv.org/abs/2105.01601). The goal is to create an strong GAN model without convolutions and show that the MLP-Mixer and Transformers may help to create a strong GAN instead of using pure [Transformers](https://arxiv.org/abs/2102.07074) or [MLP-Mixer](https://arxiv.org/abs/2105.14110) in GANs. 

## Usage

Before running ```train.py```, check whether you have libraries in ```requirements.txt```! To save your model during training, create ```./checkpoint``` folder using ```mkdir checkpoint```.

## Dataset 

``` CIFAR10 ```

## Training 

```
python train.py
```

## License

MIT



