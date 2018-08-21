# The Clean Coder
## Chapter 6
## Practicing

### Content:
* [SOME BACKGROUND ON PRACTICING](#some-background-on-practicing)
   * [Twenty-Two Zeros](#twenty-two-zeros)
   * [Turnaround Time](#turnaround-time)
* [THE CODING DOJO](#the-coding-dojo)
   * [Kata](#kata)
   * [Wasa](#wasa)
   * [Randori](#randori)
* [BROADENING YOUR EXPERIENCE](#broadening-your-experience)
   * [Open Source](#open-source)
   * [Practice Ethics](#practice-ethics)
* [CONCLUSION](#conclusion)

Chapter ini menginformasikan cara - cara bagaimana programmer dapat melatih kemampuan mereka. Dalam urusan meningkatkan kinerja, latihan sangat penting bagi pekerja profesional. Pemain sepak bola melatih kekuatan fisiknya, pengacara melatih argumennya, dan dokter melatih kemampuan bedahnya. Dalam bidang pengembangan perangkat lunak pun latihan juga menjadi bagian penting. Semua pekerja profesional melatih keahlian mereka dengan latihan - latihan yang mempertajam kemampuan mereka. Ketika dibutuhkan performa, para profesional berlatih.

### SOME BACKGROUND ON PRACTICING
&nbsp;&nbsp;&nbsp;&nbsp;Hal yang sama juga dilakukan oleh Programmer, dimana Programmer mengasah kemampuan mereka dengan berlatih banyak bahasa Pemrograman. Meskipun begitu, banyak programmer pada umumnya tidak benar - benar berlatih. Programmer terlalu sibuk membuat program dan tidak melatih kemampuan mereka. Memang pada zaman dahulu, programmer tidak memerlukan respon yang cepat dan jari yang lincah. Pada masa tersebut juga belum ditemukan siklus pendek dari TDD sehingga kita tidak memerlukan latihan yang tepat.</br>

#### Twenty-Two Zeros
&nbsp;&nbsp;&nbsp;&nbsp;Contoh paling sederhana dari latihan dalam pengembangan perangkat lunak adalah kode “Hello, World!”. Hampir semua programmer menggunakan “Hello, World!” sebagai latihan pertamanya ketika mencoba bahasa baru. Meskipun program tersebut dapat dikategorikan sebagai program latihan, programmer tidak benar-benar membuat latihan sebagai rutinitasnya. Mungkin itu dikarenakan waktu programmer-programmer terdahulu telah habis digunakan untuk menunggu hasil compile dan melakukan debugging.

&nbsp;&nbsp;&nbsp;&nbsp;Tetapi banyak sekali hal yang sudah berubah di saat ini. Sebelumnya, spesifikasi komputer sangat rendah jika dibandingkan dengan spesifikasi komputer saat ini. Perbandingannya bisa mencapat 10<sup>22</sup> kali. Angka tersebut merupakan angka yang sangat besar.

&nbsp;&nbsp;&nbsp;&nbsp;Dengan spesifikasi demikian, semakin banyak bahasa pemrograman yang lebih baik beserta alat - alat bantu yang ada. Tetapi dasar dari pengkodean tidak berubah banyak. Kode yang ada pada tahun 2010 masih dapat di mengerti oleh programmer dari 1960an. Cetakan yang kita manipulasi tidak berubah banyak dalam empat dekade ini.</br>

#### Turnaround Time
&nbsp;&nbsp;&nbsp;&nbsp;Dalam perkembangannya, komputer sekarang sudah 10<sup>22</sup> kali lebih baik dari komputer generasi pertama. Pada tahun 60an, programmer harus menunggu satu atau dua hari untuk menunggu hasil kompilasi. Di tahun 70an kecepatan kompilasi meningkat, program dengan 50.000 baris membutuhkan waktu build sebesar 45 menit. Kecepatan kompilasi terus meningkat hingga sekarang program java beserta unit testnya dengan baris sebanyak 64.000 membutuhkan waktu kurang dari 4 menit. Cepatnya waktu kompilasi membuat programmer juga harus dapat memecahkan masalah dan mengambil keputusan dengan cepat.
  
&nbsp;&nbsp;&nbsp;&nbsp;Melakukan apapun dengan cepat membutuhkan banyak latihan. Ambil pertandingan Taekwondo sebagai contoh. Masing-masing petarung harus mampu menebak apa yang akan dilakukan lawannya dalam waktu milisekon. Akan sulit untuk melakukan analisa mendalam untuk memilih respon yang terbaik terhadap serangan lawan. Dalam waktu secepat itu, tubuh bereaksi secara otomatis.
&nbsp;&nbsp;&nbsp;&nbsp;Supaya tubuh dapat menghasilkan reaksi yang tepat dibutuhkan latihan. Dalam kasus pengembangan perangkat lunak, programmer berlatih dengan cara mengulang-ulang suatu masalah dan penyelesaiannya sehingga dapat mengetahuinya secara di luar kepala. </br>

### THE CODING DOJO
&nbsp;&nbsp;&nbsp;&nbsp;Pada tahun 2005, penulis menghadiri konfrensi XP2005 di Sheffield, Inggris. Ia mengikuti sesi yang bernama <i>Coding Dojo</i>. Dalam sesi itu, instruktur mengajak semua peserta live code bersama-sama untuk membuat <i>Game of Life</i> dari Conway. Itulah yang disebut dengan ‘Kata’.

&nbsp;&nbsp;&nbsp;&nbsp;Sejak itu, banyak programmer yang mengadopsi mataphor dari seni bela diri untuk sesi latihannya. Sesekali beberapa programmer akan berkumpul di <i>Dojo</i> dan berlatih bersama, mirip seperti yang dilakukan seniman bela diri. Di saat lain, programmer juga berlatih sendirian, juga mirip seperti yang dilakukan seniman bela diri.

Terdapat berbagai kegiatan yang dilakukan di <i>Dojo</i>, diantaranya :

#### Kata
&nbsp;&nbsp;&nbsp;&nbsp;Dalam seni bela diri, sebuah <i>Kata</i> adalah set yang tepat dari gerakan koreografi yang mensimulasikan sebuah sisi pertarungan. Tujuan dari gerakan ini adalah kesempurnaan. Gerakan baik dari <i>Kata</i> sangat indah untuk dilihat.

&nbsp;&nbsp;&nbsp;&nbsp;Pada Pemrograman, <i>Kata</i> merupakan set yang tepat dari gerakan koreografi penekanan tombol dan pergerakan <i>mouse</i> yang mensimulasikan penyelesaian dari persoalan pemrograman. Dalam konteks ini, programmer di tuntut untuk mempelajari gerakan dan keputusan dalam penyelesaian permasalahan.

&nbsp;&nbsp;&nbsp;&nbsp;Tujuan dari pembelajaran sama seperti tujuan awal <i>Kata</i> yaitu kesempurnaan. Programmer diminta untuk berlatih secara berulang - ulang pemikiran dan jari - jari dalam pergerakan dan reaksi. Setelah banyak berlatih, programmer akan menemukan peningkatan efisiensi dalam pergerakan atau penyelesaian masalah.

&nbsp;&nbsp;&nbsp;&nbsp;Mempelajari beberapa set <i>Kata</i> merupakan cara yang bagus untuk melatih disiplin seperti TDD dan CI. Dan yang paling penting, <i>Kata</i> merupakan pembelajaran yang baik untuk melatih alam bawah sadar dengan persoalan/solusi yang umum ditemukan sehingga programmer dapat dengan mudah menyelesaikan persoalan yang sebenarnya dalam dunia nyata.</br>

#### Wasa
&nbsp;&nbsp;&nbsp;&nbsp;<i>Wasa</i> dapat dianalogikan dengan <i>Kata</i> yang terdiri dari dua orang. Rutin yang dilakukan adalah penghafalan dan pengulangan. Satu orang bertindak sebagai penyerang dan satu orang lainnya bertindak sebagai penjaga dan peran ini akan dirotasi terus menerus.

&nbsp;&nbsp;&nbsp;&nbsp;Programmers dapat melatih <i>Wasa</i> dengan mengikuti gaya permainan <i><b>ping-pong</b></i>. Kedua pihak memilih sebuah <i>Kata</i> atau persoalan yang sederhana. Salah satu pihak membuat <i>Unit Test</i> dan pihak yang lain harus membuat <i>Unit Test</i> tersebut dapat lewat.</br>

#### Randori
&nbsp;&nbsp;&nbsp;&nbsp;<i>Randori</i> merupakan gaya bebas dalam pertarungan. Dalam pemrograman, kelompok membuat beberapa jenis skenario dan menetapkan skenario tersebut. Kemudian salah satu orang diminta sebagai penjaga, sedangkan yang lainnya menyerang secara berurutan. Beberapa skenario juga dapat digunakan seperti dua orang penjaga dan dua orang penyerang, dan lain sebagainya.

&nbsp;&nbsp;&nbsp;&nbsp;Dalam pemrograman, salah satu cara untuk melatih <i>Randori</i> adalah dengan memproyeksikan layar ke dinding, kemudian satu orang mengkodingkan <i>Test</i>. Orang berikutnya harus membuat <i>Test</i> tersebut lewat dan kemudian membuat <i>Test</i> berikutnya.

&nbsp;&nbsp;&nbsp;&nbsp;Dengan latihan ini, programmer akan mendapatkan wawasan baru bagaimana orang lain memecahkan permasalahan tersebut. Dengan wawasan ini, programmer dapat meningkatkan kemampuan dalam penyelesaian masalah.</br>

### BROADENING YOUR EXPERIENCE
&nbsp;&nbsp;&nbsp;&nbsp;Programmer professional sering kali mendapati ketidakcukupan dari jenis - jenis permasalahan yang dihadapi. Pekerja sering kali hanya menggunakan satu bahasa, <i>platform</i>, dan <i>domain</i> dimana pekerjaan mereka gunakan. Hal ini tentu saja membuat programmer menjadi tidak siap untuk menghadapi perubahan - perubahan yang terjadi dalam industri pemrograman.</br>

#### Open Source
&nbsp;&nbsp;&nbsp;&nbsp;Salah satu cara untuk mempersiapkan hal tersebut adalah dengan berkontribusi pada proyek <i>open-source</i>. Sangat banyak proyek - proyek <i>open-source</i> yang ada, dan dari proyek tersebut, programmer dapat melatih kemampuan pemrograman mereka.</br>

#### Practice Ethics
&nbsp;&nbsp;&nbsp;&nbsp;Bukanlah pekerjaan yang membuat <i>resume</i> tetap baik. Pasien tidak membayar dokter untuk belajar ilmu kedokteran, penggemar sepakbola tidak membayar pemain untuk berlatih di lapangan dan perusahaan tidak membayar programmer untuk berlatih. 

&nbsp;&nbsp;&nbsp;&nbsp;Programmer sendiri yang harus meluangkan waktu untuk mempelajari hal - hal baru. Jangan hanya menggunakan satu bahasa maupun <i>platforms</i>, pelajari bahasa - bahasa lain untuk meningkatkan terus kemampuan.</br>

### CONCLUSION
&nbsp;&nbsp;&nbsp;&nbsp;Bagaimanapun juga, semua professional tetap berlatih. Mereka melakukan ini karena mereka peduli akan pekerjaan terbaik yang dapat mereka lakukan. Mereka mengatur waktu sendiri untuk berlatih karena mereka sadar itu merupakan tanggung jawab mereka, bukan perusahaan ataupun instansi lainnya. Melatih diri bukan untuk agar diri sendiri mendapatkan bayaran, tetapi untuk kedepannya bayaran yang lebih tinggi lagi.</br>
