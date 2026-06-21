# House-Price-Prediction
# 🏡 Real Estate Price Prediction

## 📌 Overview

Real estate valuation often relies on guesswork. This project eliminates uncertainty by building a machine learning regression model to predict house prices based on features like size, rooms, and amenities. It includes a complete data pipeline: from exploration and cleaning to model training, evaluation, and visualization.

## 🛠️ Tech Stack

**Python 3.x** | **Pandas** | **Scikit-learn** | **Matplotlib & Seaborn**

## ⚙️ Methodology

Using a dataset of 545 residential properties, the data was cleaned, categorically encoded (binary mapping and one-hot encoding), and split into 80/20 training and testing sets. Two predictive models were trained and compared:

* **Linear Regression** (Baseline)
* **Random Forest Regressor** (Ensemble)

Models were evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and the R² Score.

## 📈 Key Findings

The **Linear Regression** model proved slightly more reliable for this dataset, explaining roughly **65.3%** of the variance in house prices (R² = 0.6529).

By analyzing feature importances from the Random Forest model, the data revealed actionable market insights:

1. **Space is Premium:** Total property area is the strongest price predictor, driving roughly 47% of the model's weight.
2. **Bathrooms Over Bedrooms:** Buyers heavily prioritize bathrooms (15% importance) over extra bedrooms (4.8%).
3. **Valuable Amenities:** Air conditioning and parking availability are the most lucrative secondary additions.
4. **Location Nuance:** Surprisingly, being situated on a "mainroad" had a negligible statistical impact (~1.0%) compared to the physical traits of the property itself.

## 💼 Business Value

This analysis provides data-driven strategies for real estate professionals. Agents should emphasize square footage and bathroom counts in listings, while sellers looking for high-ROI renovations should prioritize adding air conditioning or extra bathrooms over additional bedrooms.

## 🚀 Quick Start

1. Clone the repository.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Run the Jupyter Notebook to view the full analysis, statistical breakdown, and visual charts.
