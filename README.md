# Jamur Mr.Pj

Website company profile Jamur Mr.Pj. Website ini statis (HTML dan CSS saja), jadi tidak perlu install apa pun dan tidak ada proses build.

## Isi folder

- `index.html` : isi halaman
- `style.css` : tampilan
- `assets/` : logo, foto, dan video
- `vercel.json` : pengaturan Vercel

## Cara melihat di komputer

Klik dua kali `index.html`, atau jalankan `npx serve` di folder ini.

## Cara upload ke GitHub

Lewat situs:

1. Login ke github.com, klik **New repository**, beri nama, misalnya `jamur-mrpj`, lalu **Create repository**.
2. Klik **uploading an existing file**, tarik semua isi folder ini (termasuk folder `assets`), lalu klik **Commit changes**.

Total ukuran folder sekitar 18 MB. Setiap file di bawah batas 25 MB untuk upload lewat situs GitHub.

Lewat terminal:

```bash
git init
git add .
git commit -m "Website Jamur Mr.Pj"
git branch -M main
git remote add origin https://github.com/USERNAME/jamur-mrpj.git
git push -u origin main
```

Ganti `USERNAME` dengan nama akun GitHub kamu.

## Cara hosting di Vercel

1. Login ke vercel.com dengan akun GitHub.
2. Klik **Add New**, pilih **Project**, lalu **Import** repository `jamur-mrpj`.
3. Pada **Framework Preset** pilih **Other**. Kosongkan Build Command dan Output Directory.
4. Klik **Deploy**. Website langsung online di alamat `nama-proyek.vercel.app`.

Setiap kali kamu mengubah file di GitHub, Vercel otomatis memperbarui website.

Catatan: paket gratis Vercel (Hobby) dibatasi untuk penggunaan non-komersial. Untuk website usaha, cek syaratnya atau pakai paket Pro.

## Pakai domain sendiri

Di Vercel buka **Settings**, lalu **Domains**, tambahkan domain kamu dan ikuti petunjuk DNS.

## Mengubah isi

- Nomor WhatsApp: cari `6285263262056` dan `+62 852-6326-2056` di `index.html`.
- Alamat dan jam layanan: cari bagian `id="kontak"` dan `id="outlet"` di `index.html`.
- Teks tentang kami, produk, tahap budidaya, dan keunggulan: ada di `index.html`.
- Warna: ada di bagian `:root` di `style.css`.
- Foto dan video: ganti file di folder `assets` dengan nama yang sama.
