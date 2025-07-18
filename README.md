# Deteksi dan Analisis Berita Hoax vs Faktual Menggunakan IBM Granite

## Project Overview

Proyek ini bertujuan untuk mendeteksi dan menganalisis berita hoax (fake news) dibandingkan dengan berita faktual (real news) menggunakan Large Language Model (LLM) IBM Granite. Dengan memanfaatkan AI, sistem ini mampu mengklasifikasikan judul berita sebagai Fake atau Real dan membuat ringkasan singkat dari isi berita untuk mempermudah pemahaman.

## Raw Dataset Link

- Fake News Detection Datasets – Kaggle
- https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets

## Insight & Findings

- Proporsi berita Fake dan Real dalam dataset seimbang sehingga cocok untuk model classification.
- Berita Fake cenderung menggunakan kata-kata sensasional seperti "Breaking", "Shocking", "Exclusive", sementara berita Real menggunakan bahasa yang lebih netral.
- Kata-kata umum dalam berita Real: "announces", "reports", "confirms".

## AI Support Explanation

- **Model Digunakan:** IBM Granite 3.3-8B Instruct via Replicate API.
- **Fungsi AI:**
  - Mengklasifikasikan judul berita sebagai Fake atau Real.
  - Membuat ringkasan singkat dari isi berita.
  - Menghasilkan insight dan rekomendasi otomatis.
- **Alasan Penggunaan:**
  - IBM Granite memiliki kemampuan instruksi yang kuat untuk classification dan summarization.
  - Dapat memproses berbagai teks berita secara langsung melalui API.

---

> Dibangun menggunakan Google Colab, Gradio, Pandas, Matplotlib, Langchain Community, dan Replicate API.
