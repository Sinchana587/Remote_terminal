# 🔐 Secure Remote Terminal with GUI (SSL Enabled)

This project implements a **secure remote shell/terminal communication system** using **Python sockets and SSL/TLS encryption**. It allows a remote client to securely execute terminal commands on a server machine. The server includes a **Tkinter-based GUI** for easy control, and both communication and command execution are handled with safety in mind.

---

## 📌 Features

- 🔒 **Encrypted Communication**  
  All data exchanged between client and server is encrypted using TLS (via Python's `ssl` module).

- ✅ **Safe Command Execution**  
  Only a predefined set of allowed commands (e.g., `dir`, `echo`, `ipconfig`, etc.) can be executed, ensuring system safety.

- 🖥️ **Graphical Server Interface**  
  The server includes a Tkinter GUI for setting host and port values and visualizing activity.

- 🧑‍💻 **Interactive CLI Client**  
  Lightweight terminal-based client script to securely connect and interact with the server.

- 🔄 **Real-time Command Processing**  
  Commands are processed live and the results are sent back instantly.

- 🧾 **Certificate-based SSL Authentication**  
  The server uses `server.crt` and `server.key` files for TLS handshake.

---

## 🛠️ Technologies Used

```json
[
  "Languages & Libraries: Python 3, socket, ssl, tkinter, subprocess, sys, os",
  "Security: TLS (SSLContext) using X.509 certificates",
  "Frontend: Tkinter (GUI for server)",
  "Execution: subprocess module for controlled command execution",
  "Cross-platform Support: Windows/Linux"
]
