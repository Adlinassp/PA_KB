# PA_KB
<div align="center">
    <h1>PROYEK AKHIR<br><b>Garbage Classification 🗑️</b><br><b>Kecerdasan Buatan</b></h1><br>
    <div>
        <a>
            <img src="Images/unmul.png" height="150">
        </a>
        <!-- <p><h2>Presented for :</h2></p>
        <a>
            <img src="Images/ascii.png" height="100">
        </a>
        <a>
            <img src="Images/labif.png" alt="unmul" height="100">
        </a><br><br> -->
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

#### - Rezky Nur Sya'ban / 22109106009
<!-- [![raymond](https://github.com/kmyk/online-judge-template-generator/workflows/test/badge.svg)](https://github.com/Raymond211101) -->
- Sebagai Ketua Kelompok
- Sebagai yang membuat dan mengatur bagian Evaluasi 🗃️

#### - Andi Nur Fadilah / 2109106015
<!-- [![wendra](https://github.com/kmyk/online-judge-template-generator/workflows/test/badge.svg)](https://github.com/wendra08) -->
- Sebagai yang membuat dan mengatur Data Collecting 🗂️, dan Data Visualization and Data Analyst 📊 

#### - Adlina Safa Sephia Putri / 2109106021
<!-- [![sukoshi2](https://github.com/kmyk/online-judge-template-generator/workflows/test/badge.svg)](https://github.com/Sukoshi2) -->
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
- Mengimport Library yang dibutuhkan <br>

- Data Collecting <br>
A. Train <br>
B. Validation <br>
C. Test <br>
<br>

- Data Preprocessing <br>
A. Augmentasi <br>
<br>

- Data Analisis dan Visualisasi <br>
A. Visualisasi Dataset<br>
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

- Save Model
