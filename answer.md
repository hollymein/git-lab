Answer 1:
git version 2.26.2.windows.1

Answer 2: 
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl                            ts/ca-bundle.crt        
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false                                rams\Microsoft VS Code\C
credential.helper=manager
core.editor="C:\Users\Holly Mein\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
user.name=hollymein                                lp
user.email=hm917618@ohio.edu

Answer 3:
It opens up a new window in my browser titled, "git-add(1) Manual Page". This is a help page. 

Answer 4:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)      
        README.md
        answer.md

nothing added to commit but untracked files present (use "git add" to 
track)

Answer 5:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)      
        answer.md

Answer 6:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answer.md

Answer 7:
On branch master
nothing to commit, working tree clean

Answer 8: 
commit e916566f019e66c28083cc236dcb8e3395f1fac3 (HEAD -> master, origin/master)
Author: hollymein <hm917618@ohio.edu>
Date:   Wed May 13 13:54:07 2020 -0700

    Initial COMMIT

commit cb414becc3c0b5c10fc0646ece89bce345acfd59
Author: hollymein <65195100+hollymein@users.noreply.github.com>       
Date:   Wed May 13 12:26:17 2020 -0700

    Updating README.md on github webpage

commit c60c0ebda08386f6a6aaa578694885eef6601b21
Author: hollymein <hm917618@ohio.edu>
Date:   Wed May 13 12:04:08 2020 -0700

    Initial commit

Answer 9:
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Answer 10:
No my changes were not reflected in my local directory

Answer 11:
To https://github.com/hollymein/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/hollymein/git-lab.git'
hint: Updates were rejected because the remote contains work that you 
do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12:
Using git pull did update my local repository and gave me this output:

remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 726 bytes | 90.00 KiB/s, done.
From https://github.com/hollymein/git-lab
   cd81037..e115b1e  master     -> origin/master
Updating cd81037..e115b1e
Fast-forward
 README.md | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

 Answer 13:
When I type ls:

    Directory: C:\Users\Holly Mein\Desktop\CS 2400\git-lab-2


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        5/13/2020   3:33 PM            302 .gitignore
-a----        5/13/2020   3:33 PM             11 README.md




