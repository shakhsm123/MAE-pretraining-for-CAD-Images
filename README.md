# Team Project: Image Processing - ROBT 310

## Project Title: Advancing Coronary Angiography Vessel Image Analysis via Guided Self-Supervised Masking Pre-training Strategy

### Description
This project is designed as final project of the ROBT 310 course. The goal is to introduce compare random masking and guided masking approaches to the Masked Autoencoder by modifying its encoder and inference architecture on a basis of Frangi Filtering of the CAD image. The.ipynb notebooks contain models and architectures both for Guided_MAE and Classical_MAE approach.
By running all cells there, one can see how well these models perform in the visual task of reconstructing an image patches of a vessels and a backround. 


#### Google Drive Link
In this google drive video explanation and demonstration can be found. The weights of a models are there too: for Classical MAE for 100 epochs and for Guided MAE with 100 epochs. 
(https://drive.google.com/drive/folders/1dvqCOgyshzM3gAMt7CJN3zZzOdRvwWvN)

## Features
- Feature 1: The first .ipynb notebook showcases the implementation of a guided masking strategy based on numpy Frangi Filter along indexes of 1-6 sigma values with a Vessel Probability map and experiments on masking with vessel and masking ratio. 
- Feature 2: Both second and third notebooks highlight the inference codes, MAE architecture designs as well as Frangi Filter implementations for tensor computations and Guided Masking and Random masking cases. The visualizations are also present.

## Project Structure

| Folder/File         | Description                                         |
|---------------------|-----------------------------------------------------|
| `Classical_MAE.ipynb| Classical MAE with random masking pipeline for reconstruction                     |
| `First_Guided_Masking_Implementation.ipynb| First image processing implementation pipeline for Guided Masking                                     |
| `Guided_MAE_working.ipynb| Guided masking reconstruction                                 |
| `requirements.txt`  | List of dependencies           |
| `/Demo/*`            | Contains sample CAD images for which one can run reconstruction inference                |



## Prerequisites
Before you begin, ensure you have the following installed:

- Python 3.8+
- PyTorch
- skimage
- math
- numbers
- numpy
- OpenCV
- timm
- matplotlib
- functools

  
## Installation Guide
Follow these steps to set up the project locally:

1. **Clone the repository**  
   First, clone the repository to your local machine:
   ```bash
   git clone https://github.com/shakhsm123/MAE-pretraining-for-CAD-Images.git
2. **install packages from requirements.txt file**
   ```bash
   pip install -r requirements.txt
4. **run jupyter notebooks**
