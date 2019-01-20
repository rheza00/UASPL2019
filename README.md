# UASPL2019
Dikarenakan disini kami masih menggunakan database lokal yaitu Database dari MS OFFICE dengan menggunakan OLEDB, dan pada saat ingin dieksekusi di pc lain mengalami error, itu dikarenakan letak database yang lokal tadi. Jadi kita perlu mengganti lokasi link databasenya di setiap programnya, seperti berikut ::

carilah codingan seperti di bawah dengan mengkopynya lalu eksekusi pencarian

connection.ConnectionString = @"Provider = Microsoft.Jet.OLEDB.4.0; Data Source = C:\Users\Akiraa\Videos\Pemrograman Lanjutan1\Data Barang.mdb;

pada data source diatas perlu kita ganti dengan letak source databasenya, dan letak databasenya ada di dalam FOLDER Pemrograman Lanjutan1
