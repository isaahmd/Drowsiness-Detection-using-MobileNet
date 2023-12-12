# Drowsiness-Detection-using-MobileNet

Proyek ini menggunakan bahasa pemrograman Python dan memanfaatkan modul-modul dari library TensorFlow untuk melatih model machine learning serta library OpenCV untuk mendeteksi status mata pengendara.

## Teknik Vision-Based

Proyek ini mengadopsi teknik vision-based, di mana keputusan diambil berdasarkan informasi visual. Dataset yang digunakan berasal dari "MRL Eye Dataset" yang dapat diakses melalui [http://mrl.cs.vsb.cz/eyedataset](http://mrl.cs.vsb.cz/eyedataset).

## Transfer Learning dengan MobileNet

Dikarenakan keterbatasan waktu, model Deep Learning tidak dibangun dari awal. Sebagai gantinya, proyek ini menggunakan metode transfer learning untuk mencapai akurasi yang lebih baik. Proses transfer learning dilakukan dengan memanfaatkan arsitektur convolutional neural network (CNN) MobileNet. MobileNet berperan sebagai "mata" suatu mesin, dan dengan menggunakan transfer learning, proses machine learning akan mengklasifikasikan status mata (terpejam atau terbuka) tanpa perlu membuat model dari awal.

## Langkah-langkah Proyek:

1. Pengambilan Dataset: Menggunakan dataset dari "MRL Eye Dataset".
2. Transfer Learning: Proses transfer learning dilakukan dengan menggunakan MobileNet.
3. Deteksi Status Mata: Menggunakan model hasil transfer learning untuk mendeteksi status mata pengendara (terpejam atau terbuka).

Proyek ini bertujuan untuk memberikan solusi deteksi status mata pengendara secara efisien menggunakan teknik transfer learning dengan memanfaatkan MobileNet.
