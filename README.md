# 🛒 Price Optimization Using Python

This project explores **dynamic pricing strategies** using real-world-like data to analyze and optimize product pricing for a retail environment. Leveraging statistical analysis, machine learning, and visualization techniques, it compares a store's pricing and performance against competitors, calculates elasticity, and simulates the impact of price changes on sales and profit.

## 📊 Key Features

- 📈 **Data Analysis & Visualization**  
  - Price distribution comparison between store and competitors  
  - Sales trends over time  
  - Price vs sales amount scatter plots  
  - Price elasticity visualization  
  - Seasonal effects (holiday analysis)

- 🤖 **Dynamic Pricing Strategy**  
  - Customer segmentation based on pricing behavior  
  - Segment-wise elasticity calculation  
  - Rule-based price adjustments (e.g., increase/decrease based on elasticity)  
  - Recommended pricing engine based on demand sensitivity

- 🌲 **Machine Learning for Sales Prediction**  
  - Uses **Random Forest Regressor** to forecast item quantity  
  - Evaluates feature importance for price, competition price, and customer segments

- 🧪 **A/B Testing Simulator**  
  - Compares control (original) vs test (recommended) pricing  
  - Measures total and average sales per item

- 🔥 **Profit Optimization**  
  - Compares total profit under existing and optimized pricing  
  - Evaluates price sensitivity to changes in quantity and profit

- 🧠 **Scenario Simulation Tool**  
  - Projects impact of various price changes on quantity, revenue, and profit

- 🔮 **Price Forecasting (Optional)**  
  - Implements **Facebook Prophet** to forecast price trends

## 🧾 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Prophet)
- Data source: `Competition_Data.csv`
- IDE: Google Colab

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/price-optimization-python.git
   cd price-optimization-python
   ```

2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn prophet
   ```

3. Place your `Competition_Data.csv` in the working directory or update the path in the script.

4. Run the Python script:
   ```bash
   python price_optimization_using_python.py
   ```

## 📈 Example Visuals

- Price vs Sales Distribution
- Price Elasticity Over Time
- Dynamic vs Existing Pricing Revenue Comparison
- Heatmap: Elasticity by Segment and Bracket
- Prophet Forecast: Future Price Trend

## 🧠 Insights

- Competitors generally maintain more stable and higher pricing strategies.
- Demand responsiveness (elasticity) varies significantly over time and by product segment.
- Dynamic pricing outperforms static pricing in terms of profitability under simulated conditions.
- External factors like holidays have a measurable impact on price sensitivity and volume.

## 📂 Project Structure

```
price_optimization_using_python.py
Competition_Data.csv
README.md
```

## 📌 Future Improvements

- Incorporate real-time competitor pricing APIs
- Add advanced ML models (e.g., XGBoost, LightGBM)
- Integrate with dashboards (e.g., Streamlit)
- Introduce promotion and discount impact modeling

