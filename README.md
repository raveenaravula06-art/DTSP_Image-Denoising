# DTSP Image Denoising

This project compares different image denoising techniques for grayscale images affected by noise.

## Overview
The system loads an image dataset, adds different types of noise, applies multiple denoising filters, and compares the restored image quality using objective metrics.

## Features
- Loads images from a dataset
- Adds Gaussian noise and salt-and-pepper noise
- Applies:
  - Mean filter
  - Median filter
  - Gaussian filter
  - Wavelet denoising
- Displays original, noisy, and denoised images
- Calculates:
  - PSNR
  - MSE
- Saves denoised output images

## Files
- `dtsp_pbl.py` — main Python implementation
- `README.md` — project summary
- `DTSP_Conference_Paper_Image_Denoising.docx` — conference paper
- `DTSP_PBL_Final_Documentation.docx` — project documentation

## Requirements
Install the required Python libraries:

```bash
pip install opencv-python matplotlib numpy scikit-image
