# MixerGANsformer: Can We Built A Strong GAN with Transformers and MLP-Mixers?

Official implementation of MixerGANsformer in PyTorch. A novel model in GANs which consists of Transformer Encoder Block in generator and MLP-Mixer in discriminator. Preprint will be published soon. In this implementation CIFAR10 dataset was used.

<p align="center"><img width="100%" src="https://github.com/asarigun/MixerGANsformer/blob/main/images/model.png"></p>

## Installation

Before running ```train.py```, check whether you have libraries in ```requirements.txt```! To save your model during training, create ```./checkpoint``` folder using ```mkdir checkpoint```.

## Dataset 

``` CIFAR10 ```

## Training 

```
python train.py
```

## License

MIT



