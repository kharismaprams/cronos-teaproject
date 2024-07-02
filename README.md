# cronos-teaproject
This project created for Tea.xyz based on CRO Token MultiSender - Cronos project created by @kharismaprams

Untuk mengubah proyek dari repo GitHub yang ada menjadi paket yang dapat terbaca di website seperti https://app.tea.xyz/ dengan banyak dependency dan dependent, Anda dapat mengikuti langkah-langkah ini. Anda tidak perlu membuat proyek baru, hanya perlu melanjutkan dari repo yang ada.

Daftar di Gitpod dan Buat Workspace:

Daftar di Gitpod dan ambil trial jika belum punya akun.
Login ke GitHub dan buat repository baru.
Salin link git repository baru tersebut.
Login ke Gitpod, buat workspace baru dan masukkan link git repository baru.
Clone dan Setup Proyek di Gitpod:

Clone proyek Anda ke Gitpod menggunakan link repository baru.
sh
Salin kode
git clone https://github.com/kharismaprams/TOKEN-MULTISENDER-USING-JS
cd TOKEN-MULTISENDER-USING-JS
Install Dependencies dan Setup Proyek:

Pastikan semua dependency yang diperlukan sudah terinstal. Buat atau perbarui file package.json jika perlu.
sh
Salin kode
npm install
Tambahkan Konfigurasi untuk TEA:

Pastikan file package.json Anda memiliki informasi yang benar untuk name, version, description, dan repository.
json
Salin kode
{
  "name": "token-multisender",
  "version": "1.0.0",
  "description": "A tool to send tokens to multiple addresses",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/kharismaprams/TOKEN-MULTISENDER-USING-JS"
  },
  "author": "kharismaprams",
  "license": "MIT",
  "dependencies": {
    // tambahkan dependency yang diperlukan di sini
  }
}
Publish ke NPM:

Login ke npmjs.com dan buat akun jika belum punya.
Linked GitHub akun Anda dengan npmjs.com.
Kembali ke Gitpod, login ke npm di terminal:
sh
Salin kode
npm login
Publikasikan paket Anda:
sh
Salin kode
npm publish
Cek di TEA:

Pastikan paket Anda terpublikasi dengan benar di npmjs.com.
Masukkan URL npm paket Anda di TEA untuk mengecek skor dan dependencies.
Berikut adalah langkah-langkah lebih rinci untuk memastikan semua proses berjalan dengan baik:

Step 1: Clone Repository
Masuk ke workspace Gitpod dan clone repository Anda.

sh
Salin kode
git clone https://github.com/username/TOKEN-MULTISENDER-USING-JS
cd TOKEN-MULTISENDER-USING-JS
Step 2: Perbarui package.json
Perbarui file package.json untuk menambahkan informasi yang diperlukan:

json
Salin kode
{
  "name": "token-multisender",
  "version": "1.0.0",
  "description": "A tool to send tokens to multiple addresses",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/username/TOKEN-MULTISENDER-USING-JS"
  },
  "author": "kharismaprams",
  "license": "MIT",
  "dependencies": {
    "web3": "^1.0.0",  // Tambahkan dependency yang diperlukan
    // Tambahkan dependency lainnya jika perlu
  }
}
Step 3: Login dan Publish ke NPM
Login ke npm dan publish paket Anda:

sh
Salin kode
npm login
npm publish
Step 4: Verifikasi di npmjs.com
Pastikan paket Anda muncul di profil npmjs.com Anda di bawah tab 'packages'.

Step 5: Tambahkan ke TEA
Kunjungi TEA, dan tambahkan URL npm paket Anda untuk mengecek skor dan dependencies.

Dengan mengikuti langkah-langkah di atas, Anda dapat membuat proyek Anda menjadi paket yang bisa terbaca di TEA dan memiliki dependency serta dependent yang banyak.
