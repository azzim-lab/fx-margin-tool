# FX Margin Call Calculator  

**What It Does:**  
- Fetches live USD/SGD rates using Python.  
- Calculates daily margin requirements for $1M trades.  
- Identifies who owes whom (bank or client).  

**How to Run:**  
1. Open `FX_Margin_Call_Tool.ipynb` in [Google Colab](https://colab.research.google.com/).  
2. Click "Runtime" → "Run all".  

**Next Steps:**  
- Add email alerts (Excel VBA).  
- Expand to 10+ currency pairs.  

![Demo](screenshot.png) *(Upload your screenshot!)*  

eur_rate = data["rates"]["EUR"]
print(f"1 EUR = {eur_rate} USD")  # Add this below your SGD code
