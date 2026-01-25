# 08. UTS Case — Analisis Sistem Hidrologi Sederhana

## CPL & Posisi dalam RPS
- **CPL:** CPL-04 (Problem-Solving)
- **Tahap:** 8 (UTS Case)
- **Cakupan Materi:** Modul 1–7 (Sistem hidrologi, neraca air, presipitasi, ET, infiltrasi, limpasan, hidrograf)

---

# 🧩 SOAL KASUS

Sebuah DAS kecil dengan luas **5 km²** menerima hujan sebesar **120 mm** dalam satu kejadian hujan.

Kondisi DAS:
- Sebagian besar berupa lahan pertanian
- Tanah dalam kondisi **cukup lembap**
- Diperkirakan:
  - Evapotranspirasi selama kejadian dapat diabaikan
  - Infiltrasi kumulatif sebesar **50 mm**
  - Perubahan simpanan air tanah sebesar **10 mm**

### Pertanyaan

1. Buat skema sistem hidrologi (input–proses–output) untuk kejadian ini.
2. Hitung besar limpasan langsung (direct runoff) dalam satuan **mm**.
3. Hitung volume limpasan langsung dalam satuan **m³**.
4. Jelaskan bagaimana bentuk hidrograf yang mungkin terjadi (naik cepat/lambat, puncak tinggi/rendah).
5. Jika kondisi tanah berubah menjadi **jenuh**, bagaimana perubahan limpasan dan hidrografnya?

---

# 🧭 KISI-KISI PENYELESAIAN (UNTUK MAHASISWA)

Langkah berpikir yang diharapkan:

### Langkah 1 — Identifikasi Komponen Neraca Air
Gunakan konsep neraca air kejadian:

\[
P = Q_d + F + \Delta S
\]

Dimana:
- P = hujan total
- Qd = limpasan langsung
- F = infiltrasi
- ΔS = perubahan simpanan

---

### Langkah 2 — Masukkan Data ke Neraca Air
Masukkan semua data yang diketahui, lalu cari Qd.

---

### Langkah 3 — Konversi Kedalaman Limpasan ke Volume
Gunakan hubungan:

\[
V = Q_d \times A
\]

Perhatikan konversi satuan:
- mm → meter
- km² → m²

---

### Langkah 4 — Analisis Hidrograf Secara Konseptual
Gunakan pemahaman tentang:
- kondisi tanah
- besar limpasan
- respon DAS kecil

---

### Langkah 5 — Bandingkan dengan Kondisi Tanah Jenuh
Gunakan konsep:
- infiltrasi menurun
- losses berkurang
- limpasan meningkat

---

# ✅ PENYELESAIAN KOMPREHENSIF (KUNCI DOSEN)

## 1. Skema Sistem Hidrologi

**Input:** Hujan = 120 mm  
**Proses:** Infiltrasi + Perubahan Simpanan  
**Output:** Limpasan langsung menuju sungai

Skema:
Hujan → (Infiltrasi + Storage) + Limpasan → Sungai

---

## 2. Perhitungan Limpasan Langsung

Gunakan neraca air kejadian:

\[
P = Q_d + F + \Delta S
\]

\[
120 = Q_d + 50 + 10
\]

\[
Q_d = 120 - 60 = 60 \text{ mm}
\]

---

## 3. Volume Limpasan Langsung

Konversi satuan:

\[
Q_d = 60 \text{ mm} = 0.06 \text{ m}
\]

\[
A = 5 \text{ km}^2 = 5 \times 10^6 \text{ m}^2
\]

\[
V = 0.06 \times 5 \times 10^6 = 300{,}000 \text{ m}^3
\]

---

## 4. Analisis Bentuk Hidrograf

Karakteristik:
- DAS kecil → respon relatif cepat
- Tanah lembap → infiltrasi tidak maksimum
- Limpasan cukup besar (60 mm)

Maka:
- **Rising limb cukup curam**
- **Debit puncak relatif tinggi**
- **Waktu menuju puncak relatif singkat**
- Recession limb dipengaruhi pelepasan simpanan air tanah

---

## 5. Jika Tanah Jenuh

Jika tanah jenuh:
- Infiltrasi turun drastis
- Misal infiltrasi hanya 20 mm

Maka:
\[
Q_d = 120 - (20 + 10) = 90 \text{ mm}
\]

Dampaknya:
- Limpasan jauh lebih besar
- Hidrograf naik lebih cepat
- Debit puncak lebih tinggi
- Risiko banjir meningkat

---

# 📦 Output Mahasiswa

Mahasiswa mengumpulkan:
- Jawaban numerik lengkap
- Skema sistem hidrologi
- Sketsa hidrograf konseptual
