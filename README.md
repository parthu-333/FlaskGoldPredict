# Gold Price Prediction using Flask
## Overview
This Project is a **Gold Price Prediction Web Application** built using **Flask** for the backend, a machine model for prediction, and a simple frontend for user interaction. The model predicts gold prices based on historical data and relevant economic indicators.
## Features
- Web-based interface for prediction gold prices
- Machine learning model trained on historical gold price data
- Flask backend to handle API requests
- Interactive UI for user input and prediction results
- Deployed locally
## Technology Used
- **Fronted**: HTML, CSS, Javascript
- **Backend**: Flask(Python)
- **Machine Learning**: Scikit-learn, Pandas, NumPy;
- **Algoritmes**: Polynomial regression
- **Deployment**: Flask server
## DataSet

## Installation and Setup
### Prerequisites
Ensure you have the followig installed:
- Python 3.7+
- Pip(Python package manager)
- Virtual environment (Optional but recommended)
### Steps to run locally
1. **Clone the Repository
```
git clone https://github.com/parthu-333/FlaskGoldPredict.git
cd FlaskGoldPredict
```
2. **Install Dependencies**
```
pip install
```
3. **Run the Flask App**
```
python app.py
```
4. **Access the Web Application** Open your browser and go to:
```
http://127.0.0.1:5000/
```
## API Endpoints

| Endpoint  | Method | Description |
|-----------|--------|-------------|
| `/`       | GET    | Home page |
| `/predict`| POST   | Predicts gold price based on input data |
## Screenshots
### Home Page
### Predictin Result
## Future Improvements
- Improve the machine learning model accuracy
- Add more economic indicators as features
- Deploy on a cloud platform
- Improve UI with better visualization
