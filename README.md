# Hypernetworks_tf2_keras
[Hypernetworks](https://arxiv.org/abs/1609.09106) (Ha et al., ICLR 2017) implementation in keras using tensorflow 2.0 as backend using custom layers and models.
The code is for MNIST and CIFAR-10 but it's easy to use it for any other dataset. It's also very easy to use it for deep architectures of different depths.
The code is implemented using custom layer and models. The custom layer can be configured to use with Sequential model just like Conv2d layer without any explicit handling of weights, multiple embeddings for a layer. For more details,start with HYPERCNN_MNIST jupyter notebook and then HYPERCNN_CIFAR-10 notebook.
(Please cite this repository if you use any of the code here, Thanks!)

# CIFAR-10 
Different models are trained from scratch for CIFAR-10 which include one VGG-Block and then addition of blocks for deeper models. Check the Report.pdf for experiments and results.


# Useful resources and other repositories.

..* [Blog](http://blog.otoro.net/2016/09/28/hyper-networks/)
..* [Pytorch code fro HyperCNN](https://github.com/g1910/HyperNetworks)
..* [TensorFlow implementation](https://github.com/hardmaru/supercell/blob/master/supercell.py)
