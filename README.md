# A Simple Framework for Contrastive Learning of Visual Representation. (SimCLR)



![Image of SimCLR Arch](https://sthalles.github.io/assets/contrastive-self-supervised/cover.png)

## Dependencies

- tensorflow 2.x

## file structure


```yaml
pretrained_weights                : pretrained weights of simclr model.
images                            : contains images like plots.
simclr-data-creator.ipynb         : file contains code for creating a custom imagenet data.
simclr-model.ipynb                : file contains code for training simclr model.
simclr-linear_evaluator-lg.ipynb  : file contains code for the linear evaluation of the trained simclr model, with logistic regression.
simclr-nonlinear-evaluator.ipynb  : file contains code for nonlinear evaluation of trained simclr moel, with None linear dense tensorflow layer.
resnet-supervised-model.ipynb     : file contains code for creating a supervised model for the custom imagenet data.  

```

## Acknowledgements
- Loss function comes from : https://github.com/sthalles/SimCLR-tensorflow/blob/master/utils/losses.py.
- Data Creation function comes from: https://github.com/mf1024/ImageNet-Datasets-Downloader

## Dataset
Dataset, is created using the simclr-data-creator.ipynb file, which  creates a custom imagenet data.

## References
- https://arxiv.org/abs/2002.05709
- https://www.youtube.com/watch?v=lW0ZIOyhRic
- https://www.v7labs.com/blog/self-supervised-learning-guide
- https://amitness.com/2020/03/illustrated-simclr/
- https://sthalles.github.io/simple-self-supervised-learning/
- https://github.com/sthalles/SimCLR
- https://github.com/sayakpaul/SimCLR-in-TensorFlow-2
- https://github.com/garder14/simclr-tensorflow2
