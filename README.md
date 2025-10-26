# Spam Detection - Text Classification Project

## Informasi Project
- **Nomor Kelompok:** 10
- **Tipe Klasifikasi:** Spam Detection
- **Dataset:** SMS Spam Collection (Kaggle)
- **Total Data:** 5,574 SMS messages
- **Metode:** Deep Learning (Bi-LSTM + CNN 1D)

## Struktur Folder
        Kelompok_10_SD/
        
        ├── Kelompok_10_SD.ipynb # Main notebook
                
        ├── README.md # Documentation
                
        ├── requirements.txt # Dependencies
                
        └── spam.csv # Dataset (optional - bisa via gitignore)


## Anggota Kelompok
- [Aditia Fahreza] (NIM: 12345678)
- [Aldy Abdul Aziz] (NIM: 12345679)
- [Muhamad Rifqi Salim] (NIM: 10222089)

## Deskripsi Project
Proyek ini mengimplementasikan sistem deteksi spam SMS menggunakan Deep Learning. 
Kami membandingkan dua arsitektur neural network:
1. **Bidirectional LSTM (Bi-LSTM)** - Menangkap konteks dua arah
2. **CNN 1D** - Mendeteksi pola lokal dalam teks

## Hasil Model
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Bi-LSTM | 98.67% | 96.84% | 92.00% | 94.34% |
| CNN 1D | 97.94% | 91.92% | 93.00% | 92.45% |

**Best Model:** Bi-LSTM dengan akurasi 98.67%

## Tahapan Pengerjaan
1. **Data Understanding** - Analisis dataset SMS spam
2. **Data Preprocessing** - Tokenisasi, lemmatisasi, stopword removal
3. **Data Vektorisasi** - TF-IDF untuk vektorisasi teks
4. **Modeling** - Training Bi-LSTM dan CNN 1D
5. **Evaluation** - Confusion matrix dan classification report
6. **Comparison** - Perbandingan performa kedua model

## Cara Menjalankan
Install dependencies
pip install -r requirements.txt

Jalankan notebook
jupyter notebook Kelompok_10_SD.ipynb

text

## Libraries yang Digunakan
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- nltk
- tensorflow, keras

## References
- [UCI Machine Learning - SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- [Keras Documentation](https://keras.io/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
