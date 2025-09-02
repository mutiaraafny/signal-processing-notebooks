# Pengantar Pengolahan Sinyal dengan Python

**Repositori ini berisi Jupyter Notebooks yang dibuat untuk mengeksplorasi konsep dasar pengolahan sinyal digital (DSP) secara visual dan interaktif.**

Proyek ini bertujuan untuk membantu memahami operasi-operasi fundamental pada sinyal 1D (seperti gelombang suara) dan sinyal 2D (seperti gambar) melalui implementasi kode yang jelas dan visualisasi menggunakan library Python populer.

---

### Daftar Isi

* **`notebooks/Operasi-Sinyal-Dasar.ipynb`**: Notebook utama yang menjelaskan dan mengimplementasikan operasi-operasi berikut:
    * **Sinyal 1D**: Penskalaan, penggeseran, penjumlahan, dan perkalian sinyal.
    * **Sinyal 2D**: Penerapan filter (blur, edge detection, sharpen) pada gambar.
    * **Kombinasi Sinyal**: Penjumlahan dan konvolusi dua sinyal.
* **`html/visualisasi-interaktif.html`**: File HTML asli yang menjadi dasar proyek ini, menampilkan visualisasi interaktif melalui JavaScript dan Plotly.

---

### Cara Menjalankan Notebook

Anda bisa menjalankan file Jupyter Notebook ini di berbagai lingkungan.

1.  **Menggunakan Google Colab atau Kaggle:**
    * Cara termudah karena tidak memerlukan instalasi.
    * Unggah file `Operasi-Sinyal-Dasar.ipynb` ke Google Colab atau Kaggle Notebooks.
    * Jalankan setiap sel kode secara berurutan.

2.  **Menjalankan Secara Lokal (VS Code / Jupyter):**
    * Pastikan Anda sudah menginstal **Python** dan **Git**.
    * Kloning repositori ini ke komputer Anda:
        ```bash
        git clone [https://github.com/nama-organisasi/signal-processing-notebooks.git](https://github.com/nama-organisasi/signal-processing-notebooks.git)
        cd signal-processing-notebooks
        ```
    * Instal library yang diperlukan:
        ```bash
        pip install numpy matplotlib scipy
        ```
    * Buka Jupyter Notebook atau VS Code, lalu buka file `Operasi-Sinyal-Dasar.ipynb` dan jalankan sel-sel kodenya.

---

### Contoh Visualisasi

Berikut adalah contoh visualisasi dari notebook yang menunjukkan operasi penjumlahan dua sinyal.



---

### 👥 Kontribusi Tim

Proyek ini merupakan hasil kerja kolaboratif dari anggota tim:

| Nama Anggota | Kontribusi Utama | Tautan GitHub |
| :--- | :--- | :--- |
| **Mutiara Afny** | Inisialisasi proyek dan implementasi fungsi sinyal 1D | [@mutiaraafny](https://github.com/mutiaraafny) |
| **Firlana Umi** | Implementasi fungsi sinyal 2D dan penulisan sel kode | [@blackcatin](https://github.com/blackcatin) |
| **Andini Putri** | Perbaikan bug pada fungsi dan penambahan visualisasi | [@ankirsydii](https://github.com/ankirsydii) |
| **Shafiyyah Al-Khansa** | Implementasi operasi kombinasi dan refactoring kode | [@shafiiyyaa](https://github.com/shafiiyyaa) |
| **Rana Rohadatul** | Penulisan dokumentasi, termasuk README dan komentar kode | [@urikkqum](https://github.com/urikkqum) |

Anda bisa melihat riwayat kontribusi secara detail di [halaman kontributor repositori](https://github.com/nama-organisasi/signal-processing-notebooks/graphs/contributors) atau di [log commit](https://github.com/nama-organisasi/signal-processing-notebooks/commits).

---

### Lisensi

Proyek ini dilisensikan di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).
