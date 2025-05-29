# 🚀 Automating Cryptocurrency API Extraction

This project automates the process of fetching live cryptocurrency market data using the CoinMarketCap Pro API. It’s built with Python and is ideal for learning how to work with APIs, automate data extraction, and structure data with pandas.

---

## 📁 Repository Structure

```
crypto-api-automation/
├── Automating_API_Extraction.ipynb            # Original notebook
├── Automating_API_Extraction_Documented.ipynb # Fully documented version
├── README.md                                   # GitHub project description
└── data/                                       # (Optional) Folder to store output CSV files
```

---

## 🧰 Libraries and Tools Used

- `requests` – to interact with the API
- `pandas` – to store and process data
- `time`, `os` – for loop delays and optional environment variables

Install all requirements with:
```bash
pip install requests pandas
```

---

## 🔑 API Key Required

Sign up at [CoinMarketCap API](https://coinmarketcap.com/api/) and get your API key.  
Update the `headers` dictionary in the notebook to include:
```python
'X-CMC_PRO_API_KEY': 'your_api_key_here'
```

---

## 🧠 Project Features

- Fetches data on the top cryptocurrencies in real-time
- Handles connection errors and retries gracefully
- Stores data in a global DataFrame `df`
- Optional: Save to CSV for later use

---

## 🚀 How to Use

1. Clone this repository:
```bash
git clone https://github.com/yourusername/crypto-api-automation.git
cd crypto-api-automation
```

2. Add your API key in the notebook.

3. Run `Automating_API_Extraction_Documented.ipynb` with Jupyter Notebook or VS Code.

---

## 📌 Future Enhancements

- Add timestamped storage for tracking changes
- Visualize price trends over time
- Alert system for large price changes

---

## ✍️ Author

**Ujjwal Karki**  
_Data + Crypto = 🔥_  
Feel free to fork and customize!
