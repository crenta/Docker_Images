# 🐳 Docker Images

Custom Docker image builders and related tools for cybersecurity labs and education.  
This directory contains scripts and guides for creating disposable, pre-configured environments.

---

## 📂 Available Projects

### 🔹 [miniGDB.py](./GDB_for_exploits/miniGDB.py)

A lightweight Python GUI launcher for creating a **disposable exploit lab** inside a Docker container.  
It automatically builds and launches a self-destructing Ubuntu container pre-installed with essential tools like:

- `gdb` (GNU Debugger)  
- `gcc` / `build-essential`  
- `python2` + `python3` (with pip for both)  
- Common utilities: `git`, `curl`, `wget`, `nano`, `vim`, `net-tools`, `ping`, etc.

👉 For full usage instructions, see the detailed [README here](./GDB_for_exploits/README.md).  

---

## 🛠️ Purpose

The goal of these images and tools is to provide:

- **Isolated environments** for safe experimentation and learning  
- **Pre-configured toolchains** to save setup and configuration time  
- **Disposable containers** that leave no traces after use 

---

## 🛡️ Disclaimer

All tools and images provided here are intended **for educational and research purposes only**.  
Do not use them for malicious activities. Use responsibly and at your own risk.  

---

## 📜 License

All projects in this directory are licensed under the **Apache 2.0 License**.  
See the [LICENSE](./LICENSE) file in this folder for details.
