# Recipe Intelligence Dashboard 🍲📊


## 📌 Deskripsi Proyek

**Recipe Intelligence Dashboard** adalah Capstone Project dari program **Dicoding Data Scientist** yang berfokus pada analisis dan visualisasi interaktif dataset resep makanan.

Proyek ini terdiri dari dua komponen utama:
- `ProjekCapstone.ipynb` — Notebook eksplorasi data, preprocessing, dan pemodelan clustering
- `dashboard/` — Aplikasi web interaktif berbasis **Streamlit** untuk menampilkan hasil analisis secara dinamis

---

## 📸 Demo Aplikasi Dashboard

**Kunjungin Url Berikut**
https://smartgroceryplanner.streamlit.app/

---

## 📂 Struktur Folder

```
DATA-SCIENTIST/
│
├── dashboard/
│   ├── dashboard.py                      
│   └── resep_bersih_clustered_new.csv    
│
├── data/                                 
│
├── ProjekCapstone.ipynb                  
├── requirements.txt                      
├── .gitignore                           
└── README.md                             
```

---

## ⚙️ Setup Environment

Ikuti langkah-langkah berikut untuk menyiapkan environment secara lokal.

### Prasyarat
Pastikan **Python 3.9+** sudah terinstal di sistem Anda. Cek dengan:
```bash
python3 --version
```

### Langkah-langkah Instalasi

**1. Clone repositori ini**
```bash
git clone https://github.com/DREAM-TEAM-2026/DATA-SCIENTIST.git
cd DATA-SCIENTIST
```

**2. Buat virtual environment**
```bash
python3 -m venv .env
```

**3. Aktifkan virtual environment**

| Sistem Operasi | Perintah |
|---|---|
| Linux / macOS | `source .env/bin/activate` |
| Windows (CMD) | `.env\Scripts\activate.bat` |
| Windows (PowerShell) | `.env\Scripts\Activate.ps1` |

**4. Instal semua dependencies**
```bash
pip install -r requirements.txt
```

---

## ▶️ Menjalankan Aplikasi

Setelah environment aktif dan dependencies terinstal, jalankan perintah berikut:

```bash
streamlit run dashboard/dashboard.py
```

Aplikasi akan otomatis terbuka di browser pada `http://localhost:8501`.

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
|---|---|
| 📊 **Analisis Data** | Pengolahan dataset resep menggunakan Pandas & NumPy |
| 🎨 **Visualisasi** | Grafik informatif dengan Matplotlib & Seaborn |
| 🖥️ **Dashboard Interaktif** | Antarmuka responsif dibangun dengan Streamlit |
| 🔍 **Clustering** | Pengelompokan resep berdasarkan karakteristik menggunakan model ML |

---

## 📝 Catatan Penting

- File dataset berukuran besar (`data/` dan `dashboard/resep_bersih_clustered_new.csv`) **tidak di-push ke GitHub** sesuai konfigurasi `.gitignore`.
- Untuk **Mentor / Reviewer**: buka `ProjekCapstone.ipynb` untuk melihat seluruh alur pemrosesan data dan analisis secara lengkap.
- Jika menemui error saat aktivasi PowerShell, jalankan: `Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned`

---

## 👨‍💻 Authors

**Dibuat oleh team Data Scientist**.

| Nama | ID Dicoding |
|---|---|
| Yunas Wildan Yudhistira | CDCC657D6Y0413 |
| Zaskiyah Sofarina | CDCC913D6X0972 |
