Scent Classification Using Neural Network (Keras)
This project uses a Neural Network classifier implemented with Keras to predict the scent family of chemical compounds based on concentrations of various chemicals recorded by sensors. The model achieves a high accuracy of 94.2% on the test set.

Model Info
Model Type: Neural Network (Keras with Dense layers)

Features Used: 16 chemical compound concentration values

Target: Scent family (multi-class classification)

Dataset Size: 5000 samples

Train/Test Split: 80% / 20%

Model Performance
Accuracy: 94.2% on the test set

Loss: 0.1662

F1 Score: Calculated in the notebook

Confusion Matrix: Available in the notebook

Files Description


scent_classification_neural_network.ipynb: Jupyter notebook for training, evaluating, and saving the neural network model.

label_encoder.pkl: Stores the label encoder used to transform string class labels to integers.

odor_dataset_final.csv: The dataset used for training and testing the model, containing 5000 samples and 16 chemical features.

