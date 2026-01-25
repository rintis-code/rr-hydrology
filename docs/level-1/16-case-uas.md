# 16. UAS Case — Pemodelan Hujan–Debit Berbasis Metode Klasik dan AI

## CPL & Posisi dalam RPS
- **CPL:** CPL-05 (Modern Tools & Engineering Skills)
- **Tahap:** 16 (UAS Case)
- **Cakupan:** Modul 9–15 (Hidrometri, debit banjir, hidrograf, HSS, routing, AI/ML)

---

## Tujuan UAS Case

Mahasiswa mampu:

1. Menganalisis respon hidrologi DAS dari data hujan dan debit.
2. Membangun model hujan–debit menggunakan metode klasik ATAU pendekatan AI/ML.
3. Membandingkan hasil model dan memberikan interpretasi teknik.
4. Menunjukkan penggunaan AI secara bertanggung jawab.

---

# 🧩 SOAL KASUS

Sebuah DAS kecil memiliki data:

- Luas DAS: 12 km²  
- Data hujan kejadian: tersedia (disediakan dosen)  
- Data debit observasi di outlet: tersedia (disediakan dosen)

Mahasiswa diminta untuk:

1. Menganalisis karakteristik DAS secara konseptual.
2. Membangun model hujan–debit dengan salah satu pendekatan:
   - **Metode klasik** (HSS + routing), ATAU
   - **Pendekatan data-driven sederhana** (regresi/ML/ANN sederhana).
3. Membandingkan debit hasil model dengan debit observasi.
4. Menjelaskan kelebihan dan keterbatasan metode yang digunakan.

---

# 🧭 KISI-KISI PENYELESAIAN

### Langkah 1 — Analisis Awal DAS
- Luas DAS
- Respon cepat/lambat
- Perkiraan limpasan besar/kecil

---

### Langkah 2 — Pilih Pendekatan Model

**Opsi A (Klasik):**
- Tentukan hujan efektif
- Gunakan HSS (Nakayasu atau Gama I)
- Lakukan routing jika diperlukan

**Opsi B (AI/ML Sederhana):**
- Gunakan data hujan sebagai input
- Gunakan regresi atau ANN sederhana untuk memprediksi debit
- Latih model dengan sebagian data

---

### Langkah 3 — Bandingkan dengan Data Observasi
- Bandingkan debit puncak
- Bandingkan waktu puncak
- Bandingkan bentuk hidrograf

---

### Langkah 4 — Evaluasi Model

Mahasiswa harus menilai:
- apakah hasil model masuk akal secara fisik
- di mana model menyimpang
- kemungkinan penyebab perbedaan

---

# 🔹 AI & Tools Integration

Mahasiswa boleh menggunakan AI untuk:

- membantu coding sederhana
- membantu plotting grafik
- membantu menyusun tabel perbandingan

AI **tidak boleh menggantikan**:
- interpretasi hidrologi
- pemilihan model akhir
- kesimpulan teknik

---

# 🔹 Engineer’s Interpretation (WAJIB)

Mahasiswa harus menjelaskan:

1. Mengapa model yang dipilih cocok/tidak cocok untuk DAS ini?
2. Apa arti fisik dari perbedaan model dan observasi?
3. Apa risiko jika hasil model digunakan tanpa evaluasi teknik?

---

# 🔹 AI Assistance Disclosure (WAJIB)

Mahasiswa wajib menuliskan:

- Tools AI apa yang digunakan
- Untuk bagian apa AI membantu
- Apa yang dimodifikasi atau diverifikasi sendiri

---

# 📊 Output yang Dikumpulkan

Mahasiswa menyerahkan:

- Grafik hujan dan debit
- Grafik hidrograf hasil model
- Tabel perbandingan observasi vs model
- Bagian **Engineer’s Interpretation**
- Bagian **AI Assistance Disclosure**

---

# 🎯 Hasil Pembelajaran yang Diharapkan

Mahasiswa menunjukkan bahwa mereka:

✔ Memahami proses hidrologi  
✔ Mampu menggunakan metode klasik  
✔ Mampu memanfaatkan AI secara bijak  
✔ Tetap mengambil keputusan sebagai engineer
