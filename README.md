# Analisis Kesehatan Mental Mahasiswa

Proyek ini mengeksplorasi data kesehatan mental mahasiswa, dengan fokus pada depresi, kecemasan, stres, dan pemikiran bunuh diri. Analisis mencakup faktor demografis dan menggunakan model pembelajaran mesin untuk memprediksi kondisi kesehatan mental.

---

## Daftar Isi

- [Latar Belakang](#latar-belakang)
- [Tujuan Proyek](#tujuan-proyek)
- [Dependensi](#dependensi)
- [Analisis Data](#analisis-data)
- [Pra-pemrosesan Data](#pra-pemrosesan-data)
- [Pemodelan dan Hasil](#pemodelan-dan-hasil)
- [Kesimpulan](#kesimpulan)
- [Ucapan Terima Kasih](#ucapan-terima-kasih)

---

## Latar Belakang

Kesehatan mental adalah aspek penting dari kesejahteraan mahasiswa, yang memengaruhi kinerja akademik dan kualitas hidup secara keseluruhan. Proyek ini menyelidiki tren kesehatan mental di kalangan mahasiswa dan bertujuan untuk memberikan wawasan yang dapat ditindaklanjuti untuk meningkatkan intervensi.

---

## Tujuan Proyek

1. **Mengidentifikasi Pola:** Menganalisis distribusi depresi, kecemasan, dan stres berdasarkan faktor demografis seperti gender, usia, tahun akademik, dan IPK.
2. **Memprediksi Masalah Kesehatan Mental:** Mengembangkan model pembelajaran mesin untuk memprediksi kondisi kesehatan mental secara efektif.
3. **Mendukung Intervensi:** Memberikan wawasan untuk mendukung kebijakan dan program bantuan bagi mahasiswa.

---

## Dependensi

Proyek ini membutuhkan pustaka Python berikut:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `xgboost`
- `imblearn`

Untuk menginstal dependensi, jalankan:
```bash
pip install -r requirements.txt
```

---

## Analisis Data

### Temuan Utama

1. **Distribusi Gender:** Mahasiswa laki-laki melaporkan tingkat depresi, kecemasan, dan stres yang lebih tinggi.
2. **Usia dan IPK:** Mahasiswa berusia 20 tahun atau dengan IPK di atas 3.6 menunjukkan kemampuan manajemen stres yang lebih baik.
3. **Jurusan dan Semester:** Mahasiswa tahun pertama dan jurusan Teknik Informatika memiliki risiko kesehatan mental yang lebih tinggi.

### Visualisasi

- Demografi gender, jurusan, dan tahun akademik.
- Metode kesehatan mental berdasarkan gender, usia, IPK, dan tingkat semester.
- Heatmap korelasi untuk mengidentifikasi faktor kunci yang memengaruhi metrik kesehatan mental.

---

## Pra-pemrosesan Data

1. **Pembersihan Data:** Menghapus duplikasi dan kolom yang tidak relevan.
2. **Encoding:** Mengonversi data kategori menjadi nilai numerik.
3. **Penyeimbangan:** Mengatasi ketidakseimbangan kelas menggunakan teknik oversampling.

---

## Pemodelan dan Hasil

### Model yang Digunakan

- **Support Vector Classifier (SVC):** Terbaik untuk memprediksi depresi dan stres.
- **Gradient Boosting Classifier:** Terbaik untuk memprediksi kecemasan dengan akurasi 93.67%.

### Metode Evaluasi

- Akurasi
- Presisi
- Recall
- F1-score

---

## Kesimpulan

Proyek ini memberikan wawasan penting tentang kesehatan mental mahasiswa:

- Mahasiswa laki-laki dan tahun pertama lebih rentan terhadap masalah kesehatan mental.
- Faktor akademik dan pribadi, seperti IPK dan usia, memengaruhi tingkat stres secara signifikan.
- Model pembelajaran mesin seperti SVC dan Gradient Boosting Classifier efektif dalam memprediksi kondisi kesehatan mental.

---

## Ucapan Terima Kasih

Proyek ini dikembangkan untuk tujuan pendidikan guna meningkatkan pemahaman tentang tren kesehatan mental mahasiswa dan pemodelan prediktif.

