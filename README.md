# Image Processing with Deep Learning

## Overview

This repository contains coursework materials for **COMP0169: Learning Learning, From Scratch** at University College London. It covers fundamental computer vision and deep learning concepts through a series of practical exercises, implemented from scratch using NumPy and Matplotlib.

**Course Team:**
- Lecturers: Niloy J. Mitra & Tobias Ritschel
- Teaching Assistants: Remy Sabathier, Niladri Shekhar Dutt & Binglun Wang

## Contents

This coursework consists of 4 main exercises totaling **100 points**:

### 1. **Linear Fitting (10 points)**
   - Implementing linear regression from scratch
   - Working with the IRIS dataset

### 2. **Image Retrieval (15 points)**
   - Building image retrieval systems
   - Feature extraction and matching

### 3. **Image Denoising (30 points)**
   - Implementing denoising algorithms
   - Working with the NoisyOCR dataset
   - Restoration techniques

### 4. **Neural Implicit Representation (30 points)**
   - Understanding implicit neural representations
   - Building neural networks from scratch
   - Advanced deep learning concepts

## Datasets

The project uses the following datasets:

- **IRIS**: Classic dataset with 4 features (sepal/petal measurements) and 3 classes
- **MNIST**: Handwritten digits dataset (28×28 grayscale images)
- **CelebA**: Large-scale face attributes dataset
- **NoisyOCR**: OCR images with noise and corresponding clean targets

### Dataset Download

For CelebA and NoisyOCR datasets, download from:
```
https://geometry.cs.ucl.ac.uk/mlvc/cw_datasets.zip
```

Extract the zip file into the same directory as the notebook:
```
Image-Processing-with-Deep-Learning/
├── VC_DL.ipynb
└── cw_datasets/
    ├── CelebA/
    └── NoisyOCR/
```

## Requirements

- Python 3.7+
- NumPy
- Matplotlib
- scikit-dataset (for downloading IRIS and MNIST)

**Note:** Only NumPy and Matplotlib are allowed for implementations unless otherwise specified.

## Usage

1. **Local Setup:**
   ```bash
   jupyter notebook VC_DL.ipynb
   ```

2. **Google Colab:**
   Open directly with the provided Colab badge in the notebook

3. **Offline Mode:**
   - Download datasets while connected to the internet
   - Save as `.npy` files
   - Load locally for offline work

## Submission Requirements

Submissions must include:

1. **VC_DL.ipynb** - Jupyter notebook with:
   - All code implementations within `#begin_solution ... #end_solution` blocks
   - Written answers in markdown cells marked "_Your reply_:"
   
2. **models/** folder - Containing trained model weights

## Implementation Guidelines

- ✏️ Cells marked with a pencil icon (✎) require modifications
- Code changes outside `#begin_solution` blocks will not be evaluated
- Do not modify `#begin_test` blocks (reserved for TAs)
- Avoid hard-coded solutions - code must work with different dataset dimensions
- Write generalizable code that works with varying sample counts and feature dimensions

## Important Notes

- All exercises must be implemented from scratch
- Only the libraries listed in the packages cell are allowed
- Solutions must be robust across different dataset sizes
- Evaluation will be tested on hidden datasets with potentially different dimensions

## File Structure

```
Image-Processing-with-Deep-Learning/
├── README.md              # This file
├── VC_DL.ipynb           # Main coursework notebook
└── cw_datasets/          # Extracted datasets (after download)
    ├── CelebA/
    └── NoisyOCR/
```

## Quick Start

1. Clone or download this repository
2. Download the datasets from the link above
3. Extract datasets into the same directory as the notebook
4. Open `VC_DL.ipynb` in Jupyter or Google Colab
5. Follow the instructions in each cell and complete the exercises

## Grading

- **Linear Fitting:** 10 points
- **Image Retrieval:** 15 points
- **Image Denoising:** 30 points
- **Neural Implicit Representation:** 30 points
- **Total:** 100 points

## Support

For questions or issues:
- Refer to the Moodle submission page for deadlines
- Contact the teaching assistants
- Check inline comments in the notebook for guidance

---

**Last Updated:** May 2026
