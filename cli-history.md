609  git init practice-repo
  610  cd practice-repo
  611  ls -al
  612  git status
  613  touch README.md
  614  ls
  615  git add README.md
  616  git commit -m "initial commit with README"
  617  git log --oneline
  618  touch file1.md file2.md file3.md file4.md file5.md file6.md
  619  ls
  620  git add *1*
  621  git commit -m "adding file 1"
  622  git add *2*
  623  git commit -m "adding file 2"
  624  git add *3*
  625  git commit -m "adding file 3"
  626  git add *4*
  627  git commit -m "adding file 4"
  628  git add *5*
  629  git commit -m "adding file 5"
  630  git add *6*
  631  git commit -m "adding file 6"
  632  ls -al
  633  git log --oneline
  634  git reset --soft HEAD~2
  635  git log --oneline
  636  ls
  637  git status
  638  git commit -m "readding file 5 and 6"
  639  git status
  640  git lol
  641  git reset HEAD~
  642  git lol
  643  git status
  644  git add file5.md
  645  git status
  646  git commit -m "file 5 again"
  647  git add *6*
  648  git commit -m "file 6 again"
  649  git lol
  650  git reset --hard 220293a
  651  git lol
  652  git status
  653  ls -al
  654  git reflog
  655  git reset --hard 92c31b5
  656  git lol
  657  git reset --hard 220293a
  658  git lol
  659  git cherry-pick 1dc1914
  660  ls -al
  661  git status
  662  git lol
  663  git checkout -b reabase-me
  664  git reflog
  665  git branch -m reabase-me rebase-me
  666  git cherry-pick ce51e81 92c31b5 f785a8b
  667  git checkout master
  668  git cherry-pick 263cc35 caf7a9b
  669  git lol
  670  git checkout rebase-me
  671  git rebase -i master
  672  git lol
  673  git checkout master
  674  git merge rebase-me
  675  git lol
