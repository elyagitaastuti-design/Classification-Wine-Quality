# Classification-Wine-Quality
Data Wine Quality (Kualitas Anggur) adalah catatan hasil uji laboratorium dari berbagai sampel anggur (wine). Dari data (data_training.csv) secara spesifik berisi. Fitur (Input) 11 variabel kimia dan fisik yang diukur dari setiap sampel wine. Ini adalah "petunjuk" yang Anda gunakan untuk menebak kualitas. Fitur-fitur tersebut meliputi:
Keasaman: fixed acidity, volatile acidity, citric acid, pH
Kemanisan: residual sugar
Lain-lain: chlorides (kadar garam), sulphates (sulfat)
Pengawet: free sulfur dioxide, total sulfur dioxide
Sifat Fisik: density (kepadatan) dan alcohol (kadar alkohol)
Identifier: Kolom Id yang merupakan nomor pengenal unik untuk setiap baris/sampel.
Target (Output): Kolom quality (kualitas). Ini adalah skor (misalnya 5, 6, 7, dst.) yang diberikan kepada wine tersebut, kemungkinan besar oleh panelis ahli pencicip anggur.

Dalam proyek Anda, data ini digunakan untuk skenario Machine Learning Klasifikasi. data_training.csv (Data Historis) data yang digunakan sebagai pelatihan model yang memiliki 857 sampel wine di mana Anda sudah tahu hasil tes lab-nya (fitur) dan skor kualitasnya (target). data_testing.csv (Data Baru) adalah data uji yang memiliki 286 sampel wine baru, tetapi Anda tidak tahu skor kualitasnya. Model seperit Random Forest adalah "mesin" yang  dilatih menggunakan data training untuk mempelajari pola-pola rumit (misalnya, "jika alcohol tinggi dan volatile acidity rendah, kualitasnya cenderung 7").

Tujuan utama dari proyek klasifikasi ini adalah untuk membangun sebuah model prediktif yang dapat secara otomatis menetapkan skor quality (kualitas) ke sampel wine baru, hanya berdasarkan hasil tes kimianya.
