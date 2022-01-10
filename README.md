# classic-data-augmentation

In this project, we examine classic data augmentation and cutout augmentation, which randomly crops sections of images on CIFAR10 and Resnet-44 model. We examine the impact on validation error and training time when we augment the data by M times (M from 2 to 32)

Resources and Citation:

1. DeVries et al. Improved Regularization of Convolutional Neural Networks with Cutout. Paper available at https://arxiv.org/pdf/1708.04552.pdf
Code available at https://github.com/uoguelph-mlrg/Cutout

2. Hoffer et al. Augment your batch: better training with larger batches. 2019
Paper available at https://arxiv.org/pdf/1901.09335.pdf
Code available at https://github.com/eladhoffer/convNet.pytorch/tree/master/models

3. He et al. Deep residual learning for image recognition. Paper available at https://arxiv.org/abs/1512.03385
