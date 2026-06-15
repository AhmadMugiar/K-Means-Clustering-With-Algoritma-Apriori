# K-Means Clustering with Apriori Algorithm

## 📌 Overview

Project ini mengimplementasikan kombinasi algoritma **K-Means Clustering** dan **Apriori Association Rule Mining** untuk melakukan segmentasi data serta menemukan pola hubungan antar item yang sering muncul bersama.

Kombinasi kedua metode ini memungkinkan analisis yang lebih mendalam terhadap data, dimana:

- K-Means digunakan untuk mengelompokkan data berdasarkan karakteristik yang mirip.
- Apriori digunakan untuk menemukan pola asosiasi dan hubungan antar item dalam setiap cluster yang terbentuk.

Pendekatan ini banyak digunakan pada analisis pelanggan, market basket analysis, segmentasi produk, dan pengambilan keputusan berbasis data. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objectives

- Melakukan clustering data menggunakan algoritma K-Means.
- Menentukan kelompok data yang memiliki karakteristik serupa.
- Menemukan association rules menggunakan algoritma Apriori.
- Menghasilkan insight yang dapat digunakan sebagai dasar pengambilan keputusan.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Mlxtend
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Repository Structure

```text
.
├── PROJEK.ipynb          # Notebook utama analisis
├── dataset.csv           # Dataset yang digunakan
├── requirements.txt      # Library dependencies
├── README.md
└── assets/
```

> Struktur dapat berbeda tergantung versi repository.

---

## ⚙️ Installation

Clone repository:

```bash
git clone https://github.com/AhmadMugiar/K-Means-Clustering-With-Algoritma-Apriori.git

cd K-Means-Clustering-With-Algoritma-Apriori
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Methodology

### 1. Data Preprocessing

Tahapan preprocessing meliputi:

- Handling Missing Values
- Duplicate Removal
- Data Transformation
- Feature Selection
- Data Normalization

---

### 2. K-Means Clustering

K-Means merupakan algoritma unsupervised learning yang bertujuan membagi data ke dalam beberapa cluster berdasarkan kedekatan terhadap centroid cluster. Algoritma bekerja secara iteratif dengan memperbarui centroid hingga mencapai kondisi konvergen. :contentReference[oaicite:1]{index=1}

Tahapan:

1. Menentukan jumlah cluster (K)
2. Inisialisasi centroid
3. Menghitung jarak data ke centroid
4. Mengelompokkan data
5. Memperbarui centroid
6. Mengulangi hingga konvergen

---

### 3. Cluster Evaluation

Penentuan jumlah cluster dapat menggunakan:

- Elbow Method
- Silhouette Score

Tujuannya adalah mendapatkan cluster yang optimal sehingga data dalam cluster memiliki kemiripan tinggi dan antar cluster memiliki perbedaan yang jelas. :contentReference[oaicite:2]{index=2}

---

### 4. Apriori Algorithm

Setelah cluster terbentuk, algoritma Apriori digunakan untuk menemukan frequent itemsets dan association rules.

Parameter utama:

- Minimum Support
- Minimum Confidence
- Lift Ratio

Output yang dihasilkan berupa aturan asosiasi seperti:

```text
Jika Item A dibeli,
maka kemungkinan Item B juga dibeli.
```

Apriori banyak digunakan pada market basket analysis untuk memahami pola pembelian pelanggan. :contentReference[oaicite:3]{index=3}

---

## 📊 Workflow

```text
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Normalization
    │
    ▼
K-Means Clustering
    │
    ▼
Cluster Formation
    │
    ▼
Apriori Algorithm
    │
    ▼
Association Rules
    │
    ▼
Business Insights
```

---

## 📈 Expected Output

Project menghasilkan:

- Hasil clustering data
- Visualisasi cluster
- Nilai centroid setiap cluster
- Frequent itemsets
- Association rules
- Insight untuk pengambilan keputusan

---

## 📚 Applications

Implementasi metode ini dapat digunakan pada:

- Customer Segmentation
- Market Basket Analysis
- Product Recommendation
- Sales Analysis
- Retail Analytics
- Customer Retention Strategy

---

## ▶️ Running the Notebook

Jalankan Jupyter Notebook:

```bash
jupyter notebook
```

Kemudian buka:

```text
PROJEK.ipynb
```

dan jalankan seluruh cell secara berurutan.

---

## 📌 Key Algorithms

### K-Means Clustering

K-Means merupakan algoritma clustering yang membagi data ke dalam K kelompok berdasarkan jarak terhadap centroid. Algoritma ini merupakan salah satu metode clustering paling populer dalam unsupervised learning. :contentReference[oaicite:4]{index=4}

### Apriori

Apriori merupakan algoritma association rule mining yang digunakan untuk menemukan pola keterkaitan antar item berdasarkan nilai support dan confidence. :contentReference[oaicite:5]{index=5}

---

## 👨‍💻 Author

**Ahmad Mugiar Sujana**

GitHub:
https://github.com/AhmadMugiar

Repository:
https://github.com/AhmadMugiar/K-Means-Clustering-With-Algoritma-Apriori

---

## 📄 License

This project is provided for educational and research purposes.
