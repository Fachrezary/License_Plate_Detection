
## Dekteksi Plat Nomor (Crop & Identifikasin Nomer)

    Proses pengolahan citra untuk deteksi plat nomor (crop & identifikasi nomor) melibatkan beberapa tahapan penting. Tahapan pertama adalah pra-pemrosesan, di mana gambar asli dimuat dan diperbaiki kualitasnya dengan meningkatkan kontras, kecerahan, dan mengurangi noise menggunakan filter atau operasi morfologi. Pra-pemrosesan ini penting untuk memperoleh citra yang lebih jelas dan memudahkan deteksi plat nomor.

    Selanjutnya, tahap deteksi plat nomor dilakukan. Tahap ini terdiri dari dua bagian utama, yaitu pra-pemrosesan dan segmentasi. Pra-pemrosesan melibatkan pengoptimalan citra agar sesuai dengan kebutuhan segmentasi, sedangkan segmentasi bertujuan untuk memisahkan plat nomor dari latar belakang dan objek lain dalam gambar. Metode segmentasi yang umum digunakan adalah deteksi tepi untuk mengidentifikasi kontur plat nomor atau segmentasi warna untuk memisahkan warna plat nomor dari warna latar belakang.

    Setelah deteksi plat nomor berhasil dilakukan, langkah selanjutnya adalah konversi gambar asli menjadi citra biner. Pada tahap ini, metode ambang (thresholding) digunakan untuk mengubah semua piksel menjadi hitam atau putih, dengan tujuan menyoroti objek yang lebih gelap, yaitu plat nomor, dan memisahkannya dari latar belakangnya. Citra biner ini memberikan informasi yang berguna dalam proses segmentasi dan identifikasi lebih lanjut.

    Selanjutnya, tahap konversi gambar asli menjadi citra tepi dilakukan menggunakan teknik deteksi tepi seperti operator Sobel, Canny, atau Roberts. Citra tepi ini akan menyoroti kontur dan garis pada gambar, termasuk kontur dan garis pada plat nomor yang terdeteksi. Hal ini berguna dalam memvisualisasikan bentuk dan karakteristik plat nomor yang dapat digunakan untuk pengenalan karakter.

    Terakhir, tahap crop dan identifikasi nomor dilakukan. Setelah plat nomor terdeteksi, bagian gambar asli yang hanya berisi plat nomor dapat dipotong (crop) berdasarkan informasi dari proses deteksi plat nomor. Setelah itu, karakter pada plat nomor diidentifikasi menggunakan teknik Optical Character Recognition (OCR). Metode OCR dapat mengenali pola karakter pada plat nomor, baik dengan menggunakan metode template matching, metode berbasis fitur, atau pendekatan pembelajaran mesin (machine learning).

    Dengan mengikuti tahapan-tahapan ini, output gambar yang dihasilkan akan mencakup gambar asli yang telah diperbaiki, gambar dengan plat nomor yang terdeteksi dan diisolasi, citra biner yang menyoroti plat nomor, serta citra tepi yang menyoroti kontur dan garis pada plat nomor. Output ini memberikan informasi yang berguna dalam visualisasi dan analisis lebih lanjut terhadap proses deteksi plat nomor.
    
