# Image classification project on Udacity deep learning nanodegree

## Introduction

In this project, you'll classify images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html).  The dataset consists of airplanes, dogs, cats, and other objects. You'll preprocess the images, then train a convolutional neural network on all the samples. The images need to be normalized and the labels need to be one-hot encoded.  You'll get to apply what you learned and build a convolutional, max pooling, dropout, and fully connected layers.  At the end, you'll get to see your neural network's predictions on the sample images.

## Environment & Tools

* [Anaconda Python3 version](https://www.anaconda.com/download/#macos) 
* [jupyter notebbok](http://jupyter.org/install)
* create environment (in MacOS and linux):

	`cd` to the directory of `environment.yml` and type the following line in your terminal:
	```
	conda env create -f environment.yml
	```
	It will create an environment named `dlnd-tf-lab`. You need to activate this environment through the following line:
	```
	source activate dlnd-tf-lab
	```
	The required packages have been installed.

## Start your project

`cd` to the directory of this notebook (ipynb) and lanuch jupyter notebook server:
```
jupyter notebook
```
A browser window will automatically open and you'll see the notebook in the current directory. If not, check the output in your terminal and find the line `The Jupyter Notebook is running at: http://localhost:XXXX/......`. Paste `http://localhost:XXXX/` in your browser. 
