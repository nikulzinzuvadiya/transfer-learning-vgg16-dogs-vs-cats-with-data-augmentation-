# transfer-learning-vgg16-dogs-vs-cats-with-data-augmentation

This repository demonstrates transfer learning with the pre-trained VGG16 model for binary image classification on the "Dogs vs. Cats" dataset. It includes feature extraction with data augmentation, which enhances the model's ability to generalize by simulating real-world variations in the dataset.

The project highlights:

1.Dataset Management:

Automatic downloading and extraction of the "Dogs vs. Cats" dataset from Kaggle.
Augmentation techniques such as rotation, zoom, and flipping.

2.Model Architecture:

VGG16 pre-trained on imagenet as the base model.
Fully connected layers added for binary classification.

3.Transfer Learning:

Feature extraction by freezing the pre-trained convolutional layers.
Fine-tuning on the augmented "Dogs vs. Cats" dataset.

4.Visualization:

Plots of training and validation accuracy/loss over epochs.
