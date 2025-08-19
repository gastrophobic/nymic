````markdown
# Nymic 🔍

A fast **Roblox username availability checker** with live grayscale console output.  

Nymic generates usernames in different modes (words, digits, random combos, barcodes), checks them against the Roblox signup API, and logs results in real time with a smooth **dark gray → white → dark gray looping gradient**. Results are saved into text files automatically.

---

## ✨ Features
- Multiple generation modes (words, digits, barcodes, random combos)  
- Animated grayscale console output (dark gray → white → dark gray)  
- Saves **available usernames** into mode-specific `.txt` files  
- Saves **taken usernames** into `failed.txt`  
- Works with or without proxies  
- One-click Windows launcher (`run.bat`) — auto-installs Python + all requirements  

---

## 🚀 Quick Start (Windows)

1. Download the latest release from the [**Releases page**](https://github.com/gastrophobic/nymic/releases).  
2. Extract the ZIP anywhere.  
3. Double-click **`run.bat`**  
   - Installs Python 3.11 if missing (with PATH + pip)  
   - Installs all dependencies  
   - Launches **Nymic**  
4. Pick modes (`1,5,7` or `all`).  
5. Watch results stream in with the live gradient log.  

---

## 🐧 Linux/macOS (Manual Run)

For non-Windows users, you’ll need Python 3.9+ and pip:

```bash
pip install requests random_word colorama
python nymic.py
````

---

## 🌐 Proxy Support (Optional)

Nymic works **without proxies** by default.
For faster scans and fewer rate limits:

1. Go to [ProxyScrape](https://proxyscrape.com/)
2. Sign up for a free account
3. Get 100 free proxies in the trial
4. Save them into a file named `proxies.txt` in the same folder as the script

Supported formats:

```
ip:port
ip:port:user:pass
```

---

## 📂 Output Files

* `failed.txt` → taken usernames
* `wordname.txt`, `5l.txt`, `4digits.txt`, etc. → available usernames (per mode)

---

## ⚠️ Disclaimer

This project is for **educational purposes only**.
Use responsibly and respect Roblox’s Terms of Service.
