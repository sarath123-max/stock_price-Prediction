Sure! Here's a complete and clean `README.md` file tailored to your stock price prediction project using `RandomForestRegressor`:

---

# 📈 Stock Price Prediction Using Random Forest

This project demonstrates how to build a machine learning model to predict stock closing prices based on historical market data using a **Random Forest Regressor**.

## 🗂️ Overview

We use a supervised machine learning approach to predict the **closing stock price** using the following features:

- Open price
- High price
- Low price
- Volume of stocks traded

The model is trained and evaluated using **scikit-learn's RandomForestRegressor**, and performance is measured using **Mean Squared Error (MSE)**.

---

## 📁 Dataset

The dataset used is a cleaned CSV file named `cleaned_stock_data.csv`. It contains the following columns:

- `Date`: Date of the trading session
- `Open`: Opening stock price
- `High`: Highest stock price during the session
- `Low`: Lowest stock price during the session
- `Close`: Closing stock price (Target)
- `Volume`: Number of shares traded

> Ensure this file is placed in the same directory as the script.

---

## ⚙️ Libraries Used

- `pandas` – Data manipulation and preprocessing
- `scikit-learn` – Model training and evaluation

You can install the required libraries with:
```bash
pip install pandas scikit-learn
```

---

## 🧠 Model Description

- **Algorithm:** Random Forest Regressor
- **Train-Test Split:** 80% training, 20% testing
- **Target Variable:** `Close`
- **Features Used:** `Open`, `High`, `Low`, `Volume`

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
   ```

2. Ensure the dataset `cleaned_stock_data.csv` is in the project folder.

3. Run the script:
   ```bash
   python stock_prediction.py
   ```

4. Output:
   ```
   Mean Squared Error: <value>
   ```

---

## 📊 Sample Code Output

```
Mean Squared Error: 1.234567
```

> The value will vary depending on your data and model parameters.

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 📬 Contact

For questions or suggestions, feel free to reach out or open an issue.

---

Let me know if you'd like to add visuals (like plots or feature importance) or expand this project further!
