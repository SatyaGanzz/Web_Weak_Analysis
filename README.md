<p align="center">
  <img src="https://img.shields.io/badge/Satya%20Ganzz-Automated-red?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/USERNAME/REPO?style=for-the-badge"/>
</p>

<h1 align="center">🕵‍♂ Web_Weak_Analysis</h1>
<p align="center">
  All-in-one web penetration testing toolkit (Recon → Scan → Reporting).<br/>
  <em>Educational & Ethical Hacking Only — gunakan hanya pada target yang Anda miliki izin eksplisit.</em>
</p>

---
<p align="center">
  <img src="/img/Banner.png" alt="Example output Web_Weak_Analysis" width="800"/>
</p>




## 🔎 Summary
Web_Weak_Analysis is a Python-based web security testing toolkit for reconnaissance, directory enumeration, subdomain checks, security header analysis, CORS testing, open redirect detection, SQLi/XSS/LFI probes, port scanning, SSL inspection, cookie flag analysis, rate-limit testing, and CSRF checks. Results can be exported to Markdown / JSON / HTML.

---

## ✨ First Feature
- Recon: IP, DNS, HTTP headers, technologies, JS libraries.
- Subdomain enumeration (small wordlist).
- Sensitive directories & files checking.
- Security Headers & WAF detection.
- CORS & Open Redirect checks.
- SQL Injection (error/boolean/time), Reflected XSS, and LFI checks.
- Threaded port scanning & SSL certificate information.
- Cookie flags & simple rate-limit checks.
- CSRF detection for POST forms.
- Generate reports in Markdown / JSON / (HTML if jinja2 is installed).
---



## 📥 How to Clone
```bash
git clone https://github.com/SatyaGanzz/Web_Weak_Analysis.git
cd Web_Weak_Analysis
```

## Instalation on Linux
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y python3 python3-pip git
pip3 install -r requirements.txt
```

### Recomended using Virtualenv
```bash
sudo apt update && sudo apt install -y python3-venv git
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Install on Termux
```bash
pkg update && pkg upgrade -y
pkg install -y python git
git https://github.com/SatyaGanzz/Web_Weak_Analysis.git
cd Web_Weak_Analysis
pip install --upgrade pip
pip install -r requirements.txt
```
### How to run
```bash
sudo python3 web_weak_analysis.py
```

## 🖼 Demo / Example Output

<p align="center">
  <img src="/img/Demo1.png" alt="Contoh output Web_Weak_Analysis" width="800"/><br>
  <em>Demo Script Running: <code><br>Input Url target<pentest_output/</code>.</em>
</p>

<p align="center">
  <img src="/img/Demo_Proses_scaning.png" alt="Contoh output Web_Weak_Analysis" width="800"/><br>
  <em>Demo Proces scanning web
</p>

<p align="center">
  <img src="/img/Demo_hasil_scanning2.png" alt="Contoh output Web_Weak_Analysis" width="800"/><br>
  <em>Demo Result scanning web 
</p>
&copy SatyaGanz

