# Cat-vs-Dog-using-Transfer-Learning
# Overview
This project focuses on building a Cat-vs-Dog classifier using Transfer Learning, a popular technique in deep learning. Transfer learning allows us to leverage pre-trained convolutional neural network (CNN) models to perform image classification tasks with limited data. In this project, we aim to train a model to distinguish between images of cats and dogs by fine-tuning a pre-trained CNN model.

# Dataset
The dataset used for this project consists of images containing cats and dogs. The images are preprocessed and augmented to improve model generalization. The dataset is divided into training, and test sets to facilitate model training and evaluation.

# Transfer Learning
Transfer learning involves taking a pre-trained CNN model, such as VGG, and adapting it to a new task. In this project, we remove the fully connected layers at the top of the pre-trained model and replace them with new layers suitable for our classification task. We then fine-tune the model on our dataset to improve its performance.
