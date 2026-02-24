# Associate-Data-Scientist-Python---Nasional
Courses KOMDIGI LMS

## Instalasi Python dan Konfigurasi Editor Python

### Pendahuluan

**Python** adalah salah satu bahasa pemrograman paling populer di dunia, dikenal karena sintaksisnya yang sederhana, fleksibilitas tinggi, dan ekosistem pustaka (library) yang sangat kaya. Baik Anda seorang pemula maupun pengembang berpengalaman, menginstal Python dengan benar adalah langkah penting untuk memastikan pengalaman ngoding yang lancar.

### Memahami Instalasi Python
**Apa itu Python?**

Python adalah bahasa pemrograman tingkat tinggi (high-level programming language) yang diinterpretasikan, dengan fokus pada keterbacaan kode (readability) dan kemudahan penulisan.

Python mendukung berbagai paradigma pemrograman seperti prosedural, berorientasi objek (object-oriented programming/OOP), dan fungsional (functional programming). Python banyak digunakan dalam pengembangan web, data science, machine learning, artificial intelligence, otomasi, dan banyak bidang teknologi lainnya.

**Mengapa Perlu Menginstal Python?**

Menginstal Python di komputer Anda memungkinkan:

* Menulis dan menjalankan program Python.
* Mengakses pustaka standar Python serta library pihak ketiga.
* Menggunakan pip (Python package manager) untuk menginstal dan mengelola library tambahan.
* Menjalankan aplikasi, framework, atau script berbasis Python.

### Panduan Instalasi Python Langkah demi Langkah
**Mengunduh Python**
* Buka [situs resmi Python](https://www.python.org/).
* Unduh installer Python terbaru yang stabil sesuai dengan sistem operasi Anda (Windows, macOS, atau Linux).

Instalasi Python di Windows
* **Download Installer**: Kunjungi [halaman unduhan Python](https://www.python.org/downloads/windows/) dan pilih file executable installer (.exe) terbaru.
* **Menjalankan Installer**: Klik dua kali file .exe yang telah diunduh. **Sangat penting**: Centang opsi "Add Python to PATH" sebelum klik Install Now.
* **Verifikasi Instalasi**: Buka Command Prompt (CMD) dan ketik perintah:
```
python --version
```
Jika instalasi berhasil, akan muncul informasi versi Python.

Instalasi Python di macOS
* **Download Installer**: Kunjungi [halaman unduhan Python](https://www.python.org/downloads/windows/) dan unduh file installer dengan ekstensi .pkg.
* **Menjalankan Installer**: Klik dua kali file .pkg dan ikuti instruksi di layar. Pastikan Python ditambahkan ke PATH sistem.
* **Verifikasi Instalasi**: Buka Terminal dan ketik perintah:
```
python3 --version
```

Instalasi Python di Linux
* **Cek Python yang Sudah Terpasang**: Banyak distribusi Linux sudah menyertakan Python secara default. Untuk mengeceknya:
```
python3 --version
```
* **Instalasi via Package Manager**:
  * Untuk Ubuntu/Debian:
    ```
    sudo apt update
    sudo apt install python3
    ```
  * Untuk Fedora:
    ```
    sudo dnf install python3
    ```
* **Verifikasi Instalasi**: Setelah instalasi, cek kembali dengan:
```
python3 --version
```
### Memilih dan Mengonfigurasi Editor untuk Pemrograman Python
**Apa itu Editor Python?**

Editor Python (juga disebut IDE - Integrated Development Environment atau editor kode) adalah alat untuk menulis, menjalankan, dan men-debug kode Python dengan efisien. Editor yang baik menyediakan fitur seperti syntax highlighting, auto-complete, debugging tools, dan dukungan integrasi ekstensi/plugin.

**Editor dan IDE Populer untuk Python**:

* **Jupyter Notebook**: Cocok untuk analisis data, data science, dan coding interaktif. Menyajikan kombinasi kode, teks, dan visualisasi dalam satu file.
* **Visual Studio Code (VS Code)**: Editor ringan, fleksibel, dan sangat bisa dikustomisasi. Ekosistem plugin sangat kaya, cocok untuk pengembangan Python.
* **PyCharm**: IDE khusus untuk Python dari JetBrains, menawarkan fitur canggih seperti code navigation, debugging, testing tools, dan integrasi version control.
* **Sublime Text**: Editor cepat dan ringan, mendukung Python lewat instalasi plugin tambahan.

Instalasi Plugin Python di VS Code

* **Instalasi Ekstensi Python**:
  * Buka **Visual Studio Code**.
  * Klik ikon **Extensions** di sidebar (atau tekan Ctrl+Shift+X).
  * Cari ekstensi "**Python**".
  * Pilih ekstensi resmi dari **Microsoft**, lalu klik **Install**.

* **Konfigurasi Ekstensi Python Setelah Instalasi**:
  * Set Interpreter: Tekan **Ctrl+Shift+P**, ketik **_Python: Select Interpreter_**, lalu pilih interpreter Python yang sesuai.
  * **Aktifkan Linter**: Gunakan tools seperti _Pylint_, _Flake8_, atau _Black_.
  * **Tambahkan Formatter Otomatis**: Install **Black** atau **autopep8** untuk formatting otomatis saat menyimpan file.

* **Plugin Tambahan Opsional**:
  * **Code Runner**: Menjalankan snippet kode dengan cepat.
  * **GitLens**: Visualisasi riwayat Git di dalam editor.
  * **Bracket Pair Colorizer**: Memberi warna pada pasangan tanda kurung, membuat kode lebih mudah dibaca.

### Catatan Tambahan

* Gunakan **Virtual Environment** (venv) untuk mengelola dependensi proyek Python secara terpisah.
* Biasakan menggunakan _pip_ atau _pipenv_ untuk instalasi library eksternal.
* Rajin memperbarui Python dan plugin untuk menjaga kompatibilitas dan keamanan.
