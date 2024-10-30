# Laporan Remote Linux Server 
- Nama : Alrin Melanie Putri
- NIM : 09011282328085
- Kelas : SK3A
- Mata Kuliah : Sistem Operasi dan Praktikum Sistem Operasi
- Dosen Pengampu : Adi Hermansyah, S.Kom., M.T.
# Instalasi 
Unduh file ISO Ubuntu Server dari situs resmi Ubuntu.
![Screenshot (122)](https://github.com/user-attachments/assets/8313388e-c30e-43f9-a3eb-64fca5fcc923)
# 1. Konfigurasi
![Screenshot 2024-10-30 201230](https://github.com/user-attachments/assets/735cfa78-fd2f-4f12-bae7-917cb42e2437)
# 2. Profil konfigurasi server
Ini digunakan untuk layanan dan akses jarak jauh menggunakan SSH
![Screenshot 2024-10-30 201835](https://github.com/user-attachments/assets/2d2c49c9-3502-45f2-b0f6-0c4d5eab4615)
# Persiapan SSH
sudo apt install openssh-server
![Screenshot 2024-10-30 212052](https://github.com/user-attachments/assets/67c58fbf-3821-4871-8c6c-63077115dadf)
# 1. Cek status SSH
![Screenshot 2024-10-30 212512](https://github.com/user-attachments/assets/a92c74e7-0f90-4e8c-8727-272d838da230)
# 2. Ubah port 22 jadi 40
![Screenshot 2024-10-30 213200](https://github.com/user-attachments/assets/29e91271-b43f-4929-9777-2c3a7f216db3)
# 3. Restart SSH
![Screenshot 2024-10-30 215144](https://github.com/user-attachments/assets/0287fd46-9c1a-4d40-a2ed-b30dc4d8d961)
# Remote
ssh username@server_ip -p 40
![Screenshot 2024-10-30 220558](https://github.com/user-attachments/assets/a313db55-e6f2-4781-8821-ad0d1293060e)
# Remote sesudah ubah port
![Screenshot 2024-10-30 220659](https://github.com/user-attachments/assets/1bd13ab8-ec26-499a-b732-8062f0b08fb6)


