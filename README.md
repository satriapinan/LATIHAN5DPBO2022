# LATIHAN5DPBO2022

## Identitas
1. Nama : Satria Pinandita Abyatarsyah
2. NIM : 2000514
3. Prodi : Ilmu Komputer

## Janji
Saya Satria Pinandita Abyatarsyah mengerjakan evaluasi Latihan 5 Tugas Praktikum dalam mata kuliah DPBO untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Tahap Pengerjaan
a. **Mengganti font dan ukuran teks.** \
   Tahap ini dapat dilakukan dengan cara melakukan klik kanan pada komponen yang ingin diubah. Pilih menu `Properties`. Lalu ubah jenis font dan ukuran teks.
   Font yang digunakan adalah `Poppins` dengan default size `12`. Namun, pada title diberikan font size `36`\
b. **Ubah nama variabel komponen.** \
   Tahap ini dapat dilakukan dengan cara melakukan klik kanan pada komponen yang ingin diubah. Pilih menu `Change Variable Name`. Lalu ubah nama variabel sesuai dengan
   fungsi/jenis komponennya. \
c. **Menambahkan validasi ketika inputan tidak lengkap.** \
   Tahap ini dapat dilakukan dengan cara menambahkan satu method baru, yaitu `checkingData()` dan dengan memanfaatkan fungsi `equals("")`. Method akan dipanggil disetiap
   input maupun update. Jika method return 1, maka `JOptionPane` akan mengeluarkan pesan "Harap lengkapi data!". \
d. **Menghapus Data pada label inputan ketika sudah selesai melakukan suatu action** \
   Tahap ini dapat dilakukan dengan cara mereset isi semua variabel inputan dengan menggunakan `setText("")`. Setelah action pada suatu button dilakukan maka kode
   berikut akan dijalankan.
   ```
   txtNIM.setText("");
   txtName.setText("");
   txtScore.setText("");
   txtClass.setText("");
   ```
e. **Mengupdate tabel setiap kali ada perubahan** \
   Tahap ini dapat dilakukan dengan cara mengupdate tabel dengan menggunakan kode `tableRecord.setModel(setTable());` setelah modifikasi dilakukan.
   
## Run Program
1. Tampilan awal \
![TampilanAwal](https://user-images.githubusercontent.com/99194983/159202438-b4304441-0f09-433b-87ed-1ba6d1a1a065.png)
2. Insert data \
![Insert](https://user-images.githubusercontent.com/99194983/159202457-d41b023d-fecc-4d8c-9001-6b40c5b3ecfa.png)
3. Invalid data \
![invalid](https://user-images.githubusercontent.com/99194983/159202476-ffc6ac1d-3ad8-449a-ac02-4b2583c75427.png)
4. Update data \
![Update](https://user-images.githubusercontent.com/99194983/159202463-a7649584-6dd5-462f-873b-58e384a3eb15.png)
5. Delete data \
![Delete](https://user-images.githubusercontent.com/99194983/159202485-a1704735-38ad-4c8f-9866-940e654bb142.png)
