# Praktikum5
**Soal :**
Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut:
- Progam meminta memasukkan data sebanyak-banyaknya(gunakanperulangan)
- Tampilkan pertanyaan untuk menambah data (y/t?), apabilajawabant (Tidak), maka program akan menampilkan daftar datanya. 
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md. 
- Commit dan push repository ke github.

**Flowchart :**
![Praktikum4 flowchart](https://github.com/user-attachments/assets/0b0dc552-d150-4569-95aa-67b07b4d7700)

**Jawaban :**
> Flowchart ini menggambarkan algoritma untuk memproses data mahasiswa dan menghitung nilai akhir mereka. Berikut penjelasan detailnya:

1. **Mulai:** Program dimulai.
2. **Inisialisasi Data = []:** Sebuah list kosong dibuat untuk menyimpan data mahasiswa.
3. **Input data Mahasiswa:** Program meminta input data mahasiswa yang meliputi nama, NIM, nilai tugas, nilai UTS, dan nilai UAS.
4. **Masukan Nama, Nim, Nilai Tugas, Nilai UTS, Nilai UAS:** Program menerima input data mahasiswa tersebut.
5. **Hitung Nilai Akhir:** Program menghitung nilai akhir dengan rumus: (Nilai Tugas x 30%) + (Nilai UTS x 35%) + (Nilai UAS x 35%).
6. **Tambahkan ke List data:** Data mahasiswa, termasuk nilai akhir, disimpan ke dalam list data.
7. **Tambah Data Lagi? (y/t):** Program bertanya kepada pengguna apakah mereka ingin memasukkan data mahasiswa lain.
8. **Jika ya (y):** Program kembali ke langkah 3 untuk memasukkan data mahasiswa baru.
9.** Jika tidak (t):** Program melanjutkan ke langkah selanjutnya.
10. **Cetak garis pembatas 50 karakter '-':** Program mencetak baris pemisah dengan 50 tanda "-" sebelum mencetak tabel data mahasiswa.
11. **Cetak Header Tabel:** Program mencetak header tabel yang berisi kolom: No, Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS, dan Nilai Akhir.
12. **Loop data dengan enumerate:** Program menggunakan loop untuk mengulangi setiap data mahasiswa dalam list data.
13. **Cetak Data:** Program mencetak data setiap mahasiswa dalam format tabel, termasuk: Nomor urut, Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS, dan Nilai Akhir.
14. **Cetak garis pembatas:** Program mencetak baris pemisah dengan 50 tanda "-" setelah mencetak data semua mahasiswa.
15. **Selesai:** Program berakhir.
