# SkinEctive-ML

## Overview

SkinEctive is a mobile application designed to facilitate early detection of skin diseases using advanced machine learning and mobile technology. The app leverages camera capabilities and EfficientNetB0 Convolutional Neural Network architecture to provide accurate identification of suspicious skin conditions, empowering users to seek timely medical intervention.

## Dataset

- **Source:** [Link to the dataset on Kaggle](https://www.kaggle.com/datasets/subirbiswas19/skin-disease-dataset)
- **Description:** The dataset consists of 8 classes representing different skin diseases. The data is divided into three subsets: 2214 images in data train, 187 images in data validation, and 234 images in data test.
- **Preprocessing Steps:**
  - Step 1: Resize image to (224,224)
  - Step 2: Use the preprocess_input() fuction from Tensorflow EfficientNet

## Exploratory Data Analysis (EDA)
**Distribution of each class:**
- Train Subset
  - Cellulitis: 324 images
  - Impetigo: 192 images
  - Athlete foot: 297 images
  - Nail fungus: 309 images
  - Ringworm: 216 images
  - Cutaneous larva migrans: 240 images
  - Chickenpox: 324 images
  - Shingles: 312 images

- Validation Subset
  - Cellulitis: 28 images
  - Impetigo: 16 images
  - Athlete foot: 25 images
  - Nail fungus: 26 images
  - Ringworm: 18 images
  - Cutaneous larva migrans: 20 images
  - Chickenpox: 28 images
  - Shingles: 26 images

- Test Subset
  - Cellulitis: 34 images
  - Impetigo: 20 images
  - Athlete foot: 32 images
  - Nail fungus: 33 images
  - Ringworm: 23 images
  - Cutaneous larva migrans: 25 images
  - Chickenpox: 34 images
  - Shingles: 33 images


## Modeling

- **Models Used:** EfficientNetB0 with Adamax Optimizer
- **Evaluation Metrics:** accuracy, recall, precision, f1-score, confusion matrix

## Usage
1. Open Kaggle. Go to [the dataset on Kaggle](https://www.kaggle.com/datasets/subirbiswas19/skin-disease-dataset) and sign in with your Kaggle account.
2. Create a New Notebook. Click on "File" in the top-left corner of the Kaggle interface and select "New Notebook" to create a new notebook.
3. You can clone this repo or just download the notebook.
4. Open the notebook in Kaggle.
5. Run the notebook.
