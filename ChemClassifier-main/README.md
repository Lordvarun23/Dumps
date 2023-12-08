# ChemClassifier

ChemClassifier is a project that classifies the given dashed structure of a hydrocarbon into alkane, alkene, or alkyne using a Multi-Layer Perceptron (MLP). The MLP is trained on a dataset of hydrocarbons with known chemical structures which was collected by web scrappping.
## Dataset

The dataset used for this project consists of 200 hydrocarbons with known chemical structures. Each hydrocarbon is represented as a dashed structure, and the corresponding chemical structure is provided in the dataset. The dataset is split into 80% training data and 20% testing data. Data Augmentation was performed.
## Requirements

This project requires Python 3.x and the following libraries:

    pandas
    numpy
    scikit-learn
    Keras
    TensorFlow
