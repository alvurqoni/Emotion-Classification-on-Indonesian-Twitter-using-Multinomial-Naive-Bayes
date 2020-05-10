# Emotion-Classification-on-Indonesian-Twitter-using-Multinomial-Na-ve-Bayes

1. Dataset
Dataset yang digunakan sebanyak 1000 tweet yang berbahasa Indonesia. Setiap tweet hanya mewakili satu
emosi saja, ada enam jenis emosi yang digunakan yaitu anger, fear, joy, dan sadness. Dataset diperoleh dari
penelitian sebelumnya yang dilakukan oleh Alif Septian Nurdianto, Angelina Prima Kurniati, Alfian Akbar tentang
klasifikasi emosi pada twitter menggunakan Multiclass Support Vector Machine. Data yang diperoleh telah di
validasi oleh responden ahli.


2. Preprocessing
a. Remove punctuation adalah tahap pembersihan data yang mengandung angka, url, mention, RT.

b. Case folding adalah tahap pengubahan kata yang mengandung huruf kapital menjadi huruf kecil.

c. Slang handling adalah tahap pengubahan kata yang tidak formal menjadi kata yang sesuai dengan EYD.

d. Negation convert adalah tahap penggabungan dua kata yang mengandung arti negasi menjadi satu kata,
misalnya “tidak mau” menjadi “tidakmau”.

e. Stopword removal adalah tahap yang dilakukan dengan cara menghilangkan kata yang tidak penting,
atau kata bantu.

f. Tokenization adalah melakukan pemecahan suatu kalimat menjadi kata per kata yang tunggal.

g. Stemming adalah mengubah kata yang memiliki imbuhan menjadi kata dasar secara kasar dengan
menghapus imbuhan yang terdiri dari awalan, akhiran, sisipan, dan kombinasi.
