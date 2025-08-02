# 🛰️ Windows Ping Monitor (Python GUI)

This is a simple and elegant Python-based Windows application that continuously pings a list of IP addresses and shows their response times in a GUI. Built with `tkinter`, it’s perfect for basic network monitoring and troubleshooting.

## ✅ Features

- Clean and minimal user interface
- Pings multiple IP addresses every 5 seconds
- Colored feedback based on latency:
  - 🟢 Green = Good (< 50ms)
  - 🟡 Yellow = OK (50–100ms)
  - 🔴 Red = Slow (> 100ms)
- Gracefully handles timeouts
- Built as a Windows `.exe` with **no flashing windows**

---

## 🖥️ Sample Output

8.8.8.8 : 23 ms ✅
4.2.2.4 : timeout ❌

<img width="319" height="273" alt="image" src="https://github.com/user-attachments/assets/d09b9ac4-9887-4b15-b7c2-8a2a88c87cd1" />
