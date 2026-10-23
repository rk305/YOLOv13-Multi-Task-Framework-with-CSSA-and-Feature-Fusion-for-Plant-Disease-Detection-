# Plant Disease Detection Project

An end-to-end deep learning framework for plant disease classification and detection.

## Directory Structure

```text
plant_disease_project/
├── configs/       # Experiment configuration files (YAML, JSON)
├── checkpoints/   # Saved model weights and checkpoints (.pt, .pth)
├── data/          # Raw and processed datasets (ignored by git)
├── experiments/   # Experiment logs and metrics
├── outputs/       # Evaluation outputs, confusion matrices, prediction visualizations
├── reports/       # Summaries, figures, and documentation
├── src/           # Core source code (models, data pipelines, training routines)
├── requirements.txt
├── .gitignore
└── README.md
```

## Quick Start

### 1. Setup Virtual Environment
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# Linux / macOS
source .venv/bin/activate
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
