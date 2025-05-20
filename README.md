# Brain Tumor MRI Multi-Class Classification

Proyek ini merupakan implementasi model klasifikasi gambar berbasis deep learning menggunakan dataset [Brain Tumor MRI Multi-Class Dataset](https://www.kaggle.com/datasets/maxwellbernard/brain-tumor-mri-multi-class-dataset). Model dibangun untuk mengenali berbagai jenis tumor otak dari citra MRI.

## Kontributor

- **Nama**: Alvina Aulia Nisa  
- **Email**: alvinaaulians@gmail.com  
- **ID Dicoding**: alvinaaulianisa

## Deskripsi Dataset

Dataset terdiri dari citra MRI otak yang terbagi dalam beberapa kelas tumor:

- Glioma
- Meningioma
- Pituitary
- No Tumor

Struktur folder dataset digunakan untuk pelatihan model klasifikasi multi-kelas.

## Teknologi dan Library

Notebook ini menggunakan library berikut:

- TensorFlow / Keras
- NumPy, Matplotlib
- Scikit-learn
- ImageDataGenerator untuk augmentasi data
- Callback Keras seperti `EarlyStopping`, `ModelCheckpoint`, dan `ReduceLROnPlateau`

## Tahapan Proyek

1. **Import Library**
2. **Persiapan Data** (pemisahan dataset train/val/test)
3. **Augmentasi Gambar**
4. **Arsitektur CNN** menggunakan Keras Sequential API
5. **Training Model**
6. **Evaluasi Model** dengan confusion matrix dan classification report
7. **Visualisasi Hasil**

## Hasil Evaluasi

Model dilatih dan dievaluasi menggunakan metrik seperti akurasi, confusion matrix, dan classification report untuk menilai performa pada data uji.

## Struktur Notebook

Notebook terdiri dari 30+ cell yang mencakup dokumentasi markdown, kode Python, dan visualisasi hasil.

## Catatan

- Notebook dijalankan di Google Colab.
- Pastikan Anda mengunggah dataset ke direktori yang sesuai sebelum menjalankan cell pemrosesan data.
- Model dapat disimpan dan diekspor ke format TensorFlow SavedModel, TF Lite, atau TF.js jika dibutuhkan.

## Lisensi Dataset

Lihat detail lisensi dataset di:  
[https://www.kaggle.com/datasets/maxwellbernard/brain-tumor-mri-multi-class-dataset](https://www.kaggle.com/datasets/maxwellbernard/brain-tumor-mri-multi-class-dataset)

---

> Notebook ini dikembangkan untuk proyek klasifikasi citra tumor otak sebagai bagian dari pembelajaran dan eksplorasi model CNN dalam domain medis.