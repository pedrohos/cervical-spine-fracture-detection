# Overview
This repository aims to solve the problem of cervical column fracture detection in images of computed tomography with the RSNA 2022 dataset provided by a Kaggle competition.
It does so with techniques of digital image processing and deep learning, especially the YOLO v8 detection module.
A Jupyter Notebook is provided with an EDA of the dataset and the preprocessing followed by the network traning.

# Usage
It is expected to download the [Kaggle competition dataset](https://www.kaggle.com/competitions/rsna-2022-cervical-spine-fracture-detection) a unzip all of its files into a folder called "dataset" in the same folder as the notebook.ipynb.
The necessary dependencies are specified inside a Jupyter Notebook cell.
Make sure to install [PyTorch](https://pytorch.org/) with GPU support to achieve faster training speeds.
For more details about possible training parameters read the [Ultralytics YOLO v8 Repo](https://github.com/ultralytics/ultralytics)

# Results
The achieved results are stored in the folder best_models, there you can check the result achieved in the training as well as the predictions of the validation and test set.