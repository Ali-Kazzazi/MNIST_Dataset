# MNIST_Dataset
-------
#### This repo contains MNIST Dataset files (.mat &amp; .gz) and the ways to use in.

-----

# How to use
****

### MATLAB

1. first unrar the file "mnist.rar" which exists in ".mat" directory to extract the file "mnist.mat".
2. use the code snip blow to utilize the dataset.

``` Matlab
dataset = load('/path/to/mnist.mat');
train_data = dataset.training.images;
test_data = dataset.test.images;

train_labels = dataset.training.labels;
test_labels = dataset.test.labels;

img_height = dataset.training.height;
img_width = dataset.training.width;
```

### Python


```
```