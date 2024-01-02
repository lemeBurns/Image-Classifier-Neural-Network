
# Image-Classifier-Neural-Network

The Image-Classifier-Neural-Network is designed to recognize handwritten numbers from an image using the MNIST dataset.

## Description

This repository contains code for an image classifier built using PyTorch. The classifier is trained on the MNIST dataset and is capable of predicting digits in images. The provided neural network architecture employs Convolutional Neural Networks (CNNs) to effectively identify and classify hand-written digits.

## Requirements

- Python 3.1x
- PyTorch
- OpenCV (cv2)
- NumPy
- Matplotlib
- Pillow (PIL)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/lemeBurns/your-repository.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the MNIST dataset using the provided script or manually by running the Jupyter Notebook.

## Usage

To run the image classifier:

1. Ensure you have the required dependencies installed.
2. Execute the Jupyter Notebook or Python script.
3. The code trains a convolutional neural network on the MNIST dataset.
4. After training, the model is saved as `model_state.pt`.
5. Test the model by loading the trained model and making predictions on new images. Provide image paths for testing.

### Training

The code trains an image classifier using the MNIST dataset. Adjust the number of epochs or other hyperparameters in the provided code snippet in the Jupyter Notebook or Python script.

```python
#Training flow
for epoch in range(10): # train for 10 epochs
    for batch in dataset:
        # ... (rest of the training code)
```

### Testing

To test the trained model on new images, use the code snippet provided in the Jupyter Notebook or Python script. Update the image paths to test the classifier on different images.

```python
# Testing
img1 = Image.open('img_1.jpg')
# ... (rest of the testing code)
```

---
