#SUMMARY OF THE CLEAN CODER CHAPTER 5 (TEST DRIVEN DEVELOPMENT)
---------------------------------------------------------------

Test Driven Development atau yang lebih dikenal sebagai TDD awalnya dibuat pada tahun 1998 yang dikembangkan oleh Kent Beck. TDD adalah suatu pendekatan pengembangan sebuah software dengan membuat test terlebih dahulu. 
Pada awalnya pendekatan ini menjadi kontroversi dikalangan software engineer karena dianggap tidak masuk akal menulis test terlebih dahulu sebelum code production ditulis. Namun kontroversi ini mulai menghilang karena TDD bekerja dengan baik dan memberi efek yang signifikan bagi kalangan software engineer.

Dalam menerapkan TDD ada 3 (Tiga) hukum atau peraturan yang menjadi panduan bagi engineer yaitu :

###1. You are not allowed to write any production code until you have first written a failing unit test.
	Artinya kita tidak boleh menulis code production sebelum kita membuat sebuah unit test yang hasilnya gagal.
###2. You are not allowed to write more of a unit test than is sufficient to fail—and not compiling is failing.
	Artinya kita tidak boleh membuat unit test yang lebih banyak dari unit test yang hasilnya gagal.
###3. You are not allowed to write more production code that is sufficient to pass the currently failing unit test.
	Artinya kita tidak boleh menulis lebih banyak code production sebelum menulis code yang membuat unit test yang masih gagal menjadi berhasil

Dari panduan diatas kita dapat memahami bahwa dalam menerapkan TDD kita membuat unit test lalu kita menulis code sedikit demi sedikt untuk unit test tersebut dan begitulah proses ini berulang-ulang.

##Keuntungan Menerapkan TDD
####1. Certainty
	Dengan kita menerapkan TDD, ketika kita membuat perubahan code, dan kita telah melewati unit test maka kita dapat memastikan bahwa code tersebut tidak akan mengganggu unit lain dikarenakan kita telah membuat unit test terlebih dahulu.
####2. Defect Injection Rate
	Dengan menerapkan TDD bug di dalam code kita akan berkurang dengan signifikan sehingga jika terjadi kegagalan sistem akan mudah dilacak dan tidak mematikan sistem.
####3. Courage
	Dengan melakukan pendekatan TDD, kita lebih berani dalam melakukan perubahan code karena sudah yakin tidak akan mempengaruhi sistem atau unit lain.
####4. Documentation
	Dengan menerapkan TDD kita lebih mudah membuat dokumentasi dari sistem kita karena akan ada dokumentasi per unit dan sudah diuji.
####5. Design
	Dengan menerapkan TDD kita akan dipermudah dalam men-design jalannya unit tersebut, karena kita terlebih dahulu membuat test dari jalannya sistem tersebut, maka alur atau designnya sudah jelas, dan ketika kita menulis code, kita sudah terarah.

Dengan pendekatan TDD kita akan menjadi seorang software engineer yang professional. 


######BY : Abdi Elman D. A. Dan Samuel A. Napitupulu
----------------------------------------------------
