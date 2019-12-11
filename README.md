# NI-Project-RSA
Representation Similarity Analysis vs Performance
(Neural Information Processing project at TU Berlin)

# Introduction

Representational Similarity Analysis (RSA) is a method from neuroscience used to compare representations of different models. While it has been applied to neural networks before, there exists no comprehensive study on how representation as measured by RSA relates to performance. We relate model accuracy to RSA on FashionMNIST and ImageNet datasets. The term paper is uploaded as ``rsa_vs_performance.pdf``. The code in this repo can be used for reproducing the experiments.

# Structure

Provided notebooks are structured to be as independent as possible, but most of them make use of a set of trained models. This is done in the script ``rsa_on_fashionmnist.ipynb``, which is to be run first, as it includes model training and calculating RDMs for RSA on FashionMNIST. To avoid training, we provide model saves: [MLP saves](https://drive.google.com/open?id=11BX3eCNumSSpDqHBHCtyt5YAovqMcvBc), [CNN saves](https://drive.google.com/open?id=1yNRf0NAYb2fFJZFHRvAxcVSeS0XzgIED). To use them, follow the instructions in the script.

For the other notebooks, we tried making their names descriptive of the content. 
If something's not clear, feel free to raise questions in the Issues.
