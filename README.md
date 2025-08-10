# housing_data_linear_regression
Housing Prices Prediction using Regression
 
The model is trained on historical housing data, learns relationships between house features and prices, and then predicts the price for unseen houses.

---


## ⚙️ Steps Performed
1. **Data Preprocessing**
   - Checked for missing values and handled them.
   - Encoded categorical variables.
   - Scaled numerical features for better model performance.

2. **Model Training**
   - Used **Linear Regression** as the baseline model.
   - Trained on **70% of the dataset**, tested on **30%**.

3. **Evaluation**
   - Metrics used:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
     - R² Score
   - Plotted **Actual vs Predicted Prices**.

---

## 📊 Model Performance
| Metric | Value |
|--------|-------|
| MAE    | 970043.40 |
| MSE    | 1754318687330.66 |
| RMSE   |1324506.96 |
| R²     | 0.65 |



---

## 📈 Visualization
The **Actual vs Predicted Prices** plot shows:
- Each point represents a house.
- The **red regression line** indicates the predicted relationship between actual and predicted prices.
- Points closer to the line indicate more accurate predictions.
