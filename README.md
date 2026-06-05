<div align="center">ScanXSS

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=850&lines=Cross+Site+Scripting+Scanner;Fast+Parameter+Discovery;Python+%7C+Termux+%7C+Linux;Developed+by+AnsXploit" /><br><p align="center">
<img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Platform-Termux-000000?style=for-the-badge">
<img src="https://img.shields.io/badge/Linux-Supported-success?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p></div>---

Overview

ScanXSS adalah tool berbasis Python yang dirancang untuk membantu proses identifikasi parameter input yang berpotensi digunakan dalam pengujian keamanan aplikasi web.

Tool ini dibuat dengan fokus pada:

- Kecepatan
- Kemudahan penggunaan
- Kompatibilitas Termux
- Tampilan terminal yang bersih
- Workflow sederhana

---

Screenshot

<p align="center">
<img src="./preview.jpg" width="100%">
</p>---

Features

✔ Fast Parameter Discovery

✔ Lightweight Scanner

✔ Clean Terminal Interface

✔ Python Based

✔ Termux Compatible

✔ Easy To Use

✔ Single Target Testing

✔ Colorized Output

---

Installation

pkg update -y

pkg install git python -y

git clone https://github.com/AnsThub/scanxss

cd scanxss

python scanxss.py

---

Usage

Run:

python scanxss.py

Target Example:

https://example.com/search?q=test

---

Parameter Reference

<details><summary><strong>Click To Expand</strong></summary>inurl:?q=
inurl:?s=
inurl:?search=
inurl:?query=
inurl:?keyword=
inurl:?id=
inurl:?page=
inurl:?cat=
inurl:?user=
inurl:?name=
inurl:?msg=
inurl:?comment=

</details>---

Workflow

Target URL
     │
     ▼
Parameter Detection
     │
     ▼
Payload Injection
     │
     ▼
Response Analysis
     │
     ▼
Result Output

---

Supported Platforms

Platform| Status
Linux| ✅
Termux| ✅
Ubuntu| ✅
Debian| ✅
Kali Linux| ✅

---

Repository Structure

scanxss/
│
├── scanxss.py
├── preview.jpg
├── README.md
│
└── assets/

---

Author

Name: AnsXploit
Project: ScanXSS
Language: Python
Platform: Linux / Termux

---

Disclaimer

This project is intended solely for educational purposes and authorized security testing.

Users are responsible for ensuring that all activities conducted with this software comply with applicable laws, regulations, and authorization requirements.

---

<div align="center">If you like this project, consider giving it a ⭐

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1000&color=00FF41&center=true&vCenter=true&width=500&lines=Thanks+for+using+ScanXSS;Happy+Coding" /></div>[■■■■□□□□□□] 40%
[■■■■■■□□□□] 60%
[■■■■■■■■□□] 80%
[■■■■■■■■■■] 100%

Initializing ScanXSS...
Loading Payload Database...
Preparing Scanner Engine...
Scanner Ready ✔

---

🚀 About

ScanXSS adalah tool berbasis Python yang digunakan untuk membantu menemukan parameter input yang berpotensi rentan terhadap Cross Site Scripting (XSS).

Features

- 🔍 Fast Parameter Discovery
- ⚡ Lightweight
- 📜 Multiple Parameter Support
- 🎯 Single Target Scan
- 📱 Termux Supported
- 🐍 Python Based

---

tool :

![Preview](preview.jpg)

---

📦 Installation

pkg update -y && pkg upgrade -y

pkg install git python -y

git clone https://github.com/AnsThub/scanxss.git

cd scanxss

python scanxss.py

---

🎮 Usage

python scanxss.py

Contoh:

https://target.com/search?q=test

---

🔎 PARAMETER DISCOVERY REFERENCE

==================================================================
DORK PARAMETER UMUM
==================================================================

inurl:?q=
inurl:?s=
inurl:?search=
inurl:?query=
inurl:?keyword=
inurl:?id=
inurl:?page=
inurl:?cat=
inurl:?user=
inurl:?name=
inurl:?msg=
inurl:?comment=

==================================================================
DORK SITE .ID (INDONESIA)
==================================================================

inurl:?q= site:.id
inurl:?search= site:.id
inurl:?id= site:.id
inurl:?page= site:.id
inurl:?s= site:.id
inurl:?keyword= site:.id
inurl:?cat= site:.id
inurl:?user= site:.id

==================================================================
DORK SITE .CO.ID
==================================================================

inurl:?q= site:.co.id
inurl:?search= site:.co.id
inurl:?id= site:.co.id
inurl:?page= site:.co.id

==================================================================
DORK SITE .GO.ID
==================================================================

inurl:?q= site:.go.id
inurl:?search= site:.go.id
inurl:?id= site:.go.id
inurl:?page= site:.go.id

==================================================================
DORK SITE .AC.ID
==================================================================

inurl:?q= site:.ac.id
inurl:?search= site:.ac.id
inurl:?id= site:.ac.id
inurl:?page= site:.ac.id

==================================================================
DORK SITE .COM
==================================================================

inurl:?q= site:.com
inurl:?search= site:.com
inurl:?id= site:.com
inurl:?page= site:.com
inurl:?s= site:.com
inurl:?query= site:.com

==================================================================
DORK SITE .ORG
==================================================================

inurl:?q= site:.org
inurl:?search= site:.org
inurl:?id= site:.org
inurl:?page= site:.org

==================================================================
DORK SITE .NET
==================================================================

inurl:?q= site:.net
inurl:?search= site:.net
inurl:?id= site:.net

==================================================================
DORK SITE .MY
==================================================================

inurl:?q= site:.my
inurl:?search= site:.my
inurl:?id= site:.my

==================================================================
DORK SITE .SG
==================================================================

inurl:?q= site:.sg
inurl:?search= site:.sg
inurl:?id= site:.sg

==================================================================
DORK SITE .PH
==================================================================

inurl:?q= site:.ph
inurl:?search= site:.ph
inurl:?id= site:.ph

==================================================================
DORK SITE .TH
==================================================================

inurl:?q= site:.th
inurl:?search= site:.th
inurl:?id= site:.th

---

👨‍💻 Author

Author  : AnsXploit
Tool    : ScanXSS
Version : 1.0
Language: Python

---

⚠ Disclaimer

Tool ini dibuat untuk tujuan edukasi dan pengujian pada sistem yang Anda miliki atau memiliki izin untuk diuji. Penggunaan tool ini menjadi tanggung jawab pengguna.

---

<div align="center">⭐ Don't Forget To Star This Repository

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00FF00&center=true&vCenter=true&width=500&lines=Thanks+For+Using+ScanXSS;Happy+Coding+%F0%9F%94%A5" /></div>
