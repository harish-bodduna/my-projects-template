# my-projects-template

A Cookiecutter template for building robust ML projects on Kaggle datasets, optimized for NVIDIA DGX Spark. Designed for fundamental algorithms (e.g., Logistic Regression, Linear Regression), it provides a structured pipeline with GPU-ready Dev Containers, Kaggle automation, and experiment tracking.

## Features
- Structured pipeline for data, code, notebooks, and tests.
- Kaggle API scripts for dataset downloads and submissions.
- GPU-optimized Dev Containers with PyTorch and `nvidia-ml-py`.
- Jupyter notebooks for EDA and results.
- MLflow and W&B for experiment tracking.
- Pytest and GitHub Actions for testing.

## Usage
```bash
pip install cookiecutter
cookiecutter https://github.com/harish-bodduna/my-projects-template