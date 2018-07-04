# A. Make changes

```$ git checkout -b feature/readmePrepare
Switched to a new branch 'feature/readmePrepare'

$ git branch -va
  develop                c32bc54 Initial commit
* feature/readmePrepare  c32bc54 Initial commit
  master                 c32bc54 Initial commit
  remotes/origin/HEAD    -> origin/master
  remotes/origin/beta    c32bc54 Initial commit
  remotes/origin/develop c32bc54 Initial commit
  remotes/origin/master  c32bc54 Initial commit

$ git status
On branch feature/readmePrepare
nothing to commit, working tree clean

$ pwd
/Users/konstantinos/Development/iOS-dev/iOS-Review-2015/Swift/testSwift
$ mkdir source
$ subl  README.md 

$ git status
On branch feature/readmePrepare
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

  modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

  source/

no changes added to commit (use "git add" and/or "git commit -a")

$ git add source/instructions.md 

$ git status
On branch feature/readmePrepare
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

  new file:   source/instructions.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

  modified:   README.md


$ git commit -m "Add readme details and instructions template"
[feature/readmePrepare 266fa1c] Add readme details and instructions template
 1 file changed, 16 insertions(+)
 create mode 100644 source/instructions.md

$ git status
On branch feature/readmePrepare
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

  modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")


$ git commit -a -m "Add readme details and instructions template"
[feature/readmePrepare af0bbf2] Add readme details and instructions template
 1 file changed, 59 insertions(+), 1 deletion(-)
 rewrite README.md (100%)

$ git status
On branch feature/readmePrepare
nothing to commit, working tree clean```


# B. Submit changes

```$ git push origin feature/readmePrepare
Username for 'https://github.com': pirmavk
Password for 'https://pirmavk@github.com': 
Counting objects: 7, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 1.56 KiB | 532.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0)
To https://github.com/pirmavk/testSwift.git
 * [new branch]      feature/readmePrepare -> feature/readmePrepare```

# C. Next steps

## create Pull request to merge from feature/readmePrepare into develop
## merge from feature/readmePrepare into develop
