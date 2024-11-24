# PengelolaKontak
# Vina Ramadhanti Putri Pratiwi-2410010559-Latihan3AplikasiPengelolaKontak

Deskripsi Program:
• Aplikasi menyimpan informasi kontak seperti nama, nomor telepon, dan
kategori kontak ke dalam database SQLite.
• Pengguna dapat menambahkan, mengedit, menghapus kontak tersimpan.
• Kontak dapat dikelompokkan berdasarkan kategori yang dipilih dari
JComboBox, seperti keluarga, teman, atau kerja.

Komponen GUI: JFrame, JPanel, JLabel, JTextField, JButton, JList, JComboBox,
JTable, JScrollPane

Logika Program: database SQLite, fitur CRUD (Create, Read, Update, Delete)

Events:
• ActionListener untuk tombol Tambah, Edit, Hapus, dan Cari Kontak.
• ItemListener untuk JComboBox kategori kontak

Variasi:
• Menambahkan fitur pencarian kontak berdasarkan nama atau nomor
telepon, lalu tampilkan hasilnya di JTable
• Membuat validasi input untuk memastikan nomor telepon yang dimasukkan
hanya berisi angka dan memiliki panjang yang sesuai
• Menyediakan fitur untuk mengekspor daftar kontak ke file CSV dan
mengimpor kontak dari file CSV ke database.
