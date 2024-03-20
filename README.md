# Fine-Tuned Image Classification with ResNet152
This project demonstrates fine-tuning a deep learning model based on ResNet152 for image classification task. The goal is to classify images into predefined categories using transfer learning and data augmentation techniques.



# Description
The project includes the following steps:

Data Preparation: Resize dataset, Split the dataset into training, validation, and test sets. Ensure proper labeling of images according to their categories.

Model Architecture: Load the pre-trained ResNet152 model without the top layers and add custom top layers for classification, including a global average pooling layer, dropout layer, and dense layers with ReLU activation for feature extraction and classification.

Training: Fine-tune the model by training all layers with the Adam optimizer and a lower learning rate. Implement data augmentation during training to enhance model generalization and prevent overfitting.

Evaluation: Evaluate the fine-tuned model on the test set to assess its performance in classifying images into the predefined categories. Measure metrics to evaluate model effectiveness.
