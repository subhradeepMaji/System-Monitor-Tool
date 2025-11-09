# 🖥️ System Monitor Tool (Assignment 3 - LSP)

![System Monitor Preview](/images/one.png)

## 📘 Objective
The **System Monitor Tool** is a C++ application that displays real-time information about system processes, memory usage, and CPU load — similar to the `top` command in Linux.  
It uses system calls to gather process and resource data, updates in real time, and allows process management directly from the terminal.

---

## 🧩 Features
- Display of **active processes** with CPU and memory usage.
- **Sorting functionality** by CPU or memory consumption.
- Ability to **kill processes** directly from the interface.
- **Real-time data refresh** every few seconds.
- Simple and clear **terminal-based UI**.

---

## 🗓️ Day-wise Task Breakdown

### **Day 1**
- Design basic UI layout.
- Gather system data using system calls (e.g., `/proc` in Linux).

### **Day 2**
- Display the process list with corresponding **CPU** and **memory usage**.

### **Day 3**
- Implement sorting of processes based on CPU and memory utilization.

### **Day 4**
- Add functionality to **terminate (kill)** processes by process ID.

### **Day 5**
- Implement a **real-time update** feature to refresh data automatically.

---

## ⚙️ Technologies Used
- **Language:** C++
- **Libraries:** `<iostream>`, `<fstream>`, `<sstream>`, `<vector>`, `<string>`, `<unistd.h>`, `<dirent.h>`, `<sys/types.h>`
- **Platform:** Linux (recommended for `/proc`-based process information)

---

## 🧠 Learning Outcomes
- Understanding of **system-level programming** in C++.
- Usage of **system calls** and interaction with the `/proc` filesystem.
- Implementation of **real-time data updates**.
- Enhanced skills in **object-oriented design** and **modular programming**.

---

## 🚀 How to Run
1. Clone or download the repository:
   ```bash
   git clone <your-repo-link>
   cd system-monitor-tool
