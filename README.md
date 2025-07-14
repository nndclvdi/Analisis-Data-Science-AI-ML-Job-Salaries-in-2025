Analisis Gaji di Industri Data Science 2025

 Deskripsi Proyek
Proyek ini merupakan bagian dari capstone project pembelajaran Data Analytics. Tujuan utamanya adalah menganalisis dataset gaji pekerjaan di industri Data Science global dari tahun 2020 hingga 2023, serta membangun model AI sederhana untuk memprediksi gaji berdasarkan fitur seperti job title, lokasi, dan remote ratio.

Dataset
Dataset yang digunakan berasal dari Kaggle: [Salaries for Data Science Jobs](https://www.kaggle.com/datasets/adilshamim8/salaries-for-data-science-jobs)

File utama: `salaries.csv`
Tujuan Analisis
- Mengetahui distribusi gaji di berbagai posisi pekerjaan data science
- Mengetahui negara dan kondisi kerja (remote/onsite) yang berpengaruh pada gaji
- Memprediksi gaji berdasarkan fitur-fitur pekerjaan dengan dukungan model AI

Dukungan AI
Model regresi linear dibangun menggunakan `scikit-learn` di Google Colab untuk memprediksi `salary_in_usd` berdasarkan:
- `job_title`
- `experience_level`
- `company_location`
- `remote_ratio`

> Model menunjukkan akurasi terbatas karena keterbatasan data fitur (R² Score ≈ 0.15).
 Insight & Temuan

| 1. | Posisi dengan gaji tertinggi secara rata-rata adalah Manager, Software Engineer dan ML Engineer 
| 2. | Perusahaan dari US mendominasi gaji tinggi dalam industri data science 
| 3. | Pekerjaan full remote cenderung memiliki gaji lebih tinggi daripada yang onsite 
| 4. | Model prediksi sederhana dapat digunakan sebagai referensi kasar, namun tidak akurat untuk keputusan besar 

 Tools yang Digunakan
- Google Colab (Python, Pandas, Seaborn, Scikit-learn)
- Kaggle Dataset
- Matplotlib & Seaborn untuk visualisasi
- IBM Granite (optional insight support)

Link Proyek
- 🔗 Notebook Google Colab: (https://colab.research.google.com/drive/1RfZXTGbejBnpxBswxXFvFje-vPUY5z6D?usp=sharing)
- 🔗 GitHub Repo: [https://github.com/nndclvdi/Analisis-Data-Science-AI-ML-Job-Salaries-in-2025](https://github.com/nndclvdi/Analisis-Data-Science-AI-ML-Job-Salaries-in-2025)


Donanda Msuwondo – Mahasiswa Informatika UPN Jawa Timur  
Capstone Project – Data Analytics & AI (2025)
