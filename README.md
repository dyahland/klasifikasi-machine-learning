# klasifikasi-machine-learning

SUMMARY

Perusahaan PT Bank Indonesia Jaya ingin mengembangkan sektor perbankan mereka di bidang deposito berjangka. Hal ini dikarenakan, ketika seorang nasabah memilih produk deposito berjangka, mereka akan menyimpan uang dalam jangka waktu yang lama dengan jumlah uang yang disetorkan konstan. Uang tersebut akan digunakan oleh bank untuk berinvestasi dalam produk keuangan dengan harapan mendapatkan keuntungan lebih tinggi. Namun, tidak semua nasabah yang dimiliki oleh PT Bank Indonesia Jaya memiliki potensi untuk mengambil deposito berjangka. Oleh karena itu, peran data science sangat diperlukan untuk mengidentifikasi nasabah yang memiliki peluang lebih tinggi untuk berlangganan deposito berjangka dan memfokuskan upaya pemasaran pada klien-klien tersebut.               

TARGET

- 1: Nasabah yang akan mengambil produk deposito berjangka
- 0: Nasabah tidak mengambil produk deposito berjangka

- FP: nasabah yang tidak mengambil deposito berjangka diprediksi mengambil deposito berjangka --> membuang-buang waktu untuk menjelaskan karena nasabah tersebut tidak tertarik untuk mengambil produk keuangan tersebut
- FN: nasabah yang akan mengambil deposito berjangka diprediksi tidak akan mengambil deposito berjangka --> bank akan merugi karena akan kehilangan nasabah yang akan menabung secara konstan karena ketidaktauan informasi tersebut

METRIC

Dalam permasalahan bisnis PT Bank Indonesia Jaya, metrik yang sesuai adalah **F2 score**

Alasannya metrik ini memberikan lebih banyak bobot pada recall daripada presisi, sehingga lebih sensitif terhadap false negative. Dengan menggunakan F2 score, akan menekankan pentingnya mengidentifikasi nasabah yang akan mengambil deposito berjangka secara akurat untuk menghindari kerugian bagi bank.

PROBLEM

Bank memiliki ribuan bahkan puluhan data nasabah yang terdeftar, ketika pihak bank ingin menawarkan salah satu produk keuangan mereka kepada nasabah akan sangat tidak efektif jika harus menghubungi seluruh nasabah tersebut, dikarenakan nasabah tersebut belum tentu akan mau mengambil produk keuangan yang sedang ditawarkan.

GOALS

Dari permasalahan yang ada tersebut, pihak bank ingin mengefisienkan waktu pihak marketing ketika ingin menawarkan produk keuangan, karena waktunya akan singkat dan dapat mengenai target marketing dengan tepat sasaran dengan  mengidentiikasi nasabah yang tidak dan memiliki potensi untuk mengambil deposito berjangka.

Analytic Approach

- Yang akan dilakukan adalah menganalisis data dan menemukan pola pada machine learning berbasis klasifikasi untuk membedakan nasabah mana yang akan berpotensi mengambil deposito berjangka dan mana yang tidak, sehingga nasabah lama dan nasabah baru dapat diidentifikasi dengan mudah.
