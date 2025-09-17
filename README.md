# IMDB Movie Reviews Classification & Summarization with IBM Granite

# Overview
Project ini merupakan bagian dari Capstone Project dengan tujuan:
- Mengembangkan model klasifikasi sentimen (positive/negative) dari ulasan film IMDB.
- Menghasilkan ringkasan singkat dari ulasan panjang menggunakan IBM Granite (AI Support).
- Memberikan insight tentang pola sentimen dari ulasan film.

Proyek ini menggunakan dataset publik IMDB Reviews dan dilakukan melalui tahapan:
1. Data Understanding & Exploratory Data Analysis (EDA)
2. Data Cleaning & Preprocessing
3. Modeling (Logistic Regression + model tambahan)
4. Evaluation
5. Summarization dengan bantuan AI (IBM Granite)
6. Insight & Recommendation

---

## Dataset
- **Nama Dataset:** IMDB Dataset of 50K Movie Reviews  
- **Link Publik:** [Kaggle – IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)  
- **File Raw (Repo):** [data/raw/IMDB Dataset.csv](data/raw/IMDB%20Dataset.csv)  

Dataset ini berisi 50.000 ulasan film dengan dua kolom:
- `review` → teks ulasan film
- `sentiment` → label sentimen (positive / negative)

---

## Insight & Findings (akan dilengkapi)
- Distribusi sentimen seimbang (25k positif, 25k negatif).  
- Review rata-rata panjangnya >100 kata, cocok untuk summarization.  
- Ditemukan adanya beberapa duplikat dan HTML tags (`<br />`) pada teks review.  

---

## AI Support (IBM Granite)
Dalam project ini, **IBM Granite** digunakan untuk:
1. **Summarization**: menghasilkan ringkasan singkat dari ulasan film panjang.  
2. **Classification support**: membantu eksplorasi representasi teks untuk klasifikasi.  
3. **Insight generation**: membantu menyarikan hasil analisis agar lebih mudah dipahami.  

---

## 📂 Project Structure
capstone-imdb-granite/
├─ data/
│ ├─ raw/ # dataset asli (IMDB Dataset.csv)
│ └─ processed/ # dataset hasil cleaning
├─ notebooks/
│ ├─ 00-setup.ipynb # load data & setup awal
│ ├─ 01-eda.ipynb # exploratory data analysis
│ ├─ 02-preprocessing.ipynb
│ ├─ 03-modeling.ipynb
│ └─ 04-evaluation.ipynb
├─ src/
│ └─ utils.py # helper functions
├─ presentation/
│ └─ slides.pdf # presentasi final
├─ README.md
└─ requirements.txt

---

## 🚀 How to Run
1. Clone repo:  
   ```bash
   git clone https://github.com/<username>/capstone-imdb-granite.git
   cd capstone-imdb-granite
2. Install dependencies:
pip install -r requirements.txt
3. Jalankan notebook di Google Colab atau WatsonX.
