📈 Stock Portfolio Tracker

A simple Python-based Stock Portfolio Tracker that calculates the total investment value based on manually defined stock prices.

This project is designed for beginners to practice Python dictionaries, user input, loops, basic arithmetic, and file handling.

🚀 Features

- 📊 Predefined stock prices using a Python dictionary
- 📝 Enter stock names and quantities
- 💰 Calculate investment value for each stock
- 📈 Calculate total portfolio investment
- 🔄 Add multiple stocks
- ⚠️ Handles invalid stock names
- ⚠️ Handles invalid quantities
- 💾 Option to save the portfolio to a ".txt" file

🛠️ Technologies Used

- Python 3
- Dictionary
- Loops
- Conditional Statements
- User Input
- Basic Arithmetic
- File Handling
- Exception Handling

📋 Available Stocks

The program currently uses these manually defined prices:

Stock| Price
AAPL| $180
TSLA| $250
GOOGL| $150
MSFT| $420
AMZN| $190

«Note: These are hardcoded example prices and are not real-time market prices.»

▶️ How to Run

1. Clone the repository

git clone https://github.com/akshat0070/stock-portfolio-tracker.git

2. Open the project folder

cd stock-portfolio-tracker

3. Run the Python program

python3 stock_portfolio.py

On Windows, you can also use:

python stock_portfolio.py

💻 Example

===== STOCK PORTFOLIO TRACKER =====
Available Stocks: AAPL, TSLA, GOOGL, MSFT, AMZN

Enter stock name (or 'done' to finish): AAPL
Enter quantity: 5
5 shares of AAPL added.

Enter stock name (or 'done' to finish): TSLA
Enter quantity: 2
2 shares of TSLA added.

Enter stock name (or 'done' to finish): done

===== YOUR PORTFOLIO =====
AAPL: 5 shares × $180 = $900
TSLA: 2 shares × $250 = $500
--------------------------------
Total Investment: $1400

Do you want to save the portfolio? (yes/no): yes
Portfolio saved successfully in portfolio.txt

📁 Project Structure

stock-portfolio-tracker/
│
├── stock_portfolio.py
├── portfolio.txt
└── README.md

"portfolio.txt" is created by the program when the user chooses to save the portfolio.

🧮 How It Works

The program stores stock prices in a dictionary:

stock_prices = {
    "AAPL": 180,
    "TSLA": 250,
    "GOOGL": 150,
    "MSFT": 420,
    "AMZN": 190
}

The investment for each stock is calculated using:

Investment = Stock Price × Quantity

The program then adds the individual investments to calculate the total portfolio value.

🎯 Learning Goals

This project helped practice:

- Python dictionaries
- "input()"
- "if/else"
- "while" loops
- "for" loops
- Type conversion
- Exception handling
- File handling with "open()"
- Basic calculations

🔮 Future Improvements

Possible improvements for future versions:

- 🌐 Add real-time stock prices using an API
- 📊 Add portfolio performance tracking
- 💵 Support different currencies
- 📁 Save data using CSV
- 📈 Add profit/loss calculation
- 🖥️ Create a graphical user interface

👨‍💻 Author

Akshat Saini

BCA Student | Python Learner

---

⭐ If you found this project useful, consider giving the repository a star!
