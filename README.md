# MatkulUTDI-LookUp 📚

**MatkulUTDI-LookUp** adalah aplikasi desktop sederhana untuk lookup dan manajemen mata kuliah semester 2 di Universitas Teknologi Digital Indonesia (UTDI). Aplikasi ini memudahkan mahasiswa untuk mengakses e-learning dan folder materi kuliah dengan cepat melalui antarmuka pencarian yang responsif.

## 🎯 Fitur Utama

- ✅ **Live Search** - Pencarian real-time untuk mata kuliah
- ✅ **Akses E-Learning** - Link langsung ke portal e-learning UTDI
- ✅ **Akses Folder Lokal** - Buka folder materi kuliah dari Windows Explorer
- ✅ **Interface yang Responsif** - Grid layout otomatis dengan card layout yang rapi
- ✅ **Keyboard Shortcut** - Tekan `CTRL + Q` untuk menutup aplikasi
- ✅ **Auto-focus Search** - Mulai mengetik langsung tanpa klik search box

## 🖥️ Teknologi

- **HTA (HTML Application)** - Teknologi Windows untuk desktop application
- **HTML5** - Struktur markup
- **CSS3** - Styling dan grid layout responsif
- **JavaScript Vanilla** - Logika pencarian dan interaksi
- **ActiveXObject** - Integrasi dengan Windows Shell (membuka browser & folder)

## 📋 Mata Kuliah yang Tersedia

Aplikasi ini mencakup 10+ mata kuliah semester 2:

1. BAHASA INGGRIS
2. JARINGAN NIRKABEL
3. MATEMATIKA KOMPUTASI
4. PANCASILA
5. PEMROGRAMAN SISI FRONT-END
6. SISTEM BASIS DATA
7. STATISTIKA
8. STRUKTUR DATA
9. PRAKTIKUM STRUKTUR DATA
10. PRAKTIKUM STATISTIKA
11. PRAKTIKUM PEMROGRAMAN FRONT-END

## 📸 Preview Aplikasi

### Tampilan Awal
![Preview 1](https://drive.google.com/uc?export=view&id=1QUQ3h_zM0QgsfSlFEu9dIPtlJVPHMec-)

### Tampilan dengan Live Search
![Preview 2](https://drive.google.com/uc?export=view&id=1HTaYV2qJ5Zz8YRiTjySYOkdvJStUlX6K)

## 🚀 Cara Menggunakan

### 1. Download Repository
```bash
git clone https://github.com/christianxavierVibecode/MatkulUTDI-LookUp.git
cd MatkulUTDI-LookUp
```

### 2. Jalankan Aplikasi
- **Double-click** file `elearning.hta`
- Aplikasi akan terbuka sebagai desktop application

### 3. Menggunakan Fitur
- **Cari Mata Kuliah** - Ketik nama mata kuliah di search box (pencarian real-time)
- **Buka E-Learning** - Klik tombol "Buka E-Learning" untuk membuka portal
- **Buka Folder** - Klik tombol "Buka Folder" untuk membuka folder materi lokal
- **Keluar** - Tekan `CTRL + Q` atau klik tombol close

## ⚙️ Kustomisasi

Untuk menambahkan mata kuliah baru, edit bagian data array dalam file `elearning.hta`:

```javascript
var data = [  
  {
    "url": "https://elearning.utdi.ac.id/course/view.php?id=XXXX",
    "title": "NAMA MATA KULIAH",
    "localpath": "C:\\CostumFiles\\KULIAH\\Semester 2\\FOLDER_MATERI"
  },
  // Tambahkan data mata kuliah lainnya di sini
];
```

## 📝 Catatan

- Aplikasi ini adalah **prototype** yang dikembangkan menggunakan teknologi HTA (HTML Application).
- Path folder lokal dapat disesuaikan dengan struktur folder Anda sendiri.
- Pastikan folder yang ditunjuk di `localpath` sudah ada di komputer Anda.

## 🔮 Rencana Pengembangan

Aplikasi ini akan dikembangkan lebih lanjut dengan teknologi yang lebih modern:

- 🚀 **Electron** - Framework desktop application yang lebih powerful
- 💻 **React/Vue.js** - UI framework yang lebih flexible
- 🗄️ **Database Integration** - Penyimpanan data yang lebih scalable
- 🎨 **Modern UI/UX** - Desain yang lebih menarik dan user-friendly

Untuk saat ini, aplikasi ini sudah cukup untuk memenuhi kebutuhan manajemen mata kuliah harian.

## 📂 Struktur File

```
MatkulUTDI-LookUp/
├── elearning.hta      # File aplikasi utama
├── icon.ico           # Icon aplikasi (16x16)
├── appLogo.ico        # Logo aplikasi (256x256)
├── icon.png           # PNG icon
└── README.md          # File dokumentasi (ini)
```

## 👨‍💻 Author

**christianxavierVibecode**

## 📄 Lisensi

Proyek ini tersedia untuk penggunaan personal dan pengembangan lebih lanjut.

---

**Dibuat dengan ❤️ untuk memudahkan perkuliahan di UTDI**
