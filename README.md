# Image Denoising (Deep Learning)

A simple, end-to-end project for training and using a deep learning model for image denoising. The model is trained during the notebook run and saved as `mymodel.h5`.

## What this project does
- **Train a model** and save it as `mymodel.h5`, then **denoise images**.
- **Evaluate quality** with PSNR (Peak Signal-to-Noise Ratio).

Example PSNR results on four test images:
- Test 1: 26.811
- Test 2: 25.530
- Test 3: 25.550
- Test 4: 31.750

## Project contents
- `Image_Denoising.ipynb`: Notebook to load data, add noise, train the model, denoise, and measure PSNR.
- `mymodel.h5`: Model saved after training (created when you run the notebook).
- `Project Report.pdf`: Report document.

## Requirements
- Recommended packages:
  - tensorflow or tensorflow-gpu
  - numpy
  - opencv-python
  - scikit-image
  - matplotlib
