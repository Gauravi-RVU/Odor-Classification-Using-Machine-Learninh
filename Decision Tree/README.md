Scent Classification Using Decision Tree
This project uses a Decision Tree classifier to predict the scent family of chemical compounds based on concentrations of various chemicals recorded by sensors. The model performs multi-class classification to identify different scent families (e.g., Alcoholic, Chemical, Fruity, Gasoline-like, Sweet) based on sensor data.

Model Info
Model Type: Decision Tree Classifier (Entropy Criterion)

Features Used: Chemical compound concentration values from 16 different sensors

Target: Scent family (multi-class classification)

Dataset Size: 5000 samples

Train/Test Split: 90% / 10%

Model Performance
Accuracy: 75.6% on the test set

F1 Score: 0.76 (Weighted Average)

Confusion Matrix: Detailed in the output section of the notebook

Files Description


decision_tree_scent_classification.ipynb: Jupyter notebook containing the code to train, evaluate, and save the Decision Tree model.

label_encoder.pkl: Stores the label encoder used to transform string class labels to integers.

odor_dataset_final.csv: The dataset used for training and testing the model, containing 5000 samples and 16 chemical features.
