# Klasifikasi Tingkat Kemiskinan di Indonesia

Proyek ini bertujuan untuk mengklasifikasikan tingkat kemiskinan di Indonesia berdasarkan berbagai indikator sosial-ekonomi menggunakan algoritma **Random Forest**. Dataset yang digunakan mencakup data dari seluruh wilayah Indonesia, dengan target klasifikasi berupa dua kategori: **Kelas 0 (Tidak Miskin)** dan **Kelas 1 (Miskin)**.

## **Fitur Utama**
- **Pra-pemrosesan Data**: Membersihkan data, menghapus kolom yang tidak relevan, dan menangani data yang tidak seimbang.
- **Model Klasifikasi**: Menggunakan algoritma Random Forest untuk membangun model klasifikasi dengan akurasi hingga 98%.
- **Evaluasi Model**: Mencakup metrik seperti precision, recall, F1-score, serta visualisasi confusion matrix.
- **Visualisasi Pentingnya Fitur**: Menampilkan tingkat kontribusi setiap fitur dalam menentukan klasifikasi.

## **Struktur Proyek**
- `data/`: Berisi dataset yang digunakan untuk analisis.
- `notebooks/`: Notebook Jupyter untuk eksplorasi data, pemrosesan, dan pelatihan model.
- `results/`: Hasil evaluasi dan visualisasi, seperti confusion matrix dan plot pentingnya fitur.
- `scripts/`: Skrip Python untuk pemrosesan data dan pelatihan model.

## **Teknologi yang Digunakan**
- **Python Libraries**:
  - `scikit-learn`: Untuk algoritma Random Forest dan evaluasi model.
  - `pandas` & `numpy`: Untuk manipulasi dan analisis data.
  - `matplotlib` & `seaborn`: Untuk visualisasi data.
- **Visual Studio Code**: Untuk eksperimen dan dokumentasi proses.

## **Cara Menjalankan Proyek**
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/klasifikasi-kemiskinan.git
   ```
2. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook atau skrip Python yang sesuai untuk melatih atau mengevaluasi model.

## **Hasil**
- Akurasi model: **99.03%**.
- Model dapat memprediksi tingkat kemiskinan dengan baik, bahkan pada data yang tidak seimbang.
- Visualisasi pentingnya fitur menunjukkan bahwa indikator seperti **rata-rata lama sekolah** dan **pengeluaran per kapita** memiliki kontribusi besar dalam klasifikasi.

## **DATASET**
Data set yang digunakan: https://www.kaggle.com/datasets/ermila/klasifikasi-tingkat-kemiskinan-di-indonesia


