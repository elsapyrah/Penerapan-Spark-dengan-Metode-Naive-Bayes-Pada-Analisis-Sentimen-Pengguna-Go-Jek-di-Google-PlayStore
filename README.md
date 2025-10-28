# Penerapan-Spark-dengan-Metode-Naive-Bayes-Pada-Analisis-Sentimen-Pengguna-Go-Jek-di-Google-PlayStore

# Deskripsi Proyek
Analisis sentimen adalah proses menganalisis teks digital untuk menentukan apakah nada emosional 
pesan tersebut positif, negatif, atau netral. Naive Bayes adalah algoritma probabilistik yang didasarkan pada Teorema Bayes dengan asumsi bahwa fitur-fitur dalam data bersifat independen satu sama lain. Apache Spark adalah sistem pemrosesan terdistribusi sumber terbuka yang digunakan untuk beban kerja big data.

# Evaluasi Model
1. K-fold Cross Validation 
K-Fold Cross Validation adalah proses pengujian  dengan  melipat  (fold)  data  menjadi bagian   set   data   dengan   jumlah   yang   sama sebanyak  K  lipatan/pecahan dan menguji model pada setiap subset.
2. Confussion Matriks 
Confusion Matrix adalah alat evaluasi yang digunakan dalam pembelajaran mesin dan 
statistik untuk menilai kinerja model klasifikasi.

# Hasil
Modelan dengan Naive Bayes diperoleh nilai akurasi sebesar 0.8861924371486057, artinya sebanyak 88% ulasan label positif dan negatif. Kemudian, pada pemodelan K-fold Cross Validation dengan k=6 diperoleh nilai akurasi sebesar 0.8868923515871916, artinya model Naive Bayes dapat menjelaskan klasifikasi dari ulasan pengguna ke dalam setiap kelas sebesar 88%. 
