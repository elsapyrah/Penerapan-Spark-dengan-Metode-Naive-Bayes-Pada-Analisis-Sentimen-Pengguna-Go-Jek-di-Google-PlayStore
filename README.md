# Penerapan-Spark-dengan-Metode-Naive-Bayes-Pada-Analisis-Sentimen-Pengguna-Go-Jek-di-Google-PlayStore

# Deskripsi Proyek
Analisis sentimen adalah proses menganalisis teks digital untuk menentukan apakah nada emosional pesan tersebut positif, negatif, atau netral. Secara umum, analisis sentimen dibagi menjadi dua kategori utama, yaitu:
1. Coarse - grained sentiment analysis: Proses analisis dan klasifikasi orientasi sebuah 
dokumen secara keseluruhan.
2. Fined - grained sentiment analysis: Objek yang diklasifikasikan bukan pada level 
dokumen, melainkan pada level kalimat dalam sebuah dokumen.

Apache Spark adalah sistem pemrosesan terdistribusi sumber terbuka yang digunakan untuk beban kerja big data.

# Model
Naive Bayes Classification adalah teknik klasifikasi yang didasarkan pada Teorema Bayes dengan asumsi adanya independensi di antara prediktor. Naive Bayes Classifier memprediksi probabilitas masa depan berdasarkan pengalaman sebelumnya yang dikenal juga sebagai Teorema Bayes. Secara sederhana, klasifikasi Naive Bayes mengasumsikan bahwa keberadaan suatu fitur tertentu dalam suatu kelas tidak ergantung pada keberadaan fitur lainnya. 

# Evaluasi Model
1. K-fold Cross Validation 
K-Fold Cross Validation adalah proses pengujian  dengan  melipat  (fold)  data  menjadi bagian   set   data   dengan   jumlah   yang   sama sebanyak  K  lipatan/pecahan dan menguji model pada setiap subset.
2. Confussion Matriks 
Confusion Matrix adalah alat evaluasi yang digunakan dalam pembelajaran mesin dan 
statistik untuk menilai kinerja model klasifikasi.

# Hasil
Modelan dengan Naive Bayes diperoleh nilai akurasi sebesar 0.8861924371486057, artinya sebanyak 88% ulasan label positif dan negatif. Kemudian, pada pemodelan K-fold Cross Validation dengan k=6 diperoleh nilai akurasi sebesar 0.8868923515871916, artinya model Naive Bayes dapat menjelaskan klasifikasi dari ulasan pengguna ke dalam setiap kelas sebesar 88%. 
