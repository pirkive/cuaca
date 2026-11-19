# Cuaca BMKG

Aplikasi cuaca Android berbasis Flutter yang memakai data terbuka BMKG.
Tugas mata kuliah Pemrograman Komputer Bergerak.

## Fitur
- Cuaca otomatis berdasarkan GPS (kelurahan/desa, kode adm4)
- Pencarian lokasi dan favorit
- Info gempa terkini
- Mode offline (cache) dan tema dinamis

## Versi yang dipakai tim
- Flutter 3.50.x (channel stable)
- Dart 3.14.x (ikut bundel Flutter)
- Cek dengan: flutter --version

## Cara menjalankan
1. Pasang Flutter 3.50.x dan Android Studio (Android SDK)
2. git clone https://github.com/pirkive/cuaca.git
3. cd cuaca
4. git switch develop
5. flutter pub get
6. flutter run  (tambah --dart-define=USE_MOCK=true untuk data tiruan)

## Struktur singkat
lib/ (app, core, domain, data, services, presentation), assets/, docs/, test/, tool/

## Alur kontribusi
Branch dari develop, commit Conventional Commits, PR ke develop.
Detail ada di CONTRIBUTING.md.

## Sumber data
- Cuaca dan gempa: BMKG (Badan Meteorologi, Klimatologi, dan Geofisika) - https://data.bmkg.go.id/
- Kode wilayah: Kemendagri, lewat repositori cahyadsn/wilayah (lisensi dan keakuratan dicek di Tahap 0, hasilnya dicatat di docs/api-notes.md)
- Aplikasi ini bukan aplikasi resmi BMKG.

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