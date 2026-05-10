# SobatKulit Groq Chatbot

SobatKulit adalah aplikasi chatbot berbasis React + TypeScript + Vite yang berfungsi sebagai asisten AI konsultasi kesehatan kulit non-diagnostik menggunakan Groq API.

SobatKulit membantu pengguna memahami kondisi kulit secara umum, memberikan edukasi skincare harian, serta memberi saran perawatan awal yang aman tanpa menggantikan diagnosis medis profesional.


## SobatKulit membantu pengguna dalam:
- Daily skincare routine
- Perawatan kulit dasar
- Edukasi masalah kulit umum
- Jerawat
- Kulit sensitif
- Kulit berminyak
- Kulit kering
- Iritasi ringan
- Rekomendasi langkah awal perawatan
- Arahan ke dokter kulit jika kondisi serius


# Features
- Konsultasi kesehatan kulit non-diagnostik berbasis AI
- Daily skincare guidance
- Edukasi kondisi kulit umum
- Prompt injection protection
- Aman dari manipulasi sistem
- Rekomendasi perawatan awal
- Escalation ke dermatologis jika diperlukan
- Health check otomatis API
- Modern chat interface
- Fast response menggunakan Groq LLM


# Important Medical Disclaimer
SobatKulit:
- Bukan pengganti dokter
- Tidak memberikan diagnosis pasti
- Tidak meresepkan obat keras
- Tidak menggantikan konsultasi medis profesional

Jika pengguna mengalami kondisi berat, memburuk, infeksi, atau gejala serius, SobatKulit akan menyarankan pemeriksaan langsung ke dokter kulit atau tenaga medis terkait.

---

# Branch Naming
**Catatan Penamaan Branch**
- Silahkan membuat `branch` anda sendiri sebelum mengerjakan fitur
- contoh : `nama/feature` = `budi/landing-pages`


## Instalation
Clone Repository
```sh
git git clone https://github.com/username/chefbot-groq-chatbot.git
```
Tulis perintah dibawah in untuk menginstal depedensi yang di perlukan 
```
npm install
```

Lalu copy file .env 
```sh
cp .env.example .env
```

Lalu isi API KEY pada .env
```sh
VITE_GROQ_API_KEY=your_groq_api_key_here
``` 

## Running Project
```sh
npm run dev
```
