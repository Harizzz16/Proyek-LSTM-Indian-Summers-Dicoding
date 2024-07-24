# Proyek-LSTM-Indian-Summers-Dicoding
Proyek-LSTM-Indian-Summers-Dicoding
Laporan Proyek Machine Learning LSTM Cuaca Musim Panas India - Haris Amaldi
Domain Proyek
Musim panas dengan temperaturnya yang panas memang bisa menjadi kesempatan yang menyenangkan untuk piknik dan berjemur di pantai. Akan tetapi, temperatur panas yang ekstrem juga dapat menjadi tantangan bagi setiap orang untuk beraktivitas secara produktif dan bahkan bisa berujung masalah serius seperti dehidrasi hingga heat stroke yang mematikan. Maka dari itu, dalam proyek ini dibuat machine learning yang dapat memprediksi temperature udara di India selama musim panas.

Business Understanding
Dataset yang digunakan pada proyek ini didapatkan dari link di bawah ini: https://www.kaggle.com/datasets/akashram/indian-summer-over-the-years

Problem Statements
Masalah pada proyek ini antara lain:
1. Berapa besar data yang akan dianalisis?
2. Berapakah MAE yang dimiliki oleh machine learning ini?
3. Berapa persen MAE terhadap nilai skala data yang tercatat pada dataset?

Goals
Tujuan dari proyek ini antara lain:
1. Seberapa besar MAE dari machine learning ini?
2. Apakah machine learning ini dapat memiliki MAE <10% dari skala data?


Solution statements
1. Solusi ini akan menggunakan model LSTM (Long short term memory network) untuk menganalisis data yang ada.

Data Understanding
Dataset ini terdiri atas satu dataset, yaitu Indian Summers - Over the years.csv. Dataset tersebut memiliki 13650 data dengan 20 kolom antara lain:
1. City : Nama kota
2. Date : Tanggal input data
3. tempmax : Temperatur tertinggi di hari tersebut
4. tempmin : Temperatur terrendah di hari tersebut
5. temp : temperatur rata-rata harian
6. feelslikemax : Temperatur yang dirasakan para warga secara subjektif pada saat temperatur tertinggi harian
7. feelslikemin : Temperatur yang dirasakan para warga secara subjektif pada saat temperatur terrendah harian
8. dew :
9. humidity : kelembaban udara
10. windspeed : kecepatan angin
11. winddir :arah angin dalam derajat
12. sealevelpressure : tekanan udara di daerah permukaan air laut
13. cloudcover : tutupan awan
14. visibility : keterlihatan/jarak pandang
15. sunrise : waktu matahari terbit
16. sunset :waktu matahari terbenam
17. moonphase : fase bulan
18. condition : kondisi cuaca dan langit
19. description : deskripsi cuaca

Data Preparation


Modeling

Evaluation

---Ini adalah bagian akhir laporan---
