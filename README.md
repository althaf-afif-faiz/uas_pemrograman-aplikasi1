# uas_pemrograman-aplikasi1

# Nama : Althaf Afif Faiz
# NIM : 312410404
# Kelas : TI.24.A.3

# ☕ KoffNet - Android Coffee Shop App

**KoffNet** adalah aplikasi pemesanan kopi berbasis Android yang dirancang dengan antarmuka modern, interaktif, dan ramah pengguna.  
Aplikasi ini dikembangkan menggunakan **Java** dan **XML** di Android Studio.

## 📱 Fitur Unggulan
Aplikasi ini memiliki beberapa fitur utama yang telah dikembangkan secara bertahap:

### 1. Interactive Splash Screen
- Animasi logo dan teks sambutan yang halus.
- **Audio Integration:** Memutar suara startup (*startup sound*) saat aplikasi dibuka untuk pengalaman yang imersif.
- Transisi otomatis ke halaman utama.

### 2. Main Dashboard (Menu)
- Tampilan **Grid Layout** yang rapi menampilkan daftar menu kopi.
- Pilihan menu: Americano, Caramel Macchiato, Matcha Latte, Caffe Latte, Espresso, dan Hazelnut Latte.
- **Haptic/Audio Feedback:** Efek suara "Klik" setiap kali pengguna memilih menu atau menekan tombol, memberikan respons nyata.

### 3. User Profile Management (Local Storage)
- **Persistent Data:** Menyimpan data pengguna (Nama, Email, No HP, Alamat) menggunakan `SharedPreferences`. Data tidak hilang meskipun aplikasi ditutup.
- **Edit Profile:** Pengguna dapat mengedit informasi pribadi secara langsung.
- **Photo Profile:** Fitur untuk mengganti foto profil dari galeri HP dengan penanganan izin (*permission handling*) yang aman untuk mencegah *crash*.

## 🛠️ Teknologi & Tools
- **Bahasa:** Java (Native Android Development)
- **UI/Layout:** XML (ConstraintLayout, RelativeLayout, CardView, GridLayout)
- **IDE:** Android Studio Ladybug / Meerkat
- **Storage:** SharedPreferences (Untuk data sesi pengguna yang ringan)
- **Media:** MediaPlayer API (Untuk manajemen efek suara)

## 🚀 Development Journey (Proses Pengembangan)
Proyek ini dibangun melalui beberapa tahap penyempurnaan:
1.  **Inisialisasi UI:** Membangun layout dasar menggunakan XML dan CardView.
2.  **Logika Java:** Menghubungkan tampilan dengan logika pemrograman di `MainActivity`.
3.  **Handling Error:**
    - Memperbaiki masalah *crash* pada saat pengambilan foto profil dengan memperbarui `AndroidManifest` dan `Permissions`.
    - Menyelesaikan konflik resource (`Duplicate Resources`) pada file `strings.xml`.
    - Memastikan kompatibilitas pada Emulator API 36 (Android 15).
4.  **Polishing:** Menambahkan folder `raw` untuk aset suara dan memperbaiki bug layar hitam (*black screen*) pada emulator.

## 📸 Screenshots

### Splash Screen Aplikasi :
<img width="355" height="778" alt="image" src="https://github.com/user-attachments/assets/8da05ea2-8d0e-4122-8727-259e61cf582a" />

*(Tempatkan screenshot aplikasi Anda di sini nanti setelah di-upload)*

## 👤 Author
Dikembangkan oleh **Afif** sebagai bagian dari proyek pengembangan aplikasi Android.

---
*Dibuat dengan ❤️ dan Segelas Kopi.*
