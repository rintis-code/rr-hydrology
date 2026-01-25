# 8. Konsep dan Arsitektur Agent AI dalam Sistem SDA

## Posisi Modul
Level 3 — Expert Hydrology (AI Agents)

Modul ini memperkenalkan konsep Agent AI sebagai bagian dari sistem keputusan sumber daya air, bukan sebagai pengganti engineer.

---

## Tujuan Modul

Setelah mempelajari modul ini, mahasiswa mampu:

1. Memahami perbedaan antara model ML dan Agent AI.
2. Menjelaskan peran Agent AI dalam sistem SDA.
3. Mengidentifikasi batasan penggunaan Agent AI dalam rekayasa.
4. Menempatkan Agent AI sebagai decision-support, bukan decision-maker.

---

## 1. Apa itu Agent AI?

Agent AI adalah sistem cerdas yang:

- menerima informasi dari berbagai sumber
- mengevaluasi beberapa kemungkinan
- memberi rekomendasi berdasarkan tujuan tertentu

Agent AI bekerja pada **level keputusan**, bukan hanya prediksi.

---

## 2. Perbedaan Model ML vs Agent AI

| Model ML | Agent AI |
|----------|----------|
| Fokus pada prediksi | Fokus pada rekomendasi keputusan |
| Input → Output | Input → Evaluasi → Opsi tindakan |
| Biasanya satu fungsi | Mengelola banyak tujuan & batasan |

ML bisa menjadi bagian dari Agent AI, tetapi Agent AI lebih kompleks.

---

## 3. Arsitektur Sederhana Agent AI dalam SDA

Agent AI menerima:

- hasil model hidrologi
- hasil model hidraulika
- batas teknis infrastruktur
- tujuan sistem (misal: minimalkan risiko banjir)

Agent AI kemudian:

- membandingkan beberapa opsi tindakan
- menilai risiko tiap opsi
- memberikan rekomendasi kepada engineer

---

## 4. Mengapa Agent AI Diperlukan?

Sistem SDA modern memiliki:

- banyak model
- banyak skenario
- banyak tujuan yang saling bertentangan

Agent AI membantu mengevaluasi kompleksitas tersebut secara cepat dan sistematis.

---

## 5. Batasan Agent AI

Agent AI tidak memiliki:

- tanggung jawab hukum
- pemahaman konteks sosial sepenuhnya
- kewenangan kebijakan

Karena itu keputusan akhir tetap dilakukan manusia.

---

## 🔹 AI & Tools Integration

Mahasiswa boleh menggunakan AI untuk:

- membantu membuat diagram arsitektur Agent AI
- membantu menjelaskan perbedaan ML dan Agent AI

AI tidak boleh menggantikan:
- analisis peran manusia dalam sistem
- penentuan batas tanggung jawab engineer

---

## 🔹 Engineer’s Reflection

Mahasiswa harus menjawab:

1. Mengapa Agent AI bukan pengganti engineer?
2. Apa perbedaan utama antara model ML dan Agent AI?
3. Mengapa sistem SDA modern membutuhkan Agent AI?

---

## Output yang Dikumpulkan

Mahasiswa menyerahkan:

- Diagram arsitektur Agent AI dalam sistem SDA
- Penjelasan peran dan batasan Agent AI
- Jawaban Engineer’s Reflection
