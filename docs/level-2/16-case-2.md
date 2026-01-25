# 16. KASUS 2 — Integrasi Model Fisik dan Machine Learning

## Posisi Modul
Level 2 — Hydrology with Engineering Tools, ML & AI  
Evaluasi Blok B (Modul 9–15)

**Catatan:** Laporan tugas menggunakan format IMRAD sesuai panduan Level 2.

---

## Tujuan Kasus

Mahasiswa mampu:

1. Mengintegrasikan model hidrologi/hidraulika dengan pendekatan ML.
2. Membandingkan hasil model fisik dan model data-driven.
3. Mengevaluasi sensitivitas dan ketidakpastian model.
4. Menunjukkan tanggung jawab profesional dalam interpretasi hasil.

---

## 🧩 Deskripsi Kasus

Diberikan data:

- Hidrograf debit hasil model HEC-HMS  
- Data tinggi muka air observasi di sungai  
- Data historis hujan dan debit

Mahasiswa diminta:

1. Menjalankan model hidraulika (HEC-RAS) menggunakan debit dari HMS  
2. Mengembangkan model ML sederhana untuk memprediksi debit atau tinggi muka air  
3. Membandingkan kedua pendekatan

---

## 📌 Tugas Mahasiswa

### 1. Model Fisik
- Gunakan debit dari HMS
- Jalankan simulasi HEC-RAS
- Hasilkan profil muka air

### 2. Model ML
- Gunakan data historis
- Bangun model ML (misal ANN/regresi)
- Prediksi debit atau muka air

### 3. Perbandingan Model
Bandingkan:
- kinerja statistik
- kewajaran fisik
- stabilitas hasil

### 4. Analisis Sensitivitas
Uji satu parameter penting pada model fisik atau ML.

---

## 🧭 KISI-KISI PENYELESAIAN

Langkah berpikir yang diharapkan:

1. Pahami karakteristik sistem sungai
2. Pastikan integrasi model konsisten
3. Evaluasi hasil tidak hanya dari statistik
4. Identifikasi keterbatasan masing-masing model

---

## 🔹 Struktur Laporan (WAJIB IMRAD)

### Introduction
Latar belakang integrasi model fisik dan ML dalam analisis banjir.

### Methods
Penjelasan model fisik, model ML, dan data yang digunakan.

### Results
Grafik hasil kedua model dan tabel perbandingan kinerja.

### Discussion
Interpretasi fisik hasil, kelebihan dan kekurangan masing-masing model.

### Conclusion
Ringkasan temuan dan rekomendasi teknik.

---

## 🔹 AI & Tools Integration

Mahasiswa boleh menggunakan AI untuk:

- membantu coding model ML
- membantu visualisasi hasil
- membantu format laporan

AI tidak boleh menggantikan:
- pemilihan metode model
- interpretasi hasil
- diskusi keterbatasan model

---

## 🔹 Engineer’s Interpretation (WAJIB)

Mahasiswa harus menjelaskan:

1. Model mana yang lebih realistis secara fisik?
2. Mengapa model ML bisa lebih baik/buruk?
3. Apa keterbatasan utama dari masing-masing pendekatan?

---

## 🔹 AI Assistance Disclosure (WAJIB)

Mahasiswa wajib menyatakan:
- AI tools yang digunakan
- Bagian yang dibantu AI
- Cara verifikasi hasil dilakukan

---

## 📊 Output yang Dikumpulkan

Mahasiswa menyerahkan:

- Diagram sistem model terpadu
- Grafik hasil model fisik dan ML
- Tabel evaluasi statistik
- Bagian **Engineer’s Interpretation**
- Bagian **AI Assistance Disclosure**
