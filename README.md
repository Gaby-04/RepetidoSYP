
REPOSITORIO https://github.com/Gaby-04/RepetidoSYP.git


$ git init

$ touch Respuestas.txt


$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git commit -m "Agregando archivo de respuestas"


san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git remote add origin https://github.com/Gaby-04/RepetidoSYP.git

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 236 bytes | 236.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Gaby-04/RepetidoSYP.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git commit -m "Agregando respuesta 1"
[master e8055a4] Agregando respuesta 1
 1 file changed, 13 insertions(+)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git branch master2

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git checkout master2
Switched to branch 'master2'

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master2)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master2)
$ git commit -m "agregando respuesta 2"
[master2 85bf6b5] agregando respuesta 2
 1 file changed, 14 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master2)
$ git checkout master
Switched to branch 'master'
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 667 bytes | 667.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Gaby-04/RepetidoSYP.git
   204e7bd..e8055a4  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ git checkout master2
Switched to branch 'master2'

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master2)
$ git push -u origin master2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.02 KiB | 1.02 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master2' on GitHub by visiting:
remote:      https://github.com/Gaby-04/RepetidoSYP/pull/new/master2
remote:
To https://github.com/Gaby-04/RepetidoSYP.git
 * [new branch]      master2 -> master2
Branch 'master2' set up to track remote branch 'master2' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master2)
$ git branch master3

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master2)
$ git checkout master3
Switched to branch 'master3'

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master3)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master3)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master3)
$ git commit -m "Agregando respuesta 3"
[master3 022b3a6] Agregando respuesta 3
 1 file changed, 11 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master3)
$ git push -u origin master3
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 627 bytes | 627.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'master3' on GitHub by visiting:
remote:      https://github.com/Gaby-04/RepetidoSYP/pull/new/master3
remote:
To https://github.com/Gaby-04/RepetidoSYP.git
 * [new branch]      master3 -> master3
Branch 'master3' set up to track remote branch 'master3' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master3)
$ git branch master4

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master3)
$ git checkout master4
Switched to branch 'master4'
M       Respuestas.txt

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master4)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master4)
$ git commit -m "Agregando respuesta 4"
[master4 a4095f3] Agregando respuesta 4
 1 file changed, 15 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master4)
$ git push -u origin master4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 635 bytes | 635.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'master4' on GitHub by visiting:
remote:      https://github.com/Gaby-04/RepetidoSYP/pull/new/master4
remote:
To https://github.com/Gaby-04/RepetidoSYP.git
 * [new branch]      master4 -> master4
Branch 'master4' set up to track remote branch 'master4' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master4)
$ git branch master5

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master4)
$ git checkout master5
Switched to branch 'master5'

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master5)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master5)
$ git commit -m "Agregando respuesta 5"
[master5 8f4bb4b] Agregando respuesta 5
 1 file changed, 4 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master5)
$ git push -u origin master5
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 423 bytes | 423.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'master5' on GitHub by visiting:
remote:      https://github.com/Gaby-04/RepetidoSYP/pull/new/master5
remote:
To https://github.com/Gaby-04/RepetidoSYP.git
 * [new branch]      master5 -> master5
Branch 'master5' set up to track remote branch 'master5' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master5)
$ git branch master6

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master5)
$ git checkout master6
Switched to branch 'master6'

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master6)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master6)
$ git commit -m "Agregando respuesta 6"
[master6 d00ab3d] Agregando respuesta 6
 1 file changed, 7 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master6)
$ git push -u origin master6
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 474 bytes | 474.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'master6' on GitHub by visiting:
remote:      https://github.com/Gaby-04/RepetidoSYP/pull/new/master6
remote:
To https://github.com/Gaby-04/RepetidoSYP.git
 * [new branch]      master6 -> master6
Branch 'master6' set up to track remote branch 'master6' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master6)
$ git checkout master3
Switched to branch 'master3'
Your branch is up to date with 'origin/master3'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master3)
$ git merge master4
Updating 022b3a6..a4095f3
Fast-forward
 Respuestas.txt | 16 +++++++++++++++-
 1 file changed, 15 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master3)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$ touch README.md

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/REPETIDOSYP (master)
$
