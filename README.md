# Operator
Lab 1

Penggunaan end
Di dalam fungsi "print()" di dalam bahasa python terdapat parameter "end". Parameter "end" adalah parameter yang digunakan untuk memasukan string atau karakter apapun untuk mengakhiri sebuah statement. Secara default jika kita melakukan print dalam python, output akan dicetak dalam baris baru. Tapi jika kita memasukan fungsi "end" maka hasil output tidak akan langsung berada di garis baru. Contoh kode :

Terlihat dari output A, B dan C dicetak dalam baris yang sama, sedangkan output X, Y dan Z dicetak dengan baris baru. Jika kalian ingin membuat garis baru menggunakan fungsi end, kalian bisa memasukan "\n".
Contoh :

print('A', end="\n") 
Penggunaan Separator
Separator "sep" dalam python digunakan sebagai pembatas antara output yang dihasilkan.

Contoh Kode :

![lab 1](https://user-images.githubusercontent.com/56498195/68079013-87a43f00-fe14-11e9-9f46-ae015db79d90.PNG)

output:

![output lab 1](https://user-images.githubusercontent.com/56498195/68079024-d9e56000-fe14-11e9-81e6-103b8817e8b9.PNG)


Kita bisa mengisi sep='isi_disini' dengan string atau karakter apapun.

Penggunaan string format
String format digunakan ketika kita ingin mengatur dan memposiskan print output menjadi sedemikian rupa.
Contoh kode :

![lab 2](https://user-images.githubusercontent.com/56498195/68079043-30eb3500-fe15-11e9-95fa-7a46b1171af3.PNG)



Dalam contoh di atas terdapat { } yang berfungsi sebagai placeholder atau penempat arguments. Argument secara default urutannya adalah berurutan.

output:


![output lab 2](https://user-images.githubusercontent.com/56498195/68079061-917a7200-fe15-11e9-8d09-b927762b0b19.PNG)



Misalnya dalam contoh di atas, terdapat argument "0" dan "10 ** 0" didalam format(0, 10 ** 0), yang dipisah dengan tanda "," (koma), yang berarti "0" adalah argument pertama dan "10**0" adalah argument ke dua. Sedangkan angka 0 dan 1 di dalam placeholder, merupakan urutan yang kita masukan. Misalnya placeholder pada urutan pertama yaitu "{0:>3}" dan kita ingin mengganti menjadi "1" maka yang akan dicetak di placeholder pertama adalah output dari "10 ** 0". Contoh kode :


![lab 3](https://user-images.githubusercontent.com/56498195/68079080-05b51580-fe16-11e9-9d52-7682bf724b45.PNG)


output:


![output lab 3](https://user-images.githubusercontent.com/56498195/68079082-0e0d5080-fe16-11e9-97af-75d011a93382.PNG)

print('{1:>3} {0:>16}'.format(0, 10 ** 0))
contoh code:


![lab 4](https://user-images.githubusercontent.com/56498195/68079083-182f4f00-fe16-11e9-9e5d-b60710b55c89.PNG)



Output yang didapat :


![output lab 4](https://user-images.githubusercontent.com/56498195/68079089-1feef380-fe16-11e9-9e9b-49066be55303.PNG)



Lab2
Lab2 membahas tentang bagaimana memasukan input, menghitung dan mengubah tipe data serta membuat format print yang akan dicetak ke output.

Contoh kode :




