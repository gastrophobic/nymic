````markdown
# Nymic 🔍

A fast Roblox username availability checker with a live grayscale console output.  

Nymic generates usernames in modes like words, digits, random combos, and barcodes, checks availability via the Roblox signup API, logs them in real time with a **dark-gray ↔ white looping gradient**, and saves results to text files.

---

##  Features

- Multiple generation modes (words, digits, barcodes, random combos)
- Animated grayscale console log (dark gray → white → dark gray)
- Results saved per mode (.txt files) and a `failed.txt` for taken names
- Proxy support (optional) with automatic retry logic
- One-click Windows launcher (`run.bat`): auto-installs Python + dependencies

---

##  Quick Start (Windows)

1. Head to the [**Releases** page](https://github.com/gastrophobic/nymic/releases) and download the latest ZIP.
2. Extract it anywhere.
3. Double-click **`run.bat`**:
   - Installs Python 3.11 (if needed, with PATH and pip),
   - Installs required dependencies,
   - Launches Nymic.
4. Select mode(s) (`1,5,7` or `all`) and watch the gradient log do its thing.

---

##  Linux/macOS (Manual Run)

For non-Windows users:

```bash
pip install requests random_word colorama
python nymic.py
````

---

## Proxy Support (Optional)

No proxy required—but for faster scanning and fewer rate limits:

1. Visit [ProxyScrape](https://proxyscrape.com/) and sign up.
2. Get a free trial with 100 proxies.
3. Save them to `proxies.txt` in the script folder.

Supported proxy formats:

```
ip:port
ip:port:user:pass
```

---

## Output Files

* `failed.txt`: taken usernames
* Mode files like `wordname.txt`, `5l.txt`, `4digits.txt`: available usernames

---

## Disclaimer

For educational use only. Respect Roblox’s terms of service.
