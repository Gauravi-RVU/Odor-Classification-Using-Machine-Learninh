# Odor Classification using Machine Learning

A research project demonstrating odor classification with machine learning, using synthetic datasets modeled after MQ/TGS gas sensor outputs. No installation required — explore the report and results directly.

## Overview
- **Goal**: Classify 5 odor types using simulated sensor data.
- **Approach**: Compared Decision Trees, Random Forests, and Deep Neural Networks (DNNs).
- **Key Outcome**: Random Forests and DNNs achieved >90% F1-score, outperforming Decision Trees.

## Dataset
- **Synthetic Data**: 5,000 samples, 16 features, 5 classes (balanced).
- **Sensor Simulation**: Based on MQ/TGS series gas sensors (chemiresistive principle).

## Models & Results
| Model          | Precision | Recall | F1-Score |
|----------------|-----------|--------|----------|
| Random Forest  | 0.92      | 0.91   | 0.91     |
| DNN            | 0.93      | 0.92   | 0.92     |
| Decision Tree  | 0.85      | 0.84   | 0.84     |

## Key Findings
1. **DNNs** performed best but require more computational resources.
2. **Random Forests** offered a balance of accuracy and interpretability.
3. **Synthetic Data** avoided class imbalance issues common in real-world datasets (e.g., SMILES).

## Applications
- Electronic noses (e-noses) for healthcare diagnostics.
- Environmental VOC monitoring.
- Multisensory AI development.

## Report Contents
1. **Methodology**: Dataset design and model architectures.
2. **Sensor Details**: MQ/TGS working principles.
3. **Comparative Analysis**: Model performance metrics.
4. **References**: OSHA/NIOSH thresholds, SMILES/DREAM datasets.

## Contributors
- Dhruti Avadhani  
- Aneesh Adithya SR  
- Buvica M  
- Gauravi Suryavamshi  

---
**License**: MIT  
**Note**: Refer to the full report for implementation details.
