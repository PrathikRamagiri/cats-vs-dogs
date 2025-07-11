# cats-vs-dogs

#   Cats vs Dogs Classification

This project implements an image classification model to distinguish between dogs and cats using deep learning. It uses Google Colab with a free T4 GPU and includes all necessary steps from dataset download to model training, evaluation, and result visualization.

##  Project Contents:

- **Source Code and Result.ipynb**: Main Jupyter notebook containing:
  - Dataset loading
  - Performance evaluation
  - Visualizations of predictions
  - Image preprocessing
  - Model building using CNN (Keras/TensorFlow)
  - Training and validation


## Dataset

The dataset is hosted on Google Drive and can be downloaded using:

```python
https://drive.google.com/uc?id=12WhCCpKTWpeBztLegcoYx2gMo2KbaxDG
```

Unzip the file after downloading and organize the directory as expected by the code.

## Model Overview

- **Architecture**: Convolutional Neural Network (CNN)
- **Framework**: TensorFlow / Keras
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Metrics**: Accuracy
- **Epochs**: Set in the notebook

## Desired Output

- Training vs. Validation Accuracy and Loss graphs
- Confusion matrix and classification report
- Sample predictions with image previews and predicted labels

## Results

The notebook displays predictions for test images, including whether the model correctly classifies them as a cat or a dog.
