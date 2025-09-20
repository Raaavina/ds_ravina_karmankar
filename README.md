
# Analysis of Crypto Market Sentiment and Trading Behavior

This repository contains the analysis of the relationship between Bitcoin market sentiment (Fear vs. Greed) and trading behavior using historical data from the Hyperliquid exchange. The project aims to uncover correlations and potential hidden signals that can inform smarter trading strategies.

## 📁 Project Structure

The project is organized into the following directory structure:

# Analysis of Crypto Market Sentiment and Trading Behavior

This repository contains the analysis of the relationship between Bitcoin market sentiment (Fear vs. Greed) and trading behavior using historical data from the Hyperliquid exchange. The project aims to uncover correlations and potential hidden signals that can inform smarter trading strategies.

## 📁 Project Structure

The project is organized into the following directory structure, adhering to the requested format:

ds_ravina_karmankar/
├── notebook_1.ipynb # All analysis.
├── csv_files/ # Contains the raw data files.
│ ├── fear_greed.csv
│ └── historical_trader_data.csv
├── outputs/ # Contains all generated plots and charts.
│ ├── long_short_ratio_boxplot.png
│ ├── pnl_distribution_boxplot.png
│ ├── sentiment_behavior_barplot.png
│ └── time_series_analysis.png
├── ds_report.pdf # Final report
└── README.md # Setup instructions and project overview.

## 🚀 How to Reproduce the Analysis

1.  The complete analysis, from data preparation to visualization, is documented in the Google Colab notebook. You can view the notebook.

2.  **Clone the Repository:** To explore the project files locally, clone this repository to your machine.
    ```bash
    git clone https://github.com/Raaavina/ds_ravina_karmankar.git
    ```

## 📈 Key Findings & Insights

The analysis yielded the following key insights into the dynamics between market sentiment and trading behavior:

*   **Behavioral Alignment:** Average trading metrics largely follow market sentiment. Higher average daily volume and positive average net PnL are characteristic of "Greed" periods, while increased volatility (higher standard deviation of PnL) is more prominent during periods of "Fear."
*   **Hidden Signals in Divergence:** While sentiment and behavior often align, analyzing periods of divergence reveals valuable signals. A price rally accompanied by low volume during a period of "Fear," for instance, may indicate a weak, unsustainable move.
*   **Contrarian Opportunities:** The `long_short_ratio` (ratio of long volume to short volume) shows interesting behavior. During periods of "Fear," a rise in this ratio could signal that larger, sophisticated traders are accumulating positions while retail traders panic.
*   **Risk Management:** The analysis of PnL standard deviation provides a clear indicator of market volatility. This can inform strategies for adjusting position sizing during different market phases.
*   **Data Limitations:** It is important to note that the provided dataset did not include leverage data. This omission means the analysis on specific leverage usage by traders could not be performed.

## 📄 Final Report

For a detailed summary of the methodology, findings, and strategic recommendations, please refer to the final report.
