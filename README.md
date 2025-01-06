# DatascienceReseachProject
# Stock Market Analysis Using Yahoo Finance Data

## Features

### Dataset

- **Source**: Stock data from Yahoo Finance for Apple Inc. (AAPL).
- **Columns**: Open, High, Low, Close, Adj Close, Volume.

### Libraries Used

- **Data Processing**: NumPy, Pandas
- **Data Source**: yfinance
- **Modeling**: TensorFlow, Keras
- **Visualization**: Matplotlib
- **Evaluation**: Scikit-learn

### Analysis and Modeling

1. **Data Loading**
   - Downloaded historical stock prices for AAPL from Yahoo Finance.
   - Preprocessed the data, including handling missing values and scaling features.

2. **Exploratory Data Analysis**
   - Visualized historical trends in stock prices.
   - Analyzed key metrics such as daily closing prices and trading volume.

3. **Modeling**
   - Built a Sequential model with LSTM layers to predict future stock prices.
   - Used Dropout layers to prevent overfitting.

4. **Evaluation**
   - Metrics: Mean Squared Error (MSE), Mean Absolute Error (MAE), R-squared (R²).
   - Visualized predictions versus actual prices.

## Requirements

- Python 3.7+
- TensorFlow
- Pandas
- yfinance
- Scikit-learn
- Matplotlib

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Z-Kainat/DatascienceReseachProject
   ```


2. Run the notebook:

   ```bash
   jupyter notebook CodeFile.ipynb
   ```

3. Customize the `ticker` variable in the notebook to analyze a different stock.

## Results and Visualizations

- Time series plots of stock prices.
- Predictions versus actual stock prices.
- Evaluation metrics displayed for model performance.

## Conclusion

This notebook provides a framework for analyzing stock price trends and building predictive models using LSTM networks. It demonstrates the use of historical stock data to forecast future trends effectively.

## Future Work

- Extend analysis to multiple stocks.
- Implement additional deep learning models for comparison.
- Optimize hyperparameters for improved predictions.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

For questions or feedback, please reach out to Kainatali283@gmail.com

