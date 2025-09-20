
Analyzing how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed), to identify hidden trends or signals that could influence smarter trading strategies.
📁 Project Structure
The project is organized into the following directory structure, adhering to the requested format:
ds_ravina_karmankar/
├── notebook_1.ipynb           # All analysis and code implementation.
├── csv_files/                 # Contains the raw data files.
│   ├── fear_greed.csv
│   └── historical_trader_data.csv
├── outputs/                   # Contains all generated plots and charts.
│   ├── long_short_ratio_boxplot.png
│   ├── pnl_distribution_boxplot.png
│   ├── sentiment_behavior_barplot.png
│   └── time_series_analysis.png
├── ds_report.pdf              # Final summarized insights and explanations.
└── README.md                  # Setup instructions and project overview.
🚀 How to Reproduce the Analysis
Access the Google Colab Notebook: The complete analysis, from data preparation to visualization, is documented in the Google Colab notebook. You can view the notebook.
Clone the Repository: To explore the project files locally, clone this repository to your machine.
bash
git clone https://github.com/Raaavina/ds_ravina_karmankar.git
Use code with caution.

📈 Key Findings & Insights
The analysis yielded the following key insights into the dynamics between market sentiment and trading behavior:
Behavioral Alignment: Average trading metrics largely follow market sentiment. Higher average daily volume and positive average net PnL are characteristic of "Greed" periods, while increased volatility (higher standard deviation of PnL) is more prominent during periods of "Fear."
Hidden Signals in Divergence: While sentiment and behavior often align, analyzing periods of divergence reveals valuable signals. A price rally accompanied by low volume during a period of "Fear," for instance, may indicate a weak, unsustainable move.
Contrarian Opportunities: The long_short_ratio (ratio of long volume to short volume) shows interesting behavior. During periods of "Fear," a rise in this ratio could signal that larger, sophisticated traders are accumulating positions while retail traders panic. This can point to potential market bottoms.
Risk Management: The analysis of PnL standard deviation provides a clear indicator of market volatility. This can inform strategies for adjusting position sizing during different market phases.
Data Limitation: It is important to note that the provided dataset did not include leverage data. This omission means the analysis on specific leverage usage by traders could not be performed.
📝 Strategic Recommendations
Based on the insights from this analysis, the following trading strategies are recommended:
Validate Market Moves: Use volume and sentiment as confirming indicators for price movements.
Exploit Divergence: Actively monitor for divergence, especially in the long/short ratio during extreme sentiment, to identify potential market reversals.
Implement Dynamic Risk Management: Adjust position sizing based on market volatility, scaling back during turbulent periods ("Fear") to protect capital.
📄 Final Report
For a detailed summary of the methodology, findings, and strategic recommendations, please refer to the final report.

[End of README.md]
