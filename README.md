# UAS Analisis Data – Prediksi Putus Sekolah di Indonesia

## Informasi Proyek
- **Nama**: Anggia Dhini Hanifa  
- **NIM**: 2401489  
- **Mata Kuliah**: Analisis Data  
- **Jenis Tugas**: Ujian Akhir Semester (UAS)  
- **Topik**: Analisis dan Prediksi Putus Sekolah  
- **Pendekatan**: Data Analysis & Machine Learning  

---

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi tingkat **putus sekolah di Indonesia** serta membangun **model prediktif** menggunakan pendekatan *machine learning*.  
Analisis dilakukan berdasarkan data pendidikan per provinsi untuk memahami pola, distribusi, dan variabel yang berkontribusi terhadap fenomena putus sekolah.

Model yang digunakan bersifat **prediktif**, sehingga hasil analisis tidak dimaksudkan untuk menyimpulkan hubungan sebab-akibat, melainkan sebagai dukungan **pengambilan keputusan berbasis data**.

---

## Dataset
Dataset yang digunakan merupakan data pendidikan tingkat provinsi di Indonesia yang mencakup beberapa indikator, antara lain:
- Jumlah siswa  
- Jumlah sekolah  
- Kondisi sarana dan prasarana  
- Variabel pendidikan lain yang relevan  

Tahapan pengolahan data meliputi:
- Data cleaning  
- Exploratory Data Analysis (EDA)  
- Feature selection  

---

## Metodologi Analisis

### 1. Eksplorasi Data
- Analisis distribusi tingkat putus sekolah  
- Visualisasi per provinsi  
- Identifikasi outlier dan pola data  

### 2. Pemodelan
- **Baseline Model**: Ridge Regression  
- **Model Utama**: Random Forest Regressor  
- Pembagian data menjadi data latih dan data uji  

### 3. Evaluasi Model
Kinerja model dievaluasi menggunakan:
- **MAE (Mean Absolute Error)**  
- **RMSE (Root Mean Squared Error)**  
- **R² (Coefficient of Determination)**  
- **5-Fold Cross Validation** untuk menguji kestabilan dan kemampuan generalisasi model  

### 4. Interpretasi Model
- Analisis error prediksi  
- Visualisasi residual  
- Analisis feature importance  

---
