
# Analisis Pencocokan Fitur pada Citra Mobil dan Bus Menggunakan SIFT

Final project untuk mata kuliah Visi Komputer.  
Project ini bertujuan untuk mengimplementasikan algoritma **Scale Invariant Feature Transform (SIFT)** dalam proses **feature detection** dan **feature matching** pada citra kendaraan.


## Deskripsi Proyek

Dalam proyek ini, algoritma SIFT digunakan untuk mendeteksi titik-titik fitur (keypoint) dan mencocokkan fitur antara dua citra kendaraan, yaitu **mobil** dan **bus**.  
Proses pencocokan fitur dilakukan menggunakan **Brute Force Matcher (BFMatcher)**.  
Implementasi dilakukan menggunakan bahasa pemrograman Python dengan library OpenCV, NumPy, dan Matplotlib.


##  Struktur File
├── final-project.ipynb # Notebook utama implementasi SIFT
├── random-kuda-dan-mobil.ipynb # Eksperimen tambahan mobil vs kuda
├── mobil.jpg # Dataset citra mobil
├── bus.jpg # Dataset citra bus
├── kuda.png # Dataset tambahan untuk eksperimen
├── final project.pdf # Laporan akhir
└── README.md # Dokumentasi proyek

## library dan tools
- Python 
- OpenCV  
- NumPy  
- Matplotlib

  ##  Cara Menjalankan (Reproducibility)

### 1️.Clone Repository

```bash
git clone https://github.com/username/Analisis-Pencocokan-Fitur-pada-Citra-Mobil-dan-Bus-Menggunakan-sift.git
cd Analisis-Pencocokan-Fitur-pada-Citra-Mobil-dan-Bus-Menggunakan-sift

```
## 2.install library
pip install opencv-python numpy matplotlib

## 3.jalankan notebook 
jupyter notebook final-project.ipynb

## Atau upload file notebook dan dataset ke Kaggle Notebook.

##Metodologi Eksperimen
1.Membaca citra mobil dan bus
2.Konversi citra ke grayscale
3.Deteksi keypoint dan descriptor menggunakan SIFT
4.Pencocokan fitur menggunakan Brute Force Matcher
5.Visualisasi keypoint dan hasil matching
6.Analisis jumlah keypoint dan matching

## Hasil Eksperimen

1.SIFT berhasil mendeteksi keypoint pada kedua citra kendaraan
2.Feature matching menunjukkan kecocokan fitur antara mobil dan bus
3.Eksperimen tambahan dilakukan dengan objek berbeda (mobil dan kuda) untuk melihat pengaruh perbedaan objek terhadap jumlah matching

## kesimpulan singkat
Algoritma SIFT mampu mendeteksi dan mencocokkan fitur pada citra kendaraan dengan baik. Namun, jumlah kecocokan fitur sangat dipengaruhi oleh karakteristik objek pada citra. Pada objek yang sangat berbeda, seperti mobil dan kuda, jumlah kecocokan fitur tetap ada tetapi tidak merepresentasikan kesamaan objek secara semantik.

## Author
Nama: Muhammad Haekal
Final Project Visi Komputer
