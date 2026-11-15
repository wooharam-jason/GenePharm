# GenePharm Explorer

Platform Analisis Mutasi Gen Penyakit & Farmakogenomik Presisi — berbasis web, single-file, standar CPIC.

## 🧬 Tentang

GenePharm Explorer adalah alat eksplorasi farmakogenomik dan detektor gen penyebab penyakit berbasis web untuk mahasiswa farmasi, peneliti medis, dan praktisi kesehatan. Platform ini mengikuti alur:

**Penyakit → Gen Penyebab Mutasi → Struktur Molekul 2D → Rekomendasi Dosis CPIC**

## ✨ Fitur

- **Disease-First Search** — Pencarian berbasis nama penyakit dengan filter multi-kategori
- **Gene Workstation** — Identifikasi gen, lokus kromosom, dan tabel varian rsID
- **2D Chemical Structure** — Visualisasi skeletal formula obat pada HTML5 Canvas
- **CPIC Dosing Chart** — Grafik respons terapi berdasarkan genotipe (Chart.js)
- **Custom Disease Input** — Modal untuk menambahkan data penyakit baru
- **Clinical Dossier Print** — Cetak laporan klinis langsung dari browser

## 🗂️ Dataset Klinis Bawaan

| Penyakit | Gen | Lokus | Obat |
|---|---|---|---|
| Resistensi Clopidogrel | CYP2C19 | 10q24.2 | Clopidogrel |
| Kanker Payudara Herediter | BRCA1/BRCA2 | 17q21.31 / 13q13.1 | Olaparib |
| Sistisk Fibrosis | CFTR | 7q31.2 | Ivacaftor |
| Sensitivitas Warfarin | VKORC1/CYP2C9 | 16p11.2 / 10q23.33 | Warfarin |
| Toksisitas 5-FU | DPYD | 1p21.4 | 5-Fluorouracil |
| Hipersensitivitas Abacavir | HLA-B | 6p21.33 | Abacavir |
| Miopati Simvastatin | SLCO1B1 | 12p12.1 | Simvastatin |

## 🚀 Cara Menjalankan

Buka `index.html` langsung di browser modern (Chrome, Safari, Edge, Firefox).

```bash
# Opsional: local server
python3 -m http.server 8080
# Buka http://localhost:8080
```

## 🎨 Desain

- **Theme:** Medical High-Tech Dark Mode
- **Fonts:** Plus Jakarta Sans, Inter, Fira Code
- **Stack:** HTML5, Tailwind CSS CDN, Chart.js, Vanilla JS

## 📋 Standar Acuan

CPIC (Clinical Pharmacogenetics Implementation Consortium) / PharmGKB / DPWG Guidelines

## 📄 Lisensi

MIT License
