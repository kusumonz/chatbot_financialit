<div align="center">

# 📈 Chatbot Financialit: AI Personal Finance Assistant

**Saatnya finansial kamu ikutan *glow up*! ✨**  
Asisten cerdas untuk bantu kamu atur *cash flow*, pahami investasi, dan capai kebebasan finansial berbasis data.

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=for-the-badge&logo=Streamlit&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2.svg?style=for-the-badge&logo=Google%20Bard&logoColor=white)
![Yahoo Finance](https://img.shields.io/badge/Yahoo%20Finance-7856FF.svg?style=for-the-badge&logo=yahoo&logoColor=white)

</div>

---

## 🚀 Apa itu Financialit?

**Financialit** *(Financial Literacy Bot)* bukan sekadar *chatbot* biasa. Ini adalah **Command Center** tata kelola keuangan pribadimu! Dibangun menggunakan teknologi *Large Language Model* (LLM) mutakhir dari Google Gemini, sistem ini dirancang untuk memberikan edukasi keuangan yang terstruktur, logis, dan *no-ribet*.

Dari bantu bedah gaji bulanan, atur strategi Dana Darurat, sampai nentuin instrumen investasi yang cocok sama profil risiko kamu — semua dipandu dengan *friendly* dan didukung oleh data pasar nyata (*real-time*). 💸

---

## ✨ Fitur Unggulan

| Fitur | Deskripsi |
|---|---|
| 🧠 **AI-Powered Financial Mentor** | Menggunakan `gemini-2.5-flash` dengan *prompt engineering* tingkat lanjut yang mengadopsi kerangka *Financial Planning* & *Behavioral Finance* |
| 📊 **Live Market Dashboard (IHSG)** | Integrasi langsung dengan `yfinance` untuk menampilkan pergerakan IHSG secara *real-time* dengan grafik *Emerald Green* |
| 🎯 **Dynamic Risk Profiling** | AI menyesuaikan gaya edukasi & rekomendasi instrumen investasi berdasarkan profil risiko: Konservatif, Moderat, atau Agresif |
| 🔒 **Secure & Stateless Memory** | *Session state* untuk mengingat konteks obrolan + manajemen API Key yang aman via *Environment Secrets* |
| 🎨 **Modern UI/UX** | Antarmuka responsif Streamlit dengan *custom CSS* (animasi *pulse-glow* & *floating coin*) |

---

## 🏗️ Arsitektur & Pendekatan Empiris

Proyek ini tidak hanya sekadar *wrapper* API, tetapi dibangun dengan landasan teori **Sistem Informasi Akuntansi (SIA)** dan **Data Analytics**.

Sistem memproses input pengguna melalui kerangka kerja terstruktur:

```
Input Pengguna
      │
      ▼
┌─────────────────────────────┐
│  1. Cash Flow & Debt Mgmt   │  ← Evaluasi likuiditas pribadi
│  2. Risk Management         │  ← Mitigasi via asuransi & OJK
│  3. Wealth Accumulation     │  ← Alokasi aset (Modern Portfolio Theory)
└─────────────────────────────┘
      │
      ▼
  Gemini LLM Response
```

---

## 🛠️ Tech Stack

- **Frontend & Framework:** [Streamlit](https://streamlit.io/)
- **AI Engine:** [Google GenAI SDK](https://aistudio.google.com/) — `gemini-2.5-flash`
- **Market Data API:** [yfinance](https://pypi.org/project/yfinance/)
- **Deployment/Testing:** Ngrok *(local tunneling / Colab)*

---

## 💻 Cara Menjalankan Secara Lokal

### 1. Clone Repositori

```bash
git clone https://github.com/username-kamu/financialit.git
cd financialit
```

### 2. Install Dependensi

Pastikan Python sudah terinstal. Sangat disarankan menggunakan *virtual environment*.

```bash
pip install -r requirements.txt
```

> **Catatan:** Pastikan `streamlit`, `google-genai`, dan `yfinance` ada di dalam `requirements.txt`.

### 3. Konfigurasi API Key *(Direkomendasikan)*

Atur Google AI API Key sebagai *environment variable* agar lebih aman:

```bash
# Windows
set GEMINI_API_KEY="API_KEY_KAMU"

# Mac / Linux
export GEMINI_API_KEY="API_KEY_KAMU"
```

### 4. Jalankan Aplikasi 🚀

```bash
streamlit run financialit.py
```

Aplikasi akan otomatis terbuka di browser pada alamat **http://localhost:8501**.

---

## 📦 requirements.txt

```plaintext
streamlit==1.32.0
google-genai
yfinance
```

---

## 🤝 Mari Berkontribusi!

Punya ide untuk bikin Financialit makin *smart*? Mau tambah fitur kalkulator *Compound Interest* otomatis atau model prediktif baru?  
**Pull Requests sangat terbuka!** Kami mengapresiasi kontribusi dari komunitas — pegiat Fintech, Data Science, mahasiswa, hingga inovator *Women in Tech*. 💡

```bash
# Langkah kontribusi
git fork https://github.com/username-kamu/financialit.git
git checkout -b feature/FiturKeren
git commit -m 'Menambahkan fitur kalkulator pajak'
git push origin feature/FiturKeren
# → Buka Pull Request di GitHub
```

---

## ⚠️ Disclaimer Edukasi

> **Financialit** dibangun secara eksklusif untuk tujuan **EDUKASI** dan **LITERASI KEUANGAN**.  
> Sistem ini **bukan** Penasihat Keuangan Tersertifikasi (CFP).  
> Semua data, simulasi, dan analisis yang dihasilkan AI **tidak boleh** dianggap sebagai saran investasi mutlak, rekomendasi beli/jual (*buy/sell*), atau jaminan imbal hasil.  
> Selalu lakukan riset mandiri (**DYOR — Do Your Own Research**) sebelum mengambil keputusan finansial nyata.

---

<div align="center">

Made with ❤️ for Financial Literacy in Indonesia 🇮🇩  
⭐ *Star this repo* jika Financialit membantumu makin melek finansial!

</div>
