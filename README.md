# peraktikum-8

Nama : Yudi Fermana 

NIM : 312210321

Kelas : TI.22.A3

Penjelasan Ke 1

![example](https://user-images.githubusercontent.com/115516653/208462171-a841e2f4-6ae5-483b-9912-15fdc2c61ef2.png)

Berikut adalah fungsi yang mengubah mengubah suhu suhu dari derajat Kelvin ke derajat Fahrenheit. Karena nol derajat Kelvin sedingin yang didapat. Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback...AssertionError artinya terjadi error pada pernyataan assert.

Penjelasan Ke 2

![example 2](https://user-images.githubusercontent.com/115516653/208462338-839eebf9-894b-4148-9863-9b5e78dc8167.png)

contoh ini membuka file, menulis konten di file, dan keluar tidak ada masalah, Ini menghasilkan hasil berikut

Written content in the file successfully

Dan kenapa hasilnya begitu? karena else akan dijalankan ketika try adalah True

Penjelasan Ke 3

![example 3](https://user-images.githubusercontent.com/115516653/208462505-fd9af341-f24b-4e8a-841c-d93b8d91e898.png)

Mengapa muncul error?

Error: can't find file or read data

r adalah read - Membuka file untuk membaca, error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan

Penjelasan Ke 4

![example 4](https://user-images.githubusercontent.com/115516653/208462721-98d9f86c-23c4-4217-a494-c7252f4c2096.png)

Menghasilkan output: Error: can't find file or read data

Ini bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan

Penjelasan Ke 5

![example 5](https://user-images.githubusercontent.com/115516653/208462914-4c25baca-3976-4561-bd35-83c71fe8107e.png)
![example5(2)](https://user-images.githubusercontent.com/115516653/208462954-ca86632f-46b9-415e-b7ed-5882cde87729.png)

ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument:agar tidak error. Jika dijalankan akan muncul error lagi

The argument does not contain numbers invalid literal for int() with base 10: xyz

kenapa? karena parameter def temp_convert harus mengandung angka

Penjelasan Ke 6

![example 6](https://user-images.githubusercontent.com/115516653/208463080-6362df40-f4e1-4e5d-b7e1-aed6d90a8e9d.png)

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise Invalid level!, level ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1
