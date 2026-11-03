# Chicken Disease Classification

A deep-learning project repository for an image-classification workflow. The repository is organized around a configurable training pipeline, with configuration files, reusable components, and workflow stages.

## Project Overview

The project is intended to provide a structured workflow for experimenting with image-based chicken disease classification. The README documents the repository workflow; dataset details, class definitions, model architecture, and measured performance should be added after they are verified against the current experiment artifacts.

## Repository Workflow

The project workflow is configured through the following stages:

1. Update `config.yaml`.
2. Update `params.yaml`.
3. Define or update the relevant entities.
4. Update the configuration manager.
5. Implement or update components.
6. Connect components into the pipeline.
7. Update `main.py`.
8. Update `dvc.yaml` when changing the DVC pipeline.

## Getting Started

### Requirements

- Python (use the version supported by the project dependencies)
- Git
- A virtual environment
- The dependencies declared by the repository

### Setup

```bash
git clone https://github.com/rahat-codes/Chicken-Disease-Classification-Project.git
cd Chicken-Disease-Classification-Project

python -m venv .venv
```

Activate the environment:

**Windows PowerShell**
```powershell
.venv\Scripts\Activate.ps1
```

**macOS / Linux**
```bash
source .venv/bin/activate
```

Install the dependencies using the dependency file provided in the repository (for example, `requirements.txt`, if present):

```bash
pip install -r requirements.txt
```

Follow the configuration and pipeline workflow above before running the experiment.

## What to Document Next

To make experiments reproducible and the results independently assessable, add:

- Dataset source, license, class labels, and train/validation/test split strategy.
- Image preprocessing and augmentation details.
- Model architecture and training configuration.
- Evaluation metrics, confusion matrix, and per-class results.
- Hardware, random seeds, and exact reproduction commands.
- Sample predictions with clear labels.

**Important:** No accuracy or clinical diagnostic claim is made in this README. Add performance figures only when supported by reproducible evaluation results.

## Author

**Rahat** · [GitHub](https://github.com/rahat-codes)
