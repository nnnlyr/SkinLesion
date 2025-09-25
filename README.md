# SkinLesion

## Project Overview
A deep learning-based system for classifying skin lesions into three categories: Melanoma (MAL), Nevus (NV), and Benign lesions. This project compares traditional machine learning methods (SVM, Random Forest) with deep learning approaches (CNN, ResNet-50) for medical image classification.

## Key Features
- **Multi-class classification of skin lesions using ISIC dataset**

- **Comparison of traditional ML vs deep learning approaches**

- **Advanced data preprocessing with oversampling and augmentation**

- **Comprehensive evaluation metrics (Accuracy, Sensitivity, Specificity)**

- **ResNet-50 architecture with transfer learning**

## Performance Results
| Metric             | SVM     | RF      | CNN     | ResNet-50 |
|--------------------|---------|---------|---------|-----------|
| Overall Accuracy   | 0.6243  | 0.6224  | 0.5979  | 0.7718    |
| Overall Sensitivity| 0.4049  | 0.4482  | 0.6006  | 0.7704    |
| Overall Specificity| 0.7161  | 0.7444  | 0.7995  | 0.8861    |

## Technical Implementation
- **​​Data**​​: ISIC 2018 dataset with 7 original classes grouped into 3 categories

- **​​Preprocessing**​​: Oversampling, data augmentation, and normalization

- **Models**​​: SVM, Random Forest, CNN, ResNet-50

- **​​Evaluation**​​: Confusion matrices, classification reports, performance metrics

## Key Findings
- **ResNet-50 significantly outperforms traditional methods**

- **Deep learning models better capture complex image features**

- **Data augmentation crucial for handling class imbalance**

- **Transfer learning with ResNet-50 provides best results**

For detailed implementation and results, see the full project documentation and code.
