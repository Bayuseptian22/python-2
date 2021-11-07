# python-2 
A. String

di tutor kali ini kita akan belajar string, string adalah sebuah karakter atau bisa di sebut dengan susunan dari karakter-karakter
![image](https://user-images.githubusercontent.com/93038034/140648101-27b34692-17ed-4e67-a7cd-fc73d7b2da22.png)
-pada gambar di atas untuk mendefiniskan string ada dua cara bisa dengan tanda petik dua(") juga bisa dengan cara petik satu (') fungsi nya hampir gak ada bedanya sama sekali
-nah bagaimana jika kita ingin menampilkan nama depan saya saja
-kita cukup gunakan kurung siku [], lalu kita hitung huruf nya atau karakter nya di sini jika kita menghitung dari depan kita mulai dengan Nol(0) karena karakter nama depan saya adalah 5 jadi kita masukkan 5 maka dia akan mencetak Azlam saja seperti pada gambar di bawah ini
![image](https://user-images.githubusercontent.com/93038034/140648224-ef53b9a6-d949-44e4-a005-a18364395854.png)
-bagaimana jika saya hanya ingin mencetak nama belakang saya? bisa cukup kita mulai dari angka 6 karena nama belakang saya di mulai dari karakter 6 sampai dengan 14 maka dia akan mencetak nama belakang saya saja yaitu wahyudin seperti pada gambar di bawah ini
![image](https://user-images.githubusercontent.com/93038034/140648262-15e49bc0-b47a-4daa-9260-70a5aee64949.png)
B.Formatted string

-formatted ini cukup rumit si lansung aja kita jelaskan gambar nya
![image](https://user-images.githubusercontent.com/93038034/140648452-afaaca1e-17ee-426f-b6aa-f8cd09dbcd8c.png)
-di situ saya menggunakan dua cara agar bagaimana bisa menampilakan formatted string
-dan di sana saya menambahkan first_nama dan last_nama.
-cukup kita jumlahkan menggunakan cara di atas maka dia akan mencetak nama anda
C. String Method

-di sini kita akan belajar fungsi string, di sini karena fungsi nya terlalu banyak maka saya hanya menjelaskan sedikit
-yang pertamaa di sini bagaimana cara kita mengetahui berapa jumlah karakter yang kita masukkan yaitu dengan cara membuat variabel panjang seperti pada contoh dibawah lalu sama dengan len(kursus) lalu kita print maka dia akan mencetak berapa jumlah karakter yang anda masukkan
![image](https://user-images.githubusercontent.com/93038034/140648546-26e292cf-8b44-45f8-a695-dd2aba2706b2.png)
bagaimana jika kita ingin membuat semua string tersebut menjadi huruf capital semua
nah kali ini kita menggunakan upper dan coba kita jalankan maka dia akan menghasilakan semua huruf karakternya menjadi huruf capital
![image](https://user-images.githubusercontent.com/93038034/140648649-ec8a7ca6-3c62-4dea-91c0-2197e2240f95.png)
-dan coba kita print kursus nya maka dia akan menghasilkan karakter yang asli dan karakter yang sudah diubah menjadi huruf capital semua
![image](https://user-images.githubusercontent.com/93038034/140648714-3affd2d3-4a49-4104-92e2-fdb4eb2f43e0.png)
trus bagaimana cara kita untuk membuat semua huruf tersebut menjadi huruf kecil
cukup mudah kita cuman mengganti upper menjadi lower maka hasilnya akan keluar mencetak huruf kecil seperti pada terminal saya
![image](https://user-images.githubusercontent.com/93038034/140648763-9044b2b9-9234-4a8c-81e9-53a675d09b72.png)
D. Matematika

kali ini kita akan belajar tutorial variabel matematika
di sini variabel x saya taro nilai 6 dan variabel y saya taro 8 dan dia akan mencetak hasil 14 dari penjumlahan.mudah bukan
![image](https://user-images.githubusercontent.com/93038034/140648798-baa24d32-0ba3-4b33-8e75-55f772a8fa5f.png)
kemudian bagaimana untuk perkalian, gampang sekali kita tinggal mengubah penjumlahan di dalam kurung ke perkalian
![image](https://user-images.githubusercontent.com/93038034/140648840-4c4d2c14-8fae-4970-99fe-080ca879c150.png)
nah jika kita menggunakan pembagian dia akan menghasilakan bilangan pecahan.
![image](https://user-images.githubusercontent.com/93038034/140648876-9c155edf-9f4b-4c38-a4d9-9534232101c6.png)
bagaimana kita bisa mengubah bilangan pecahan tersebut menjadi bilangan bulat yaitu dengan menambahkan pembagian nya sampai 2 kali ssperti pada contoh dibawah maka dia akan mencetak bilanagan bulat
![image](https://user-images.githubusercontent.com/93038034/140648913-d05d2171-4293-4152-9993-822ed140c1a0.png)
E. Operator Presedence

nah pada operasi presedence ini adalah operasi manakah yang akan di hitung duluan
seperti pada gambar jika anda menghitung penjumlahan terlebuh dahulu anda salah, karena yang doi dahulukan adalah perkalian
![image](https://user-images.githubusercontent.com/93038034/140648955-17cf6702-4fd7-4179-9c8d-3687ef8b36e4.png)
karena dalam sistem matematika yang di dahulukan adalah

a.tanda kurung

b.perpangkatan

c.perkalian dan penjumlahan

d.penjumlahan danpengurangan

bagaimana agar penjumlahan bisa di hitung terlebih dahulu, seperti yang sudah saya jelaskan tanda kurung lebih di dahulukan maka penjumlahan akan di hitung terlebih dahulu seperti pada gambar dibawah

![image](https://user-images.githubusercontent.com/93038034/140649005-47692612-48f2-4a19-999c-45b6f5289366.png)
F. Math Modula

di sini saya punya nomor = bilangan pecahan, di sini bagaimana cara kita mengubah bilangan pecahan ke bilangan bulat
yaitu dengan menggunakan round(nomor) seperti pada gambar
![image](https://user-images.githubusercontent.com/93038034/140649057-6e6262bd-024d-4308-9cfb-3718decf6be5.png)
jika bilangan pecahan pecahan di bawah 5 dia akan mencetak 4 jika dia di atas 5 dia akan mencetak 5
bagaimana cara kita memaksa untuk mencetak nya yaitu dengan ceil
![image](https://user-images.githubusercontent.com/93038034/140649112-77d5a799-6d83-4664-bcf6-23416c5fd4a6.png)
kemudian kita masukkan import math lalu masukkan ceil maka dia akan menghasilkan bilangan bulat
![image](https://user-images.githubusercontent.com/93038034/140649159-c0c40841-a28b-499e-8b2a-708f177c5d29.png)
lalu bagaimana jika kita ingin memaksa bilangan pecahan yang di atas 5 menjadi bilangan bulat yang menghasilkan angka 4 yaitu dengan cara mengganti ceil tadi dengan floor yaitu kebalikan dari ceil, mudah bukan
![image](https://user-images.githubusercontent.com/93038034/140649183-d4e99253-9e17-439c-9fe4-5a1addb03b53.png)
