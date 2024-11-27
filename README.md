# Skin Cancer Classification Project

## Problem Statement
The goal of this project is to classify melanoma and other skin conditions using a convolutional neural network (CNN). Early detection of melanoma can save lives, making this an impactful problem to solve.

## Dataset
The dataset contains images of skin lesions, categorized into the following 9 classes:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Approach
1. A **custom CNN model** was built and trained to establish baseline performance.
2. **Transfer Learning** with MobileNetV2 was applied to leverage pre-trained weights.
3. **Fine-tuning** was performed by unfreezing some layers of the pre-trained model.

## Results
- **Test Accuracy**: 22.0%
- **Test Loss**: 3.88

## Challenges
- Limited dataset size and class imbalance affected performance.
- Task complexity requires more advanced models or larger datasets.

## Future Work
- Use larger, more diverse datasets.
- Experiment with advanced architectures like EfficientNet or ResNet.
- Apply hyperparameter tuning and additional data augmentation.

## Instructions to Run
1. Open the `.ipynb` file in Google Colab.
2. Follow the sequential steps in the notebook.
3. Ensure that the dataset paths are correctly set.

