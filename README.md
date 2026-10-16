
# Pertemuan 07 Fungsi Python

Nama: Hana Karimah Ghoziyah
NIM: 2225250165
Kelas: 3B

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan
Jalankan program praktik melalui terminal VS Code dengan perintah:

python3 praktik/utilitas_matematika.py

Jika perintah python3 tidak dikenali, gunakan:

& C:\Users\kontr\.local\bin\python3.14.exe praktik/utilitas_matematika.py

## Struktur Fungsi

1. `luas_persegi_panjang(p, l)`
   - Parameter: `p` (panjang) dan `l` (lebar).
   - Return: hasil perkalian panjang dan lebar.

2. `luas_segitiga(a, t)`
   - Parameter: `a` (alas) dan `t` (tinggi).
   - Return: setengah dari hasil perkalian alas dan tinggi.

3. `jumlah_n(n)`
   - Parameter: `n` (batas bilangan).
   - Return: jumlah bilangan dari 1 sampai n.

4. `faktorial(n)`
   - Parameter: `n` (bilangan yang dihitung faktorialnya).
   - Return: hasil faktorial n.

5. `tampilkan_menu()`
   - Parameter: tidak ada.
   - Return: tidak mengembalikan nilai; fungsi menampilkan menu pilihan.

## Hasil Pengujian

| Menu | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| 1. Luas persegi panjang | p = 8, l = 5 | 40.0 | 40.0 | Berhasil |
| 2. Luas segitiga | a = 10, t = 6 | 30.0 | Belum diuji | Belum diuji |
| 3. Jumlah 1 sampai n | n = 5 | 15 | Belum diuji | Belum diuji |
| 4. Faktorial | n = 5 | 120 | Belum diuji | Belum diuji |

## Refleksi

Program menjadi lebih sederhana karena setiap perhitungan dipisahkan ke dalam fungsi masing-masing. Fungsi luas persegi panjang, luas segitiga, jumlah bilangan, dan faktorial dapat dipanggil sesuai kebutuhan tanpa menulis ulang seluruh proses perhitungannya.
