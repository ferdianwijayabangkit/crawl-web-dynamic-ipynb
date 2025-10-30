# ⚙️ Web Scraping: Ekstraksi Dinamis
### **Implementasi Scraping Halaman Dinamis dengan Python & Selenium**

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Selenium](https://img.shields.io/badge/Selenium-WebDriver-green.svg)
![WebDriver--Manager](https://img.shields.io/badge/WebDriver--Manager-auto--install-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Affiliation](https://img.shields.io/badge/Affiliation-UNTIRTA-orange.svg)

Repositori ini menyajikan modul pembelajaran yang memandu Anda melalui alur kerja **Web Scraping** untuk halaman **dinamis**. Proyek ini mendemonstrasikan implementasi di **Python** untuk mengekstrak data dari website yang memuat kontennya menggunakan JavaScript, dengan memanfaatkan pustaka `Selenium`.

---

## ✨ Fitur Utama

- **Implementasi Python**: Fokus pada implementasi *scraping* dinamis menggunakan ekosistem Python.
- **Materi Pembelajaran**: Menyajikan definisi, contoh, dan alur kerja untuk *scraping* halaman dinamis (JS-rendered), menjadikannya sumber daya yang ideal untuk pemula.
- **Metode Scraping Dinamis**: Menerapkan strategi *browser automation* pada **[quotes.toscrape.com/js/](http://quotes.toscrape.com/js/)**:
    - **`Selenium`**: Mengotomatisasi dan mengontrol browser (Chrome) untuk memuat halaman.
    - **`webdriver-manager`**: Mengelola instalasi driver browser secara otomatis.
    - **`time.sleep()`**: Memberi jeda waktu agar browser dapat selesai mengeksekusi JavaScript dan memuat data.
    - **`.find_elements()`**: Mengekstrak data (kutipan dan penulis) setelah data tersebut berhasil dimuat ke dalam DOM.
- **Laporan Reproducibel**: Menyediakan file Jupyter Notebook (`.ipynb`) yang mendokumentasikan setiap langkah, dari inisiasi *driver* hingga ekstraksi data.

---

## 📂 Struktur Proyek

- `ekstrasi dinamis.ipynb`: Notebook Python untuk implementasi *scraping* halaman dinamis.
- `README.md`: File ini.

*(Catatan: Proyek ini tidak memerlukan file data eksternal karena data diambil langsung dari web.)*

---

## 🔧 Tumpukan Teknologi (Tech Stack)

- **Bahasa**: `Python 3.7+`
- **Pustaka Python**: `selenium`, `webdriver-manager`, `time`
- **Lingkungan**: `Jupyter Notebook / Lab`

---

## 🚀 Cara Memulai

### Prasyarat

- Instalasi Python 3.x.
- **Browser Google Chrome** yang terinstal di sistem Anda.
- Pustaka yang diperlukan (lihat instalasi di bawah).
- Jupyter Notebook/Lab.

### Instalasi & Penggunaan

1.  **Unduh Repositori**: *Clone* atau unduh proyek ini ke komputer Anda.
2.  **Instal Pustaka**: Buka terminal atau *command prompt* Anda dan jalankan:
    ```bash
    pip install selenium webdriver-manager
    ```
3.  **Jalankan Notebook**:
    - Jalankan Jupyter Lab/Notebook.
    - Buka file `ekstrasi dinamis.ipynb` dan jalankan sel kode di dalamnya.
    - Jendela browser Chrome baru akan terbuka secara otomatis, memuat halaman, lalu menutup.

---

## 📊 Ringkasan Hasil Utama

| Masalah | Metode Utama | Hasil Utama |
|---|---|---|
| **Ekstraksi Data Web Dinamis** (`.../js/`) | Dynamic Scraping (`Selenium`) | Berhasil mengotomatisasi browser, menunggu JavaScript memuat data, dan mengekstrak 10 kutipan dari halaman. |

---

## ⚖️ Lisensi & Ketentuan Penggunaan

- **Hak Cipta**: © 2025 Ferdian Bangkit Wijaya - Seluruh Hak Dilindungi.
- **Penggunaan Akademik**: Diizinkan secara bebas untuk keperluan penelitian dan pendidikan non-komersial dengan atribusi.
- **Penggunaan Komersial**: Memerlukan izin tertulis dari pengembang.

---

## 👨‍💻 Author

- **Ferdian Bangkit Wijaya**
- Universitas Sultan Ageng Tirtayasa (UNTIRTA)
- Banten, Indonesia 🇮🇩

---

> Proyek ini berfungsi sebagai panduan praktis untuk web scraping dinamis, menunjukkan bagaimana `Selenium` dapat mengatasi tantangan website yang dimuat oleh JavaScript.
