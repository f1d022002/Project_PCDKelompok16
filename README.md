# Project_PCDKelompok16

Program yang dikembangkan bertujuan untuk mengklasifikasikan citra daun tan05aman anggur menjadi tiga kategori: Black Rot, Esca Black Measles, dan kondisi sehat. Proses dimulai dengan mengumpulkan citra dari dataset yang telah didapatkan, kemudian dilakukan pengolahan citra untuk mengekstraksi fitur-fitur penting. Fitur yang diekstraksi mencakup berbagai parameter tekstur seperti kontras, dissimilarity, homogenitas, energi, korelasi, entropi, dan ASM (Angular Second Moment). Setelah fitur-fitur ini diekstraksi, data tersebut diolah lebih lanjut menggunakan Principal Component Analysis (PCA) untuk mengurangi dimensi dan menghilangkan redundansi. Data yang telah diproses kemudian digunakan untuk melatih beberapa model pembelajaran mesin, yaitu K-Nearest Neighbors (KNN), Support Vector Machine (SVM), dan Random Forest. Hasil dari setiap model kemudian dievaluasi menggunakan metrik seperti akurasi, precision, recall, dan F1 score, serta ditampilkan dalam bentuk confusion matrix.


list prepro:
Segmentasi warna
Grayscale
Normalisasi
Equalisasi histogram
Gaussian blur
Sobel edge detect
