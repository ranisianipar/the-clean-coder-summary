#The Clean Coder
##Chapter 8
##Testing Strategies

###Content:
* [QA Tidak Seharusnya Menemukan Apapun](#qa-tidak-seharusnya-menemukan-apapun)
* [Piramida Automasi Pengujian](#piramida-automasi-pengujian)
  * [Uji Unit](#uji-unit)
  * [Uji Komponen](#uji-komponen)
  * [Uji Integrasi](#uji-integrasi)
  * [Uji Sistem](#uji-sistem)
  * [Uji Eksplorasi Manual](#uji-eksplorasi-manual)
* [Konklusi](#konklusi)

### QA Tidak Seharusnya Menemukan Apapun
&nbsp;&nbsp;&nbsp;&nbsp;Strategi pengujian bertujuan agar QA (Quality Assurance) “ tidak menemukan apapun”. Selain itu QA juga adalah bagian dari team development agar dapat memastikan kualitas dari sistem yang dibuat. Peran terbaik QA sebagai bagian tim adalah menjadikan QA sebagai penentu dan karakter.

### Piramida Automasi Pengujian
&nbsp;&nbsp;&nbsp;&nbsp;Agar mencapai pengujian yang disiplin dapat mengacu pada piramid pengujian automasi yang dilakukan secara bertahap dari bagian terendah hingga bagian yang atas (kompleks). Berdasarkan piramid pengujian automasi maka urutan yang diuji adalah pengujian unit, pengujian komponen, pengujian integrasi, pengujian sistem, dan juga pengujian Eksplorasi Manual.
#### Uji Unit
&nbsp;&nbsp;&nbsp;&nbsp;Pada bagian dasar piramid adalah pengujian unit. Pengujian unit ditulis oleh progammer kepada progammer. Dengan tujuan awal adalah untuk melakukan pengujian detail sistem pada level terendah.

#### Uji Komponen
&nbsp;&nbsp;&nbsp;&nbsp;Komponen pada umumnya didirikan berdasarkan aturan-aturan bisnis. sehingga pengujian untuk komponen-komponen tersebut adalah tes penerimaan untuk aturan-aturan bisnis. Pengujian komponen ditulis oleh QA dan badan bisnis yang dibantu dari pihak pengembang.
&nbsp;&nbsp;&nbsp;&nbsp;Pengujian Komponen terpisah dengan pengujian dengan menggunakan pendekatan mocking dan juga teknik uji penggandaan. Pengujian komponen kurang lebih melingkupi setengah dari sistem. pengujian diarahkan pada situasi batas, jalan alternatif kasus. Sebagian besar kasus-kasus tidak di tercover oleh pengujian unit. 

#### Uji Integrasi
&nbsp;&nbsp;&nbsp;&nbsp;Pengujian Integrasi adalah Pengujian sistem yang lebih besar dan melibatkan beberapa atau sekelompok komponen sekaligus. Pengujian ini menguji seberapa baik hubungan antara komponen. Sedikit berbeda dengan pengujian Komponen, pengujian integrasi tidak melakukan pengujian terhadap aturan bisnis. Pengujian plumbing ditujukan untuk melakukan pengujian terhadap keterhubungan dan interaksi yang baik antar komponen. Pengujian integrasi ditulis oleh arsitek sistem, kepala desain dari sistem. Pengujian ini untuk memastikan struktur arsitektur dari sistem.

#### Uji Sistem
&nbsp;&nbsp;&nbsp;&nbsp;Pengujian Sistem adalah tes yang secara otomatis dilakukan terhadap seluruh sistem terintegrasi. Pengujian ini hanya mengecek apakah sistem sudah terhubung dengan baik dan komponen-komponen di dalamnya beroperasi sesuai dengan rencana. Pengujian Sistem dilakukan oleh arsitek sistem dan kepala bagian teknis serta hanya menguji sekitar 10% dari keseluruhan sistem untuk memastikan bahwa konstruksi sistem sudah benar.

#### Uji Eksplorasi Manual
&nbsp;&nbsp;&nbsp;&nbsp;Pengujian ini dilakukan oleh manusia, tidak dibuat secara otomatis maupun dibuat menggunakan kode. Pengujian ini bertujuan untuk mengeksplorasi respon yang tidak diharapkan sembari mengkonfirmasi respon yang diharapkan. Tujuan dari tes ini bukan untuk membuktikan aturan bisnis dan setiap jalur eksekusi, melainkan untuk memastikan bahwa sistem bekerja dengan baik di bawah kontrol manusia.

###Konklusi
&nbsp;&nbsp;&nbsp;&nbsp;TDD dan Acceptance Test merupakan hal yang baik, namun mereka hanyalah bagian dari strategi pengujian. Untuk mencapai tujuan “QA tidak menemukan apa-apa”, tim development harus bekerja sama dengan QA untuk membuat hirarki dari unit, komponen, integrasi, sistem dan exploratory test. Pengujian ini perlu dijalankan sesering mungkin untuk menghasilkan feedback yang cukup dan memastikan sistem berjalan dengan bersih.
