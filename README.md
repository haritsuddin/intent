
# Intent
Intent adalah mekanisme untuk melakukan sebuah action dan komunikasi antar komponen aplikasi misal activity, services, dan broadcast receiver. Ada tiga penggunaan umum intent dalam aplikasi Android yaitu :

 Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
 
 Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task).
 
 Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh sistem Android untuk event booting tersebut.
 
# Intent dibagi menjadi 2 yaitu
 Intent Explicit yang berfungsi untuk mengaktifkan komponen-komponen dalam satu aplikasi yang sama. Misalnya seperti : Berpindah Activity.
 
 Intent Implisit yang berfungsi untuk memanggil fungsi activity yang sudah ada di fungsi internal android seperti : Dial Number, dan lainnya.
