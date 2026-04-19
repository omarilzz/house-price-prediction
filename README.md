# House Price Prediction Model

### Project Overview
This project predicts housing prices using a linear regression model. Through exploratory data analysis, I identified 'area' as the primary feature driving property value and built a streamlined model that achieves high predictive accuracy.

### Key Technologies
* Python (Pandas, NumPy, Scikit-Learn)
* Matplotlib/Seaborn for visualization
* GitHub for version control

### Model Performance
* **R-squared Score:** 0.9828 (The model explains ~98% of the variance).
* **Mean Absolute Error (MAE):** ~48,450

### Key Learnings
* **Feature Selection:** Dropped irrelevant features (correlation ~0.00) to prevent overfitting.
* **Validation:** Verified that training and test scores are nearly identical, ensuring the model generalizes well to new data.

### How to Run
1. Clone this repository.
2. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
3. Install dependencies: `pip install -r requirements.txt`
