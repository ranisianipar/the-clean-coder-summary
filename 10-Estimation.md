The Clean Coder
Chapter 10
Estimation

Content:
What is an Estimate?
A Commitment
An Estimate
Implied Commitments
PERT
Estimating Tasks
Wideband Delphi
Flying Fingers
Planning Poker
Affinity Estimation
Trivariate Estimates
The Law of Large Numbers
Conclusion

What is an Estimate?
A Commitment
	Komitmen adalah suatu hal yang harus dicapai. Jika kita berkomitmen bahwa suatu pekerjaan harus selesai pada tanggal yang telah ditentukan, maka pekerjaan tersebut harus selesai walaupun itu berarti bekerja lebih lama. Profesional biasanya tidak akan membuat komitmen kecuali mereka tahu hal tersebut dapat dicapai.
An Estimate
	Estimasi dapat diartikan sebagai dugaan. Kita dapat mengestimasi suatu pekerjaan akan selesai pada tanggal tertentu. Tetapi jika pekerjaan tersebut tidak dapat diselesaikan pada tanggal yang telah ditentukan, hal tersebut tidak menjadi masalah karena jika kita mengestimasi suatu pekerjaan, itu berarti kita tidak tahu pasti berapa lama sebuah pekerjaan akan memakan waktu.
	Estimasi sebenarnya adalah probability distribution bukan sebuah angka pasti. Karena estimasi merupakan dugaan yang dapat berubah tergantung suatu kondisi.
Implied Commitments
	Implied Commitments atau komitmen tersirat merupakan sebuah komitmen yang kita buat tanpa kita sadari. Hal tersebut bisa terjadi saat kita menggunakan kata “try” atau “mencoba” karena jika kita bersedia untuk mencoba berarti kita telah berkomitmen untuk menyelesaikannya pada waktu yang telah ditentukan. Profesional biasanya akan sangat berhati-hati agar tidak membuat komitmen tersirat dengan mengkomunikasikan estimasi mereka sejelas mungkin sehingga sang manajer dapat membuat rencana yang sesuai.
PERT (Program Evaluation and Review Technique)
	PERT dibuat pada tahun 1957 untuk membantu proyek kapal selam Polaris milik U.S Navy. Salah satu elemen dari PERT adalah bagaimana perkiraan dikalkulasikan. Skema ini menyediakan cara yang sangat sederhana namun juga sangat efektif untuk mengubah perkiraan menjadi distribusi probabilitas yang sesuai untuk manajer.
	Saat anda memperkirakan suatu task, anda menyediakan tiga angka yang disebut trivariate analysis :
O : Optimistic Estimate. Angka ini sangat optimis, anda hanya dapat menyelesaikan task dengan cepat jika semuanya berjalan dengan baik. Dan agar perhitungan dapat dilakukan, angka ini harus kurang dari 1%.
N : Nominal Estimate. Ini merupakan perkiraan dengan peluang sukses terbesar.
P : Pessimistic Estimate. Sangat pesimis serta harus mencakup semuanya kecuali angin topan, perang nuklir, lubang hitam, dan bencana lainnya. Dan juga, perhitungan hanya dapat dilakukan jika angka ini kurang dari 1%.

μ adalah durasi tugas yang diharapkan

σ adalah standar deviasi dari distribusi probabilitas tugas tersebut. Ini adalah ukuran seberapa tidak pastinya tugas tersebut.

Untuk setiap urutan tugas, durasi yang diharapkan dari urutan tersebut adalah jumlah dari semua jangka waktu yang diharapkan dari tugas dalam urutan tersebut.

Standar deviasi dari urutan suatu tugas adalah akar kuadrat dari jumlah kuadrat dari standar deviasi tugas tersebut.
Estimating Tasks
Wideband Delphi
	Pada tahun 1970-an Barry Boehm memperkenalkan sebuah teknik estimasi yang dinamakan “Wideband Delphi”. Strategi teknik ini cukup sederhana. Sekelompok orang berkumpul, memulai diskusi, mengestimasi sebuah tugas, dan mengulang diskusi dan estimasi sampai mendapatkan sebuah kesepakatan.
	Ada banyak variasi yang ditemukan dalam beberapa tahun. Beberapa diantaranya formal, beberapa tidak formal; tetapi semuanya mempunyai sebuah kesamaan: konsensus.
