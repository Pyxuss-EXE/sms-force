<p align="center"><img src="Screenshot_2026-02-18-13-45-24-072_com.termux.jpg" width="600"></p>
<h1 align="center">💥 SMS-FORCE v1.1.1 💥</h1>
<p align="center"><b>The Ultimate SMS Brute Force Tool for IVAS Users</b><br><i>Fast • Multi-Threaded • Proxy Support • Made by Pyxuss</i></p>
<p align="center"><img src="https://img.shields.io/badge/Version-1.1.1-red?style=for-the-badge"> <img src="https://img.shields.io/badge/Platform-Termux-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/Purpose-Educational-green?style=for-the-badge"> <img src="https://img.shields.io/badge/Creator-Pyxuss-purple?style=for-the-badge"> <img src="https://img.shields.io/badge/Price-PAID-orange?style=for-the-badge"></p>

---

## 📱 ABOUT SMS-FORCE
**SMS-FORCE v1.1.1** is a powerful SMS exploitation tool designed specifically for IVAS users. This tools is working super fast with thread system. This is for IVAS user only. This is only for education purposes please don't hurt anyone.

## ⚡ KEY FEATURES

## 📋 COMPLETE STEP-BY-STEP GUIDE
### **STEP 1: GET NUMBERS**
- Take range or number from IVAS
- Save that number in any .txt file
- Format: one number per line

### **STEP 2: GET PROXIES (IMPORTANT)**
- You must use proxies matching the target number's country
- Save proxies in proxy.txt (format: ip:port)
- Without proxies = tool won't work properly

### **STEP 3: RUN THE TOOL**
1. Open command/terminal
2. Press option 1 for SMS Brute Force
3. Input your number file (example: numbers.txt)
4. Add proxies manually if you have them
5. Enter the domain where you want to run
6. Set thread count (remember: API can die, so use better threads like 5 or 3)
7. Press Enter to start

## 🔧 INSTALLATION
```bash
pkg update && pkg upgrade -y
pkg install python git -y
git clone https://github.com/PYXUSS-EXE/sms-force
cd sms-force
pip install -r requirements.txt
python run.py
