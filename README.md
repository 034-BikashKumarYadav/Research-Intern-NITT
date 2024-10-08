# Research-Intern-NITT
# Project Title:AI-Driven Colorectal Cancer Detection Using Machine Learning and  Deep Learning
* Fine-tuning an image classification model on a Colorectal-Cancer-medical image dataset.
* This is a biological 8-class classification problem.
* The dataset consists of 5000 images.
* Each example is a 150 x 150 x 3 RGB image of one of 8 classes.
* The class labels are: ("tumor", "stroma", "complex", "lympho", "debris", "mucosa", "adipose", "empty")
* The state-of-the-art CNN, ResNet50V2, is used as base model.
* The last 10 layers of the base model are unfreezed for fine-tuning.
* Data augmentation is implemented for regularization.
* Learning rate reduction callback is implemented.
* F1-score and confusion matrix are visualized.
* Accuracy of 90% is achieved on validation and test datasets.
* Dataset Source: https://zenodo.org/record/53169#.XGZemKwzbmG
  
