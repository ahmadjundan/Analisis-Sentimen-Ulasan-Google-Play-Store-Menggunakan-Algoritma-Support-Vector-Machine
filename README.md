# Scrap Playstore dan Analisis Sentimen Aplikasi

Repositori ini berisi kode untuk melakukan scraping data ulasan aplikasi dari Google Play Store, pra-pemrosesan teks, dan analisis sentimen menggunakan model machine learning. Proyek ini mencakup langkah-langkah seperti scraping data, pra-pemrosesan teks, dan evaluasi model untuk analisis sentimen.

## Fitur

1. **Scraping Data dari Playstore**:
   - Mengumpulkan ulasan pengguna dari aplikasi yang tersedia di Google Play Store.

2. **Pra-Pemrosesan Teks**:
   - **Casefolding**: Mengubah teks menjadi huruf kecil.
   - **Cleansing**: Menghapus karakter yang tidak diperlukan (seperti tanda baca, simbol, dll.).
   - **Normalisasi**: Mengubah kata tidak baku menjadi bentuk baku.
   - **Tokenisasi**: Memecah teks menjadi kata-kata individual.
   - **Stopword Removal**: Menghapus kata-kata umum yang tidak memiliki makna penting menggunakan library Sastrawi.
   - **Stemming**: Mengubah kata ke bentuk dasarnya menggunakan library Sastrawi.
   - **Labeling**: Memberikan label sentimen menggunakan Modified Indonesia Sentiment Lexicon.

3. **Training dan Evaluasi Model**:
   - **Split Data**: Membagi dataset menjadi data training dan testing.
   - **TF-IDF**: Mengubah teks menjadi vektor fitur menggunakan Term Frequency-Inverse Document Frequency.
   - **K-Fold Cross Validation**: Mengevaluasi model menggunakan validasi silang.
   - **Confusion Matrix**: Mengukur performa rata-rata model dengan confusion matrix.
