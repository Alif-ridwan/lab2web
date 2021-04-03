# lab2web
Nama		: M. Alif Ridwan Hanafi

NIM		: 311910801

Kelas		: Ti.19.B1

TUGAS 2 CSS DASAR

Laporan Praktikum
1. Buatlah repository baru dengan nama Lab2Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus.

Screen Shoot beserta Penjelasan  :
-	Untuk yang pertama ini adalah untuk membuat dokumen HTMLnya, Beserta tampilan pada browsernya.
![image](https://user-images.githubusercontent.com/81422149/113474278-47c60900-9499-11eb-8334-914bd3a9fe17.png)
![image](https://user-images.githubusercontent.com/81422149/113474293-5ca29c80-9499-11eb-865e-1649eeeb5776.png)
-	Kemudian deklarasi ini adalah deklarasi css internal pada bagian head dokumen.
![image](https://user-images.githubusercontent.com/81422149/113474296-67f5c800-9499-11eb-9219-7ccdedec0ed6.png)
![image](https://user-images.githubusercontent.com/81422149/113474297-6b894f00-9499-11eb-8bc3-a29b4e252093.png)
-	Kemudian deklarasi ini deklarasi inline untuk merubah warna teks pada dokumen.
![image](https://user-images.githubusercontent.com/81422149/113474301-75ab4d80-9499-11eb-9d48-774789c0258b.png)
![image](https://user-images.githubusercontent.com/81422149/113474306-7a700180-9499-11eb-8f72-033f75563537.png)
-	Kemudian menggunakan tag link untuk merujuk ke file css khusus. 
![image](https://user-images.githubusercontent.com/81422149/113474314-82c83c80-9499-11eb-992d-f17c6cc9075c.png)
![image](https://user-images.githubusercontent.com/81422149/113474315-85c32d00-9499-11eb-98a0-6e1579181e33.png)
![image](https://user-images.githubusercontent.com/81422149/113474317-88be1d80-9499-11eb-8bf4-07a154afdd64.png)
-	Kemudian menambahkan css selector yang menggunakan ID dan class selector untuk memberikan style yang berbeda pada HTML.

![image](https://user-images.githubusercontent.com/81422149/113474328-94114900-9499-11eb-9a93-742de9096cdb.png)
![image](https://user-images.githubusercontent.com/81422149/113474329-9673a300-9499-11eb-84ea-ed489b859a99.png)

Pertanyaan dan Tugas :
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( p id="paragraf-1" class="text-paragraf" )

Jawaban :
1. 
Pertanyaan dan Tugas :
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( p id="paragraf-1" class="text-paragraf" )

Jawaban :

1. 
![image](https://user-images.githubusercontent.com/81422149/113474382-e94d5a80-9499-11eb-9722-75b5119c7622.png)
![image](https://user-images.githubusercontent.com/81422149/113474389-ed797800-9499-11eb-80d7-4be9b9e24ffa.png)
![image](https://user-images.githubusercontent.com/81422149/113474392-f10cff00-9499-11eb-8378-b236c417b14e.png)
![image](https://user-images.githubusercontent.com/81422149/113474395-f5391c80-9499-11eb-91be-e06ca1817013.png)
![image](https://user-images.githubusercontent.com/81422149/113474397-f8340d00-9499-11eb-893c-01f46a4683e8.png)

2. - perbedaan dari H1 adalah penggunaan langsung pada css tanpa tanda(#) dan titik(.) karena h1 tersebut tidak memiliki id ataupun class
    - sedangkan H1 intro memiliki id maka penggunaan pada css dengan pagar (#) , dan di dalam file index.html dalam pemanggilan nya menggunakan id=" ".

3. - CSS Internal : adalah kode CSS yang ditulis di dalam tag <style> dan kode HTML dituliskan di bagian atas (header) file index.html, dan perubahan Internal CSS hanya berlaku pada satu halaman saja.
Contoh :

![image](https://user-images.githubusercontent.com/81422149/113474454-3f220280-949a-11eb-8123-e8b2b9e19447.png)

- CSS Eksternal : adalah kode CSS yg ditulis terpisah dengan kode html, CSS ditulis pada sebuah file khusus yg berektensi .css. diletakan pada bagian dan di panggil dengan tag .
Contoh :

![image](https://user-images.githubusercontent.com/81422149/113474472-5103a580-949a-11eb-85a9-38c1d48dc888.png)

- Inline CSS : adalah kode CSS yang ditulis langsung pada atribut elemen HTML. Setiap elemen HTML memiliki atribut style, di situ lah inline CSS ditulis.
Contoh :

![image](https://user-images.githubusercontent.com/81422149/113474475-595be080-949a-11eb-96dc-07841745f396.png)

kesimpulannya adalah jadi dari deklarasi dia atas tersebut jika di gabung ditampilkan pada browser akan normal asalkan penggunaanya secara benar dan tidak ada yg error pada saat coding, dan 1 hal di dalam 3 metode css di atas ada perbedaannya dan tergantung developer 1 elemen hanya bisa 1 selector pemanggilan dalam CSS, kecuali elemen tersebut menggunakan ID atau CLASS agar bisa penggunaan deklarasi secara ulang.
4. contoh ketika elemen terdapat ID dan Class dan masing-masing selector terdapat deklarasi :

![image](https://user-images.githubusercontent.com/81422149/113474487-68429300-949a-11eb-93f2-264923084445.png)

maka hasilnya pada browser :

![image](https://user-images.githubusercontent.com/81422149/113474493-77c1dc00-949a-11eb-9d20-fdb47b670b4c.png)

penjelasaanya adalah ketika di klik button(informasi selengkapnya) maka akan muncul halaman yg sama kecuali alamat pada href diganti ke alamat lain.

![image](https://user-images.githubusercontent.com/81422149/113474500-814b4400-949a-11eb-9b15-2850000922d1.png)
