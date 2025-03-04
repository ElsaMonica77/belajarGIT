Daftar tugas / branch
  1. Tugas-git
  2. Tugas-html
  3. Tugas-css
  4. Tugas-js
  5. Tugas-midProject
  6. Tugas-php
  7. Tugas-finalProject
    
Daftar perintah GiT

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~
$ cd Documents

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents
$ git clone https://github.com/ElsaMonica77/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents
$ cd belajarGIT

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git 9c52fca] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 37e7dc9..9c52fca
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 324 bytes | 324.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ElsaMonica77/belajarGIT.git
   37e7dc9..9c52fca  main -> main

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-git.html

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html 35a3834] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating 9c52fca..35a3834
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ElsaMonica77/belajarGIT.git
   9c52fca..35a3834  main -> main

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css eb30d87] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating 35a3834..eb30d87
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 361 bytes | 361.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ElsaMonica77/belajarGIT.git
   35a3834..eb30d87  main -> main

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "menambahkan Tugas-js.txt"
[Tugas-js 8253027] menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating eb30d87..8253027
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 294 bytes | 294.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ElsaMonica77/belajarGIT.git
   eb30d87..8253027  main -> main

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject 2bab862] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating 8253027..2bab862
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 317 bytes | 317.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ElsaMonica77/belajarGIT.git
   8253027..2bab862  main -> main

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php 0a8a15a] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating 2bab862..0a8a15a
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 300 bytes | 300.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ElsaMonica77/belajarGIT.git
   2bab862..0a8a15a  main -> main

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject f0d858e] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalproject
Updating 0a8a15a..f0d858e
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

V  I  C  T  U  S@LAPTOP-NH5ILNTK MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 315 bytes | 315.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ElsaMonica77/belajarGIT.git
   0a8a15a..f0d858e  main -> main
