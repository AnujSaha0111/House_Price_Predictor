# Bangalore House Price Prediction
This Project predicts the price of a Real Estate property on the basis of Features like: `area_type`, `location`, `total_sqft`, `balcony`, `bathroom` and `BHK`

## 🌐 Live Demo
Visit the live application: [Bangalore House Price Predictor](https://anujsaha0111-house-price-predictor.streamlit.app/)

## 🏗 Project Structure
```plaintext
├── Bengaluru_House_Data.csv    # Original dataset
├── Bengaluru_Real_Estate_Price.ipynb    # Data analysis and model building
├── Cleaned_data.csv            # Preprocessed dataset
├── Columns.json                # Model features
├── bangalore_home_prices_model.pickle    # Trained model
├── app.py                      # Streamlit web application
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

<hr>

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- pip package manager

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/AnujSaha0111/house_price_predictor.git
   cd house_price_predictor
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application
   ```bash
   streamlit run app.py
   ```

<hr>

## 💡 Usage
1. Enter the required property details:
   - Total square footage
   - Number of balconies
   - Number of bathrooms
   - BHK (Bedroom, Hall, Kitchen)
   - Area type
   - Location
2. Click "Predict" to get the estimated property price

<hr>

## 🔧 Model Information
- The model is built using scikit-learn
- Features include area type, location, total square footage, balconies, bathrooms, and BHK
- Prices are predicted in lakhs/crores (Indian currency format)

<hr>

## Data Collection 

Data From Kaggle: https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data

<hr>

