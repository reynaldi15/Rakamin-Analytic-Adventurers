# Holiday_Package_Prediction

![status](https://img.shields.io/badge/status-active-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8-blue)

![alt text](./img/dataset-cover.jpg)

"Trips & Travel.Com" company wants to enable and establish a viable business model to expand the customer base. One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information. The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being. However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

## Table of Contents 🖥️ 
1. [Overview](#overview)
2. [Project Structure](#project-structure)
3. [Data PreProcessing](#data-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)

## Overview
penjelasan detail :
- Tujuan proyek
  Untuk meningkatkan conversion rate guna mengoptimalkan pemasaran paket liburan dengan fokus pada segmen pelanggan yang paling relevan.  Dengan memanfaatkan data pelanggan yang ada, kami akan     mengidentifikasi pelanggan yang paling mungkin tertarik pada paket wellness dan menargetkan mereka secara spesifik.

## Project Structure

```bash
├── Dataset/              # Dataset asli
├── file_py/              # Jupyter Notebooks
├── Homework/             # PPT
├── img/                  # Image resource
├── README.md             # File ini
```

## Data PreProcessing ⚙️
Pada tahapan Data Pre-Processing menghasilkan sebuah data yang sudah diolah menjadi data yang berguna kedepannya dalam pemodelan data. Holiday package masih memiliki beberapa data yang tidak normal dan tidak sesuai type data. Hal teresebut akan membuat kesalah dalam pemodelan prediksi, maka dari hal tersebut tahapan Pre-processing sangat membantu dalam mengolah data yang dimiliki dengan menggunakan metode serta pendekatan yang sesuai dalam memperbaiki dataset. tahapan ini tidak hanya membuang feature yang tidak digunakan pada pemodelan namun juga meghasilkan sebuah feature terbaru yang membantu dalam peningkatan model prediksi, seperti membuat klasifikasi umur yang berasal dari feature yang sudah ada. serta feature lainnya yang masih belum ada di dataset.

## Exploratory Data Analysis (EDA) 💡〽️
Pada tahapan Exploratory Data Analysis (EDA) menghasilkan sebuah insgiht baru yang dapat membantu dalam pemrosesan pemodelan data serta mendapatkan pandangan baru untuk bidang bisnis. pada tahapan ini insight yang didapat pada pemodelan adalah fitur target yang akan digunakan berupa ProdTaken memiliki korelasi dengaan fitur lainnya dan terdapat beberapa fitur yang tidak memiliki korelais kuat untuk pengembangan model.
### Business Insights
- 60% paket yang diambil tawarannya adalah pake Basic, kemudian Deluxe, Standard, serta Super Deluxe dan King.
- harga paket bukanlah masalah utama seseorang dalam mengambil paket setelah ditawarkan asalkan sales dapat dengan tepat memilih segment pelanggan yang sesuaikan untuk di-pitch.
- adanya kecenderungan bahwa semakin banyak jumlah follow-up yang dilakukan oleh sales, semakin tinggi persentase pelanggan yang akhirnya memutuskan untuk membeli paket perjalanan. Presentase pelanggan yang membeli meningkat secara signifikan dari sekitar 11.36% pada satu follow-up menjadi 39.71% pada enam follow-up.
Hal ini menunjukkan adanya korelasi positif antara jumlah follow-up yang dilakukan oleh sales dengan keputusan pelanggan untuk membeli paket perjalanan. Semakin banyak interaksi atau tindak lanjut yang dilakukan, semakin tinggi kemungkinan pelanggan untuk mengambil keputusan pembelian. Hal ini dapat menjadi indikasi bahwa strategi follow-up yang lebih intens memiliki dampak yang positif terhadap peningkatan konversi pelanggan dalam membeli paket perjalanan.
- ingkat konversi, atau persentase pelanggan yang telah mengambil produk, ternyata lebih tinggi di CityTier 3 (23.60%) dan CityTier 2 (23.23%) meskipun jumlah pelanggannya lebih sedikit dibandingkan dengan CityTier 1 (16.30%) yang memiliki jumlah pelanggan terbanyak. Hal ini menunjukkan bahwa meskipun jumlah pelanggan bisa lebih sedikit, tingkat konversi yang lebih tinggi di CityTier 3 dan 2 bisa menjadi peluang yang menarik dalam strategi pemasaran, mungkin dengan fokus lebih lanjut pada profil atau preferensi pelanggan di tingkat kota tersebut.
- terdapat perbedaan signifikan dalam persentase pelanggan yang telah mengambil produk antara mereka yang memiliki paspor dan yang tidak memiliki. Proporsi pelanggan yang telah mengambil produk jauh lebih tinggi di antara mereka yang memiliki paspor (34.74%) dibandingkan dengan yang tidak memiliki (12.29%). Hal ini bisa menunjukkan adanya korelasi atau pengaruh antara kepemilikan paspor dengan keputusan pelanggan untuk mengambil produk. Namun, perlu analisis lebih lanjut untuk memahami apakah faktor kepemilikan paspor secara langsung memengaruhi keputusan tersebut atau terdapat faktor lain yang turut berperan dalam pengambilan keputusan pelanggan.
- setiap paket memiliki segment pasar (khususnya dalam income) sesuai dengan harga paket tersebut. Paket termurah yaitu Basic didominasi oleh pelanggan dengan low income. Paket menengah yaitu Deluxe didominasi dengan pelanggan dengan middle income. Paket menengah ke termahal yaitu paket Standard, Super Deluxe, dan King didominasi oleh pelanggan dengan high income.
Dikarenakan paket baru yang akan ditawarkan merupakan paket yang berfokus pada kesehatan yaitu paket Wellness Tourism dan dengan biaya/tarif yang lebih mahal dibandingkan dengan paket King, sehingga ke depannya pemasaran paket paker Wellness Tourism bisa didasarkan oleh segmentasi income dari King Package.
-  paket Basic didominasi oleh anak muda dan orang tua, sedangkan paket Deluxe dan Super Deluxe didominasi oleh umur menengah, dan paket Standard dan Paket King didominasi oleh orang tua. Jika pemasaran paket Wellness Toursim mengacu pada paket King, maka segmentasi umur yang sesuai adalah orang tua berumur 50 tahun ke atas dengan high income.

