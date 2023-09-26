# RANCANG BANGUN APLIKASI PREDIKSI HARGA SAHAM MENGGUNAKAN DEEP LEARNING DENGAN ALGORITMA LONG SHORT-TERM MEMORY 

### Penulis

- Nama             : Gesang Paudra Jaya
- Program Studi    : Sistem Informasi
- Perguruan Tinggi : Universitas Banisaleh


### REQUIREMENTS

Program bisa dijalankan di 2 tempat, lokal (local training), maupun Google Colab

+ Local Training :
    - Anaconda 3 Environment with :
        - Tensorflow GPU
        - Matplotlib
        - SKLearn
        - Yahoo Finance API
        - Tensorboard
        
    - High Performance GPU

+ Google Colab : 
    - Tensorflow GPU Enabled
    - Koneksi Google Drive (Menyimpan data, hasil, logs)
    - Python Front-End services (untuk GUI input data) [optional]

### PARAMETERS
- N_STEPS :[int] Menentukan berapa banyak data saham yang akan digunakan (dalam hari perdagangan)
- LOOKUP_STEP: [int] Step Pencarian, 1 = besok hari
- SCALE : [Boolean] Menentukan data diskalakan atau tidak
- SHUFFLE : [Boolean] Menentukan data diacak atau tidak
- 
