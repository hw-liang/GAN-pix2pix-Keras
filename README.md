## Keras-GAN
This is the start work of my research on Style transfer learning using GAN for Histopathoplogical images. This is the Keras implementations of pix2pix model suggested in paper---Image-to-Image Translation with Conditional Adversarial Networks by Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros, CVPR, 2017. I used this model for histopathoplogical images' color normalization.

## Installation
    $ git clone https://github.com/hanwen0529/GAN-pix2pix-Keras.git
    $ cd GAN-pix2pix-Keras/
    $ sudo pip3 install -r requirements.txt

## Implementations
Implementation of _Image-to-Image Translation with Conditional Adversarial Networks_.
Paper: https://arxiv.org/abs/1611.07004

<p align="center">
    <img src="http://eriklindernoren.se/images/pix2pix_architecture.png" width="640"\>
</p>

#### Example
```
$ python3 pix2pix.py
``` 
