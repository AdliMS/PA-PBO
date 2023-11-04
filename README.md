# Top-up ML

### Muhammad Akmal Falah 2209116091
### Adli Imam Suryadin 2209116096

## Deskripsi Projek
Projek akhir ini adalah tentang penerapan sistem top up untuk game Mobile Legends menggunakan bahasa pemrograman Java dan database MySQL. Tujuan utama dari proyek ini adalah untuk memungkinkan pemain game Mobile Legends untuk melakukan top up atau membeli item-game dengan cara yang aman dan efisien.

## Flowchart Program
![WhatsApp Image 2023-10-27 at 12 17 50 AM](https://github.com/AdliMS/PA-PBO/assets/53502055/8eb4e1a1-60ab-4edf-968a-ef322558e229)

## ERD
![image](https://github.com/AdliMS/PA-PBO/assets/53502055/bc89194e-7e1a-4cc8-8ff4-723d437358b0)

## Hierarki Kelas
![image](https://github.com/AdliMS/PA-PBO/assets/53502055/a4e10d62-8379-492c-9047-9c331e238fdc)

## Screenshot Kodingan dengan Penjelasan
![image](https://github.com/AdliMS/PA-PBO/assets/53502055/fe1e97ce-8516-4cf6-b72b-7250c542527d)

Ini adalah method create_connection() pada kelas DBCon untuk membuat hubungan ke database.


![image](https://github.com/AdliMS/PA-PBO/assets/53502055/6180f05c-9d37-4267-acbe-cdc165d8e00f)

method login_admin() untuk menghandle login bagi akun admin.


![image](https://github.com/AdliMS/PA-PBO/assets/53502055/0be29a18-0c6b-4519-b58f-79f50459935a)

method register() untuk menghandle register bagi akun user.


![image](https://github.com/AdliMS/PA-PBO/assets/53502055/fe872994-f863-4ac9-a75d-1641caaccabf)
method fill_table() di dalam kelas ItemList yang merupakan subclass dari DBCon (extends DBCon). Method ini berfungsi untuk mengisi (populate) table di dalam jFrame MenuCRUD.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/d8771ebb-3112-4b4c-92b8-c3272e34093c)
method ini berfungsi untuk menambahkan diamond ke dalam tabel di jFrame MenuCRUD. 

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/3f7803d0-8954-4e0e-a995-13989bce5a7e)
method ini berfungsi untuk mengubah diamond yang dipilih di tabel dalam jFrame MenuCRUD.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/6e09e023-773a-407d-a392-3f8725be9087)
method ini berfungsi untuk menghapus diamond yang dipilih di tabel dalam jFrame MenuCRUD.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/dbcc6724-1e9f-4602-b6ed-37f8cd6cf93f)
method ini berfungsi untuk melakukan reload pada tabel agar data yang telah diubah, ditambah, maupun dihapus dapat lngsung ditampilkan di tabelnya.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/47ff73c5-e19e-4502-b237-c7c9d6ba7331)
method-method setter dan getter untuk harga dan stok item, juga getter untuk id item.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/47a96e46-671a-4c88-b476-59e09051c1b2)
kelas - kelas turunan dari kelas ItemList.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/9c1be2b4-4612-4bbc-aa30-144c6d5c0039)
Ini adalah method login_user() pada kelas User, yang merupakan turunan dari kelas DBCon (extends DBCon). Method ini berfungsi untuk menghandle login bagi user.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/8401a86d-fa9c-4c26-bc5a-82dc70ae815d)
method getter untuk mendapatkan saldo dari tabel user di database.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/f3a2ed5a-dfa2-4625-b6b7-409a86be4101)
method getter untuk mendapatkan id user berdasarkan username dari user.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/cfc158c9-67d5-43b2-9cf1-bb7d7bf8a2b9)
![image](https://github.com/AdliMS/PA-PBO/assets/53502055/16d3ec14-a1b1-41f6-a4ab-89b3afdd2851)
method buttonActionPerformed pada jFrame Login.java. Dalam kodenya, terdapat dua macam login. Yaitu untuk admin dan user.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/2c7b20cf-0432-44e3-981e-830cd36e2d82)
method buttonActionPerformed untuk menuju ke laman register (Register.java).

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/e9f051fe-705c-4ebc-b8f9-5194cee75762)
method buttonActionPerformed pada jFrame Register.java untuk melakukan register.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/d338e1a2-d219-4f43-b05b-defbea3912d3)
method buttonActionPerformed untuk kembali ke laman login (Login.java).

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/52ea56e8-59af-4554-b465-535638574398)
method buttonActionPerformed untuk menampilkan JOptionPane "Yes" dan "No". Jika pilihan "Yes", maka akan kembali ke laman Login (Login.java). Jika pilihan "No", maka akan tetap di laman Admin (MenuCRUD).

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/ee1e7ecc-0c0b-4dbb-ba1a-47fd9f4fa5f4)
method buttonActionPerformed untuk mengupdate item pada comboBox dari database. Lalu menentukan harga item berdasarkan pilihan dari comboBox yang dipilih.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/e819bc60-5573-4950-bea2-22274469bc04)
method buttonActionPerformed untuk menambahkan item (AddItem.java).

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/ed92f81c-a43b-454e-beae-66c0c2107e21)
method buttonActionPerformed untuk menampilkan JOptionPane "Yes" dan "No". Jika pilihan "Yes", maka akan kembali ke laman Login (Login.java). Jika pilihan "No", maka akan tetap di laman Admin (MenuCRUD).

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/27030a2b-fc4d-41b8-b332-fa4ce69b91aa)
method buttonActionPerformed untuk menambahkan listener ke tabel.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/239e4743-8c3c-43bc-ad25-65b8934ad4e5)
method buttonActionPerformed untuk menghapus item dari database lalu mengupdate tabel.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/0c481f34-6060-436f-aa09-e6ca59a531d5)
method buttonActionPerformed untuk mengubah item di dalam tabel dan database.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/2f1c1a5e-a23e-4a6a-9fa7-4715d2644f9e)
method buttonActionPerformed untuk menambahkan item dari database lalu mengupdate tabel.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/8590540c-dad0-4f44-8c41-e993a7d641c4)
method buttonActionPerformed untuk menerima konfirmasi penambahan data dari admin.

![image](https://github.com/AdliMS/PA-PBO/assets/53502055/5eaff652-9b13-4ca6-9416-da2347858415)
method buttonActionPerformed untuk menerima konfirmasi pengubahan data dari admin.

## Screenshot Output
![Screenshot 2023-11-04 044350](https://github.com/AdliMS/PA-PBO/assets/53502055/536f53ca-ec8e-4251-acb8-359bdffe2a32)
![Screenshot 2023-11-04 044356](https://github.com/AdliMS/PA-PBO/assets/53502055/3c239a3e-60ed-4563-8c91-7a53f314fb75)
![Screenshot 2023-11-04 044414](https://github.com/AdliMS/PA-PBO/assets/53502055/156e1b4b-b71f-4ca9-9f00-0e6917dfb6fc)
![Screenshot 2023-11-04 044448](https://github.com/AdliMS/PA-PBO/assets/53502055/caae709d-4685-4c24-86fa-d2989008c4b6)
![Screenshot 2023-11-04 044456](https://github.com/AdliMS/PA-PBO/assets/53502055/e4e03a42-131b-4d49-b3c6-c7d89f9cc95f)
![Screenshot 2023-11-04 044519](https://github.com/AdliMS/PA-PBO/assets/53502055/3c495988-6cda-4055-be60-27d065052c6b)
