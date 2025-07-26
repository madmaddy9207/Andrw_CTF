```markdown
# Android CTF Challenge: InsecureBankv2ctf - Multi-Stage Pentesting Lab

## Overview

Welcome to the **Android CTF Challenge** based on a modified version of InsecureBankv2!
This CTF is designed to teach and test real-world Android pentesting skills, including static analysis, dynamic analysis, network interception, logic exploitation, and advanced API attacks.

---

## Challenge Story

You are a security researcher investigating a vulnerable Android banking app.
Your mission: **Find all the flags** by analyzing the APK, intercepting network traffic, and exploiting app logic and hidden APIs.

---

## Stages

### **Stage 1: Static Analysis**
- Decompile the APK using tools like JADX-GUI or apktool.
- Find **fake flags** and **hints** hidden in:
  - `xml's`
  - Java classes
  - Smali files
  - Layouts and assets

### **Stage 2: Dynamic Analysis**
- Use Burp Suite to intercept the response.

### **Stage 3: Logic Exploitation**

### **Stage 4: Advanced Flag**

---

## Flags

- **Fake Flags:**
  - `C**{not_the_flag_1}`
  - `C**{not_the_flag_2}`
  - `C**{not_the_flag_3}`
- **Main Flag:**
  - `**********{coupon_code_found}`
- **Hard Flag:**
  - `***{****_***_*****_***}`

---

## Setup Instructions

### **1. Backend Server**

- Install Python 3.8 or 3.9 (recommended).
- Create a virtual environment:
  ```bash
  python3.9 -m venv .venv
  source .venv/bin/activate  # On Windows: .venv\\Scripts\\activate

```

- Install dependencies:
    
    ```bash
    pip install -r requirements.txt
    
    ```
    
    
- Start the server:
    
    ```bash
    python app.py
    
    ```
    

### **2. Android App**

- Install the provided APK on an emulator or test device.
- Set the app’s server IP to your PC’s IP and the correct port (default: 8888).

### **3. Tools Needed**

- [JADX-GUI](https://github.com/skylot/jadx)
- [apktool](https://github.com/iBotPeaches/Apktool)
- [Burp Suite](https://portswigger.net/burp)
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
- [Frida](https://frida.re/) / [Objection](https://github.com/sensepost/objection) (optional, for advanced analysis)

---

## Rules

- No brute-forcing or DoS attacks.
- Use only your own test accounts.
- Have fun and learn!

---

## Credits

- Based on [InsecureBankv2](https://github.com/dineshshetty/Android-InsecureBankv2)
- CTF design and modifications by -abinp

---

## License

This project is for educational and CTF use only.

Do not use for unauthorized testing of real-world apps.

---

```

---
