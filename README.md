<div align="center">

---

# Data Gengs
### Pengelompokan Kabupaten/Kota di Pulau Sulawesi Berdasarkan Indeks Khusus Penanganan Stunting Menggunakan Bat Algorithm - Fuzzy C Means

</div>

---

<p align="center">
  <a href="#tentang">Tentang</a> •
  <a href="#deskripsi-project">Deskripsi Project</a> •
  <a href="#demo">Demo</a> •
  <a href="#alur-proyek">Alur Proyek</a>
</p>

---

## Tentang

ASK-MAN adalah sebuah proyek yang bertujuan untuk memverifikasi keaslian tanda tangan dokumen menggunakan teknik deep learning. Proyek ini memanfaatkan Convolutional Neural Network (CNN) dan Siamese Neural Network (SNN) dengan pengukuran Jarak Mahalanobis untuk mencocokkan tanda tangan yang tertera pada dokumen.

---

## Deskripsi Proyek

Proyek ini menggabungkan teknik machine learning untuk memverifikasi tanda tangan pada dokumen menggunakan dua model utama: CNN untuk ekstraksi fitur dan SNN untuk perbandingan tanda tangan. Mahalanobis Distance digunakan untuk mengukur kesamaan antara tanda tangan yang terverifikasi dengan yang ditandatangani pada dokumen.

### Fitur Utama:
- **Verifikasi Tanda Tangan**: Menggunakan deep learning untuk memverifikasi keaslian tanda tangan pada dokumen.
- **Model Deep Learning**: Menggunakan CNN dan SNN untuk menganalisis dan membandingkan tanda tangan.
- **Pengukuran Jarak Mahalanobis**: Menggunakan Mahalanobis Distance untuk menghitung kesamaan tanda tangan.

---

## Demo

Untuk melihat demo dari proyek ini, silakan klik link berikut:

[**Demo Project**](#)

Demo ini memperlihatkan cara kerja model deep learning dalam memverifikasi tanda tangan dokumen.

---

## Alur Proyek

1. **Input**: Memasukkan dokumen yang berisi tanda tangan.
2. **Preprocessing**: Memproses gambar untuk meningkatkan kualitas dan mengekstraksi fitur dari tanda tangan.
3. **Pelatihan Model**: Melatih model CNN dan SNN dengan dataset tanda tangan yang sudah diberi label.
4. **Verifikasi**: Menggunakan model yang telah dilatih untuk memverifikasi tanda tangan pada dokumen yang diberikan.
5. **Output**: Hasil verifikasi yang menunjukkan apakah tanda tangan pada dokumen tersebut asli atau palsu.

---

## Instalasi

Untuk menjalankan proyek ini secara lokal, ikuti langkah-langkah berikut:

### Prasyarat:
1. Python 3.6+
2. TensorFlow atau PyTorch
3. OpenCV

### Langkah-langkah:
1. Clone repository:
    ```bash
    git clone https://github.com/yourusername/ASK-MAN.git
    ```
2. Instal dependensi:
    ```bash
    pip install -r requirements.txt
    ```
3. Jalankan proyek:
    ```bash
    python main.py
    ```

---

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan buat pull request atau buka issue untuk saran dan perbaikan.

---

## Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.
