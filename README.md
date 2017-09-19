# Line Echart

I. Jenis : Dynamic Data + Time Axis
II. Option : 

### **TITLE** ###
1.	Title : Text (string) -> untuk membuat judul.
2.	Title : textStyle (number) fontSize -> untuk mengubah ukuran text.
3.	Title : textStyle (string) color -> untuk mengubah warna.
4.	Title : textStyle (string) fontFamily -> mengubah jenis font.
5.	Title : textStyle (string) fontWeight bold-> membuat judul menjadi tebal.
6.	Title : textStyle (number) fontStyle-> untuk membuat gaya teks menjadi miring.
7.	Title : textBaseline (string) -> mengatur posisi teks secara vertical (top,middle,bottom).
8.	Title : link (string) -> untuk memindahkan halaman dari judul.
9.	Title : Target (string) blank -> untuk membuka halaman lain di tab baru.
            -Target (string) self -> untuk membuka halamanlain pada tab yang sama.
10.	Title : shadowOffsetX (number) -> jarak bayangan horizontal.
11.	Title : shadowOffsetY (number) -> jarak bayangan vertical.
12.	Title : shadowColor (color) -> menentukan warna shadow.
13.	Title : textAlign (string) -> menentukan letak teks (center,right,left).

### **TOOLTIP** ###
1.	Tooltip : backgroundColor (color) -> untuk mengubah warna latar belakang lapisan apung tooltip.
2.	Tooltip : Trigger (string) Axis -> digunakan untuk grafik yang memiliki sumbu kategori, seperti grafik batang atau diagram garis.

### **AxisPointer** ###
1.	AxisPointer : AxisPointer adalah alat untuk menampilkan garis referensi dan nilai sumbu di bawah penunjuk mouse. 
2.	AxisPointer : Type (string) cross ->  digunakan untuk  menampilkan jalan pintas untuk mengaktifkan dua sumbu pointer dua sumbu      ortometrik.

### **xAXIS** ###
1.	xAxis : Type (string) time -> Dibandingkan dengan sumbu nilai, ia memiliki pemformatan yang lebih baik untuk waktu dan metode perhitungan yang berbeda. Misalnya, ia memutuskan untuk menggunakan bulan, minggu, hari atau jam untuk tanda centang berdasarkan kisaran rentang.
2.	xAsis : Position (string) top/bottom -> untuk mengatur posisi sumbu x diatas/bawah.
3.	xAxis : nameGap (number) -> jarak antara nama sumbu dengan garis sumbu.
4.	xAxis : Name (string) -> untuk memberi nama sumbu x.
5.	xAxis : name Location (string) -> untuk menempatkan posisi nama sumbu.
6.	xAxis : NameTextStyle color (color)   ->  untuk memberi warna pada nama sumbu x
7.	xAxis : nameTextStyle fontFamily (string) -> unntuk mengubah gaya huruf pada nama sumbu.
8.	xAxis : nameTextStyle fontSize (number) -> untuk mengubah ukuran huruf.
9.	xAsis : nameRotate (number) -> rotasi dari nama sumb x.
10.	xAxis : Show (Boolean) False -> digunakan untuk tidak menampilkan sumbu x.
jika show true -> akan menampilkan sumbu 

### **yAXIS** ###
1.	yAxis : Type (string) value -> digunakan pada sumbu numerik, cocok untuk data kontinu.
2.	yAxis : position ( string) left/right -> untuk menempatkan posisi sumbu y.
3.	yAxis : nameGap (number) -> jarak antara nama sumbu dengan garis sumbu.
4.	yAxis : Name (string) -> untuk menberi nama pada sumbu y.
5.	yAxis : NameLocation (string) -> untuk menempatkan posisi nama sumbu y.
6.	yAxis : nameTextStyle color (color) -> untuk memberi warna pada nama sumbu y. 
7.	yAxis : nameTextStyle fontFamily (string) ->  untuk mengubah gaya huruf pada nama sumbu.
8.	yAxis : nameTextStyle fontSize (string) ->untuk mengubah ukuran huruf.
9.	yAxis : nameRotate (number) -> rotasi dari nama sumbu y.
10.	yAxsis : Show (Boolean) true -> akan menampilkan sumbu y.
11.	jika show false -> tidak akan menampilkan sumbu y
12.	yAxis : BoundaryGap (string, array) [0, '100%'] -> Batas batas pada kedua sisi sumbu koordinat. Pengaturan dan perilaku sumbu kategori dan sumbu non-kategori berbeda. Batas dari sumbu kategori dapat diset ke true atau false. Nilai dapat diatur dalam nilai numerik atau persentase relatif, yang menjadi tidak valid setelah menyetel min dan maks. 
13.	yAxis : Show (boolean) false -> digunakan untuk tidak menampilkan sumbu y. 
14.	jika show : true -> akan menampilkan sumbu y

### **SERIES** ###
1.	Series : Type Line -> Bagan garis rusak yang menghubungkan semua simbol titik data dengan garis putus-putus, yang digunakan untuk menunjukkan kecenderungan perubahan data. Ini bisa digunakan dalam koordinat koordinat dan koordinat dua persegi.
2.	Series : showSymbol (Boolean) false -> digunakan untuk  tidak akan menunjukkan simbol. Ini akan ditunjukkan saat tooltip hover.
3.	Series : hoverAnimation (Boolean) false -> digunakan agar tidak mengaktifkan efek animasi saat mouse berada pada simbol.
Series : Data (object) -> Pada dasarnya, data diwakili oleh array dua dimensi, di mana setiap kolom diberi nama sebagai "dimensi".

### **GRID** ###
1.	Grid : left (string, nuber) -> jarak antara komponen grid dan sisi kiri.
2.	Grid : bottom (string, number) -> jarak antara komponen grid dan sisi bawah.
3.	Grid : top (string, number) ->jarak antara komponen grid dan sis atas.
4.	Grid : right (string, number) -> jaral antara komponen grid dan sisi kanan.
5.	Grid : backgroundColor (color) -> untuk memberi warna latar belakang grid.
6.	Grid : borderColor (color) -> untuk memberikan warna pada batas grid.
7.	Grid : show (string) true -> untuk menunjukan grid dalam koordinat.

