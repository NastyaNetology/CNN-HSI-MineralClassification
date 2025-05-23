CNN-HSI-MineralClassification
1D_CNN for supervised mineral classification using hyperspectral imaging (HSI) data

This repository contains a 1D Convolutional Neural Network (CNN) for supervised mineral classification using hyperspectral imaging (HSI) data. The model is designed to analyze spectral signatures from hyperspectral images and classify minerals based on their unique spectral characteristics.

Setup Instructions

Step 1: Create the Environment
Run the following commands in Anaconda Prompt or Terminal to set up the required environment:
conda create -n multispectral python=3.8
conda activate multispectral
conda install -n multispectral ipykernel --update-deps --force-reinstall
pip install rasterio
pip install geopandas
pip install matplotlib
pip install scikit-learn
pip install tensorflow
pip install fiona==1.9

Running the Models
Step 2: Execute the Notebooks
Run the following notebooks in order:
1D_CNN_supervisd_learning.ipynb → Implements a 1D CNN for supervised mineral classification.
semisupervised_learning.ipynb → Extends the model using semi-supervised learning.
Deep_active_learning.ipynb → Applies deep active learning for more efficient labeling and classification.
 
