# Image Processing with Deep Learning

## Overview

This repository contains coursework materials for **COMP0169: Learning Learning, From Scratch** at University College London. The main deliverable is the notebook [VC_DL.ipynb](VC_DL.ipynb), which walks through a set of image processing and deep learning exercises using the course-provided datasets and the libraries listed in the notebook itself.

**Course Team:**
- Lecturers: Niloy J. Mitra and Tobias Ritschel
- Teaching Assistants: Remy Sabathier, Niladri Shekhar Dutt, and Binglun Wang

## Coursework Structure

The notebook contains 5 questions totaling **100 points**:

### 1. Linear Fitting (10 points)
- Fit a linear model from scratch
- Work with the IRIS dataset

### 2. Image Retrieval (15 points)
- Build a simple image retrieval pipeline
- Compare feature-based similarity scores

### 3. Image Denoising (30 points)
- Implement a denoising CNN in PyTorch
- Train and evaluate on the NoisyOCR data

### 4. Texture Synthesis (15 points)
- Build a texture synthesis objective
- Optimize an input image to match target statistics

### 5. Implicit Neural Representation (30 points)
- Model images and video frames with coordinate-based neural networks
- Evaluate reconstruction quality and frame accuracy

## Datasets

The notebook uses the following datasets:

- IRIS: classic tabular dataset used for linear fitting
- MNIST: handwritten digits dataset
- CelebA: face image dataset used for retrieval and style/texture tasks
- NoisyOCR: noisy OCR scans paired with clean targets

IRIS and MNIST are downloaded in the notebook through `sklearn.datasets`.

CelebA and NoisyOCR are distributed in a separate archive:

https://geometry.cs.ucl.ac.uk/mlvc/cw_datasets.zip

Extract it so that `cw_datasets/` sits next to the notebook:

```text
Image-Processing-with-Deep-Learning/
├── VC_DL.ipynb
└── cw_datasets/
    ├── CelebA/
    └── NoisyOCR/
```

## Requirements

Use the packages listed in the notebook’s package cell. The imported stack currently includes:

- Python 3.7+
- NumPy
- Matplotlib
- SciPy
- scikit-learn
- PyTorch
- torchvision
- Pillow
- imageio
- OpenCV
- scikit-image
- tqdm

## Usage

1. Open [VC_DL.ipynb](VC_DL.ipynb) in Jupyter or VS Code.
2. Or open the notebook directly in Google Colab using the badge at the top of the notebook.
3. Make sure `cw_datasets/` is available before running the later notebook sections.

## Submission

Submit a zipped folder containing:

1. [VC_DL.ipynb](VC_DL.ipynb), with all required code and written answers completed inside the designated solution blocks.
2. A `models/` folder containing any trained weights requested by the notebook.

## Implementation Notes

- Only edit cells marked with the pencil icon.
- Write code only inside `#begin_solution ... #end_solution` blocks.
- Do not change `#begin_test ... #end_test` blocks.
- Keep solutions general so they work on hidden data with different shapes or sample counts.
- Follow the notebook’s package restrictions when adding imports.

## Support

For deadlines and submission guidance, refer to Moodle and the teaching team.

**Last Updated:** May 2026
