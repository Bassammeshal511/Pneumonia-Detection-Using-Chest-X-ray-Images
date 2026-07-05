# Pneumonia Detection Using Chest X-ray Images

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/) [![TensorFlow](https://img.shields.io/badge/TensorFlow-2.8%2B-orange.svg)](https://www.tensorflow.org/)

A professional AI-powered system for detecting pneumonia from chest X-ray images. The model classifies X-rays into `Normal` or `Pneumonia`, helping healthcare professionals improve diagnostic speed, triage accuracy, and clinical decision support.

---

## Executive Summary

This repository presents a complete pneumonia detection pipeline built with deep learning and transfer learning. It is tailored to impress both technical reviewers and non-technical stakeholders by combining strong engineering practices with a clear, business-focused presentation.

## Key Outcomes

- Automated pneumonia screening from chest X-ray images
- Multi-model comparison using MobileNetV2, VGG16, ResNet50, and DenseNet121
- Reproducible training, evaluation, and visualization inside a Jupyter notebook
- Interactive Gradio demo for real-time inference
- Clean repository structure for easy review and extension

## Why this matters

- Speeds up initial chest X-ray triage
- Helps identify pneumonia cases early
- Delivers AI explanations and a transparent workflow
- Supports future adoption in clinical or research settings

## Repository Contents

- `Pneumonia.ipynb` — Notebook containing the full model pipeline from data loading to Gradio deployment
- `Data.txt` — External dataset download link
- `requirements.txt` — Python dependencies
- `LICENSE` — MIT license
- `.gitignore` — Recommended ignore rules for Python projects

## Dataset and Local Setup

The dataset is not included in this repository. Download the dataset from the link in `Data.txt` and place it in the project root as shown below.

```text
chest_xray/
  ├── train/
  └── test/
```

### Local setup

```bash
python -m venv .venv
```

Activate on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open `Pneumonia.ipynb` in VS Code or Jupyter Notebook and run the cells sequentially.

## Notebook Highlights

- Data augmentation and preprocessing for reliable model training
- Transfer learning with frozen pre-trained backbones
- Evaluation on a dedicated test set
- Accuracy comparison across multiple architectures
- Gradio interface for live image prediction

## Recommended GitHub Presentation Assets

To make the repository page compelling for managers and recruiters, add these images to the repository root and reference them in the README:

- `screenshot-training.png` — training progress and validation metrics
- `screenshot-comparison.png` — model accuracy comparison chart
- `screenshot-gradio.png` — Gradio interface demo

A clean set of visuals makes the project immediately understandable to reviewers who may not read every line of code.

## How to Use the Project

1. Download the dataset and place it in `chest_xray/`
2. Install dependencies
3. Run the notebook cells from top to bottom
4. Review the model comparison outputs and Gradio demo

## License

This project is licensed under the MIT License.
