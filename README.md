# Iceberg or Ship? Classifying the content of radar images using deep learning.
![Alt text](/Images/rgbShips.png "RGB representation of radar data containing ships.")
This repo contains my submission to the Statoil/C-Core Iceberg Classifier Challenge from Kaggle.  An overview of the project and its exact details and requirements can be found [here](https://www.kaggle.com/c/statoil-iceberg-classifier-challenge). The main goal is to create an algorithm capable of differentiating between icebergs and ships using only images obtained from satellite radar data. My final submission obtained an accuracy of about 91% on the test data and consisted on a model that used a Convolutional Neural Network as its primary algorithm. 

## Running this project on your machine

This repo includes the project as-is. It does not include any of the training and testing data which should be downloaded from the Kaggle link above. The language used was Python 3.5 with the libraries listed below:

```
* Keras
* Sci-kit learn
* Jupyter notebooks
* Numpy 
* Matplotlib
* Tensorflow
* h5py
```

Many packages listed above require others to work so I recommend using a virtualenv to avoid any possible clashes between your regular work environment and these packages. 

## Final submission & Detail Explanation

The script used for the final submission was annotated in a  jupyter notebook that you can take a look at [here](http://nbviewer.jupyter.org/github/Angelo1211/Statoil-Project/blob/master/Scripts/Final/Statoil%20Iceberg%20Challenge%20Submission.ipynb). It includes a much more detailed explanation of each component of the algorithm and follows the general steps that I did when building this model.

Other scripts can be found in the scripts folder under WIP but most of them were just tests of a specific concept and are not guaranteed to work at all, but can be interesting to look at. 

## Authors

* **Angel Ortiz** - *Project Lead* - [GitHUB](https://github.com/Angelo1211)

## References

* https://www.kaggle.com/muonneutrino/exploration-transforming-images-in-python
* https://www.kaggle.com/c/statoil-iceberg-classifier-challenge
* https://yashk2810.github.io/Applying-Convolutional-Neural-Network-on-the-MNIST-dataset/
* http://neuralnetworksanddeeplearning.com/index.html
* https://keras.io/



