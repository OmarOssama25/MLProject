# Pneumonia Classification Using PyTorch

## Project Overview
This project aims to classify chest X-rays to detect pneumonia using various deep learning models implemented in PyTorch. The models evaluated include:

- Fully Connected Neural Network (FCNN)
- VGG16
- VGG19
- Inception

The dataset used for this project is the Chest X-Ray Images (Pneumonia) from Kaggle.

## Dataset
- **Source:** Kaggle Chest X-Ray Images (Pneumonia)
- **Description:** The dataset consists of chest X-ray images used to detect pneumonia in patients, including both normal and pneumonia-positive images.

## Models and Results

### 1. Fully Connected Neural Network (FCNN)
- **Optimizer:** Adam
- **Loss Function:** CrossEntropyLoss
- **Training Details:**
  - Images resized to a constant size.
  - Images reshaped into a vector for classification using fully connected layers.

### 2. VGG16
- **Optimizer:** Adam
- **Loss Function:** CrossEntropyLoss
- **Batch Size:** 32
- **Epochs:** 10
- **Results:**
  - Training Accuracy: 95.86%
  - Validation Loss: 0.1512
  - Validation Accuracy: 92.82%
  - Test Accuracy: 92%

### 3. VGG19
- **Optimizer:** Adam
- **Loss Function:** CrossEntropyLoss
- **Batch Size:** 32
- **Epochs:** 10
- **Results:**
  - Training Accuracy: 93.06%
  - Validation Loss: 0.1781
  - Validation Accuracy: 92.82%
  - Test Accuracy: 90.6%

### 4. Inception Architecture
- **Optimizer:** SGD
- **Loss Function:** CrossEntropyLoss
- **Batch Size:** 32
- **Epochs:** 10
- **Results:**
  - Training Accuracy: 97.16%
  - Validation Loss: 0.1081
  - Validation Accuracy: 96.92%
  - Test Accuracy: 96%

## Conclusion
The Inception architecture achieved the highest accuracy across training, validation, and test datasets. This indicates that the Inception model is more effective for classifying pneumonia from chest X-rays compared to VGG16 and VGG19 architectures.

## Additional Information
For detailed implementation steps, analysis, and code, refer to the project report.

## References
- **Dataset:** Kaggle Chest X-Ray Images (Pneumonia)
- **Institution:** Alexandria University CCE: Pattern Recognition, Faculty of Engineering
