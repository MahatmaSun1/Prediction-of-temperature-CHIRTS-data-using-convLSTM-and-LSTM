# Prediction-of-temperature-CHIRTS-data-using-convLSTM-and-LSTM
Prediction of temperature CHIRTS data using convLSTM and LSTM

# Proyek-Skripsi

### 1. Preprosesing data
- File mentahan "TEXT.CSV" berisi 9462 titik (baris) dengan 408 Bulan (Kolom)

- Banyak Cell yang bersisi "NA" menandakan bahwa pada titik itu adalah lautan yang tidak di ukur suhunya

- Menghilangkan Cell yang bernilai "NA"

- Digunakan library Pandas dan Numpy

- Ouput dengan nama file "Text_No_Na.csv"

- Kemudian dijumlah setiap bulan dan dirata2, Disimpan pada "File3.csv"

- Setiap data dibuatkan indeks bulanan dengan format "bulan-tahun", Disimpan pada "file1.csv"

### 2. LSTM
- Install Statsmodel
> pip install statsmodels 0.10.2
- Install Keras, sklearn, matplotlib
> pip install keras, sklearn, matplotlib
- Terdapat 2 program didalam folder
    - Program LSTM data average
        - Dilakukan preprosesing data dengan menghilangkan kolom data dan urutan
        - Import librari
        - Pembuatan Model
        - Training data
        - Validasi
        - Prediksi
    - Program LSTM data Sum
        - Dilakukan preprosesing data dengan menghilangkan kolom average dan urutan
        - Import librari
        - Pembuatan Model
        - Training data
        - Validasi
        - Prediksi
- Model di save dalam format "h5"
- Terdapat Program Load Model
- Model yang paling baik saat ini adalah menggunakan 2 layer dengan 200 neuron dan 100 neuron


cuda_10.0.130_411.31_win10

pip install numpy matplotlib pandas statsmodels sklearn scikit-image jupyter notebook

python versio 3.7.3


conda install keras

