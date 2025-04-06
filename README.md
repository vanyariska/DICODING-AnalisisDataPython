# Dashboard Analisis Penyewaan Sepeda 🚴‍♀️

Proyek ini dirancang untuk menganalisis dan memvisualisasikan data penyewaan sepeda melalui dashboard interaktif Streamlit. Proyek ini mengeksplorasi pola data, memberikan wawasan yang berguna, dan menjawab pertanyaan bisnis utama.

---

## Fitur 📊

1. **Notebook Analisis Data**:
   - Sebuah Jupyter Notebook (`Vanyariska_Indriani_Proyek_Analisis_Data.ipynb`) yang melakukan analisis mendalam terhadap data penyewaan sepeda.
   - Wawasan mengenai pola seperti:
     - Pengaruh musim terhadap jumlah penyewaan sepeda.
     - Pengaruh kondisi cuaca terhadap jumlah penyewaan sepeda.
     - Pola penyewaan per jam pada hari kerja dibandingkan hari libur.
     - Perbandingan penggunaan antara pengguna kasual dan terdaftar.

2. **Dashboard Interaktif Streamlit**:
   - Filter dan eksplorasi data penyewaan sepeda berdasarkan:
     - Musim.
     - Kondisi cuaca.
     - Tahun.
   - Visualisasi pola penyewaan per jam untuk hari kerja dan hari libur.
   - Perbandingan penggunaan antara pengguna kasual dan terdaftar.
   - Dapatkan wawasan tentang pola dan tren data khusus.

---

## Struktur Proyek 📚

```
submission_Vanyariska/
├── dashboard/
│   ├── data/
│   │    ├── hour.csv     # Data penyewaan sepeda per jam
│   │    ├── day.csv      # Data penyewaan sepeda per hari
│   ├── dashboard.py      # Skrip dashboard Streamlit
│
├── data/
│   ├── hour.csv          # Data penyewaan sepeda per jam
│   ├── day.csv           # Data penyewaan sepeda per hari
│
├── url.txt               # Link deploy dashboard
├── requirements.txt      # Dependensi Python
├── README.md             # Dokumentasi proyek
├── Vanyariska_Indriani_Proyek_Analisis_Data.ipynb  # Notebook analisis data
```

---

## Menyiapkan Lingkungan - Anaconda 🫠

1. Buat dan aktifkan lingkungan:
   ```bash
   conda create --name main-ds python=3.9
   conda activate main-ds
   ```

2. Instal dependensi:
   ```bash
   pip install -r requirements.txt
   ```

---

## Menyiapkan Lingkungan - Shell/Terminal 🛠️

1. Buat folder proyek:
   ```bash
   mkdir proyek_analisis_data
   cd proyek_analisis_data
   ```

2. Siapkan lingkungan:
   ```bash
   pipenv install
   pipenv shell
   pip install -r requirements.txt
   ```

---

## Menjalankan Aplikasi Streamlit 🌐

Untuk menjalankan dashboard, gunakan perintah berikut:

```bash
streamlit run dashboard/dashboard.py
```

---

## Wawasan yang Disediakan 🕵️‍♂️

Dashboard ini memberikan wawasan seperti:

1. Bagaimana musim memengaruhi jumlah penyewaan sepeda.
2. Pengaruh kondisi cuaca terhadap penyewaan sepeda.
3. Perbedaan pola penyewaan per jam antara hari kerja dan hari libur.
4. Perbandingan penggunaan antara pengguna kasual dan terdaftar.

---

## Sumber Data 🔖

- `hour.csv`: Berisi data penyewaan sepeda per jam, termasuk jumlah penyewaan, cuaca, dan detail musim.
- `day.csv`: Berisi data penyewaan sepeda per hari dengan jumlah penyewaan yang sudah diakumulasi dan informasi cuaca.

---

## Dependensi 🔧

Proyek ini membutuhkan pustaka Python berikut:

- `matplotlib==3.9.4`
- `pandas==2.2.3`
- `seaborn==0.13.2`
- `streamlit==1.40.2`

Instal dependensi ini menggunakan:

```bash
pip install -r requirements.txt
```

---

## Link Deploy 📡

Akses dashboard yang telah dideploy menggunakan link di file `url.txt`.

---

## Penulis 👤

**Vanyariska Indriani**
- Proyek: Dashboard Analisis Penyewaan Sepeda
- Kontak: vanyariskaindriani@gmail.com