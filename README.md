# UTS-NLP-SemanticSquad
Proyek ini dibuat untuk memenuhi tugas UTS NLP.
## Anggota Tim:
1. Yurida Yahsya - 0110224100
2. Ayu Nur Intany - 0110224133
3. Dania islamia - 0110224221
4. Nuril Anwar Al-Absory - 0110224128
   
# 📦 E-Commerce Product Category Classifier
Proyek ini merupakan sistem klasifikasi otomatis yang mampu menebak kategori produk berdasarkan ulasan (review) atau nama produk menggunakan teknik Natural Language Processing (NLP).

### 🚀 Fitur Utama:
* **Data Processing:** Pembersihan teks (Cleaning, Stopword Removal, & Stemming Sastrawi).
* **Feature Engineering:** Implementasi TF-IDF (N-Gram 1,2) dan Word Embedding (Word2Vec).
* **Modeling:** Eksperimen menggunakan Naive Bayes, Logistic Regression, dan SVM.
* **Deployment:** Aplikasi web interaktif menggunakan Gradio.

### 📊 Dataset:
Dataset terdiri dari 12.000 data produk yang diseimbangkan (balanced) mencakup 6 kategori:
1. Elektronik
2. Handphone & Tablet
3. Kesehatan
4. Makanan & Minuman
5. Olahraga
6. Pertukangan

### 🛠️ Tech Stack:
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NLTK, Sastrawi, Gensim
* **Deployment:** Gradio
* **Environment:** Google Colab

## Cara Menjalankan:
1. Buka Notebook di folder `Notebooks`.
2. Upload file di folder `Models` ke Google Colab.
3. Jalankan aplikasi Gradio.

### 📝 Hasil Evaluasi:
Model terbaik yang dipilih adalah SVM dengan fitur TF-IDF, yang memberikan keseimbangan akurasi terbaik untuk data teks bahasa Indonesia.
