# Praktikum Git - 556158

Website sederhana untuk tugas praktikum Git & GitHub.

## Deskripsi Project

Project ini dibuat untuk memenuhi tugas praktikum mata kuliah
Praktikum Pemrograman Web 1. Website berisi halaman utama dengan navbar,
konten, dan footer.

## Cara Menjalankan

1. Clone repository:
   git clone https://github.com/celliaanastavio/praktikum-git-556158.git
2. Buka file index.html di browser

## Screenshot Website

![Website](Website.png)

## Git Log

![Git Log](gitlog.PNG)

## Branch Protection

![Branch Protection Setting](ProtectionSettings.PNG)
![Branch Protection Active](Protection.PNG)

## Dokumentasi Perintah Git

| Perintah                                        | Penjelasan                                        |
| ----------------------------------------------- | ------------------------------------------------- |
| `git clone <url>`                               | Menyalin repository dari GitHub ke komputer lokal |
| `git add .`                                     | Menambahkan semua perubahan ke staging area       |
| `git commit -m "pesan"`                         | Menyimpan perubahan dengan pesan deskriptif       |
| `git push origin main`                          | Mengunggah commit lokal ke GitHub                 |
| `git push origin nama-branch`                   | Mengunggah branch baru ke GitHub                  |
| `git pull origin main`                          | Mengunduh perubahan terbaru dari GitHub           |
| `git checkout -b nama`                          | Membuat branch baru sekaligus pindah ke sana      |
| `git checkout main`                             | Berpindah ke branch main                          |
| `git merge nama-branch`                         | Menggabungkan branch lain ke branch aktif         |
| `git log --oneline --graph`                     | Melihat riwayat commit dalam bentuk grafik        |
| `git rebase -i HEAD~3`                          | Interactive rebase untuk squash beberapa commit   |
| `git rebase --abort`                            | Membatalkan proses rebase yang sedang berjalan    |
| `git config --global core.editor "code --wait"` | Mengatur VS Code sebagai editor default Git       |
