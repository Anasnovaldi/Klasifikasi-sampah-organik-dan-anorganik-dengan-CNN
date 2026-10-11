# Klasifikasi-sampah-organik-dan-anorganik-dengan-CNN

Project ini mengklasifikasikan gambar sampah ke dalam dua kategori, Organik dan Anorganik, menggunakan Convolutional Neural Network dengan pendekatan transfer learning (MobileNet). Alur kerjanya meliputi pengambilan dataset dari Kaggle, penggabungan subkategori menjadi dua kelas utama, pembagian data latih dan uji, augmentasi serta normalisasi gambar lewat ImageDataGenerator, pelatihan model, evaluasi menggunakan confusion matrix dan classification report, hingga pengujian model dengan gambar baru yang diunggah sendiri.
 
## Dataset
 
Dataset diambil dari Kaggle: [`arthurwaruwu/DatasetCapstoneFixx`](https://www.kaggle.com/datasets/arthurwaruwu/datasetcapstonefixx), berisi gambar sampah yang terbagi dalam folder `Anorganik` (10 subkategori) dan `Organik` (7 subkategori).
 
## Cara Menjalankan
 
Project ini dirancang untuk dijalankan di **Google Colab**.
 
1. Buka notebook `Klasifikasi_Organik_Anorganik.ipynb` di Google Colab.
2. Siapkan API token Kaggle (`kaggle.json`) melalui **Kaggle → Settings → API Tokens → Generate**.
3. Jalankan cell secara berurutan dari atas ke bawah. Pada cell upload, pilih file `kaggle.json` saat diminta.
4. Dataset akan otomatis terunduh dan terekstrak ke folder kerja.
5. Lanjutkan menjalankan seluruh cell hingga tahap training, evaluasi, dan pengujian model dengan gambar sendiri.

## Rekomendasi
Gunakan Jupyter Notebook atau Google Colab untuk menjalankan program.
[Pelajari di sini](https://colab.research.google.com/notebooks/intro.ipynb?hl=id)

## Requirements

Lihat `requirements.txt`. Sebagian besar library (TensorFlow, Keras, scikit-learn, dll.) sudah tersedia secara default di Google Colab. 