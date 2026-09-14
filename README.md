# TransMamm

### Transformer-Based TransMamm: A Density-Aware Hybrid Vision Transformer Framework for Robust Lesion Detection in Dense Breast Tissue

TransMamm is an ongoing research project focused on developing a deep learning framework for robust mammographic image analysis, with particular emphasis on lesion detection in dense breast tissue.

The project explores a hybrid architecture combining Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) to capture both local visual features and global contextual information from mammographic images.

---

## Research Motivation

Dense breast tissue can make lesions difficult to distinguish from normal fibroglandular tissue, because both may appear with similar intensity on mammograms.

This project investigates whether a density-aware hybrid CNN–Vision Transformer framework can improve lesion representation and robustness in challenging mammographic imaging scenarios.

---

## Research Areas

- Machine Learning
- Deep Learning
- Computer Vision
- Medical Image Analysis
- Mammographic Image Analysis
- Breast Lesion Detection
- Convolutional Neural Networks (CNNs)
- Vision Transformers (ViTs)
- Density-Aware Attention
- Self-Supervised Learning
- Contrastive Learning
- Domain Generalization
- Explainable AI (XAI)
- Score-CAM

---

## Datasets

The project explores publicly available mammographic datasets, including:

| Dataset | Role |
|---|---|
| **CBIS-DDSM** | Primary dataset for initial development and experimentation |
| **INbreast** | External validation |
| **CMMD** | External validation |
| **MIAS** | External validation |

> **Note:** The datasets are not included in this repository due to their size and licensing considerations.

---

## Planned Architecture

The proposed TransMamm framework is based on a hybrid CNN and Vision Transformer architecture:

```text
                 Mammographic Image
                         │
              ┌──────────┴──────────┐
              │                     │
              ▼                     ▼
             CNN                   ViT
              │                     │
              └──────────┬──────────┘
                         │
                         ▼
              Density-Aware Fusion
                         │
                         ▼
                Feature Representation
                         │
                         ▼
                 Lesion Detection
                         │
                         ▼
                  Classification
                         │
                         ▼
                    Score-CAM
```

---

## Project Structure

```text
TransMamm/
│
├── notebooks/
│   └── CBIS_DDSM_Analysis.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── dataset.py
│   ├── model.py
│   ├── train.py
│   └── evaluate.py
│
├── results/
│
├── README.md
└── requirements.txt
```

> The project structure will be updated as the research implementation progresses.

---

## Current Progress

- [x] CBIS-DDSM dataset exploration
- [ ] Image-path mapping
- [ ] Dataset preprocessing
- [ ] Patient-level data splitting
- [ ] Mammogram preprocessing pipeline
- [ ] CNN feature extraction
- [ ] Vision Transformer integration
- [ ] Density-aware attention
- [ ] Hybrid CNN–ViT architecture
- [ ] Model training
- [ ] Model evaluation
- [ ] Cross-dataset validation
- [ ] Score-CAM explainability
- [ ] Ablation studies

---

## Technologies
- Python
- PyTorch
- torchvision
- NumPy
- Pandas
- OpenCV
- scikit-learn
- Matplotlib
- Jupyter Notebook
- kaggle GPU

---

The main objectives of this project are to:

- Develop a hybrid CNN–Vision Transformer framework for mammographic image analysis.
- Incorporate breast density information into the learning process.
- Improve lesion representation in dense breast tissue.
- Investigate model robustness across different mammographic datasets.
- Explore explainable AI techniques for interpreting model predictions.

---

## Project Status

🚧 **Research in Progress**

This repository is actively being developed as part of an undergraduate research project. Implementation details, experiments, evaluation results, and findings will be added as the research progresses.

---

## Author

**Mayeda Islam**
<br>Central University of Science and Technology (CUST)
<br>Computer Science and Engineering

**Research Interests:**
Machine Learning · Deep Learning · Computer Vision · Medical Imaging · Vision Transformers · Explainable AI

---

## Disclaimer

This project is intended for academic and research purposes only. The models developed in this repository are not intended for clinical diagnosis or medical decision-making.
