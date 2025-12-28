# Nymic 🔍

A fast Roblox username availability checker with a live grayscale log display.

Nymic generates usernames in different styles (words, digits, random sequences, etc.) and checks them against the Roblox signup API. Results are written to text files for each mode, and displayed in real-time with a smooth **dark gray → white → dark gray looping gradient** in the console.

---

## ✨ Features

* Multiple username generation modes (words, digits, random combos, barcodes, etc.)
* Live animated console output with grayscale gradient logging
* Saves **available usernames** into mode-specific `.txt` files
* Saves **taken usernames** into `failed.txt`
* Works with or without proxies
* Built-in **installer/launcher (`run.bat`)** → auto-installs Python + all requirements if missing

---

## 🚀 Quick Start (Windows)

1. Go to the [**Releases**](../../releases) page and download the latest `.zip`.
2. Extract the zip anywhere on your PC.
3. Double-click **`run.bat`**.

   * If Python isn’t installed → it will auto-download & install Python 3.11 (with PATH + pip).
   * Installs all required dependencies automatically.
   * Then launches **Nymic**.
4. **Pick modes from the menu** (`1,5,7` or `all`).
5. Watch results stream in with a live gradient log.

---

## 🐧 Linux/macOS (Manual Run)

For non-Windows users, you’ll need Python 3.9+ and pip:

```bash
pip install requests random_word colorama
python nymic.py
```

---

## 🌐 Proxy Support (Optional)

* Nymic works **without proxies** by default.
* For better speed & fewer rate limits:

  1. Go to [ProxyScrape](https://proxyscrape.com/)
  2. Sign up for a free account
  3. You’ll get **100 free proxies** in your trial
  4. Save them into a file named `proxies.txt` in the same folder as the script

Formats supported:

```
ip:port
ip:port:user:pass
```

---

## 📂 Output Files

* `failed.txt` → taken usernames
* `wordname.txt`, `5l.txt`, `4digits.txt`, etc. → available usernames

---

## ⚠️ Disclaimer

This project is for **educational purposes only**.
Use responsibly and respect Roblox’s terms of service.

