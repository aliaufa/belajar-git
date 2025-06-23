# belajar-git

## Clone Using SSH

1. Harus ada Repositori Githubnya dulu. lalu copy URL SSH.
2. Buka terminal (cmd, powershell, bash) dengan working directory di folder yang mana kita mau menyimpan repository tersebut.
3. Dalam terminal gunakan command `git clone <url ssh>`
4. repositori akan terbentuk di folder tersebut.

Selanjutnya buka working directory di repositori-nya atau langsung buka vscode di repository

## Track and Commit File(s) Changes

kalau kerja dengan orang lain, jangan lupa lakukan `git pull` di awal
1. Cek status files dalam repositori dengan `git status`
2. Untuk track perubahan pada file(s) gunakan `git add <nama file>` untuk 1 file saja atau `git add .` untuk semua file
3. kalau cek `git status` lagi file akan berubah jadi tracked dan siap dilakukan commit.
4. Untuk menyimpan perubahan lakukan dengan `git commit -m "message commit"`
(kalau gajadi commit bisa `git reset --mixed` atau `git revert`)
5. Untuk Menyimpan perubahan ke repository remote lakukan `git push`