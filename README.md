# Dokumentasi

Alihan ke Bahasa Melayu. 

Website asal adalah dalam Bahasa Inggeris boleh didapati disini **https://ninjutsu-os.github.io/docs/**

## Ninjutsu OS

Bahagian penting untuk sesebuah sistem pengendalian (OS) adalah dokumentasi, manual teknikal yang menerangkan operasi dan penggunaan program tersebut.

Sebagai sebahagian daripada usahanya untuk membuat sistem pengendalian yang berkualiti tinggi, Ninjutsu Projek berusaha sedaya upaya untuk menyediakan dokumentasi yang tepat dan padat kepada semua penggunanya dalam bentuk yang mudah diakses.

Dokumentasi ini adalah kerja berterusan yang sedang berjalan, dan semua pengguna Ninjutsu dijemput untuk menyumbang dalam proses pembuatan dan terjemahan dokumentasi ini.

![image](https://user-images.githubusercontent.com/44063862/82111864-77352f80-977a-11ea-8d37-29a18ec4675b.png)

## Apakah Ninjutsu Projek?

Ninjutsu adalah Ujian Penembusan/pengedaran pasukan merah berdasarkan Windows yang berfokus pada Ujian Penembusan, pasukan merah, Pengauditan Keselamatan, perisian berbahaya dan Ujian Penembusan Android.

Ini termasuk alat mudah alih yang lengkap untuk pakar keselamatan, tetapi ia juga termasuk Ujian Penembusan persekitaran bersepadu Android yang telah dikonfigurasi dan dipasang. Selain itu, lindungi privasi anda dengan mengubah dan menyesuaikan Windows 10, mengnyahaktifkan perkhidmatan/Aplikasi pengumpulan untuk meningkatkan anonimitas dan prestasi.

Ninjutsu berisi lebih dari 800 alat yang ditujukan untuk pelbagai tugas keselamatan informasi, seperti Ujian Penembusan, pasukan merah, perisian berbahaya, Ujian Penembusan Android, dan Kejuruteraan balikan. Ninjutsu diciptakan dan disesuaikan oleh [Hasan Al-Qawzai](https://www.linkedin.com/in/alqawzai/) (Pakar keselamatan maklumat).

Projek Ninjutsu ini dilancarkan pada 08th May, 2020.

## Fungsi

* Hadir dengan fungsi Ujian Penembusan, Pasukan Merah dan Ujian Penembusan persekitaran bersepadu Android untuk Windows 10.
* Lebih dari 800 alat Ujian Penembusan
* Alat percuma dari sumber terbuka. 
* Fungsi baris perintah (CL).
* Terminal dengan banyak ciri yang berguna.
* Windows 10 yang disesuaikan dengan perubahan yang besar dan optimum.
* Lindungi privasi anda dengan Windows 10 yang telah diubah dan disesuaikan.
* Mengnyahaktifkan kebanyakan ciri-ciri yang tidak disukai yang terdapat di dalam Windows.
* Penyingkiran komponen Windows yang tidak diingini.
* Mengnyinkirkan atau kebanyakan mengnyahaktifkan program dan perkhidmatan Windows.

## Muat turun Projek Ninjutsu

**PENTING!** Jangan sekali-kali memuat turun sistem pengendalian Ninjutsu dari tempat lain selain dari sumber rasmi. Sentiasa mengesahkan MD5/SHA256 sistem ini yang telah anda muat turun dengan nilai rasmi kami. Sangat mudah bagi entiti yang berniat jahat untuk mengubah pemasangan Projek Ninjutsu agar mengandungi eksploitasi atau perisian berbahaya dan menghoskannya secara tidak rasmi.

## Dimana anda boleh dapatkan sistem pengendalian Ninjutsu secara rasmi

Sistem pengendalian Projek Ninjutsu boleh didapati sebagai fail .iso yang boleh dimuat turun secara langsung atau melalui fail .torrent.

## Mengesahkan Sistem pengendalian Ninjutsu yang anda muat turun

**Kenapa saya perlu lakukan ini?**

Sebelum anda menjalankan OS Ninjutsu, atau memasangnya ke cakera keras anda, anda ingin memastikan bahawa apa yang anda miliki sebenarnya adalah OS Ninjutsu sebenar, dan bukannya palsu. Ninjutsu adalah alat ujian penembusan profesional dan pasukan merah. Sebagai penguji penembusan profesional, adalah sangat penting untuk anda yakin terhadap integriti alat anda: jika alat anda tidak boleh dipercayai, penyiasatan anda juga tidak boleh dipercayai.

### Windows

```
Ex : CertUtil -hashfile <File Nme> MD5
     CertUtil -hashfile Ninjutsu-v1.0.iso MD5
```
![image](https://user-images.githubusercontent.com/44063862/82112839-8371ba80-9783-11ea-9616-7930b8d116bf.png)

Menggunakan alat pihak ketiga:

1- Muat turun [Kalkulator Checksum](http://www.checksumcalculator.com/)

2- Jalankan **checksumcalculator_setup.exe**

3- Ikut arahan untuk memasang program.

4- Buka Kalkulator Checksum, klik butang "Browse" di sebelah kotak fail dan semak fail yang anda ingin periksa. Pilih fail "Ninjutsu-v1.0.iso".

5- Pilih jenis Checksum, tetapan asal, Checksum ditetapkan ke MD5.

6- Klik butang kira.

![image](https://user-images.githubusercontent.com/44063862/82113024-355db680-9785-11ea-95ae-ab9c636d6442.png)

### Linux

```
md5sum Ninjutsu-v1.0.iso

sha256sum Ninjutsu-v1.0.iso
```

### MacOS

```
md5 Ninjutsu-v1.0.iso

shasum -a 256 Ninjutsu-v1.0.iso
```

## Panduan pengguna

**Untuk permulaan**

Keperluan Sistem Minimum:

* CPU : Intel/AMD Prosesor "Dual core" 
* RAM : 2 GB of RAM DDR3/DDR4
* Storan : 60 GB ruang cakera keras

**Memasang Ninjutsu sebagai sistem pengendalian pada komputer atau laptop:**

Apa yang anda perlukan:

* Sahkan skema pembahagi anda
* Pemacu kilat USB bersaiz 32 GB
* Iso sistem pengendalian Ninjutsu
* Storan : 60 GB ruang cakera keras (Minimum) (Sistem pengendalian Ninjutsu akan mengambil 53 GB dari jumlah storan yang ada)
* [Rufus software](https://rufus.ie)

Sebelum anda mula format mesin anda, periksa skema partition cakera anda

**PENTING!** Jangan lupa komputer riba anda termasuk pemasangan windows asal anda, ia dipanggil mod pemulihan atau kilang tetapan semula windows, jadi jangan lakukan tutorial ini jika anda tidak mahu kehilangan windows pemulihan anda, saya cadangkan anda menggunakan **PartitionMagic** untuk memeriksa cakera anda sebelum format.

Anda dapat melihat maklumat ini di alat Pengurusan Cakera yang disertakan dengan Windows. Untuk mengaksesnya, klik-kanan pada menu Start atau tekan kekunci Windows+X dan pilih Pengurusan Cakera. Anda juga boleh menekan Windows+R untuk membuka dialog "Run", taip "diskmgmt.msc" ke dalam kotak, dan tekan kekunci "Enter".

![image](https://user-images.githubusercontent.com/44063862/82113514-24af3f80-9789-11ea-89fd-4230d1496e0b.png)

Pilih Pengurusan Cakera

![image](https://user-images.githubusercontent.com/44063862/82113533-4f999380-9789-11ea-9044-260e3f2cda8c.png)

![image](https://user-images.githubusercontent.com/44063862/82113541-5fb17300-9789-11ea-8ccb-41d130c389f9.png)

Cari cakera yang ingin anda periksa di tetingkap Pengurusan Cakera. Klik-kanan dan pilih "Properties."

Klik ke tab "Volume". Di sebelah kanan "Partition style", anda akan nampak "Master Boot Record (MBR)" atau "GUID Partition Table (GPT)", bergantung pada cakera yang digunakan.

![image](https://user-images.githubusercontent.com/44063862/82113584-b5861b00-9789-11ea-8e74-9a7f27093f5a.png)

Muat turun Muat turun perisian Rufus dan plugin atau Pemacu kilat USB

Buka perisian Rufus

![image](https://user-images.githubusercontent.com/44063862/82113609-f54d0280-9789-11ea-821d-c8c4d9b4864d.png)

Dalam contoh kami, kami akan membuat Pemacu kilat USB yang boleh di boot "GPT" yang mengandungi sistem pengendalian Ninjutsu, Jangan mengikuti pelajaran secara membabi buta, mungkin komputer riba/komputer anda adalah MBR, jadi berhati-hatilah.

Sesudah selesai membuat pemacu kilat USB yang boleh di boot, Selepas itu mulakan semula komputer anda dan boot dari pemacu kilat USB.

Gunakan sumber internet untuk mencari Cara Boot dari pemacu kilat USB pada Windows

![image](https://user-images.githubusercontent.com/44063862/82113718-b9ff0380-978a-11ea-978b-a183de800516.png)

![image](https://user-images.githubusercontent.com/44063862/82113724-c4210200-978a-11ea-8bdc-40746102764e.png)

![image](https://user-images.githubusercontent.com/44063862/82113726-c84d1f80-978a-11ea-8edf-09b5d755858e.png)

![image](https://user-images.githubusercontent.com/44063862/82113731-d26f1e00-978a-11ea-9fbe-0c9c6a6ea6d3.png)

**AMARAN** Sekarang berhati-hati saya tidak mahu anda memformat pemacu yang salah dan kehilangan data anda

Tekan kekunci shift+F10 untuk membuka CMD

Kemudian taip arahan berikut:

```
Diskpart
List vol
Dir d:\
```

![image](https://user-images.githubusercontent.com/44063862/82113806-5c1eeb80-978b-11ea-8fbd-3f2e98cd89ad.png)

![image](https://user-images.githubusercontent.com/44063862/82113811-6214cc80-978b-11ea-9430-e4bd9e128f77.png)

![image](https://user-images.githubusercontent.com/44063862/82113816-6e992500-978b-11ea-941c-15b439b1f7cb.png)

![image](https://user-images.githubusercontent.com/44063862/82113819-722cac00-978b-11ea-8602-d6d1c4e24a18.png)

![image](https://user-images.githubusercontent.com/44063862/82113836-84a6e580-978b-11ea-86bc-bdd9858f1c3e.png)

![image](https://user-images.githubusercontent.com/44063862/82113840-8bcdf380-978b-11ea-8790-69c340339014.png)

![image](https://user-images.githubusercontent.com/44063862/82113859-a1dbb400-978b-11ea-8f14-33bf7d0302f9.png)

Pemasangan selesai. Tahniah!

Selepas pemasangan mungkin Windows 10 anda akan perlahan dari biasa. Jadi saya cadangkan anda untuk mengemas kini pemacu, anda boleh menggunakan Driver Booster 7 untuk mengemas kini dan mengubah suai komputer riba anda.

[Download](https://www.iobit.com/en/driver-booster.php)




























