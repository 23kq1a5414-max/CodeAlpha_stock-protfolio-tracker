# 📈 Stock Portfolio Calculator

A simple Python program to calculate the total investment value of a stock portfolio.  
This project demonstrates how to use dictionaries, loops, and file handling in Python.

---

## 📌 Overview
The program allows users to:
- Enter the number of stocks they own
- Input stock names and quantities
- Calculate the value of each stock based on predefined prices
- Display the total investment
- Save the result to a file (`portfolio.txt`)

---

## ✨ Features
- Predefined stock prices for:
  - `AAPL` (Apple)
  - `TSLA` (Tesla)
  - `GOOG` (Google)
  - `MSFT` (Microsoft)
- Case-insensitive stock name input
- Handles unavailable stocks gracefully
- Saves total investment value to a text file

---

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Standard Python libraries (no external dependencies)

---

## 🚀 Getting Started

### Prerequisites
- Install [Python 3.x](https://www.python.org/downloads/)

### Run the program
```bash
python portfolio.py
📖 Example Run
Code
Enter number of stocks: 2
Enter stock name: GOOG
Enter quantity: 1
Value: 150
Enter stock name: ABC
Enter quantity: 5
Stock not available
Total Investment: 150
The result will also be saved in portfolio.txt:

Code
Total Investment Value: 150
📂 Project Structure
Code
├── portfolio.py   # Main script
└── README.md      # Project documentation
