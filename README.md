# 💱 Currency Converter (Tkinter GUI)

A straightforward desktop application for converting currencies using up-to-date (or user-defined) exchange rates, built with Python's Tkinter GUI toolkit. Instantly convert between common currencies in a modern, clickable window.

---

## ✨ Features

- **User-friendly GUI:** Clean Tkinter interface for fast, no-hassle conversions
- **Supports many currencies by editing the JSON file** (defaults to USD, EUR, GBP, INR, JPY)
- **Custom exchange rates:** Easily update `exchange_rates.json` to whatever rates you want
- **Instant results:** Live conversion with error handling
- **No external dependencies required** (Tkinter and json are standard)

---

## 🚀 How to Run

1. **Python 3 required (Tkinter included)**
2. **Make sure both `currency.py` and `exchange_rates.json` are in the same folder**
3. **Run:**
    ```
    python currency.py
    ```
    or double-click the script
4. **Choose amount, from currency, and to currency, then click Convert**

---

## 🗂️ Data Format (`exchange_rates.json`)

The JSON file should look like:
{
"USD": 1.0,
"EUR": 0.85,
"GBP": 0.75,
"INR": 74.0,
"JPY": 110.0
}
_Add/edit more currencies as needed (the numbers are relative to 1 USD)._

---

## 🧑‍💻 Usage

- Enter amount to convert
- Select source (**From Currency**) and target (**To Currency**)
- Press **Convert** and view the converted value instantly

---

## 🛠️ How It Works

- Loads exchange rates from the local JSON file
- Converts from any currency to USD (base), then to target currency
- Simple error messages for missing currencies or invalid input

---

## 📄 License

MIT License — free for learning, teaching, and tinkering.

---

A great project for students or anyone needing an offline currency calculator.  
Expand as needed: add more currencies, more advanced math, or even fetch rates automatically!
