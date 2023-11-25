# CIFAR-100-Classification-using-Custom-Model
ResNet with Dropout for CIFAR-100 Image Classification. Explore this IPython notebook for a resilient CNN. Trained with ResNet architecture and dropout for enhanced accuracy on CIFAR-100 images. Model weights included for immediate use or further exploration. Dive into deep learning for robust image classification

## Prerequisites

Ensure you have the following dependencies installed:

- Python 3
- TensorFlow 2.x
- Jupyter Notebook

```bash
pip install tensorflow jupyter
```

## Model Architecture
The model is built upon the ResNet architecture with the incorporation of dropout for regularization. The IPython notebook (model.ipynb) provides a detailed overview of the architecture.

## Data Augmentation
Data augmentation is employed using TensorFlow's ImageDataGenerator for training enhancement. Augmentation includes rotation, width shift, height shift, and horizontal flip.

## Training
The model is trained using the Adam optimizer, a popular optimization algorithm, with categorical cross-entropy as the loss function. 

## Results
After 50 epochs with a batch size of 64, the model achieves an accuracy of 64.89% on the test set. Refer to the notebook for detailed evaluation metrics.

Feel free to explore and experiment! If you encounter issues or have suggestions, please open an issue.

Happy coding! 🚀
