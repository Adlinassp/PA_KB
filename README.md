# PA_KB
<div align="center">
    <h1>PROYEK AKHIR<br><b>Garbage Classification 🗑️</b><br><b>Kecerdasan Buatan</b></h1><br>
    <div>
        <a>
            <img src="Images/unmul.png" height="150">
        </a>
        <div align="center">
            <p style="font-size: 18px;">
                Program Studi Informatika<br>
                Fakultas Teknik<br>
                Universitas Mulawarman
            </p>
        </div>
    </div>
</div>

<div align="center">
    <div>
        <p><h4>Disusun Oleh : </h4></p>
        <p><h4>Kelompok 7 Kelas A1 2021</h4></p>
        <div>
            <p><h3>
                Rezky Nur Sya'ban 2109106009 (Ketua)<br>
                Andi Nur Fadilah 2109106015<br>
                Adlina Safa Sephia Putri 2109106021
            </h3></p>
        </div>
    </div>
</div>
<br>
<div align="center">
<h1>JOB DESK<h1>
</div>

#### - Rezky Nur Sya'ban / 2109106009
- Sebagai Ketua Kelompok
- Sebagai yang membuat dan mengatur bagian Evaluasi 🗃️

#### - Andi Nur Fadilah / 2109106015
- Sebagai yang membuat dan mengatur Data Collecting 🗂️, dan Data Visualization and Data Analyst 📊 

#### - Adlina Safa Sephia Putri / 2109106021
- Sebagai yang membuat dan mengatur bagian bagian re-Processing ⌛ dan PModelling 🔍


## 1. Penjelasan DataSet
Link Sumber Dataset Klasifikasi Sampah yang berasal dari [kaggle](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification/code)<br> 
Link Dataset Klasifikasi Sampah yang telah diperbarui disimpan [Disini](https://drive.google.com/drive/folders/19n4_o_hunrj9GS1fPXFMMBPSwbEmhI7G?usp=sharing)<br>

Kumpulan data yang berisikan gambar berbagai jenis sampah namun kami hanya mengambil 3 jenis sampah, yaitu kaca, kertas, dan plastik. Data citra tersebut kemudian dibagi menjadi 3 kelas berdasarkan kondisinya, yaitu 'glass', 'paper', dan 'plastic' ke dalam folder yang terpisah, yakni train, test, dan val dengan perbandingan 7:1:2.

<!-- Tiap-tiap gambar berukuran 227 x 227 pixel dengan penggunaan warna RGB.  -->

<!-- Dataset dibagi menjadi berberapa Direktori atau Folder, dimana sistem akan mengenali atau klasifikasi mana gambar yang merupakan 'kaca', 'kertas', dan 'plastik'. -->

## 2. Penjelasan Project
Projek akhir ini membahas mengenai model kecerdasan buatan dalam Pemilahan sampah yang melibatkan pemisahan sampah menurut cara penanganan atau pengolahannya. Penting untuk didaur ulang karena beberapa bahan dapat didaur ulang dan yang lainnya tidak.



## 3. Table of Content
"## Table Of Content\n",<br>
    "* [Import Library](#import)\n",<br>
    "* [Data Collecting](#data-collecting)\n",<br>
    "    * [Data Split](#data-split)\n",<br>
    "    * [Memuat Dataset](#memuat-dataset)\n",<br>
    "       * [1.Train](#train)\n",<br>
            * [2.Validation](#validation)\n",<br>
            * [3.Test](#test)\n",<br>
    "* [Data Preprocessing](#data-preprocessing)\n",<br>
    "    * [A.Augmentasi](#augmentasi)\n",<br>
    "    * [B.Visualisasi Augmentasi](#visualisasi-augmentasi)\n",<br>
    "* [Data Analyst dan Visualization](#visualisasi-data)\n",<br>
    "    * [A.Meta Data](#meta-data)\n",<br>
    "    * [B.Visualisasi](#visualisasi)\n",<br>
    "       * [1.Dataset(Preview)](#preview)\n",<br>
    "       * [2.Data Training](#train-validation-test)\n",<br>
    "* [Modelling](#modelling)\n",<br>
    "    * [A.Arsitektur Model](#arsitektur-model)\n",<br>
    "    * [B.Parameter Layer](#parameter-layer)\n",<br>
    "    * [C.Konfigurasi Model](#konfigurasi-model)\n",<br>
    "       * [1.Optimasi Model](#optimasi-model)\n",<br>
    "       * [2.Callback](#callback)\n",<br>
    "    * [D.Training Model](#training-model)\n",<br>
    "* [Evaluasi](#evaluasi)\n",<br>
    "    * [A.Evaluasi Test Set](#test-set)\n",<br>
    "    * [B. Visualisasi Hasil Training (Train dan Validaton)](#accuracy)\n",<br>
    "       * [1. Membandingkan perkembangan epoch Train vs. Validation Accuracy](#train-epoch)\n",<br>
    "    * [C. Pratinjau Prediksi](#prediksi)\n",<br>
    "       * [1. Pratinjau Hasil Prediksi](#hasil-prediksi)\n",<br>
    "       * [2. Pratinjau Kesalahan Prediksi](#hasil-prediksi-salah)\n",<br>
    "* [Save Model](#save)"


- Data Collecting <br>
A. Train <br>
B. Validation <br>
C. Test <br>
<br>

- Data Preprocessing <br>
A. Augmentasi <br>
B. Visualisasi Augmentasi<br>
<br>

- Data Analisis dan Visualisasi <br>
A. Meta Data <br>
B. Visualisasi<br>
<br>

- DATA MODELLING <br>
A. Callback <br>
B. Optimasi Model <br>
C. Fitting Training Model <br>
<br>

- EVALUASI <br>
A. Membandingkan perkembangan epoch <br>
B. Pratinjau Hasil Prediksi :  <br>
  - Visualisasi Gambar yang Diprediksi Benar <br>
  - Visualisasi Gambar yang Diprediksi Salah <br>
<br>

<br>
<div align="center">
<h1>AKHIR DARI README<br><b>Garbage Classification 🗑️</b><br><b>Kecerdasan Buatan</b></h1><br>
</div>
<div align="center">
<h1>Terimakasih atas perhatiannya<br><b>Semoga bermanfaat untuk semua<h1><br>
</div>
