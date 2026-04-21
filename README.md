# 💰 Personal Finance Manager (CLI-Based Multi-User System)

A **Python-based command-line application** that helps users manage their personal finances by tracking income, expenses, and generating useful financial insights.

---

## 📌 Overview

The **Personal Finance Manager** is a multi-user system that allows individuals to:
- Securely create accounts and log in  
- Track income and expenses  
- Visualize spending patterns  
- Receive smart financial suggestions  

This project demonstrates real-world implementation of Python concepts like file handling, modular programming, and data visualization.

---

## 🎯 Objective

- Track and manage personal finances efficiently  
- Provide insights into spending habits  
- Enable better financial decision-making  
- Support multiple users with secure data handling  

---

## 🚀 Features

- 🔐 Multi-user login and signup system  
- 👤 Unique username validation  
- 📁 User-specific CSV data storage  
- 💰 Income tracking  
- 🧾 Expense tracking (Food, Travel, Bills, Others)  
- 📊 Expense visualization (Pie Chart using Matplotlib)  
- 📉 Automatic balance calculation  
- 📜 Transaction history  
- 💡 Financial recommendations:
  - Overspending alert  
  - High spending warning  
  - Good financial condition  
- 🗑️ Delete single or all transactions  
- ⚠️ Input validation and error handling  
- 🧩 Modular code design  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - csv  
  - os  
  - matplotlib  

---

## 📂 Project Structure
Finance-Manager/
│── main.py
│── users.csv
│── <username>_data.csv
│── README.md

---

## ⚙️ Working Algorithm

1. Start program  
2. Signup / Login  
3. Load user data  
4. Perform operations:
   - Add income  
   - Add expense  
   - Show balance  
   - View transactions  
   - Visualize expenses  
   - Get recommendations  
5. Save data  
6. Exit  

---

## ▶️ How to Run

### 1. Clone Repository
```bash
git clone https://github.com/your-username/finance-manager.git
cd finance-manager

## Install Required Library
pip install matplotlib

## Run the Program
python main.py

📊 Sample Output
CLI-based dashboard for user interaction
Transaction logs displayed in terminal
Pie chart visualization of expenses
Real-time balance calculation

✅ Result

The project was successfully implemented and tested. It:

Supports multiple users independently
Accurately tracks income and expenses
Provides visual insights and recommendations
Is efficient and user-friendly

🧠 Learning Outcomes
File handling using CSV
Python modular programming
CLI-based application development
Data visualization using Matplotlib
User authentication logic

🔮 Future Enhancements
GUI version (Tkinter / PyQt)
Database integration (SQLite/MySQL)
Cloud storage support
Mobile/Web application version
Advanced analytics and budgeting tools
