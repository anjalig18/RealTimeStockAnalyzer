
# RealTimeStockAnalyzer

RealTimeStockAnalyzer is a real-time stock price prediction and investment suggestion system developed using machine learning techniques. It fetches streaming price data, computes technical indicators, trains predictive models, and generates profitable buy/sell signals.

## Features

- Fetches real-time stock price data from the Yahoo Finance API
- Preprocesses the raw data by handling missing entries, removing noise, and adding descriptive features
- Computes various technical indicators like Moving Averages, Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD), and Bollinger Bands
- Trains machine learning models (e.g., Random Forest, Recurrent Neural Networks, LSTM) on historical data to predict short-term price movements
- Generates buy/sell investment suggestions based on the predicted price changes
- Visualizes real-time trading signals overlaid on live market data through a dashboard
- Continuously evaluates model performance against live market movements and retrains the models to maintain accuracy

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/RealTimeStockAnalyzer.git
```

2. Navigate to the project directory:

```bash
cd RealTimeStockAnalyzer
```

3. Create a new virtual environment (optional but recommended):

```bash
python -m venv env
```

4. Activate the virtual environment:

   - On Windows:
   ```bash
   env\Scripts\activate
   ```

   - On Unix or macOS:
   ```bash
   source env/bin/activate
   ```

5. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Start the Jupyter Notebook server:

```bash
jupyter notebook
```

2. Open the `RealTimeStockAnalyzer.ipynb` notebook file in your browser.

3. Follow the instructions in the notebook to fetch real-time stock data, preprocess it, train machine learning models, make predictions, and generate investment suggestions.

4. The notebook includes visualizations and explanations for each step of the process.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Yahoo Finance API for providing real-time stock data
- [scikit-learn](https://scikit-learn.org/) for machine learning algorithms
- [Pandas](https://pandas.pydata.org/) for data manipulation
- [Matplotlib](https://matplotlib.org/) and [Plotly](https://plotly.com/) for data visualization

