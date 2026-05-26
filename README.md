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
  <img src="/img/Banner.png" alt="Contoh output Web_Weak_Analysis" width="800"/>
</p>




## 🔎 Ringkasan
Web_Weak_Analysis adalah toolkit Python untuk pengujian keamanan web: reconnaissance, directory enumeration, subdomain check, pemeriksaan header keamanan, CORS, open-redirect, SQLi/XSS/LFI probes, port scan, SSL info, cookie flags, rate-limit dan CSRF checks. Hasil dapat diekspor ke Markdown / JSON / HTML.

---

## ✨ Fitur Utama
- Recon: IP, DNS, HTTP headers, teknologi, js libs.
- Subdomain enumeration (wordlist kecil).
- Direktori & file sensitif checking.
- Pemeriksaan Security Headers & WAF detection.
- CORS & Open Redirect checks.
- SQL Injection (error/boolean/time), Reflected XSS, LFI checks.
- Port scanning (threaded) & SSL certificate info.
- Cookie flags & simple rate-limit check.
- CSRF detection for POST forms.
- Generate laporan Markdown / JSON / (HTML jika jinja2 tersedia).

---



## 📥 Cara Clone
```bash
git clone https://github.com/SatyaGanzz/Web_Weak_Analysis.git
cd Web_Weak_Analysis
```

## instalasi kali linux
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y python3 python3-pip git
pip3 install -r requirements.txt
```

### Rekomendadi menggukan Virtualenv
```bash
sudo apt update && sudo apt install -y python3-venv git
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Install Termux
```bash
pkg update && pkg upgrade -y
pkg install -y python git
git https://github.com/SatyaGanzz/Web_Weak_Analysis.git
cd Web_Weak_Analysis
pip install --upgrade pip
pip install -r requirements.txt
```
### Cara Menjalankan
```bash
sudo python3 web_weak_analysis.py
```

## 🖼 Demo / Contoh Output

<p align="center">
  <img src="/img/Demo1.png" alt="Contoh output Web_Weak_Analysis" width="800"/><br>
  <em>Demo Script Dijalankan: <code><br>Masukan Url target<pentest_output/</code>.</em>
</p>

<p align="center">
  <img src="/img/Demo_hasil_scanning.png" alt="Contoh output Web_Weak_Analysis" width="800"/><br>
  <em>Demo Proses scanning web
</p>

<p align="center">
  <img src="/img/Demo_hasil_scanning.png" alt="Contoh output Web_Weak_Analysis" width="800"/><br>
  <em>Demo Hasil scanning web 
</p>
&copy SatyaGanz

