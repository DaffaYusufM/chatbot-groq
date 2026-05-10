# ChefBot Groq Chatbot
ChefBot adalah aplikasi chatbot berbasis React + TypeScript + Vite yang berfungsi sebagai asisten AI rekomendasi menu restoran menggunakan Groq API.

# Rules Contributor
**ChefBot membantu pengguna memilih makanan, minuman, dan dessert berdasarkan:**
- Budget
- Selera
- Mood makan
- Alergi
- Dietary restriction

# Features
- Rekomendasi menu restoran berbasis AI
- Prompt injection protection
- Validasi daftar menu & harga resmi
- Health check otomatis API
- Modern chat interface
- Fast response menggunakan Groq LLM

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
