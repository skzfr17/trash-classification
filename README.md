# ♻️ Klasifikasi Sampah Menggunakan CNN dan DenseNet121

## 📌 Deskripsi Proyek

Proyek **Klasifikasi Sampah** ini bertujuan untuk mengklasifikasikan jenis sampah berdasarkan citra (gambar) menggunakan pendekatan **Deep Learning**. Pada proyek ini dilakukan **perbandingan performa dua model**, yaitu **Convolutional Neural Network (CNN)** dan **DenseNet121**, untuk melihat model mana yang memberikan hasil klasifikasi terbaik.

Proyek ini dikembangkan sebagai bagian dari **portofolio** dan mencerminkan penerapan alur kerja lengkap dalam pengolahan data citra dan pemodelan deep learning.

---

## 🎯 Tujuan

* Mengklasifikasikan jenis sampah berdasarkan gambar
* Membandingkan performa model CNN dan DenseNet121
* Menerapkan pipeline deep learning dari awal hingga akhir
* Menguji model menggunakan **data asli (real-world images)**

---

## 🧾 Dataset

Dataset dikumpulkan dari beberapa sumber:

* **Google Images** (pengumpulan manual)
* **Kaggle** (dataset publik)

### Kelas Sampah

Dataset terdiri dari beberapa kelas berikut:

* Kaca
* Kardus
* Kertas
* Metal
* Minyak
* Organik
* Pakaian
* Plastik

---

## 🛠️ Metodologi

Pipeline yang digunakan dalam proyek ini meliputi:

1️⃣ **Load Data**
Memuat dataset citra dari berbagai sumber dan mengelompokkannya berdasarkan kelas.

2️⃣ **Preprocessing**

* Resize gambar
* Normalisasi pixel
* Data augmentation

3️⃣ **Data Splitting**

* Data training
* Data validation
* Data testing

4️⃣ **Modeling**

* Model 1: Convolutional Neural Network (CNN)
* Model 2: DenseNet121 (pre-trained model)

5️⃣ **Training**

* Pelatihan model dengan parameter yang telah ditentukan
* Monitoring performa selama proses training

6️⃣ **Evaluation**

* Evaluasi menggunakan metrik akurasi dan loss
* Perbandingan hasil antara CNN dan DenseNet121

7️⃣ **Testing dengan Data Baru**

* Pengujian model menggunakan data citra asli (real-world images)

---

## 📊 Hasil

* Kedua model mampu melakukan klasifikasi sampah dengan baik
* DenseNet121 menunjukkan performa yang lebih stabil dibandingkan CNN standar
* Pengujian menggunakan data asli membuktikan kemampuan generalisasi model


---

## 🧪 Teknologi & Tools

* Python
* TensorFlow
* CNN
* DenseNet121
* NumPy
* Matplotlib
* PIL


---

## 📌 Catatan

* Proyek ini ditujukan untuk **pembelajaran dan portofolio**
* Dataset berasal dari berbagai sumber publik
* Model dapat dikembangkan lebih lanjut dengan:

  * Penambahan data
  * Hyperparameter tuning
  * Deployment ke aplikasi web atau mobile

---

## 👤 Author

**Bayyinahtun Dwi Sumatri**
Mahasiswa Ilmu Komputer
Minat: Deep Learning, Computer Vision, dan Data Science

---

⭐ *Proyek ini dapat digunakan sebagai referensi pembelajaran di bidang klasifikasi citra dan pengelolaan sampah berbasis AI.*
