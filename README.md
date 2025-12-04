# Sentiment Analysis Pengguna Platform Twitter Terhadap Program Makan Siang Gratis Pemerintah Indonesia Menggunakan Deep Learning LSTM dan CNN

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-LSTM%20%26%20CNN-green.svg)](https://github.com/)

## 📋 Deskripsi Proyek

Proyek Tugas Akhir ini bertujuan untuk menganalisis sentimen pengguna platform Twitter terhadap Program Makan Siang Gratis yang dicanangkan oleh Pemerintah Indonesia. Analisis dilakukan menggunakan pendekatan Deep Learning dengan menggabungkan arsitektur Long Short-Term Memory (LSTM) dan Convolutional Neural Network (CNN) untuk mendapatkan hasil klasifikasi sentimen yang akurat.

## 👥 Tim Pengembang

| NIM | Nama | Peran |
|-----|------|-------|
| 11422010 | David Kristian Silalahi | Developer |
| 11422034 | Kevin Hutajulu | Developer |
| 11422047 | Deby Cynthia Manalu | Developer |

## 👨‍🏫 Dosen Pembimbing

**Yohanssen Pratama, S.Si, M.T**

## 🎯 Tujuan Penelitian

1. Mengumpulkan dan menganalisis data tweet mengenai Program Makan Siang Gratis
2. Membangun model Deep Learning menggunakan kombinasi LSTM dan CNN
3. Mengklasifikasikan sentimen masyarakat (positif, negatif, atau netral)
4. Memberikan insight mengenai persepsi publik terhadap program pemerintah
5. Membandingkan performa model LSTM dan CNN dalam analisis sentimen

## 🔧 Teknologi yang Digunakan

- **Bahasa Pemrograman**: Python 3.8+
- **Deep Learning Framework**: TensorFlow/Keras
- **Natural Language Processing**: NLTK, Sastrawi
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Twitter API**: Tweepy
- **Development Environment**: Jupyter Notebook

## 📊 Metodologi

### 1. Pengumpulan Data
- Scraping data Twitter menggunakan API
- Filter berdasarkan keyword "Makan Siang Gratis"
- Periode pengumpulan data yang relevan

### 2. Preprocessing Data
- Text cleaning (removal stopwords, punctuation, dll)
- Tokenization
- Stemming/Lemmatization menggunakan Sastrawi
- Normalisasi teks bahasa Indonesia

### 3. Model Development
- **LSTM Model**: Untuk menangkap dependensi sekuensial dalam teks
- **CNN Model**: Untuk ekstraksi fitur lokal dari teks
- **Hybrid LSTM-CNN**: Kombinasi kedua arsitektur untuk performa optimal

### 4. Evaluasi Model
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 📁 Struktur Proyek

```
TA-03---2022---D4TRPL/
│
├── data/                   # Dataset dan data mentah
├── notebooks/              # Jupyter notebooks untuk eksplorasi
├── src/                    # Source code
│   ├── preprocessing/      # Script preprocessing
│   ├── models/            # Model LSTM dan CNN
│   └── utils/             # Utility functions
├── results/               # Hasil eksperimen dan visualisasi
├── docs/                  # Dokumentasi proyek
└── README.md             # File ini
```

## 🚀 Cara Menggunakan

### Instalasi Dependencies

```bash
# Clone repository
git clone https://github.com/DavidKristianSilalahi/TA-03---2022---D4TRPL.git
cd TA-03---2022---D4TRPL

# Install dependencies
pip install -r requirements.txt
```

### Menjalankan Proyek

```bash
# Preprocessing data
python src/preprocessing/preprocess.py

# Training model
python src/models/train_lstm.py
python src/models/train_cnn.py

# Evaluasi model
python src/models/evaluate.py
```

## 📈 Hasil Penelitian

Hasil penelitian akan diperbarui setelah eksperimen selesai dilakukan.

## 📚 Referensi

1. Hochreiter, S., & Schmidhuber, J. (1997). Long short-term memory. Neural computation, 9(8), 1735-1780.
2. Kim, Y. (2014). Convolutional neural networks for sentence classification. arXiv preprint arXiv:1408.5882.
3. Zhang, L., Wang, S., & Liu, B. (2018). Deep learning for sentiment analysis: A survey. Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery, 8(4), e1253.

## 📝 Lisensi

Proyek ini dibuat untuk keperluan akademik Tugas Akhir di Program Studi D4 Teknologi Rekayasa Perangkat Lunak.

## 📞 Kontak

Untuk pertanyaan atau kolaborasi, silakan hubungi:
- David Kristian Silalahi - [GitHub](https://github.com/DavidKristianSilalahi)

---

**Institut Teknologi Del**  
**Program Studi D4 Teknologi Rekayasa Perangkat Lunak**  
**Tahun 2022**