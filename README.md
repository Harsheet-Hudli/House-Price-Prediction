# 🏠 House Price Prediction

A Machine Learning web application that predicts house prices based on property details such as location, total square feet, number of bedrooms (BHK), and bathrooms. The application is built using Python, Streamlit, and a Random Forest Regression model.

## 🚀 Features

- Predicts house prices instantly
- User-friendly Streamlit interface
- Location-based price estimation
- Market price comparison with similar properties
- Price insights (Underpriced, Fairly Priced, or Overpriced)
- Histogram visualization for market comparison

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib

## 📂 Project Structure

```
House Price Prediction/
│── app.py
│── cleaned_df.csv
│── Bengaluru_House_Data.csv
│── rf_model.joblib
│── model_columns.joblib
│── requirements.txt
│── eda.ipynb
│── house_logo.png
│── hdlogo.webp
```

## 📊 Machine Learning Model

- Algorithm: Random Forest Regressor
- Dataset: Bengaluru House Price Dataset
- Model Serialization: Joblib

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
```

2. Navigate to the project folder

```bash
cd House-Price-Prediction
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the application

```bash
streamlit run app.py
```

## 📌 Input Features

- Location
- Total Square Feet
- Number of Bedrooms (BHK)
- Number of Bathrooms

## 📈 Output

- Predicted House Price
- Market Price Insight
- Comparison with Similar Properties
- Price Distribution Visualization

## 📚 Future Improvements

- Improve prediction accuracy
- Add more property features
- Deploy on Streamlit Cloud
- Interactive analytics dashboard

## 👨‍💻 Author

**Harsheet Hudli**

GitHub: https://github.com/Harsheet-Hudli
