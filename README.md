# GuardBot-Health-AI
Diciptakan untuk menyelesaikan project dari hactive8
# GuardBot: AI Health & Innovation Assistant

**GuardBot** adalah chatbot cerdas berbasis AI yang dirancang khusus untuk menjadi asisten kesehatan, kebugaran, dan gaya hidup. Proyek ini merupakan representasi digital dari sistem **Muscle Guard** (perangkat wearable sEMG) dan aplikasi pendamping **MyoGuard**.

Chatbot ini dikembangkan menggunakan **Streamlit** dan **Google Gemini AI** untuk memberikan pengalaman interaksi yang natural, informatif, dan profesional.

## 🚀 Fitur Utama

- **RAG (Retrieval-Augmented Generation):** Mampu membaca dan menjawab berdasarkan dokumen referensi internal (PDF) untuk memberikan jawaban yang akurat terkait teknis *Muscle Guard*.
- **Alur Berpikir (Reasoning):** Fitur transparansi yang memungkinkan pengguna melihat bagaimana AI menganalisis pertanyaan dan mencari referensi dokumen.
- **Memory & Session Management:** Mendukung riwayat percakapan (Chat History) sehingga pengguna dapat beralih antar sesi chat dengan mudah.
- **Quick Replies:** Tombol akses cepat untuk pertanyaan umum guna mempermudah interaksi awal.
- **UI Kustom ala Gemini:** Antarmuka yang bersih, responsif, dan modern menggunakan integrasi HTML/CSS di dalam Streamlit.

## 🛠️ Teknologi yang Digunakan
- **Bahasa Pemrograman:** Python
- **Framework UI:** Streamlit
- **LLM Engine:** Google Gemini 2.5 Flash
- **RAG Framework:** LangChain (ChromaDB, Google Generative AI Embeddings)
- **Styling:** Custom CSS & HTML Injection

## 📋 Prasyarat
Sebelum menjalankan aplikasi, pastikan Anda memiliki:
1. Python 3.9 atau versi lebih baru.
2. API Key dari [Google AI Studio](https://aistudio.google.com/).

## ⚙️ Cara Menjalankan
1. **Instal Library yang Dibutuhkan:**
   ```bash
   pip install -r requirements.txt
