Code ini untuk melakukan deteksi gambar menggunakan Google Collab untuk melakukan proses pengolahan dan pengenalan data menggunakan Neural Network yang ada pada tensorflow

Dengan requirement seperti berikut :
- Dataset yang dipakai haruslah dataset berikut : rockpaperscissors, atau gunakan link ini pada wget command: https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip.
- Dataset harus dibagi menjadi train set dan validation set.
- Ukuran validation set harus 40% dari total dataset (data training memiliki 1314 sampel, dan data validasi sebanyak 874 sampel).
- Harus mengimplementasikan augmentasi gambar.
- Menggunakan image data generator.
- Model harus menggunakan model sequential.
- Pelatihan model tidak melebihi waktu 30 menit.
- Program dikerjakan pada Google Colaboratory.
- Akurasi dari model minimal 85%.

Panduan penggunaan program sebagai berikut :
- Jalankan Baris kode secara berurutan dari bawah sampai akhir pada google collab
- Upload gambar tangan yang sedang membentuk salah satu dari ketiga simbol (batu, gunting, kertas)
- Program akan mengenali simbol tangan tersebut
