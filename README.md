# DogCatVGG16_Model
This project demonstrates how to use TensorFlow/Keras and VGG16 for classifying dog and cat images. The VGG16 model, pre-trained on ImageNet, is fine-tuned to distinguish between dogs and cats in the dataset.
**Key Features:**
Transfer Learning: Uses the pre-trained VGG16 model for feature extraction and fine-tunes it with custom layers for binary classification.
Data Augmentation: Random transformations (e.g., shearing, zooming, and horizontal flipping) are applied to the training dataset to improve model performance.
Callbacks: Implements early stopping, learning rate reduction, and model checkpointing for efficient training.
Model Evaluation & Visualization: Displays accuracy and loss curves for training and validation, and shows predictions with sample images.
**Requirements:**
TensorFlow/Keras
Matplotlib
NumPy
**Dataset:**
The model is trained using the Dogs vs Cats dataset, which can be downloaded from Kaggle. The dataset should be organized as follows:

/PetImages
    /train
        /Cat
        /Dog
    /validation
        /Cat
        /Dog
**Usage:**
Training: Use the provided code to train the model on the dog vs cat images.
Evaluation: The model's performance is evaluated on a separate validation set.
Visualization: Random images are displayed alongside the true labels and predicted results for model evaluation.
