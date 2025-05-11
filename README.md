# Klasifikasi Channel Pelanggan Wholesale menggunakan Algoritma K-Nearest Neighbors (KNN)

Repositori ini berisi implementasi algoritma K-Nearest Neighbors (KNN) untuk klasifikasi pelanggan berdasarkan jenis channel (Horeca atau Retail) menggunakan data pembelian dari dataset Wholesale Customers. Proyek ini bertujuan untuk membangun model machine learning yang mampu memprediksi jenis pelanggan berdasarkan pengeluaran tahunan dalam berbagai kategori produk.

## 📊 Dataset

Dataset yang digunakan diambil dari kaggle https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set, terdiri dari 440 pelanggan grosir dengan informasi pengeluaran tahunan.

### Fitur Input:
- **Fresh**: Pengeluaran untuk produk segar
- **Milk**: Pengeluaran untuk susu
- **Grocery**: Pengeluaran untuk bahan kebutuhan pokok
- **Frozen**: Pengeluaran untuk makanan beku
- **Detergents_Paper**: Pengeluaran untuk deterjen dan kertas
- **Delicassen**: Pengeluaran untuk makanan jadi
- **Region**: Lokasi pelanggan

### Target Klasifikasi:
- **Channel**: Tipe pelanggan  
  - 1 = Horeca (Hotel/Restaurant/Café)  
  - 2 = Retail (Toko Ritel)

## 🎯 Tujuan Proyek

- Membuat model klasifikasi untuk memprediksi channel pelanggan berdasarkan pola pembelian produk.
- Mengoptimalkan nilai `k` dalam KNN untuk meningkatkan akurasi prediksi.
- Menilai performa model menggunakan metrik evaluasi seperti akurasi dan confusion matrix.

## ⚙️ Teknologi dan Library

- Python 3.x
- Jupyter Notebook
- Pandas dan NumPy untuk manipulasi data
- Scikit-learn untuk pemodelan machine learning
- Matplotlib dan Seaborn untuk visualisasi

## 🔁 Alur Implementasi

1. **Eksplorasi Data**  
   Visualisasi distribusi data dan hubungan antar fitur.

2. **Pra-pemrosesan Data**  
   - Normalisasi fitur numerik  
   - Pembagian data menjadi data latih dan uji

3. **Modeling KNN**  
   - Pemilihan nilai `k` yang optimal  
   - Pelatihan model dan prediksi data uji

4. **Evaluasi Model**  
   - Akurasi  
   - Confusion Matrix  
   - Classification Report (precision, recall, f1-score)

## ✅ Hasil 

Model KNN menunjukkan performa yang baik dalam mengklasifikasikan tipe pelanggan Horeca dan Retail berdasarkan data pembelian tahunan. Eksperimen terhadap nilai `k` memperlihatkan pengaruh langsung terhadap performa model.


