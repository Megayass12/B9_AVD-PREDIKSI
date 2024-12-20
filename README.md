## Analisis dan Prediksi Cuaca

Program ini dirancang untuk menganalisis dan memprediksi data cuaca berdasarkan berbagai variabel seperti suhu minimum, suhu maksimum, kelembapan, curah hujan, dan durasi sinar matahari. 
Dengan menggunakan algoritma regresi linier, program ini dapat memprediksi suhu rata-rata berdasarkan data historis.

Program ini mencakup langkah-langkah berikut:
- Pembersihan data dan penanganan nilai yang hilang.
- Normalisasi data menggunakan skala standar.
- Pelatihan model regresi linier.
- Evaluasi performa model dengan metrik statistik.
- Visualisasi hasil prediksi untuk analisis lebih lanjut.

## Prasyarat
Pastikan Anda telah menginstal perangkat lunak berikut:
- **Python 3.8+**
- **pip** (untuk mengelola pustaka Python)

Library Python yang diperlukan:
- pandas
- numpy
- matplotlib
- scikit-learn

## Langkah-langkah Instalasi dan Eksekusi

1. **Kloning atau Unduh Proyek**
2. **Instal Pustaka yang Dibutuhkan**
   Gunakan perintah berikut untuk menginstal semua pustaka yang diperlukan:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
3. **Siapkan Dataset**
   Pastikan file dataset `data_cuaca.csv` tersedia di direktori yang sama dengan file notebook. Dataset harus sesuai format:
   - Kolom: `temp_min`, `temp_max`, `lembab_rata-rata`, `ch`, `cahaya_jam`, `temp_rata-rata`.
   - Format: CSV dengan separator `;`.

4. **Buka Notebook**
   Jalankan Jupyter Notebook untuk membuka file `PREDIKSI_AVD.ipynb`:

5. **Jalankan Seluruh Notebook**
   Setelah notebook terbuka, pilih **Cell** > **Run All** untuk mengeksekusi seluruh kode.

## Output Program
- **Metrik Evaluasi:**
  - Mean Squared Error (MSE): Mengukur rata-rata kesalahan kuadrat prediksi.
  - R-squared Score (R²): Menilai performa model secara keseluruhan.

- **Visualisasi:**
  - Scatter plot yang menunjukkan hubungan antara nilai aktual dan prediksi.
  - Scatter plot yang menunjukkan hubungan curah hujan vs suhu rata-rata (Log scale)
  - Heatmap pairwise correlation antar parameter cuaca

- **Analisis Koefisien:**
  - Menampilkan kontribusi setiap fitur terhadap prediksi suhu rata-rata.


**Happy Coding!** 🚀

