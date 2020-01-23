# Pengenalan Python
![python-logo](https://user-images.githubusercontent.com/47344288/72213664-3fe11880-3525-11ea-8d36-93bf35c0dfdf.png)

Python adalah bahasa pemrograman interpretatif multiguna. Tidak seperti bahasa lain yang susah untuk dibaca dan dipahami,
python lebih menekankan pada keterbacaan kode agar lebih mudah untuk memahami sintaks. Hal ini membuat Python sangat mudah dipelajari baik untuk pemula maupun untuk yang sudah menguasai bahasa pemrograman lain.

Bahasa ini muncul pertama kali pada tahun 1991, dirancang oleh seorang bernama Guido van
Rossum. Sampai saat ini Python masih dikembangkan oleh Python Software Foundation. Bahasa
Python mendukung hampir semua sistem operasi, bahkan untuk sistem operasi Linux, hampir
semua distronya sudah menyertakan Python di dalamnya.
Dengan kode yang simpel dan mudah diimplementasikan, seorang programmer dapat lebih
mengutamakan pengembangan aplikasi yang dibuat, bukan malah sibuk mencari syntax error.

print("Follow github suryapardana")

Hanya dengan menuliskan kode print seperti yang diatas, anda sudah bisa mencetak apapun yang
anda inginkan di dalam tanda kurung (). Dibagian akhir kode pun, anda tidak harus
mengakhirnya dengan tanda semicolon ;

# Instalasi Python
Sebelum Anda menggunakan Python, Anda harus menginstalnya terlebih dahulu di sistem operasi komputer Anda. Saat ini Python memiliki 2 versi yang berbeda, yaitu Python versi 3.4.3 dan Python versi 2.7.10. Disini kita akan belajar bahasa pemrograman Python menggunakan versi terbaru 3.4.3

Cara menginstal python sangat mudah, ikuti panduan dibawah ini. Dibawah adalah panduan cara instal python di platform Linux, Windows dan Mac OS.

## 1.1 Linux
```
- Buka browser, kunjungi http://www.python.org/downloads/source/
- Download versi terbaru Python berbentuk file zip untuk Unix/Linux
- Ekstrak file zip yang baru saja di download
- Edit file Modules/Setup jika Anda ingin kostumisasi Python
- Jalankan ./configure script
- make
- make install
```
Langkah ini akan menginstal Python di lokasi standar /usr/local/bin dan library di /usr/local/lib/pythonXX dimana XX adalah versi terbaru Python yang anda gunakan.

 ## 1.2 Windows
```
- Buka browser, kunjungi http://www.python.org/downloads/windows/
- ATAU, klik direct link https://www.python.org/ftp/python/3.4.3/python-3.4.3.msi
- Buka (klik 2x) file installer python yang baru saja di download
- Ikuti langkah instalasi sampai selesai
```

##  1.3 Mac OS
```
- Buka browser, kunjungi http://www.python.org/download/mac/
- Download versi terbaru Python untuk Macintosh
- Buka file yang baru saja di download
- Ikuti langkah instalasi sampai selesa
```
# Integrated Daveloper Environment

IDE adalah sebuah software aplikasi yang memberikan Anda fasilitas bermanfaat ketik membuat program. Biasanya sebuah IDE terdiri dari source code editor build automation tool dan debugger.
Untuk menulis sebuah program, bisa menggunakan text editor atau IDE nya. Bagi yang sudah mahir, menulis program dengan text editor bukanlah menjadi masalah. Tetapi untuk pemula, akan lebih mudah menggunakan IDE. IDE untuk Python sangatlah banyak, tersedia bermacam-macam IDE dengan kelebihan dan kekurangan masing-masing.

Beberapa IDE untuk Python yang cukup populer adalah :

- Komodo
- LiClipse
- NetBeans
- PyCharm
- Kdevelop
- PyDev
- Wing IDE
- dan masih banyak lainnya

 (http://wiki.python.org/moin/IntegratedDevelopmentEnvironments).

# Menjalankan Python
Untuk menjalankan Python ada banyak cara yang bisa dilakukan. Anda bisa menggunakan sheel, terminal atau menggunakan IDE (Integrated Development Environment). Di bawah ini adalah langkah-langkah menjalankan Python dengan cara yang paling mudah.

## 2.1 Linux
- Buka terminal (Ctrl + Alt + T)
- Ketik python maka Anda akan masuk ke sheel Python. 
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit()

atau 

- Gunakan teks editor, misalnya gedit.
- Buat file baru, dan ketikan script python Anda, contoh: print("Selamat datang di Python").
- Save As dengan ekstensi .py (contoh: cetak.py).
- Jalankan file dengan menggunakan Terminal.
- Buka terminal (Ctrl + Alt + T).
- Masuk ke direktori dimana file Python Anda disimpan (contoh: cd /Users/admin/Desktop/).
- Jalankan script Python dengan menggunakan python diikuti dengan nama file (contoh: python cetak.py).
- Script Python Anda akan dieksekusi/dijalankan.

 ## 2.2 Windows

- Buka Python sheel, Anda bisa mencarinya di tombol Start.
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit()

## 2.3 Macintosh

- Buka terminal.
- Ketik python maka Anda akan masuk ke sheel Python. 
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit() atau 
- Gunakan teks editor.
- Buat file baru, dan ketikan script python Anda, contoh: print("Selamat datang di Python").
- Save As dengan ekstensi .py (contoh: cetak.py).
- Jalankan file dengan menggunakan Terminal.
- Buka terminal (Ctrl + Alt + T).
- Masuk ke direktori dimana file Python Anda disimpan (contoh: cd /Users/admin/Desktop/).
- Jalankan script Python dengan menggunakan python diikuti dengan nama file (contoh: python cetak.py).
- Script Python Anda akan dieksekusi/dijalankan.

# Syntax Dasar Python
Dibawah ini adalah contoh fungsi Python yang digunakan untuk mencetak. Di Python untuk mencetak cukup gunakan fungsi print(), dimana sesuatu yang akan dicetak harus diletakkan diantara kurung buka dan kurung tutup, bahkan di Python versi 2.x Anda tidak harus menggunakan tanda kurung kurawal, cukup pisahkan dengan spasi.
Jika ingin mencetak tipe data String langsung, Anda harus memasukanya ke dalam tanda kutip terlebih dahulu.

print("Hello World")

Saat anda menjalankan script diatas, Anda akan melihat output berupa text Hello World

# Komentar Python

Komentar (comment) adalah kode di dalam script Python yang tidak dieksekusi atau tidak dijalankan mesin. Komentar hanya digunakan untuk menandai atau memberikan keterangan tertulis pada script.
Komentar biasa digunakan untuk membiarkan orang lain memahami apa yang dilakukan script. atau untuk mengingatkan kepada programmer sendiri jika suatu saat kembali mengedit script tersebut.
Untuk menggunakan komentar anda cukup menulis tanda pagar #, diikuti dengan komentar Anda.
Dibawah ini adalah contoh penggunaan komentar pada Python.
```
#Ini adalah komentar

#Tulisan ini tidak akan dieksekusi

#komentar dengan tanda pagar hanya bisa digunakan

#untuk

#satu

#baris

print("Hello World") #ini juga komentar

#print("Welcome")

#komentar bisa berisi spesial karakter !@#$%^&*(

#mencetak nama

print("Budi")

#mencetak angka/integer

print(123)
```

Saat anda menjalankan script diatas, Anda akan melihat output berupa Hello World, Budi dan 123, karena tulisan/komentar yang ditulis tidak dieksekusi.

# Python Case Sensitive
Python bersifat case sensitif, ini artinya huruf besar dan huruf kecil memiliki perbedaan.
Sebagai contoh jika Anda menggunakan fungsi print dengan huruf kecil print() akan
berhasil. Lain hal jika anda menggunakan huruf kapital Print() atau PRINT(), akan
muncul pesan error.
Aturan ini berlaku untuk nama variabel ataupun fungsi-fungsi lainya

# Tipe Data

Tipe data adalah suatu media atau memori pada komputer yang digunakan untuk menampung informasi.

Python sendiri mempunyai tipe data yang cukup unik bila kita bandingkan dengan bahasa pemrograman yang lain.

Berikut adalah tipe data dari bahasa pemrograman Python :

| Tipe Data     | Contoh                    | Penjelasan                                                                        |
| ------------- |-------------------------- | --------------------------------------------------------------------------------- |
| Boolean       |	`True` atau `False`	    | Menyatakan benar `True` yang bernilai `1`, atau salah `False` yang bernilai `0`   |
| String        |	`"Ayo belajar Python"`  | Menyatakan karakter/kalimat bisa berupa huruf angka, dll (diapit tanda `"` atau `'`)|
| Integer       |	`25` atau `1209`        | Menyatakan bilangan bulat                                                         |
| Float         |	`3.14` atau `0.99`      | Menyatakan bilangan yang mempunyai koma                                           |
| Hexadecimal   |	`9a` atau `1d3`	        | Menyatakan bilangan dalam format heksa (bilangan berbasis 16)                     |
| Complex       |	`1 + 5j  `              | Menyatakan pasangan angka real dan imajiner                                       |
| List          |	`['xyz', 786, 2.23]`    | Data untaian yang menyimpan berbagai tipe data dan isinya bisa diubah-ubah        |
| Tuple         |	`('xyz', 768, 2.23)`    | Data untaian yang menyimpan berbagai tipe data tapi isinya tidak bisa diubah      |
| Dictionary    |	`{'nama': 'adi','id':2}`| Data untaian yang menyimpan berbagai tipe data berupa pasangan penunjuk dan nilai |

Untuk mencoba berbagai macam tipe data, silahkan coba script Python dibawah ini.
```

#tipe data Boolean
print(True)

#tipe data String
print("Ayo belajar Python")
print('Belajar Python Sangat Mudah')

#tipe data Integer
print(20)

#tipe data Float
print(3.14)

#tipe data Hexadecimal
print(9a)

#tipe data Complex
print(5j)

#tipe data List
print([1,2,3,4,5])
print(["satu", "dua", "tiga"])

#tipe data Tuple
print((1,2,3,4,5))
print(("satu", "dua", "tiga"))

#tipe data Dictionary
print({"nama":"Budi", 'umur':20})
#tipe data Dictionary dimasukan ke dalam variabel biodata
biodata = {"nama":"Andi", 'umur':21} #proses inisialisasi variabel biodata
print(biodata) #proses pencetakan variabel biodata yang berisi tipe data Dictionary
type(biodata) #fungsi untuk mengecek jenis tipe data. akan tampil <class 'dict'> yang berarti dict adalah tipe data dictionary

```
# Variabel Python

Variabel adalah lokasi memori yang dicadangkan untuk menyimpan nilai-nilai. Ini berarti bahwa ketika Anda membuat sebuah variabel Anda memesan beberapa ruang di memori. Variabel menyimpan data yang dilakukan selama program dieksekusi, yang nantinya isi dari variabel tersebut dapat diubah oleh operasi - operasi tertentu pada program yang menggunakan variabel.

Variabel dapat menyimpan berbagai macam tipe data. Di dalam pemrograman Python, variabel mempunyai sifat yang dinamis, artinya variabel Python tidak perlu didekralasikan tipe data tertentu dan variabel Python dapat diubah saat program dijalankan.


Penulisan variabel Python sendiri juga memiliki aturan tertentu, yaitu :
1. Karakter pertama harus berupa huruf atau garis bawah/underscore `_`
2. Karakter selanjutnya dapat berupa huruf, garis bawah/underscore `_` atau angka
3. Karakter pada nama variabel bersifat sensitif (case-sensitif). Artinya huruf kecil dan huruf besar dibedakan. Sebagai contoh, variabel `namaDepan` dan `namadepan` adalah variabel yang berbeda.

Untuk mulai membuat variabel di Python caranya sangat mudah, Anda cukup menuliskan variabel lalu mengisinya dengan suatu nilai dengan cara menambahkan tanda sama dengan `=` diikuti dengan nilai yang ingin dimasukan.

Dibawah ini adalah contoh penggunaan variabel dalam bahasa pemrograman Python


```

#proses memasukan data ke dalam variabel
nama = "John Doe"
#proses mencetak variabel
print(nama)

#nilai dan tipe data dalam variabel  dapat diubah
umur = 20               #nilai awal
print(umur)             #mencetak nilai umur
type(umur)              #mengecek tipe data umur
umur = "dua puluh satu" #nilai setelah diubah
print(umur)             #mencetak nilai umur
type(umur)              #mengecek tipe data umur

namaDepan = "Budi"
namaBelakang = "Susanto"
nama = namaDepan + " " + namaBelakang
umur = 22
hobi = "Berenang"
print("Biodata\n", nama, "\n", umur, "\n", hobi)

#contoh variabel lainya
inivariabel = "Halo"
ini_juga_variabel = "Hai"
_inivariabeljuga = "Hi"
inivariabel222 = "Bye" 

panjang = 10
lebar = 5
luas = panjang * lebar
print(luas)

```

# Operator Python
Operator adalah konstruksi yang dapat memanipulasi nilai dari operan. 

Sebagai contoh operasi 3 + 2 = 5. Disini `3` dan `2` adalah operan dan `+` adalah operator.

Bahasa pemrograman Python mendukung berbagai macam operator, diantaranya :
- [Operator Aritmatika (Arithmetic Operators)](#operator-aritmatika)
- [Operator Perbandingan (Comparison (Relational) Operators)](#operator-perbandingan)
- [Operator Penugasan (Assignment Operators)](#operator-penugasan)
- [Operator Logika (Logical Operators)](#operator-logika)
- [Operator Bitwise (Bitwise Operators)](#operator-bitwise)
- [Operator Keanggotaan (Membership Operators)](#operator-keanggotaan)
- [Operator Identitas (Identity Operators)](#operator-identitas)
 
### Operator Aritmatika <a name="operator-aritmatika"></a>

| Operator| 	Contoh	 | Penjelasan |
| --- | --- | --- |
| Penjumlahan `+`| 	`1 + 3 = 4` | 	Menjumlahkan nilai dari masing-masing operan atau bilangan |
| Pengurangan `-`| 	`4 - 1 = 3`	 | Mengurangi nilai operan di sebelah kiri menggunakan operan di sebelah kanan |
| Perkalian `*`| 	`2 * 4 = 8`	 | Mengalikan operan/bilangan |
| Pembagian `/`| 	`10 / 5 = 2`	 | Untuk membagi operan di sebelah kiri menggunakan operan di sebelah kanan |
| Sisa Bagi `%`| 	`11 % 2 = 1`	 | Mendapatkan sisa pembagian dari operan di sebelah kiri operator ketika dibagi oleh operan di sebelah kanan |
| Pangkat `**`| 	`8 ** 2 = 64`	 | Memangkatkan operan disebelah kiri operator dengan operan di sebelah kanan operator |
| Pembagian Bulat `//`| 	`10 // 3 = 3` |	Sama seperti pembagian. Hanya saja angka dibelakang koma dihilangkan |

Dibawah ini adalah contoh penggunaan Operator Aritmatika dalam bahasa pemrograman Python
```

#OPERATOR ARITMATIKA

#Penjumlahan
print(13 + 2)
apel = 7
jeruk = 9
buah = apel + jeruk #
print(buah)

#Pengurangan
hutang = 10000
bayar = 5000
sisaHutang = hutang - bayar
print("Sisa hutang Anda adalah ", sisaHutang)

#Perkalian
panjang = 15
lebar = 8
luas = panjang * lebar
print(luas)

#Pembagian
kue = 16
anak = 4
kuePerAnak = kue / anak
print("Setiap anak akan mendapatkan bagian kue sebanyak ", kuePerAnak)

#Sisa Bagi / Modulus
bilangan1 = 14
bilangan2 = 5
hasil = bilangan1 % bilangan2
print("Sisa bagi dari bilangan ", bilangan1, " dan ", bilangan2, " adalah ", hasil)

#Pangkat
bilangan3 = 8
bilangan4 = 2
hasilPangkat = bilangan3 ** bilangan4
print(hasilPangkat)

#Pembagian Bulat
print(10//3) 
#10 dibagi 3 adalah 3.3333. Karena dibulatkan maka akan menghasilkan nilai 3

```
### Operator Perbandingan <a name="operator-perbandingan"></a>

Operator perbandingan (comparison operators) digunakan untuk membandingkan suatu nilai dari masing-masing operan.

| Operator	| Contoh	| Penjelasan| 
| --- | --- | --- |
| Sama dengan `==` | 	`1 == 1`  | bernilai True	Jika masing-masing operan memiliki nilai yang sama, maka kondisi bernilai benar atau True. | 
| Tidak sama dengan `!=` |	`2 != 2`  | bernilai False	Akan menghasilkan nilai kebalikan dari kondisi sebenarnya. | 
| Tidak sama dengan `<>` |	`2 <> 2`  | bernilai False	Akan menghasilkan nilai kebalikan dari kondisi sebenarnya. | 
| Lebih besar dari `>` |	`5 > 3`  | bernilai True	Jika nilai operan kiri lebih besar dari nilai operan kanan, maka kondisi menjadi benar. | 
| Lebih kecil dari `<` |	`5 < 3`  | bernilai True	Jika nilai operan kiri lebih kecil dari nilai operan kanan, maka kondisi menjadi benar. | 
| Lebih besar atau sama dengan `>=` |	`5 >= 3`  | bernilai True	Jika nilai operan kiri lebih besar dari nilai operan kanan, atau sama, maka kondisi menjadi benar. | 
| Lebih kecil atau sama dengan `<=` |	`5 <= 3`  | bernilai True	Jika nilai operan kiri lebih kecil dari nilai operan kanan, atau sama, maka kondisi menjadi benar. | 


### Operator Penugasan <a name="operator-penugasan"></a>

Operator penugasan digunakan untuk memberikan atau memodifikasi nilai ke dalam sebuah variabel.

| Operator	| Contoh	| Penjelasan | 
| --- | --- | --- |
| Sama dengan `=`	 | `a = 1` | 	Memberikan nilai di kanan ke dalam variabel yang berada di sebelah kiri. | 
| Tambah sama dengan `+=` | 	`a += 2` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri ditambah dengan nilai di sebelah kanan. | 
| Kurang sama dengan `-=`	 | `a -= 2` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri dikurangi dengan nilai di sebelah kanan. | 
| Kali sama dengan `*=` | 	`a *= 2` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri dikali dengan nilai di sebelah kanan. | 
| Bagi sama dengan `/=` | 	`a /= 4` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri dibagi dengan nilai di sebelah kanan. | 
| Sisa bagi sama dengan `%=`	 | `a %= 3` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri dibagi dengan nilai di sebelah kanan. Yang diambil nantinya adalah sisa baginya. | 
| Pangkat sama dengan `**=` | 	`a **= 3`	 | Memberikan nilai variabel dengan nilai variabel itu sendiri dipangkatkan dengan nilai di sebelah kanan. | 
| Pembagian bulat sama dengan `//=` | 	`a //= 3`	 | Membagi bulat operan sebelah kiri operator dengan operan sebelah kanan operator kemudian hasilnya diisikan ke operan sebelah kiri. | 


### Prioritas Eksekusi Operator di Python
Dari semua operator diatas, masing-masing mempunyai urutan prioritas yang nantinya prioritas pertama akan dilakukan paling pertama, begitu seterusnya sampai dengan prioritas terakhir. 
```
| Operator |	Keterangan | 
| --- | --- | --- |
| `**` |	Aritmatika | 
| `~, +, -` |	Bitwise | 
| `*, /, %, //` |	Aritmatika |
| `+, -`	 |Aritmatika |
| `>>, <<` |	Bitwise |
| `&`	 |Bitwise |
| `^, |`  |	Bitwise |
| `<=, <, >, >=` |	Perbandingan |
| `<> , ==, !=` |	Perbandingan |
| `=, %=, /=, //=, -=, +=, *=, **=` |	Penugasan |
| `is, is not` |	Identitas |
| `in, not in` |	Membership (Keanggotaan) |
| `not, or, and` |	Logika |
```

# Kondisi
### Kondisi If

Pengambilan keputusan (kondisi if) digunakan untuk mengantisipasi kondisi yang terjadi saat jalanya program dan menentukan tindakan apa yang akan diambil sesuai dengan kondisi.

Pada python ada beberapa statement/kondisi diantaranya adalah `if`, `else` dan `elif` Kondisi `if` digunakan untuk mengeksekusi kode jika kondisi bernilai benar `True`.

Jika kondisi bernilai salah `False` maka statement/kondisi `if` tidak akan di-eksekusi.

Dibawah ini adalah contoh penggunaan kondisi if pada Python
```

#Kondisi if adalah kondisi yang akan dieksekusi oleh program jika bernilai benar atau TRUE

nilai = 9

#jika kondisi benar/TRUE maka program akan mengeksekusi perintah dibawahnya
if(nilai > 7):
    print("Selamat Anda Lulus")

#jika kondisi salah/FALSE maka program tidak akan mengeksekusi perintah dibawahnya
if(nilai > 10):
    print("Selamat Anda Lulus")

```
Dari contoh diatas, jika program dijalankan maka akan mencetak string `"Selamat Anda Lulus Ujian"` sebanyak 1 kali yaitu pada if pertama. Di if kedua statement bernilai salah, jadi perintah `print("Selamat Anda Lulus")` tidak akan dieksekusi.


### Kondisi If Else
Pengambilan keputusan (kondisi if else) tidak hanya digunakan untuk menentukan tindakan apa yang akan diambil sesuai dengan kondisi, tetapi juga digunakan untuk menentukan tindakan apa yang akan diambil/dijalankan jika kondisi tidak sesuai.

Pada python ada beberapa statement/kondisi diantaranya adalah if, else dan elif Kondisi if digunakan untuk mengeksekusi kode jika kondisi bernilai benar.

Kondisi if else adalah kondisi dimana jika pernyataan benar `True` maka kode dalam if akan dieksekusi, tetapi jika bernilai salah `False` maka akan mengeksekusi kode di dalam else.

Dibawah ini adalah contoh penggunaan kondisi if else pada Python
```

#Kondisi if else adalah jika kondisi bernilai TRUE maka akan dieksekusi pada if, tetapi jika bernilai FALSE maka akan dieksekusi kode pada else

nilai = 3
#Jika pernyataan pada if bernilai TRUE maka if akan dieksekusi, tetapi jika FALSE kode pada else yang akan dieksekusi.
if(nilai > 7):
    print("Selamat Anda Lulus")
else:
    print("Maaf Anda Tidak Lulus")

```
Pada contoh diatas, jika program dijalankan maka akan mencetak string `"Maaf Anda Tidak Lulus"` karena pernyataan pada if bernilai `False`

### Kondisi Elif

Pengambilan keputusan (kondisi if elif) merupakan lanjutan/percabangan logika dari "kondisi if". Dengan elif kita bisa membuat kode program yang akan menyeleksi beberapa kemungkinan yang bisa terjadi. Hampir sama dengan kondisi "else", bedanya kondisi "elif" bisa banyak dan tidak hanya satu. 

Dibawah ini adalah contoh penggunaan kondisi elif pada Python
```

#Contoh penggunaan kondisi elif

hari_ini = "Minggu"

if(hari_ini == "Senin"):
    print("Saya akan kuliah")
elif(hari_ini == "Selasa"):
    print("Saya akan kuliah")
elif(hari_ini == "Rabu"):
    print("Saya akan kuliah")
elif(hari_ini == "Kamis"):
    print("Saya akan kuliah")
elif(hari_ini == "Jumat"):
    print("Saya akan kuliah")
elif(hari_ini == "Sabtu"):
    print("Saya akan kuliah")
elif(hari_ini == "Minggu"):
    print("Saya akan libur")

```
Pada contoh diatas, jika program dijalankan maka akan mencetak string `"Saya akan libur"`.

# Loop python


Secara umum, pernyataan pada bahasa pemrograman akan dieksekusi secara berurutan. Pernyataan pertama dalam sebuah fungsi dijalankan pertama, diikuti oleh yang kedua, dan seterusnya. Tetapi akan ada situasi dimana Anda harus menulis banyak kode, dimana kode tersebut sangat banyak. Jika dilakukan secara manual maka Anda hanya akan membuang-buang tenaga dengan menulis beratus-ratus bahkan beribu-ribu kode. Untuk itu Anda perlu menggunakan pengulangan di dalam bahasa pemrograman Python.

Di dalam bahasa pemrograman Python pengulangan dibagi menjadi 3 bagian, yaitu :
- While Loop
- For Loop
- Nested Loop

### While Loop
Pengulangan While Loop di dalam bahasa pemrograman Python dieksesusi statement berkali-kali selama kondisi bernilai benar atau `True`.

Dibawah ini adalah contoh penggunaan pengulangan While Loop.

```

#Contoh penggunaan While Loop

count = 0
while (count < 9):
    print ('The count is:', count)
    count = count + 1

print ("Good bye!")

```
### For Loop
Pengulangan `for` pada Python memiliki kemampuan untuk mengulangi item dari urutan apapun, seperti `list` atau `string`.

Dibawah ini adalah contoh penggunaan pengulangan While Loop.
```

#Contoh pengulangan for sederhana
angka = [1,2,3,4,5]
for x in angka:
    print(x)

#Contoh pengulangan for
buah = ["nanas", "apel", "jeruk"]
for makanan in buah:
    print("Saya suka makan", makanan)

```
### Nested Loop
Bahasa pemrograman Python memungkinkan penggunaan satu lingkaran di dalam loop lain. Bagian berikut menunjukkan beberapa contoh untuk menggambarkan konsep tersebut. 

Dibawah ini adalah contoh penggunaan Nested Loop.
```

#Contoh penggunaan Nested Loop

i = 2
while(i < 100):
    j = 2
    while(j <= (i/j)):
        if not(i%j): break
        j = j + 1
    if (j > i/j) : print(i, " is prime")
    i = i + 1

print "Good bye!"

```

# Number

Number adalah tipe data Python yang menyimpan nilai numerik. Number adalah tipe data yang tidak berubah. Ini berarti, mengubah nilai dari sejumlah tipe data akan menghasilkan objek yang baru dialokasikan.

Objek Number dibuat saat Anda memberikan nilai pada-nya. Sebagai contoh : `angkaPertama = 1`
`angkaKedua = 33 `

Python mendukung beberapa tipe data Number diantaranya :
- Int
- Float
- Complex

Berikut ini adalah beberapa contoh dari Tipe data Number pada Python :

| Int |	Float |	Complex |
| --- | --- | --- |
| 20 |	0.1 |	3.14j |
| 300 |	1.20 |	35.j |
| -13 |	-41.2 |	3.12e-12j |
| 020 |	32.23+e123 |	.873j |
| -0103 |	-92. |	-.123+0J |
| -0x212 |	-32.52e10 |	3e+123J |
| 0x56 |	60.2-E13 |	4.31e-4j |


### Konversi Tipe Data Number Python
Pada Python Anda bisa mengkonversi tipe data dengan menggunakan fungsi. Dibawah ini adalah beberapa fungsi untuk mengkonversi tipe data number Python. 
- `int(x)`
untuk meng-konversi x menjadi plain integer.
- `long(x)`
untuk meng-konversi x menjadi long integer.
- `float(x)`
untuk meng-konversi x menjadi floating point number.
- `complex(x)`
untuk meng-konversi x menjadi complex number dengna real part x dan imaginary part zero.
- `complex(x, y)`
untuk meng-konversi x dan y menjadi complex number dengan real part x dan imaginary part y. x dan numeric expressions y. 


### Fungsi Matematika Python
Pada bahasa pemrograman Python terdapat fungsi untuk melakukan perhitungan matematis, berikut adalah daftarnya :

| Nama |	Penggunaan |	Penjelasan |
| --- | --- | --- |
| Absolute |	`abs(x)` |	Nilai absolut dari x:(positive) jarak antara x and 0. |
| Ceiling |	`ceil(x)` |	Ceiling dari x: integer terkecil yang kurang dari x. |
| Cmp |	`cmp(x, y)` |	-1 if x < y, 0 if x == y, or 1 if x > y. Tidak berlaku lagi dengan Python 3. Sebaliknya gunakan return (x>y)-(x |
| Eksponen |	`exp(x)` |	Nilai eksponen dari x: ex |
| Fabs |	`fabs(x)` |	Nilai absolut dari x. |
| Floor |	`floor(x)` |	The floor of x: the largest integer not greater than x. |
| Floor |	`floor(x)` |	Nilai dasar dari x: internet terbesar tidak lebih besar dari x. |
| Log |	`log(x)` |	Logaritma dari x, untuk x > 0. |
| Log 10 |	`log10(x)` |	Basis 10 logaritma dari x, untuk x > 0. |
| Max |	`max(x1, x2,...)`	 | Argumen terbesar: Nilai terdekat dengan tak terhingga positif |
| Min |	`min(x1, x2,...)` |	Argumen terkecil: nilai yang paling mendekati tak berhingga negatif. |
| Modf |	`modf(x)` |	Bagian pecahan dan bilangan bulat dari x dalam tupel dua item. Kedua bagian memiliki tanda yang sama dengan x. Bagian integer dikembalikan sebagai float. |
| Pow |	`pow(x, y)` |	Nilai x ** y. |
| Round |	`round(x [,n])` |	X dibulatkan menjadi n digit dari titik desimal. Putaran Python jauh dari nol sebagai tie-breaker: round (0.5) adalah 1.0 dan round (-0.5) adalah -1.0. |
| Akar Kuadrat |	`sqrt(x)` |	Akar kuadrat x untuk x> 0. |


### Fungsi Nomor Acak Python
Nomor acak digunakan untuk aplikasi permainan, simulasi, pengujian, keamanan, dan privasi. Python mencakup fungsi berikut yang umum digunakan. Berikut adalah daftarnya :

| Nama | 	Penggunaan | 	Penjelasan | 
| --- | --- | --- |
| Choice | 	`choice(seq)` | 	Item acak dari list, tuple, atau string. | 
| RandRange | 	`randrange ([start,] stop [,step])` | 	Elemen yang dipilih secara acak dari jangkauan (start, stop, step). | 
| Random | 	`random()` | 	A random float r, sehingga 0 kurang dari atau sama dengan r dan r kurang dari 1 | 
| Seed | 	`seed([x])` | 	Menetapkan nilai awal integer yang digunakan dalam menghasilkan bilangan acak. Panggil fungsi ini sebelum memanggil fungsi modul acak lainnya. Tidak ada pengembalian | 
| Shuffle | 	`shuffle(lst)` | 	Mengacak daftar dari daftar di tempat. Tidak ada pengembalian | 
| Floor	| `floor(x)`	 | The floor of x: the largest integer not greater than x. | 
| Uniform| 	`uniform(x, y)` | 	Sebuah float acak r, sedemikian rupa sehingga x kurang dari atau sama dengan r dan r kurang dari y. | 


### Fungsi Trigonometri Python
Python mencakup fungsi berikut yang melakukan perhitungan trigonometri. Berikut adalah daftarnya :
```
| Nama |	Penggunaan	Penjelasan |
| --- | --- | --- |
| Acos |	`acos(x)` |	Kembalikan kosinus x, di radian. |
| Asin |	`asin(x)` |	Kembalikan busur sinus x, dalam radian. |
| Atan |	`atan(x)` |	Kembalikan busur singgung x, di radian. |
| Atan 2 |	`atan2(y, x)`	 | Kembali atan (y / x), di radian. |
| Kosinus |	`cos(x)` |	Kembalikan kosinus x radian. |
| Hypot	 | `hypot(x, y)` |	Kembalikan norma Euclidean, sqrt (x * x + y * y). |
| Sin |	`sin(x)` |	Kembalikan sinus dari x radian. |
| Tan |	`tan(x)` |	Kembalikan tangen x radian. |
| Derajat |	`degrees(x)` |	Mengonversi sudut x dari radian ke derajat. |
| Radian |	`radians(x)` |	Mengonversi sudut x dari derajat ke radian. |
```
### Konstanta Matematika Python
Modul ini juga mendefinisikan dua konstanta matematika. Berikut adalah daftarnya :

| Nama |	Penggunaan	| Penjelasan| 
| --- | --- | --- |
| Pi	| `pi`	| Konstanta Pi matematika| 
| e	| `e`	| Konstanta e matematika| 

# String

String adalah jenis yang paling populer di bahasa pemrograman. Kita bisa membuatnya hanya dengan melampirkan karakter dalam tanda kutip. Python memperlakukan tanda kutip tunggal sama dengan tanda kutip ganda. Membuat string semudah memberi nilai pada sebuah variabel.

Dibawah ini adalah contoh sederhana dari sebuah string pada bahasa pemrograman Python.
```

print("Hello World")

```
### Mengakses Nilai dalam String

Python tidak menggunakan tipe karakter titik koma ; Ini diperlakukan sebagai string dengan panjang satu, sehingga juga dianggap sebagai substring.

Untuk mengakses substring, gunakan tanda kurung siku untuk mengiris beserta indeks atau indeks untuk mendapatkan substring Anda. Sebagai contoh : 
```

name = 'John Doe' message = "John Doe belajar bahasa python di Belajarpython"
print ("name[0]: ", name[0])
print ("message[1:4]: ", message[1:4])

```
Bila kode diatas dieksekusi, maka akan menghasilkan hasil sebagai berikut :

`name[0]: J`
`message[1:4]: ohn `


### Mengupdate String

Anda dapat "memperbarui" string yang ada dengan (kembali) menugaskan variabel ke string lain. Nilai baru dapat dikaitkan dengan nilai sebelumnya atau ke string yang sama sekali berbeda sama sekali. Sebagai contoh
```

message = 'Hello World'
print ("Updated String :- ", message[:6] + 'Python')

```
Bila kode diatas dieksekusi, maka akan menghasilkan hasil sebagai berikut :

`Updated String :- Hello Python`

### Escape Characters / Karakter Escape Python

Dibawah ini adalah tabel dari daftar karakter escape atau karakter non-printable yang dapat diwakili/ditulis dengan awalan notasi backslash.

| Notasi Backslash	 | Karakter Hexadecimal	 | Penjelasan |
| --- | --- | --- |
| \a | 	0x07 | 	Bell atau alert |
| \b | 	0x08 | 	Backspace |
| \cx | 	 | 	Control-x |
| \C-x	 |  | 	Control-x |
| \e | 	0x1b | 	Escape |
| \f | 	0x0c | 	Formfeed |
| \M-\C-x | 	 | 	Meta-Control-x |
| \n | 	0x0a | 	Newline |
| \nnn | 	 | 	Octal notation, dimana n berada di range 0.7 |
| \r | 	0x0d | 	Carriage return |
| \s | 	0x20 | 	Space |
| \t | 	0x09 | 	Tab |
| \v | 	0x0b | 	Vertical tab |
| \x | 	 | 	Character x |
| \xnn	 |   | 	Notasi Hexadecimal, dimana n berada di range 0.9, a.f, atau A.F |


### Operator Spesial String Python

Asumsikan variabel string adalah 'Belajar' dan variabel b adalah 'Python', lalu dibawah ini adalah operator yang bisa dipakai pada kedua string di variabel tersebut. `a = "Belajar"` `b = "Python"`


Berikut adalah daftar operator spesial string pada Python : 

| Operator | 	Contoh	Penjelasan | 
| --- | --- | --- |
| + | 	a + b  | akan menghasilkan BelajarPython	Concatenation - Menambahkan nilai pada kedua sisi operator | 
| * | 	a*2  | akan menghasilkan BelajarBelajar	Pengulangan - Membuat string baru, menggabungkan beberapa salinan dari string yang sama | 
| [] | 	a[1]  | akan menghasilkan e	Slice - Memberikan karakter dari indeks yang diberikan | 
| [ : ] | 	a[1:4]  | akan menghasilkan ela	Range Slice - Memberikan karakter dari kisaran yang diberikan | 
| in | 	B in a  | akan menghasilkan 1	Keanggotaan - Mengembalikan nilai true jika ada karakter dalam string yang diberikan | 
| not in | 	Z not in a  | akan menghasilkan 1	Keanggotaan - Mengembalikan nilai true jika karakter tidak ada dalam string yang diberikan | 
| r/R | 	print r'\n' prints \n dan print R'\n'prints \n	Raw String -  | Menekan arti aktual karakter Escape. Sintaks untuk string mentah sama persis dengan string biasa kecuali operator string mentah, huruf "r", yang mendahului tanda petik. "R" bisa berupa huruf kecil (r) atau huruf besar (R) dan harus ditempatkan tepat sebelum tanda kutip pertama. | 
| %	 |  | 	Format - Melakukan format String | 

### Operator Format String Python

Salah satu fitur Python yang paling keren adalah format string operator %. Operator ini unik untuk string dan membuat paket memiliki fungsi dari keluarga printf C () C. 
berikut adalah contoh sederhananya : `print ("My name is %s and weight is %d kg!" % ('Zara', 21)) `


Berikut adalah daftar lengkap simbol yang bisa digunakan bersamaan dengan % : 

| Operator | 	Penjelasan | 
| --- | --- |
| %c | 	character | 
| %s | 	Konversi string melalui str () sebelum memformat | 
| %i | 	Dianggap sebagai bilangan bulat desimal | 
| %d | 	Dianggap sebagai bilangan bulat desimal | 
| %u | 	Unsigned decimal integer | 
| %o | 	Bilangan bulat oktal | 
| %x | 	Bilangan bulat heksadesimal (huruf kecil) | 
| %X | 	Bilangan bulat heksadesimal (huruf besar) | 
| %e | 	Notasi eksponensial (dengan huruf kecil 'e') | 
| %E | 	Notasi eksponensial (dengan huruf besar 'E') | 
| %f | 	Bilangan real floating point | 
| %g | 	Yang lebih pendek dari% f dan% e | 
| %G | 	Lebih pendek dari% f dan% E | 

### Triple Quote Python

Python triple quotes digunakan dengan membiarkan string untuk ditulis dalam beberapa baris, termasuk kata kerja NEWLINEs, TABs, dan karakter khusus lainnya. 
Sintaks untuk triple quotes terdiri dari tiga tanda kutip tunggal atau ganda ditulis berturut-turut :
Berikut adalah contohnya : 
```

kutipantiga = """this is a long string that is made up of
several lines and non-printable characters such as
TAB ( \t ) and they will show up that way when displayed.
NEWLINEs within the string, whether explicitly given like
this within the brackets [ \n ], or just a NEWLINE within
the variable assignment will also show up.
"""
print (kutipantiga)

```
### String Unicode Python

Pada Python 3, semua string diwakili dalam Unicode. Sedangkan pada Python 2 disimpan secara internal sebagai 8-bit ASCII, maka diperlukanlampiran 'u' untuk membuatnya menjadi Unicode. Tetapi hal ini tidak lagi diperlukan sekarang. :

Metode String Built-in

Python menyertakan metode built-in berikut untuk memanipulasi string 

| Metode | 	Penjelasan | 
| --- | --- |
| `capitalize()` | 	Meng-kapitalkan huruf pertama string | 
| `center(width, fillchar)` | 	Mengembalikan string yang dilapisi dengan fillchar dengan string asli yang dipusatkan pada total width kolom. | 
| `count(str, beg = 0,end = len(string))`	 | Menghitung berapa kali str yang terjadi dalam string atau dalam substring string jika memulai indeks beg dan end index end diberikan. | 
| `decode(encoding = 'UTF-8',errors = 'strict')`	 | Dekode string menggunakan codec yang terdaftar untuk pengkodean. Encoding default ke pengkodean string default. | 
| `encode(encoding = 'UTF-8',errors = 'strict')`	 | Mengembalikan versi string yang dikodekan string; Pada kesalahan, default adalah menaikkan ValueError kecuali jika kesalahan diberikan dengan 'ignore' atau 'replace'. | 
| `endswith(suffix, beg = 0, end = len(string))`	 | Menentukan apakah string atau substring string (jika memulai indeks memohon dan mengakhiri akhir indeks diberikan) berakhir dengan akhiran; Mengembalikan nilai true jika benar dan salah. | 
| `expandtabs(tabsize = 8)`	 | Memperluas tab dalam string ke banyak ruang; Default ke 8 spasi per tab jika tabsize tidak tersedia. | 
| `find(str, beg = 0 end = len(string))`	 | Tentukan jika str terjadi dalam string atau dalam substring string jika memulai indeks beg dan end index end diberikan return index jika ditemukan dan -1 sebaliknya. | 
| `index(str, beg = 0, end = len(string))`	 | Sama seperti find (), namun menimbulkan pengecualian jika str tidak ditemukan. | 
| `isalnum()`	 | Mengembalikan true jika string memiliki minimal 1 karakter dan semua karakternya alfanumerik dan false sebaliknya. | 
| `isalpha()`	 | Mengembalikan true jika string memiliki minimal 1 karakter dan semua karakter adalah abjad dan false sebaliknya. | 
| `isdigit()`	 | Mengembalikan true jika string hanya berisi digit dan false sebaliknya. | 
| `islower()`	 | Mengembalikan true jika string memiliki setidaknya 1 karakter casing dan semua karakter casing dalam huruf kecil dan false sebaliknya. | 
| `isnumeric()`	 | Mengembalikan true jika string unicode hanya berisi karakter numerik dan false sebaliknya. | 
| `isspace()`	 | Mengembalikan true jika string hanya berisi karakter spasi dan false sebaliknya. | 
| `istitle()` | 	Mengembalikan true jika string benar "titlecased" dan false sebaliknya. | 
| `isupper()`	 | Mengembalikan true jika string memiliki setidaknya satu karakter casing dan semua karakter casing ada dalam huruf besar dan false sebaliknya. | 
| `join(seq)` | 	Merges (concatenates) representasi string elemen dalam urutan seq menjadi string, dengan string pemisah. | 
| `len(string)`	 | Mengembalikan panjang string | 
| `ljust(width[, fillchar])`	 | Mengembalikan string berlapis ruang dengan string asli dibiarkan dibenarkan ke kolom lebar total. | 
| `lower()` | 	Mengonversi semua huruf besar dalam bentuk string menjadi huruf kecil. | 
| `lstrip()` | 	Menghapus semua spasi utama dalam string. | 
| `maketrans()` | 	Mengembalikan tabel terjemahan untuk digunakan dalam fungsi terjemahan. | 
| `max(str)` | 	Mengembalikan karakter alfabetik dari string str. | 
| `min(str)`	 | Mengembalikan min karakter abjad dari string str. | 
| `replace(old, new [, max])`	 | Menggantikan semua kemunculan lama dalam string dengan kejadian baru atau paling maksimal jika max diberikan. | 
| `rfind(str, beg = 0,end = len(string))`	 | Sama seperti find (), tapi cari mundur dalam string. | 
| `rindex( str, beg = 0, end = len(string))`	 | Sama seperti index (), tapi cari mundur dalam string. | 
| `rjust(width,[, fillchar])`	 | Mengembalikan string berlapis ruang dengan senar asli benar-dibenarkan untuk total kolom lebar. | 
| `rstrip()` | 	Menghapus semua spasi spasi string. | 
| `split(str="", num=string.count(str))`	 | Membagi string sesuai dengan pemisah str (ruang jika tidak disediakan) dan mengembalikan daftar substring; Terpecah menjadi paling banyak substring jika diberikan. | 
| `splitlines( num=string.count('\n')) `| 	Membagi string sama sekali (atau num) NEWLINEs dan mengembalikan daftar setiap baris dengan NEWLINEs dihapus. | 
| `startswith(str, beg=0,end=len(string)`		 | Determines if string or a substring of string (if starting index beg and ending index end are given) starts with substring str; returns true if so and false otherwise. | 
| `strip([chars])`		 | Lakukan kedua lstrip () dan rstrip () pada string | 
| `swapcase()`	 | 	Kasus invers untuk semua huruf dalam string. | 
| `title()`		 | Mengembalikan versi string "titlecased", yaitu, semua kata diawali dengan huruf besar dan sisanya huruf kecil. | 
| `translate(table, deletechars="")	`	 | Menerjemahkan string sesuai dengan tabel terjemahan str (256 karakter), menghapus string del. | 
| `upper()`	 | 	Mengonversi huruf kecil dalam bentuk string ke huruf besar. | 
| `zfill (width)`	 | 	Mengembalikan string asli yang tertinggal dengan angka nol ke total karakter lebar; Dimaksudkan untuk angka, zfill () mempertahankan tanda apapun yang diberikan (kurang satu nol). | 
| `isdecimal()`	 | 	Mengembalikan nilai true jika string unicode hanya berisi karakter desimal dan false sebaliknya. | 

# List

Dalam bahasa pemrograman Python, struktur data yang paling dasar adalah urutan atau lists. Setiap elemen-elemen berurutan akan diberi nomor posisi atau indeksnya. Indeks pertama dalam list adalah nol, indeks kedua adalah satu dan seterusnya.

Python memiliki enam jenis urutan built-in, namun yang paling umum adalah list dan tuple. Ada beberapa hal yang dapat Anda lakukan dengan semua jenis list. Operasi ini meliputi pengindeksan, pengiris, penambahan, perbanyak, dan pengecekan keanggotaan. Selain itu, Python memiliki fungsi built-in untuk menemukan panjang list dan untuk menemukan elemen terbesar dan terkecilnya.

### Membuat List Python

List adalah tipe data yang paling serbaguna yang tersedia dalam bahasa Python, yang dapat ditulis sebagai daftar nilai yang dipisahkan koma (item) antara tanda kurung siku. Hal penting tentang daftar adalah item dalam list tidak boleh sama jenisnya.

Membuat list sangat sederhana, tinggal memasukkan berbagai nilai yang dipisahkan koma di antara tanda kurung siku. Dibawah ini adalah contoh sederhana pembuatan list dalam bahasa Python.
```go

#Contoh sederhana pembuatan list pada bahasa pemrograman python
list1 = ['kimia', 'fisika', 1993, 2017]
list2 = [1, 2, 3, 4, 5 ]
list3 = ["a", "b", "c", "d"]

```
### Akses Nilai Dalam List Python

Untuk mengakses nilai dalam list python, gunakan tanda kurung siku untuk mengiris beserta indeks atau indeks untuk mendapatkan nilai yang tersedia pada indeks tersebut.

Berikut adalah contoh cara mengakses nilai di dalam list python :

```

#Cara mengakses nilai di dalam list Python

list1 = ['fisika', 'kimia', 1993, 2017]
list2 = [1, 2, 3, 4, 5, 6, 7 ]

print ("list1[0]: ", list1[0])
print ("list2[1:5]: ", list2[1:5])

```
Setelah Anda mengeksekusi kode diatas, hasilnya akan seperti dibawah ini :

`list1[0]: fisika`
`list2[1:5]: [2, 3, 4, 5]`

### Update Nilai Dalam List Python

Anda dapat memperbarui satu atau beberapa nilai di dalam list dengan memberikan potongan di sisi kiri operator penugasan, dan Anda dapat menambahkan nilai ke dalam list dengan metode append (). Sebagai contoh :

```

list = ['fisika', 'kimia', 1993, 2017]
print ("Nilai ada pada index 2 : ", list[2])

list[2] = 2001
print ("Nilai baru ada pada index 2 : ", list[2])

```
### Hapus Nilai Dalam List Python

Untuk menghapus nilai di dalam list python, Anda dapat menggunakan salah satu pernyataan del jika Anda tahu persis elemen yang Anda hapus. Anda dapat menggunakan metode remove() jika Anda tidak tahu persis item mana yang akan dihapus. Sebagai contoh :
```

#Contoh cara menghapus nilai pada list python

list = ['fisika', 'kimia', 1993, 2017]

print (list)
del list[2]
print ("Setelah dihapus nilai pada index 2 : ", list)

```
### Operasi Dasar Pada List Python

List Python merespons operator + dan * seperti string; Itu artinya penggabungan dan pengulangan di sini juga berlaku, kecuali hasilnya adalah list baru, bukan sebuah String.

Sebenarnya, list merespons semua operasi urutan umum yang kami gunakan pada String di bab sebelumnya. Dibawah ini adalah tabel daftar operasi dasar pada list python.

| Python Expression	| Hasil		| Penjelasan	| 
| --- | --- | --- |
| `len([1, 2, 3, 4])`		| `4`	| Length	| 
| `[1, 2, 3] + [4, 5, 6]`	| 	`[1, 2, 3, 4, 5, 6]`	| 	Concatenation	| 
| `['Halo!'] * 4`		| `['Halo!', 'Halo!', 'Halo!', 'Halo!']`	| 	Repetition	| 
| `2 in [1, 2, 3]`	| `	True`	| 	Membership	| 
| `for x in [1,2,3] : print (x,end = ' ')`	| 	`1 2 3`		| Iteration	| 

### Indexing, Slicing dan Matrix Pada List Python

Karena list adalah urutan, pengindeksan dan pengiris bekerja dengan cara yang sama untuk list seperti yang mereka lakukan untuk String.

Dengan asumsi input berikut :

`L = ['C++'', 'Java', 'Python']`

 | Python Expression | 	Hasil | 	Penjelasan | 
 | --- | --- | --- | 
 | `L[2]`	 | `'Python'` | 	Offset mulai dari nol | 
 | `L[-2]` | 	`'Java'` | 	Negatif: hitung dari kanan | 
 | `[1:]`	 | `['Java', 'Python']` | 	Slicing mengambil bagian | 
 
### Method dan Fungsi Build-in Pada List Python

Python menyertakan fungsi built-in sebagai berikut :

| Python Function | 	Penjelasan | 
| --- | --- |
| cmp(list1, list2)	# |  Tidak lagi tersedia dengan Python 3 | 
| len(list)	 | Memberikan total panjang list. | 
| max(list)	 | Mengembalikan item dari list dengan nilai maks. | 
| min(list)	 | Mengembalikan item dari list dengan nilai min. | 
| list(seq)	 | Mengubah tuple menjadi list. | 

Python menyertakan methods built-in sebagai berikut

 | Python Methods | 	Penjelasan | 
 | --- | --- | 
 | list.append(obj)	 | Menambahkan objek obj ke list | 
 | list.count(obj) | 	Jumlah pengembalian berapa kali obj terjadi dalam list | 
 | list.extend(seq) | 	Tambahkan isi seq ke list | 
 | list.index(obj) | 	Mengembalikan indeks terendah dalam list yang muncul obj | 
 | list.insert(index, obj)	 | Sisipkan objek obj ke dalam list di indeks offset | 
 | list.pop(obj = list[-1])	 | Menghapus dan mengembalikan objek atau obj terakhir dari list | 
 | list.remove(obj) | 	Removes object obj from list | 
 | list.reverse() | 	Membalik list objek di tempat | 
 | list.sort([func])	 | Urutkan objek list, gunakan compare func jika diberikan | 
 
 # Tuple
 
 Sebuah tupel adalah urutan objek Python yang tidak berubah. Tupel adalah urutan, seperti daftar. Perbedaan utama antara tupel dan daftarnya adalah bahwa tupel tidak dapat diubah tidak seperti List Python. Tupel menggunakan tanda kurung, sedangkan List Python menggunakan tanda kurung siku.

Membuat tuple semudah memasukkan nilai-nilai yang dipisahkan koma. Secara opsional, Anda dapat memasukkan nilai-nilai yang dipisahkan koma ini di antara tanda kurung juga. Sebagai contoh : 


```

#Contoh sederhana pembuatan tuple pada bahasa pemrograman python

tup1 = ('fisika', 'kimia', 1993, 2017)
tup2 = (1, 2, 3, 4, 5 )
tup3 = "a", "b", "c", "d"

```
Tupel kosong ditulis sebagai dua tanda kurung yang tidak berisi apa-apa, contohnya : tup1 = ();
Untuk menulis tupel yang berisi satu nilai, Anda harus memasukkan koma, meskipun hanya ada satu nilai, contohnya : tup1 = (50,)
Seperti indeks String, indeks tuple mulai dari 0, dan mereka dapat diiris, digabungkan, dan seterusnya

### Akses Nilai Dalam Tuple Python

Untuk mengakses nilai dalam tupel, gunakan tanda kurung siku untuk mengiris beserta indeks atau indeks untuk mendapatkan nilai yang tersedia pada indeks tersebut. Sebagai contoh :

```

#Cara mengakses nilai tuple

tup1 = ('fisika', 'kimia', 1993, 2017)
tup2 = (1, 2, 3, 4, 5, 6, 7 )

print ("tup1[0]: ", tup1[0])
print ("tup2[1:5]: ", tup2[1:5])

```
Setelah Anda mengeksekusi kode diatas, hasilnya akan seperti dibawah ini :

`tup1[0]: fisika`
`tup2[1:5]: (2, 3, 4, 5)`

### Update Nilai Dalam Tuple Python

Tuple tidak berubah, yang berarti Anda tidak dapat memperbarui atau mengubah nilai elemen tupel. Anda dapat mengambil bagian dari tupel yang ada untuk membuat tupel baru seperti ditunjukkan oleh contoh berikut.

```

tup1 = (12, 34.56)
tup2 = ('abc', 'xyz')

# Aksi seperti dibawah ini tidak bisa dilakukan pada tuple python
# Karena memang nilai pada tuple python tidak bisa diubah
# tup1[0] = 100;

# Jadi, buatlah tuple baru sebagai berikut
tup3 = tup1 + tup2
print (tup3)

```
### Hapus Nilai Dalam Tuple Python

Menghapus elemen tuple individual tidak mungkin dilakukan. Tentu saja, tidak ada yang salah dengan menggabungkan tupel lain dengan unsur-unsur yang tidak diinginkan dibuang.

Untuk secara eksplisit menghapus keseluruhan tuple, cukup gunakan del statement. Sebagai contoh

```

tup = ('fisika', 'kimia', 1993, 2017);

print (tup)
del tup;
print "Setelah menghapus tuple : "
print tup

```

### Operasi Dasar Pada Tuple Python

Tupel merespons operator + dan * sama seperti String; Mereka berarti penggabungan dan pengulangan di sini juga berlaku, kecuali hasilnya adalah tupel baru, bukan string.

Sebenarnya, Tuple merespons semua operasi urutan umum yang kami gunakan pada String di bab sebelumnya. Dibawah ini adalah tabel daftar operasi dasar pada Tuple python


| Python Expression	 | Hasil | 	Penjelasan | 
| --- | --- | --- | 
| len((1, 2, 3)) | 	3 | 	Length | 
| (1, 2, 3) + (4, 5, 6) | 	(1, 2, 3, 4, 5, 6) | 	Concatenation | 
| ('Halo!',) * 4 | 	('Halo!', 'Halo!', 'Halo!', 'Halo!') | 	Repetition | 
| 3 in (1, 2, 3) | 	True | 	Membership | 
| for x in (1,2,3) : print (x, end = ' ') | 	1 2 3 | 	Iteration | 

### Indexing, Slicing dan Matrix Pada Tuple Python

Karena tupel adalah urutan, pengindeksan dan pengiris bekerja dengan cara yang sama untuk tupel seperti pada String, dengan asumsi masukan berikut

Dengan asumsi input berikut : `T = ('C++', 'Java', 'Python')`

 | Python Expression | 	Hasil | 	Penjelasan |
 | --- | --- | --- |
 | `T[2]` | 	`'Python'` | 	Offset mulai dari nol | 
 | `T[-2]` | 	`'Java'`	 | Negatif: hitung dari kanan | 
 | `T[1:]` | 	`('Java', 'Python')` | 	Slicing mengambil bagian | 

### Fungsi Build-in Pada Tuple Python

Python menyertakan fungsi built-in sebagai berikut

| Python Function |	Penjelasan |	
| --- | --- |
| `cmp(tuple1, tuple2)` |		# Tidak lagi tersedia dengan Python 3 |	
| `len(tuple)` |		Memberikan total panjang tuple. |	
| `max(tuple)` |		Mengembalikan item dari tuple dengan nilai maks. |	
| `min(tuple)` |		Mengembalikan item dari tuple dengan nilai min. |	
| `tuple(seq)` |		Mengubah tuple menjadi tuple. |

# Dictionary

Dictionary Python berbeda dengan List ataupun Tuple. Karena setiap urutanya berisi key dan value. Setiap key dipisahkan dari value-nya oleh titik dua (:), item dipisahkan oleh koma, dan semuanya tertutup dalam kurung kurawal. Dictionary kosong tanpa barang ditulis hanya dengan dua kurung kurawal, seperti ini: {}.

Nilai kamus bisa berupa tipe apa pun, namun key harus berupa tipe data yang tidak berubah seperti string, angka, atau tupel.

### Akses Nilai Dalam Dictionary Python

Untuk mengakses elemen Dictionary, Anda dapat menggunakan tanda kurung siku yang sudah dikenal bersama dengan key untuk mendapatkan nilainya. Berikut adalah contoh sederhananya :

```

#Contoh cara membuat Dictionary pada Python

dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'}
print ("dict['Name']: ", dict['Name'])
print ("dict['Age']: ", dict['Age'])

```
### Update Nilai Dalam Dictionary Python

Anda dapat memperbarui Dictionary dengan menambahkan entri baru atau pasangan nilai kunci, memodifikasi entri yang ada, atau menghapus entri yang ada seperti ditunjukkan pada contoh sederhana yang diberikan di bawah ini.


```

#Update dictionary python

dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'}
dict['Age'] = 8; # Mengubah entri yang sudah ada
dict['School'] = "DPS School" # Menambah entri baru

print ("dict['Age']: ", dict['Age'])
print ("dict['School']: ", dict['School'])

```
### Hapus Elemen Dictionary Python

Anda dapat menghapus elemen Dictionary individual atau menghapus keseluruhan isi Dictionary. Anda juga dapat menghapus seluruh Dictionary dalam satu operasi.

Untuk menghapus seluruh Dictionary secara eksplisit, cukup gunakan del statement. Berikut adalah contoh sederhana :

```

#Contoh cara menghapus pada Dictionary Python

dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'}

del dict['Name'] # hapus entri dengan key 'Name'
dict.clear()     # hapus semua entri di dict
del dict         # hapus dictionary yang sudah ada

print ("dict['Age']: ", dict['Age'])
print ("dict['School']: ", dict['School'])

```
### Fungsi Build-in Pada Dictionary Python

Python menyertakan fungsi built-in sebagai berikut :

| Fungsi Python | 	Penjelasan | 
| --- | --- |
| cmp(dict1, dict2)	 | Membandingkan unsur keduanya. | 
| len(dict)	 | Memberikan panjang total Dictionary. Ini sama dengan jumlah item dalam Dictionary. | 
| str(dict) | 	Menghasilkan representasi string yang dapat dicetak dari Dictionary | 
| type(variable)	 | Mengembalikan tipe variabel yang lulus. Jika variabel yang dilewatkan adalah Dictionary, maka akan mengembalikan tipe Dictionary. | 


### Method Build-in Pada Dictionary Python

Python menyertakan method built-in sebagai berikut :

 | Method Python | 	Penjelasan | 
 | --- | --- |
 | dict.clear() | 	Menghapus semua elemen Dictionary | 
 | dict.copy()	 | Mengembalikan salinan Dictionary | 
 | dict.fromkeys() | 	Buat Dictionary baru dengan kunci dari seq dan nilai yang disetel ke nilai. | 
 | dict.get(key, default=None)	 | For key, nilai pengembalian atau default jika tombol tidak ada dalam Dictionary | 
 | dict.has_key(key) | 	Mengembalikan true jika key dalam Dictionary, false sebaliknya | 
 | dict.items() | 	Mengembalikan daftari dari pasangan tuple dictionary (key, value) | 
 | dict.keys()	 | Mengembalikan daftar key dictionary | 
 | dict.setdefault(key, default=None) | 	Mirip dengan get (), tapi akan mengatur dict [key] = default jika kunci belum ada di dict |
 | dict.update(dict2) | 	Menambahkan pasangan kunci kata kunci dict2 ke dict | 
 | dict.values() | 	Mengembalikan daftar nilai dictionary | 
 
 # Tanggal dan Waktu
 
 Program Python dapat menangani tanggal dan waktu dengan beberapa cara. Konversi antara format tanggal adalah tugas umum untuk komputer. Modul waktu dan kalender Python melacak tanggal dan waktu.

### Apa itu Tick?

Interval waktu adalah bilangan floating-point dalam satuan detik. Instansi tertentu dalam waktu dinyatakan dalam hitungan detik sejak pukul 12:00 1 Januari 1970.

Dibawah ini adalah contoh penggunanaya.

```

import time;  # Digunakan untuk meng-import modul time

ticks = time.time()
print "Berjalan sejak 12:00am, January 1, 1970:", ticks

```
### Apa itu TimeTuple Python?

Banyak fungsi waktu Python menangani waktu sebagai tuple dari 9 nomor, seperti yang terdapat pada tabel di bawah ini.

 | Index | 	Field	 | Value | 
 | --- | --- | --- |
 | 0 | 	4-digit year | 	2008 | 
 | 1 | 	Bulan | 	1 sampai 12 | 
 | 2 | 	Hari | 	1 sampai 31 | 
 | 3 | 	Jam | 	0 sampai 23 | 
 | 4 | 	Menit | 	0 sampai 59 | 
 | 5 | 	Detik | 	0 sampai 61 | 
 | 6 | 	Hari dalam Minggu | 	0 sampai 6 (0 adalah Senin) | 
 | 7 | 	Hari dalam Bulan | 	1 sampai 366 | 
 | 8 | 	Daylight savings | 	-1, 0, 1, -1 means library determines DST | 

Tuple di atas setara dengan struktur struct_time. Struktur ini memiliki atribut berikut

 | Index | 	Atribut	 | Value | 
 | --- | --- | --- |
 | 0 | 	tm_year	 | 2008 | 
 | 1 | 	tm_mon | 	1 sampai 12 | 
 | 2 | 	tm_mday	 | 1 sampai 31 | 
 | 3 | 	tm_hour | 	0 sampai 23 | 
 | 4 | 	tm_min | 	0 sampai 59 | 
 | 5 | 	tm_sec | 	0 sampai 61 | 
 | 6 | 	tm_wday | 	0 sampai 6 (0 adalah Senin) | 
 | 7 | 	tm_yday | 	1 sampai 366 | 
 | 8 | 	tm_isdst | 	-1, 0, 1, -1 means library determines DST | 

### Mendapatkan Waktu Saat Ini

Untuk menerjemahkan waktu instan dari satu detik sejak nilai floating-point ke waktu menjadi tupel waktu, lewati nilai floating-point ke fungsi (mis., Localtime) yang mengembalikan waktu tupel dengan semua sembilan item valid.

```

import time;

localtime = time.localtime(time.time())
print "Waktu lokal saat ini :", localtime

```
### Mendapatkan Waktu yang berformat

Anda dapat memformat kapan saja sesuai kebutuhan Anda, namun metode sederhana untuk mendapatkan waktu dalam format yang mudah dibaca adalah asctime ()

```

import time;

localtime = time.asctime( time.localtime(time.time()) )
print "Waktu lokal saat ini :", localtime

```
### Mendapatkan kalender dalam sebulan

Modul kalender memberikan berbagai macam metode untuk dimainkan dengan kalender tahunan dan bulanan. Di sini, kami mencetak kalender untuk bulan tertentu (Jan 2008)
```

import calendar

cal = calendar.month(2008, 1)
print "Dibawah ini adalah kalender:"
print cal

```
### Modul time pada Python

Ada modul waktu populer yang tersedia dengan Python yang menyediakan fungsi untuk bekerja dengan waktu dan untuk mengkonversi antara representasi. Dibawah ini adalah tabel dari modul time pada python yang ada.

| Fungsi Python | 	Penjelasan | 
| --- | --- |
| time.altzone | 	Diimbangi zona waktu DST lokal, dalam detik di sebelah barat UTC, jika seseorang didefinisikan. Ini negatif jika zona waktu DST lokal berada di sebelah timur UTC (seperti di Eropa Barat, termasuk Inggris). Gunakan saja ini jika siang hari tidak nol. | 
| time.asctime([tupletime]) | 	Menerima time-tupel dan mengembalikan string 24-karakter yang dapat dibaca seperti 'Tue Dec 11 18:07:14 2008'. | 
| time.clock() | 	Mengembalikan waktu CPU saat ini sebagai jumlah floating-point detik. Untuk mengukur biaya komputasi dari berbagai pendekatan, nilai time.clock lebih bermanfaat daripada time.time (). | 
| time.ctime([secs]) | 	Seperti asctime (localtime (detik)) dan tanpa argumen seperti asctime () | 
| time.gmtime([secs]) | 	Menerima instan yang diungkapkan dalam hitungan detik sejak zaman dan mengembalikan waktu tuple t dengan waktu UTC. Catatan: t.tm_isdst selalu 0 | 
| time.localtime([secs]) | 	Menerima instan yang dinyatakan dalam hitungan detik sejak zaman dan mengembalikan waktu tuple t dengan waktu setempat (t.tm_isdst adalah 0 atau 1, tergantung pada apakah DST berlaku seketika oleh peraturan lokal). | 
| time.mktime(tupletime) | 	Menerima instan dinyatakan sebagai time-tuple di waktu setempat dan mengembalikan nilai floating-point dengan instan yang dinyatakan dalam hitungan detik sejak zaman. | 
| time.sleep(secs) | 	Menangguhkan panggilan untuk beberapa detik. | 
| time.strftime(fmt[,tupletime]) | 	Menerima instan dinyatakan sebagai tupel waktu di waktu lokal dan mengembalikan sebuah string yang mewakili instan seperti yang ditentukan oleh string fmt. | 
| time.strptime(str,fmt='%a %b %d %H:%M:%S %Y')	 | Parses str sesuai dengan format string fmt dan mengembalikan format instant-tuple. | 
| time.time() | 	Mengembalikan waktu saat ini secara instan, jumlah detik mengambang beberapa detik sejak zaman itu. | 
| time.tzset()	 | Mengatur ulang aturan konversi waktu yang digunakan oleh rutinitas perpustakaan. Variabel lingkungan TZ menentukan bagaimana hal ini dilakukan. | 

Ada dua atribut penting yang tersedia dengan modul waktu:

 | Method Python | 	Penjelasan | 
 | --- | --- |
 | time.timezone | 	Atribut time.timezone adalah offset dalam detik zona waktu lokal (tanpa DST) dari UTC (> 0 di Amerika; <= 0 di sebagian besar Eropa, Asia, Afrika). | 
 | time.tzname	 | Atribut time.tzname adalah sepasang string yang bergantung pada lokal, yang merupakan nama zona waktu lokal tanpa dan dengan DST. | 

### Modul calendar pada Python

Modul kalender menyimpan fungsi yang berhubungan dengan kalender, termasuk fungsi untuk mencetak kalender teks untuk bulan atau tahun tertentu.

Secara default, kalender mengambil hari Senin sebagai hari pertama dalam minggu dan minggu sebagai yang terakhir. Untuk mengubah ini, fungsi call calendar.setfirstweekday ().

Berikut adalah daftar fungsi yang tersedia dengan modul kalender:


 | Fungsi Python | 	Penjelasan | 
 | --- | --- |
 | calendar.calendar(year,w=2,l=1,c=6)	 | Mengembalikan string multiline dengan kalender untuk tahun tahun yang diformat menjadi tiga kolom yang dipisahkan oleh ruang c. W adalah lebar karakter setiap tanggal; Setiap baris memiliki panjang 21 * w + 18 + 2 * c. L adalah jumlah baris untuk setiap minggu. | 
 | calendar.firstweekday( )	 | Mengembalikan pengaturan saat ini untuk hari kerja yang dimulai setiap minggu. Secara default, saat kalender pertama kali diimpor, ini adalah 0, yang berarti Senin. | 
 | calendar.isleap(year) | 	Pengembalian True jika tahun adalah tahun kabisat; Jika tidak, False | 
 | calendar.leapdays(y1,y2) | 	Mengembalikan jumlah lompatan hari dalam tahun-tahun dalam rentang (y1, y2). | 
 | calendar.month(year,month,w=2,l=1) | 	Mengembalikan string multiline dengan kalender untuk bulan bulan tahun, satu baris per minggu ditambah dua baris header. W adalah lebar karakter setiap tanggal; Setiap baris memiliki panjang 7 * w + 6. L adalah jumlah baris untuk setiap minggu. | 
 | calendar.monthcalendar(year,month) | 	Mengembalikan daftar daftar int. Setiap sublist menunjukkan seminggu. Hari di luar bulan bulan tahun diatur ke 0; Hari dalam bulan ditetapkan ke hari ke bulan, 1 dan ke atas. | 
 | calendar.monthrange(year,month) | 	Mengembalikan dua bilangan bulat. Yang pertama adalah kode hari kerja untuk hari pertama bulan bulan di tahun; Yang kedua adalah jumlah hari dalam sebulan. Kode hari kerja adalah 0 (Senin) sampai 6 (Minggu); Angka bulan adalah 1 sampai 12. | 
 | calendar.prcal(year,w=2,l=1,c=6)	 | Seperti kalender cetak.calendar (tahun, w, l, c). | 
 | calendar.prmonth(year,month,w=2,l=1)	 | Seperti kalender cetak. Bulan (tahun, bulan, w, l). | 
 | calendar.setfirstweekday(weekday) | 	Mengatur hari pertama setiap minggu sampai hari kerja kode hari kerja. Kode hari kerja adalah 0 (Senin) sampai 6 (Minggu). | 
 | calendar.timegm(tupletime) | 	Kebalikan dari time.gmtime: menerima waktu instan dalam bentuk tupel waktu dan mengembalikan detik yang sama seperti jumlah floating-point dalam hitungan detik sejak zaman. | 
 | calendar.weekday(year,month,day)	 | Mengembalikan kode hari kerja untuk tanggal yang ditentukan. Kode hari kerja adalah 0 (Senin) sampai 6 (Minggu); Bulan adalah 1 (Januari) sampai 12 (Desember). | 
 
 # Fungsi
 Fungsi adalah blok kode terorganisir dan dapat digunakan kembali yang digunakan untuk melakukan sebuah tindakan/action. Fungsi memberikan modularitas yang lebih baik untuk aplikasi Anda dan tingkat penggunaan kode yang tinggi.

### Mendefinisikan Fungsi Python

Anda dapat menentukan fungsi untuk menyediakan fungsionalitas yang dibutuhkan. Berikut adalah aturan sederhana untuk mendefinisikan fungsi dengan Python.

- Fungsi blok dimulai dengan def kata kunci diikuti oleh nama fungsi dan tanda kurung (()).
- Setiap parameter masukan atau argumen harus ditempatkan di dalam tanda kurung ini. Anda juga dapat menentukan parameter di dalam tanda kurung ini.
- Pernyataan pertama dari sebuah fungsi dapat berupa pernyataan opsional - string dokumentasi fungsi atau docstring.
- Blok kode dalam setiap fungsi dimulai dengan titik dua (:) dan indentasi.
- Pernyataan kembali [ekspresi] keluar dari sebuah fungsi, secara opsional menyampaikan kembali ekspresi ke pemanggil. Pernyataan pengembalian tanpa argumen sama dengan return None.

Contoh fungsi
```

def printme( str ):
   "This prints a passed string into this function"
   print (str)
   return

```
 
Disini kita akan belajar semua fungsi dasar I/O yang tersedia pada Python 3. Jika Anda ingin mempelajari lebih detail, lihat dokumentasi standar Python.

### Print

Cara termudah untuk menghasilkan output adalah dengan menggunakan pernyataan cetak di mana Anda bisa melewati nol atau lebih banyak ekspresi yang dipisahkan dengan koma. Fungsi ini mengubah ekspresi yang Anda berikan ke string dan menulis hasilnya ke output standar sebagai berikut :
```

print ("Python adalah bahasa pemrograman yang hebat")

```
### Membaca Input Keyboard

Python 2 memiliki dua fungsi built-in untuk membaca data dari input standar, yang secara default berasal dari keyboard. Fungsi ini adalah input() dan raw_input()

Dengan Python 3, fungsi raw_input() tidak digunakan lagi. Selain itu, input() berfungsi membaca data dari keyboard sebagai string, terlepas dari apakah itu tertutup dengan tanda kutip ('' atau '") atau tidak.

### Fungsi Input Python

Fungsi input([prompt]) setara dengan raw_input, kecuali mengasumsikan bahwa input adalah ekspresi Python yang valid dan mengembalikan hasil yang dievaluasi ke Anda.
```


>>> x = input("something:")
something:10

>>> x
'10'

>>> x = input("something:")
something:'10' #entered data treated as string with or without ''

>>> x
"'10'"

```
# Modul
Modul memungkinkan Anda mengatur kode Python secara logis. Mengelompokkan kode terkait ke dalam modul membuat kode lebih mudah dipahami dan digunakan. Modul adalah objek Python dengan atribut yang diberi nama yang bisa Anda bind dan dijadikan referensi.

Secara sederhana modul adalah file yang terdiri dari kode Python. Modul dapat mendefinisikan fungsi, kelas dan variabel. Modul juga bisa menyertakan kode yang bisa dijalankan "runable".

Berikut adalah contoh modul sederhana pada Python :

```

def print_func( par ):
   print "Halo : ", par
   return

```
### Import Statement

Anda dapat menggunakan file sumber Python apapun sebagai modul dengan mengeksekusi pernyataan impor di file sumber Python lainnya. Impornya memiliki sintaks berikut.

Ketika interpreter menemukan sebuah pernyataan import, ia mengimpor modul jika modul tersebut ada di jalur pencarian. Jalur pencarian adalah daftar direktori yang ditafsirkan juru bahasa sebelum mengimpor modul. Misalnya, untuk mengimpor modul hello.py, Anda perlu meletakkan perintah berikut di bagian atas script.
```

## Import module support
import support

## Anda bisa memanggil fungsi defined sebagai berikut
support.print_func("Andy")

```

# I/O
Disini kita akan belajar semua fungsi dasar I/O yang tersedia pada Python 3. Jika Anda ingin mempelajari lebih detail, lihat dokumentasi standar Python.

### Print

Cara termudah untuk menghasilkan output adalah dengan menggunakan pernyataan cetak di mana Anda bisa melewati nol atau lebih banyak ekspresi yang dipisahkan dengan koma. Fungsi ini mengubah ekspresi yang Anda berikan ke string dan menulis hasilnya ke output standar sebagai berikut :
```

print ("Python adalah bahasa pemrograman yang hebat")

```
### Membaca Input Keyboard

Python 2 memiliki dua fungsi built-in untuk membaca data dari input standar, yang secara default berasal dari keyboard. Fungsi ini adalah input() dan raw_input()

Dengan Python 3, fungsi raw_input() tidak digunakan lagi. Selain itu, input() berfungsi membaca data dari keyboard sebagai string, terlepas dari apakah itu tertutup dengan tanda kutip ('' atau '") atau tidak.

### Fungsi Input Python

Fungsi input([prompt]) setara dengan raw_input, kecuali mengasumsikan bahwa input adalah ekspresi Python yang valid dan mengembalikan hasil yang dievaluasi ke Anda.

```

>>> x = input("something:")
something:10

>>> x
'10'

>>> x = input("something:")
something:'10' #entered data treated as string with or without ''

>>> x
"'10'"



```
# Exception Python
Python menyediakan dua fitur yang sangat penting untuk menangani kesalahan tak terduga dalam program Python Anda dan menambahkan kemampuan debugging di dalamnya.

- Exception Handling
- Assertions
Exception adalah sebuah peristiwa, yang terjadi selama pelaksanaan program yang mengganggu aliran normal instruksi program. Secara umum, ketika skrip Python menemukan situasi yang tidak dapat diatasi, hal itu menimbulkan pengecualian. Exception adalah objek Python yang mewakili kesalahan.

Ketika skrip Python menimbulkan Exception, ia harus menangani Exception begitu saja sehingga berhenti dan berhenti.

### Standard Exceptions

| Nama	| Penjelasan	| 
| --- | --- |
| Exception		| Kelas dasar untuk semua pengecualian / exception	| 
| StopIteration		| Dibesarkan ketika metode (iterator) berikutnya dari iterator tidak mengarah ke objek apa pun.	| 
| SystemExit	| 	Dibesarkan oleh fungsi sys.exit ().	| 
| StandardError		| Kelas dasar untuk semua pengecualian built-in kecuali StopIteration dan SystemExit.	| 
| ArithmeticError	| 	Kelas dasar untuk semua kesalahan yang terjadi untuk perhitungan numerik.	| 
| OverflowError		| Dibesarkan saat perhitungan melebihi batas maksimum untuk tipe numerik.	| 
| FloatingPointError	| 	Dibesarkan saat perhitungan floating point gagal.	| 
| ZeroDivisonError	| 	Dibesarkan saat pembagian atau modulo nol dilakukan untuk semua tipe numerik.	| 
| AssertionError	| 	Dibesarkan jika terjadi kegagalan pernyataan Assert.	| 
| AttributeError	| 	Dibesarkan jika terjadi kegagalan referensi atribut atau penugasan.	| 
| EOFError		| Dibesarkan bila tidak ada input dari fungsi raw_input () atau input () dan akhir file tercapai.	| 
| ImportError		| Dibesarkan saat sebuah pernyataan impor gagal.	| 
| KeyboardInterrupt	| 	Dibesarkan saat pengguna menyela eksekusi program, biasanya dengan menekan Ctrl + c.	| 
| LookupError	| 	Kelas dasar untuk semua kesalahan pencarian.	| 
| IndexError	| 	Dibesarkan saat sebuah indeks tidak ditemukan secara berurutan.	| 
| KeyError		| Dibesarkan saat kunci yang ditentukan tidak ditemukan dalam kamus.	| 
| NameError		| Dibesarkan saat pengenal tidak ditemukan di namespace lokal atau global.	| 
| UnboundLocalError	| 	Dibesarkan saat mencoba mengakses variabel lokal dalam suatu fungsi atau metode namun tidak ada nilai yang ditugaskan padanya.	| 
| EnvironmentError	| 	Kelas dasar untuk semua pengecualian yang terjadi di luar lingkungan Python.	| 
| IOError	| 	Dibesarkan saat operasi input / output gagal, seperti pernyataan cetak atau fungsi open () saat mencoba membuka file yang tidak ada.	| 
| OSError	| 	Dibangkitkan untuk kesalahan terkait sistem operasi.	| 
| SyntaxError	| 	Dibesarkan saat ada kesalahan dengan sintaks Python.	| 
| IndentationError	| 	Dibesarkan saat indentasi tidak ditentukan dengan benar.	| 
| SystemError	| 	Dibesarkan saat penafsir menemukan masalah internal, namun bila kesalahan ini ditemui juru bahasa Python tidak keluar.	| 
| SystemExit	| 	Dibesarkan saat juru bahasa Python berhenti dengan menggunakan fungsi sys.exit (). Jika tidak ditangani dalam kode, menyebabkan penafsir untuk keluar.	| 
| TypeError		| Dibesarkan saat operasi atau fungsi dicoba yang tidak valid untuk tipe data yang ditentukan.	| 
| ValueError	| 	Dibesarkan ketika fungsi bawaan untuk tipe data memiliki jenis argumen yang valid, namun argumen tersebut memiliki nilai yang tidak valid yang ditentukan.	| 
| RuntimeError	| 	Dibesarkan saat kesalahan yang dihasilkan tidak termasuk dalam kategori apa pun.	| 
| NotImplementedError		| Dibesarkan ketika metode abstrak yang perlu diimplementasikan di kelas warisan sebenarnya tidak dilaksanakan.	| 

Python telah menjadi bahasa berorientasi objek sejak bahasa Python sendiri dibuat. Untuk membuat dan menggunakan kelas dan objek pada Python benar-benar mudah. Pada tutorial ini Anda akan dibantu untuk menjadi ahli dalam penggunaan pemrograman berorientasi objek Python.

Jika Anda tidak memiliki pengalaman sebelumnya dengan pemrograman berorientasi objek (OOP), Anda mempelajarinya terlebih dahulu agar Anda dapat memahami konsep dasarnya.

Jika memang sudah mengerti konsep dasar OOP berikut ini adalah pengenalan dari Object-Oriented Programming (OOP) untuk membantu Anda.

### Istilah Dalam OOP

| Istilah | Penjelasan |
| --- | --- |
| Class	 | Prototipe yang ditentukan pengguna untuk objek yang mendefinisikan seperangkat atribut yang menjadi ciri objek kelas apa pun. Atribut adalah data anggota (variabel kelas dan variabel contoh) dan metode, diakses melalui notasi titik. | 
| Class variable | 	Sebuah variabel yang dibagi oleh semua contoh kelas. Variabel kelas didefinisikan dalam kelas tapi di luar metode kelas manapun. Variabel kelas tidak digunakan sesering variabel contoh. | 
| Data member | 	Variabel kelas atau variabel contoh yang menyimpan data yang terkait dengan kelas dan objeknya. | 
| Function overloading | 	Penugasan lebih dari satu perilaku ke fungsi tertentu. Operasi yang dilakukan bervariasi menurut jenis objek atau argumen yang terlibat. | 
| Instance variable	 | Variabel yang didefinisikan di dalam sebuah metode dan hanya dimiliki oleh instance kelas saat ini. | 
| Inheritance	 | Pengalihan karakteristik kelas ke kelas lain yang berasal darinya. | 
| Instance	 | Objek individu dari kelas tertentu. Obyek obj yang termasuk dalam Lingkaran kelas, misalnya, adalah turunan dari Lingkaran kelas. | 
| Instantiation	 | Penciptaan sebuah instance dari sebuah kelas. | 
| Method | 	Jenis fungsi khusus yang didefinisikan dalam definisi kelas. | 
| Object | 	Contoh unik dari struktur data yang didefinisikan oleh kelasnya. Objek terdiri dari kedua anggota data (variabel kelas dan variabel contoh) dan metode. | 
| Operator overloading | 	Penugasan lebih dari satu fungsi ke operator tertentu. | 


# Membuat Class Python

Statement class digunakan untuk membuat definisi kelas baru. Nama kelas segera mengikuti kelas kata kunci diikuti oleh titik dua sebagai berikut.

`class ClassName:` `'Optional class documentation string'` `class_suite`

Dibawah ini adalah contoh cara membuat class dan penggunaanya :
```

class Employee:
   'Common base class for all employees'
   empCount = 0

   def __init__(self, name, salary):
      self.name = name
      self.salary = salary
      Employee.empCount += 1
   
   def displayCount(self):
     print "Total Employee %d" % Employee.empCount

   def displayEmployee(self):
      print "Name : ", self.name,  ", Salary: ", self.salary

```
### Membuat Instance Objects

To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts Untuk membuat instances kelas, Anda memanggil class menggunakan nama class dan meneruskan argumen apa pun yang metode __init__ terima.

```

This would create first object of Employee class
emp1 = Employee("Zara", 2000)
This would create second object of Employee class
emp2 = Employee("Manni", 5000)

```
### Mengakses Atribut

Anda mengakses atribut objek menggunakan dot operator dengan objek. Variabel kelas akan diakses dengan menggunakan nama kelas sebagai berikut :
```

emp1.displayEmployee()
emp2.displayEmployee()
print ("Total Employee %d" % Employee.empCount)

```
Contoh lengkapnya, silahkan lihat kode dibawah ini.
```

class Employee:
   'Common base class for all employees'
   empCount = 0

   def __init__(self, name, salary):
      self.name = name
      self.salary = salary
      Employee.empCount += 1
   
   def displayCount(self):
     print ("Total Employee %d" % Employee.empCount)

   def displayEmployee(self):
      print ("Name : ", self.name,  ", Salary: ", self.salary)


#This would create first object of Employee class"
emp1 = Employee("Zara", 2000)
#This would create second object of Employee class"
emp2 = Employee("Manni", 5000)
emp1.displayEmployee()
emp2.displayEmployee()
print ("Total Employee %d" % Employee.empCount)

```
# Akses Database
Standar Interface Python untuk database adalah Python DB-API. Kebanyakan Interface database Python mematuhi standar ini.

Anda bisa memilih database yang tepat untuk aplikasi Anda. API Database Python mendukung berbagai macam server database seperti.
- GadFly
- mSQL
- MySQL
- PostgreSQL
- Microsoft SQL Server 2000
- Informix
- Interbase
- Oracle
- Sybase
- SQLite

Berikut adalah link untuk mempelajari lebih lengkap daftar antarmuka/interface database Python - Antarmuka dan API Database Python. Anda harus mendownload modul DB API terpisah untuk setiap database yang perlu Anda akses. Sebagai contoh, jika Anda perlu mengakses database Oracle dan juga database MySQL, Anda harus mendownload kedua modul database Oracle dan MySQL.

API DB menyediakan standar minimal untuk bekerja dengan database menggunakan struktur dan sintaks Python sedapat mungkin. API ini meliputi:

- Mengimpor modul API.
- Mendapatkan koneksi dengan database.
- Menerbitkan pernyataan SQL dan prosedur tersimpan.
- Menutup koneksi

Python memiliki dukungan built-in untuk SQLite. Pada bagian ini, kita akan mempelajari semua konsep menggunakan MySQL. Modul MySQLdb, antarmuka yang populer dengan MySQL tidak kompatibel dengan Python 3. Sebagai gantinya, kita akan menggunakan modul PyMySQL.

### Apa itu PyMySQL ?

PyMySQL adalah sebuah antarmuka untuk menghubungkan ke server database MySQL dari Python. Ini mengimplementasikan API Database Python v2.0 dan berisi perpustakaan klien MySQL murni-Python. Tujuan PyMySQL adalah penggantian drop-in untuk MySQLdb.

### Cara Instal PyMySQL

Sebelum melanjutka, pastikan Anda telah menginstal PyMySQL di komputer Anda. Cukup ketik berikut ini di skrip Python Anda dan jalankan.

`import PyMySQL`

Jika menghasilkan hasil berikut, berarti modul MySQLdb tidak terpasang:

`Traceback (most recent call last):`
    `File "test.py", line 3, in `
        `Import PyMySQL`
`ImportError: No module named PyMySQL`

Untuk menginstal modul PyMySQL silahkan gunakan command/perintah berikut di command prompt:

`pip install PyMySQL`

### Database Connection

Sebelum terhubung ke database MySQL, pastikan beberapa hal dibawah ini :

- Anda telah membuat database TESTDB.
- Anda telah membuat tabel EMPLOYEE di TESTDB.
- Tabel ini memiliki bidang FIRST_NAME, LAST_NAME, AGE, SEX, dan INCOME.
- User ID "testuser" dan password "test123" diatur untuk mengakses TESTDB.
- Python modul PyMySQL terinstal dengan benar pada mesin Anda.
- Anda telah melalui tutorial MySQL untuk memahami Dasar-Dasar MySQL

Berikut ini adalah contoh koneksi dengan database MySQL "TESTDB"


```

import PyMySQL

# Open database connection
db = PyMySQL.connect("localhost","testuser","test123","TESTDB" )

# prepare a cursor object using cursor() method
cursor = db.cursor()

# execute SQL query using execute() method.
cursor.execute("SELECT VERSION()")

# Fetch a single row using fetchone() method.
data = cursor.fetchone()

print ("Database version : %s " % data)

# disconnect from server
db.close()

```

### Membuat Tabel Database

```

import PyMySQL

# Open database connection
db = PyMySQL.connect("localhost","testuser","test123","TESTDB" )

# prepare a cursor object using cursor() method
cursor = db.cursor()

# Drop table if it already exist using execute() method.
cursor.execute("DROP TABLE IF EXISTS EMPLOYEE")

# Create table as per requirement
sql = """CREATE TABLE EMPLOYEE (
   FIRST_NAME  CHAR(20) NOT NULL,
   LAST_NAME  CHAR(20),
   AGE INT,  
   SEX CHAR(1),
   INCOME FLOAT )"""

cursor.execute(sql)

# disconnect from server
db.close()

```
### Operasi Insert

Contoh berikut, mengeksekusi pernyataan SQL INSERT untuk membuat catatan di tabel EMPLOYEE


```

import PyMySQL

# Open database connection
db = PyMySQL.connect("localhost","testuser","test123","TESTDB" )

# prepare a cursor object using cursor() method
cursor = db.cursor()

# Prepare SQL query to INSERT a record into the database.
sql = """INSERT INTO EMPLOYEE(FIRST_NAME,
   LAST_NAME, AGE, SEX, INCOME)
   VALUES ('Mac', 'Mohan', 20, 'M', 2000)"""
try:
   # Execute the SQL command
   cursor.execute(sql)
   # Commit your changes in the database
   db.commit()
except:
   # Rollback in case there is any error
   db.rollback()

# disconnect from server
db.close()

```
Contoh di atas bisa dituliskan sebagai berikut untuk membuat query SQL secara dinamis

```

import PyMySQL

# Open database connection
db = PyMySQL.connect("localhost","testuser","test123","TESTDB" )

# prepare a cursor object using cursor() method
cursor = db.cursor()

# Prepare SQL query to INSERT a record into the database.
sql = "INSERT INTO EMPLOYEE(FIRST_NAME, \
   LAST_NAME, AGE, SEX, INCOME) \
   VALUES ('%s', '%s', '%d', '%c', '%d' )" % \
   ('Mac', 'Mohan', 20, 'M', 2000)
try:
   # Execute the SQL command
   cursor.execute(sql)
   # Commit your changes in the database
   db.commit()
except:
   # Rollback in case there is any error
   db.rollback()

# disconnect from server
db.close()


``
### Read Operation

READ Operation pada database apapun berarti mengambil beberapa informasi berguna dari database.

Setelah koneksi database terbentuk, Anda siap untuk membuat query ke dalam database ini. Anda bisa menggunakan metode fetchone()
untuk mengambil satu record atau fetchall() metode untuk mengambil beberapa nilai dari tabel database.

Fetchone () - Ini mengambil baris berikut dari kumpulan hasil query. Set hasil adalah objek yang dikembalikan saat objek kursor digunakan untuk query tabel.

Fetchall () - Ini menjemput semua baris dalam kumpulan hasil. Jika beberapa baris telah diekstraksi dari himpunan hasil, maka akan diambil baris yang tersisa dari kumpulan hasil.

Rowcount - Ini adalah atribut read-only dan mengembalikan jumlah baris yang dipengaruhi oleh metode execute ().

Prosedur berikut menanyakan semua catatan dari tabel EMPLOYEE yang memiliki gaji lebih dari 1000

```

import PyMySQL

# Open database connection
db = PyMySQL.connect("localhost","testuser","test123","TESTDB" )

# prepare a cursor object using cursor() method
cursor = db.cursor()

# Prepare SQL query to INSERT a record into the database.
sql = "SELECT * FROM EMPLOYEE \
       WHERE INCOME > '%d'" % (1000)
try:
   # Execute the SQL command
   cursor.execute(sql)
   # Fetch all the rows in a list of lists.
   results = cursor.fetchall()
   for row in results:
      fname = row[0]
      lname = row[1]
      age = row[2]
      sex = row[3]
      income = row[4]
      # Now print fetched result
      print ("fname = %s,lname = %s,age = %d,sex = %s,income = %d" % \
             (fname, lname, age, sex, income ))
except:
   print ("Error: unable to fetch data")

# menutup koneksi ke server
db.close()

```
Setelah Anda eksekusi kode diatas, akan muncul hasil seperti dibawah ini :
`fname = Mac, lname = Mohan, age = 20, sex = M, income = 2000`

### Update Operation

Operasi UPDATE pada database apapun berarti mengupdate satu atau lebih catatan, yang sudah tersedia di database.
Prosedur berikut memperbarui semua catatan yang memiliki SEX sebagai 'M'. Di sini, kita meningkatkan UMUR semua laki-laki satu tahun.

```

import PyMySQL

## Open database connection
db = PyMySQL.connect("localhost","testuser","test123","TESTDB" )

## prepare a cursor object using cursor() method
cursor = db.cursor()

# Prepare SQL query to UPDATE required records
sql = "UPDATE EMPLOYEE SET AGE = AGE + 1
                          WHERE SEX = '%c'" % ('M')
try:
   # Execute the SQL command
   cursor.execute(sql)
   # Commit your changes in the database
   db.commit()
except:
   # Rollback in case there is any error
   db.rollback()

# disconnect from server
db.close()

```
### Delete Operation

Operasi DELETE diperlukan bila Anda ingin menghapus beberapa catatan dari database Anda. Berikut ini adalah prosedur untuk menghapus semua catatan dari EMPLOYEE dimana AGE lebih dari 20



```
```
import PyMySQL

## Open database connection
db = PyMySQL.connect("localhost","testuser","test123","TESTDB" )

## prepare a cursor object using cursor() method
cursor = db.cursor()

## Prepare SQL query to DELETE required records
sql = "DELETE FROM EMPLOYEE WHERE AGE > '%d'" % (20)
try:
   ## Execute the SQL command
   cursor.execute(sql)
   ## Commit your changes in the database
   db.commit()
except:
   ## Rollback in case there is any error
   db.rollback()

## disconnect from server
db.close()

```
```

Selain itu masih ada beberapa operasi sebagai berikut :

- Commit Operation db.commit()
- Rollback Operation db.rollback()
- Disconnect Operation db.close()
```
Jika Anda menginginkan dokumentasi yang lebih lengkap dari bahasa pemrograman python, silahkan buka dokumentasi resmi dari Python - [Dokumentasi Lengkap Python](https://docs.python.org/3/)

# Networking python
Python menyediakan dua tingkat akses ke layanan jaringan. Pada tingkat rendah, Anda dapat mengakses dukungan soket dasar dalam sistem operasi yang mendasarinya, yang memungkinkan Anda untuk mengimplementasikan klien dan server untuk kedua protokol berorientasi koneksi dan tanpa sambungan.

Python juga memiliki pustaka yang menyediakan akses tingkat lebih tinggi ke protokol jaringan tingkat aplikasi tertentu, seperti FTP, HTTP, dan seterusnya.

Bab ini memberi Anda pemahaman tentang konsep paling terkenal dalam Networking - Socket Programming.

### Apa itu Socket?

Soket adalah titik akhir dari saluran komunikasi dua arah. Soket dapat berkomunikasi dalam suatu proses, antara proses pada mesin yang sama, atau antara proses di berbagai benua.

Soket dapat diimplementasikan melalui sejumlah jenis saluran yang berbeda: soket domain Unix, TCP, UDP, dan sebagainya. Pustaka socket menyediakan kelas khusus untuk menangani transportasi umum serta antarmuka umum untuk menangani sisanya.

### Modul Socket

Untuk membuat soket, Anda harus menggunakan fungsi socket.socket () yang tersedia dalam modul soket, yang memiliki sintaks umum

`s = socket.socket (socket_family, socket_type, protocol=0)`

### Server Socket Method

 | Method  | Penjelasan |
 | --- | --- |
 | s.bind() |   This method binds address (hostname, port number pair) to socket. | 
 | s.listen()  | This method sets up and start TCP listener. | 
 | s.accept()  | This passively accept TCP client connection, waiting until connection arrives (blocking). | 

### Client Socket Method

 | Method  | Penjelasan |
 | --- | --- |
 |s.connect() | This method actively initiates TCP server connection.|
 
## General Method Socket 

 | Method  | Penjelasan |
 | --- | --- |
| s.recv() |  This method receives TCP message | 
| s.send() |  This method transmits TCP message | 
| s.recvfrom()  | This method receives UDP message | 
| s.sendto()  | This method transmits UDP message | 
| s.close()  | This method closes socket | 
| socket.gethostname()  | Returns the hostname. | 
```

#!/usr/bin/python           # This is server.py file

import socket               # Import socket module

s = socket.socket()         # Create a socket object
host = socket.gethostname() # Get local machine name
port = 12345                # Reserve a port for your service.
s.bind((host, port))        # Bind to the port

s.listen(5)                 # Now wait for client connection.
while True:
   c, addr = s.accept()     # Establish connection with client.
   print 'Got connection from', addr
   c.send('Thank you for connecting')
   c.close()                # Close the connection

```
   
### Server Sederhana

Untuk menulis server Internet, kami menggunakan fungsi soket yang tersedia di modul soket untuk membuat objek soket. Objek soket kemudian digunakan untuk memanggil fungsi lain untuk menyiapkan server soket.

Sekarang sebut `bind(hostname,port)` berfungsi untuk menentukan port untuk layanan Anda pada host yang diberikan.

Selanjutnya, panggil metode penerimaan objek yang dikembalikan. Metode ini menunggu sampai klien terhubung ke port yang Anda tentukan, dan kemudian mengembalikan objek koneksi yang mewakili koneksi ke klien itu.

### Client Sederhana

Mari kita menulis program klien yang sangat sederhana yang membuka koneksi ke port yang diberikan 12345 dan host yang diberikan. Ini sangat sederhana untuk membuat klien soket menggunakan fungsi modul soket Python.

Socket.connect (hosname, port) membuka koneksi TCP ke hostname pada port. Setelah Anda memiliki soket terbuka, Anda dapat membaca darinya seperti objek IO apa pun. Setelah selesai, jangan lupa untuk menutupnya, karena Anda akan menutup file.

Kode berikut adalah klien yang sangat sederhana yang terhubung ke host dan port yang diberikan, membaca data yang tersedia dari soket, dan kemudian keluar
```

#!/usr/bin/python           # This is client.py file

import socket               # Import socket module

s = socket.socket()         # Create a socket object
host = socket.gethostname() # Get local machine name
port = 12345                # Reserve a port for your service.

s.connect((host, port))
print s.recv(1024)
s.close                     # Close the socket when done

```
Sekarang jalankan server.py ini di latar belakang dan kemudian jalankan di atas client.py untuk melihat hasilnya.

##### Jalankan server.
`python server.py &`

Setelah server berjalan lanjutkan

##### Jalankan client:
`python client.py`

Hasilnya akan seperti ini :
`Got connection from ('127.0.0.1', 48437)`
`Thank you for connecting`

### Modul Internet pada Python

Berikut tabel daftar beberapa modul penting dalam pemrograman Jaringan / Internet Python.

 | Protocol	 | Common function | 	Port No	 | Python module | 
 | --- | --- | --- | --- |
 | HTTP | 	Web pages | 	80 | 	httplib, urllib, xmlrpclib | 
 | NNTP	 | Usenet news	 | 119 | 	nntplib | 
 | FTP	 | Transfer file | 	20 | 	ftplib, urllib | 
 | SMTP	 | Mengirim email | 	25 | 	smtplib | 
 | POP3	 | Fetching email | 	110 | 	poplib | 
 | IMAP4 | 	Fetching email | 	143	 | imaplib | 
 | Telnet | 	Command lines | 	23 | 	telnetlib | 
 | Gopher | 	Document transfers | 	70	 | gopherlib, urllib | 

# Pengembangan Web
Pengembangan web adalah istilah umum untuk membuat konsep, membuat, menyebarkan, dan mengoperasikan aplikasi website dan antarmuka pemrograman aplikasi untuk Website.


### Penggunaan Python dalam Pengembangan Web

Python dapat digunakan untuk membangun aplikasi web sisi server. Sementara kerangka web tidak diperlukan untuk membangun aplikasi web, jarang sekali pengembang tidak akan menggunakan pustaka sumber terbuka yang ada untuk mempercepat kemajuan mereka dalam membuat aplikasi mereka berfungsi.

Python tidak digunakan di browser web. Bahasa yang dijalankan di browser seperti Chrome, Firefox, dan Internet Explorer adalah JavaScript. Proyek seperti pyjs dapat dikompilasi dari Python ke JavaScript. Namun, sebagian besar pengembang Python menulis aplikasi web mereka menggunakan kombinasi Python dan JavaScript. Python dieksekusi di sisi server sementara JavaScript diunduh ke klien dan dijalankan oleh browser web.

Untuk membuat website dengan menggunakan Python sebagai bahasa pemrogramanya, caranya sangat mudah. Tetapi perlu diingat bahwa sebelumnya Anda sudah harus menguasai HTML, CSS dan Javascript.

### Web Framework Python

Framework pengembangan web pada python yang paling populer dan mudah dipelajari ada Django dan Flask

#### Flask 

Flask adalah sebuah microframework web python yang mudah untuk dipelajari, mudah diinstal dan pengembangan yang sangat simpel.

Berikut adalah beberapa kelebihanya :

- mudah digunakan.
- dibangun di server pengembangan dan debugger
- dukungan pengujian unit terpadu
- Kirim permintaan yang tenang
- menggunakan tempering Jinja2
- dukungan untuk cookie aman (sesi sisi klien)
- 100% WSGI 1.0 compliant
- Berbasis Unicode
- didokumentasikan secara ekstensif

Instalasi Flask
`pip install Flask`

Hello World Web App dengan Flask
```

from flask import Flask
app = Flask(__name__)
 
@app.route("/")
def hello():
    return "Hello World!"
 
if __name__ == "__main__":
    app.run()

```
Jalankan server dengan perintah: 
`python hello.py`

Buka [http://localhost:5000/](http://localhost:5000/) dibrowser anda dan akan muncul `Hello World!`



#### Django
Django adalah kerangka kerja Python Web tingkat tinggi yang menangani banyak kerumitan pengembangan Web, sehingga Anda dapat fokus untuk menulis aplikasi tanpa perlu menemukan kembali roda.

Kelebihan Framework Django dibanding yang lain adalah pada segi skalabilitas. Framework ini cocok untuk pengembangan aplikasi besar.

Untuk menginstal Django jalankan perintah dibawah ini :
`pip install Django==1.7.1`

Setelah terinstal, buat direktori /django-hello/ untuk aplikasi Anda. Dalam direktori ini buat file hello.py dengan code dibawah ini:
```

#!/usr/bin/env python
import sys
from django.conf import settings 
from django.conf.urls import patterns
from django.http import HttpResponse
from django.core.management import execute_from_command_line
 
settings.configure(
    DEBUG=True,
    SECRET_KEY='asecretkey',
    ROOT_URLCONF=sys.modules[__name__],
)
 
def index(request):
    return HttpResponse('Hello, World')
 
urlpatterns = patterns('',
    (r'^hello/$', index),
)
 
if __name__ == "__main__":
    execute_from_command_line(sys.argv)

```
Jalankan server dengan perintah :
`python hello.py runserver`

Server HTTP Django akan mulai dan jika Anda membuka [http://127.0.0.1:8000/hello/](http://127.0.0.1:8000/hello/)

# Untuk lebih lengkapnya anda bisa cek di [python.org](python.org)
