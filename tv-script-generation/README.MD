# Image classification project on Udacity deep learning nanodegree

## Introduction

In this project, you'll generate your own [Simpsons](https://en.wikipedia.org/wiki/The_Simpsons) TV scripts using RNNs.  You'll be using part of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data) of scripts from 27 seasons.  The Neural Network you'll build will generate a new TV script for a scene at [Moe's Tavern](https://simpsonswiki.com/wiki/Moe's_Tavern).

## Environment & Tools

* [Anaconda Python3 version](https://www.anaconda.com/download/#macos) 
* [jupyter notebbok](http://jupyter.org/install)
* create environment (in MacOS and linux):

	`cd` to the directory of `environment.yml` and type the following line in your terminal:
	```
	conda env create -f environment.yml
	```
	It will create an environment named `tv_script`. You need to activate this environment through the following line:
	```
	source activate tv_script
	```
	The required packages have been installed.

## Start your project

`cd` to the directory of this notebook (ipynb) and lanuch jupyter notebook server:
```
jupyter notebook
```
A browser window will automatically open and you'll see the notebook in the current directory. If not, check the output in your terminal and find the line `The Jupyter Notebook is running at: http://localhost:XXXX/......`. Paste `http://localhost:XXXX/` in your browser. 
