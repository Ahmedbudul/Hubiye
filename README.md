# Hubiye
# 🔍 Web Scanner Pro — By Dv.Ahmed

**Web Scanner Pro** waa qalab Ethical Hacking ah oo loogu talagalay in lagu baaro amniga websiteyada, API-yada, subdomains-ka, ports-yada iyo in lagu barto daciifnimada sida XSS & SQL Injection.  
Waxaa lagu dhisay Python, wuxuuna si buuxda uga shaqeeyaa **Termux, Linux & Windows**.

🚨 *Kaliya loogu talagalay ujeedooyin waxbarasho & security testing sharci ah.*

---

## ⚡ Features
- ✅ **URL Scanner**
- ✅ **Subdomain Enumerator**
- ✅ **Port Scanner (Fast Multi-Threading)**
- ✅ **Vulnerability Scanner (XSS / SQLi detection)**
- ✅ **Proxy Support**
- ✅ **TOR Routing Mode**
- 🔥 **Animated Banner (Matrix / Fire / Numbers Rain)**  
- 📶 **WiFi Security Checker** *(Local network only)*
- 🎧 **Keylogger (Local device test only)**
- 📂 **Save Results to File**
- ♻️ **Auto-Updater**
- ⚙️ **High-Speed Async Requests**

---

## 📸 Demo (Banner + Scanning)
*(Ku beddel sawir markaad repo-ga galiso)*
---

🛡️ Legal Disclaimer

Project-kan waa waxbarasho iyo ethical security testing oo keliya.
Adigu ayaad mas’uul ka tahay sida aad u isticmaasho.
Ha baarin website aadan lahayn ama aadan oggolaansho ka haysan.

## 📦 Installation

### Termux
```bash
pkg update -y
pkg install python git -y
pip install requests dnspython colorama pysocks
pip install bs4
pkg install tor -y
pkg install unzip -y
termux-setup-storage
git clone https://github.com/Ahmedbudul/Hubiye.git
