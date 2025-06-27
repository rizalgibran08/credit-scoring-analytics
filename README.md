# **Credit Scoring Analytics**

## 🗂️ Business Understanding
Finance Merdeka merupakan sebuah perusahaan teknologi baru yang bergerak di bidang keuangan. Ia menyediakan berbagai solusi keuangan berbasis teknologi untuk memberdayakan individu dan pelaku usaha. Walaupun menyediakan berbagai solusi keuangan berbasis teknologi, terdapat beberapa tahapan dalam layanan tersebut yang dilakukan secara manual. Salah satu tahapan tersebut ialah pemeriksaan risiko kredit ketika individu dan pelaku usaha mengajukan pinjaman. Tahapan ini sepenuhnya dilakukan secara manual oleh tim Risk Analytics Analyst. Tahapan ini tentunya memakan banyak waktu dan sangat tidak efisien. Oleh karena itu, Finance Merdeka berupaya untuk mengoptimalkan tahapan tersebut.

## 📌 Cakupan Proyek
Untuk menjawab permasalahan bisnis tersebut, kita akan menggunakan data yang telah dikumpulkan untuk mengembangkan sebuah sistem berbasis machine learning untuk memprediksi risiko kredit dari seorang pelanggan.

Pada proses pengembangannya, kita akan bereksperimen dengan berbagai pendekatan atau algoritma machine learning serta membandingkannya untuk memperoleh model dengan performa terbaik.

Selain itu, kita juga akan mengembangkan sebuah prototipe sederhana dari sistem tersebut. Berikut merupakan gambaran umum dari sistem yang akan kita kembangkan.

## Persiapan
1. **Menyiapkan data**

   Dataset dari tautan berikut: [credit score classification](https://www.kaggle.com/datasets/parisrohan/credit-score-classification).
2. **Menyiapkan environment proyek**
   
   a. **Membuat virtual environment menggunakan conda**

      Apabila menginstal Python melalui Anaconda ataupun miniconda, Anda dapat menggunakan conda sebagai package manager dan environment management system. Berikut merupakan tahapan dalam membuat virtual environment menggunakan conda.
   1. Buka terminal atau PowerShell.
   2. Jalankan perintah berikut.
      ```
      conda create --name credit_scoring python=3.9
      ```
   3. Aktifkan virtual environment dengan menjalankan perintah berikut.
      ```
      conda activate credit_scoring
      ```
   4. Instal semua library yang dibutuhkan menggunakan perintah berikut.
      ```
      pip install numpy pandas scipy matplotlib seaborn jupyter sqlalchemy scikit-learn==1.2.2 joblib==1.3.1 streamlit==1.24.0
      ```
   6. Buka jupyter-notebook dengan menjalankan perintah berikut.
      ```
      jupyter-notebook .
      ```
   8. Buat sebuah folder baru bernama proyek_customer_segmentation. Folder tersebut akan menjadi directory utama dalam proyek ini. 

   b. **Membuat virtual environment menggunakan pipenv**

   Jika menginstal python melalui official home, Anda dapat menggunakan pip sebagai package manager dan pipenv sebagai environment management. Berikut merupakan tahapan dalam membuat virtual environment menggunakan pipenv.
   
   1. Buka terminal atau PowerShell.
   2. Buat sebuah folder baru bernama proyek_credit_scoring dengan menjalankan perintah berikut.
      ```
      mkdir proyek_credit_scoring
      ```
   3. Pindah ke folder terbaru tersebut menggunakan perintah berikut.
      ```
      cd proyek_credit_scoring
      ```
   4. Buat sebuah virtual environment dengan menjalankan perintah berikut.
      ```
      pipenv install
      ```
   5. Aktifkan virtual environment dengan menjalankan perintah berikut.
      ```
      pipenv shell
      ```
   6. Instal semua library yang dibutuhkan menggunakan perintah berikut.
      ```
      pip install numpy pandas scipy matplotlib seaborn jupyter sqlalchemy scikit-learn==1.2.2 joblib==1.3.1 streamlit==1.24.0 
      ```
   7. Buka jupyter-notebook dengan menjalankan perintah berikut.
      ```
      jupyter-notebook .
      ```
