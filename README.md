# Pneumonia-Detection-Using-Chest-X-ray-Images

An AI-powered deep learning system for detecting pneumonia from chest X-ray images. The model classifies X-rays into Normal or Pneumonia, helping healthcare professionals improve diagnostic speed and accuracy through AI-assisted decision support.

---

## 🚀 Project Overview

This repository contains a Jupyter notebook implementation for pneumonia detection using transfer learning architectures such as MobileNetV2, VGG16, ResNet50, and DenseNet121. The notebook trains, evaluates, and compares multiple deep learning models on chest X-ray images.

## 🔍 Why this project matters

- Supports faster triage in medical imaging
- Provides AI-assisted decision support for clinicians
- Uses modern transfer learning for accurate binary classification
- Designed to be reproducible and easy to extend

## 📁 Repository Contents

- `Pneumonia.ipynb` — Main notebook with data pipeline, model training, evaluation, and an interactive Gradio demo.
- `Data.txt` — Link to the dataset source.
- `requirements.txt` — Python dependencies for local setup.
- `LICENSE` — MIT open source license.
- `.gitignore` — Clean Python project ignored files.

## 🧠 Model Pipeline

1. Load chest X-ray images from a training/test dataset structure
2. Preprocess images with rescaling, augmentation, and validation split
3. Build transfer learning models with pre-trained ImageNet weights
4. Train models with frozen base layers
5. Evaluate performance on the test set
6. Compare model accuracy and visualize results
7. Launch a Gradio interface for image prediction

## ⚠️ Important Note

The dataset is not included in this repository. Download the dataset using the link in `Data.txt` and place the extracted folder in the project directory.

Expected local data layout:

```text
chest_xray/
  ├── train/
  ├── test/
```

## 🛠️ Local Setup

1. Create a Python virtual environment:

```bash
python -m venv .venv
```

2. Activate the environment:

Windows PowerShell:
```powershell
.venv\Scripts\Activate.ps1
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open `Pneumonia.ipynb` with Jupyter Notebook or VS Code and run the cells.

## ▶️ Running the Notebook

- Execute the notebook cells from top to bottom.
- Update the dataset path in the notebook if needed.
- If dataset paths are local, remove or disable the Colab-specific drive mounting section.

## 📌 GitHub Presentation Tips

To make the repository stand out for hiring managers and companies:

- Add a clean screenshot of the notebook training results and model comparison chart.
- Add a demo screenshot of the Gradio interface.
- Use concise captions and a large project title at the top of the README.
- Keep the README language simple and emphasize business value.

## 📝 License

This project is licensed under the MIT License.
