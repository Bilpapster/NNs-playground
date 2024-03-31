# NNs-playground

### Deep Learning architectures for multiclass image classification problems + autoencoders for MNIST digit dataset.

In this repository you can find source code for various Deep Learning (NNs) architectures. The code is provided in the form of Python Notebooks ( `.ipynb` files) cover the following:

- Multiclass image classification using [Intel Image Classification dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification/data). The available classifiers are the following:
  - Multilayer Perceptron (MLP), using `TensorFlow` and `Keras`
  - Support Vector Machines (SVMs), using `scikit-learn` wrapper for `LIBSVM`
- Image reconstruction tasks for [MINST digit dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) using `TensorFlow` and `Keras`. The available autoencoder flavors are the following:
  - classic convolutional autoencoder for image reconstruction
  - denoising autoencoder in several variations, including an autoencoder trained to reconstruct the **noisy** image
  - autoencoder to reconstruct the **next** digit
  - autoencoder to reconstruct the **sum** (as two images), given two input digits (as images)

The code was developed alongside with the Course [Neural Networks - Deep Learning](https://qa.auth.gr/en/x/class/1/600237255) the author attended during their 6th semester of studies at the [Computer Science Department of AUTh](https://www.csd.auth.gr/en/). The interested reader can find a [presentation](https://docs.google.com/presentation/d/1b7eVXVlLL_73TKspzRxm7bFrcKHUHAfz2G752kAQn8s/edit?usp=sharing) that summarizes the work produced.

## Results

### Next-digit autoencoder

<p align="center">
  <img src=https://github.com/Bilpapster/NNs-playground/assets/59035668/87cab455-da1a-40d3-b292-beaea4a95412" />
</p>


### Adder autoencoder

<p align="center">
  <img src=https://github.com/Bilpapster/NNs-playground/assets/59035668/fc9672f4-3405-4cea-acb2-67bd79f58333" />
</p>

For a comprehensive description of the adopted workflow, as well as the produced results, the interested reader can refer to the [presentation](https://docs.google.com/presentation/d/1b7eVXVlLL_73TKspzRxm7bFrcKHUHAfz2G752kAQn8s/edit?usp=sharing) file. 
