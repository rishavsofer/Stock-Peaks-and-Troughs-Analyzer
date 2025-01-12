### Stock Peaks and Troughs Analyzer

#### Overview
The Stock Peaks and Troughs Analyzer is a Python-based application designed to analyze the historical performance of two stock tickers. By identifying key peaks and troughs and analyzing their statistical relationship, the tool provides insights into how these stocks are related over time.

#### Features
- Fetches historical stock data for the last 24 months using `yfinance`.
- Identifies peaks and troughs for each stock based on price movement trends.
- Calculates statistical correlation and p-value between the two stocks.
- Visualizes price trends along with peaks and troughs for better interpretation.

#### Requirements
To run the application, ensure you have Python installed with the following libraries:
- `yfinance`
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`

You can install these dependencies using pip:
```bash
pip install yfinance numpy pandas matplotlib scipy
```

#### How to Use
1. Clone or download this repository.
2. Run the `stock_analysis.py` script.
3. Enter two stock tickers when prompted (e.g., AAPL, MSFT).
4. View the statistical results and a visualization of the stock prices with their peaks and troughs.

#### Example Output
The application will display:
- Correlation coefficient and p-value.
- The number of peaks and troughs for each stock.
- A visualization plot of both stock prices with annotations for peaks and troughs.

#### Sample Input
```bash
Enter the first stock ticker: AAPL
Enter the second stock ticker: MSFT
```

#### Sample Output
```text
Correlation between AAPL and MSFT: 0.85
P-value: 0.0021
Number of Peaks in AAPL: 15 | Number of Peaks in MSFT: 17
Number of Troughs in AAPL: 14 | Number of Troughs in MSFT: 16
```
A detailed plot will also be displayed showing the price trends and key points.

#### Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for enhancements or bug fixes.

#### License
This project is licensed under the MIT License. See the LICENSE file for details.

#### Contact
For questions or feedback, contact:
- Email: rishavlincoln@gmail.com
- GitHub: [Your GitHub Profile](https://github.com/rishavsofer)

