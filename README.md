# 💻✨ Selamat Datang di Playground Ngoprek Web!

Yo! Ini tempat gue ngumpulin hasil utak-atik dunia *cybersecurity*, terutama di bagian **web security**.  
Kadang ngulik celah, kadang iseng scan, kadang juga… eh, nyenggol origin server sampe down 🤭 (seriusan ini pernah kejadian, nanti gue ceritain 👇)

---

## 🔍 Cerita Nyata dari Lapangan

> Target: subdomain sekolah  
> Endpoint: `/login`  
> Tools: `nmap + proxychains`

🎯 Ceritanya iseng enum database, eh taunya ngehit **origin langsung**, bukan ke Cloudflare-nya.  
Dan... BOOM! Pas dibuka di browser: **"host unreachable"**, tapi Cloudflare-nya masih standby 🤡  
Auto ngakak, tapi juga langsung sadar:  
**"Oops, ini kayaknya udah nyentuh titik sensitif."**

Tenang, udah gue laporin ke pihak yang bersangkutan baik-baik. Edukatif, bukan eksploitasi 🙌

---

## 🧪 Mainan Favorit

| Tools      | Kegunaan                           |
|------------|------------------------------------|
| 🔎 Burp     | Intercept traffic web             |
| 🐍 sqlmap   | Cari SQL Injection otomatis        |
| 🎯 Nmap     | Port scanning + service detection |
| 💥 XSStrike | Testing XSS auto payload          |
| 🌐 Curl     | Intip response dan header         |
| 🧠 Amass    | Subdomain hunter                   |
| 🧵 Slowloris| Simulasi DoS ringan                |
| ⚙️ Rapidscan| Quick scan multiple tools          |

Gue juga suka oprek `bash` atau bikin skrip kecil buat bantu enum. Simple tapi efektif 😎

---

## 📁 Isi Playground Ini

- 🐞 Laporan kerentanan dari bug bounty & audit manual  
- 🔬 Catatan testing, scanning, dan analisa web security  
- ⚙️ Koleksi tools & snippet oprekan pribadi  
- 🚧 Kadang random eksperimen, jadi harap maklum kalau berantakan

---

## 🌱 Misi

Belajar sambil ngeksplor, bukan ngehancurin.  
Bantu edukasi soal keamanan aplikasi web, satu bug, satu laporan, satu tawa pada waktunya 😄  
Karena jadi hacker tuh gak harus dark mode terus. Kadang *debugging sambil ngopi juga seni.*

---

> “Kadang yang bikin down bukan serangan, tapi rasa penasaran berlebihan 😅”

Thanks udah mampir — kalo nyasar ke sini dan punya cerita atau mau diskusi, drop aja issues atau fork repo ini.

Stay safe & keep hacking (the legal way)! 🛡️✨
[![HackerOne](https://img.shields.io/badge/HackerOne-Profile-black?logo=hackerone&logoColor=white)](https://hackerone.com/chunsky)
