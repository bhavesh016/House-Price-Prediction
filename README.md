# House Price Prediction

## Objective
To develop and evaluate machine learning models for predicting house prices based on property characteristics and amenities.

## Dataset
- Dataset: Housing.csv
- Rows: 545
- Columns: 13
- Target Variable: Price

## Models Used
- Linear Regression
- Random Forest Regressor

## Results

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 970,043 | 1,324,507 | 0.653 |
| Random Forest Regressor | 1,021,546 | 1,400,566 | 0.612 |

## Key Findings
- Area was the most influential feature affecting house prices.
- Bathrooms, stories, and parking facilities also contributed significantly.
- Linear Regression outperformed Random Forest with a higher R² score.
- Location and amenities had a noticeable impact on house prices.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
HousePricePrediction_BhaveshBhaisare
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
└── charts
    ├── histogram.png
    ├── heatmap.png
    └── scatter.png
```

## Conclusion
Machine learning models can effectively estimate house prices using property characteristics. Linear Regression achieved the best performance on this dataset.
