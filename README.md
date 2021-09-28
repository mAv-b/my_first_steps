Questão 1 : 

https://github.com/mAv-b/my_first_steps

Questão 2 :

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT
$ git init
Initialized empty Git repository in C:/Users/Mark/Documents/Directorys_Git/my_first_steps_GIT/.git/

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git config user.name "Mark"

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git config user.email "marcosrafaelp.camargo@gmail.com"

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git remote add origin git@github.com:mAv-b/my_first_steps.git

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$

Questão 3 :

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ cat >> ola_mundo.txt
298/09/2021


Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git add ola_mundo.txt
warning: LF will be replaced by CRLF in ola_mundo.txt.
The file will have its original line endings in your working directory

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git commit -m "exercise 3"
[master (root-commit) 94b1171] exercise 3
 1 file changed, 1 insertion(+)
 create mode 100644 ola_mundo.txt

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 232 bytes | 29.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:mAv-b/my_first_steps.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$

Questão 4


Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ touch .gitignore

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ echo serei_ignorado.txt >> .gitignore

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git add .gitignore
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git commit -m "exercise 4 .gitignore"
[master e3ba182] exercise 4 .gitignore
 1 file changed, 1 insertion(+)
 create mode 100644 .gitignore

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ echo sumiu >> serei_ignorado.txt


Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$ git add serei_ignorado.txt
The following paths are ignored by one of your .gitignore files:
serei_ignorado.txt
hint: Use -f if you really want to add them.
hint: Turn this message off by running
hint: "git config advice.addIgnoredFile false"

Mark@LAPTOP-0424DBFI MINGW64 ~/Documents/Directorys_Git/my_first_steps_GIT (master)
$

