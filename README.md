<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License" />
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg" alt="Python 3.8+" />
  <img src="https://img.shields.io/badge/TensorFlow-2.8%2B-orange.svg" alt="TensorFlow 2.8+" />
</p>

<h1 align="center">🚑 Pneumonia Detection Using Chest X-ray Images</h1>

<p align="center">
  An AI-powered pneumonia screening solution that classifies chest X-rays into <strong>Normal</strong> or <strong>Pneumonia</strong> with transfer learning models.
</p>

---

## ⭐ Project Snapshot

- **Purpose:** Accelerate pneumonia triage using deep learning on chest X-ray images
- **Approach:** Transfer learning with MobileNetV2, VGG16, ResNet50, and DenseNet121
- **Output:** Model comparison, evaluation dashboard, and Gradio inference demo
- **Value:** Clear, explainable AI workflow with strong documentation for reviewers

## 🚀 Why this project matters

- Reduces diagnostic time for pneumonia screening
- Supports clinical decision-making with AI-assisted inference
- Demonstrates a strong end-to-end model pipeline for medical imaging
- Designed for reviewers who need fast clarity and strong technical delivery

## 📦 Repository Structure

- `Pneumonia.ipynb` — Full notebook with data preparation, model training, evaluation, and Gradio demo
- `Data.txt` — External dataset download source
- `requirements.txt` — Install dependencies locally
- `LICENSE` — MIT open source license
- `.gitignore` — Python project ignore rules

## 🧠 Core Features

- Local training pipeline for chest X-ray classification
- Data augmentation and validation split
- Multi-model transfer learning comparison
- Test set evaluation and accuracy reporting
- Real-time prediction demo using Gradio

## 📌 Data Requirements

This repository does not include the dataset. Download the dataset from the link in `Data.txt` and place it in the project root.

Expected folder structure:

```text
chest_xray/
  ├── train/
  └── test/
```

## ⚙️ Setup Instructions

```bash
python -m venv .venv
```

Activate the environment on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Then open `Pneumonia.ipynb` in VS Code or Jupyter and run the notebook cells from top to bottom.

## 📊 Notebook Highlights

- Clean data pipeline with `ImageDataGenerator`
- Frozen pre-trained backbones for fast model training
- Evaluation on a reserved test set
- Visual accuracy comparison across architectures
- Gradio interface for demo-ready predictions

## 💡 Notes for Reviewers

- Designed to support clear communication for non-technical stakeholders
- The notebook is structured for reproducibility and easy edits
- Use the dataset link in `Data.txt` to prepare local data
- No external images are required to understand the project

## 📝 License

This project is licensed under the MIT License.
