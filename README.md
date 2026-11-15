# DTSP Image Denoising

This project compares different image denoising techniques for grayscale images affected by noise.

What it does
Loads an image dataset
Adds Gaussian and salt-and-pepper noise
Applies denoising methods:
Mean filter
Median filter
Gaussian filter
Wavelet denoising
Displays the original, noisy, and restored images
Calculates PSNR and MSE to compare quality
Saves denoised output images
Files
dtsp_pbl.py — main Python implementation
README.md — project summary
DTSP_Conference_Paper_Image_Denoising.docx — conference paper
DTSP_PBL_Final_Documentation.docx — project documentation
Requirements
bash
pip install opencv-python matplotlib numpy scikit-image
Run
bash
python dtsp_pbl.py
Result
The script helps compare which filter works best for each type of noise:

Median filter works well for salt-and-pepper noise
Gaussian filter reduces Gaussian noise
Wavelet denoising preserves edges better
This project is useful for learning digital image processing and comparing denoising methods.
