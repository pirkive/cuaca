# Cuaca BMKG 
Aplikasi cuaca Android berbasis Flutter yang memakai data terbuka BMKG. Tugas mata kuliah Pemrograman Komputer Bergerak. 
## Fitur 
- Cuaca otomatis berdasarkan GPS (kelurahan/desa, kode adm4) 
- Pencarian lokasi dan favorit 
- Info gempa terkini 
- Mode offline (cache) dan tema dinamis 
## Cara menjalankan 
1. Pasang Flutter (versi: ISI_VERSI_TIM) dan Android SDK 
2. git clone https://github.com/pirkive/cuaca.git 
3. git switch develop 
4. flutter pub get 
5. flutter run (tambah --dart-define=USE_MOCK=true untuk data tiruan) 
## Struktur singkat 
lib/ (app, core, domain, data, services, presentation), assets/, docs/, test/, tool/ 
## Alur kontribusi 
1. Buat branch dari develop, contoh: feature/dashboard-header 
2. Commit dengan pesan yang jelas 
3. Buka Pull Request ke develop, minta 1 teman meninjau 
4. Jangan push langsung ke develop atau main 
## Sumber data 
Sumber data: BMKG (Badan Meteorologi, Klimatologi, dan Geofisika) - https://data.bmkg.go.id/ 
Page 17 of 26
Dokumen Perencanaan Teknis (Versi Final): Aplikasi Cuaca Mobile BMKG 
Aplikasi ini bukan aplikasi resmi BMKG. Data wilayah: ISI_SUMBER_DAN_LISENSI. 

## Tim Cuaca
| Peran | Nama |
|---|---|
| UI/UX Designer | |
| UI Slicing 1 (Splash, Izin, Dashboard) | |
| UI Slicing 2 (Navigasi, Cari, Gempa, Pengaturan) | |
| GPS dan Mapping adm4 | |
| API dan Networking | |
| Database dan State | |
| QA dan Git Manager | |