# 🖱️ Mouse Click Test

## 🔍 Overview
This is a simple web-based **Mouse Click Test** application that helps detect and log mouse interactions. It was primarily created to diagnose **mouse malfunctions**, such as when a single click occasionally registers as a double click.

## ✨ Features
- ✅ Detects **single clicks** and **double clicks**.
- 🖱️ Differentiates between **left, middle, and right button clicks**.
- 🔄 Logs **mouse wheel scrolling**.
- 💡 Uses a **neon-themed terminal-style log window** to display click events.
- ❌ Prevents the default context menu from appearing on right-click.

## 🎯 Purpose
The main reason for creating this application is to check if a mouse is **malfunctioning**, where:
- A **single click** is mistakenly registered as a **double click**. 🧐
- **Unexpected clicks** appear in the log. ⚠️

## 🚀 Usage
1. Open the `index.html` file in a **web browser**. 🌐
2. Click inside the **test area** to generate log entries. 🖱️
3. Observe the **event log** 📜:
   - **Single clicks** appear in **🔵 cyan**.
   - **Double clicks** appear in **🟠 orange**.
4. If a **single click frequently registers as a double click**, it may indicate a **faulty mouse switch**. 🔧

## ⚙️ How It Works
- 🎯 The script listens for `click`, `dblclick`, and `wheel` events.
- 📝 Each event is logged in a **scrollable terminal-style window**.
- 🌈 Colors help differentiate between different interactions.

## 🔬 How to Check for Mouse Issues
- 🖱️ Click slowly and observe if **extra clicks** appear.
- ❗ If **double-click events appear unexpectedly**, your mouse might be defective.
- ❌ If the mouse **fails to register some clicks**, there may be hardware issues.

## 📌 Notes
- 🚫 This tool does **not** require installation—just open it in a browser.
- 🏆 Works best in **modern browsers** like Chrome, Firefox, and Edge.

## 📜 License
This project is **open-source** and free to use. 🎉
