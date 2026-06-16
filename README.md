# Protein Kinase Prediction using Machine Learning

## Overview

This project predicts whether a human protein is a kinase protein using sequence-derived features and a Random Forest classifier.

## Dataset

- Human protein sequences (FASTA)
- Gene Ontology (GO) annotations

## Methods

1. Protein sequence parsing using Biopython
2. Amino acid composition feature extraction
3. Kinase label generation from GO annotations
4. SMOTE balancing
5. Random Forest classification

## Results

Accuracy: 95.5%

Precision: 27.6%

Recall: 42.7%

F1 Score: 0.335

## Technologies

- Python
- Pandas
- Scikit-learn
- Biopython
- Imbalanced-learn
