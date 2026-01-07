Fuzzy System Air Quality

1. Deskripsi Program
Program ini merupakan implementasi Sistem Fuzzy Logic menggunakan metode Mamdani dengan defuzzification Centroid untuk menentukan kualitas udara. Sistem fuzzy dibangun secara manual tanpa menggunakan library fuzzy, sesuai dengan ketentuan Tugas Besar Mata Kuliah Kecerdasan Buatan.
Input sistem berupa data kualitas udara dari dataset AirQualityUCI, sedangkan output sistem berupa skor kualitas udara dalam rentang 0–100 serta pemilihan 5 data dengan kualitas udara terbaik berdasarkan hasil perhitungan sistem fuzzy.

2. Dataset dan Atribut Input
Dataset yang digunakan adalah AirQualityUCI.xlsx.

Atribut yang digunakan dalam sistem fuzzy:
  1) CO(GT)
  2) NO2(GT)
  3) C6H6(GT) sebagai proxy O₃
  4) NOx(GT) sebagai indikator tingkat polusi udara

3. Metode yang Digunakan
- Metode Inferensi        : Mamdani
- Operator AND            : Minimum (MIN)
- Agregasi Aturan         : Maximum (MAX)
- Metode Defuzzification  : Centroid
- Rentang Output          : 0 – 100

4. Bahasa dan Library
Bahasa pemrograman yang digunakan adalah Python.
Library Python yang digunakan:
- pandas
- numpy

5. Cara Menjalankan Program
Program direkomendasikan dijalankan menggunakan Google Colab.

Langkah-langkah menjalankan program:
  1. Buka Google Colab (https://colab.research.google.com)
  2. Upload file berikut ke Google Colab:
     - TUBES AI_FUZZY SYSTEM.ipynb
     - AirQualityUCI.xlsx
  3. Pastikan kedua file berada dalam folder yang sama.
  4. Jalankan seluruh cell atau jalankan file Python tersebut.
  5. Program akan memproses data kualitas udara menggunakan Sistem Fuzzy.
  6. Hasil akan ditampilkan pada output dan disimpan dalam file CSV.

6. Output Program
Output program berupa:
- Skor kualitas udara untuk setiap data
- File hasil bernama:
  "Top5_Kualitas_Udara_Fuzzy.csv"

7. Catatan Penting
- Program dibangun sesuai dengan ketentuan Tugas Besar Kecerdasan Buatan.
- Tidak diperkenankan menggunakan library fuzzy apa pun.
- Variabel NOx(GT) dan C6H6(GT) digunakan sebagai indikator polusi udara
  sesuai dengan ketersediaan atribut pada dataset AirQualityUCI.
