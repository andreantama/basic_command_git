# BASIC COMMAND GIT
some basic command how to use git 
1. git config --global user.name "Andreantama"
2. git config --global user.email "tama@gmail.com"
3. git init (untuk memonitor semua yang ada didalam folder)
4. git add namafile.html 
5. git status
6. git commit --message "Apa yang telah dilakukan di file namafile.html dijelaskan disini"
7. git log ("Melihat history file yang telah di commit")
8. git diff (melihat semua perubahan pada suatu file/folder)
9. git show 'nomor commit' (melihat detail pada file perubahannya)
10. git reset 'nomor commit'
11. git config --list (melihat semua list settings)

BRANCH(cabang)
1. git branch (melihat cabang) 
2. git branch nama-cabang (membuat cabang dari master)
3. git checkout nama-cabang(berubah fokus cabang dari master ke nama-cabang)
4. git merge nama-cabang (menggabungkan perubahan itu master)
5. git branch -d nama-cabang (delete cabang nama-cabang)

REMOTE
1. git remote add origin
2. git remote -v
3. git push -u origin nama-cabang (mengirim file ke github)
