# HTML-CSS
Catatan
HTML & CSS I
- Aturan pertama penulisan code HTML adalah mengapit teks dengan tag. Tag dapat memberikan arti seperti judul atau tautan pada teks.
- Sebagian besar element HTML memerlukan sepasang tag, tag pembuka dan tag penutup, dengan teks disisipkan di antara keduanya.
  Saat menggunakan tag penutup, pastikan untuk meletakkan /.
  
  Judul & Paragraf
- Tag judul digunakan untuk memformat element judul.
  Tag ini bervariasi mulai dari <h1> hingga <h6>, <h1> menjadi yang terbesar dan <h6> menjadi yang terkecil (※ h mewakili heading (judul)).
- Tag <p> menentukan paragraf (※ p mewakili paragraf).
- Teks yang diapit oleh tag seperti <h2> dan <p> dimulai di baris baru.
- Tag <h1>...<h6> digunakan sesuai ukuran dan signifikansi judul seperti ditunjukkan di bawah. Untuk teks yang bukan merupakan judul, gunakan tag <p>.
- Teks yang diapit oleh <!-- --> menjadi komentar. Komentar tidak ditampilkan di browser. Komentar sangat berguna untuk menjelaskan code Anda.

  Tautan
  - Anda dapat dengan mudah membuat tautan dengan tag <a> (※ a mewakili anchor (penambat)).Teks dalam tag <a> ditampilkan di browser sebagai teks tautan.
  - Setiap tautan memiliki tujuan. Jadi, agar tautan berfungsi, Anda harus menentukan URL tujuan di element <a> dengan menambahkan atribut href. Seperti yang ditampilkan pada   
    gambar di sisi kiri, URL tujuan masuk ke bagian url dari <a href="url">.
  - Pada HTML, Anda dapat menentukan atribut seperti href di tag pembuka (※ lihat gambar di sisi kiri). Selalu letakkan nilai atribut dalam tanda kutip ganda ". (Url harus
    diapit dengan tanda kutip dua).

   Gambar
  - Tag <img> digunakan untuk menampilkan gambar. Kita dapat menetapkan gambar dengan menentukan url di atribut src seperti berikut: <img src="url">. Perhatikan bahwa tag <img>
    tidak memerlukan tag penutup karena tidak ada teks yang diapit.
  
  Daftar
  - Anda dapat membuat daftar dengan mengapit teks dengan tag <li>. 
  - Jenis daftar akan berubah tergantung pada tag yang Anda gunakan. Dengan tag <ul> Anda dapat membuat daftar dengan bullet. Jika element Anda "bersarang" seperti gambar dikiri 
    bawah ini, element yang menutupi akan menjadi induk dan element yang ditutupi akan menjadi anak-nya.<ul> (elemen induk) dan <li> (elemen anak).
  
  Indentasi (Lebih merujuk kepada kerapihan antar tags pembuka dan penutupnya)
  Untuk element bersarang, praktik yang baik adalah mensejajarkan code dengan indentasi. Meskipun tidak diperlukan, indentasi dapat memudahkan Anda untuk melihat hubungan induk
  anak, terutama pada saat code Anda sudah mulai banyak dan rumit (※ untuk membuat indentasi, tekan tombol "tab" di awal baris). 
  
  CSS
 - CSS digunakan untuk mendesain situs web. Dengan CSS, Anda dapat mengubah hal-hal seperti warna, ukuran, dan spasi pada element HTML.
 - CSS ditulis dalam file terpisah dari HTML. Anda dapat menerapkan CSS ke element HTML dengan menentukan "dimana", "apa", dan "bagaimana" Anda ingin mengubahnya. Pada contoh
  dibawah, CSS diterapkan ke element <h1> ("dimana"), dan warnanya ("apa") diubah menjadi merah ("bagaimana"). Element HTML yang ditargetkan disebut sebagai Selector. Penulisan
  CSS <h1> hanya ditulis h1 karena bukan class.
  
  Warna
 - Di CSS, warna ditentukan oleh nilai heksadesimal seperti color: #ff0000;
 - Seperti HTML, Anda harus selalu mengindentasi code CSS seperti gambar di bawah. Selain itu, perhatikan bahwa anda harus menambahkan titik dua : di akhir property CSS dan  
   titik koma ; diakhir baris seperti gambar dibawah.
  
  Komentar
 - Seperti di HTML, Anda dapat menulis komentar di file CSS. Namun di CSS, komentar harus diapit oleh /* */.
  
  Font Size
 - Ukuran font dapat ditetapkan dengan property font-size. Satuan umum untuk menentukan font-size adalah px (piksel).
  
  Font- Family
 - Dengan property font-family, Anda dapat menentukan jenis font. Anda dapat melakukan ini dengan menetapkanfont-family: nama font; Jika nama font berisi spasi, Anda harus
   mengapitnya dengan tanda petik ganda.
  
  Background Color
 - Property background-color memungkinkan Anda untuk mengubah warna latar belakang. Anda dapat menetapkan warna latar belakang seperti menetapkan property color. Selain itu,  
   jika huruf yang sama memanjang seperti #dddddd, ini dapat disingkat menjadi #ddd.

  Class
 - Anda dapat melakukannya dengan memberi label pada element yang ditargetkan dengan menggunakan atribut class. Dengan menambahkan class ke tag HTML, Anda dapat menerapkan CSS
  yang berbeda ke setiap element. Saat menerapkan CSS ke class selector, perhatikan bahwa titik . diperlukan di depan nama class.
  - SELECTOR CLASS MEMERLUKAN TITIK NAMUN UNTUK TAG TIDAK.
  
  Struktur HTML
