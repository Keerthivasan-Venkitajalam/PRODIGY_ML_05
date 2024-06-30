# FoodCal: Food Recognition and Calorie Estimation

**FoodCal** is an advanced AI tool designed to recognize food items from images and estimate their calorie content. This facilitates users in tracking their dietary intake and making informed food choices. The project is based on a deep learning model trained with the Food-101 dataset.

## Features

- **Food Recognition**: Employs a convolutional neural network (CNN) to identify a variety of food items from images.
- **Calorie Estimation**: Calculates the calorie content for recognized food items.
- **Nutritional Insights**: Provides comprehensive nutritional information to help users manage their diet.
- **Customizable Database**: Supports adding new food items and updating nutritional information.
- **Cross-Platform Compatibility**: Works seamlessly on both mobile and desktop platforms.

## Dataset

This project utilizes the [Food-101 dataset](https://www.kaggle.com/dansbecker/food-101) from Kaggle, which includes 101,000 images covering 101 different food categories.


## Model Training

The model is trained using a convolutional neural network (CNN) architecture, leveraging transfer learning from a pre-trained network (e.g., ResNet50). The training process is detailed in the `food_detection.pynb` notebook.

## Usage

1. **Upload an image**: Submit an image to the model for analysis.
2. **Receive feedback**: The model provides the recognized food item and its estimated calorie content.
3. **Track dietary intake**: Utilize the detailed nutritional insights to manage and track dietary intake effectively.

## Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. Evaluation results and relevant visualizations can be found in the `food_detection.pynb` notebook.
