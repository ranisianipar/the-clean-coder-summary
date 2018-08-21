# The Clean Coder
## Chapter VII
## Acceptance Test

### Content:
* [Communicating Requirements](#communicating-requirements)
* [Premature Precision](#premature-precision)
   * [The Uncertainty Principle](#the-uncertainty-principle)
   * [Estimation Anxiety](#estimation-anxiety)
* [Late Ambiguity](#late-ambiguity)
* [Acceptance Test](#acceptance-test)
   * [The Definition of Done](#the-definition-of-done)
   * [Communication](#communication)
   * [Automation](#automation)
   * [Extra Work](#extra-work)
   * [Who Writes Acceptance Tests, and When?](#who-writes-acceptance-tests-and-when?)
   * [The Developers Role](#the-developers-role)
   * [The Negotiation and Passive Aggression](#the-negotiation-and-passive-aggression)
   * [Acceptance Tests and Unit Tests](#acceptance-tests-and-unit-tests)
   * [GUI and Other Complications → Testing through right interface](#gui-and-other-complications-testing-through-right-interface)
   * [Continuous Integration Stop the presses](#continuous-integration-stop-the-presses)
   * [Conclusion](#conclusion)

Berdasarkan prinsip *garbage-in/garbage-out*, peran *professional developer* adalah terlibat dalam komunikasi dan sebagai *developer* juga. Sehingga sebagai *professional developer*, harus memastikan bahwa komunikasi antara *team member* dengan *business people* akurat.



### Communicating Requirements
&nbsp;&nbsp;&nbsp;&nbsp;Masalah yang paling umum terjadi antara *programmer* dan *business* adalah *requirement*. *Business People* menyatakan apa yang mereka yakini akan membutuhkannya, sedangkan *Programmer* membuat apa yang mereka yakini sudah sesuai dengan kebutuhan *Business People*. Kenyataannya, membicarakan tentang *requirement* sangatlah susah. Hal ini dikarenakan dapat tercipta *ambiguity* antara keinginan *business people* yang hanya mengejar kesesuaian dengan *business flow* tanpa memperhatikan aspek lain (cth. jangka waktu *log file* di-*update*, bagaimana merespons *error*, dll.), dengan pemahaman seorang *developer* yang punya *background* sebagai *IT developer*.
</br>

### Premature Precision
&nbsp;&nbsp;&nbsp;&nbsp;*Business people* ingin tahu hal apa yang mereka dapat sebelum mengotorisasi suatu *project*. Di sisi lain, *developer* ingin tahu hal apa yang harus mereka beri sebelum mereka memperkirakan suatu *project*. Kedua pihak menginginkan sebuah perkiraan yang tidak bisa tercapai.

#### _The Uncertainty Principle_
&nbsp;&nbsp;&nbsp;&nbsp;*Business people* menuliskan *requirement* → diserahkan ke *developer* → *product* jadi sesuai deskripsi awal → *business people* tidak puas dan mendapat ide baru setelah melihat cara kerja → *business people* memperbaiki *requirement*. 
Apa yang dilakukan *business people* ini disebut *observer effect* atau istilah lainnya *uncertainty principle*. Semakin detail *requirement*-nya, semakin kurang relevan *requirement* yang ditulis dengan sistem yang akan dipakai.
</br>

#### _Estimation Anxiety_
&nbsp;&nbsp;&nbsp;&nbsp;*Professional Developer* sadar bahwa suatu estimasi berdasarkan *low precision requirement*, dan menyadari bahwa estimasi tersebut hanyalah sebuah perkiraan. Untuk menghadapi hal tersebut, seorang *professional developer* selalu menyertakan kemungkinan *error*, agar *business people* memahami atas ketidakpastiannya.

### Late Ambiguity
&nbsp;&nbsp;&nbsp;&nbsp;Seringkali para stakeholders berasumsi bahwa pihak yang membaca *requirement* yang mereka mau sudah paham. Memang secara konteks itu jelas, tetapi bisa berarti beda bagi *programmer* yang membacanya. Inilah konteks ambigu yang juga terjadi antara *customer* dengan *programmer*.
</br>

### Acceptance Test
&nbsp;&nbsp;&nbsp;&nbsp;Seringkali para stakeholders berasumsi bahwa pihak yang membaca *requirement* yang mereka mau sudah paham. Memang secara konteks itu jelas, tetapi bisa berarti beda bagi *programmer* yang membacanya. Inilah konteks ambigu yang juga terjadi antara *customer* dengan *programmer*.
</br>

#### _The Definition of Done_
&nbsp;&nbsp;&nbsp;&nbsp;*Acceptance test* adalah pengujian yang dibuat berdasarkan kolaborasi antara *stakeholders* dan *programmer* untuk mendefinisikan kapan sebuah *requirement* itu dianggap selesai. Definisi selesai adalah ketika seluruh kode program sudah ditulis dan lulus pengujian, serta program diterima oleh QA dan para *stakeholder*. Seorang *programmer* sebaiknya mendefinisikan *requirements* sampai pembuatan *acceptance test* yang sudah terotomasi untuk mengurangi biaya pengujian.


#### _Communication_
&nbsp;&nbsp;&nbsp;&nbsp;Tujuan pembuatan *acceptance test* untuk media komunikasi, kejelasan dan presisi. Dengan begitu, seharusnya seluruh pihak yang menyetujui *acceptance test* paham atas perilaku sistem dengan jelas. Merupakan tanggung jawab *developer* untuk bekerja sama dengan *stakeholder* dan *tester*, memastikan semua pihak mengerti sistem seperti apa yang akan dibangun.


#### _Automation_
&nbsp;&nbsp;&nbsp;&nbsp;Pengujian merupakan salah satu tahap penting dalam *software lifecycle* yang tidak bisa dihilangkan begitu saja, namun pengujian manual mampu menghabiskan banyak biaya. Karena itulah *acceptance test* harus otomatis. Biaya *acceptance test* otomatis jauh lebih murah dibanding pengujian manual. Merupakan tanggung jawab *developer* untuk memastikan pengujian otomatis bisa dilakukan. 
Saat ini terdapat banyak alat pengujian, baik *open-source* maupun komersil yang mendukung otomatisasi *acceptance test*, seperti FitNesse, Cucumber, cuke4duke, robot framework, dan Selenium. Masih banyak lagi contoh lainnya, yang memungkinkan penggunanya menciptakan pengujian otomatis spesifik agar pihak non-programmer tetap dapat membaca, mengerti bahkan menulis bahan uji.


#### _Extra Work_
&nbsp;&nbsp;&nbsp;&nbsp;Pembuatan *acceptance test* memang terlihat sebagai pekerjaan tambahan. Namun bila dilihat dari sisi lain, pembuatan pengujian ini sama dengan menspesifikan sistem, supaya *programmer* bisa tahu sejauh apa “selesai” yang harus dicapai, *stakeholder* bisa memastikan sistem yang mereka biayai sesuai dengan apa yang mereka butuhkan, serta pengujian otomatis bisa dibuat. Pengujian ini akan menghindarkan *developer* dari pengimplementasian sistem yang salah.


#### _Who Writes Acceptance Tests, and When?_
&nbsp;&nbsp;&nbsp;&nbsp;Dalam kondisi ideal, seharusnya *stakeholder* dan QA yang bekerja sama untuk menulis *acceptance test* lalu ditinjau oleh *developer* untuk mengecek konsistensi. Namun dalam kondisi riil, penulisan *acceptance test* bisa saja dilakukan oleh *business analyst*, QA atau bahkan *developer*. Bila tugas tersebut jatuh pada *developer*, harus dipastikan bahwa *developer* yang menulis pengujian berbeda dengan *developer* yang mengimplementasikan fitur yang akan diuji. 
Biasanya, *business analyst* menulis versi “happy path” pengujian, untuk mendeskripsikan bahwa fitur terkait memiliki nilai bisnis, sedangkan QA menulis versi “unhappy path” pengujian, seperti kondisi batas, kasus ujung maupun *exception*, untuk memastikan apa saja yang mungkin menyebabkan *error*. 
Sebaiknya *acceptance test* ditulis seakhir mungkin, biasanya beberapa hari sebelum sebuah fitur diimplementasi. Dalam proyek *Agile*, pengujian ditulis setelah sebuah fitur dipilih untuk *Sprint* selanjutnya. Hal ini dilakukan untuk mengikuti prinsip *late precision* yang dibahas di bagian sebelumnya.

#### _The Developers Role_
&nbsp;&nbsp;&nbsp;&nbsp;Implementasi sebuah fitur dimulai ketika *acceptance test* selesai dibuat. *Developer* mengeksekusi pengujian fitur tersebut, lalu menghubungkannya ke sistem. Setelah itu, *developer* harus memastikan seluruhnya lulus pengujian.


#### _The Negotiation and Passive Aggression_
&nbsp;&nbsp;&nbsp;&nbsp;Terdapat kemungkinan di mana pengujian yang tersedia tidak relevan saat mulai diimplementasikan, mungkin karena terlalu rumit, janggal atau terlalu banyak asumsi. Bila hal ini terjadi, dibandingkan bertindak pasif agresif dengan mengimplementasi hal yang salah dan menyalahkannya pada pembuat sistem, *developer* seharusnya bernegosiasi dengan penulis pengujian untuk memperbaiki pengujian. 


#### _Acceptance Tests and Unit Tests_
&nbsp;&nbsp;&nbsp;&nbsp;*Acceptance Tests* bukanlah *Unit Tests*. Pengujian ini dibuat dengan bentuk yang mudah dimengerti siapapun (orang-orang tanpa *background IT*). Di sisi lain, *unit test* hanya dimengerti *programmer*.


#### _GUI and Other Complications Testing through right interface_
&nbsp;&nbsp;&nbsp;&nbsp;Pada dasarnya, tampilan (*UI/ user interface*) mengalami perubahan yang dinamis, menyesuaikan kebutuhan masyarakat pada zamannya masing-masing. Sehingga kita tidak bisa membuat soal uji yang berketergantungan dengan hal-hal sementara (posisi button, warna, dll). Kita bisa melakukannya dengan memberi ID(penunjuk) pada objek dalam pembuatan *acceptance test*-nya.


#### _Continuous Integration Stop the presses_
&nbsp;&nbsp;&nbsp;&nbsp;Dalam *continuous integration*, kita harus memastikan untuk selalu menjalankan *acceptance test* dan *unit test*. Sangatlah penting untuk menaruh *CI tests* setiap waktu. Lebih baik setiap subfitur yang dibuat segera diuji, agar setiap *error* bisa segera tertangani. Hal ini untuk mencegah kesalahan yang menumpuk. Sehingga setelah produk jadi, *programmer* ditekan untuk membuat tes, menemukan bug, dan begitu terus sampai sempurna.


### Conclusion
&nbsp;&nbsp;&nbsp;&nbsp;
* Menjelaskan detail itu sulit. Antara *programmer* dengan *stakeholder* bisa saling berasumsi bahwa mereka sudah satu paham, padahal sebenarnya tidak.
* Cara efektif untuk mengeliminasi *communication error* antara *programmer* dengan *stakeholder* dapat diatasi dengan menulis *acceptance tests*. Test ini tidak ambigu dan tidak keluar dari implementasi produk (aplikasi).

