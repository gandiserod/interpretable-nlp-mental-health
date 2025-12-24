# Interpretable NLP for Mental Health Signal Detection

## Overview
This project investigates interpretable NLP approaches for detecting distress-related signals in text.  
Rather than optimizing solely for accuracy, the focus is on explanation quality, stability, and trustworthiness in sensitive domains.

## Models
We compare three approaches:
1. **Logistic Regression (TF-IDF baseline)** — interpretable coefficients
2. **Fine-tuned BERT** — strong performance baseline
3. **Explainable BERT with Attention** — intrinsic token-level explanations

## Explainability
- Feature coefficients (Logistic Regression)
- Attention weights (Explainable BERT)
- SHAP explanations (BERT-based models)

## Ethical Considerations
Due to privacy concerns, datasets are not distributed.  
This repository contains only code for modeling, training, and evaluation.

## Repository Structure
src/
preprocessing/
models/
training/
evaluation/
utils/

## Notes
This repository accompanies an academic capstone project at New York University.# interpretable-nlp-mental-health
