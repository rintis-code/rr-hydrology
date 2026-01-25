# 8. KASUS 1 — Pemodelan Hujan–Debit dengan HEC-HMS

## Posisi Modul
Level 2 — Hydrology with Engineering Tools, ML & AI  
Evaluasi Blok A (Modul 1–7)

Modul ini adalah studi kasus pertama untuk menguji pemahaman mahasiswa tentang dasar pemodelan hidrologi.

---

## Tujuan Kasus

Mahasiswa mampu:

1. Membangun model hujan–debit sederhana menggunakan HEC-HMS.
2. Menentukan metode losses dan transform yang sesuai.
3. Menjalankan simulasi dan menghasilkan hidrograf debit.
4. Mengevaluasi hasil model secara fisik, bukan hanya numerik.

---

## 🧩 Deskripsi Kasus

Sebuah DAS kecil memiliki data:

- Luas DAS: 25 km²  
- Data hujan kejadian (disediakan dosen)  
- Data debit observasi di outlet (disediakan dosen)

Tugas mahasiswa adalah membangun model hujan–debit menggunakan HEC-HMS untuk merepresentasikan kejadian tersebut.

---

## 📌 Tugas Mahasiswa

### 1. Setup Model
- Buat basin model DAS
- Masukkan data hujan
- Tentukan control specification

### 2. Pemilihan Metode
Mahasiswa harus memilih:
- Metode losses
- Metode transform
Disertai alasan teknis

### 3. Simulasi
- Jalankan model
- Hasilkan hidrograf debit di outlet

### 4. Evaluasi Hasil
Bandingkan:
- debit puncak simulasi vs observasi
- waktu puncak simulasi vs observasi
- bentuk hidrograf

---

## 🧭 KISI-KISI PENYELESAIAN

Langkah berpikir yang diharapkan:

1. Identifikasi karakteristik DAS (ukuran kecil → respon cepat)
2. Pilih metode losses yang masuk akal
3. Pilih transform method yang sesuai
4. Evaluasi apakah debit puncak realistis

---

## 🔹 AI & Tools Integration

Mahasiswa boleh menggunakan AI untuk:

- membantu memahami fungsi metode di HEC-HMS
- membantu membuat tabel perbandingan hasil
- membantu plotting grafik

AI tidak boleh menggantikan:
- pemilihan metode model
- interpretasi hasil simulasi

---

## 🔹 Engineer’s Interpretation (WAJIB)

Mahasiswa harus menjelaskan:

1. Mengapa metode yang dipilih sesuai dengan DAS?
2. Apakah debit hasil model realistis? Mengapa?
3. Apa penyebab perbedaan antara simulasi dan observasi?

---

## 🔹 AI Assistance Disclosure (WAJIB)

Mahasiswa harus menuliskan:
- Tools AI yang digunakan
- Bagian mana AI membantu
- Bagaimana hasil diverifikasi sendiri

---

## 📊 Output yang Dikumpulkan

Mahasiswa menyerahkan:

- Diagram model HEC-HMS
- Grafik hujan dan debit simulasi
- Tabel perbandingan simulasi vs observasi
- Bagian **Engineer’s Interpretation**
- Bagian **AI Assistance Disclosure**