Flying Fingers
	Semua orang duduk mengelilingi meja. Tugas didiskusikan secara satu persatu mulai dari tugas itu menyangkut apa, apa yang akan mempersulitnya, dan bagaimana hasil diskusi tersebut akan diimplementasikan. Lalu peserta akan meletakkan tangan mereka dibawah meja dan mengacungkan 0 hingga 5 jari berdasarkan pemikiran mereka berapa lama tugas tersebut akan memakan waktu. Moderator lalu akan menghitung 1-2-3 dan semua peserta mengangkat tangan mereka secara bersamaan.
	Jika semua setuju, maka diskusi akan dilanjutkan ke tugas selanjutnya. Tetapi jika tidak maka diskusi akan dilanjutkan pada tugas yang sama hingga mencapai persetujuan.
Planning Poker
	Pada tahun 2002 James Grenning menuliskan sebuah paper yang mendeskripsikan “Planning Poker”. Variasi “Wideband Delphi” ini kemudian menjadi begitu populer. Ide dari variasi ini begitu sederhana, yakni peserta diberikan beberapa kartu yang berkisar antara 0-5. Setelah itu peserta akan memilih tugas dan mendiskusikannya. Pada akhir diskusi, peserta diminta untuk memilih sebuah kartu berdasarkan estimasi mereka berapa banyak waktu yang diperlukan untuk menyelesaikan tugas tersebut. Moderator kemudian akan memberi arahan untuk menunjukkan kartu yang dipilih. Proses selanjutnya sama dengan konsep “Flying Fingers”.

Affinity Estimation
	Merupakan sebuah variasi unik dari Wideband Delphi. Semua tugas ditulis ke kartu tanpa menunjukkan perkiraan apapun. Tim estimasi berdiri di sekitar meja atau dinding dengan kartu tersebar secara acak. Anggota tim tidak berbicara, mereka mulai mengurutkan kartu satu sama lain secara lain, Tugas yang membutuhkan waktu lebih lama dipindahkan ke kanan dan yang lebih kecil dipindah ke kiri. Setiap anggota tim dapat memindahkan kartu apapun kapan saja, meski telah dipindahkan oleh anggota lain. Setelah pengurutan kartu berakhir, diskusi dapat dimulai. Ketidaksepakatan tentang pengurutan kartu dieksplorasi. Langkah selanjutnya adalah menggambar garis antara kartu yang mewakili ukuran ember, baik dalam hitungan hari, minggu, maupun titik. Biasanya digunakan 5 ember dalam urutan Fibonacci (1, 2, 3, 5, 8).

Trivariate Estimates
	Teknik-teknik delphi wideband ini bagus untuk memilih satu perkiraan untuk suatu tugas. Namun, sebagian besar dari kami menginginkan tiga perkiraan agar dapat dibuat menjadi distribusi probabilitas. Nilai optimis dan pesimis juga dapat dihasilkan dengan cepat menggunakan salah satu teknik wideband delphi. Contohnya jika anda menggunakan perencanaan poker, anda hanya meminta untuk memegang kartu untuk perkiraan pesimis mereka dan kemudian mengambil yang tertinggi. Untuk perkiraan optimis sama, namun yang diambil adalah yang terendah.

The Law of Large Numbers
	Estimasi biasanya penuh dengan kesalahan. Salah satu cara untuk mengatasi hal tersebut adalah dengan “Law of Large Numbers”. Prinsip utamanya adalah memecah tugas yang besar menjadi beberapa bagian lalu estimasi bagian-bagian tersebut. Mengestimasi bagian-bagian yang lebih kecil akan lebih akurat dibandingkan dengan mengestimasi tugas yang besar dan rumit.
Conclusion
	Pengembang software profesional tahu cara untuk menyediakan bisnis dengan perkiraan yang praktis. Mereka tidak membuat janji yang tidak bisa mereka tepati, dan juga mereka tidak membuat komitmen yang tidak mereka yakini dapat mereka lakukan. Saat para profesional membuat komitmen, mereka memberikan angka-angka sulit, lalu mereka membuatnya. Tetapi dalam banyak kasus, mereka tidak membuat komitmmen seperti itu namun mereka memberikan perkiraan probabilistik yang menggambarkan waktu penyelesaian yang diharapkan. Teknik yang dijelaskan dalam bab ini adalah contoh dari beberapa cara yang berbeda. Ini bukan satu-satunya teknik dan juga belum tentu merupakan teknik terbaik. Mereka hanyalah teknik yang saya temukan dan bekerja baik dengan saya.
