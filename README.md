# pytorch_FashionMNIST
FashionMNIST Classification with TinyVGG 🧥👖👟

This project implements a TinyVGG-style convolutional neural network using PyTorch to classify grayscale clothing images from the FashionMNIST dataset. It includes the full pipeline — from data loading and preprocessing to model training, evaluation, and result visualization — all in a single Jupyter notebook.

📌 Project Overview

FashionMNIST is a dataset of 28×28 grayscale images of 10 clothing categories. This project replicates the TinyVGG architecture to explore how a small but effective CNN performs on this dataset.

🧠 What is TinyVGG?

TinyVGG is a simplified version of the VGG network architecture consisting of:

Repeated Conv2d -> ReLU -> MaxPool2d blocks

Fully connected output layers

Designed to be lightweight and educational
