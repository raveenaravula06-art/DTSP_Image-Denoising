# DTSP Image Denoising

This project compares different image denoising techniques for grayscale images affected by noise.

## What it does
- Loads an image dataset
- Adds Gaussian and salt-and-pepper noise
- Applies denoising methods:
  - Mean filter
  - Median filter
  - Gaussian filter
  - Wavelet denoising
- Displays the original, noisy, and restored images
- Calculates PSNR and MSE to compare results
- Saves denoised outputs as JPG files

## Files
- `dtsp_pbl.py` — main Python implementation
- `README.md` — project overview
- `DTSP_Conference_Paper_Image_Denoising.docx` — conference paper
- `DTSP_PBL_Final_Documentation.docx` — final documentation

## Requirements
```bash
pip install opencv-python matplotlib numpy scikit-image
```

## Run
```bash
python dtsp_pbl.py
```

## Result
The script helps visualize and compare which filter works best for each noise type. In general:
- Median filter works well for salt-and-pepper noise
- Gaussian filter helps reduce Gaussian noise
- Wavelet denoising usually preserves edges better

This project is useful for learning digital image processing and comparing denoising methods.