# House_Price_Prediction
Machine learning model to predict housing prices using Linear Regression.


A machine learning project to predict housing prices based on multiple property features using **Linear Regression**.  
This project demonstrates the complete workflow: **data preprocessing → exploratory data analysis (EDA) → feature scaling → model training → evaluation**.

---

## 📌 Features
- Load and inspect housing dataset.
- Handle categorical variables and convert them into numerical form.
- Standardize numerical features for better model performance.
- Perform exploratory data analysis with correlation heatmaps and histograms.
- Train a **Linear Regression** model using `scikit-learn`.
- Evaluate the model using **R² score**.

---

## 📊 Technologies Used
- **Python 3.x**
- **pandas** – Data handling
- **numpy** – Numerical operations
- **matplotlib** – Visualization
- **seaborn** – Heatmaps & statistical plots
- **scikit-learn** – Data preprocessing, model training, evaluation

---

## 📂 Dataset
- **File:** `Housing.csv`  
- Contains features like:
  - `area`
  - `bedrooms`
  - `bathrooms`
  - `stories`
  - `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`
  - `furnishingstatus`
  - `price`

---

## ⚙️ Installation
#1. Clone the repository:
   ```bash
   git clone https://github.com/Yokitha-07/house_Price_Prediction

#2. Navigate to the project directory:
cd housing-price-prediction

#3. Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn

🚀 Usage

#1. Place the dataset file Housing.csv in the project directory.

#2. Run the script:

python housing_price_prediction.py


#3. The script will:

- Preprocess the data

- Display correlation heatmap & histograms

- Train a Linear Regression model

- Output the model’s R² score (accuracy)
  
#📈 Example Output

- Correlation Heatmap:


- R² Score Example:

Model Accuracy (R²): 84.25%

#🔮 Future Improvements

- Try other algorithms (Random Forest, Gradient Boosting).

- Apply cross-validation for more robust evaluation.

- Tune hyperparameters for better performance.'

- Deploy as a web app using Flask or Streamlit.
