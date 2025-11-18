# ImageProcessing
# Colab Image Processing Projects

This repository contains Google Colab notebooks for **image processing and super-resolution projects**. The notebooks demonstrate techniques such as:

- Reading images from Google Drive  
- Grayscale to color conversion  
- Image subsampling  
- Zooming images using classical interpolation (bilinear, cubic)  
- Deep learning-based super-resolution (ESPCN / EDSR)  

## Notebooks

1. `angelomathews_image.ipynb` – Image subsampling and zooming  
2. `Pasindu_Srilankaheritagesigiriya.ipynb` – Grayscale to BGR color conversion  

## Features

- **Colab-ready notebooks** – run directly in Google Colab  
- **Drive integration** – load images from your Google Drive  
- **Super-resolution using deep learning** – smooth zoom without losing details  
- Visualization using `matplotlib`  

## How to use

1. Open the notebook in [Google Colab](https://colab.research.google.com/)  
2. Mount your Google Drive to access images:  
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
