A. # Prediksi-Kelulusan-Mahasiswa-Menggunakan-Support-Vector-Machine-SVM-

B. Fitur-fitur dalam Dataset:
1. NAMA - Nama mahasiswa (tidak digunakan untuk modeling)
2. JENIS KELAMIN - Kategorikal: PEREMPUAN, LAKI - LAKI
3. STATUS MAHASISWA - Kategorikal: BEKERJA, MAHASISWA
4. UMUR - Numerik: Usia mahasiswa
5. STATUS NIKAH - Kategorikal: MENIKAH, BELUM MENIKAH
6. IPS 1 sampai IPS 8 - Numerik: Indeks Prestasi Semester 1-8 (skala 0-4)
7. IPK - Numerik: Indeks Prestasi Kumulatif (skala 0-4)
8. STATUS KELULUSAN - Target: TEPAT, TERLAMBAT
C. Langkah pengerjaan : 
1. . Exploratory Data Analysis (EDA)
2. Preprocessing Data
3. Training Model SVM
4. Evaluasi Model
5.  Interpretasi Model
6.  Deployment Sederhana
7.   Dokumentasi & GitHub
D. HASIL evaluasi model:
Model SVM dengan kernel RBF berhasil memprediksi status kelulusan mahasiswa (TEPAT vs TERLAMBAT) dengan akurasi 92.41%. Model menunjukkan performa excellent dengan precision 92.70%, recall 92.41%, dan ROC-AUC 96.50%.
FAKTOR PENENTU:
1.  K - faktor paling dominan
2.  IPS Semester 4 - titik kritis studi
3.  Status Mahasiswa - full-time lebih tepat waktu
4.  Konsistensi IPS dari semester awal
E.  Cara Menjalankan Notebook
Di Google Colab:
Buka Google Colab
Pilih "Upload notebook"
Upload file SVM_kelulusan.ipynb
Jalankan sel pertama untuk mengupload dataset
Upload file datakelulusanmahasiswa.csv
Jalankan semua sel (Runtime → Run all)
F.  Identitas mahasiswa :
1. Nama :Norresa Ramadani
2. Prodi: Manajemen
3. NPM :2461201002125

   link tugas : https://colab.research.google.com/drive/12O4fOIhg65pLqcJbcQdjmTvVywIX518O?usp=sharing
