Fungsi utama program ini adalah untuk mengidentifikasi apakah sebuah bilangan bulat yang dimasukkan oleh pengguna termasuk dalam kategori bilangan ganjil atau bilangan genap.
Cara kerja program ini sangat bergantung pada satu operasi matematika, yaitu Modulo.

Minta Input: Program meminta pengguna memasukkan satu bilangan bulat (menggunakan Scanner).
Hitung Sisa Bagi: Program mengambil bilangan tersebut dan menghitung sisa hasil baginya jika dibagi 2. Operasi ini menggunakan operator % (modulo).
Contoh: 10 % 2 hasilnya 0 (karena 10 habis dibagi 2)
Contoh: 7 % 2 hasilnya 1 (karena 7 dibagi 2 adalah 3, sisa 1)
Ambil Keputusan: Program menggunakan if-else untuk memeriksa hasil sisa bagi tersebut.
Jika sisa == 0: Bilangan itu genap.
Jika sisa != 0 (atau sisa == 1): Bilangan itu ganjil.
