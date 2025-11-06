AI/ML Intermediate Project
# Weather Prediction with Machine Learning

## Overview
This project predicts temperature using weather parameters such as humidity, wind speed, visibility, and pressure. It applies both Linear Regression and Random Forest Regressor models to forecast temperature values based on historical weather data. The project also includes an interactive Gradio application for real-time predictions.

## Dataset
- Dataset Name: Weather History
- Source: https://www.kaggle.com/datasets/muthuj7/weather-dataset
- Description: The dataset contains weather conditions including temperature, humidity, pressure, and visibility.
- Note: The dataset was used directly from the CSV file without additional downloads during notebook execution.

## Project Workflow
1. **Data Loading and Inspection**
   - Loaded `weatherHistory.csv` and examined structure, missing values, and features.
   - Handled missing entries in the `Precip Type` column.

2. **Data Preprocessing**
   - Encoded categorical columns such as precipitation type.
   - Selected key numeric features for model training.
   - Split the data into training and testing sets.

3. **Model Training**
   - Trained two models: Linear Regression and Random Forest Regressor.
   - Evaluated models using MAE, RMSE, and R² score.

4. **Model Performance**
   - **Linear Regression**
     - MAE: 0.742
     - RMSE: 0.948
     - R²: 0.990
   - **Random Forest Regressor**
     - MAE: 0.012
     - RMSE: 0.044
     - R²: 1.000

   The Random Forest model achieved near-perfect accuracy, indicating excellent performance on this dataset.

5. **Gradio Web App**
   - A Gradio-based interactive web app allows users to input weather conditions such as humidity, visibility, and pressure to predict temperature instantly.
   - Interface includes sliders and radio buttons for easy input.
   - The app can be launched locally or shared publicly via a generated link.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Gradio
- Matplotlib (for visualization)

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/weather-prediction-ml.git
   cd weather-prediction-ml
   ```

## Contributing
Contributions are welcome!
Feel free to fork the repository, improve the game, and open a pull request. Let's grow this classic game together!

## License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

## Author
**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)


