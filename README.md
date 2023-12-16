# Forecasting-Produksi-Pertanian-Komoditas-Bahan-Pangan-di-Pulau-Sumatera
## Overview 
Projek ini merupakan kolaborasi berkelompok untuk memenuhi kebutuhan Seminar Nasional SENOVTIK 2023 yang diadakan oleh IndoCEISS. Penelitian ini bertujuan untuk memprediksi produksi beras di Pulau Sumatera dengan menggunakan model Long Short-Term Memory (LSTM). Berikut adalah anggota kelompok beserta nama dan NIM mereka:

- Cahyo Prakoso (5200411379)
- Ach. Nur Aqil Wahid (5200411387)
- Fahri Putra Herlambang (5200411389)
- Muhammad Aulia (5200411482)
- Muhammad Rousydi Hunafa (5200411483)
- Ilham Rafiedhia Pramutighna (5200411490)

Projek ini diinisiasi sebagai tanggapan terhadap tantangan perubahan iklim dan perubahan pola konsumsi yang mempengaruhi sistem produksi pangan di Sumatera. Dengan menggunakan pendekatan berbasis model LSTM, kami berharap dapat memberikan kontribusi dalam menjaga ketahanan pangan di pulau ini.

## Background
Tingkat ketersediaan pangan di Pulau Sumatra memiliki dampak signifikan terhadap kesejahteraan dan keamanan pangan di Indonesia. Meskipun pulau ini memiliki lebih dari 50 persen lahan pertanian yang menyediakan komoditas pangan utama seperti padi, jagung, kacang tanah, dan ubi, tantangan seperti fluktuasi iklim dan perubahan pola konsumsi memberikan tekanan pada sistem produksi pangan.

## Dataset
Dataset ini dirancang untuk memprediksi hasil produksi bahan pangan di Pulau Sumatera menggunakan metode regresi, dengan fokus pada komoditas padi. Menggabungkan data pertanian dari website BPS dan data cuaca dari BMKG, dataset mencakup hasil produksi tahunan, luas panen, serta variabel cuaca seperti curah hujan, kelembapan, dan suhu rata-rata harian. Dengan periode pengumpulan data dari tahun 1993 hingga 2020, dataset ini memberikan gambaran yang komprehensif untuk memahami dan meramalkan dampak perubahan cuaca terhadap produksi bahan pangan di Sumatera. Digunakan untuk membangun model prediktif dengan metode decision tree dan Artificial Neural Network (ANN), dataset ini diharapkan dapat memberikan wawasan yang berharga dalam mendukung keberlanjutan dan ketahanan pangan di pulau ini. Dataset dapat diakses melalui [tautan Kaggle berikut](https://www.kaggle.com/datasets/ardikasatria/datasettanamanpadisumatera).

## Penggunaan
1. Install beberapa library dengan menjalankan perintah berikut:

   ```shell
   pip install pandas
   pip install numpy
   pip install matplotlib
   pip install seaborn
   pip install scikit-learn
   pip install keras
   pip install tensorflow
   pip install tqdm
