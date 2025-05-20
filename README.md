#  Proyek Klasifikasi Gambar: Brain Tumor MRI Multi-Class Dataset
Proyek ini bertujuan untuk membangun model deep learning berbasis Convolutional Neural Network (CNN) untuk mengklasifikasi citra MRI otak ke dalam beberapa kategori tumor, menggunakan dataset multi-kelas dari Kaggle. Klasifikasi ini mencakup jenis tumor seperti meningioma, glioma, pituitary, dan kondisi non-tumor (normal).

## Dataset
Dataset yang digunakan merupakan kumpulan gambar MRI otak berlabel yang bersumber dari:
📁 https://www.kaggle.com/datasets/maxwellbernard/brain-tumor-mri-multi-class-dataset

Dataset terdiri dari 4 kelas utama:
- Glioma Tumor
- Healthy
- Meningioma Tumor
- Pituitary Tumor

## Alur Proyek
- Preprocessing gambar (resizing, augmentasi, normalisasi)
- Split dataset menjadi training, validation, dan test
- Membangun model CNN menggunakan TensorFlow/Keras
- Pelatihan model dengan EarlyStopping dan model checkpoint
- Evaluasi menggunakan confusion matrix dan classification report
- Ekspor model ke format TensorFlow SavedModel, TFLite, dan TensorFlow.js

## Hasil & Evaluasi
Model mencapai akurasi lebih dari 90% pada data uji. Disediakan pula visualisasi training loss dan accuracy, serta confusion matrix untuk memahami performa klasifikasi.

## Teknologi yang Digunakan
- Python 3.x
- TensorFlow / Keras
- NumPy, OpenCV, Matplotlib, scikit-learn
- Google Colab (untuk eksperimen dan pelatihan)

## Output Model
- model/saved_model/ (SavedModel format)
- model/brain_tumor.tflite
- model/tfjs_model/ (TensorFlow.js)

## Struktur Folder
submission
├───tfjs_model
| ├───group1-shard1of1.bin
| └───model.json
├───tflite
| ├───model.tflite
| └───label.txt
├───saved_model
| ├───saved_model.pb
| └───variables
├───notebook.ipynb
├───README.md
└───requirements.txt

## Tujuan Proyek
Proyek ini ditujukan sebagai kontribusi awal terhadap deteksi dini tumor otak menggunakan teknologi pembelajaran mesin dan dapat dijadikan dasar untuk integrasi ke sistem berbasis web atau mobile untuk deteksi tumor berbasis citra medis.
