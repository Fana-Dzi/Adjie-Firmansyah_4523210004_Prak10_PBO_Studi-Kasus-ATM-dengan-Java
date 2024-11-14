# Sistem Simulasi ATM

Ini adalah program simulasi ATM berbasis konsol sederhana yang dibuat dengan bahasa Java. Program ini memungkinkan pengguna untuk melakukan operasi dasar ATM seperti cek saldo, penarikan, deposit, transfer, dan penggantian PIN. Sistem ini juga menerapkan persyaratan saldo minimal.

## Fitur

- **Autentikasi Pengguna**: Pengguna harus memasukkan nomor akun dan PIN untuk mengakses fitur ATM.
- **Cek Saldo**: Menampilkan saldo akun saat ini.
- **Penarikan**: Menarik dana dengan ketentuan saldo minimal Rp50.000.
- **Deposit**: Menyetor dana ke dalam akun.
- **Transfer**: Mentransfer dana ke akun lain.
- **Ubah PIN**: Mengganti PIN akun setelah verifikasi PIN lama.

## Struktur Proyek

- **`ATM.java`**: Kelas utama yang menginisialisasi akun, menangani autentikasi pengguna, dan menyediakan menu ATM.
- **`Account.java`**: Kelas model yang merepresentasikan akun bank dengan atribut seperti nomor akun, PIN, dan saldo.
- **`Transaction.java`**: Kelas dasar abstrak untuk transaksi, yang diperluas oleh jenis transaksi lainnya.
- **`Withdrawal.java`, `Deposit.java`, `Transfer.java`**: Kelas untuk jenis transaksi tertentu, masing-masing menerapkan logika transaksi unik.

## Prasyarat

- **Java Development Kit (JDK)** versi 8 atau lebih tinggi
- **Maven** atau **Gradle** (opsional, untuk pengelolaan proyek)

## Cara Menjalankan Proyek

1. **Clone repositori ini**:
   ```bash
   git clone https://github.com/username-anda/ATM-Simulation.git
