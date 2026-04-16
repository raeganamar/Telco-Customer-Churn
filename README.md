# 📊 Telco Customer Churn Analysis — Day 36

---

## 🧾 Project Overview
> 📌 **Background**  
Industri telekomunikasi memiliki tingkat kompetisi yang tinggi, sehingga mempertahankan pelanggan (customer retention) menjadi sangat penting. Salah satu tantangan utama adalah **customer churn**, yaitu kondisi ketika pelanggan berhenti menggunakan layanan.

> 🎯 **Objective**  
Menganalisis faktor-faktor yang memengaruhi customer churn serta membangun model prediktif untuk mengidentifikasi pelanggan yang berpotensi churn.

> 🚀 **Goals**
- Mengidentifikasi pola dan karakteristik pelanggan yang churn  
- Menentukan faktor utama yang memengaruhi churn  
- Membangun model machine learning untuk prediksi churn  
- Memberikan insight bisnis untuk strategi retention  

---

## 📁 Dataset Information
- Source: Telco Customer Dataset  
- Jumlah data: 7043 rows, 21 columns  
- Target variable: `Churn`  

---

## ⚙️ Workflow
1. Data Understanding  
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Building & Evaluation  
6. Business Insight & Recommendation  

---

## 🧠 Models Used
- Logistic Regression  
- Decision Tree / Random Forest  
- (Tambahkan jika ada model lain)

---

## 📊 Key Insights
- Pelanggan dengan kontrak bulanan cenderung lebih tinggi churn  
- Pengguna dengan tenure rendah memiliki risiko churn lebih besar  
- Layanan tambahan tertentu memengaruhi retention  

---

## 💡 Business Recommendations
- Fokus retention pada pelanggan baru (< X bulan)  
- Tawarkan paket kontrak jangka panjang  
- Optimalkan layanan tambahan untuk meningkatkan engagement  

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)  
- Visualization (Matplotlib, Seaborn)  
- Machine Learning (Scikit-learn)  

---

## 📌 Conclusion
Model berhasil mengidentifikasi pelanggan berpotensi churn dengan performa yang cukup baik, sehingga dapat digunakan sebagai dasar strategi bisnis untuk meningkatkan customer retention.

---

## 📊 Model Performance

| Model                | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|---------------------|----------|----------|--------|----------|--------|
| Logistic Regression | 0.8045   | 0.6495   | 0.5749 | 0.6099   | 0.8359 |
| Random Forest       | 0.7839   | 0.6151   | 0.5000 | 0.5516   | 0.8158 |
| XGBoost             | 0.7669   | 0.5650   | 0.5348 | 0.5495   | 0.8019 |

---

## 🏆 Best Model
**Logistic Regression** menunjukkan performa terbaik dengan:
- ROC AUC tertinggi (0.8359)
- F1-score paling optimal dibanding model lain
- Generalization stabil (CV ROC AUC ~0.8459)

---

## 📌 Model Insight
- Model cenderung lebih baik dalam memprediksi **non-churn (class 0)** dibanding churn  
- Recall churn masih bisa ditingkatkan (important for business case)  
- ROC AUC menunjukkan model sudah cukup baik dalam membedakan churn vs non-churn


---

## ✍️ Author
**Raegan Ammar Prawira**
