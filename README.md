# 🧠 Breast Cancer Classification using Machine Learning

## 📌 Overview

Project ini bertujuan untuk melakukan klasifikasi kanker payudara (malignant vs benign) menggunakan pendekatan machine learning. Dataset yang digunakan adalah Breast Cancer Dataset yang terdiri dari 30 fitur independen dan 1 variabel target.

Proses analisis meliputi eksplorasi data (EDA), visualisasi, serta penerapan beberapa algoritma klasifikasi seperti Decision Tree, Random Forest, dan Self-Training. Selain itu, dilakukan optimasi model menggunakan teknik pruning serta analisis terhadap multikolinearitas fitur.

Hasil menunjukkan bahwa model Random Forest memberikan performa terbaik dengan akurasi mencapai 97%, sehingga lebih unggul dalam menangani kompleksitas data dibandingkan model lainnya.

---

## 📊 Dataset

* Sumber: Breast Cancer Dataset (scikit-learn)
* Jumlah fitur: 30
* Target:

  * 0 = malignant (ganas)
  * 1 = benign (jinak)

---

## ⚙️ Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🔍 Methodology

### 1. Exploratory Data Analysis (EDA)

* Analisis distribusi data target
* Visualisasi jumlah kasus malignant vs benign
* Identifikasi pola awal pada dataset

### 2. Decision Tree

* Implementasi model klasifikasi
* Evaluasi performa awal (~95% akurasi)
* Optimasi menggunakan cost-complexity pruning

### 3. Random Forest

* Ensemble learning untuk meningkatkan akurasi
* Mengurangi overfitting
* Analisis feature importance
* Handling multikolinearitas

### 4. Self-Training

* Pendekatan semi-supervised learning
* Eksperimen dengan berbagai threshold
* Evaluasi performa berdasarkan confidence model

---

## 📈 Results

| Model         | Accuracy |
| ------------- | -------- |
| Decision Tree | ~95%     |
| Random Forest | **97%**  |
| Self-Training | Varies   |

---

## 💡 Key Insights

* Random Forest memberikan performa terbaik karena mampu mengurangi overfitting dan menangani multikolinearitas.
* Decision Tree cenderung overfitting tanpa pruning.
* Self-Training sangat bergantung pada threshold, sehingga performanya tidak stabil.

---

## 🚀 Conclusion

Pendekatan machine learning terbukti efektif dalam melakukan klasifikasi kanker payudara. Model Random Forest menjadi pilihan terbaik dalam studi ini dengan akurasi tinggi dan stabilitas yang baik.

Project ini menunjukkan bagaimana data science dapat digunakan untuk membantu pengambilan keputusan dalam bidang kesehatan, khususnya dalam proses diagnosis awal.

---

## 📁 Project Structure

* `notebook.ipynb` → proses analisis & modeling
* `UTSKLBD.pdf` → laporan lengkap
* `README.md` → dokumentasi project

---

## 👤 Author

Sayyid Abdullah
Master of Mathematics – Data Science
