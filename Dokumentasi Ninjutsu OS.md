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

### Memasang Ninjutsu sebagai sistem pengendalian pada komputer atau laptop:

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

### Dual boot Windows 10,8,7 dengan sistem pengendalian Ninjutsu

Kami akan menerangkan segalanya secara terperinci mengenai "Bagaimana untuk memasang sistem pengendalian Ninjutsu sebagai boot kedua dengan Windows 10,8,7 utama anda.

Keperluan Sistem Minimum:

1- Sistem pengendalian Ninjutsu

2- Pembahagi pemacu yang kosong di dalam mesin anda dengan 55 GB (Minimum) (Sistem pengendalian Ninjutsu akan mengambil 53 GB dari jumlah storan yang ada)

Dalam contoh ini, saya akan memasang sistem pengendalian Ninjutsu pada pembahagi pmacu E:
Anda hanya perlu menentukan di mana anda ingin memasang sistem operasi lain (sistem pengendalian Ninjutsu) di komputer riba/komputer anda.

Anda dapat melihat maklumat ini di alat Pengurusan Cakera yang disertakan dengan Windows. Untuk mengaksesnya, klik-kanan pada menu Start atau tekan kekunci Windows+X dan pilih Pengurusan Cakera. Anda juga boleh menekan Windows+R untuk membuka dialog "Run", taip "diskmgmt.msc" ke dalam kotak, dan tekan kekunci "Enter".

