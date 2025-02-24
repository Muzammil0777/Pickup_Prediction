# GBR Model Predictor 📊  

This is a Streamlit web application that uses a pre-trained Gradient Boosting Regressor (GBR) model to make predictions based on user-inputted features. Simply input the required values, and the app will provide a predicted output along with a visualization of the input features.  

## Features  
- User-friendly interface with dynamic input fields for each required feature.  
- Scalable input data using `StandardScaler` for accurate predictions.  
- Real-time predictions with an option to visualize input data using bar charts.  
- Error handling for model loading and prediction processes.  

## Requirements  
- Python 3.x  
- Streamlit  
- scikit-learn  
- numpy  
- pandas  
- joblib  

## Installation  
1. Clone the repository:  
    ```bash
    git clone https://github.com/your-username/gbr-model-predictor.git
    cd gbr-model-predictor
    ```
2. Install the required dependencies:  
    ```bash
    pip install -r requirements.txt
    ```
3. Ensure the pre-trained model file (`best_gbr_model.pkl`) is in the root directory.  

## Usage  
Run the app using the following command:  
```bash
streamlit run app.py
