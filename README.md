# Keylogger

This project consists of a **basic keylogger**, developed using Python.

## 🚀 Features

### **Keylogger**
- Logs all keystrokes in the background.
- Stores logs in a local file.
- Can be extended to send logs via email (for ethical use only).

## 📂 Project Structure
```
key_logger/
│── keylogger.py      # Basic keylogger script
│── logs.txt          # Stores captured keystrokes

```

## 🔧 Installation & Usage (Kali Linux)

### **1. Install Dependencies**
Ensure you have Python installed. Then install required libraries:
```sh
sudo apt update && sudo apt install python3 python3-pip -y
pip3 install -r requirements.txt
```

### **2. Run the Keylogger (For Testing)**
```sh
python3 key_logger.py
```
🔹 This will start logging keystrokes in `logs.txt`.

## ⚠️ Disclaimer
This project is for **educational and ethical use only**. Unauthorized usage for malicious purposes is strictly prohibited.
