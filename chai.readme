git--> software
github-->software online host krne ka general service

repository-->folder status
git --version //git version 2.47.1.windows.1

pwd //present working directory

git config --global user.email "ankitakoley81@gmail.com"
PS D:\chai_django\one> git config --global user.name "Ankita koley"
PS D:\chai_django\one> git config --list

git status
git init -->repository bnn gya

FOR STAGING FILE-->git add .

"git rm --cached <file>..." to unstage 

git commit -m "first commit"-->repo


PS D:\chai_django\one> git log --oneline
4b36dc5 (HEAD -> main) second  commit
bcb8ac6 first commit


Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

PS D:\chai_django\one> git add .gitignore
PS D:\chai_django\one> git commit -m "add gitignore"
[main 06888e5] add gitignore
 3 files changed, 15 insertions(+), 2 deletions(-)
 create mode 100644 one/.gitignore
PS D:\chai_django\one> git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../images/

nothing added to commit but untracked files present (use "git add" to track)
PS D:\chai_django\one>

.gitkeep --> iss ko rakne se git empty file ka track nhi rakhta hai

commit object ---reference deta hai---Tree object ----- blob object

PS D:\chai_django> cd one
PS D:\chai_django\one> git branch
* main
PS D:\chai_django\one> git branch bug-fix
PS D:\chai_django\one> git branch
  bug-fix
* main
PS D:\chai_django\one> git switch bug-fix
M       chai.readme
Switched to branch 'bug-fix'
PS D:\chai_django\one> git add fixes.txt
PS D:\chai_django\one> git commit -m "add fix file"
[bug-fix f8b6cf9] add fix file
 1 file changed, 1 insertion(+)
 create mode 100644 one/fixes.txt
PS D:\chai_django\one> git status
On branch bug-fix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../chai.readme

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../images/

no changes added to commit (use "git add" and/or "git commit -a")
PS D:\chai_django\one> git log
commit f8b6cf99b4815f65ed54f3e486a80b6e89de58bb (HEAD -> bug-fix)
Author: Ankita koley <ankitakoley81@gmail.com>
Date:   Mon Feb 2 16:16:18 2026 +0530

    add fix file

commit 06888e5c7c2bcdadcd7da20bb446b974c735fd80 (main)    
Author: Ankita koley <ankitakoley81@gmail.com>
Date:   Mon Feb 2 15:20:20 2026 +0530

    add gitignore

commit 4b36dc5fde9ed58ee3c0eb9ae71a04ded89caff0
Author: Ankita koley <ankitakoley81@gmail.com>
Date:   Mon Feb 2 14:59:14 2026 +0530

    second  commit

:
commit f8b6cf99b4815f65ed54f3e486a80b6e89de58bb (HEAD -> bug-fix)
Author: Ankita koley <ankitakoley81@gmail.com>
Date:   Mon Feb 2 16:16:18 2026 +0530

    add fix file

commit 06888e5c7c2bcdadcd7da20bb446b974c735fd80 (main)    
Author: Ankita koley <ankitakoley81@gmail.com>
Date:   Mon Feb 2 15:20:20 2026 +0530

    add gitignore

commit 4b36dc5fde9ed58ee3c0eb9ae71a04ded89caff0
Author: Ankita koley <ankitakoley81@gmail.com>
Date:   Mon Feb 2 14:59:14 2026 +0530

    second  commit

commit bcb8ac6228bf919fb4206f8e886ac0771a463c73
Author: Ankita koley <ankitakoley81@gmail.com>
Date:   Mon Feb 2 14:56:42 2026 +0530

    first commit







PS D:\chai_django> git branch
* bug-fix
  main
PS D:\chai_django> git switch main
M       chai.readme
Switched to branch 'main'
PS D:\chai_django> git switch bug-fix
M       chai.readme
Switched to branch 'bug-fix'
PS D:\chai_django> git switch main   
M       chai.readme
Switched to branch 'main'
PS D:\chai_django> git switch -c dark-mode
Switched to a new branch 'dark-mode'
PS D:\chai_django> git checkout orange-mode
error: pathspec 'orange-mode' did not match any file(s) known to git
PS D:\chai_django> git branch orange-mode
PS D:\chai_django> git checkout orange-mode
M       chai.readme
Switched to branch 'orange-mode'
PS D:\chai_django> 

-----------------------------------------------------------------------------------

//PS D:\campaign-be> git clone https://github.com/Indus-Action-Initiatives/campaign-be.git .
>> 
Cloning into '.'...
remote: Enumerating objects: 9403, done.
remote: Counting objects: 100% (792/792), done.
remote: Compressing objects: 100% (208/208), done.
remote: Total 9403 (delta 677), reused 590 (delta 584), pack-reused 8611 (from 3)
Receiving objects: 100% (9403/9403), 2.57 MiB | 4.86 MiB/s, done.
Resolving deltas: 100% (6509/6509), done.
PS D:\campaign-be> git branch
* prod
PS D:\campaign-be> git pull
Already up to date.
PS D:\campaign-be> git status
On branch prod
Your branch is up to date with 'origin/prod'.

nothing to commit, working tree clean
PS D:\campaign-be> git checkout -b ankita-working
Switched to a new branch 'ankita-working'
PS D:\campaign-be> git branch
* ankita-working
  prod
PS D:\campaign-be> git status
Your branch is up to date with 'origin/prod'.

nothing to commit, working tree clean
PS D:\campaign-be> git checkout -b ankita-working
Switched to a new branch 'ankita-working'
PS D:\campaign-be> git branch
* ankita-working
  prod
PS D:\campaign-be> git status
* ankita-working
  prod
PS D:\campaign-be> git status
PS D:\campaign-be> git status
On branch ankita-working
nothing to commit, working tree clean
PS D:\campaign-be>











