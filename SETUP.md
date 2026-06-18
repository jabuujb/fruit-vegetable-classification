# Setup Instructions

This document explains how to configure and run the CNN, DNN, and MLP fruit and vegetable classification notebooks.

## Dataset Setup

1. Download and extract the Fruit and Vegetable dataset.
2. Place the extracted dataset folder in a convenient location on your computer.
3. Verify that the following directories exist:

```text
train/
validation/
test/
imgTest/
```

## Update Dataset Paths

Each notebook contains hardcoded dataset paths. Update the following paths to match the location of your extracted dataset:

```python
for dirname, _, filenames in os.walk('path/to/Final Project Data'):
```

```python
train_dir = Path('path/to/Final Project Data/train')
```

```python
valid_dir = Path('path/to/Final Project Data/validation')
```

```python
test_dir = Path('path/to/Final Project Data/test')
```

```python
imgTest_dir = Path('path/to/Final Project Data/imgTest')
```

Repeat these updates for each notebook:

* cnn_classifier.ipynb
* dnn_classifier.ipynb
* mlp_classifier.ipynb

## Running the Models

Open the desired notebook in Jupyter Notebook, JupyterLab, or VS Code and run all cells.

Available models:

* CNN (Convolutional Neural Network)
* DNN (Deep Neural Network)
* MLP (Multi-Layer Perceptron)

## Testing Custom Images

Place custom images into the `imgTest` directory and rerun the prediction section of the notebook.

The model will classify the image into one of 51 produce categories and further categorize it as:

* Fruit
* Vegetable
* Unknown

## Dataset Source

This project is based on the Fruit and Vegetable Image Recognition Dataset by Kritik Seth and was extended from 36 to 51 classes for experimentation and evaluation.

## Reference

Kritik Seth, "Fruits and Vegetables Image Recognition Dataset," Kaggle, 2020.

https://www.kaggle.com/kritikseth/fruit-and-vegetable-image-recognition