- Di dokumen HTML, ada beberapa aturan yang harus Anda ikuti. Misalnya, element <head> dan <body> wajib berada didalam apitan element <html> (※ Lihat gambar di sisi kiri).  
- Element <head> berisi informasi dokumen sementara element <body> berisi konten yang terlihat di browser.
- Disetiap dokumen HTML, Anda harus memulai dengan deklarasi DOCTYPE. Ini akan memastikan versi HTML situs web Anda adalah yang terbaru. Kita akan menggunakan <!DOCTYPE html>,
  untuk menentukan versi HTML secara otomatis. Jangan terlalu khawatir tentang versi ini, cukup ingat bahwa ini adalah hal yang harus selalu Anda lakukan.
- Element <head> berisi settingan dokumen HTML yang tidak terlihat dibrowser. Ada tiga element yang harus Anda letakkan di <head>.
  Kita akan lihat masing-masing element ini dipelajaran berikutnya.
  
  Head
 - Dalam element <head>, kita akan menentukan 1) pengcodean karakter, 2) judul situs web, dan 3) tautan ke file CSS. Anda tidak harus menghapalnya, namun mari kita lihat arti
  element ini
 - Dengan menentukan pengcodean karakter di atribut charset seperti <meta charset="utf-8">, Anda dapat mencegah situs web menjadi kacau. UTF-8 adalah karakter encoding yang 
  direkomendasikan untuk HTML5.
 - Element <title> menentukan judul dokumen. Seperti yang ditampilkan pada gambar disisi kanan, judul yang ditentukan di element <title> hanya akan muncul di tab browser
 - Anda harus membuat tautan antara HTML dan file CSS dengan menentukan <link rel="stylesheet"> di dokumen HTML Anda. Anda dapat menentukan nama file CSS menggunakan atribut
   href
  
  Layout
  - Layout (tata letak) adalah salah satu bagian paling penting dalam membuat situs web. Layout situs web yang akan Anda buat umumnya terdiri dari tiga bagian seperti yang 
    ditampilkan pada gambar dibawah. (Header, Main, Footer).
  - Kita akan membuat tata letak dengan element <div> (※ "div" mewakili "divisi"). Tag <div> digunakan untuk mengelompokkan element. Seperti contoh dibawah, layout dibagi 
    menjadi tiga element <div> dengan nama class header, main, dan footer.
  - Mulai dari sini, Anda akan menulis banyak tag. Untuk mencegah kesalahan ketik, mari kita gunakan fungsi autocomplete di editor.
  
  Header
  - Class list dan Logo
  - Dengan menerapkan property list-style di element <li>, Anda dapat menghilangkan bullet. Karena kita tidak menginginkan bullet didaftar kita, mari kita tetapkan list-style ke
    none.
  
  Layout Header
  - Dengan menggunakan property float, Anda dapat menyejajarkan element secara horizontal. Seperti yang ditampilkan pada contoh, menentukan float: left; akan mengatur element 
    secara bersisian dari kiri ke kanan.
  - Mari kita mulai mengatur item daftar diheader secara bersisian. Dengan menerapkan float: left; ke setiap element <li> , Anda dapat menyejajarkannya secara horizontal dari 
    kiri ke kanan.
  - Kemudian, mari kita letakkan logo header dan keseluruhan daftar secara bersisian. Dengan menerapkan float: left; ke header-logo seperti yang ditampilkan dibawah, Anda dapat 
    menyejajarkan logo dan keseluruhan daftar secara horizontal .
  
  Padding
  - Jika Anda ingin menambahkan ruang ke element, Anda dapat menggunakan property padding. Dengan menerapkan padding: 〇〇px;, ruang yang ditentukan akan ditambahkan ke semua 
   sisi element.
  - Anda mungkin ingin menambahkan ruang hanya ke satu sisi element. Dalam kasus ini, Anda dapat menggunakan property seperti padding-top, padding-right, padding-bottom dan 
  padding-left. Misalnya, untuk menambahkan ruang dibagian atas, tetapkan padding-top: 〇〇px;.
  - Saat empat nilai ditentukan, padding diterapkan searah jarum jam dari bagian atas. Saat dua nilai ditentukan, padding diterapkan dalam urutan "atas/bawah" dan "kanan/kiri".
  
  Footer
  - Saat membuat header, kita menerapkan float dan padding ke setiap element <li>. Karena itu, property CSS juga diterapkan ke element <li> di footer. Menurut Anda, bagaimana 
    kita dapat menerapkan property CSS ini hanya ke tag <li> di header?
  - Dengan menambahkan li setelah header-list (dengan spasi di antara keduanya), Anda dapat menerapkan CSS hanya ke element <li> di header-list. Ini memungkinkan Anda untuk
  menerapkan CSS yang berbeda ke element <li> di header dan element <li> di footer.
  
  Float
  - Dengan menggabungkan float: left; dan float: right;, Anda dapat meletakkan logo dan daftar menu footer di baris dari kiri kekanan. Mari kita terapkan float: left; ke 
    selector footer-logo sehingga posisinya akan ke tepi kiri, dan menerapkan float: right; ke selector footer-list untuk memindahkannya ke tepi kanan.
  
  Konten
  Layout Bagian Utama
  -  layout bagian utama! Seperti yang ditampilkan dibawah, layout utama terdiri dari tiga element, yaitu copy-container, contents, dan contact-form. Ini mungkin akan sedikit 
   lebih rumit daripada layout lain yang telah kita buat. Tapi jangan khawatir! Kami akan menjelaskan setiap langkahnya.
  - Anda dapat menerapkan CSS ke sebagian teks dengan mengapitnya di tag <span>. Gambar dibawah mengilustrasikan hal ini dengan menerapkan color: red; ke selector span. Tidak 
   ada baris baru yang dimasukkan sebelum atau setelah element <span>.
  - Di HTML, beberapa element akan dimulai dibaris baru dan beberapa tidak. Element block seperti div akan di mulai dibaris baru, dan diperluas ke keseluruhan lebar element 
  induknya. Sedangkan Element inline seperti span hanya mengambil lebar secukupnya saja.
  
  Contents-item
  - Bagian berikutnya adalah konten. Pertama, mari kita buat bagian layout konten. Kita memerlukan judul dan 4 contents-item.
  
  Border
  - Anda dapat menambahkan batas dengan property border. Seperti yang ditampilkan pada gambar, Anda dapat menentukan lebar, style, dan warna. Gunakan property border untuk 
  menerapkan batas ke semua sisi. Untuk menambahkan batas kesisi tertentu, gunakan salah satu property berikut: border-bottom, border-top, border-left, atau border-right.
  
  Padding & Margin
  - Sebelumnya kita menggunakan property padding untuk memberikan ruang disekitar element. Namun, padding hanya menambahkan ruang di dalam batas. Untuk menambahkan ruang di luar 
   batas, anda dapat menggunakan property margin. Anda dapat menentukan nilai margin seperti menentukan nilai padding.
  - Property margin, border dan padding yang telah kita bahas sejauh ini didasarkan pada konsep model kotak. Setiap element HTML memiliki batas (secara default, sebagian 
  besarnya tidak terlihat). Ruang diluar batas kotak adalah margin, sedangkan ruang diantara batas dan teks adalah padding.
  
  Tag <input> & tag <textarea>
  - Selanjutnya, mari kita lihat cara membuat bidang input. Tag <input> digunakan untuk menerima satu baris teks, sementara tag <textarea> digunakan untuk menerima beberapa 
  baris teks. Perhatikan bahwa tag <input> tidak membutuhkan tag penutup.
  - Kita juga dapat membuat tombol submit (kirim) dengan menambahkan atribut type ke element <input>. Saat Anda menetapkan atribut type ke submit, element <input> menjadi tombol 
  submit (kirim) seperti gambar di bawah. Secara default, teks yang ditampilkan ditombol adalah "Submit".
  - Jika diinginkan, Anda dapat mengubah teks yang ditampilkan di tombol submit (kirim) dengan menentukan atribut value. Dengan atribut ini, kita dapat mengubah nama tombol 
  submit menjadi apapun, seperti Kirim.
  
  Menerapkan CSS ke beberapa Selector
  - Anda dapat mengelompokkan CSS yang sama dengan memisahkan beberapa selector dengan koma , seperti yang ditunjukkan pada gambar tengah. Dengan melakukan hal tersebut, Anda 
  dapat menerapkan CSS yang sama ke berbagai selector. Untuk situs web kita, mari terapkan CSS yang sama ke element <input> dan <textarea> menggunakan metode ini.
  
  SABTU DISKUSI 
  https://www.vulnhub.com/entry/damn-vulnerable-web-application-dvwa-107,43/
  
  nama format image paling ringan. webp
