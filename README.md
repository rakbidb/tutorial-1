# eshop Adpro Tutorial
#### by Rakha Abid Bangsawan - 2206081585 - Adpro C
<hr>

# Jawaban Refleksi 1
<hr>

Setelah mengerjakan Exercise 1, saya menyadari bahwa ilmu dalam perkodingan saya masih sangat kurang untuk dapat bersaing nantinya di dunia kerja. Banyak sekali ilmu pengetahuan tentang prinsip meng-coding yang belum saya ketahui.

Clean Code Principles yang beberapa sudah saya terapkan dalam tutorial ini, yaitu:

* Meaningful Names, dalam tutorial ini saya sudah menerapkan penamaan variabel agar sesuai dengan fungsi aslinya sehingga tidak perlu menambahkan komen untuk menjelaskannya.
* Function, dalam tutorial ini saya juga menerapkan clean code dalam function yaitu agar panjangnya tidak melebihi layar dan memiliki nama yang sesuai dengan fungsi dari function tersebut.
* Comment, dalam tutorial ini saya sudah sebisa mungkin untuk menulis code yang jelas sehingga tidak memerlukan comment apapun.
* Object and Data Structures, dalam tutorial ini saya sudah menerapkan OOP dan membuat interface class sehingga dapat menerapkan implementasi dari fungsinya. Modifier yang digunakan juga pada umumnya adalah private agar program menggunakan getter dan setter.
* Error Handling, nah kekurangan saya ada di error handling ini, misalnya dalam mencari item dengan id, saya belum menghandle jika item yang dicari itu tidak ada dan malah me-return null.
* Lalu, untuk secure coding, belum saya terapkan karena di exercise belum ada tutorial untuk menambahkan, seperti autentikasi pengguna sehingga saya masih ragu dan belum memiliki ilmu terkait hal tersebut.

Setelah menulis refleksi pertama ini, saya menjadi kepikiran untuk memperbaiki kode saya agar semakin dekat dengan clean code. Pertama, saya ingin memperbaiki edit dan delete karena saya masih menggunakan method http GET dan POST untuk edit dan delete product. Kedua, mungkin saya akan menambahkan validasi input dalam membuat product.
<hr>

# Jawaban Refleksi 2
<hr>

1. Setelah menulis unit test pada tutorial ini, saya merasa banyak hal yang saya belum mengerti di dunia perkodingan. <b>Jumlah unit test yang seharusnya dibuat dalam satu class</b>, misalnya, menurut saya itu tergantung dengan seberapa kompleks kode yang kita buat sehingga kita dapat menerka berapa banyak test yang harus dibuat untuk meng-cover semua kode tersebut agar dijamin sudah benar. Menurut saya, <b>100% code coverage</b> itu belum menjamin bahwa kode tersebut terbebas dari bug atau error lainnya. Bisa jadi masih ada logical error dalam penulisan kode sehingga codenya masih bisa berjalan, tetapi menghasilkan output yang salah.<br><br>