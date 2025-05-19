<div align="center">

---

# Data Gengs
### Pengelompokan Kabupaten/Kota di Indonesia Berdasarkan Indeks Khusus Penanganan Stunting Menggunakan Self Organizing Maps

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

ASK-MAN adalah sebuah proyek yang bertujuan untuk memverifikasi keaslian tanda tangan dokumen menggunakan teknik deep learning. Proyek ini memanfaatkan Convolutional Neural Network (CNN) dan Siamese Neural Network (SNN) dengan pengukuran Jarak Mahalanobis untuk mencocokkan tanda tangan yang tertera pada dokumen.

---

## 📄 Deskripsi Proyek

Proyek ini bertujuan untuk mengelompokkan provinsi di Indonesia berdasarkan indeks khusus yang berkaitan dengan penanganan stunting. Stunting merupakan masalah gizi yang mempengaruhi pertumbuhan fisik dan perkembangan anak, yang dapat memiliki dampak jangka panjang terhadap kualitas sumber daya manusia di masa depan. Oleh karena itu, pengelompokan provinsi berdasarkan penanganan stunting sangat penting untuk memahami distribusi dan kondisi penanganan stunting di seluruh Indonesia.

Dalam proyek ini, metode yang digunakan untuk melakukan analisis pengelompokan adalah Self Orgainizing Maps.

**Self Orgainizing Maps (SOM)**:
   SElf Organizing Maps adalah metode tanpa pengawasan yang digunakan untuk memetakan dan mengelompokkan provinsi berdasarkan indikator stunting. Dengan SOM, wilayah dengan karakteristik serupa ditampilkan berdekatan dalam peta, membantu analisis pola dan mendukung pengambilan keputusan yang lebih tepat sasaran dalam penanggulangan stunting di Indonesia.

Proyek ini melibatkan pengumpulan dan analisis data yang mencakup faktor-faktor yang mempengaruhi stunting, seperti tingkat pendidikan, akses ke layanan kesehatan, gizi, dan indikator sosial-ekonomi lainnya. Data yang telah diproses dan distandarisasi kemudian dianalisis menggunakan kedua algoritma tersebut untuk mengidentifikasi klaster-klaster yang mencerminkan kondisi penanganan stunting di provinsi-provinsi Indonesia.

**Output yang Diharapkan**:

- Pembentukan klaster-klaster provinsi berdasarkan tingkat keberhasilan penanganan stunting, yang dapat digunakan untuk merencanakan kebijakan yang lebih tepat sasaran.

- Visualisasi hasil pengelompokan dalam bentuk peta atau diagram yang memudahkan pemangku kebijakan dan masyarakat untuk memahami distribusi penanganan stunting di Indonesia.

- Rekomendasi kebijakan berdasarkan hasil pengelompokan untuk meningkatkan penanganan stunting di provinsi-provinsi dengan indeks rendah.

Dengan pendekatan ini, diharapkan proyek ini dapat memberikan wawasan yang lebih mendalam tentang tantangan yang dihadapi dalam penanganan stunting di Indonesia dan membantu pemerintah serta organisasi terkait untuk merancang intervensi yang lebih efektif.

---

## Demo

Untuk melihat demo dari proyek ini, silakan klik link berikut:

[**Demo Project**](#)

Demo ini memperlihatkan cara kerja model deep learning dalam memverifikasi tanda tangan dokumen.

---

## 📈 Alur Proyek

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
