# Fashion-MNIST Classification Project

# Project Overview
- The Fashion-MNIST project aims to classify images of fashion items into 10 distinct categories using deep learning techniques. This project uses the Fashion MNIST dataset, which includes 60,000 training and 10,000 test grayscale images, each of size 28x28 pixels.

# Goal
- To develop a model that surpasses the baseline performance by accurately classifying fashion images such as T-shirts, trousers, dresses, etc., with a targeted improvement in model accuracy to reach an F1 score between 92-95%.

# Data Description
- The Fashion MNIST dataset comprises grayscale images in 10 categories, representing a diverse range of fashion products. Each 28x28 pixel image is classified into one of the following categories: T-shirts/tops, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots.

# Methodology
- Data Preprocessing: Applied comprehensive data cleaning, including handling missing values and employing one-hot encoding and LabelEncoder for categorical data transformation.
- Model Development: Started with a baseline CNN model, followed by experiments with various architectures, including additional convolutional layers and filters, to improve performance.
- Model Enhancement Techniques: Incorporated data augmentation, dropout, and regularization techniques to enhance model accuracy and prevent overfitting.
-Performance Evaluation: Conducted detailed performance evaluations using F1 score, precision, and recall metrics.

# Results
- Baseline Model Performance: Achieved an F1 score of 89%.
- Improved Model Performance: The enhanced CNN model achieved a significant increase in accuracy, with an F1 score of 93%.
  
# Challenges
- Encountered challenges included managing the extensive training data volume, optimizing hyperparameters, and preventing overfitting. Further efforts were focused on fine-tuning the model to enhance accuracy and ensure effective generalization.

# Technologies Used
- Convolutional Neural Networks (CNN)
- Data augmentation
- Adam optimizer
- Batch normalization
- Dropout and L2 regularization
