# Proyek Analisis dan Visualisasi Teks Al-Qur'an

Proyek ini bertujuan untuk melakukan analisis semantik, visualisasi, dan ekstraksi informasi dari teks Al-Qur'an beserta terjemahannya dalam bahasa Indonesia. Data yang digunakan diambil dari API Qur'an dan beberapa sumber dataset terjemahan.

## Fitur Utama
- Pengambilan data ayat Al-Qur'an beserta terjemahan bahasa Indonesia dari API:
  ```
  https://api.qurancdn.com/api/v4/verses/by_chapter/${chapter}?language=id&translations=33,134&words=0&fields=text_uthmani&per_page=300
  ```
- Analisis semantik menggunakan Cosine Similarity.
- Ekstraksi kata kunci dengan KeyBert.
- Visualisasi hasil analisis menggunakan UMAP dan grafik lainnya.
- Analisis sentimen dan n-gram (bigram, trigram) pada teks terjemahan.

## Struktur Folder
- `Dataset/` : Berisi dataset ayat dan terjemahan.
- `Semantic Analysis Results/` : Hasil analisis semantik dan visualisasi.
- `Sentiment Analysis Results/` : Hasil analisis sentimen dan n-gram.
- `BG-Google-Translated/` : Dataset hasil terjemahan Google.

## Sumber Data
- API Qur'an: [Quran.com API](https://quran.api-docs.io/)
- Dataset terjemahan: Google Translate, sumber lain sesuai kebutuhan.

## Catatan
- Proyek ini untuk keperluan riset dan pembelajaran.
- Silakan modifikasi sesuai kebutuhan analisis Anda.