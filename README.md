# Chest X-Ray Pneumonia Classifier (CNN)

A convolutional neural network that classifies chest X-ray images as **Normal** or **Pneumonia**, built and trained on Kaggle.

## 📓 Notebook

`notebook1eb1d28f3c.ipynb` — end-to-end image classification pipeline:

- Loads and preprocesses chest X-ray images
- Builds a CNN (`Conv2D` layers) for binary classification
- Trains with `binary_crossentropy` loss, tracking training/validation accuracy
- Evaluates model performance on a held-out test set

## 📊 Dataset

Built on the [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) dataset from Kaggle — X-ray images labeled as `NORMAL` or `PNEUMONIA`.

## 🛠️ Tools used

- Python
- TensorFlow / Keras
- Kaggle Notebooks

## 🚀 How to use

1. Open the notebook in [Kaggle Notebooks](https://www.kaggle.com/code) or download it and run locally with the dataset linked above
2. Attach/download the Chest X-Ray Pneumonia dataset
3. Run all cells to train and evaluate the model
