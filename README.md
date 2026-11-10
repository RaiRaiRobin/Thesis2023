# Semi-Supervised Learning for Image Classification

This repository contains Jupyter notebooks associated with Robin Rai's master's thesis work at Mercy University. The work explores semi-supervised learning for image classification using image datasets and PyTorch.

## Notebooks

- `cifar_10.ipynb` — experiments using CIFAR-10.
- `cifar_20.ipynb` — experiments using CIFAR-20.
- `stl10.ipynb` — experiments using STL-10.

The notebooks include model and data-preprocessing code, including contrastive and clustering models, image augmentation, and pseudo-labeling components. They are research notebooks rather than a packaged software release.

## Working with the notebooks

The notebooks were developed in a Google Colab/Google Drive environment and contain environment-specific paths. To run them elsewhere, review and update the paths and data locations, install the imported dependencies, and check the dataset and compute requirements. The notebooks import PyTorch, torchvision, NumPy, SciPy, and Pillow, among other packages. A compatible GPU may be useful for training.

The repository does not yet provide a pinned environment or a complete reproduction guide; results and setup details should be checked against the thesis and original experimental environment.

## Researcher

Robin Rai — master's thesis work, Mercy University.
