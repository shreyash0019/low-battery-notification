# 📘 Low Battery Notification

This repository contains a Python script that displays a desktop notification when your battery level drops below 30% and your device is not plugged in.

---

## 📂 File

- `main.py` – The main script that checks battery percentage and sends a notification if needed.

---

## 🛠️ Requirements

Ensure you have Python 3.x installed.

Install the required packages using pip:

```bash
pip install psutil
pip install py-notifier
pip install win10toast
```

---

## ▶️ Usage

Run the script using:

```bash
python main.py
```

If your battery is at or below 30% and the laptop is not plugged in, you’ll receive a desktop notification.

---

## 🔧 How It Works

- Uses `psutil` to check battery status.
- If battery is low and not charging, sends a notification using `py-notifier` and `win10toast`.

---

## 📋 Example Output

A Windows toast notification with:

- **Title:** "Battery Low"
- **Description:** "30% Battery remain!!" (or current %)
- **Duration:** 5 seconds

---

## 🤝 Contributions

Feel free to fork the repo and submit a pull request if you want to add features like:
- Periodic checks
- Custom battery thresholds
- Sound alerts

---

