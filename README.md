# Machine-Learning-and-Deep-Learning
Number 1 Memprediksi Churn Status di Perbankan
a. Melengkapi kode yang diberikan, dan membuat tiga model berbeda.
b. Membandingkan ketiga model tersebut, dan rangkum model mana yang terbaik.
c. Menggunakan metode optimasi model apabila perlu (seperti hyperparameter tuning, feature selection, dll).

Number 2 Menentukan Jumlah Kluster Terbaik dari Random Data Points
a. Melengkapi kode yang diberikan.
b. Merangkum berapa banyak cluster yang terbaik untuk data yang diberikan.
c. Memvisualisasikan kluster yang berhasil dibuat.

Number 3 Memprediksi Harga Rumah dengan Multilayer Perceptron
1. Mengubah "features" dan "target" dari Numpy Array ke Pandas DataFrame
2. Memisahkan data menjadi train, validation, dan test
3. Melakukan standarisasi untuk data train, validation, dan test menggunakan StandardScaler()
4. Melakukan normalisasi untuk data train, validation, dan test menggunakan MinMaxScaler()
5. Membuat hidden layer pertama dengan 30 neuron dan ReLU sebagai activation function
6. Membuat hidden layer kedua dengan 30 neuron dan ReLU sebagai activation function
7. Menentukan jumlah epoch (iterasi)
8. Menentukan jumlah batch
9. Memberikan nama file untuk model, diakhiri dengan ekstensi .keras
10. Reload model dan lakukan prediksi dengan data baru (`x_new_A` dan `x_new_B`)

Number 4 Klasifikasi Credit Card Fraud dengan Multilayer Perceptron
Memastikan Hasil evaluasi model (dengan data test) di atas 95%.
1. Impor dataset dengan Pandas, gunakan fungsi "read_by_CPU"
2. Menghilangkan kolom ID
3. Menentukan X (features) dan Y (target), gunakan "data_gpu"
4. Pecah dataset dengan komposisi 80% train set dan 20% test set, dengan fungsi "splitCPU"
5. Melakukan hal yang sama untuk data spliting, tetapi dengan fungsi "splitGPU"
6. Aktifkan GPU (CUDA) sebagai device untuk training
7. Tentukan nilai batch
8. Mencari perbedaan hyperparameters dan parameters?
9. Menentukan hyperparameters
10. Menentukan besaran input untuk model
11. Mengetahui total "trainable parameters" sama dengan total keseluruhan parameter?
12. Melakukan fine-tuning jika akurasi masih dibawah 95%.