![image](https://user-images.githubusercontent.com/44063862/82114273-524ab780-978e-11ea-8c92-875d1de8260e.png)

Jika anda tidak mempunyai pembahagi pemacu kosong untuk memasang sistem pengendalian Ninjutsu, anda harus membuat pembahagi pemacu dan memformatnya, dalam tutorial saya pembahagi pemacu Windows 10

Langkah 1: Klik-kanan satu pembahagi pemacu cakera keras dan pilih "Shrink Volume".

![image](https://user-images.githubusercontent.com/44063862/82114368-04827f00-978f-11ea-930c-3f2b78087612.png)

Langkah 2: Masukkan jumlah ruang yang ingin anda kecilkan dalam MB seperti yang ditunjukkan di bawah kemudian klik pada butang "Shrink".

![image](https://user-images.githubusercontent.com/44063862/82114376-1401c800-978f-11ea-8dc1-fbaa132cdb1f.png)

Langkah 3: Klik-kanan pada ruang yang tidak diperuntukkan dan pilih "New Simple Volume".

![image](https://user-images.githubusercontent.com/44063862/82114467-76f35f00-978f-11ea-9a2a-4a263019f63b.png)

Langkah 4: Anda sekarang akan memasuki antara muka "New Simple Volume" dengan mengklik "Seterusnya" dan tentukan ukuran saiz.

![image](https://user-images.githubusercontent.com/44063862/82114513-b1f59280-978f-11ea-92e1-f39cbcb22e8b.png)

Langkah 5: Tetapkan Huruf atau Laluan Pemacu, kemudian format pembahagi ke dalam tetapan asal sistem fail NTFS. Klik "Selesai" untuk menyelesaikan pembuatan partisi baru di Windows 10.

![image](https://user-images.githubusercontent.com/44063862/82114524-c6398f80-978f-11ea-880a-f35dc4c54a33.png)

Kami akan menerangkan cara memasang dan menggunakan edisi dua tetingkap di komputer/komputer riba yang sama:

```
C:\ ------------> Windows 10 , 8 or 7
E:\ ------------> Ninjutsu OS
D:\ ------------> Ninjutsu OS Image
```

Untuk memasang sistem pengendalian Ninjutsu, taip arahan berikut:

```
dism /Apply-Image /ImageFile:D:\Sources\install.wim /Index:1 /ApplyDir:E:\
```

![image](https://user-images.githubusercontent.com/44063862/82114643-8cb55400-9790-11ea-9df7-1a2a4be267ac.png)

Sekarang tunggu sehingga sistem pengendalian Ninjutsu digunakan di pemacu E: anda

Langkah seterusnya, tambahkan Windows yang digunakan pada pemacu E: ke menu boot Windows, gunakan arahan berikut:

```
bcdboot E:\Windows
```

![image](https://user-images.githubusercontent.com/44063862/82114733-21b84d00-9791-11ea-97e9-e2ef90c317ba.png)

Now write this command to check defult profile and currnet profile windows

Sekarang tulis arahan ini untuk memeriksa tetingkap profil tetapan asal dan profil semasa

BCDEdit ialah alat baris perintah (CL) yang digunakan untuk "Boot Configuration Data"(BCD)

Fail BCD menyediakan ruang yang digunakan untuk menerangkan aplikasi boot dan tetapan aplikasi boot.

BCDEdit 
BCDEdit dapat digunakan untuk berbagai tujuan, termasuk membuat ruang baru, mengubahsuai ruang yang ada, menambahkan pilihan menu boot, dan sebagainya.

Anda memerlukan hak pentadbiran untuk menggunakan BCDEdit untuk mengubah BCD

buka cmd anda sebagai pentadbir

```
bcdedit 
```

Pengecam Pilihan Boot:

```
{default} device partion E:  (Ninjutso OS)

{current} device partion C: (your current system )
```

![image](https://user-images.githubusercontent.com/44063862/82114937-46f98b00-9792-11ea-800c-3a31cf5f4efe.png)

Sekarang kita perlu mengubah penerangan boot. Ketika digunakan, OS baru mempunyai ID {tetapan asal}. Untuk menamakan semula, berikan penerangan yang lebih baik, gunakan arahan berikut:

```
bcdedit /set {default} description "Ninjutsu OS"
bcdedit /set {current} description Windows 10 Pro"
```

![image](https://user-images.githubusercontent.com/44063862/82114991-b0799980-9792-11ea-8b3e-765aaade9808.png)

![image](https://user-images.githubusercontent.com/44063862/82115003-bcfdf200-9792-11ea-83ee-95f9c2a78bfd.png)

![image](https://user-images.githubusercontent.com/44063862/82115012-c8e9b400-9792-11ea-96bf-2c37a74078de.png)


## Cara Memasang sistem pengendalian Ninjutsu di VMware Workstation :

![image](https://user-images.githubusercontent.com/44063862/82115342-d3a54880-9794-11ea-9411-d74f90653310.png)

![image](https://user-images.githubusercontent.com/44063862/82115346-d7d16600-9794-11ea-857b-e060a3c9eba4.png)

![image](https://user-images.githubusercontent.com/44063862/82115352-dd2eb080-9794-11ea-949f-a0ebafc208a2.png)

![image](https://user-images.githubusercontent.com/44063862/82115361-e3249180-9794-11ea-80ad-314a79fde708.png)

![image](https://user-images.githubusercontent.com/44063862/82115370-e9b30900-9794-11ea-8724-3e646f3302ca.png)

![image](https://user-images.githubusercontent.com/44063862/82115372-ecadf980-9794-11ea-80bb-b251389bd641.png)

![image](https://user-images.githubusercontent.com/44063862/82115376-f0da1700-9794-11ea-83cd-4d24510e13b0.png)

![image](https://user-images.githubusercontent.com/44063862/82115380-f59ecb00-9794-11ea-8c04-4b3a9546cd9a.png)

![image](https://user-images.githubusercontent.com/44063862/82115384-fc2d4280-9794-11ea-8b05-5e01d91d6c1b.png)

![image](https://user-images.githubusercontent.com/44063862/82115390-00f1f680-9795-11ea-9896-0bf6434f9d19.png)

![image](https://user-images.githubusercontent.com/44063862/82115395-051e1400-9795-11ea-8e56-9255d575960b.png)

![image](https://user-images.githubusercontent.com/44063862/82115398-09e2c800-9795-11ea-97e2-f1e7a1ac382f.png)

![image](https://user-images.githubusercontent.com/44063862/82115402-0d764f00-9795-11ea-92ce-90a1262be8b1.png)

![image](https://user-images.githubusercontent.com/44063862/82115406-1109d600-9795-11ea-8453-c3357b0eaa70.png)

![image](https://user-images.githubusercontent.com/44063862/82115408-1535f380-9795-11ea-86bc-7cd4e4d4ce2a.png)

![image](https://user-images.githubusercontent.com/44063862/82115410-19621100-9795-11ea-8c78-fcdedeebb8c9.png)

![image](https://user-images.githubusercontent.com/44063862/82115413-1cf59800-9795-11ea-9c4b-d64bb0feb5eb.png)


## Cara Memasang sistem pengendalian Ninjutsu di Oracle VM VirtualBox :

![image](https://user-images.githubusercontent.com/44063862/82115441-60e89d00-9795-11ea-9f6b-aaa4fe2ba982.png)

![image](https://user-images.githubusercontent.com/44063862/82115444-647c2400-9795-11ea-88d0-da49c6a57342.png)

![image](https://user-images.githubusercontent.com/44063862/82115445-66de7e00-9795-11ea-9cc2-b71cb023abcd.png)

![image](https://user-images.githubusercontent.com/44063862/82115448-69d96e80-9795-11ea-900b-6c65c4248c62.png)

![image](https://user-images.githubusercontent.com/44063862/82115450-6c3bc880-9795-11ea-85e3-41761b939642.png)

![image](https://user-images.githubusercontent.com/44063862/82115452-6f36b900-9795-11ea-9336-3427a645fecd.png)

![image](https://user-images.githubusercontent.com/44063862/82115456-71991300-9795-11ea-9e8d-b1b6fc4cb2a7.png)

![image](https://user-images.githubusercontent.com/44063862/82115459-765dc700-9795-11ea-93b9-f9a075e602ac.png)

![image](https://user-images.githubusercontent.com/44063862/82115462-79f14e00-9795-11ea-831c-9dc6ed3b06e6.png)

![image](https://user-images.githubusercontent.com/44063862/82115466-7d84d500-9795-11ea-9158-6f76a868d8a4.png)

![image](https://user-images.githubusercontent.com/44063862/82115468-807fc580-9795-11ea-88ab-e4dcb63758bc.png)

![image](https://user-images.githubusercontent.com/44063862/82115471-84134c80-9795-11ea-8bed-3e620d0b3a4f.png)

![image](https://user-images.githubusercontent.com/44063862/82115473-870e3d00-9795-11ea-8198-db3c291a9326.png)

![image](https://user-images.githubusercontent.com/44063862/82115478-8b3a5a80-9795-11ea-9c5a-5dcd0d31f3c4.png)

![image](https://user-images.githubusercontent.com/44063862/82115479-8f667800-9795-11ea-894c-02f210d7ced4.png)

![image](https://user-images.githubusercontent.com/44063862/82115507-cdfc3280-9795-11ea-88d3-5a671e203015.png)

![image](https://user-images.githubusercontent.com/44063862/82115516-d81e3100-9795-11ea-8588-6c8464dcc799.png)


### Tingkatkan privasi anda dengan Simple dnscrypt + VPN:

Apakah maklumat yang mungkin akan didedahkan kepada kerajaan/ISP semasa anda melayari Internet? Dan apa jalan penyelesaiannya?

Dalam penggunaan Internet yang biasa, maklumat yang perlu anda jaga:

1. Alamat MAC

2. Permintaan DNS

3. Alamat laman web atau perkhidmatan walaupun dalam sambungan TLS

4. Alamat IP laman web atau perkhidmatan

5. Maklumat yang tidak disulitkan

>  Alamat MAC

Alamat Mac ini dapat mengesan kedudukan anda. Sebaiknya anda mempunyai alamat MAC yang berbeza setiap kali anda menyambung ke Internet. Anda boleh menggunakan pelbagai alat, tetapi di Windows 10, anda boleh mengaktifkannya:

Hidupkan atau Matikan Alamat MAC Perkakasan Rawak untuk Wi-Fi di Windows 10

![image](https://user-images.githubusercontent.com/44063862/82115769-62b36000-9797-11ea-85a8-4cf68d0bb989.png)

Cara lain untuk menukar alamat MAC anda dengan menggunakan perisian seperti

* MAC Address Scanner 5.0 https://www.majorgeeks.com/files/details/mac_address_scanner.html
* MacMakeup 2.2.3.5 https://www.majorgeeks.com/files/details/mac_makeup.html


>  Permintaan DNS

Biasanya, walaupun anda menggunakan 1.1.1.1, permintaan DNS anda dapat didengar dengan mudah. Hanya jika anda menggunakan DNSCrypt atau item lain yang disulitkan, permintaan DNS anda tidak akan didengari.

Anda boleh menggunakan SimpleDNScrypt, ikuti gambar yang ditunjukkan di bawah

![image](https://user-images.githubusercontent.com/44063862/82115832-cfc6f580-9797-11ea-9de0-12b4cbb4f640.png)

![image](https://user-images.githubusercontent.com/44063862/82115834-d6ee0380-9797-11ea-8593-59698e6c8cbc.png)

![image](https://user-images.githubusercontent.com/44063862/82115839-db1a2100-9797-11ea-96b0-c64e3e10ca90.png)

> Alamat laman web atau perkhidmatan walaupun dalam sambungan TLS

Alamat laman web yang anda kunjungi akan dikirim dalam teks biasa melalui SNI, yang dapat didengar. Anda hanya boleh menggunakan proksi atau VPN yang sah untuk menyelesaikan masalah ini.

> Alamat IP laman web atau perkhidmatan

Banyak laman web mempunyai pelayan khusus. Menyumbangkan alamat IP, sama dengan menyumbangkan alamat laman web. Seperti sebelumnya, anda hanya boleh menggunakan proksi atau VPN yang sah untuk menyelesaikan masalah ini.

> Maklumat yang tidak disulitkan

Maklumat yang tidak disulitkan tidak memerlukan penjelasan dan anda harus menggunakan VPN. Tetapi masih ada masalah besar! Apa yang berlaku sekiranya anda memutuskan sambungan VPN secara sengaja atau tidak sengaja?

Ikuti gambar yang ditunjukkan di bawah

![image](https://user-images.githubusercontent.com/44063862/82115991-fb96ab00-9798-11ea-9419-011a428bfc55.png)

![image](https://user-images.githubusercontent.com/44063862/82115995-fe919b80-9798-11ea-8a63-e2e26db4bc5e.png)

![image](https://user-images.githubusercontent.com/44063862/82116002-02252280-9799-11ea-9fbb-e4240593fc87.png)

![image](https://user-images.githubusercontent.com/44063862/82116004-05201300-9799-11ea-8e9c-3da4973eb0dd.png)

![image](https://user-images.githubusercontent.com/44063862/82116006-07826d00-9799-11ea-882e-787844369d17.png)

![image](https://user-images.githubusercontent.com/44063862/82116011-0cdfb780-9799-11ea-923f-d1d8c6cd31ca.png)

## Memasang Docker untuk Windows dan memasang Kali linux:

Docker membantu anda mempunyai persekitaran di mana kita boleh mempunyai alat yang berbeza tanpa harus mempunyai masalah dengan perpustakaan atau pergantungan yang berbeza yang memerlukan alat tertentu.

Kini menggunakan Docker untuk menjalankan Alat Keselamatan Siber semakin popular.

Untuk menggunakan docker di komputer anda, anda haruslah:

1) Aktifkan Hyper-V, secara tetapan asal, sistem pengendalian Ninjutsu telah aktifkan "Hyper-V".

2) Aktifkan Virtualisasi Intel VT-X/AMD pada VMware/VirtualBox dan PC.

Anda harus sedar bahawa Docker memerlukan sambungan perkakasan maya VT-X/AMD-v untuk diaktifkan sebelum anda dapat menjalankan sebarang kontena.

Bergantung pada komputer anda, anda mungkin perlu menghidupkan semula dan mengaktifkannya di BIOS anda.

Anda boleh memeriksa apakah VT-X/AMD-v diaktifkan dengan menjalankan maklumat sistem dari command prompt.

```
systeminfo
```

### 1. Aktifkan Hyper-V pada Windows 10 

![image](https://user-images.githubusercontent.com/44063862/82136686-c8a8f180-9842-11ea-992a-26e32d5cca94.png)

### 2. Aktifkan virtualisasi Intel VT-x atau AMD 

Untuk membolehkan virtualisasi Intel VT-X & AMD, buka VMware dan pilih mesin maya yang anda mahu aktifkan virtualisasi Intel/AMD, kemudian klik Edit tetapan mesin maya.

![image](https://user-images.githubusercontent.com/44063862/82136727-16bdf500-9843-11ea-887e-8e61e9cbe62a.png)

Sekarang pilih pilihan Pemproses dan anda akan melihat pilihan Virtualisasi Intel VT-X & AMD di sebelah dan tandakan jika anda mahu. Anda juga boleh membiarkan mesin virtualisasi secara tetapan asal (Automatik), pilihan automatik menggunakan tiga pilihan di sana apabila diperlukan dan matikannya apabila tidak diperlukan.

![image](https://user-images.githubusercontent.com/44063862/82136762-74ead800-9843-11ea-8616-64c40ec57d6e.png)

Aktifkan virtualisasi Intel VT-x/AMD pada VirtualBox.

![image](https://user-images.githubusercontent.com/44063862/82136770-90ee7980-9843-11ea-80da-cafb67d9c959.png)

Di sini, pilih tab Sistem dan pilih tab Pecutan, maka anda dapat lihat dan aktifkan virtualisasi Intel VT-x atau AMD dan klik Ok.

![image](https://user-images.githubusercontent.com/44063862/82136794-c2ffdb80-9843-11ea-8a21-6916ec9bd164.png)

Aktifkan Virtualisasi Intel VT-x/AMD pada komputer/Komputer riba anda.

Ikuti panduan motherboard/Laptop untuk mengaktifkan Intel VT-x/AMD Virtualization dari Bios.

![image](https://user-images.githubusercontent.com/44063862/82136808-f17db680-9843-11ea-8c02-26abda4168c0.png)

Jadi sekarang setelah mengaktifkan virtualisasi Intel VT-x atau AMD di Vmware/VirtualBox dan komputer anda, kita akan mula memasang Docker.

## Memasang Docker

Anda boleh muat turun Docker untuk Windows:

```
choco install docker-desktop
```

![image](https://user-images.githubusercontent.com/44063862/82136835-63ee9680-9844-11ea-9a5e-4fd0f6eaea51.png)

Sekiranya semuanya berfungsi seperti yang diharapkan, anda akan melihat senarai kontena kosong yang sedang berjalan.

### Memasang Kali Linux daripada Docker

Kita semua sudah mengetahui kali Linux mempunyai pelbagai alat yang berguna untuk menjalankan tugas yang berbeza, tetapi kita juga mempunyai docker untuk menggunakan kali.

Menyediakan sistem pengendalian Docker Kali Linux :

```
docker pull kalilinux/kali-rolling
docker run -t -i kalilinux/kali-rolling /bin/bash
```

![image](https://user-images.githubusercontent.com/44063862/82136884-1aeb1200-9845-11ea-9bcc-ca374009a101.png)

Sekarang saya akan memasang Metasploit, nmap dan sqlmap pada Kali Linux.

```
apt-get update && apt-get install metasploit-framework nmap sqlmap
```

![image](https://user-images.githubusercontent.com/44063862/82136894-43730c00-9845-11ea-9313-62107e06eae9.png)

![image](https://user-images.githubusercontent.com/44063862/82136896-4837c000-9845-11ea-9619-f43cf35211e4.png)

Cara hapuskan kontena Docker Kali Linux dari komputer anda:

Anda boleh mendapatkan senarai semua kontena dengan menyerahkan bendera -a ke perintah ls kontena docker:

```
docker container ls -a
```

Hasilnya akan kelihatan seperti ini:

```
C:\Users\Administrator\Desktop>docker container ls -a
CONTAINER ID    IMAGE                    COMMAND          CREATED             STATUS                    PORTS          NAMES
2e89361f5005    kalilinux/kali-rolling   "/bin/bash"      54 minutes ago      Exited (130) 1 second ago                vibrant_meitner
```

Setelah anda mengetahui ID Kontena dari kontena yang ingin anda padamkan, hantarkannya ke docker kontena perintah rm. Sebagai contoh, untuk membuang dua kontena pertama yang disenaraikan dalam hasil di atas jalankan:

```
docker container rm 2e89361f5005
```

Kaedah dan contoh lain cara membuang Docker:

```
# docker ps -a
docker ps -a    
CONTAINER ID        IMAGE               COMMAND                CREATED             STATUS              PORTS               NAMES
d1c01c8eb336        ubuntu:14.04        "/bin/bash"            5 seconds ago       Exited (0) 3 seconds ago                ubuntu
df7834f86c78        debian:stable       "/bin/bash"            10 seconds ago      Up 9 seconds                            debian       
9bdd9d49a75b        mongo:3             "/entrypoint.sh mong   18 minutes ago      Up 18 minutes       27017/tcp           mongodb  
774b02c9c51a        oraclelinux:7       "/bin/bash"            27 minutes ago      Up 27 minutes                           oracle7

docker rm --force debian
docker rm --force mongodb
docker rm --force ubuntu
```

![image](https://user-images.githubusercontent.com/44063862/82137032-b3ce5d00-9846-11ea-9c49-352a8e14ca9c.png)

Untuk memeriksa saiz Docker:

```
C:\Users\Administrator\Desktop>docker image ls
REPOSITORY                   TAG                 IMAGE ID            CREATED             SIZE
ctfd/ctfd                    latest              ba8fec4b9a20        2 days ago          500MB
ctfwiki/ctf-wiki             latest              a4ad75128371        5 days ago          195MB
kalilinux/kali-rolling       latest              d88b418fb1f9        6 days ago          114MB
parrotsec/security           latest              35cfd692bb97        2 weeks ago         4.71GB
pyaillet/ctf-tools           latest              f57c8c381e52        6 months ago        992MB
simplysecurity/simplyemail   latest              58c90bda30f4        2 years ago         684MB
```

### Memasang sistem pengendalian Parrot pada sistem pengendalian Ninjutsu:

Repositori [Parrot](https://hub.docker.com/u/parrotsec)

Anda boleh memasang alat yang berbeza tanpa perlu ada masalah dengan perpustakaan atau pergantungan yang berbeza,

```
docker pull parrotsec/security
docker run -ti --network host parrotsec/security
```

![image](https://user-images.githubusercontent.com/44063862/82137077-47a02900-9847-11ea-934f-09d2af4368e7.png)

### Memasang alat tunggal SimplyEmail pada sistem pengendalian Ninjutsu:

```
docker pull simplysecurity/simplyemail
docker run -ti simplysecurity/simplyemail -h
docker run -ti simplysecurity/SimplyEmail.py -all -e cybersyndicates.com
or in verbose

docker run -ti simplysecurity/SimplyEmail.py -all -v -e cybersyndicates.com
or in verbose and no "Scope"

    docker run -ti simplysecurity/SimplyEmail.py -all -v -e cybersyndicates.com -s

or with email verification

    docker run -ti simplysecurity/SimplyEmail.py -all -v -verify -e cybersyndicates.com 

or with email verification & Name Creation

    docker run -ti simplysecurity/SimplyEmail.py -all -v -verify -n -e cybersyndicates.com 

or json automation

    docker run -ti simplysecurity/SimplyEmail.py -all -e cybersyndicates.com --json cs-json.txt
```

![image](https://user-images.githubusercontent.com/44063862/82137103-86ce7a00-9847-11ea-8785-a789d08644c3.png)

![image](https://user-images.githubusercontent.com/44063862/82137105-8a620100-9847-11ea-93ca-410fe688c29e.png)

### Memasang alat CTF:

```
docker pull zardus/ctf-tools
docker run -ti zardus/ctf-tools
```

![image](https://user-images.githubusercontent.com/44063862/82137120-aebddd80-9847-11ea-9e2c-c17ce51ba592.png)

![image](https://user-images.githubusercontent.com/44063862/82137121-b2516480-9847-11ea-9b77-b82fcfec24db.png)

Docker lain yang juga sangat berguna:

* https://hub.docker.com/r/aaaguirrep/pentest

**Kali Linux**

```
docker pull kalilinux/kali-rolling
docker run -t -i kalilinux/kali-rolling /bin/bash
```

**Parrot**

```
docker pull parrotsec/parrot-core
docker run -t -i parrotsec/parrot-core /bin/bash
```

**Flan vulnerability scanner** [Nmap-vulners](https://github.com/cloudflare/flan)

**Metasploit framework**

```
docker pull remnux/metasploit
docker run -t -i remnux/metasploit /bin/bash
```

**SQLMap**

```
docker pull paoloo/sqlmap
docker run -it paoloo/sqlmap --url http://localhost
```

**W3AF vulnerability scanner**

```
docker pull andresriancho/w3af
docker run -t -i kalilinux/kali-rolling /bin/bash
```

**Amass**

```
docker build -t amass https://github.com/OWASP/Amass.git
docker run -v OUTPUT_DIR_PATH:/.config/amass/ amass enum --list
```

**Sherlock**

```
docker build -t mysherlock-image .
docker run --rm -t mysherlock-image user123
docker run --rm -t -v "$PWD/results:/opt/sherlock/results" mysherlock-image -o /opt/sherlock/results/text.txt user123
```

## Docker Notes

**Senarai arahan CLI Docker**

```
docker
docker container --help
```

**Memaparkan maklumat dan versi Docker**

```
docker --version
docker version
docker info
```

**Mencari Docker**

```
docker search [search term]
docker search pentest
docker search centos
```

**Bina Docker image daripada Dockerfiles**

```
docker build -t <image name>:<tag> <file path of Dockerfile>
```

Pilihan:

Pilihan -t option adalah untuk spesifikkan nama atau tag "Image" (Jika tag tidak dispesifikkan, tetapan asal iaitu "terkini" akan digunakan)

Contoh: docker build -t nginx

**Menjalankan Docker**

```
docker run hello-world
```

**Senarai Docker**

```
docker images
docker image ls
```

Pilihan:

* **-quite** = pilihan ini untuk hanya menunjukkan ID "Image Dokcker"
* **-filter** = pilihan ini untuk menyaring image berdasarkan keadaan tertentu (contoh: –filter = dangling = true)

```
docker ps -a               # Lists containers (and tells you which images they are spun from)
docker rm <container_id>   # Removes a container
docker rmi <image_id>      # Removes an image 
docker rmi -f <image_id>   # Forces removal of image even if it is referenced in multiple repositories, 
                           # i.e. same image id given multiple names/tags 
                           # Will still fail if there is a docker container referencing image
```

* Senarai kontena Docker (berjalan, -all, semuanya dalam mod senyap)

```
docker container ls
docker container ls –all
docker container ls -aq
```

* Buang Docker images

```
docker rmi {image-id || image-name}
```

* Buang kontena Docker

```
docker rm {container-id} (no need to enter all id)
```

Alihan bahasa oleh **_Adani Kamal_**
