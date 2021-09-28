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
  - Pada HTML, Anda dapat menentukan atribut seperti href di tag pembuka (※ lihat gambar di sisi kiri). Selalu letakkan nilai atribut dalam tanda kutip ganda ". (Url harus diapit 
    dengan tanda kutip dua).

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
