# Human Activity Recognition using Smartphone Sensors

## Overview

This project involves the collection of data using smartphone sensors placed on different body parts, including the wrist, belly, shoulder, ankle, pant pocket, etc. Various metrics such as accelerometer, gyroscope, gravity, rotation vector, etc., were recorded across three dimensions (x, y, z). The goal was to classify human activities, including standing, walking, sitting, upstairs movement, downstairs movement, and running, based on these input parameters.

## Data Collection

- **Sensor Placement:**
  - Smartphone sensors were strategically placed on different body parts to capture a diverse range of movements and postures.

- **Recorded Metrics:**
  - Metrics such as accelerometer, gyroscope, gravity, rotation vector, etc., were recorded to capture the dynamic aspects of human activities.

- **Activity Labels:**
  - Human activities were labeled, including standing, walking, sitting, upstairs movement, downstairs movement, and running.

## Machine Learning Models

The collected data was used to train machine learning models for activity recognition. The following classifiers were employed:

1. **Decision Tree**
2. **Random Forest**
3. **XGBoost**
4. **Extra Tree Classifier**

## Model Performance

The models were evaluated using various performance metrics:

| Classifier             | Min Accuracy | Max Accuracy | Precision | Recall | F1-Score |
|------------------------|--------------|--------------|-----------|--------|----------|
| Decision Tree          | 80.08%       | 81.20%       | 0.809     | 0.807  | 0.808    |
| Random Forest          | 90.56%       | 91.29%       | 0.92      | 0.90   | 0.91     |
| XGBoost                | 89.00%       | 90.34%       | 0.895     | 0.880  | 0.885    |
| Extra Tree Classifier  | 93.39%       | 94.07%       | 0.94      | 0.93   | 0.93     |

## Conclusion

The models demonstrated varying performance across different metrics. Extra Tree Classifier emerged as the top-performing model, exhibiting high accuracy, precision, recall, and F1-Score. The choice of classifier can be tailored based on specific requirements, considering factors such as precision, recall, and overall accuracy.

This project provides valuable insights into human activity recognition using smartphone sensors, with implications for applications in health monitoring, fitness tracking, and more.
