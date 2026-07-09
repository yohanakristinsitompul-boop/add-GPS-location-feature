# Profile Card App

## Deskripsi App

Profile Card App adalah aplikasi mobile berbasis React Native yang digunakan untuk membuat dan menyimpan informasi profil pengguna secara sederhana.
Aplikasi ini menyediakan fitur pengelolaan data profil seperti nama, NIM, program studi, kelas, serta foto profil. Selain itu, aplikasi memanfaatkan fitur native perangkat seperti kamera, galeri, GPS, penyimpanan lokal, dan integrasi Google Maps.
Data pengguna akan tersimpan otomatis menggunakan AsyncStorage sehingga informasi profil tetap tersedia ketika aplikasi dibuka kembali.

---

## Fitur Native yang Digunakan

Aplikasi ini menggunakan beberapa fitur native dari perangkat:

1. **Camera**
   - Mengambil foto secara langsung menggunakan kamera perangkat.

2. **Gallery / Media Library**
   - Memilih foto profil dari penyimpanan galeri perangkat.

3. **GPS / Location**
   - Mengambil koordinat lokasi pengguna secara real-time.

4. **Google Maps Integration**
   - Membuka lokasi pengguna melalui Google Maps berdasarkan koordinat GPS.

5. **AsyncStorage**
   - Menyimpan data profil secara lokal pada perangkat.

6. **Permission System**
   - Meminta izin akses kamera, galeri, dan lokasi dari pengguna.

---

# Daftar Fitur Aplikasi

## Level 2 Features

| No | Fitur | Status |
|---|---|---|
| 1 | Profile Card dengan data pengguna | ✅ Level 2 |
| 2 | Input Nama, NIM, Program Studi, dan Kelas | ✅ Level 2 |
| 3 | Mengambil foto menggunakan Camera | ✅ Level 2 |
| 4 | Memilih foto melalui Gallery | ✅ Level 2 |
| 5 | Mengambil lokasi menggunakan GPS | ✅ Level 2 |
| 6 | Menampilkan Latitude dan Longitude | ✅ Level 2 |
| 7 | Membuka lokasi melalui Google Maps | ✅ Level 2 |
| 8 | Auto Save menggunakan AsyncStorage | ✅ Level 2 |
| 9 | Load data otomatis ketika aplikasi dibuka | ✅ Level 2 |
| 10 | Reset data dengan dialog konfirmasi | ✅ Level 2 |
| 11 | Permission dialog untuk Camera, Gallery, dan Location | ✅ Level 2 |

---

## 1. Tampilan Awal Profile Card

(<img width="540" height="1412" alt="WhatsApp Image 2026-07-09 at 01 35 29 (2)" src="https://github.com/user-attachments/assets/91bae87b-6de5-4213-acc3-1d877769a82d" />)

## 2. Input Data Profile

(<img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 35 45 (1)" src="https://github.com/user-attachments/assets/cb05aaeb-a3e5-4ad4-98c9-20609904c094" />)

## 3. Fitur Camera

(<img width="540" height="1412" alt="WhatsApp Image 2026-07-09 at 01 36 02" src="https://github.com/user-attachments/assets/56ac498b-fcbf-44ca-bd9c-6ef5660a7298" />)

## 4. Fitur Gallery

(<img width="540" height="1412" alt="WhatsApp Image 2026-07-09 at 01 36 11" src="https://github.com/user-attachments/assets/f8ec452e-a759-42c3-ad0c-035720829b1c" />)

## 5. Fitur GPS

(<img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 36 27" src="https://github.com/user-attachments/assets/71980cb1-3365-47bf-ab0b-aa26d79378d3" />)

## 6. Fitur Google Maps

(<img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 36 44" src="https://github.com/user-attachments/assets/0d7699c3-81d8-4912-b4f7-93dfa5089ba3" />)

## 7. Reset Data

(<img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 37 55" src="https://github.com/user-attachments/assets/4c06cde4-21dc-4404-a996-21e9b7cb2e6c" />)

## 8. Dialog Izin Permission

(<img width="720" height="1600" alt="WhatsApp Image 2026-07-09 at 01 52 06" src="https://github.com/user-attachments/assets/fd72d792-d3ed-4e0f-863f-16453f91d1e2" />)

---

# Cara Menjalankan Aplikasi

## 1. Install
Jalankan Expo: npx expo start
Kemudian:
Scan QR Code menggunakan aplikasi Expo Go
Pastikan perangkat terhubung dengan jaringan yang sama
Izinkan permission Camera, Gallery, Location, dan sebainya
Screenshot hasil

## Expo Snack

Link Expo Snack:
https://snack.expo.dev/@yohana06/b102b6
