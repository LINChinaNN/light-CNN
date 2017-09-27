Base on tiny-dnn, and refer to darknet and caffe, I rewrite a light-CNN which only uses CPU.
The following are some experimental results (I use a i7-6700 4cores 8threads, 8GB desktop).
1. MNIST, achieve 99.56% accuracy in 680s.
2. CIFAR10, accuracy 87.03% in 2000s, and 90.06% in 4hrs.

Rewriting the algorithm let me better understand the CNN (and resnet, densenet). However, it still has many things to learn.
For example, how to construct a more efficient network (since "Residual Networks Behave Like Ensembles of Relatively Shallow Networks", maybe we shouldn't alway try to deepen the network, sometimes properly broaden the network also is important). 
Any guidance will be truely appreciated.
