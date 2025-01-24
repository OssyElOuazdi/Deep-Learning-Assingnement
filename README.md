# Deep Learning Assignment: Time Series Prediction & Image Classification

This repository contains the implementation of two deep learning tasks :

1. **Task 1 : Time Series Prediction using LSTMs**  
   Predicting weather-related variables such as temperatures and rainfall using Long Short-Term Memory (LSTM) models.

2. **Task 2 : Image Classification using CNNs**  
   Classifying images of animals into seven categories: Bear, Camel, Chicken, Elephant, Horse, Lion, and Squirrel, using Convolutional Neural Networks (CNNs).

---

## Key Features

### Time Series Prediction
- Preprocessing and feature engineering for temporal data.
- Implementation of LSTMs to capture long-term dependencies.
- Forecasting temperature and rainfall variables with future predictions.

### Image Classification
- Exploratory Data Analysis (EDA) and preprocessing of image data.
- CNN model design and training for classifying images into categories.
- Evaluation using metrics such as accuracy, confusion matrix, and classification report.

---

## Datasets

The datasets required for this project can be downloaded from the following Google Drive folder:  
[Download Datasets]([https://drive.google.com/your-link-here](https://drive.google.com/drive/folders/19Lo1TDWRM0UEoAkCQxL03G5g_nwgofZp?usp=drive_link))

- **Time Series Prediction Dataset**: `TemperatureRainFall.csv`
- **Image Classification Dataset**: `DeepLearningTask-1.7z`

Ensure to download the datasets and place them in appropriate locations as specified in the notebooks, or update the paths accordingly.

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/OssyElOuazdi/deep-learning-assignment.git
   ```
2. Navigate to the desired notebook (`DeepLearning_Task1.ipynb` or `DeepLearning_Task2.ipynb`).
3. Ensure the required datasets are present in the specified paths or modify paths as necessary.
4. Ensure the dependencies are installed.
5. Run the notebooks to explore the implementation and results.

---

## Results

- **Time Series Prediction**: Achieved promising results for temperature variables, with room for improvement in predicting rainfall due to its variability.
- **Image Classification**: Achieved 61% accuracy on test data, with strong performance in some categories and challenges in others.

---

## Room for Improvement

- **Time Series**: Incorporating additional features and experimenting with advanced models like transformers.
- **Image Classification**: Balancing datasets, hyperparameter tuning, and exploring deeper CNN architectures.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to contribute or raise issues for any clarifications or suggestions!

   
