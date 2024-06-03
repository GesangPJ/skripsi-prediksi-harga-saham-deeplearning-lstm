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
    - Anvil App For Front-End or GUI [optional]

### PARAMETERS
- N_STEPS :[int] Menentukan berapa banyak data saham yang akan digunakan (dalam hari perdagangan)
- LOOKUP_STEP: [int] Step Pencarian, 1 = besok hari
- SCALE : [Boolean] Menentukan data diskalakan atau tidak
- SHUFFLE : [Boolean] Menentukan data diacak atau tidak
- SPLIT_BY_DATE : [Boolean] Menentukan data latih/test dipisah berdasarkan tanggal atau tidak
- TEST_SIZE : [Double] Rasio data yang diambil untuk tes, format dalam persen
- FEATURE_COLUMNS : [Array] Kolom apa saja yang digunakan
- N_LAYERS : [int] Menentukan berapa layer yang digunakan (state dan hidden)
- CELL : [String] Menentukan CELL apa yang digunakan
- UNITS : [int] Menentukan berapa banyak Neurons
- DROPOUT : [Double] Maksimum rasio dropout dalam persen
- BIDIRECTIONAL : [Boolean] Menentukan LSTM bidirectional atau tidak
- LOSS : [String] Menentukan Fitur LOSS
- OPTIMIZER : [String] Menentukan Fitur Optimizer
- BATCH_SIZE : [int] Menentukan ukuran BATCH_SIZE untuk training
- EPOCHS : [int] Menentukan berapa kali data dilatih




<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
