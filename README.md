# Rijal Ramadan_uts_Teknik Kompilasi

Mini Compiler Python
Nama
Rijal Ramadan 

Deskripsi
Project Mini Compiler sederhana menggunakan Python.

Fitur
Lexical Analysis
Parser
AST
Semantic Checking
Three Address Code
Operator Pangkat (^)
Cara Menjalankan
python UTS_TEKNIIK-KOMPILASI.py

Contoh Output
t1 = a ^ 2 t2 = b * c t3 = t1 + t2

1. Mengapa fungsi power() dipanggil di dalam term()?

Karena operator pangkat (^) memiliki prioritas lebih tinggi dibanding operator perkalian (*) dan pembagian (/). Oleh karena itu operasi pangkat harus diproses terlebih dahulu.

2. Apa yang terjadi jika variabel z tidak ada di symbol_table?

Compiler akan menghasilkan Semantic Error karena variabel belum didefinisikan.

Contoh:

Semantic Error: Undefined variable 'z'
3. Mengapa instruksi a ^ 2 muncul sebelum + pada TAC?

Karena operasi pangkat memiliki prioritas lebih tinggi sehingga harus dihitung terlebih dahulu sebelum operasi penjumlahan.