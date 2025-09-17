# Capstone Project: IMDB Movie Reviews Sentiment Analysis with IBM Granite

## Project Overview
Proyek ini bertujuan untuk menganalisis sentimen ulasan film dari dataset IMDB (50.000 review).  
Tahapan utama:
- Data preparation (cleaning, label encoding, TF-IDF vectorization)
- Modeling dengan Logistic Regression (baseline) & Random Forest (pembanding)
- Evaluasi dengan Accuracy, Precision, Recall, F1, dan ROC-AUC
- Dukungan AI menggunakan **IBM Granite via Replicate** untuk summarization review

## Raw Dataset Link
[IMDB Dataset of 50K Movie Reviews – Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Insight & Findings
- Dataset seimbang: 25.000 review positif & 25.000 negatif  
- Setelah cleaning → 49.582 review  
- Logistic Regression menunjukkan performa baseline yang solid  
- Random Forest dipakai sebagai pembanding  
- TF-IDF efektif merepresentasikan teks ke bentuk numerik (10.000 fitur)

## AI Support Explanation
IBM Granite via Replicate digunakan untuk **summarization** review panjang.  
Tujuannya:
- Membantu memahami inti ulasan lebih cepat  
- Mendukung eksplorasi data kualitatif  
- Memberikan nilai tambah pada analisis dengan meringkas teks panjang menjadi ringkas

### Contoh Hasil Summarization
| Original Review (potongan) | Summary |
|-----------------------------|---------|
| *"I don't know how or why this film has a meager..."* | *This film, "I am Curious: Yellow," is a multifaceted critique of societal norms.* |
| *"Terry Gilliam's and David Peoples' teamed up to..."* | *Terry Gilliam and David Peoples crafted an intriguing narrative blending time travel and human struggle.* |
