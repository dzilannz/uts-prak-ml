## Klasifikasi Menggunakan Naive Bayes

### Dataset
Dataset berisi atribut: Usia, Pendapatan, Status Mahasiswa, Rating Kredit, dan Label Buys_Computer.

### Langkah-Langkah

1. **Import library** yang dibutuhkan (pandas, sklearn).
2. **Load dataset** dari file CSV.
3. **Preprocessing**:
   - Encode kolom kategorikal ke numerik dengan `LabelEncoder`.
4. **Split dataset** menjadi data latih dan uji (70:30).
5. **Modeling** dengan algoritma Gaussian Naive Bayes.
6. **Evaluasi** menggunakan akurasi, confusion matrix, dan classification report.
7. **Prediksi data baru** untuk mengetahui kelayakan berdasarkan input contoh.

### Algoritma
Naive Bayes cocok untuk klasifikasi data diskrit seperti dataset ini. Model menghitung probabilitas masing-masing kelas dan memilih kelas dengan probabilitas tertinggi.
