# GTZAN Genre Classification Using CNN

This repository contains a Jupyter notebook for the classification of musical genres based on the GTZAN dataset using Convolutional Neural Networks (CNN). The notebook demonstrates the end-to-end process from data loading and preprocessing, feature extraction, model building, training, and finally evaluating the performance of the model.

## Installation

To run this notebook, you will need to install several Python libraries. It is recommended to use a virtual environment to manage dependencies. You can install the required libraries using pip:

```bash
pip install numpy pandas matplotlib librosa tensorflow ipython
```

## Dataset Overview

The GTZAN dataset is used in this project, which includes 1000 audio tracks each 30 seconds long. Each track is a different genre, categorized into 10 genres. This notebook explores these audio files, processes them into spectrograms, and uses these for training a CNN model.

## Model Overview

The notebook builds a CNN model to classify audio into one of 10 categories. It discusses the architecture of the CNN, its implementation using TensorFlow, and how the model is trained and evaluated.

## Usage

To use this notebook:
1. Ensure you have Jupyter Notebook or JupyterLab installed.
2. Launch Jupyter Notebook and open the `GTZAN_classification.ipynb` file.
3. Run the cells sequentially to observe the workflow from data preprocessing to model evaluation.
