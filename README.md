### Bear Classifier

This is an experiment/demo for understanding how the Binder service works for deploying a Jupyter-based web app rendered with Voila.

A web app deployed through Binder. This service accepts any image file upload and returns a classification as one of four types of bear, grizzly, black, teddy, or polar.

Backend is a resnet18 CNN model trained on 378MB of labeled bear images from Bing Image Search.

Accuracy of the model is not bad at 98.4% on the test set. UX of the app is not super clean.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GeneChalfant/Bear-Classr/HEAD?labpath=BearClassr.ipynb)
