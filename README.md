# Stock Price Prediction using Machine Learning

This project predicts stock prices using machine learning models like Linear Regression, Decision Tree, KNN, and SVM. An ensemble model (Voting Regressor) is used to combine the predictions of these models to improve accuracy. Additionally, sentiment analysis is performed using news data to capture the impact of significant news events on stock prices.

## Features
- Uses real-time stock data from Yahoo Finance.
- Predicts future stock prices based on historical data and news sentiment.
- Combines multiple regression models for enhanced accuracy.
- Incorporates sentiment analysis to capture market sentiment impact.
- Evaluates performance with metrics like MSE, MAE, and R².

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/username/stock-price-prediction.git
cd stock-price-prediction
pip install -r requirements.txt
```

## Usage
1. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Project_1.ipynb
   ```
2. Follow the notebook instructions and execute the cells step by step.

## Project Structure
```
stock-price-prediction/
├── Project_1.ipynb       # Jupyter Notebook with the project code
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── data/                 # Directory for stock data files
```

## Technologies Used
- **Python**: Core programming language.
- **Scikit-learn**: ML models and evaluation metrics.
- **Pandas and NumPy**: Data manipulation and analysis.
- **Matplotlib and Seaborn**: Data visualization.
- **Yahoo Finance API**: Stock data retrieval.
- **NLTK and TextBlob**: Sentiment analysis.

## Evaluation Metrics
- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values.
- **Mean Absolute Error (MAE)**: Measures the average absolute difference between predicted and actual values.
- **R² Score**: Indicates how well the model explains the variability of the data.

## Results
The ensemble model significantly improves prediction accuracy by combining the strengths of individual models and incorporating sentiment analysis.

## License
This project is licensed under the MIT License.
