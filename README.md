# Applied-Machine-Learning

Pada repository Applied Machine Learning ini akan diberikan lima macam code untuk analisis dengan metode Market Basket Analysis (MBA), Collaborative Filtering (CF), Content Based (CB), Hybrid Approach, dan A/B Testing. Lebih detailnya berikut akan kami detailkan.

## Market Basket Analysis
Pada code ini akan dilakukan market basket analisis dengan metode apriori dari data transaksi pembelian 24 customer pada sebuah online shop.

Analisis ini ditujukan untuk melihat frekuensi penjualan masing-masing item pada online shop tersebut serta item mana saja yang sering dipilih secara bersamaan pada online shop tersebut. Sehingga dapat memberikan rekomendasi:
1. Susunan peletakan item barang pada website ataupun aplikasi online shop.
2. Rekomendasi item yang sering dibeli oleh customer.
3. Promo untuk item yang kurang diminati oleh customer.
4. Paket bundling untuk item yang kurang dimiinati dengan item yang sering diminati untuk meningkatkan penjualan.

Data yang digunakan terdiri atas lima features, yaitu waktu transaksi customer pada online shop, nama customer, item pertama yang dimasukkan ke dalam keranjang, item kedua yang dimasukkan ke dalam keranjang, dan item ketiga yang dimasukkan ke dalam keranjang.

## Collaborative Filtering
Pada code ini akan dilakukan colaborative filtering (user-based nearest neighbor) dari data pemberian rating oleh 24 customer pada 10 film yang ada pada dataset.

Analisis ini ditujukan untuk:
1. Menentukan rekomendasi film kepada customer tertentu terhadap film-film yang belum ditonton. Dalam hal ini ketika customer tidak memberikan rating pada film maka diasumsikan bahwa customer tersebut belum menonton film tersebut.
2. Mengetahui hubungan antar dua orang customer berdasarkan kemiripan rating yang diberikan kepada masing-masing film pada dataset.
3. Mengetahui hubungan antar dua orang customer berdasarkan kemiripan film-film yang sudah ditonton dan belum ditonton.

Dataset yang digunakan terdiri atas 11 features, yaitu nama customer dan rating yang diberikan kepada masing-masing film terpilih.

## Content Based
Jenis filter ini hanya menggunakan seorang customer saja dalam melakukan analisis. Analisis yang dilakukan adalah melihat customer behavior untuk memberikan rekomendasi film yang belum pernah ditonton oleh customer tersebut dan tentunya yang paling sesuai dengan seleranya. Dengan kata lain, algoritma ini akan memilih item dengan konten yang mirip untuk direkomendasikan kepada customer.

Dalam kasus ini akan digunakan dataset yang berisi 10 judul film dari indonesia dan hollywood yang dilengkapi oleh feature genre, rating, dan duration. Dengan data set tersebut akan dicari hubungan/kesamaan paling erat diantara 10 film yang ada. Sehingga ketika seseorang sudah menonton suatu film, dapat diberikan rekomendasi untuk menonton film lainnya yang memiliki kesamaan.

## Hybrid Approach


# A/B Testing
Pada code ini akan dilakukan A/B Testing dengan metode Z_test dari data 38 pengunjung suatu website dari 11 Oktober sampai dengan 16 November.

Analisis ini ditujukan untuk melihat bagaimana respon (perilaku) pengunjung website tampilan lama dibandingkan dengan website tampilan baru. Sehingga dapat memberikan rekomendasi:
1. Apakah akan lebih baik jika tampilan website diganti dengan yang baru
2. Apakah tidak perlu diganti secara keseluruhan, namun hanya pada elem-elemen tertentu saja.

Data yang digunakan terdiri atas 5 features, yaitu **Date**: waktu yang digunakan untuk akumulasi per baris data (hari), **Pageviews**: Banyaknya pengunjung yang masuk ke dalam website, **Clicks**: Banyaknya pengunjung yang melakukan eksplorasi pada website tersebut, **Enrollments**: Pengunjung yang melakukan pendaftaran pada website tersebut, **Payments**: Banyaknya pengunjung yang berhasil melakukan transaksi pada website tersebut.
