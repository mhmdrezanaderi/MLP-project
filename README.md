# MNIST Classification with MLP in PyTorch
This repository contains code for training and evaluating a Multi-Layer Perceptron (MLP) on the MNIST dataset using PyTorch. Additionally, it includes an extension where the model is trained and tested on a subset of classes from MNIST.

## Overview
The repository consists of the following components:

1. MLP Model: Defines a simple MLP architecture using PyTorch's nn.Module.
2. Training and Testing: Functions for training and evaluating the MLP on the full MNIST dataset.
3. Subset Classification: Extends the model to classify a subset of MNIST digits (0-4 vs. 5-9).
4. Visualization: Includes visualizations of training and testing metrics, and samples of correct and incorrect predictions.

## Requirements
- Python 3.x
- PyTorch (>=1.0.0)
- torchvision
- matplotlib
- numpy

## Setup
To set up and run the code:

1. Clone the repository:

```bash
git clone https://github.com/mhmdrezanaderi/MLP-project.git
cd MLP-project
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the main script:
```bash
python MLP.py
```

## Files
- main.py: Main script that trains the MLP on MNIST and its subset.
- mlp_model.py: Defines the MLP architectures (MLP and MLP_filtered) and training/testing functions.
- utils.py: Contains utility functions such as dataset filtering and seed setting.
- README.md: This file, providing an overview of the repository.

## Results
The results include plots of training and test losses, test accuracies, and visualizations of correct and incorrect predictions.

## Notes
- The MLP architecture consists of three fully connected layers.
- Training and testing loops are implemented separately for both the full MNIST and the filtered subset.
