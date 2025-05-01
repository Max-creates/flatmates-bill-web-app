# 🏠 Flatmates Bill Web App

A simple Flask web application to split utility bills among flatmates based on the number of days each person stayed in the house during the billing period.

## 🚀 Features

- Input total bill amount and billing period  
- Enter flatmates' names and the number of days each stayed  
- Calculate and display each person's share of the bill  

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Max-creates/flatmates-bill-web-app.git
   cd flatmates-bill-web-app
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Usage

1. **Run the application:**
   ```bash
   python main.py
   ```

2. **Open your web browser and navigate to:**
   ```
   http://127.0.0.1:5000/
   ```

3. Set environment variable `FLASK_APP=main.py` if needed.
