# House Price Prediction App

## Overview
The House Price Prediction App is a machine learning-based web application that estimates the market value of a house based on various features such as location, size, number of bedrooms, and more. It is designed to help users make informed decisions when buying or selling real estate.

## Features
- **User-Friendly Interface**: Intuitive design for entering property details.
- **Accurate Predictions**: Utilizes a trained machine learning model for reliable price estimations.
- **Data Visualization**: Insights and trends for better understanding of the housing market.
- **Customizable Filters**: Tailor predictions based on specific criteria like location and property type.

## Technology Stack
- **Frontend**: Java Script
- **Backend**: Flask
- **Machine Learning Model**: Scikit-learn Leniar Regression

### Prerequisites
- Python 3.8+
- pipenv or virtualenv for managing Python dependencies

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Access the app in your browser at `http://localhost:5000`.

## Usage
1. Open the app in your browser.
2. Enter details about the property, such as location, size, number of bedrooms, and bathrooms.
3. Click the "Estimate Price" button to get the estimated market value.


## Project Structure
```plaintext
house-price-prediction/
├── app.py               # Main application file
├── templates/           # HTML templates for the frontend
├── static/              # Static files (CSS, JavaScript, images)
├── models/              # Machine learning model files
├── data/                # Dataset files
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Model Training
If you wish to retrain the model:
1. Place your dataset in the `data/` folder.
2. Run the `train_model.py` script:
   ```bash
   python train_model.py
   ```
3. Replace the existing model file in the `models/` directory with the newly trained model.

## Contributing
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your branch:
   ```bash
   git push origin feature-name
   ```
4. Submit a pull request.

## Contact
For questions or feedback, feel free to contact us at mashrubhavya5@gmail.com.
