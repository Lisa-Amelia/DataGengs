<div align="center">

---

# Data Gengs
### Pengelompokan Kabupaten/Kota di Indonesia Berdasarkan Indeks Khusus Penanganan Stunting Menggunakan Self Organizing Maps (SOM)

</div>

---

## 📄 Deskripsi Project

Proyek ini bertujuan untuk mengelompokkan kabupaten/kota di Indonesia berdasarkan Indeks Khusus Penanganan Stunting (IKPS) menggunakan metode Self Organizing Maps (SOM). SOM adalah algoritma unsupervised learning yang digunakan untuk memetakan data ke dalam bentuk visual yang mudah dipahami. Dengan metode ini, wilayah-wilayah dengan karakteristik penanganan stunting yang mirip akan tergabung dalam satu klaster. Proyek ini diharapkan dapat membantu pengambil kebijakan dalam mengidentifikasi daerah prioritas intervensi serta merancang strategi yang lebih tepat sasaran.

---

## 🧠 Latar Belakang

---

##  Indeks Khusus Penanganan Stunting (IKPS)

---

## Self Organizing Maps (SOM)

---

## 📊 Sumber Data dan Variabel

Data yang digunakan dalam proyek ini berasal dari beberapa sumber resmi berikut:

- **Survei Status Gizi Balita Indonesia (SSGBI) 2023** – Data indeks stunting dan indikator kesehatan anak balita di seluruh provinsi Indonesia.  
  Sumber: [https://example.gov.id/ssgbi-2023](https://example.gov.id/ssgbi-2023)

- **Badan Pusat Statistik (BPS) Indonesia** – Data demografi, sosial ekonomi, dan akses layanan kesehatan provinsi.  
  Sumber: [https://bps.go.id/](https://bps.go.id/)

- **Kementerian Kesehatan Republik Indonesia (Kemenkes RI)** – Laporan tahunan dan data program penanganan stunting.  
  Sumber: [https://www.kemkes.go.id/](https://www.kemkes.go.id/)

Data tersebut telah diproses dan distandarisasi untuk keperluan analisis menggunakan metode Self Organizing Maps (SOM).

---

## 🔄 Alur Proyek

1. **Pengumpulan Data**  
   Mengumpulkan dan membersihkan data indikator penanganan stunting dari sumber resmi.  

2. **Pra-pemrosesan**  
   Melakukan normalisasi dan standarisasi data agar sesuai untuk analisis SOM.  

3. **Pelatihan SOM**  
   Melatih model Self Organizing Maps untuk memetakan provinsi ke dalam klaster.  

4. **Visualisasi Hasil**  
   Menampilkan hasil klaster dalam bentuk peta dan grafik untuk interpretasi.  

5. **Analisis dan Rekomendasi**  
   Menganalisis klaster yang terbentuk dan memberikan rekomendasi kebijakan.  

---

## 📈 Hasil Analisis

---

## 🛠️ Instalasi

Untuk menjalankan proyek ini secara lokal menggunakan R, ikuti langkah berikut:

### Prasyarat  
- R versi 4.0+  
- Paket R: `kohonen`, `openxlsx`, `ggplot2`, `cluster`

### Langkah-langkah  
1. Clone repository:  
   ```bash
   git clone https://github.com/yourusername/repo.git
---
