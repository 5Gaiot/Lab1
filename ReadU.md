C:\Local_Git\lab1>git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ReadU.md

nothing added to commit but untracked files present (use "git add" to track)

C:\Local_Git\lab1>git add ReadU.md

C:\Local_Git\lab1>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   ReadU.md


C:\Local_Git\lab1>git commit -m "add helloworld readU.md and readme.md"
[master 4d2c4bb] add helloworld readU.md and readme.md
 1 file changed, 1 insertion(+)
 create mode 100644 ReadU.md

C:\Local_Git\lab1>git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Local_Git\lab1>git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 290 bytes | 290.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/5Gaiot/Lab1
   0e3c581..4d2c4bb  master -> master