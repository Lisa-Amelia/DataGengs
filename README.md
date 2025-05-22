<div align="center">

---

# Data Gengs
### Pengelompokan Kabupaten/Kota di Indonesia Berdasarkan Indeks Khusus Penanganan Stunting Menggunakan Self Organizing Maps (SOM)

</div>

---

<p align="center">
  <a href="#tentang">Tentang</a> •
  <a href="#deskripsi-project">Deskripsi Project</a> •
  <a href="#demo">Demo</a> •
  <a href="#alur-proyek">Alur Proyek</a>
</p>

---

## ⚙️ Tentang

Proyek ini bertujuan untuk mengelompokkan provinsi di Indonesia berdasarkan Indeks Khusus Penanganan Stunting menggunakan metode Self Organizing Maps (SOM). Dengan teknik unsupervised learning ini, provinsi yang memiliki karakteristik serupa terkait penanganan stunting akan tergabung dalam klaster yang sama, sehingga dapat membantu analisis pola dan pengambilan kebijakan yang lebih tepat sasaran.

---

## 📄 Deskripsi Proyek

Stunting merupakan masalah gizi kronis yang mempengaruhi pertumbuhan dan perkembangan anak di Indonesia. Proyek ini menggunakan data indikator-indikator yang berkaitan dengan penanganan stunting, seperti akses layanan kesehatan, status gizi, pendidikan, dan faktor sosial-ekonomi lainnya.

Self Organizing Maps (SOM) adalah algoritma neural network tanpa pengawasan yang memetakan data berdimensi tinggi ke dalam peta dua dimensi sehingga klaster dengan karakteristik serupa dapat dikenali dengan mudah.

Melalui proyek ini, diharapkan dapat diidentifikasi kelompok provinsi yang membutuhkan perhatian khusus dalam penanganan stunting dan membantu perumusan kebijakan berbasis data.

**Output yang Diharapkan**:  
- Klaster provinsi berdasarkan tingkat dan karakteristik penanganan stunting  
- Visualisasi peta klaster yang mudah dipahami  
- Rekomendasi kebijakan berdasarkan hasil pengelompokan

---

## 📊 Sumber Data

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
