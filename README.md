# BTCUSD-Scraper
# Analisis BTC 4H — EDA (SMART) + Cleaning + Preprocessing + Modeling
**Klasifikasi • Regresi • Clustering**

> Repo ini menganalisis data **Bitcoin OHLCV interval 4 jam** untuk menyusun **EDA berbasis SMART**, melakukan **data cleaning & preprocessing**, serta membangun model **klasifikasi, regresi,** dan **clustering (regime detection)**.

---

## 1) Deskripsi Singkat
- **Tujuan utama**
  - Menjawab **3 pertanyaan EDA** berprinsip **SMART** dengan visual pendukung.
  - Membangun pipeline reproducible: **Cleaning → Preprocessing → Modeling → Evaluasi**.
  - Memberi rekomendasi peningkatan akurasi dan menangani potensi cacat data.
- **Hasil**
  - Grafik EDA (volatilitas mingguan, EMA crossover vs future return, regime PCA).
  - Metrik **Klasifikasi** (Accuracy, Precision, Recall, F1).
  - Metrik **Regresi** (MSE, RMSE, MAE, R²).
  - Metrik **Clustering** (Silhouette, Calinski–Harabasz, Davies–Bouldin) dan profil klaster.

---

## 2) Anggota
- **Anggota 1:** `Muhammad Naufal Firdaus`
- **Anggota 2:** `Athalah Rafif Irsyach Sarbrani`
- **Anggota 3:** `Maulana Hafiz`


---

## 3) Dataset
- **Format minimal kolom:** `Timestamp, Open, High, Low, Close, Volume`
- **Contoh path (Google Colab / Drive):**
pastikan dataset btc_merged.csv telah dimasukkan kedalam drive
dengan path `url = '/content/drive/MyDrive/Big Data Dataset/btc_4h_merged.csv`
