# Rijal Ramadan_uts_Teknik Kompilasi

1. Mengapa fungsi power() dipanggil di dalam term()?

Karena operator pangkat (^) memiliki prioritas lebih tinggi dibanding operator perkalian (*) dan pembagian (/). Oleh karena itu operasi pangkat harus diproses terlebih dahulu.

2. Apa yang terjadi jika variabel z tidak ada di symbol_table?

Compiler akan menghasilkan Semantic Error karena variabel belum didefinisikan.

Contoh:

Semantic Error: Undefined variable 'z'
3. Mengapa instruksi a ^ 2 muncul sebelum + pada TAC?

Karena operasi pangkat memiliki prioritas lebih tinggi sehingga harus dihitung terlebih dahulu sebelum operasi penjumlahan.