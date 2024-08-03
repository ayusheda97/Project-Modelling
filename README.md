### Dog Breed Image Recognition using AI

This repository contains **Python** code for predicting dog breeds from images using advanced deep learning models. After evaluating the performance of multiple models, **Model_Name** is chosen as the best-performing one, thereby using it for the main predictions.

## Motivation

The ability to accurately identify dog breeds from images is not only a fun and engaging challenge but also has practical applications in areas such as veterinary care, pet adoption, and even lost pet recovery. According to the American Kennel Club (AKC), there are nearly 200 recognized dog breeds, each with distinct characteristics and traits. For pet owners, veterinarians, and animal shelters, the ability to swiftly and accurately identify a dog's breed can significantly aid in understanding the pet's behavior, health predispositions, and care requirements.

## Dataset

The dataset used for this project is sourced from Kaggle's Dog Breed Identification competition. It contains thousands of images across various breeds, providing a robust foundation for training a deep learning model. The data is structured as follows:
- **id**: The unique identifier for each image file.
- **breed**: The breed of the dog in the image.

The dataset contains 10,222 images, each associated with one of 120 unique dog breeds.

## Machine Learning Models

The Python code in this repository leverages **TensorFlow** and other relevant libraries to implement and evaluate several deep learning models, including:

- InceptionV3
- ResNet50
- Artificial Neural Network (ANN)

The code provides a comprehensive evaluation of each model's performance using various metrics like precision, recall, and F1-score. After evaluation, InceptionV3 is selected as the best-performing model for dog breed classification.

## Usage

![Static Badge](https://img.shields.io/badge/python-3?logo=python&logoColor=%2336454F&labelColor=%23808080) ![Static Badge](https://img.shields.io/badge/jupyter-lab?logo=jupyter&labelColor=%2336454F)

1. Download this Jupyter Notebook to your local machine.
2. Install the required dependencies mentioned.
3. Run the notebook cells step-by-step to:
    - Overview the data and perform EDA (Exploratory Data Analysis)
    - Pre-process the data to achieve the required format
    - Fit the models, evaluate, and compare them
    - Use the best-performing model for **dog breed prediction**

You will majorly need the following Python libraries to run this notebook. Use the command below to install them:

```pip install pandas tensorflow```

## Code Components

### 1) Data Preprocessing

This segment focuses on preparing the image data for model training. It includes:
- Resizing images to the required dimensions
- Normalizing pixel values
- Splitting the dataset into training and validation sets

### 2) Model Training and Evaluation

This segment involves:
- Implementing and training multiple deep learning models, including vit_l32, EfficientNetB4, InceptionResNetV2, MobileNetV2, Xception and DenseNet201
- Evaluating model performance using accuracy, precision, recall, and F1-score
- Selected the top 3 performing algorithms out of 6 and building a combined model to get a better accuracy

### In Progress

## Contribution

Contributions to this repository are welcome! If you would like to suggest better ML models, improve data preprocessing, or enhance any segment of the project, feel free to open a pull request.

## License

This project is licensed under the MIT License.

## Credits

This project is in collaboration with [Ayush Heda](https://github.com/ACM40960/project-hedayush97).

Thank you for using our Jupyter Notebook!
