Last login: Fri Dec  4 01:32:07 on ttys000
➜  ~  cd Sites/DWP
➜  DWP git:(master) ll
total 8
drwxr-xr-x@ 13 Christina  staff   442B Nov 30 23:41 css
drwxr-xr-x@ 28 Christina  staff   952B Nov 30 23:55 fonts
drwxr-xr-x   9 Christina  staff   306B Nov 30 23:28 img
-rw-r--r--@  1 Christina  staff   2.5K Dec  1 22:36 index.html
drwxr-xr-x@  5 Christina  staff   170B Nov 30 22:38 js
drwxr-xr-x@ 15 Christina  staff   510B Nov 23 09:28 less
-rw-r--r--   1 Christina  staff     0B Dec  3 02:10 readme.md
drwxr-xr-x@ 15 Christina  staff   510B Nov 23 09:28 scss
➜  DWP git:(master) git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
➜  DWP git:(master) git remote add PortfolioServer ssh://cdtdesign@104.131.52.233/var/repos/portfolio.git
➜  DWP git:(master) git push PortfolioServer master
cdtdesign@104.131.52.233's password: 
Counting objects: 87, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (86/86), done.
Writing objects: 100% (87/87), 2.68 MiB | 4.28 MiB/s, done.
Total 87 (delta 12), reused 0 (delta 0)
To ssh://cdtdesign@104.131.52.233/var/repos/portfolio.git
 * [new branch]      master -> master
➜  DWP git:(master) git branch
* master
➜  DWP git:(master) git branch RobustReadme
➜  DWP git:(master) git branch
  RobustReadme
* master
➜  DWP git:(master) git checkout RobustReadme
Switched to branch 'RobustReadme'
➜  DWP git:(RobustReadme)  
