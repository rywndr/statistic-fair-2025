# 📊 statistic-fair-2025 🌟

user sentiment analysis project for the **"Identitas Kependudukan Digital"** App

### 🇮🇩 _(id)_

repo ini adalah untuk proyek kuliah, tujuan utamanya adalah untuk menganalisis sentimen dari pengguna aplikasi **"Identitas Kependudukan Digital"** yang diluncurkan oleh pemerintah Indonesia di iOS dan Android.  
📥 Data untuk proyek ini dikumpulkan dengan melakukan **scraping review** dari Google Play Store dan App Store.  
🛠️ Data tersebut kemudian **dibersihkan** dan dianalisis untuk mendapatkan wawasan tentang **sentimen pengguna**.

jumlah sampel yang digunakan untuk analisis ini ditentukan dengan rumus slovin yaitu:

$$
n = \frac{N}{1 + N(e^2)}
$$

---

### 🌍 _(en)_

this repo is for a college project, the main goal is to analyze the sentiments of people that use the **"Identitas Kependudukan Digital"** app launched by the Government of Indonesia on iOS and Android.  
📥 The data for this project is collected by **scraping reviews** from the Google Play Store and App Store.  
🛠️ The data is then **cleaned** and analyzed to gain insights about **user sentiments**.

the sample size used for this analysis is determined by the slovin formula:

$$
n = \frac{N}{1 + N(e^2)}
$$

---

repo structure:

```bash
statistic-fair-2025/
├── README.md
├── datasets/        # 📁 Dataset yang digunakan untuk analisis
│   ├── Apple_App_Store_Rev     # Dataset review dari App Store
│   └── Google_Play_Store_Rev   # Dataset review dari Google Play Store
└── notebooks/       # 📁 Jupyter Notebook dengan kode untuk scraping dan sentiment analysis
    ├── as_rev.ipynb                         # Kode untuk scraping review App Store
    ├── gps_rev.ipynb                        # Kode untuk scraping review Google Play Store
    └── revised_sentiment_analysis_si.ipynb  # Kode untuk analisis sentimen
```

💻 Made with ❤️

<sub><sup>the paper for this project is in the making</sup></sub>