## tahapan cara menyelesaikan projek

    Berikut adalah tahapan rinci tentang cara menyelesaikan proyek deteksi plat nomor (crop & identifikasi nomor) dan menghasilkan output gambar berisi gambar asli, plat yang terdeteksi, binary image, dan edges image:

    Pertama-tama, dalam tahap pra-pemrosesan, gambar asli dimuat dari sumber dan dilakukan serangkaian langkah pra-pemrosesan untuk meningkatkan kualitas citra dan mengurangi noise. Ini termasuk peningkatan kontras dan kecerahan untuk memperjelas kontur dan detail pada gambar, serta pengurangan noise menggunakan filter atau operasi morfologi untuk menghilangkan gangguan yang tidak relevan.

    Setelah itu, tahap deteksi plat nomor dimulai dengan menggunakan teknik segmentasi. Metode deteksi tepi dapat digunakan untuk mengidentifikasi kontur plat nomor, yang akan memisahkan plat nomor dari latar belakang dan objek lain dalam gambar. Selain itu, teknik segmentasi warna juga bisa diterapkan untuk memisahkan warna plat nomor dari warna latar belakang. Hasil dari tahap ini adalah gambar plat nomor yang terisolasi.

    Selanjutnya, gambar asli dikonversi menjadi citra biner menggunakan metode ambang (thresholding). Citra biner ini akan memiliki piksel yang menjadi hitam atau putih, di mana plat nomor akan menjadi objek yang lebih gelap daripada latar belakang. Ini membantu dalam proses segmentasi dan identifikasi lebih lanjut.

    Selama tahap deteksi tepi, gambar asli juga dikonversi menjadi citra tepi menggunakan teknik deteksi tepi seperti operator Sobel, Canny, atau Roberts. Citra tepi ini akan menyoroti kontur dan garis pada gambar, termasuk kontur dari plat nomor yang terdeteksi. Dengan demikian, plat nomor akan muncul sebagai garis atau kontur yang terpisah dari latar belakang dalam citra tepi.

    Terakhir, menggunakan informasi dari tahap OCR yang dilakukan pada plat nomor terdeteksi, bagian plat nomor pada gambar asli dapat dipotong atau dikrop. Hal ini akan menghasilkan gambar yang hanya berisi plat nomor dan karakter yang berhasil diidentifikasi oleh OCR.

    Dengan mengikuti tahapan-tahapan tersebut, output dari proyek ini akan mencakup gambar asli yang telah diperbaiki secara pra-pemrosesan, gambar plat nomor yang terdeteksi dan diisolasi, citra biner yang menyoroti plat nomor, serta citra tepi yang menyoroti kontur dan garis pada gambar. Hasil akhirnya adalah gambar asli yang dipotong hanya berisi plat nomor dan karakter yang teridentifikasi.
    Dalam proyek ini, Anda bisa menampilkan output gambar dalam beberapa jendela atau memadukan ke dalam satu gambar dengan beberapa area yang berbeda menunjukkan hasil dari masing-masing tahap. Dengan cara ini, Anda dapat memvisualisasikan dan memahami proses deteksi plat nomor secara lebih baik dan melihat hasil setiap tahap secara bersamaan.

    Ingatlah bahwa proyek deteksi plat nomor adalah tugas yang kompleks dan bisa melibatkan beberapa algoritma dan teknik pengolahan citra yang lebih canggih untuk memastikan tingkat akurasi dan keandalan yang tinggi dalam aplikasi nyata. Penggunaan teknologi seperti kecerdasan buatan (AI) dan pembelajaran mendalam (deep learning) telah membantu meningkatkan kinerja sistem deteksi plat nomor dengan pesat.


## Jurnal pendukung
* https://journal.universitasbumigora.ac.id/index.php/bite/article/view/1952/985
* http://repository.lppm.unila.ac.id/12436/1/Electrician_FXAS.pdf
* https://www.youtube.com/watch?v=teGvW4rmOYc
* http://yuita.lecture.ub.ac.id/files/2021/12/Paper-Tugas-4-Kelompok-1.pdf
* https://pdfs.semanticscholar.org/b167/82f81a93fcedb0189c74545484850dd9d590.pdf?_gl=1*1sibd7i*_ga*MTg3NzgyMjIxNy4xNjg4NDgxNDU4*_ga_H7P4ZT52H5*MTY4ODQ4MTQ1OC4xLjAuMTY4ODQ4MTQ2MC41OC4wLjA.
* https://ejournal.bsi.ac.id/ejurnal/index.php/ji/article/view/7997/pdf_1