# IBM
Forecasting Deforestation Using IBM Granite Data Classification and Summarization

# Project Overview
Deforestation atau Penggundulan hutan adalah salah satu masalah paling besar dan merupakan masalah seluruh dunia karna hutan dan area pepohonan merupakan sumber daya dunia yang paling penting karna banyaknya manfaat hutan seperti membuat oksigen di seluruh dunia atau meredakan Global Warming.

Data menunjukkan bahwa banyak negara mengalami penurunan luas hutan akibat aktivitas manusia seperti pertanian, penebangan liar, dan urbanisasi. Dengan adanya data satelit dan statistik, sekarang kita dapat menganalisis deforestasi secara lebih sistematis.

# Datasets
Deforestation Dataset (kaggle) : https://www.kaggle.com/datasets/konradb/deforestation-dataset
Global Forest Data: 2001-2022 (kaggle) : https://www.kaggle.com/datasets/karnikakapoor/global-forest-data-2001-2022

#  Insight & findings
Kebanyakan negara di dunia mengalami penurunan luas hutan selama dua dekade terakhir. Beberapa negara, seperti di kawasan Eropa Utara dan Asia Timur, menunjukkan peningkatan luas hutan karena program reforestasi.
Analisis menunjukkan bahwa cukup banyak negara mengalami penurunan persentase luas hutan dalam periode 20 tahun tersebut. Ini mengindikasikan bahwa deforestasi masih menjadi masalah signifikan di banyak wilayah.
Di sisi lain, ada juga sejumlah negara yang berhasil meningkatkan atau mempertahankan luas hutan mereka. Tren positif ini memberikan contoh bahwa upaya reforestasi dan konservasi bisa berhasil.

# AI Support Explanation
Dalam proyek ini, AI pada model bahasa (LLM) IBM Granite yang diakses melalui Replicate API, digunakan untuk mengatasi dua tugas utama yang memerlukan pemahaman konteks dan kemampuan meringkas:
- Mengklasifikasikan Deforestasi: AI membaca data persentase hutan tahun 2000, 2020, dan trennya untuk setiap negara, lalu mengklasifikasikannya menjadi kategori "area hutan meningkat", "menurun", atau "stabil". Ini relevan karena AI dapat menginterpretasikan data numerik menjadi kategori kualitatif secara otomatis.
- Meringkas Temuan: AI menerima data ringkasan tentang jumlah negara di setiap kategori klasifikasi dan menghasilkan rangkuman teks yang mudah dibaca mengenai pola deforestasi global. Ini relevan karena AI sangat baik dalam membuat narasi ringkas dari data.
