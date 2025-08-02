# Ping Monitor - C# Windows Forms Application

A simple Windows Forms application that continuously measures TCP "ping" latency to a list of target hosts and displays the results in a sleek dark-themed GUI.

## Features

- Measures TCP connection latency to predefined hosts on port 53 (DNS).
- Automatically updates every second.
- Visual feedback with color-coded latency:
  - **Green** for fast responses (<50 ms)
  - **Yellow** for moderate latency (<100 ms)
  - **Red** for slow responses (≥100 ms)
  - **Purple** for timeouts
- Lightweight and does not require admin privileges (no ICMP).
- Simple and clean user interface.

<img width="319" height="273" alt="image" src="https://github.com/user-attachments/assets/d09b9ac4-9887-4b15-b7c2-8a2a88c87cd1" />
