DevTools
1.html mempunyai lang=id
2.title tampil pada tab browser
3.h1, h2, h3 berurutan logis
5.header, nav, main, aside, footer ditemukan
6.tautan menuju id yang tersedia berhasil

Validasi
1.saat validasi ada program yang salah yaitu line 13 
2.setelah diperbaiki validasi tidak lagi menampilkan error

Hasil Eksperimen
1.Gejala : tidak menampilkan article di DOM
    bukti : dihalaman masih masih ada article, tetapi di dom tidak
    penyebab : tag article dihapus
    perbaikan : kembalikan tag penutup article
    BERHASIL
2.Gejala : tautan tidak bergerak
    bukti : URL memuat kegiatan
    penyebab : id berbeda
    perbaikan : Samakan href dan id
    BERHASIL
3.Gejala : tidak ada
    bukti : masih menampilkan lokakarya
    penyebab : -
    perbaikan : ubah kembali h4 menjadi h3
    BERHASIL
4.gejala : struktur folder di dom menjadi acak
    bukti : validasi menunjukkan error
    penyebab : main seharusnya tidak berada di header
    perbaikan : mengembalikan letak main
    BERHASIL