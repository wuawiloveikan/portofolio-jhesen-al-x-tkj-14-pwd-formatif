# Panduan Git, GitHub, dan Pengumpulan

## Identitas Git
Jalankan di terminal VS Code:
```bash
git config --global user.name "wuawiloveikan"
git config --global user.email "EMAIL_GITHUB_YANG_KAMU_PILIH"
```
Email GitHub dan email kontak sekolah adalah dua hal berbeda. Email sekolah yang ditampilkan di website adalah `jhesen.002@ski.sch.id`. Untuk commit, gunakan email yang terverifikasi di GitHub atau alamat noreply yang ditampilkan oleh GitHub.

## Hubungkan repository
```bash
git init
git branch -M main
git remote add origin https://github.com/wuawiloveikan/portofolio-jhesen-al-x-tkj-14-pwd-formatif.git
git remote -v
```
Jika `origin` sudah ada, gunakan `git remote set-url origin URL_REPOSITORY`.

## Commit pertama
Commit pertama harus `first commit`. Karena semua halaman sudah tersedia dalam folder ini, jika ingin mempertahankan satu commit per tugas dari awal, buat dahulu salinan/branch persiapan atau lakukan commit secara bertahap saat mengerjakan. Jangan membuat commit palsu yang seolah-olah dikerjakan pada waktu berbeda.

## Pesan commit tugas sesuai lembar
1.1 `feat: add profile page with inline styles`
1.2 `feat: add button set with hover effect`
1.3 `feat: add about section with google font and background`
2.1 `feat: add project card with box model spacing`
2.2 `feat: add card badge and back to top button`
2.3 `feat: add contact form with focus style`
3.1 `feat: add navbar component using flexbox`
3.2 `feat: add project gallery with css grid`
3.3 `feat: add sidebar layout`
4.1 `style: add smooth transition to links and buttons`
4.2 `feat: add animated hero section`
4.3 `chore: add index page with links to all pages`

## Push
```bash
git push -u origin main
```

## Pemeriksaan sebelum dikumpulkan
- Pastikan repository Public.
- Buka semua 11 link dari halaman index.
- Pastikan semua halaman memiliki tautan kembali ke beranda.
- Ambil screenshot browser untuk nomor 1.1 sampai 4.3.
- Isi identitas, URL repository, dan refleksi di dokumen Word.
