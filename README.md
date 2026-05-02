# Clarity Detection (SemEval-2026 Task 6)

This repository contains our implementation for SemEval-2026 Task 6: CLARITY.

## Model
- DeBERTa-v3-base
- Ensemble of multiple models
- Monte Carlo Dropout for inference

## Setup

Install dependencies:

pip install -r requirements.txt

## Usage

Open and run the notebook:

clarity_model.ipynb

## Data

- Training: QEvasion dataset (via HuggingFace)
- Evaluation: SemEval-2026 dataset

## Output

- prediction (text file)
- clarity_final_submission.zip

## Results

Macro-F1 score: 0.76

## Note

Training was done on GPU (Kaggle).
