# Analisis Faktor Perilaku Penyebab Churn di Spotify

Dashboard interaktif yang menganalisis mengapa pengguna berhenti berlangganan Spotify, dibangun menggunakan Python untuk pemrosesan data dan Power BI untuk visualisasi.

---

##  dashboards

![Screenshot Dashboard Spotify](screenshot_dashboard.jpg)

---

## 🎯 Deskripsi Proyek & Tujuan

Tantangan utama bagi layanan berlangganan seperti Spotify adalah mempertahankan penggunanya. Proyek ini bertujuan untuk melakukan analisis data eksploratif (EDA) untuk mengidentifikasi faktor-faktor perilaku utama yang berkorelasi dengan *customer churn* (pengguna berhenti berlangganan). Tujuannya adalah untuk memberikan wawasan berbasis data yang dapat digunakan untuk merancang strategi retensi pelanggan yang lebih efektif.

---

## 🛠️ Alur Kerja (Workflow)

1.  **Pembersihan & Transformasi Data (Python):** Data mentah dari `spotify_churn_dataset.csv` dibersihkan dan diproses menggunakan *library* Pandas di Python. Proses ini mencakup penghapusan data yang tidak relevan, mengubah nama kolom agar lebih mudah dibaca, dan membuat kategori baru (seperti "Gratis vs. Berbayar").
2.  **Visualisasi & Dashboard (Power BI):** Data yang sudah bersih kemudian diekspor ke file CSV baru dan diimpor ke Power BI. Sebuah *dashboard* interaktif dibangun untuk memvisualisasikan temuan utama dengan *slicer* untuk eksplorasi data secara dinamis.

---

## 💡 Temuan Utama (Key Insights)

* **Tingkat Churn:** Sekitar **25.9%** dari pengguna dalam dataset ini berhenti berlangganan.
* **Pengguna Gratis Paling Rentan:** Pengguna dengan tipe langganan "Gratis" menunjukkan tingkat *churn* yang secara proporsional jauh lebih tinggi dibandingkan pengguna berbayar.
* **Perilaku adalah Kunci:** Pengguna yang *churn* cenderung memiliki **waktu mendengarkan (`listening_time`) yang lebih rendah** dan **tingkat melewati lagu (`skip_rate`) yang lebih tinggi**, yang mengindikasikan tingkat keterlibatan dan kepuasan yang lebih rendah.

---

## 🔧 Tools yang Digunakan

* **Python:** Untuk pembersihan dan transformasi data.
    * *Library:* Pandas, Matplotlib, Seaborn, Scikit-learn
* **Power BI:** Untuk membuat *dashboard* interaktif.
    * *Bahasa:* DAX (untuk membuat *measure* seperti Tingkat Churn)

---

## 🚀 Cara Menjalankan

1.  **Lihat Dashboard:** *Screenshot* utama dari *dashboard* dapat dilihat di atas.
2.  **Eksplorasi File Power BI:** Unduh file `Dashboard Spotify.pbix` dan buka menggunakan Power BI Desktop untuk berinteraksi dengan *dashboard* secara penuh.
3.  **Jalankan Kode Python:** Buka file `analisis_spotify.ipynb` menggunakan Jupyter Notebook untuk melihat proses pembersihan dan analisis data.
