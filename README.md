# UTSComputerVision
## Menggunakan data emnist-letters-train.csv
Projek ini bertujuan untuk melatih komputer agar dapat mengenali huruf tulisan tangan manusia secara otomatis.
Pada projek ini digunakan metode HOG untuk mengambil ciri penting dari gambar huruf, lalu digunakan algoritma SVM untuk mengklasifikasikan huruf tersebut ke dalam kelas yang benar.

## Catatan Tambahan

True LOOCV penuh sebenarnya membutuhkan proses training yang sangat besar karena setiap data harus menjadi data testing satu kali. Dengan dataset 2600 sampel dan Grid Search parameter SVM, proses training menjadi sangat berat dan memakan waktu yang lama. Oleh karena itu pada project ini LOOCV digunakan pada training set untuk hyperparameter tuning, sedangkan 20% data testing digunakan untuk evaluasi akhir model.
