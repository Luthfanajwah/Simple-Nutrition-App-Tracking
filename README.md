# Simple Nutrition App Tracking
---

Simple Nutrition App Tracking adalah aplikasi web interaktif yang dirancang untuk membantu pengguna melacak asupan nutrisi harian (kalori dan makronutrisi) hanya dengan mengetikkan teks biasa (prompt). Dengan memanfaatkan kekuatan **Gemini API**, aplikasi ini mampu mengurai kalimat kasual menjadi data nutrisi terstruktur secara instan.

Proyek ini dikembangkan sebagai bagian dari acara **"RIPTECH AI Web-Dev Mini Hackathon & Masterclass"** untuk mendemonstrasikan bagaimana sebuah ide kreatif dapat diwujudkan menjadi *real website* siap pakai menggunakan bantuan AI.

🌐 Live Demo / Hosting
Aplikasi ini telah dideploy dan dapat diakses langsung melalui Replit:
🚀 **[Gizi App](https://asset-manager--luthfanajwah.replit.app/)**

---

🖥️ Fitur Utama

| Fitur | Deskripsi |
| :--- | :--- |
| 💬 AI Prompt Logging | Ketik makanan Anda (misal: *"Makan siang pakai nasi goreng ayam dan telur mata sapi"*), Gemini akan menghitung nutrisinya. |
| 📊 Daily Dashboard | Grafik kemajuan (*progress bar*) real-time untuk memantau sisa kuota kalori, protein, karbohidrat, dan lemak harian. |
| 📅 History Tracking | Catatan riwayat makanan yang langsung bertambah setiap kali pengguna mengirimkan prompt baru. |
| 🧠 Gemini AI Parsing | Integrasi prompt engineering berbasis *client-side* untuk mengenali nama makanan lokal maupun porsinya secara akurat. |
| ⚡ Serverless & Lightweight | Berjalan sepenuhnya di sisi klien tanpa memerlukan backend database yang rumit. |

---

👥 Tim Pengembang (Kolaborator)

Proyek ini dibangun secara kolaboratif oleh tim lintas disiplin ilmu yang memadukan keahlian teknologi, analisis data, dan ilmu terapan:

1. **Muhamad Mustofa Arif** — Pendidikan Kimia 2024
2. **Luthfa Qubailatun Najwah** — Teknik Informatika 2023
3. **Alya Rahma Fadhila** — Statistika dan Sains Data 2025
4. **Zhahiran Abyan Muhsin** — Teknik Informatika 2023

---

🏗️ Struktur Proyek

```text
Simple-Nutrition-App-Tracking/
├── index.html              # Struktur UI Utama & Dashboard
└── README.md
```
---

### Cara Menjalankan Secara Lokal / Replit

**Menjalankan di Replit (Cloud)
**Buka akun Replit Anda.
**Fork atau buat Repl baru dengan template HTML/CSS/JS.
**Upload file index.html, style.css, dan script.js ke dalam Repl tersebut.
**Tekan tombol *Run*.

### Menjalankan di Lokal (PC/Laptop)

**Clone repositori ini:
```
Bash
git clone [https://github.com/Luthfanajwah/Simple-Nutrition-App-Tracking.git](https://github.com/Luthfanajwah/Simple-Nutrition-App-Tracking.git)
cd Simple-Nutrition-App-Tracking
```
**Buka file index.html langsung di browser pilihan Anda (Double-click atau drag-and-drop).

⚠️ Catatan Penting: Pastikan Anda telah memasukkan GEMINI_API_KEY Anda di dalam variabel konfigurasi pada file script.js agar fitur pengenalan makanan berbasis AI dapat berfungsi dengan normal.
