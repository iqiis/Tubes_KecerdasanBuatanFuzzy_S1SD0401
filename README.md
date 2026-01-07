Program Fuzzy System Air Quality

1. Deskripsi Program
Program ini merupakan implementasi Sistem Fuzzy menggunakan metode Mamdani dengan defuzzification Centroid untuk menentukan kualitas udara. Program dibuat menggunakan bahasa pemrograman Python tanpa menggunakan library fuzzy, sesuai dengan ketentuan Tugas Besar Mata Kuliah Kecerdasan Buatan. Input sistem berupa data kualitas udara dari dataset AirQualityUCI, dan output berupa skor kualitas udara dalam rentang 0–100.

2. Kebutuhan Program
Untuk menjalankan program ini, diperlukan:
- Python
- Library Python:
  - pandas
  - numpy
- Dataset: AirQualityUCI.xlsx
Program direkomendasikan dijalankan menggunakan Google Colab.

3. Cara Menjalankan Program
Langkah-langkah menjalankan program di Google Colab:
  1. Buka Google Colab (https://colab.research.google.com)
  2. Upload file berikut ke Google Colab:
     - main_fuzzy_air_quality.py
     - AirQualityUCI.xlsx
  3. Pastikan kedua file berada pada folder yang sama.
  4. Jalankan seluruh cell atau jalankan file Python tersebut.
  5. Program akan memproses data menggunakan Sistem Fuzzy.
  6. Hasil akan ditampilkan pada output dan disimpan dalam file CSV.

4. Output Program
Output program berupa:
- Skor kualitas udara untuk setiap data
- File hasil bernama:
  "Top5_Kualitas_Udara_Fuzzy.csv"
yang berisi 5 data dengan kualitas udara terbaik berdasarkan hasil perhitungan sistem fuzzy.

5. Catatan Penting
- Program ini tidak menggunakan library fuzzy apa pun.
- Seluruh proses fuzzification, inferensi, dan defuzzification dilakukan secara manual.
- Variabel NOx(GT) dan C6H6(GT) digunakan sebagai indikator polusi udara sesuai dengan ketersediaan dataset AirQualityUCI.
