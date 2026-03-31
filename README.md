# GazaliEdge
GazaliEdge is a personalized finance and stock analysis tool designed for comprehensive market insights. With modern technical indicators, financial fundamentals, and custom charting, it provides detailed guidance for informed investment decisions.

GazaliEdge User Manual

Welcome to GazaliEdge! This is a personalized finance and stock analysis tool created to assist users in analyzing stock trends, obtaining financial insights, and making informed decisions. Below is a comprehensive guide to help you navigate through the features of this program.

Overview

GazaliEdge is a stock analysis program that combines technical indicators and fundamental financial analysis, allowing users to create and log into accounts, view stock prices, check technical indicato¬rs, and receive trading advice. The program operates with a GUI (Graphical User Interface) and includes input fields, buttons, and output areas for a seamless experience.

	Note: While GazaliEdge has a user-friendly GUI, certain actions, such as account creation and login, currently require input directly from the shell or terminal. This is a known limitation, and future updates will integrate these functions into the GUI.

Getting Started

1.Run the Program: Start the GazaliEdge program in Python. Ensure you have all dependencies installed, including yfinance, mplfinance, and PyQt5.

	2.Main Interface: You will see various input fields and buttons:

•Ticker Symbol Input: Enter the stock ticker symbol (e.g., AAPL, TSLA) for the stock you want to analyze.

•Feature Buttons: Each button corresponds to a different feature, such as viewing stock fundamentals, technical indicators, or plotting stock charts.

Feature Descriptions

1. Account Management

	•Create Account:

•How It Works: Click on “Create Account.” You’ll be prompted to enter your name, password, mobile number, available cash, and stock holdings in the terminal. Enter the details as instructed in the terminal window.
	
•Purpose: Creates a user profile that stores your cash balance and any stock holdings. This is useful for tracking stock investments and checking gains/losses.
	•Login:

•How It Works: Click “Login to Account.” In the terminal, enter your name and password to access your account.

•Purpose: After logging in, GazaliEdge will display your mobile number, cash balance, and any stocks you own, along with profit/loss details.

•Limitations: Both “Create Account” and “Login” currently operate in the terminal, which may feel disconnected from the GUI experience.

2. Stock Analysis Features

	•Load Stock Data:

•How It Works: Enter a ticker symbol and click “Load Stock Data.” This will fetch recent historical prices and display them in the GUI output.

	•Purpose: Allows users to see recent stock performance data and trends.

	•Current Price:

•How It Works: Enter the ticker symbol and click “Current Price.” The program retrieves the latest price of the stock and displays it in the GUI.

	•Purpose: Quickly view the current stock price without additional analysis.

	•Stock Fundamentals:

•How It Works: Click “Stock Fundamentals.” The program fetches basic financial metrics such as market cap, volume, EPS, P/E ratio, and dividend yield.

•Purpose: Provides fundamental data to assess the stock’s valuation and financial health.
	•Technical Indicators:

•How It Works: Click “Technical Indicators.” GazaliEdge will calculate common indicators (e.g., EMA, RSI, MACD) and display them.

•Purpose: Technical indicators help in understanding stock momentum, trends, and possible reversal points. Ideal for short-term traders.

	•Trading Advice:

•How It Works: Click “Trading Advice.” The program analyzes multiple indicators and provides a recommendation based on the data, such as “bullish,” “bearish,” or “hold.”

•Purpose: Offers a quick, informed suggestion on whether the stock might be a good buy or if caution is advised.

	•Company Info:

•How It Works: Enter a ticker symbol and click “Company Info.” GazaliEdge will fetch a summary of the company’s business, sector, industry, and key stats.

•Purpose: Provides a fundamental overview of the company for a more in-depth analysis.

3. Visual Tools

	•Plot Stock Chart:

•How It Works: Enter the ticker symbol and select the time frame. Click “Plot Stock Chart” to view the stock’s price over time, with options to display moving averages, RSI, and volume.

	•Purpose: Visualize stock trends and patterns over a chosen period.

Known Bugs and Limitations

1.Terminal Dependency for Account Actions: Account creation and login require input in the terminal instead of the GUI. This may be inconvenient for users expecting a fully integrated GUI experience.

2.Occasional API Issues: Yahoo Finance data may occasionally fail to load if the API experiences downtime or if the ticker symbol is invalid.

3.Basic Error Handling: Error messages may appear in the terminal instead of the GUI, which could be confusing. For instance, if an invalid ticker symbol is entered, the error is printed in the terminal rather than displayed in the GUI.

4.Limited Data Range: The program loads data starting from 2000, which might not work for newer stocks without extensive historical data.

Tips for Using GazaliEdge

•Ensure Ticker Symbol Accuracy: Verify the ticker symbol you enter to avoid errors. For example, “AAPL” for Apple, “GOOGL” for Google.

•Run in a Stable Environment: For best results, run the program on a stable internet connection to prevent API fetch issues.

•Explore Each Feature: Each feature in GazaliEdge complements the other. For instance, view the technical indicators to support trading advice or check the fundamentals before making any investment decisions.

•Future Updates: Expect enhancements in integrating the account management system into the GUI and adding more advanced error handling.

Conclusion

GazaliEdge is a versatile and informative tool for anyone looking to dive into stock analysis with an interactive experience. While it currently has some limitations, the program offers powerful insights through technical and fundamental data, alongside practical recommendations. With further enhancements, GazaliEdge will evolve into a seamless, all-in-one stock analysis tool.

Enjoy exploring GazaliEdge and making data-driven financial decisions!
