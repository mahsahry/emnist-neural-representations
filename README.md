<p align="center">
  <img src="EMNIST.png" alt="EMNIST" width="300">
</p>


# EMNIST Neural Representations

This repository contains a Jupyter Notebook that explores how a neural network learns and organizes internal representations on the EMNIST handwritten character dataset (digits).

## What is inside
- Data loading and preprocessing (EMNIST digits)
- Training a neural network for multi-class classification
- Visualization of hidden-layer representations (feature space analysis)
- Class separability analysis
- Robustness and generalization tests:
  - performance under increasing noise
  - adversarial perturbation experiments
  - confusion matrix evaluation

## Repository structure
- `FinalProject_EMNIST.ipynb` - main notebook

## How to run
1. Create and activate an environment
2. Install dependencies (typical):
   - `numpy`, `pandas`, `matplotlib`, `scikit-learn`
   - `torch`, `torchvision` (if the notebook uses PyTorch)
3. Open the notebook:
   - `jupyter notebook` or `jupyter lab`
4. Run all cells.

## Results
The notebook shows that internal representations become more separable in deeper layers, and evaluates how classification performance changes under noise and adversarial perturbations.
