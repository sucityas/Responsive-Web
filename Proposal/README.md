#My Own Money

## Permasalahan
-	Banyak mahasiswa yang tinggal di kost tidak tahu uang yang dikeluarkan untuk keperluan apa saja. Dan akan menimbulkan perilaku konsumtif

## Rancangan Solusi
-	Membuat website untuk menghitung keuangan harian
-	Ada kategori pengeluaran (makan, transport, jajan, listrik) dan pemasukan (part time, kerja, transfer)
-	uang masuk dan uang keluar dicatat sesuai dengan kategori
-	memberikan presentase pengeluaran dalam kurun waktu tertentu yang bisa disimpulkan apakah pada bulan ini termasuk hemat atau boros

## Use Case
-	user bisa menginput harta yang ada di dompet maupun e-wallet
-	user bisa mencatat pengeluaran maupun pemasukan apa saja pada hari itu
-	user bisa melihat jumlah pengeluaran dan penghasilan setiap hari
-	user bisa melihat apakah data pada web dan uang di dompet balance atau tidak
-	user bisa melihat uang yang dikeluarkan paling banyak pada kategori apa

## struktur data

User
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|nama|string|Suci|
|umur|integer|20|
|pekerjaan|varchar|mahasiswa|


Admin
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|nama|string|suci|
|Password|varchar|001rt6|

Penghasilan
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|waktu|date|08-08-2022|
|Nominal|integer|1000|
|Keterangan|varchar|kerja|

Pengeluaran
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|waktu|date|08-08-2022|
|Nominal|integer|1000|
|Keterangan|varchar|makanan|

## UX WAREFRAME

![Desktop - 1](https://user-images.githubusercontent.com/82722477/189568794-0a35bb88-d248-41a5-b3fb-a207beced63c.png)

![Desktop - 2](https://user-images.githubusercontent.com/82722477/189568825-e3bff4fc-dbc8-4a83-8af9-0f4443aa158d.png)

![Desktop - 3](https://user-images.githubusercontent.com/82722477/189568837-86ed9a33-72a6-46e0-8bd1-b40537861209.png)

![Desktop - 4](https://user-images.githubusercontent.com/82722477/189568948-45696783-1544-4fd3-98bd-ecac2043d7ce.png)
