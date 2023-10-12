# Mobile Device Price Classification

## Project Description
This project aims to develop a machine learning model to classify mobile devices into different price categories based on their features. We have a dataset containing features of 2,017 mobile devices labeled with price categories such as "Cheap", "Normal", "Expensive", and "Very Cheap". The model is trained to predict these categories for new mobile devices, enabling store personnel to tag the devices quickly and accurately.

## Dataset
The dataset `mobil.csv` includes the following features:
- Battery Power
- Bluetooth Availability
- Clock Speed
- Dual Sim Availability
- Front Camera Megapixels
- 4G Availability
- Internal Memory
- Depth
- Weight
- Number of Processor Cores
- Primary Camera Megapixels
- Pixel Resolution Height
- Pixel Resolution Width
- RAM
- Battery Life
- 3G Availability
- Touchscreen Availability
- WiFi Availability
- Price Range (Target Variable)
- Color

## Installation and Usage
1. **Clone the repository:**
    ```bash
    git clone https://github.com/bozkuya/Mobile-Device-Price-Classification
    ```

2. **Install required Python packages (it's recommended to use a virtual environment):**
    ```bash
    pip install scikit-learn
    ```

3. **Execute the Python script:**
    ```bash
    python mobile_price_classifier.py
    ```

## Model
The project utilizes a Random Forest Classifier, optimized with GridSearchCV for hyperparameter tuning. The model is evaluated using accuracy, precision, recall, and F1-score metrics.

## Results
The optimized model achieved an accuracy of 92% on the test data. The detailed performance metrics are included in the project's Jupyter Notebook.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
