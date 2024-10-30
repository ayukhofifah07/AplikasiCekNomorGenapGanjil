# AplikasiCekNomorGenapGanjil

## Identitas
Nama: Ayu Atut Khofifah

NPM: 2210010553

## Penjelasan Program

1. **Deskripsi Program**:
   - Aplikasi memiliki GUI yang terdiri dari JTextField sebagai input angka dan tombol "Cek". Pengguna memasukkan angka dalam JTextField dan menekan tombol untuk melihat hasilnya.
   - Saat tombol ditekan, program akan melakukan validasi pada input pengguna. Jika input valid (berupa angka), program akan menampilkan hasil di JLabel. Jika input tidak valid, pesan error akan ditampilkan melalui JOptionPane.

2. **Komponen GUI**:
   - Aplikasi ini menggunakan beberapa komponen GUI Java seperti JFrame, JPanel, JLabel, JTextField, dan JButton untuk tampilan antarmuka dan interaksi dengan pengguna.

3. **Logika Program**:
   - Program menggunakan struktur kondisional (if-else) untuk menentukan apakah angka yang dimasukkan adalah genap atau ganjil.
   - Program juga memvalidasi input untuk memastikan hanya angka yang dapat diproses. Jika input bukan angka, pengguna akan diberi pesan error.

4. **Events**:
   - ActionListener digunakan pada tombol "Cek" untuk memproses angka yang dimasukkan saat tombol ditekan.
   - KeyAdapter digunakan pada JTextField untuk membatasi input hanya berupa angka, sehingga pengguna tidak dapat memasukkan karakter non-numerik.

5. **Variasi Fitur**:
   - Program memiliki tambahan fitur untuk memeriksa apakah angka tersebut merupakan bilangan prima.
   - Menggunakan JOptionPane untuk menampilkan pesan hasil dan pesan error ketika terjadi kesalahan input.
   - Implementasi FocusListener pada JTextField untuk membersihkan input secara otomatis setiap kali JTextField mendapatkan fokus, sehingga pengguna dapat memasukkan angka baru dengan mudah.

## Keunggulan Program 

1. **Tampilan Sederhana dan Gampang Dipakai**:
   - Antarmuka program ini simpel banget, jadi nggak bikin bingung pengguna. Cuma ada satu kolom buat input angka dan satu tombol buat cek. Jadi, siapapun bisa langsung pakai tanpa perlu mikir lama.

2. **Validasi Input Otomatis**:
   - Program ini otomatis ngecek biar yang masuk cuma angka doang. Jadi kalau ada yang coba masukin huruf atau karakter lain, bakal langsung ditolak. Ini bikin program lebih aman dan mencegah error yang nggak perlu.

3. **Pesan Error yang Jelas**:
   - Kalau ada kesalahan input, program langsung kasih tahu lewat pop-up pesan error. Jadi pengguna langsung ngerti apa yang salah dan bisa benerin inputnya.

4. **Ada Fitur Cek Bilangan Prima**:
   - Selain buat ngecek angka genap atau ganjil, program ini juga bisa cek apakah angkanya prima atau bukan. Ini bikin program lebih fungsional dan bermanfaat, karena ada info tambahan yang bisa didapat.

5. **Input Lebih Mudah Direset**:
   - Dengan adanya fitur FocusListener, kolom input otomatis kosong lagi pas kita klik. Jadi nggak perlu ribet hapus manual tiap kali mau masukin angka baru.

6. **Cepat dan Responsif**:
   - Program ini cukup ringan dan responsif karena logika programnya sederhana. Jadi hasilnya bisa langsung muncul begitu tombol ditekan tanpa delay.

7. **Cocok buat Belajar Pemrograman GUI**:
   - Program ini bagus banget buat yang lagi belajar Java, terutama pemrograman GUI. Komponennya lengkap, mulai dari JTextField, JButton, sampai listener macam ActionListener dan KeyAdapter, jadi bisa jadi latihan yang asyik buat belajar.

## Ini dia Screenshot Programnya

**1.** ![ss an AplikasiCekNomorGanjilGenap](https://github.com/user-attachments/assets/f5222125-1a3d-4594-b184-7c46447ba1d2)


**2.** ![ss an AplikasiCekNomorGanjilGenap2](https://github.com/user-attachments/assets/dc0657ce-9b93-49ae-8897-71c3750dd1d8)


**3.** ![ss an AplikasiCekNomorGanjilGenap3](https://github.com/user-attachments/assets/86bf3a0d-8c4b-41c5-a219-c5b0385a6e7c)


